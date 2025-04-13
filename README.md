# Cat Clicker

## Overview

Cat Clicker is an interactive web-based application developed as part of Udacity's JavaScript Design Patterns course. This project demonstrates the Model-View-ViewModel (MVVM) design pattern using Knockout.js, a standalone JavaScript implementation of the MVVM pattern that helps create rich, responsive display and editor user interfaces with a clean underlying data model. The Cat Clicker game allows users to interact with different cats by clicking on their images to increase their click counts.

### Project Structure

The project is structured as follows:

- `index.html` - The entry point of the application. Contains the basic HTML structure.
- `css/` - Contains CSS files for styling the application.
- `js/` - Contains JavaScript files, including:
  - `app.js` - The main JavaScript file where Knockout.js is utilized to implement MVVM.
  - `knockout-3.5.1.js` - The Knockout.js library file.
- `img/` - Contains image files for the cats displayed in the application.

## Setup and Installation

### Prerequisites

Ensure you have Node.js installed on your machine. If not, you can download and install it from [Node.js official website](https://nodejs.org/).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cat-clicker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd cat-clicker
   ```
3. Since this project is purely frontend and uses Knockout.js included via a script tag, no further installation of dependencies is required. Simply open the `index.html` file in your browser to start using the application.

## Usage

To use Cat Clicker:

1. Open the `index.html` file in a web browser.
2. You will see a list of cats with their names and images displayed.
3. Click on a cat image to increase the click count for that cat.
4. The application dynamically updates the click count each time a cat image is clicked, demonstrating the MVVM pattern with data bindings.

## Contributing

Contributions to Cat Clicker are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Create a new Pull Request.

Please ensure your commits are well-formed and your code includes appropriate comments.

## License

Cat Clicker is open source and distributed under the MIT License. See the `LICENSE` file for more details.

---

Enjoy using Cat Clicker and happy coding!