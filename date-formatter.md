### Assignment 2: Date and Time Format Selector

**Description:**
Create a date and time formatting application using React with functional components, hooks (`useState`, `useEffect`), and the `date-fns` library. The application should allow users to input a date and time, select from different date formats, and display the formatted date and time string.

**Requirements:**
- Use functional components and hooks (`useState`, `useEffect`) for state management.
- Integrate the `date-fns` library for date manipulation and formatting.
- Display an input field for users to enter a date and time.
- Display a dropdown or radio buttons to allow users to select different date formats (e.g., "MM/dd/yyyy", "dd/MM/yyyy", "MMMM d, yyyy").
- Implement state to manage the selected date format, entered date and time, and the formatted date and time string.
- Use `useEffect` to update the displayed date and time string whenever the selected format or entered date and time change.
- Display the formatted date and time string prominently on the page.

**Basic Functionality:**
1. Display an input field for users to enter a date and time in a specific format (e.g., "yyyy-MM-dd HH:mm:ss").
2. Display a dropdown or radio buttons with different date format options.
3. Initialize the displayed date and time string with the formatted current date and time according to the default format.
4. Use `useEffect` to monitor changes in the selected format or entered date and time and update the displayed date and time string accordingly.

**Bonus:**
- Add input validation to ensure the entered date and time format is correct.
- Allow users to clear the entered date and time and reset to the current date and time.
- Implement localization to display dates and times in different languages or regions.
- Enhance the UI with CSS styles or a date picker component for selecting the date and time.
