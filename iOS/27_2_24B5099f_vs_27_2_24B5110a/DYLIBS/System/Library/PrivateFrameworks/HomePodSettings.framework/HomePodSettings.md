## HomePodSettings

> `/System/Library/PrivateFrameworks/HomePodSettings.framework/HomePodSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71714` | `0x7199c` | **`+0x288`** |
| `__TEXT.__cstring` | `0x2bb1` | `0x2ce1` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0x1220` | `0x12e0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0xa60` | `0xa80` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x90` | `0xa8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1f7c` | `0x1f94` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xb20` | `0xb30` | **`+0x10`** |

### Other Changes

```diff

-346.10.23.0.0
+346.10.26.0.0

-  Functions: 4057
-  Symbols:   2276
-  CStrings:  404
+  Functions: 4059
+  Symbols:   2282
+  CStrings:  410
Symbols:
+ +[HPSHomeKitSettingHelper fixUpDisplayMediaVisualizerDefaultColor:]
+ +[HPSHomeKitSettingHelper fixUpDisplayMediaVisualizerVisualization:]
+ _HPSKeyPathMediaUI
+ _HPSKeyPathMediaUIDefaultColor
+ _HPSKeyPathPersonalSiriEnabled
+ _HPSKeyPathTouchEnabled
Functions:
~ ___46+[HPSHomeKitSettingHelper readSettingFixupMap]_block_invoke : 288 -> 336
+ +[HPSHomeKitSettingHelper fixUpDisplayMediaVisualizerVisualization:]
+ +[HPSHomeKitSettingHelper fixUpAppleIntelligenceReportDuration:]
CStrings:
+ "fixUpDisplayMediaVisualizerDefaultColor:"
+ "fixUpDisplayMediaVisualizerVisualization:"
+ "root.display.touchAndVisualization.interaction.touchEnabled"
+ "root.display.touchAndVisualization.mediaVisualizer.defaultColor"
+ "root.display.touchAndVisualization.mediaVisualizer.visualization"
+ "root.siri.personalSiriEnabled"
```
