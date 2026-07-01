# Wishi Telegram Wishlist Bot

Wishi is a Telegram bot for creating and managing personal wishlists.  
The bot allows users to add wishes, view their own wishlist, delete items, and view another user's wishlist by username or Telegram ID.

The project uses MongoDB to store users and wishlist items.

## Features

- Add items to a personal wishlist
- View your own wishlist
- Delete wishlist items using inline buttons
- View another user's wishlist by username or Telegram ID
- Save Telegram user information in MongoDB
- Simple Telegram keyboard menu
- Secure configuration using environment variables

## Technologies Used

- Python
- pyTelegramBotAPI
- MongoDB
- PyMongo
- python-dotenv

## Bot Commands

```text
/start - Start the bot and open the main menu
/help - Show the welcome message
/add - Add a new wish
/view - View your wishlist
/delete - Delete a wish from your wishlist
/view_user - View another user's wishlist
/my_id - Show your Telegram ID
