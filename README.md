# custom-vs-css
Has some custom UI/CSS for the VS code. 🤪


# Install this VS code extension
<img width="657" height="182" alt="image" src="https://github.com/user-attachments/assets/029d84b6-4116-44bf-a428-ceb5909950ab" />

# Add the path to load custom css
- From VS code, press _Ctrl+Shift+P_ and type _"User Settings (JSON)"_
- Open the same and update the following:
  `"vscode_custom_css.imports": ["file:///C:/Users/Naveen/Desktop/custom-vs-css/custom-vscode.css"]`
  NOTE: The path may differ, but use _file:///_ as standard

- Create the files and copy the code from the repo files (or just clone the repo and change the path respectively😂)

# Enable custom css and js
- From VS code, press _Ctrl+Shift+P_ and type _"Enable Custom CSS and JS"_ and press enter.
- You may have to close the VS code and open a new one.

# For new changes to reflect
- Once you change something from the css or js, press _Ctrl+Shift+P_ and type _"Reload Custom CSS and JS"_ and press enter.

Sometimes, the css might not be loaded on the start of the application, in that case, do the same step as reloading the css and js.
