# Color Changer

A simple web application that allows users to change the background color of the page by clicking on different color buttons.

https://color-changer-livid.vercel.app/
![Screenshot 2025-03-05 003948](https://github.com/user-attachments/assets/3c358657-2865-4394-91e8-33a9412fdf0e)

## Features
- Interactive UI with color selection buttons
- Changes background color dynamically on button click
- Simple and lightweight implementation using HTML, CSS, and JavaScript

## Technologies Used
- HTML
- CSS
- JavaScript

## How to Use
1. Open the `index.html` file in a browser.
2. Click on any of the color buttons (Grey, White, Blue, Yellow) to change the background color of the page.

## Project Structure
```
Color-Changer/
│── index.html      # Main HTML file
│── style.css       # Styling file
│── script.js       # JavaScript functionality
```

## Code Explanation
### HTML (`index.html`)
- Defines a simple webpage layout with a title, heading, and four color buttons.
- Each button is assigned a unique ID corresponding to a color.
- A script file (`script.js`) is linked at the end of the body.

### CSS (`style.css`)
- Styles the page layout and color buttons.
- Provides distinct colors for each button.

### JavaScript (`script.js`)
- Selects all buttons and the `body` element.
- Adds event listeners to buttons.
- Changes the `body` background color dynamically based on the button clicked.

## Future Improvements
- Add more color options.
- Implement a reset button to restore the default background color.
- Save the selected color in local storage to persist user preference.

## Author
Dikshant 

## License
This project is open-source and available under the MIT License.
