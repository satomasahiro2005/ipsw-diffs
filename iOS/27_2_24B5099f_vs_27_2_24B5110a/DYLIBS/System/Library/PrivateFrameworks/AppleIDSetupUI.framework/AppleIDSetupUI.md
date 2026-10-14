## AppleIDSetupUI

> `/System/Library/PrivateFrameworks/AppleIDSetupUI.framework/AppleIDSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x189be8` | `0x18d8a8` | **`+0x3cc0`** |
| `__AUTH_CONST.__objc_const` | `0x11ac0` | `0x11e08` | **`+0x348`** |
| `__DATA.__data` | `0x5708` | `0x58e8` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0xa9d8` | `0xa838` | **`-0x1a0`** |
| `__TEXT.__swift5_capture` | `0x2ce8` | `0x2c54` | **`-0x94`** |
| `__AUTH.__data` | `0x3c10` | `0x3c90` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x14f0` | `0x1550` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x26cc` | `0x271c` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d60` | `0x1da8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x5778` | `0x57c0` | **`+0x48`** |
| `__TEXT.__const` | `0xd944` | `0xd924` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0xb98d` | `0xb9ad` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xef2c` | `0xef48` | **`+0x1c`** |
| `__TEXT.__constg_swiftt` | `0x5704` | `0x5718` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2520` | `0x2530` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x218` | `0x228` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3fc2` | `0x3fd2` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3620` | `0x362c` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x5158` | `0x5160` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x120` | `0x128` | **`+0x8`** |

### Other Changes

```diff

-129.125.6.1.0
+129.125.7.1.0

+  - /System/Library/PrivateFrameworks/SharingUI.framework/SharingUI

-  Functions: 7270
-  Symbols:   3197
+  Functions: 7302
+  Symbols:   3207
Symbols:
+ _CGRectGetWidth
+ _OBJC_CLASS_$_SFAdjustedImageView
+ __OBJC_$_INSTANCE_METHODS___AISSetupViewController(AppleIDSetupUI)
+ __OBJC_$_PROP_LIST_PRXCardContentProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PRXCardContentProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PRXCardContentProviding
+ __OBJC_$_PROTOCOL_REFS_PRXCardContentProviding
+ __OBJC_CLASS_PROTOCOLS_$___AISSetupViewController(AppleIDSetupUI)
+ __OBJC_LABEL_PROTOCOL_$_PRXCardContentProviding
+ __OBJC_PROTOCOL_$_PRXCardContentProviding
+ _symbolic _____Sg_ABt 10Foundation3URLV
+ _symbolic _____y_____Sg_G 7SwiftUI11EnvironmentV7ContentO 012AppleIDSetupB008ProxCardD0V
- __INSTANCE_METHODS___AISSetupViewController
- _type_layout_string 14AppleIDSetupUI15ProxCardContentV
CStrings:
+ "SetupStartViewController configure: deviceModel=%{public}s, peerDeviceClass=%{public}s, hasProxCardContent=%{bool,public}d, hasAdjustmentURL=%{bool,public}d"
- "SetupStartViewController configure: deviceModel=%{public}s, peerDeviceClass=%{public}s, hasProxCardContent=%{bool,public}d"
```
