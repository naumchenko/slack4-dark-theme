# Slack4 dark theme with green like terminal/matrix colors. 
(hack and edit colors with find/replace all)

Theme Name: youWantItDarker


For MacOS install command:

```
On every update pushed by Slack, "local-settings.json" setting  bootsonic changed to ("bootSonic":"always").

!!! If Dark Theme stopped working, re-run the command in Terminal, restart Slack.!!!
```

1) Install Theme:

```
cd ~/Library/Application\ Support/Slack/; sed -i '' "s/always/never/g" local-settings.json; curl https://raw.githubusercontent.com/naumchenko/slack4-dark-theme/master/lato.less | tee /Applications/Slack.app/Contents/Resources/app.asar.unpacked/dist/static/lato.less
```

2) Restart Slack with local theme:

```
cd ~/Library/Application\ Support/Slack/; sed -i '' "s/once/never/g" local-settings.json; open -a /Applications/Slack.app
```


# Revert changes:

To revert to the original theme edit "local-settings.json" file, change value to "bootSonic":"always", save, restart Slack.

``` open ~/Library/Application\ Support/Slack/local-settings.json ``` 
