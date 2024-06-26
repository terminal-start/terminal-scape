## Terminal Start Page

Welcome to the Terminal Start Page repository! This project provides a customizable Linux terminal start page with interactive widgets for time, options to save URL, bookmarks, and a sleek and modern terminal interface for your New Tab / Start Page.

## Discussion

### Join the Discussion
To discuss ideas, issues, or provide any feedback, join the [Discord](https://discord.com/invite/B6SU7NTdru).

## Getting Started

### Download and Setup
1. Click on the green "Code" button above and select "Download ZIP".
2. Extract the downloaded ZIP file to your desired location on your computer.
3. Alternatively you can use https://terminal-start.github.io/terminal-scape/start.html in the next steps in the guide.


### Add to Start Page
1. Open your browser and go to the Chrome Web Store.
2. Search for the "Custom New Tab URL" extension and install it.
3. Open the extension's options by clicking on its icon in the browser toolbar.
4. In the extension's options, enter `file:///E:/terminal-scape/start.html` as the custom new tab URL. Alternatively, you can use [https://terminal-start.github.io/terminal-scape/start.html](https://terminal-start.github.io/terminal-scape/start.html).
5. If you are using the local file (`file:///E:/...`) method, make sure to enable the permission "Allow access to file URLs" for the extension.
6. Save the changes in the extension's options.

**Note:** We recommend downloading the repository and using the local file method for the best experience. However, if you prefer not to download the repository, you can use the GitHub Pages URL [https://terminal-start.github.io/terminal-scape/start.html](https://terminal-start.github.io/terminal-scape/start.html) as an alternative. Keep in mind that using the GitHub Pages URL may have slight differences in functionality compared to the local file method.

### Open New Tab
- After completing the steps above, open a new tab in your browser, and you should see the custom terminal start page.

## Media

![Terminal Start Page](https://i.imgur.com/zfw5obP.gif)
![Terminal Start Page](https://github.com/ForgeSpace/terminal-scape/assets/156608888/f3093f56-9486-477b-927b-83094d26fc8e)

## Customization

You can customize the terminal start page by editing the `start.html` file. Here are a few things you can do:

- **Add Options:** To add options, type commands like `add option_name` and press Enter. This will add the specified option to the terminal interface.
- **Remove Options:** Remove options by typing commands like `remove option_name` and pressing Enter. This will remove the specified option from the terminal interface.
- **Open Links:** When typing a command that does not start with 'add' or 'remove' and does not contain '.com' or any other top-level domain (TLD), the terminal will perform a Google search using the entered term. If the command contains a URL with a valid TLD (e.g., `.com`, `.org`, etc.), the terminal will open the specified website directly in a new tab.

This customization feature allows you to manage options, perform Google searches, and open URLs directly from the terminal interface.
