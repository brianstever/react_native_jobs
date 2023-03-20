# First React Native Build - Job Search App

This is a simple React Native app that I created by following a YouTube tutorial. The app demonstrates basic features and functionality of React Native.

## YouTube Tutorial

The tutorial I followed can be found at this link:

[Build and Deploy a React Native App | 2023 React Native Course Tutorial for Beginners](https://www.youtube.com/watch?v=mJ3bGvy0WAY&t=137s)

## Features

This React Native app demonstrates the following features:

- Visually appealing UI/UX design inspired by [this Dribbble shot](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGVROUtfcFV4RGdCZzdkNE1IQnhVQUVWUFp4d3xBQ3Jtc0trblgzSFlMa29HOTNoU3lJQXdyS1JqNU9vS2UtYkItU1FZZDBnamdBRGJib215anpmOGFJb20zZFYxRjUtUXFNYUx2Z1JmSjJwQVd1YlVXTWRsbTJGYzNvZ3p5YWJKYnNHT25oT3NMc0dhQ3FwRHJmYw&q=https%3A%2F%2Fdribbble.com%2Fshots%2F11867493-Job-finder-Mobile-UI-Job-list&v=mJ3bGvy0WAY)
- Fetching data from an external API using [RapidAPI](https://rapidapi.com/)
- Integrating API data into the app, including search and pagination functionality
- Custom API data fetching hooks for better code organization and reusability
- State management using [React Hooks](https://reactjs.org/docs/hooks-intro.html)
- Clean, organized, and maintainable code with proper architecture

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- [Node.js](https://nodejs.org/) >= 14.x.x
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [Expo CLI](https://expo.io/tools#cli) installed globally (`npm install -g expo-cli`)
- A JSearch API key and API URL from [RapidAPI](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch/)

### Setting up API keys

1. Create a `.env` file in the root directory of the project.

2. Add your JSearch API key and URL from RapidAPI to the `.env` file like this:

RAPID_API_KEY=your_rapidapi_key <br>
RAPID_API_URL=jsearch.p.rapidapi.com

Replace your_rapidapi_key with your actual API key. 

### Installation

Clone the repository:

bash
git clone https://github.com/your-username/my-react-native-app.git
Change to the project directory:

cd my-react-native-app
Install the dependencies:

#### Using yarn
yarn install

#### Using npm
npm install

### Running the app

Start the development server:

#### Using yarn
yarn start

#### Using npm
npm start

Open the Expo Go app on your iOS or Android device and scan the QR code displayed in the terminal.
