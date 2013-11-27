FontAwesome-v3-Icons-in-v4
==========================

FontAwesome changed it's naming convention in version 4. Some of the icons are now missing. If you want to use them anyway you have to integrate them again into it.
This little LESS file will bring back the old names to FontAwesome. And this is how it works:

1. Move the v3icons.less into the FontAwesome less folder. Open font-awesome.less and add the following line:

	@import "v3icons";

2. Compile your LESS files into CSS.

3. That's it!
