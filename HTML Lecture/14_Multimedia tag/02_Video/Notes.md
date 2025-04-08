## 📝 HTML `<video>` Tag
---

### 🎥 What is `<video>` tag?

- `<video>` tag is used to **add videos** on your webpage.
- It is a **self-closing container** (but works better with closing `</video>`).
- You can add `.mp4`, `.webm`, or `.ogg` formats.

---

### ⚙️ Common Attributes:

| Attribute | What it does |
|-----------|--------------|
| `src`     | Path of video file |
| `controls` | Shows play/pause buttons |
| `autoplay` | Video starts playing automatically |
| `muted`    | Video starts muted (required with autoplay) |
| `loop`     | Repeats video again and again |
| `width` / `height` | Set the video size |

---

### ✅ Example 1 – Simple Video with Controls
```html
<video src="video/movie.mp4" controls width="100%" height="500px"></video>
```
- User can control play, pause, volume, etc.

---

### ✅ Example 2 – Autoplay + Muted + Loop
```html
<video src="video/movie.mp4" autoplay muted loop width="100%" height="500px"></video>
```
- Good for background video or auto intro
- Works without user click

---

### 🔄 Optional: Using `<source>` tag
```html
<video controls width="100%" height="500px">
  <source src="video/movie.mp4" type="video/mp4">
  <source src="video/movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```
- Helps with browser compatibility
- Shows message if video tag is not supported

---

### 💡 Note:

- Always use `muted` with `autoplay`.
- `loop` makes the video play again and again without stopping.
- Use responsive width like `width="100%"` to fit any screen.
