# LinuxFM

Static archive of **LinuxFM.ir**, the first Persian-language internet radio about GNU/Linux (2010–2011).

Live site: https://pesarkhobeee.github.io/linuxfm/

## Layout

- `index.html` – single-page site listing every episode and its segments
- `script/` – styles, fonts, jQuery UI and the jPlayer podcast widget
- `img/` – menu and background images
- `media/` – podcast audio (`old/<episode>/*.ogg`, `new/*.ogg`); not stored in this repository because of size

## Local preview

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000/.
