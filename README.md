# NieR Style Cursors
Uses Blender 2.82+, xcursorgen, imagemagick, and of course common bash tools like `bc` and probably more.
*Possibly* runs on blender versions as old as 2.80
## Preview Images
renditions updated when you run ./build.sh before committing.
idk how thisll look online maybe it should be one big image don't feel like writing the code to make an imagemagick grid right now.

---
![Cursor_UL](./previews/Cursor_UL.png)
![Selector](./previews/Selector.png)
![Loading_Circle](./previews/Loading_Circle.gif)

## "Cool how do I yes?"

1. have the tools installed
2. download the thing
3. run the `build.sh` file
4. a folder will appear called 'icons' that has the theme inside. up to your distro gods what to do with the generated theme.

## Cursors included in theme so far
### Adwaita is a fallback for those not included. This can be changed in the "index.theme" file present in the built theme.
- arrow -> Cursor_UL
- default -> Cursor_UL
- draft_large -> Cursor_UR
- draft_small -> Cursor_UR
- left_ptr -> Cursor_UL
- left_ptr_watch -> Cursor_Loading
- progress -> Cursor_Loading
- right_ptr -> Cursor_UR
- sb_down_arrow -> Cursor_D
- sb_left_arrow -> Cursor_L
- sb_right_arrow -> Cursor_R
- sb_up_arrow -> Cursor
- text -> Selector
- top_left_arrow -> Cursor_UL
- vertical-text -> Selector_H
- wait -> Loading_Circle
- watch -> Loading_Circle
- xterm -> Selector
- - plus the appropriate gibberish-string ones
