# jslib
my Javascript libraries.

Please
```shell
cd yourrepo/
git submodule add https://github.com/koteitan/jslib.git lib
cd lib
git submodule init
git submodule update
git remote set-url origin git@github.com:koteitan/jslib.git
cd ..
git add jslib
vim index.html
```

```html
<script type="text/javascript" src="./jslib/exarray.js"></script>
<script type="text/javascript" src="./jslib/exmath.js"></script>
<script type="text/javascript" src="./jslib/excanvas.js"></script>
<script type="text/javascript" src="./jslib/event.js"></script>
<script type="text/javascript" src="./jslib/geom.js"></script>
```
