# COT Web App Frontend

This is the frontend part of the COT Web App, which helps traders interpret signals given by the Commitment of Traders (COT) report.

## Prerequisites

- Node.js (v14 or above)
- npm (v6 or above)

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/cot-webapp-frontend.git
    cd cot-webapp-frontend
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Create a `.env` file in the root directory**:
    ```env
    REACT_APP_API_URL=http://localhost:5000
    ```

4. **Run the development server**:
    ```bash
    npm start
    ```

    The app will be available at `http://localhost:3000`.

## Project Structure

- `src/`
  - `components/`: Reusable UI components (e.g., Login form)
  - `pages/`: Page-level components (e.g., HomePage)
  - `App.js`: Main component with routing
  - `index.js`: Entry point of the React application

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm run build`: Builds the app for production
- `npm test`: Runs the test suite

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes.
