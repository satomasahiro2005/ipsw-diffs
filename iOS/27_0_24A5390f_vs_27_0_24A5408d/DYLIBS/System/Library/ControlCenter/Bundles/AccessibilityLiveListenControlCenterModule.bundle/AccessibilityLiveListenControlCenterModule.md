## AccessibilityLiveListenControlCenterModule

> `/System/Library/ControlCenter/Bundles/AccessibilityLiveListenControlCenterModule.bundle/AccessibilityLiveListenControlCenterModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10f8` | `0x1474` | **`+0x37c`** |
| `__TEXT.__oslogstring` | `0x75` | `0x2cc` | **`+0x257`** |
| `__TEXT.__const` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x360` | `0x368` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Symbols:   58
-  CStrings:  11
+  Symbols:   60
+  CStrings:  15
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
+ _objc_release_x24
Functions:
~ sub_242d78aa0 -> sub_2426feaa0 : 164 -> 352
~ sub_242d78e90 -> sub_2426fef4c : 340 -> 748
~ sub_242d790e4 -> sub_2426ff338 : 200 -> 496
CStrings:
+ "rdar://148155597 AXLiveListenModuleViewController _updateAlphas expanded=%d platterAlpha=%f shortcutFrame={%f,%f,%f,%f} buttonFrame={%f,%f,%f,%f}"
+ "rdar://148155597 AXLiveListenModuleViewController buttonTapped expanded=%d isLiveListenEnabled=%d isLiveListenRouteSelected=%d buttonFrame={%f,%f,%f,%f} platterAlpha=%f"
+ "rdar://148155597 AXLiveListenModuleViewController buttonTapped ignored (long-press) touchDownAge=%f expanded=%d isLiveListenEnabled=%d"
+ "rdar://148155597 AXLiveListenModuleViewController shortcutDidChangeSize expanded=%d viewBounds={%f,%f} newContentSize={%f,%f} isLiveListenEnabled=%d"
```
