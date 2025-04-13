# 🌍 React Tours App

A responsive React application that displays travel destinations with the ability to remove cards and refresh the list. Built with modern React hooks and clean component architecture.

## 🚀 Features

- **Interactive Tour Cards**: Each card displays destination details with a "Read More/Show Less" toggle
- **Dynamic Filtering**: Remove destinations you're not interested in
- **Empty State Handling**: Shows a refresh option when all tours are removed
- **Responsive Design**: Works well on all device sizes

## 📦 Components

### `App.js`
- Manages the main state using `useState`
- Handles tour removal logic
- Implements empty state rendering

### `Tours.js`
- Container component that maps through tours data
- Renders multiple `Card` components

### `Card.js`
- Displays individual tour information
- Implements expandable/collapsible description
- Includes removal button

## 🛠️ Tech Stack

- React (Functional Components + Hooks)
- JavaScript (ES6+)
- CSS for styling
- Vite (for fast development)

## 📂 Project Structure

~~~
react-tours-app/
├── src/
│ ├── components/
│ │ ├── Card.jsx
│ │ └── Tours.jsx
│ ├── data.js
│ └── App.jsx
├── public/
└── README.md


## 🖼️ Sample Data

The app uses the following data structure for each tour:

```javascript
{
  id: Number,
  name: String,
  info: String,
  image: URL,
  price: String
}
~~~

🏃‍♂️ Getting Started
Clone the repository

Install dependencies: npm install

Run the development server: npm run dev

Open your browser to http://localhost:3000

🎨 Customization
Update data.js with your own destinations

Modify the styling in the CSS files

Adjust the description truncation length in Card.js
