# Sveriges Radio VMA Alerts

Archive of important public announcement (VMA) alerts from [vmaapi.sr.se](https://vmaapi.sr.se). The full history of alerts are visualized as an [interactive timeline](https://pages.davidjohansson.dev/sr-vma-alerts).

## Dev

Generate the data file

```sh
scripts/generate-data-file.sh
```

Serve the site files on localhost using an http server e.g.

```sh
python3 -m http.server -d site/ 3000
```
