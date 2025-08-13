# Fancy Counter

[Preview Website](https://musel25.github.io/fancy-counter/)

A visually appealing counter application built with React and Vite. This project was created following the tutorial from [ByteGrad](https://bytegrad.com/).

## Features

- Increment and decrement a counter with visual feedback
- Reset functionality to set the counter back to zero
- Keyboard support (spacebar to increment)
- Visual indication when reaching the counter limit
- Responsive design that works on different screen sizes
- Attractive UI with smooth animations and transitions

## How It Works

The counter has a minimum value of 0 and a maximum value of 5. When the user reaches the maximum value, the UI changes to indicate that the limit has been reached, and further incrementing is disabled. 

Users can:
- Click the minus button to decrease the counter
- Click the plus button to increase the counter
- Press the spacebar to increase the counter
- Click the reset button to set the counter back to zero

## Technical Details

This project is built with:
- React (with hooks like useState and useEffect)
- Vite as the build tool
- Radix UI Icons for the icon components
- CSS for styling with a responsive design

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Building for Production

To create a production build:
```bash
npm run build
```

To preview the production build:
```bash
npm run preview
```

## Based on ByteGrad Tutorial

This project was created following the excellent React tutorial from [ByteGrad](https://bytegrad.com/). Check out their website for more React and web development tutorials.