# via-keymap
Load under configure tab in https://usevia.app/
Originally comes from the keyboard itself (I think?) it just loaded in the online app.
# via-keyboard
Import `*_v2` contents into https://usevia.app/design as a V2 definition.
Have to go to settings and enable the design tab first.
Originally comes from updated definitions in https://github.com/the-via/keyboards.git
# qmk-keymap
Put content of the folder under `qmk_firmware/keyboards/handwired/dactyl_manuform/5x6/keymaps`
before compiling firmware with `qmk compile --keyboard handwired/dactyl_manuform/5x6 --keymap via`
# keyboard-layout-editor
File exctly as imported from http://www.keyboard-layout-editor.com
Key position array from [via-keyboard](#via-keyboard) directory is based on part of this export of the layout designed in keyboard-layout-editor (but they are not the same).
