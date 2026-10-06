## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferAgent.framework/IMTransferAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16c1c` | `0x16d14` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x2a69` | `0x2a99` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1720` | `0x1748` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xd70` | `0xd80` | **`+0x10`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Symbols:   263
-  CStrings:  352
+  Symbols:   264
+  CStrings:  353
Symbols:
+ _IMStringFromCommSafetyEnablementGroup
Functions:
~ sub_286b5e3f4 -> sub_28c5423f4 : 2476 -> 2644
~ sub_286b5eea4 -> sub_28c542f4c : 1184 -> 1192
~ sub_286b5f344 -> sub_28c5433f4 : 532 -> 536
~ sub_286b61970 -> sub_28c545a24 : 1056 -> 1064
~ sub_286b689c0 -> sub_28c54ca7c : 5536 -> 5596
CStrings:
+ "About to construct the nickname with contentSafetyEnablementGroup: %@"
+ "Avatar image safety check was skipped, comm safety check group setting: %@. Creating IMNicknameAvatarImage."
+ "Download %@ file size %llu -> request priority %ld"
+ "Wallpaper safety check was skipped, comm safety check group setting: %@. Creating IMWallpaper."
- "About to construct the nickname with contentSafetyEnablementGroup: %ld"
- "Avatar image safety check was skipped, comm safety check group setting: %ld. Creating IMNicknameAvatarImage."
- "Wallpaper safety check was skipped, comm safety check group setting: %ld. Creating IMWallpaper."
```
