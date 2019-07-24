# slack4-dark-theme with lots of matrix colors. (edit colors with find/replace all)

For MacOS:

1) Edit file "~/Library/Application\ Support/Slack/local-settings.json"
- Change bootsonic value to never. "bootSonic":"never"

2) curl https://raw.githubusercontent.com/naumchenko/slack4-dark-theme/master/lato.less | tee /Applications/Slack.app/Contents/Resources/app.asar.unpacked/dist/static/lato.less
