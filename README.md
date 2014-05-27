# &lt;konami-code&gt;

A simple Web Componets for Easter Egg.

## Demo
> [Check it live](http://migre.me/jmnFI).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install konami-ce --save
```

Or [download as ZIP](https://github.com/mvaldetaro/konami-code/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="bower_components/platform/platform.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="bower_components/konami-code/src/konami-code.html">
  ```

3. Start using it!

  ```html
<konami-code></konami-code>
  ```

## Options

Attribute | Options         | Default                           | Description
---       | ---             | ---                               | ---
`image`   |                 | `src/assets/images/toasty.png`    | Specifies the image source
`sound`   |                 | `src/assets/sound/toasty-mk2.mp3` | Specifies the sound source
`width`   |                 | `150px`                           | Specifies the width of the content
`height`  |                 | `145px`                           | Specifies the height of the content
`itop`    |                 |                                   | The initial top property position
`iright`  |                 |                                   | The initial right property position
`ibottom` |                 | `0`                               | The initial bottom property position
`ileft`   |                 | `-150px`                          | The initial left property position
`etop`    |                 |                                   | The final top property position
`eright`  |                 |                                   | The final right property position
`ebottom` |                 | `0`                               | The final bottom property position
`eleft`   |                 | `0`                               | The final left property position
`time`    |                 | `0`                               | Set the animation time

## Browser Support

![IE](https://raw.github.com/paulirish/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/paulirish/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/paulirish/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/paulirish/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/paulirish/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/mvaldetaro/konami-code/releases) list.

## License

[MIT License](http://mvaldetaro.mit-license.org/) © Magno Valdetaro

## Notes

https://github.com/snaptortoise/konami-js
