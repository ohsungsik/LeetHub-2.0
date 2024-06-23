# LeetHub 2.0

LeetHub 2.0 is a Chrome extension that automatically syncs your LeetCode solutions to your GitHub account. It was created as an improved fork of the original LeetHub, addressing issues caused by changes in LeetCode and GitHub. The extension simplifies the process of tracking coding progress by pushing solved problems to a GitHub repository, helping users showcase their coding skills to recruiters.

## Features
- Automatically push your LeetCode solutions to a GitHub repository.
- Supports all LeetCode problem types.
- Customizable push frequency and repository structure.

## Changes in this Fork
- New Upload Location: Solutions are now uploaded to the leetcode/problem difficulty (Easy, Medium, Hard, Unknown) folder in your repository.

## Installation
- Run "npm run setup" to install the developer dependencies
- Run `npm run build` to build the final extension files into the `./dist/` directory
- Go to chrome://extensions
- Enable Developer mode by toggling the switch on top right corner
- Click 'Load unpacked'
- Select the `./dist/` LeetHub folder
- That's it! Be sure to `npm run build` and reload the extension after making changes

---

**For more detailed instructions and additional information, please refer to the [original LeetHub 2.0 repository.](https://github.com/arunbhardwaj/LeetHub-2.0)**