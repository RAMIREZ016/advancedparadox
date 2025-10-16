# Login Paradox

Login Paradox is a responsive and interactive login and registration portal built with **HTML**, **CSS**, and **JavaScript**. It features modern UI/UX design patterns, dual-theme support, and smooth card-flipping animations.

## Features

- **Login and Registration Forms**  
  - Separate, animated login and registration cards with smooth flipping transitions.  
  - Form validation for required fields including email, password, and captcha.

- **Dual Theme Backgrounds**  
  - Login view: dark background with light-colored elements.  
  - Registration view: light background with dark-colored elements.  
  - Automatic theme switching based on active form.

- **Quantum Neumorphism Styling**  
  - Modern neumorphic design for inputs and buttons.  
  - Subtle shadows, gradients, and depth for interactive feedback.

- **Interactive UI Components**  
  - Dust particle background with randomized motion for visual interest.  
  - Animated buttons with hover and click effects.  
  - Caps lock detection for password fields.  
  - Notification system for form submission feedback.

- **Responsive Layout**  
  - Mobile-first design that adapts to different screen sizes.  
  - Flexible container widths and heights for consistent layout across devices.

- **Accessibility and UX Enhancements**  
  - Auto-focus advancement between input fields on pressing Enter.  
  - Keyboard-friendly form navigation.

## Technical Details

- **Dust Particle Generator**  
  - Dynamically creates floating dust particles using JavaScript.  
  - Randomized size, position, animation delay, and duration.  
  - Adjusts color based on active theme (light for login, dark for signup).

- **Card Flipping Animation**  
  - Login and signup cards are rotated along the Y-axis to simulate 3D flipping.  
  - Smooth transition between login and registration forms using CSS `transform` and `transition`.  
  - Background theme switches simultaneously with card flip.

- **Form Submission Effects**  
  - Button text replaced with a spinner on submission.  
  - Disabled button state during processing.  
  - Notifications displayed after submission with auto-hide timer.

- **Caps Lock Detection**  
  - Real-time detection while typing password.  
  - Shows a warning message if Caps Lock is on.  
  - Automatically hides warning when focus is lost or Caps Lock is off.

- **Responsive and Flexible Layouts**  
  - Maximum and minimum width constraints using CSS `clamp()`.  
  - Card heights dynamically adjusted to ensure consistent layout.  
  - Uses flexbox for centering and spacing of elements.

- **Advanced Neumorphic Buttons and Inputs**  
  - Light and dark neumorphic designs for login and signup cards.  
  - Hover and active states with subtle depth and color changes.  
  - Smooth transitions and shadow animations for interactive feedback.

- **Notification System**  
  - Fixed notification box with dynamic message and type (success or error).  
  - CSS transitions for smooth entry and exit.  
  - Backdrop blur effect for modern visual style.

## File Structure

login-paradox/
├── index.html # Main login and registration page
├── README.md # Project documentation
├── .gitignore # Git ignore file
├── LICENSE # Existing license file
└── assets/ # Optional folder for images or scripts

bash
Copy code

## Setup and Deployment

1. Clone the repository:
   ```bash
   git clone https://github.com/singularitynode/advancedparadox.git
   cd advancedparadox
Open index.html in your preferred browser:

bash
Copy code
start index.html
(Optional) To deploy via GitHub Pages:

Go to the repository on GitHub.

Navigate to Settings > Pages.

Select main branch and folder / (root).

Save and wait a few minutes. Your site will be available at:

arduino
Copy code
https://singularitynode.github.io/advancedparadox/
Contribution
Contributions are welcome. Please submit issues or pull requests with clear descriptions of enhancements or bug fixes.