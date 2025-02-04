# Password Manager

## Overview
This is a simple password manager built using Python and Tkinter. It allows users to generate secure passwords, store them securely in a text file, and easily retrieve them when needed.

## Features
- **Password Generator**: Generates strong passwords with a mix of letters, numbers, and symbols.
- **Clipboard Support**: Copies the generated password to the clipboard automatically.
- **Data Storage**: Saves website credentials (website, email/username, password) in a `data.txt` file.
- **User-Friendly Interface**: Uses Tkinter to provide an interactive and simple GUI.

## Technologies Used
- Python
- Tkinter (GUI Library)
- Random (for password generation)
- Pyperclip (for clipboard functionality)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/password-manager.git
   ```
2. Navigate to the project directory:
   ```sh
   cd password-manager
   ```
3. Install dependencies:
   ```sh
   pip install pyperclip
   ```
4. Run the application:
   ```sh
   python main.py
   ```

## Usage
1. Enter the website name.
2. Enter the email/username.
3. Click **Generate Password** to create a strong password.
4. Click **Add** to save the credentials to `data.txt`.
5. The password will be copied to the clipboard automatically.

## File Structure
```
password-manager/
│── main.py      # Main application script
│── logo.png     # Application logo
│── data.txt     # Stored credentials (automatically created)
│── README.md    # Project documentation
```

## Future Improvements
- Implement a database for secure storage.
- Add password retrieval and search functionality.
- Improve UI with more customization options.

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## Contact
For any questions, contact me at [your-email@example.com](mailto:your-email@example.com).

