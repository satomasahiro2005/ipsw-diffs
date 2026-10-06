## ScreenTimeUI

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/ScreenTimeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69aa4` | `0x69b54` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1940` | `0x1950` | **`+0x10`** |
| `__TEXT.__const` | `0x3014` | `0x3024` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1968` | `0x1970` | **`+0x8`** |

### Other Changes

```diff

-655.1.9.1.0
+655.1.12.0.0

-  Functions: 2030
-  Symbols:   1976
+  Functions: 2031
+  Symbols:   1977
Symbols:
+ -[UIImage(STImageAdditions) iconFromPrecomposedImage:platform:migratedToNewScreenTime:]
Functions:
~ -[STIconCache imageForBundleIdentifier:completionHandler:] : 1372 -> 1412
~ -[STIconCache _handleiTunesResponseForAppInfo:response:data:error:completionHandler:] : 844 -> 884
~ -[STIconCache imageForBundleIdentifier:] : 1184 -> 1216
~ -[STIconCache _handleiTunesResponseForAppInfo:response:data:error:] : 688 -> 724
~ -[UIImage(STImageAdditions) iconFromPrecomposedImage:platform:] : 552 -> 8
+ -[UIImage(STImageAdditions) iconFromPrecomposedImage:platform:migratedToNewScreenTime:]
```
