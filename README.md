    $$$$$$$\   $$$$$$\   $$$$$$\  $$\   $$\  $$$$$$\  $$\   $$\ $$\     $$\ $$$$$$$$\ $$\   $$\
    $$  __$$\ $$  __$$\ $$  __$$\ $$$\  $$ |$$  __$$\ $$ |  $$ |\$$\   $$  |$$  _____|$$$\  $$ |
    $$ |  $$ |$$ /  $$ |$$ /  $$ |$$$$\ $$ |$$ /  \__|$$ |  $$ | \$$\ $$  / $$ |      $$$$\ $$ |
    $$$$$$$\ |$$$$$$$$ |$$ |  $$ |$$ $$\$$ |$$ |$$$$\ $$ |  $$ |  \$$$$  /  $$$$$\    $$ $$\$$ |
    $$  __$$\ $$  __$$ |$$ |  $$ |$$ \$$$$ |$$ |\_$$ |$$ |  $$ |   \$$  /   $$  __|   $$ \$$$$ |
    $$ |  $$ |$$ |  $$ |$$ |  $$ |$$ |\$$$ |$$ |  $$ |$$ |  $$ |    $$ |    $$ |      $$ |\$$$ |
    $$$$$$$  |$$ |  $$ | $$$$$$  |$$ | \$$ |\$$$$$$  |\$$$$$$  |    $$ |    $$$$$$$$\ $$ | \$$ |
    \_______/ \__|  \__| \______/ \__|  \__| \______/  \______/     \__|    \________|\__|  \__|

    Coding by: Bao Nguyen
    Tel: 0.96.96.89.89.3
    Email: baonguyenyam@gmail.com
    URL: fb.com/pham.nguyen.bao.nguyen,
    baonguyenyam.github.io/cv
    Design Tool: https://baonguyenyam.github.io/blog/

## Cài đặt
```bash
npm i -g cordova ionic yarn
npm install -g ios-deploy
brew install gradle

# Cài dependencies
yarn 

# Chạy Dev
ionic serve
```

## Build

`cordova platform add android ios --save`
`ionic cordova build ios --prod`
`ionic cordova build android --prod`

## Deploying

`npm run ionic:build --prod`

* Android `ionic cordova run android --prod`
  - Nếu chạy cho Android 4.4 thì nên có: `cordova plugin add cordova-plugin-crosswalk-webview`
* iOS `ionic cordova run ios --prod`
