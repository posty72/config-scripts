# Oh My ZSH Setup

```
curl https://raw.githubusercontent.com/posty72/config-scripts/master/zsh/setup.sh | sudo sh
```

# Linting configs
---
Add these to `~/.zshrc` (should happen automatically with Oh My ZSH setup):

```bash
alias addeditorconf='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/.editorconfig > .editorconfig'
alias addeslint='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/.eslintrc > .stylelintrc.json && npm i -D eslint eslint-plugin-babel eslint-plugin-react eslint-plugin-filenames eslint-plugin-import'
alias addstylelint='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/.stylelintrc > .stylelintrc && npm i -D stylelint stylelint-order'
alias addtslint='curl -s https://raw.githubusercontent.com/posty72/config-scripts/master/tslint > tslint.json && npm i -D tslint'
``` 