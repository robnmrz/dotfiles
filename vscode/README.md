### How to install vs code extension automatically

```bash
cat extensions.txt | xargs -L1 code --install-extension
```

To use the VIM extension in Vscode the default behavior for key presses needs to be adjusted
```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```
to go back to default behavior
```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool true
```
