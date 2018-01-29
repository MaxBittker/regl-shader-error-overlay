# regl-shader-error-overlay

Somewhat silly monkey-patched dev tool to render shader errors logged by regl as formatted overlays.
Ideally, this would be a plugin or option in regl itself, but this works!

![screenshot](https://i.imgur.com/B8vpErz.png)
usage:
```
import {setupOverlay} from "./shaderErrorOverlay";
setupOverlay();

//... (regl code)
```

Regl logs shader errors here: https://github.com/regl-project/regl/blob/master/lib/util/check.js#L233
