# PlasmaBoy planck layout

Default planck layout with some tweaks.

## MACROS

  **CLION1** - `Shift + Alt + 7`

  **CLION2** - `Ctrl + Alt + Home`

  **CLION3** - `Alt + Insert`

## Layers

### QWERTY

    ┌──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┐
    │ Tab  │   Q  │   W  │   E  │   R  │   T  │   Y  │   U  │   I  │   O  │   P  │ Bksp │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │ Ctrl │   A  │   S  │   D  │   F  │   G  │   H  │   J  │   K  │   L  │   ;  │   '  │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │ Shft │   Z  │   X  │   C  │   V  │   B  │   N  │   M  │   ,  │   .  │   /  │SFTENT│
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │ Esc  │  Del │ Alt  │ Gui  │Lower │    Space    │Raise │ Left │ Down │  Up  │ Right│
    └──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┘

### LOWER

    ┌──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┐
    │  ~   │  !   │  @   │  #   │  $   │  %   │  ^   │  &   │  *   │  (   │  )   │  Del │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │  Del │  F1  │  F2  │  F3  │  F4  │  F5  │  F6  │      │  +   │  {   │  }   │  |   │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │      │  F7  │  F8  │  F9  │  F10 │  F11 │  F12 │ISO # │ISO / │ Vol- │ Vol+ │      │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │      │      │      │      │      │      │      │      │ Home │ PgDn │ PgUp │  End │
    └──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┘

### RAISE

    ┌──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┐
    │   `  │   1  │   2  │   3  │   4  │   5  │   6  │   7  │   8  │   9  │   0  │ Bksp │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │  Del │  F1  │  F2  │  F3  │  F4  │  F5  │  F6  │  -   │  =   │  [   │  ]   │  \   │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │      │  F7  │  F8  │  F9  │  F10 │  F11 │  F12 │   #  │  \   │ Stop │ Play │      │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │CLION2│CLION3│      │CLION1│      │      │      │      │ Prev │ Vol- │ Vol+ │ Next │
    └──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┘

### ADJUST

    ┌──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┬──────┐
    │      │ Reset│ Debug│ RGB  │RGBMOD│ HUE+ │ HUE- │ SAT+ │ SAT- │BRGTH+│BRGTH-│  Del │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │      │      │Mu Mod│Au On │Au Off│AG Nrm│AG Swp│Qwerty│      │      │      │      │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │ CAPS │Voice-│Voice+│Mu On │Mu Off│Mi On │Mi Off│TermOn│TermOf│      │      │      │
    ├──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┼──────┤
    │      │      │      │      │      │ PrintScreen │      │      |      │      │ SLCK │
    └──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┴──────┘


## QMK Comment

  To generate ascii art of current keymap launch `qmk-commgen.py` in the same directory as `keymap.c`.
