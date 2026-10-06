## Books

> `/private/var/staged_system_apps/Books.app/Books`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ed9a4` | `0x806688` | **`+0x18ce4`** |
| `__TEXT.__swift5_typeref` | `0x57dda` | `0x5c818` | **`+0x4a3e`** |
| `__TEXT.__const` | `0x414c0` | `0x41f80` | **`+0xac0`** |
| `__DATA.__data` | `0x2ec70` | `0x2f410` | **`+0x7a0`** |
| `__DATA_CONST.__const` | `0x31100` | `0x31800` | **`+0x700`** |
| `__TEXT.__cstring` | `0x2ce7c` | `0x2d49c` | **`+0x620`** |
| `__DATA.__bss` | `0x3325c` | `0x3373c` | **`+0x4e0`** |
| `__TEXT.__unwind_info` | `0x1a5f0` | `0x1a8d0` | **`+0x2e0`** |
| `__TEXT.__auth_stubs` | `0x11e70` | `0x120d0` | **`+0x260`** |
| `__TEXT.__constg_swiftt` | `0x18050` | `0x18224` | **`+0x1d4`** |
| `__TEXT.__swift5_fieldmd` | `0x10888` | `0x10a54` | **`+0x1cc`** |
| `__TEXT.__swift5_capture` | `0x94a0` | `0x9658` | **`+0x1b8`** |
| `__TEXT.__swift5_reflstr` | `0x13600` | `0x13760` | **`+0x160`** |
| `__DATA_CONST.__auth_got` | `0x8f50` | `0x9080` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x172b4` | `0x173dc` | **`+0x128`** |
| `__DATA.__objc_data` | `0x1ab30` | `0x1aa70` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x729f0` | `0x72950` | **`-0xa0`** |
| `__DATA_CONST.__auth_ptr` | `0x6148` | `0x61d8` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x5f38` | `0x5fc8` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x211e0` | `0x21150` | **`-0x90`** |
| `__TEXT.__swift5_assocty` | `0x33e8` | `0x3478` | **`+0x90`** |
| `__DATA.__objc_const` | `0x57138` | `0x570c8` | **`-0x70`** |
| `__TEXT.__objc_methlist` | `0x2c638` | `0x2c5f0` | **`-0x48`** |
| `__TEXT.__objc_classname` | `0xa399` | `0xa369` | **`-0x30`** |
| `__TEXT.__swift5_proto` | `0x1aac` | `0x1ad0` | **`+0x24`** |
| `__TEXT.__swift5_types` | `0xfb0` | `0xfcc` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x15f18` | `0x15f08` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1730` | `0x1728` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6715.0.0.0.0
+6722.11.0.0.0

-  Functions: 40185
-  Symbols:   2126
-  CStrings:  26130
+  Functions: 40503
+  Symbols:   2125
+  CStrings:  26150
Symbols:
- _OBJC_METACLASS_$_UIGestureRecognizer
CStrings:
+ "AX value for reading position history undo/backward button"
+ "Accessibility hint for the reading position history button when it opens the undo/redo page skip menu"
+ "Accessibility label for the Redo Page Skip menu item, combining the action title with the destination page number."
+ "Accessibility label for the Undo Page Skip menu item, combining the action title with the destination page number."
+ "Accessibility value for the line guide button being in the off state in reader toolbar."
+ "Accessibility value for the line guide button being in the on state in reader toolbar."
+ "Bookmark button label in the reader toolbar"
+ "Bookmark button label in the reader toolbar when the page is bookmarked"
+ "Books.reader.chrome.contents"
+ "Books.reader.chrome.lineGuide"
+ "Books.reader.chrome.search"
+ "Books.reader.chrome.share"
+ "Books.reader.chrome.themesAndSettings"
+ "Books/BookReaderPresenter.swift"
+ "Double tap to show undo page skip menu"
+ "Line guide button label in reader toolbar"
+ "Line guide menu background dimming section header label"
+ "Line guide menu item title in reader toolbar for turning off line guide"
+ "Optional<HorizontalEdge>"
+ "Reader menu button title"
+ "Share button in reader toolbar"
+ "Undo/Redo navigation destination label"
+ "arrow.uturn.backward"
+ "arrow.uturn.forward"
+ "history-menu-button"
+ "iPad Page Label Offset"
+ "isMacCatalystApp"
+ "line-guide-menu-button"
+ "title for reading position history redo/forward button"
+ "title for reading position history undo/backward button"
- "Books.PressGestureRecognizer"
- "Unknown gesture recognizer state: %ld"
- "_TtC5Books22PressGestureRecognizer"
- "init(target:action:)"
- "isPressed => %{bool}d but state is %ld"
- "isPressed => %{bool}d; state: %ld"
- "numberOfTouches"
- "numberOfTouchesRequired"
- "touchesCancelled:withEvent:"
- "touchesMoved:withEvent:"
```
