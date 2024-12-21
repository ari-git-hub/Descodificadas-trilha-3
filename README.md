# Descodificadas-trilha-3
Atividades da trilha 3 do programa Descodificadas

# Age Calculator App

This repository contains an age calculator app built using HTML, CSS, and JavaScript. The application calculates the user's age in years, months, and days based on a valid date input. It includes validation features and provides a responsive design for both desktop and mobile layouts.

---

## Features

- **Age Calculation**: Users can calculate their age in years, months, and days by entering a valid date.
- **Validation**:
  - Ensures all fields are filled before submission.
  - Checks if the day input is between 1-31.
  - Ensures the month input is between 1-12.
  - Validates that the entered date is not in the future.
  - Detects invalid dates (e.g., April 31).
- **Responsive Design**: Adapts to desktop and mobile screen sizes.
- **Interactive States**: Includes hover and focus states for all interactive elements.
- **Bonus Feature**: (Optional) Animate the age results to their final value after form submission.

---

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/age-calculator.git
cd age-calculator
```

### 2. Open the Project Locally
You can open the `index.html` file directly in your browser to preview the project.

Alternatively, for a local server setup:
- Install [VS Code](https://code.visualstudio.com/).
- Add the **Live Server** extension.
- Right-click on `index.html` in VS Code and select **Open with Live Server**.

---

## Deployment

### Option 1: GitHub Pages
1. Push the code to a GitHub repository.
2. Go to the repository **Settings** > **Pages**.
3. Select the branch (e.g., `main`) and save.
4. Access the project at the provided GitHub Pages link.

### Option 2: Vercel
1. Create an account on [Vercel](https://vercel.com/).
2. Import your repository and deploy.
3. Vercel will generate a unique URL for your project.

### Option 3: Netlify
1. Sign up on [Netlify](https://www.netlify.com/).
2. Drag and drop the project folder onto the dashboard to deploy.
3. Netlify will provide a public link.

---

## Usage

1. Open the app in your browser.
2. Enter a valid date in the input fields for day, month, and year.
3. Submit the form to see the calculated age.
4. Fix any invalid inputs as prompted by the error messages.

---

## Design Information

### Color Palette
- Primary Blue: `#007BFF`
- Light Gray Background: `#F0F4F8`
- Error Red: `#FF0000`

### Typography
- Font: **Inter**, sourced from Google Fonts.
- Weights: 400 (Regular) and 700 (Bold).

---

## File Structure
```
project-folder/
|-- index.html        # Main HTML file
|-- styles.css        # Styling
|-- script.js         # JavaScript for functionality
|-- /assets           # Design images and other assets
```

---

## Future Enhancements

- Add animations to age calculations for a smoother user experience.
- Integrate a backend service to store user data (e.g., birthdays).
- Implement additional accessibility features.

---

## Author
Created by [Ariane Florentino]. Feel free to reach out with feedback or suggestions!

---

## License
This project is licensed under the MIT License.

