## Overview
This Python script is designed to automate the creation and management of game passes on Roblox. It enables setting game passes off-sale, creating new game passes with varied prices and names, and verifying their creation.

## Usage Instructions

1. **Script Setup**:
   - Ensure Python 3 is installed on your system.
   - Install the `requests` library, if not already installed, using pip:
     ```
     pip install requests
     ```

2. **Configuring the Script**:
   - Configuration parameters are set via a JSON file. Create a `dt.json` file with your Roblox authentication key and other necessary parameters. Example format:
     ```json
     {
         "ck": "your_auth_key",
         "start_price": 1,
         "end_price": 1000,
         "universe_id": 123456789
     }
     ```
   - Place this file in the same directory as the script.

3. **Running the Script**:
   - After setting up the script with your configuration, run it.
   - The script will execute actions based on the parameters defined in the `dt.json` file.

If you encounter any issues or need assistance, feel free to contact us on Discord or via email:

- 🌐 Website: [safemarket.xyz](https://safemarket.xyz)
- 💬 Discord: [safemarket.xyz/discord](https://safemarket.xyz/discord)
- 📧 Email: support-checkout@safemarket.xyz