# whistle.connect-react-devtools

This plugin injects code into html to connect to react-devtools. It may be useful when debugging webview or something cannot utilize chrome extension [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi).

## Note

1. based on react-devtools@4.13.5
2. may conflict with chrome extension [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)

## Usage

1. install [react-devtools](https://www.npmjs.com/package/react-devtools)
```shell
npm install -g react-devtools
```

2. install whistle.connect-react-devtools
```shell
npm install -g whistle.connect-react-devtools
```

3. add rule in whistle
```
# default connected to localhost:8097
pattern whistle.connect-react-devtools://

# customize host and port
pattern whistle.connect-react-devtools://ip:port
```

4. start react-devtools
```
react-devtools
```

5. open webpage and start debugging
