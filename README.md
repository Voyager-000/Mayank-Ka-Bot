# Mayank TG Bot Help

A feature-rich Telegram Bot built using the `python-telegram-bot` library. This bot provides a variety of interactive modules ranging from group management and games to a built-in calculator and entertainment commands.

## Features

- **Group Management ⚙️**: Manage your group efficiently with commands for banning, unbanning, kicking, muting, and managing admin permissions (`/ban`, `/mute`, `/promote`, `/setwelcome`, etc.).
- **Games 🎮**: Have fun with friends using games like Rock Paper Scissors, Truth and Dare, Dice Roll, Coin Toss, and Number Guess.
- **Calculator 🟰**: Perform basic mathematical calculations (`+`, `-`, `*`, `/`, `^`), find tables, or check if a number is prime directly in the chat.
- **Entertainment 🦍**: Play around with fun commands like roasts (`/roast`), luck predictions (`/luck`), pickup lines (`/flirt`), and more.
- **Note Saving 🗒**: Save important text or notes directly in the chat (`/save`).
- **Broadcasting 📡**: (Admin Only) Broadcast messages to all users who have interacted with the bot.

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Voyager-000/Mayank-Ka-Bot.git
   cd Mayank-Ka-Bot
   ```

2. **Install dependencies:**
   Make sure you have Python installed, then install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set your Bot Token:**
   The bot requires a token from Telegram's [BotFather](https://t.me/BotFather).
   Set the `BOT_TOKEN` environment variable:
   
   *On Windows (Command Prompt):*
   ```cmd
   set BOT_TOKEN=your-bot-token-here
   ```
   *On Windows (PowerShell):*
   ```powershell
   $env:BOT_TOKEN="your-bot-token-here"
   ```
   *On Linux/Mac:*
   ```bash
   export BOT_TOKEN="your-bot-token-here"
   ```

4. **Run the bot:**
   ```bash
   python main.py
   ```

## File Structure

- `main.py`: The core script that runs the bot and defines all command handlers.
- `requirements.txt`: Contains the required Python libraries (`python-telegram-bot==22.2`).
- `data.txt` / `data_all.txt` / `datachat.txt`: Stores user IDs and chat IDs for internal tracking and broadcasting.
- `feedback.txt`: Stores user feedback.

## Usage
Once the bot is running, go to your Telegram app, search for your bot, and send `/start`. You can also type `/menu` to explore a fully interactive inline menu of all available features.
