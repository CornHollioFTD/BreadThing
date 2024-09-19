v0.9.1
- Font size of text in components and connections will scale with zoom level.
- Text in GBG/GBS menus will be align to Left, from Center.


v0.9
- Breadcrumbs are turned up to 11.
- Preview image will be saved with breadcrumb.
- Description can be added to breadcrumb when saving.
- New file format - breadcrumbs are saved as .png images.
- Breadcrumbs can be imported/exported (as images) via clipboard.
- Breadcrumbs in the old format will be automatically covered (no previews will be generated).
- Generated previews for breadcrumbs will look nice.
- Icons added to Edit panel for Save/Load and Export/Import of breadcrumbs.
- Stamp will be added to preview to emphasize that the image is a breadcrumb.
- Hotkeys changed to F5/F1 for Save/Load.
- Alt+C - generate breadcrumb for selected components.
- Removed Export/Import of components as text string.
- Name of the author will be saved and shown.
- Added overwrite protection of existing file in Save Breadcrumb dialog.
- Imported breadcrumbs will be saved into "\BreadCrumbs\ Imported".

- Component must be of an actually available type to be pasted.
- Documentation for Maths Eval will always be visible.
- Sliders for Width/Height restored - down below.
- Alt+A - deselect all.
- Added toggle to hide text on connections to components that are not selected.
- Ctrl+Alt - show only connections of selected components.
- Holding Ctrl+Shift whle creating a new component will connect it as input to selected.
- Hotkeys page updated.
- Ctrl+F11 will advance time by one frame or less.
- Experimental feature - nO cAPS lOCK.


v0.8
- Unconnected inputs of ME will be red.
- Holding Shift while placing a new component will connect it to selected component/input/output.
- Holding Ctrl while placing a new component will try to insert it into connection to selected component/input/output.
- Outputs of ME will be red if it uses Output(i) function without corresponding output.
- Added help page with explanation for all hotkeys.
- Added Stats page. It show number of components used per each type - for bragging rights.


v0.7.3
- Fixed duplication from partial drag-select.


v0.7.2
- Added import/export of components as text.
- Alt+C will export selected components as text into clipboard.
- Ctrl+V and Alt+V will first check clipboard for exchange string and will use it once, if found.

- Added BreadCrumbs - prefabs for bread.
- F1 to save selected components as breadcrumb.
- F2 to load breadcrumb.
- Breadcrumbs are located near Prefabs/Subobjects folders in: "\From The Depths\Player Profiles\YourProfile\BreadCrumbs\".
- F1/F2 shortcuts may or may not be temporary.


v0.7.1
- Air drag in UI will be rounded to 4 digits (from 2).
- Caps Lock (freeze) will work from editor, if bread is open in build mode.
- Ctrl+D will duplicate selected component(s), without overwriting copypaste buffer.
- If a single component was pasted it will be set active.
- Ctrl+M will toggle WASD between scrolling bread and external movement.


v0.7
- Bug was fixed.


v0.6
- Default printer changed to {0:G3}.
- Rearranged inventory and edit panel.
- More space given for ME expression.
- Added scrolling with (shift)WASD and arrows. WASD while holding middle mouse button to move camera or building cursor.
- Removed copy/paste explanation from editor.
- Pause can be enabled in build mode.
- Force view can be toggled outside of build mode.
- Tab will advance time by one frame or less. Ctrl+Tab - to advance frames faster.
- ME documentation moved deep down.

- Bread will reopen at the same place it was closed.
- Ctrl+0..9 to set bookmark on selected element.
- 0..9 to warp to bookmark.
- Tilde (aka BackQuote) to warp back to last position warped from.
- Ctrl+Tilde to warp to starting screen with defaul zoom.
- Screen position at close and bookmarks are persistent and will be copypasted with bread.

- Massive performance increase for editor (especially while editing large breads).
- Holding Alt will invert grid snapping.
- Missile laser emitters set to always by default.
- Edit panel is now slightly less jumpy.
- Text on components and connections will be hidden when zoomed out.

- Copypasting reworked.
- Ctrl+C - copy selected component(s) to buffer.
- Ctrl+V - paste component(s) from buffer, keeping connections between pasted components.
- Alt+V - paste to active component content from component in buffer, if there's only one and of the same type.
- Buffer will be keeped until game is closed.
- Title of editor window will reflect selected and buffered components.

- Multiple components can be selected and dragged.
- Shift+Click - add or remove component from selection.
- Shift+MouseDrag - drag-select components.
- Ctrl+Shift+MouseDrag - drag-select components and add to currently selected.
- Ctrl+A - select all components on screen.
- Ctrl+Shift+A - add all components on screen to currently selected.
- Ctrl+I - invert selection.


To install:
Extract into Mods folder.
It should look something like this:
c:\Users\YourUserName\Documents\From The Depths\Mods\BreadThing\BreadThing.dll

Link:
https://raw.githubusercontent.com/CornHollioFTD/BreadThing/main/BreadThing.rar

