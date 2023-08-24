# Naver Hanja Dict Add Copy Button

An extension for adding copy button to naver hanja dictionary.

## Build from source

### Prerequisite

- Nvm
  - [Download](https://github.com/nvm-sh/nvm#install--update-script)
  - setup (use version described in `.nvmrc`)
    - `nvm install` (if not installed)
    - `nvm use`
- Yarn
  - Install
    - npm install --global yarn

### Build

- Install dependencies
  - `yarn install`
- Run on browser
  - Default (Chrome)
    - `yarn run start`
  - Chrome (Default)
    - `yarn run start:chrome`
  - Firefox
    - `yarn run start:firefox`
- Bundle
  - `yarn run build` (`yarn run build -- --help` for help)
- Install to browser
  - [Chrome](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked)
    - chrome://extensions/ -> Developer mode -> Load unpacked -> select 'src'
  - [Firefox](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/)
    - about:debugging -> This Firefox -> Load Temporary Add-on -> select 'src'