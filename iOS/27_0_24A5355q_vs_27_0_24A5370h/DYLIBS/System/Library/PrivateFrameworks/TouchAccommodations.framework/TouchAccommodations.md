## TouchAccommodations

> `/System/Library/PrivateFrameworks/TouchAccommodations.framework/TouchAccommodations`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2958c` | `0x29628` | **`+0x9c`** |
| `__TEXT.__oslogstring` | `0xcd1` | `0xcb6` | **`-0x1b`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0
Symbols:
+ _UISceneWillDeactivateNotification
- _UISceneDidEnterBackgroundNotification
CStrings:
+ "Setup assistant scene will deactivate. Interrupting."
+ "Setup completed while touch observer was not running."
- "Setup assistant was backgrounded. Interrupting."
- "Setup completed, but the touch observer had already been stopped (view disappeared early?)."
```
