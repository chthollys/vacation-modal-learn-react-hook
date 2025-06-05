# PlacePicker

A React app to create your personal collection of places you would like to visit or have visited. The app demonstrates the use of React hooks, side effects, geolocation, and localStorage for persistent state.

## Features

- Browse a list of available places, sorted by your current location
- Select places to add to your personal list
- Remove places from your list with a confirmation modal and countdown
- Persistent selection using browser localStorage

## Technologies Used

- React (with hooks)
- Vite (for development/build)
- JavaScript (ES6+)
- HTML/CSS

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn

### Installation

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd 08-sideEffect
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the App

Start the development server:

```bash
npm run dev
# or
yarn dev
```

Open your browser and navigate to the local server address (usually http://localhost:5173/).

## Project Structure

- `src/App.jsx` - Main application component
- `src/components/` - UI components (Places, Modal, DeleteConfirmation)
- `src/data.js` - List of available places
- `src/loc.js` - Utility for sorting places by distance
- `src/assets/` - Images and logo

## Notes

- The app requests your geolocation to sort available places. If denied, places are shown in default order.
- Selected places are saved in localStorage under the key `selectedPlaces`.

## License

This project is for educational purposes (Udemy React course).
