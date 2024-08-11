# Bot Battlr

Welcome to **Bot Battlr**! This React application is your gateway to building a custom bot army. Developed as part of a project, Bot Battlr allows users to browse, enlist, and manage robots, giving you hands-on experience with React and data management.

## Project Overview

**Bot Battlr** provides a fun and interactive way to:
- View a diverse list of robots.
- Add bots to your personal army.
- Remove or discharge bots as needed.
- Manage your bot collection effortlessly.

This project is designed to practice fundamental React concepts like components, state, and event handling.

## Features

- **Browse Bots**: Explore detailed profiles of available bots.
- **Enlist Bots**: Add bots to your army with a simple click.
- **Manage Army**: Easily release or discharge bots with user-friendly buttons.
- **Interactive UI**: Engaging interface that responds to user actions.

## Getting Started

To get started with Bot Battlr, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/KevinGitari/bot-battlr.git
   cd bot-battlr
   ```

2. **Install Dependencies**

   Ensure you have Node.js and npm installed. Install the project dependencies:

   ```bash
   npm install
   ```

3. **Set Up the JSON Server**

   Create `db.json` in the root directory with the sample data:

   ```json
   {
     "bots": [
       {
         "id": 101,
         "name": "wHz-93",
         "health": 94,
         "damage": 20,
         "armor": 63,
         "bot_class": "Support",
         "catchphrase": "1010010101001101100011000111101",
         "avatar_url": "https://robohash.org/nostrumrepellendustenetur.png?size=300x300&set=set1"
       },
       {
         "id": 102,
         "name": "RyM-66",
         "health": 86,
         "damage": 36,
         "armor": 77,
         "bot_class": "Medic",
         "catchphrase": "0110011100000100011110100110011000011001",
         "avatar_url": "https://robohash.org/quidemconsequaturaut.png?size=300x300&set=set1"
       }
     ]
   }
   ```

   Start the JSON server:

   ```bash
   npx json-server --watch db.json --port 8001
   ```

4. **Run the Application**

   Start the React development server:

   ```bash
   npm start
   ```

   Visit `http://localhost:3000` to see the application in action.

## Usage

- **Viewing Bots:** Access the bot collection from the homepage.
- **Enlisting Bots:** Click on a bot to add it to your army.
- **Managing Your Army:** Use the "Release" and "Discharge" buttons to manage your enlisted bots.

## Technologies Used

- **React**: For building the user interface.
- **CSS**: For styling and layout.
- **JSON Server**: To simulate a backend API.

## Contributing

I welcome contributions and feedback. Feel free to open issues or submit pull requests. If you have suggestions or improvements, let me know!

### LICENSE
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

