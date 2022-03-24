# ImJoy Plugins for CNS Annotation Tools [![powered by ImJoy](https://imjoy.io/static/badge/powered-by-imjoy-badge.svg)](https://imjoy.io/)

Click here [![launch ImJoy](https://imjoy.io/static/badge/launch-imjoy-badge.svg)](http://imjoy.io/#/app?plugin=https://github.com/cns-iu/annotation-web-tool-imjoy-plugins/blob/main/src/CNS-FTUAnnotator.imjoy.html&start=CNS-FTUAnnotator) to launch the app plugin.

If launching for the first time, you should see a pop-up showing plugin details. Press `INSTALL` and the plugin will launch in your browser.

## Adding a new plugin to the repo
If a new plugin file is added to the repo or you changed existing ones, please run `node src/update_manifest.js` to udpate the plugin list. The script will generate a new `manifest.imjoy.json` in the root folder, and this is a file used by ImJoy to list plugins in the repo.


## License

Each plugin file may have its own license statement, otherwise MIT will be applied.

## Acknowledgement
This repository is based on code from https://github.com/CellProfiling/cellpro-imjoy-plugins.