[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/dloeda/molecule-isotope-gallery)

# \<molecule-isotope-gallery\>

> is a webcomponent for displaying a filterable gallery using isotope.js to animage filter transitions
>
> Polymer 2.0 ready

## Usage example
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="molecule-isotope-gallery.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<molecule-isotope-gallery default-filter="mountain">
  <div slot="tags">
    <button data-filter="item">All</button>
    <button data-filter="sports">Sports</button>
    <button data-filter="mountain">Mountain</button>
    <button data-filter="foo">None</button>
  </div>  
  <img src="demo/images/mountain1.jpg" width="200" height="150" class="item mountain"/>
  <img src="demo/images/sports2.jpg" width="200" height="150" class="item sports"/>
  <img src="demo/images/mountain3.jpg" width="200" height="150" class="item mountain"/>
</molecule-isotope-gallery>
```

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install https://github.com/dloeda/molecule-isotope-gallery.git --save
```

Or [download as ZIP](https://github.com/dloeda/molecule-isotope-gallery/archive/master.zip).

## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/molecule-isotope-gallery.html">
    ```

3. Start using it!

    ```html
    <molecule-isotope-gallery>
        <div slot="tags">
            <button data-filter="sports">Sports</button>
            <button data-filter="mountain">Mountain</button>
        </div>  
        <img src="demo/images/mountain1.jpg" class="item mountain"/>
        <img src="demo/images/sports2.jpg" class="item sports"/>
        <img src="demo/images/mountain3.jpg" class="item mountain"/>
    </molecule-isotope-gallery>
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m '🎉 feat(*): Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request! 

## License

[MIT License](http://opensource.org/licenses/MIT)

