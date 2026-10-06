## RemotePlayerService

> `/System/Library/Frameworks/MediaPlayer.framework/XPCServices/RemotePlayerService.xpc/RemotePlayerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x228c` | `0x23e4` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0x2f7` | `0x3b9` | **`+0xc2`** |
| `__TEXT.__objc_stubs` | `0x620` | `0x680` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xa60` | `0xa99` | **`+0x39`** |
| `__DATA.__objc_selrefs` | `0x308` | `0x320` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x78` | `0x90` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4026.110.2.0.0
+4026.200.12.0.0

-  Symbols:   81
-  CStrings:  213
+  Symbols:   84
+  CStrings:  218
Symbols:
+ _AVSystemController_PIDToInheritApplicationStateFrom
+ _OBJC_CLASS_$_AVSystemController
+ _OBJC_CLASS_$_NSNumber
Functions:
~ sub_100001508 : 4 -> 348
~ sub_10000150c -> sub_100001664 : 204 -> 84
~ sub_1000015d8 -> sub_1000016b8 : 360 -> 204
~ sub_100001740 -> sub_100001784 : 212 -> 360
~ sub_100001814 -> sub_1000018ec : 84 -> 212
~ sub_1000027f0 -> sub_100002948 : 80 -> 68
~ sub_100002840 -> sub_10000298c : 340 -> 80
~ sub_100002994 -> sub_1000029dc : 116 -> 340
~ sub_100002a08 -> sub_100002b30 : 68 -> 116
CStrings:
+ "MPRemotePlayerService: %p: Failed to set AVSystemController_PIDToInheritApplicationStateFrom to %ld"
+ "MPRemotePlayerService: %p: Setting AVSystemController_PIDToInheritApplicationStateFrom to %ld"
+ "numberWithInt:"
+ "setAttribute:forKey:error:"
+ "sharedInstance"
```
