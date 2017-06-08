# fin-hypergrid

This repository exists solely to support it's github pages CDN, for continuity of legacy build file requests. The final version posted here is **Hypergrid v2.0.2** (new releases will not be posted here).

> NOTE: All `.js` files listed below are unminified and include the source map. Also available (but not listed below) are `.min.js` files (minified, no source map).

```html
<script src="openfin.github.io/fin-hypergrid/build/fin-hypergrid.js"></script>
<script src="openfin.github.io/fin-hypergrid/v1.3.0/build/fin-hypergrid.js"></script>
<script src="openfin.github.io/fin-hypergrid/v1.3.0/build/add-ons/*.js"></script>
```
where \* above stands for the names of the various 1.3 plug-ins.

Hypergrid apps requesting build files (with `<script>` tags) should be updated to reference the [new repo](https://github.com/fin-hypergrid)'s github pages (where all new releases will be posted):

```html
<script src="fin-hypergrid.github.io/core/build/2/fin-hypergrid.js"></script>
<script src="fin-hypergrid.github.io/core/build/1.3.0/fin-hypergrid.js"></script>
<script src="fin-hypergrid.github.io/plugin-*/build/1/yadayada.js"></script>
```
