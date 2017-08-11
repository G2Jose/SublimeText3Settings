My personal Sublime Text 3 User folder. I mainly use this to keep my sublime settings & packages in sync across my work & personal computers.

## Installation on Mac

Ensure you have Package Control installed. If not, hit `⌘ + ⇧ + P`, and type in "Install package control"

```bash
# Clone repo
git clone https://github.com/G2Jose/SublimeText3Settings.git

# Backup existing Sublime Text 3 User folder
mv ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/ ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User.backup

# Copy new folder
mv SublimeText3Settings ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User

```