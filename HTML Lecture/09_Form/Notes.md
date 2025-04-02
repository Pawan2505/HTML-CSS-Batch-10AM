# Student Form Notes
---

## Form Elements and Their Purposes

### 1. **Form Structure**
- `<form>`: Defines the start of the form.
- `<fieldset>`: Groups related form elements together.
- `<legend>`: Provides a title for the form section.

### 2. **Input Fields**

#### a) Name Input (Disabled)
- `<input type="text">`: Used for entering text.
- `required`: Ensures this field must be filled (though it's disabled in this case).
- `disabled`: Prevents user from entering data.

#### b) Email Input (Readonly)
- `<input type="email">`: Accepts only valid email formats.
- `readonly`: Prevents user modification.

#### c) Age Input
- `<input type="number">`: Restricts input to numeric values.

#### d) Date of Birth (DOB) Input
- `<input type="date">`: Provides a calendar for selecting a date.

#### e) Address Input
- `<textarea>`: Allows multiple lines of input.

#### f) Gender Selection
- `<input type="radio">`: Users can select only one option at a time.

#### g) Hobbies Selection
- `<input type="checkbox">`: Users can select multiple options.
- `checked`: Pre-selects the option (e.g., "Gaming").

#### h) File Upload
- `<input type="file">`: Enables file selection from device storage.

#### i) City Selection Dropdown
- `<select>`: Creates a dropdown list.
- `<option>`: Defines selectable choices.
- `selected`: Pre-selects the default option (e.g., "Kota").

#### j) Phone Number Input
- `<input type="tel">`: Optimized for phone number input.

#### k) Range Slider
- `<input type="range">`: Allows users to select a numerical value from a range.

#### l) Color Picker
- `<input type="color">`: Enables users to select a color.

#### m) Password Input
- `<input type="password">`: Hides user input for security purposes.

### 3. **Form Buttons**
- `<button type="submit">`: Submits form data.
- `<button type="reset">`: Clears all input fields.
- `<input type="submit" value="Save">`: Alternative way to submit the form.
- `<input type="reset" value="Reset">`: Alternative way to reset the form.

