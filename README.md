# Analog Clock Using Pure JavaScript

This project demonstrates how to create an analog clock using **HTML**, **CSS**, and **pure JavaScript**. The clock updates in real-time with the accurate movement of the hour, minute, and second hands.

## Features

- **Real-time Analog Clock**: Displays the current time with an accurate representation of the hour, minute, and second hands.
- **Smooth Movement**: The clock hands rotate smoothly and update every second.
- **Responsive Design**: The clock adjusts its size based on the screen size, ensuring it looks good on both desktops and mobile devices.
- **Minimalistic Style**: The design is simple yet elegant, with a clock face that uses an image (`clock.png`), which can be customized.

## Technologies Used

- **HTML**: For structuring the clock container and hands.
- **CSS**: For styling the clock face and hands, including responsiveness.
- **JavaScript**: Handles the logic to update the positions of the clock hands every second based on the current time.

## How It Works

The clock uses JavaScript's `Date` object to get the current time (hours, minutes, and seconds). The hands of the clock are rotated based on the calculated angles:
- The hour hand is rotated by `30°` per hour and adjusted slightly by the minutes (`1/2°` per minute).
- The minute hand is rotated by `6°` per minute.
- The second hand is rotated by `6°` per second.

### Functionality:

1. **Hour Hand**: Moves based on the current hour, with a smooth transition that also adjusts slightly for the current minute.
2. **Minute Hand**: Moves every minute with a smooth transition.
3. **Second Hand**: Moves continuously every second.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sanghita-Seal/Analog-Clock.git
