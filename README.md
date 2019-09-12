# Set up scripts
Add these to `~/.zshrc`

```bash
alias addeslint='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/.eslintrc > .stylelintrc.json && npm i -D eslint eslint-plugin-babel eslint-plugin-react eslint-plugin-filenames eslint-plugin-import # eslint
alias addstylelint='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/.stylelintrc.json > .stylelintrc.json && npm i -D stylelint stylelint-order' # stylelint
alias addeditorconf='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/.editorconfig > .editorconfig' # editor config
alias addeditorconf='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/tslint > tslint.json && npm i -D tslint' # editor config
```
