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

## Screenshots

### Start menu
<img width="763" height="673" alt="image" src="https://github.com/user-attachments/assets/d787c538-355b-409d-b010-33c874e386d7" />


### Adding a wish
<img width="910" height="793" alt="image" src="https://github.com/user-attachments/assets/d97c38dd-3820-46d0-8373-0b0276fa7ca0" />


### Viewing wishlist
<img width="1004" height="900" alt="image" src="https://github.com/user-attachments/assets/5824f0b1-f78d-4251-8d43-5a994b0eef90" />


### Deleting a wish
<img width="816" height="728" alt="image" src="https://github.com/user-attachments/assets/2ef9435d-d1df-4d11-8d75-6c591c70a9d0" />
<img width="1004" height="894" alt="image" src="https://github.com/user-attachments/assets/c09cd615-3454-49ea-a63d-74f054b5902d" />


### Viewing another user's wishlist
<img width="1004" height="898" alt="image" src="https://github.com/user-attachments/assets/e9243f0f-9568-4f95-a524-b2c96eb12f21" />
м<img width="1004" height="896" alt="image" src="https://github.com/user-attachments/assets/2318b0f3-19fc-4a03-95e8-1042ee8b3322" />


### Database structure: users and wishlists
<img width="1004" height="248" alt="image" src="https://github.com/user-attachments/assets/53c20286-6488-4c51-ba92-f5714ab8d7d1" />

### Users
<img width="666" height="644" alt="image" src="https://github.com/user-attachments/assets/e526a969-a236-4f38-9a39-362a64a5a7c7" />

### Wishlists
<img width="672" height="638" alt="image" src="https://github.com/user-attachments/assets/70a642e6-2e8f-478e-80d8-93d691cee087" />

## Bot Commands

```text
/start - Start the bot and open the main menu
/help - Show the welcome message
/add - Add a new wish
/view - View your wishlist
/delete - Delete a wish from your wishlist
/view_user - View another user's wishlist
/my_id - Show your Telegram ID




