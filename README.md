# Theme preview
![](Preview.png)
![](Preview2.png)

## Installation

Follow these steps to install the Gruvbox theme for the YouTube Music Desktop App:

### 1. Download the Theme
- Clone the repository or download the ZIP file:
  ```bash
  git clone https://github.com/lolkiller/YT-Music-gruvbox.git

### 2. Extract the Files
- If you downloaded the ZIP file, extract it to a convenient location on your computer.

### 3. Install YouTube Music Desktop App
- If you haven't already, download and install the [YouTube Music Desktop App](https://github.com/th-ch/youtube-music).

### 4. Locate the Configuration Directory
-  Open the directory where the app stores its settings:
-  Linux: **~/.config/youtube-music**
-  Windows: **%APPDATA%\youtube-music**
-  MacOS: **~/Library/Application Support/youtube-music**

### 5. Add the Gruvbox Theme
 - Copy the gruvbox.css file from the repository into the themes folder inside the app's configuration directory.
 - Note: If the themes folder doesn't exist, create it manually.
 
### 6. Configure the App to Use the Theme
- Open the config.json file in the app's configuration directory with any text editor.
- Add or update the "theme" property to reference the Gruvbox theme:
   ```json
    {
      "theme": "gruvbox.css"
    }
    
### 7. Restart the App
- Close and reopen the YouTube Music Desktop App to apply the new theme.


