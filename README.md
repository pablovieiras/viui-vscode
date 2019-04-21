<h1 align="center">
  <br>
  <a href="https://vitta-health.github.io/Vi-Ui/"><img src="https://raw.githubusercontent.com/vitta-health/Vi-Ui/master/docs/layout/components/vi-ui.svg?sanitize=true" alt="Vi-Ui" width="200"></a>
  <br>
  viui-vscode
  <br>
</h1>

<h4 align="center">A Visual Code Extension for <a href="https://vitta-health.github.io/Vi-Ui/" target="_blank">Vi-Ui</a></h4>

<p align="center">
  <a href="#intro">Intro</a> •
  <a href="#how-to-install">How To Install</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#future-ideas">Future Ideas</a> •
  <a href="#release-notes">Releases</a> •
  <a href="#license">License</a>
</p>

## Intro

Vi-Ui is a simple but consistent user interface for Vue and `viui-vscode` extension provides snippets and autocomplete to use with Visual Code.

![screenshot](https://raw.githubusercontent.com/test.gif)


## How To Install

Just search for `viui-vscode` in VS Code Extensions section or go to <a href="https://vitta-health.github.io/Vi-Ui/" target="_blank">VS Code Market Place</a> or install it with the following command:

````
ext install viui.viui-vscode
````

## How To Use
It's very simple to use this extension. All you need to do is type `vi-{component-name}` to get all options for that component.

#### Snippet

If you want to add some Vi-Ui component just type:
````
vi-{component-name}
````
For example, if you need a tooltip, type `vi-tooltip` and you'll get the full component:
````
<vi-tooltip top hover mini content="message">
  <span>Hover Me</span>
</vi-tooltip>
````
You can list all props, events or slots of a component:
````
vi-{component-name}-props
vi-{component-name}-events
vi-{component-name}-slots
````

## Future Ideas

- Add component docs when hover it
- Sintax highlighting

## Release Notes

### 1.0.0

Initial release of `viui-vscode`

-----------------------------------------------------------------------------------------------------------

## License
[MIT](https://github.com/vuetifyjs/vuetify-vscode/blob/master/LICENSE)

**Thanks!**