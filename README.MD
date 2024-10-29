# Digital Clock Project Implementation

This project creates a real-time digital clock that displays the current time and date for the `Asia/Kolkata` time zone. The project uses HTML, Bootstrap for styling, and JavaScript for dynamic updates.

---

## Implementation Overview

### 1. Centered Container and Card Design
   - **Center Alignment**: The clock display is centered on the page using Bootstrap's `d-flex`, `justify-content-center`, and `align-items-center` classes. This ensures the clock remains centered both vertically and horizontally on any screen size.
   - **Card Styling**: The digital clock is displayed within a card element, which has a dark background, white text, a shadow effect, and rounded corners to make the display visually appealing and easy to read.

### 2. Font Styling and Color Accents
   - **Font Sizes**: Font sizes for the clock title, time, and date are increased for clear readability and emphasis.
   - **Color Accent**: The time zone label is given a contrasting color using a Bootstrap text color class, making the label visually distinct and emphasizing the time zone for context.

### 3. Real-Time JavaScript Updates
   - **Time and Date Retrieval**: JavaScript’s `Date` object is used to get the current time and date each second. The functions `toLocaleTimeString()` and `toLocaleDateString()` are applied to format the time and date according to local standards.
   - **Dynamic Updates**: A `setInterval()` function updates the time and date display every second, ensuring real-time updates without requiring a page refresh. The text content of specific HTML elements is updated by selecting them using `querySelector()`.

---

This setup provides a visually appealing, responsive, and user-friendly digital clock that continuously displays the current time and date in a clean, card-based layout.
