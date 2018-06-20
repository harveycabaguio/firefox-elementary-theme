# An elementary Theme for Firefox Quantum

![Screenshot](screenshot@2x.png)

This userChrome.css mimics the [elementary GTK+ theme](https://github.com/elementary/stylesheet) to make firefox blend in better in elementary OS.

## How to install
### Terminal
```shell
curl https://git.io/fYMYZ -o "$HOME/.mozilla/firefox/$( cat $HOME/.mozilla/firefox/profiles.ini | grep -oP '(?<=Path=).*' )/chrome/userChrome.css" -sLS --create-dirs
```
### Manual
1. Go to [about:support](about:support) in Firefox
2. Application Basics > Profile Directory > Open Directory
3. Create a folder named `chrome`
4. Paste userChrome.css in this folder
