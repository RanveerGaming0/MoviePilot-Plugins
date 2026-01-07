# 🎬 MoviePilot-Plugins - Manage Your Movie Subscriptions Easily

[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-v1.0-brightgreen)](https://github.com/RanveerGaming0/MoviePilot-Plugins/releases)

## 🚀 Getting Started

Welcome to the MoviePilot-Plugins! This application simplifies how you track movie and TV show subscriptions. With just a few steps, you can ensure that your favorites are always available in your personal cloud storage.

## 💻 System Requirements

- Windows, macOS, or Linux
- Python 3.7 or higher
- Stable internet connection

## 📥 Download & Install

1. **Visit the [Releases page](https://github.com/RanveerGaming0/MoviePilot-Plugins/releases)**.
2. Choose the latest version of the plugin.
3. Download the appropriate file for your operating system.
4. Follow the installation instructions on the page or in the README file.

## 🛠️ Installation Steps

1. Open your command line interface (Terminal, Command Prompt, or PowerShell).
2. Navigate to the directory where you downloaded the file.
3. Install the required dependencies by running the following command:

   ```bash
   pip install p115client>=0.0.8.2 sqlitetools>=0.0.7 playwright
   ```

4. Follow the configuration steps below to set up the plugin.

## ⚙️ Configuration

Before using the plugin, you need to configure a few settings.

### 📌 Basic Configuration

| Configuration Item        | Description                               |
|---------------------------|-------------------------------------------|
| Enable Plugin             | Turn the plugin on or off                |
| Send Notifications        | Receive messages when transfers complete  |
| Execution Cycle           | Set the frequency of operations (default: every 8 hours) |
| TV Show Storage Directory  | Set the default directory for TV shows (default: `/我的接收/MoviePilot/TV`) |
| Movie Storage Directory    | Set the default directory for movies (default: `/我的接收/MoviePilot/Movie`) |

### 📂 115 Cloud Storage Configuration

- Enter your 115 Cookie, which you can copy from the 115网盘STRM助手.

### 🔍 Search Source Configuration

The plugin supports three search sources. You can enable multiple sources. If one source does not find a resource, the plugin will automatically try the next one.

**Nullbr (TMDB Precise Match):**
- APP ID and API Key required.
- Uses TMDB ID for accurate querying.

**PanSou:**
- A cloud storage aggregator for finding resources.

## 🎯 Features

- Automatically track new movies and TV shows from subscriptions.
- Utilize three search sources for better results.
- Smart matching for various naming formats (e.g., S01E01, EP01).
- Auto-upgrade to higher quality resources based on your settings.
- Inherit filtering conditions from MoviePilot subscriptions.
- Filter out default MoviePilot downloads to focus on this plugin.
- Prevent duplicate file transfers by checking existing files and history.
- Automatically mark subscriptions as complete when transfers finish.
- Batch operations with rate limits and intelligent retries to avoid issues.

## 🔗 Support

If you run into any problems while using the plugin, check the [Issues page](https://github.com/RanveerGaming0/MoviePilot-Plugins/issues) for solutions or report any bugs. Your feedback helps improve this tool for everyone.

## 📝 License

This project is licensed under the MIT License. See the LICENSE file for more details.

Don't forget to return to the **[Download Latest Release](https://github.com/RanveerGaming0/MoviePilot-Plugins/releases)** to get the most recent features and improvements. Enjoy managing your movie subscriptions!