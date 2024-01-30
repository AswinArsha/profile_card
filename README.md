

# Tailwind CSS Setup

This project demonstrates how to set up Tailwind CSS and run a live server to preview changes.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AswinArsha/profile_card.git
   ```

2. Navigate to the project directory:

   ```bash
   cd profile_card
   ```

3. Install dependencies:

   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```

## Usage

To compile Tailwind CSS and run the live server, follow these steps:

1. Run the following command to watch changes in the input CSS file and compile Tailwind CSS to the output file:

   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

2. Start the live server:

   ```bash
   live-server
   ```

3. Open your web browser and navigate to the live server address (usually `http://127.0.0.1:5500/src/index.html#`) to view your project.


