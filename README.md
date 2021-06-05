# Presenter Pro for Visual Studio Code

[![Badge for version for Visual Studio Code extension johnpapa.presenter-pro](https://vsmarketplacebadge.apphb.com/version/johnpapa.presenter-pro.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=johnpapa.presenter-pro&WT.mc_id=javascript-0000-jopapa) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/johnpapa.presenter-pro.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.presenter-pro&WT.mc_id=javascript-0000-jopapa)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/johnpapa.presenter-pro.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=johnpapa.presenter-pro&WT.mc_id=javascript-0000-jopapa)
This Visual Studio Code extension pack includes a set of extensions that can help presenters while showing code live in person or over recorded.

## Install

1. Open **Extensions** sidebar panel in Visual Studio Code. `View → Extensions`
1. Search for `Presenter Pro`
1. Click **Install**
1. Click **Reload**, if required

> As web tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Extensions Included

Here is the list of extensions the pack includes:

### Dimmer

Get [Dimmer](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-dimmer&WT.mc_id=javascript-0000-jopapa) here

Enable dimmer and set a subtle delay in the dimmer to reduce the API calls.

I keep the dimmer disabled until I need it, then turn it off again.

```json
  "dimmer.context": 1,
  "dimmer.opacity": 50,
  "dimmer.delay": 100,
  "dimmer.enabled": false
```

### Peacock

Get [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock&WT.mc_id=javascript-0000-jopapa) here

I change the accent color of the activity bar and status bar with Peacock. You can use any of the favorites, choose a random color, or enter your own custom color.

This is helpful for the audience when you show 2 different projects in a presentation, because they can more easily see the difference between them.

```json
  "peacock.affectActivityBar": true,
  "peacock.affectStatusBar": true,
  "peacock.affectTitleBar": false,
  "peacock.keepForegroundColor": false,
  "peacock.keepBadgeColor": false,
  "peacock.darkForegroundColor": "#15202b",
  "peacock.lightForegroundColor": "#e7e7e7",
```

### Power Mode

Get [Power Mode](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode&WT.mc_id=javascript-0000-jopapa) here

I only enable power mode for fun, use sparingly. I do not recommend enabling "shake" during presentations.

```json
  "powermode.enabled": false,
  "powermode.enableShake": false,
  "powermode.presets": "particles",
```

### Winter is Coming Theme

Get [Winter is Coming](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming&WT.mc_id=javascript-0000-jopapa) here

I prefer the dark blue theme, but the light theme can be helpful when the projector shows dark colors as washed out.

```json
  "workbench.colorTheme": "Winter is Coming (Dark Blue)",
```

## Changes

See the [CHANGELOG](CHANGELOG.md) for the latest changes.

## Resources

- [Get VS Code](https://code.visualstudio.com/?WT.mc_id=javascript-0000-jopapa)
- [Create your first VS Code extension](https://code.visualstudio.com/api/get-started/your-first-extension?WT.mc_id=javascript-0000-jopapa)
- [VS Code Extension API](https://code.visualstudio.com/api/references/vscode-api?WT.mc_id=javascript-0000-jopapa)
- [Learn how to add WebPack bundles to your favorite extensions](https://code.visualstudio.com/updates/v1_32?WT.mc_id=javascript-0000-jopapa#_bundling-extensions-with-webpack?wt.mc_id=presenterpro-github-jopapa)
