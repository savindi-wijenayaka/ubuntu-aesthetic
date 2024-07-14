# Ubuntu Aesthetic and fresh setup 

## Favourite Ubuntu apps
1. Terminator: Terminal that can split into multiple terminals horizontally and vertically.
2. Xpad: Sticky notes to keep track of your work, you can change the colours, fonts, etc to match your aesthetic. Options like strike-through (for tasks that are done) is available along with common formatting like bold, italic, etc.

## Themes for terminal
1. Install your prefered Nerd Font [[ref]](https://www.nerdfonts.com/font-downloads).
2. Install Starship and use the "starship.toml" as your config file [[ref]](https://starship.rs/guide/#%F0%9F%9A%80-installation).
3. You can adjust cursor shape, foreground background colours, font, title bar etc in the `right-click menu → Preferences → Profiles → Default`
4. Adjust the transparecy of the terminal to 70% - 80% in `Background` tab in the same section. 


## Setting up essential products

### Github
1. Download and install.
2. Configure global user name and email.
3. Create SSH key locally and add the public key to your profile [[ref]](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key).
4. Cache the Github credentials in Git using GitHub CLI [[ref]](https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git#github-cli).

### Conda
1. Download and install either miniconda or anaconda depending on your requirement.


### VS Code
1. Download and install.
2. Theme: Tokyo (Dark) → Downloaded via extension manager.
3. Install essential extensions:
    - Python
    - Python Debugger
    - autoDocstring: When you type `"""` this will automatically add the function docstrings. Google style is default and cleanest in my opinion.
4. Add file docstrings using `File → Preferences → Configure User Snippets`: When you type "docstring" at the begining of the file, this will be automatically created for you.
    - Python: 
        ```json
        {
            "Python Docstring Template": {
                "prefix": "docstring",
                "body": [
                "\"\"\"",
                "Author       : Savindi Wijenayaka",
                "Date created : ${CURRENT_DAY_NAME_SHORT} ${CURRENT_MONTH_NAME} ${CURRENT_DATE} ${CURRENT_HOUR}:${CURRENT_MINUTE}:${CURRENT_SECOND} ${CURRENT_YEAR}",
                "License      : ${2:MIT}",
                "Description  :",
                "        Write what this file is about",
                "\"\"\"$0"
                ],
                "description": "Python Docstring Template"
            }

        }
        ```

<!-- Refer https://dev.to/envoy_/150-badges-for-github-pnk for new badges -->
<!-- Sheilds.io can make any custom badge: https://img.shields.io -->
<br><hr><br>
<p align="center">
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" width="100">
<img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" width="100">
<img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
</p>
<p align="center"><img src="https://img.shields.io/badge/Made_with-♥️-crimson"></p>
