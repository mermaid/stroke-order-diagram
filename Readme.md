# Kanji Stroke Order Jenerator

## Usage
To use the browser version, just load the [web page](https://mermaid.github.io/stroke-order-diagram/index.html)

To use the cli:
1. Clone the repo
1. Install node (v12 is what I used)
1. `yarn install`
1. `node generate-diagrams.js --dir=<directory to download to> --kanji=<kanji[,kanji]>
  
The default directory is `downloaded`.

All kanji from WaniKani are committed to this repo in the `kanji` folder and can be accessed from 
`https://raw.githubusercontent.com/mermaid/stroke-order-diagram/master/katnji/<5 digit code point>.svg`

EX. for `一`, it's code point is `U+4E00`, so the filename is `04e00.svg`, and the url is `https://raw.githubusercontent.com/mermaid/stroke-order-diagram/master/katnji/04e00.svg`
