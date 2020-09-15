
> Open this page at [https://khoapmd.github.io/fab-test/](https://khoapmd.github.io/fab-test/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/khoapmd/fab-test** and import

## Edit this project ![Build status badge](https://github.com/khoapmd/fab-test/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/khoapmd/fab-test** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

```blocks
basic.forever(function () {
    for (let index = 0; index <= 25; index++) {
        screenMagic.plotAt(index)
        basic.pause(100)
    }
})
```

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
