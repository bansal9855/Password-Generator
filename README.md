# Password Generator App

## Project Overview

The **Password Generator App** is a React-based web application that generates random passwords according to user-specified preferences such as password length, inclusion of numbers, and special characters. It includes a feature to copy the generated password to the clipboard for easy use.

## Features

- **Dynamic Password Length**: Users can adjust the length of the password (from 6 to 50 characters).
- **Numbers and Special Characters**: Users can toggle the inclusion of numbers and special characters.
- **Password Display**: The generated password is displayed in a text field.
- **Clipboard Functionality**: The user can copy the password to the clipboard with a single click.
- **Responsive Design**: The application is styled with Tailwind CSS and is fully responsive.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **useState, useCallback, useEffect, useRef**: React hooks used for state management and optimization.
- **Tailwind CSS**: A utility-first CSS framework for styling.

## How It Works

1. The application generates a password based on the user's preferences using a random string of letters, numbers, and special characters.
2. The user can adjust the length of the password using a range slider.
3. The user can choose whether to include numbers and special characters via checkboxes.
4. The generated password is displayed in a text field and can be copied to the clipboard by clicking the **copy** button.

## Installation and Setup

### Prerequisites

- Ensure you have [Node.js](https://nodejs.org/) installed on your machine.
- Ensure you have a package manager like [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) installed.

### Clone the Repository

```bash
git clone https://github.com/bansal9855/Password-Generator
cd password-generator-app
```

### Install Dependencies

Run the following command to install the required packages:

```bash
npm install
```

### Start the Application

Run the following command to start the development server:

```bash
npm run dev
```

Then, open your browser and navigate to `http://localhost:5173` to see the application in action.

## Usage

1. Adjust the password length using the range slider (min length: 6, max length: 50).
2. Toggle the **Numbers** checkbox to include or exclude numeric characters.
3. Toggle the **Characters** checkbox to include or exclude special characters.
4. The password is automatically generated and updated based on your selections.
5. Click the **copy** button to copy the password to your clipboard.

## Example

- Default password: **8 characters long**, containing uppercase and lowercase letters.
- When **Numbers** are enabled: Password includes digits (e.g., "Ab12Cd34").
- When **Characters** are enabled: Password includes special characters (e.g., "Ab#1$Cd!").

