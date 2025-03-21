# React Login & Registration Form

![Project Screenshot](./assets/screenshot.png) <!-- Replace with your actual image path -->

## Overview
This is a React-based user registration and login form that includes validation and error handling. The project follows best practices for form validation using regular expressions and state management with the `useState` and `useEffect` hooks.

## Features
- User registration with username and password validation
- Password strength validation
- Error handling for username availability and server response
- Responsive design using CSS
- Uses `FontAwesome` icons for UI feedback

## Technologies Used
- React
- FontAwesome
- Axios
- CSS (custom styles for form validation and layout)

## Installation
### Prerequisites
- Node.js installed
- npm or yarn installed

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Nyabayo/react_login.git
   ```
2. Navigate to the project directory:
   ```bash
   cd react_login
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure
```
react_login/
├── src/
│   ├── api/
│   │   ├── axios.jsx
│   ├── components/
│   │   ├── Register.jsx
│   ├── assets/
│   │   ├── screenshot.png
│   ├── App.jsx
│   ├── main.jsx
│   ├── styles.css
│
├── public/
├── package.json
├── README.md
```

## Usage
1. Open the application in the browser after running the dev server.
2. Enter a username and password that meet the validation criteria.
3. Submit the form to register a user.
4. If an error occurs, appropriate messages will be displayed.

## Screenshots
![Registration Form](./assets/Screenshot.png) 


## Author
[Ernest Osindo](https://github.com/Nyabayo)

---
Feel free to update the screenshots and add more details based on your needs!

