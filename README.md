# Interactive-Dashboard


This is an assignment to create an dashboard. 


Welcome to the Dashboard Layout project! This dashboard layout is built using HTML, CSS, and JavaScript, providing a user-friendly interface for data visualization and interaction.

## Features

- **Dark and Light Theme**: Toggle between dark and light themes for better user experience in different lighting conditions.
- **WebGL Shaders Waves**: Interactive waves powered by WebGL shaders respond to mouse movement, adding a dynamic element to the dashboard.
- **File Architecture**: Clear file architecture distinguishes between components and pages, enhancing maintainability and scalability.

## File Architecture

```
Interactive-Dashboard/
│
├── app.html             # Main HTML file to run the dashboard app
├──component/
|    ├── navbar.html      #navbar file to include in main file app.js
|    └── profile.html     #profile file to include in main file app.js
|
|
├──pages/
|    └──dashboard.html    dashboard file to include in main file app.js
│ app.css         # CSS styles for the dashboard layout
│   
│
├── js/
│   ├── app.js               # JavaScript logic for dashboard theme
│   ├── index.js             # WebGL shaders for interactive waves
|   ├── include-html.min.js  # Logic  to enable atribute  include-html from other file
|   └── jquery-3.6.0.min.js  # support the above include-html.js file  to handel file
│         
│
├── img/                   # Images used in the dashboard layout
│
└── README.md              # You are here!
```

## Installation

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/dashboard-layout.git
   ```

2. Navigate to the `Interactive-Dashboard` directory:
   ```
   cd dashboard-layout
   ```

3. Open the `app.html` file in your web browser to run the dashboard app.

## Usage

1. Upon opening the dashboard, you'll see the default layout with the light theme.
2. Use the theme toggle button to switch between dark and light themes based on your preference.
3. Explore the interactive waves by moving your mouse across the dashboard.

## Contributing

Thank you for considering contributing to this project! To contribute, follow these steps:

1. Fork the repository to your GitHub account.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear, descriptive messages.
4. Push your changes to your fork and submit a pull request to the main repository.

Please adhere to the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) code of conduct.

## License

This project is licensed under the [MIT License](LICENSE), allowing you to use, modify, and distribute the code for both personal and commercial purposes. See the LICENSE file for more details.

## Credits

Acknowledgment to the creators and contributors of libraries, frameworks, and resources used in this project.


Thank you for using the Dashboard Layout! If you have any questions or feedback, feel free to reach out. Happy dashboarding! 🚀📊

n