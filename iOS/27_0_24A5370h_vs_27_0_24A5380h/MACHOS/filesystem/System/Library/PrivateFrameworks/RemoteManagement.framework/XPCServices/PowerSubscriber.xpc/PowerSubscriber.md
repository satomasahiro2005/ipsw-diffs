## PowerSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/PowerSubscriber.xpc/PowerSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f8` | `0xa40` | **`+0x348`** |
| `__TEXT.__oslogstring` | `0xc0` | `0x113` | **`+0x53`** |
| `__TEXT.__auth_stubs` | `0x160` | `0x1b0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xb8` | `0xe0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x68` | `0x40` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0x20` | `0x40` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x68` | `0x88` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4a` | `0x57` | **`+0xd`** |
| `__TEXT.__objc_methname` | `0x387` | `0x37f` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x133` | `0x12b` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-624.0.3.0.0
+624.0.8.0.0

-  Functions: 14
-  Symbols:   49
-  CStrings:  79
+  Functions: 16
+  Symbols:   55
+  CStrings:  81
Symbols:
+ _OBJC_CLASS_$_NSDictionary
+ _objc_release_x25
+ _objc_release_x26
+ _objc_retain_x20
+ _objc_retain_x21
+ _objc_retain_x8
CStrings:
+ "Battery health info was not returned for a pack"
+ "Battery pack entry was not a dictionary"
+ "Battery packs were not returned"
+ "BatteryPacks"
+ "rawBatteryHealthInfo"
- "Battery health info was not returned"
- "i16@0:8"
- "rawBatteryHealthServiceState"
```
