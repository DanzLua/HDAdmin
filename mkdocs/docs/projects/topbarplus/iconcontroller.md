# Methods

--------------------
### createIcon
```lua
IconController:createIcon(name, imageId, order)
```
Creates, stores and returns an icon, where ``name`` is a unique string identifying the icon, ``imageId`` an int representing the icons image, and ``order``, a number defining how the icon should be positioned in relation to neighbouring icons, greater values being shifted rightward.

--------------------
### createFakeChat
```lua
IconController:createFakeChat(theme)
```
Disables the default core chat icon, and creates and returns a new icon imitating it.

--------------------
### getIcon
```lua
IconController:getIcon(name)
```
Returns an icon of the corresponding name.

--------------------
### getAllIcons
```lua
IconController:getAllIcons()
```
Returns an array containing every icon.

--------------------
### removeIcon
```lua
IconController:removeIcon(name)
```
Destroys and removes references of the corresponding icon.
