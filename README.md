# NES Controller
An interactive NES controller made completely by hand using SASS.

*Check it out live on the web: **[projects.nebuloid.dev/nes-css](https://projects.nebuloid.dev/nes-css/)***

![NES Controller](./img/banner.png)

## Run locally
From the project directory, start Python's local web server:
```sh
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.
Press `Ctrl+C` to stop the server.

## Compile SASS
From the project directory, compile `nes.scss` into `nes.css` with:
```sh
npx sass nes.scss nes.css
```
