## UIIntelligenceIntents

> `/System/Library/PrivateFrameworks/UIIntelligenceIntents.framework/UIIntelligenceIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cf4c` | `0x2cf48` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-9127.1.5.0.0
+9127.1.7.0.0
Functions:
~ sub_2b8f3b0a0 -> sub_2b929b0a0 : 2444 -> 2440
CStrings:
+ "Present Writing Tools result "
+ "The text to be inserted into the app’s active text field."
+ "Window number (stringified) of the window that hosts the target text field. When provided on macOS, the bridge activates that window (`makeKeyAndOrderFront:`) before starting Writing Tools so AppKit’s default `keyWindow.firstResponder` coordinator walk lands on the intended field — necessary when a transient popover has stolen key focus."
- "Present writing tools result "
- "The text to be inserted into the app's active text field."
- "Window number (stringified) of the window that hosts the target text field. When provided on macOS, the bridge activates that window (`makeKeyAndOrderFront:`) before starting Writing Tools so AppKit's default `keyWindow.firstResponder` coordinator walk lands on the intended field — necessary when a transient popover has stolen key focus."
```
