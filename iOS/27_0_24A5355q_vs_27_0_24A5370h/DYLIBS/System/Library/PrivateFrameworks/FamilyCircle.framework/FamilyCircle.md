## FamilyCircle

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4970` | `0xc4a78` | **`+0x108`** |
| `__AUTH_CONST.__objc_const` | `0xc8d0` | `0xc900` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x410c` | `0x413c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1900` | `0x1928` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2840` | `0x2850` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x55b8` | `0x55a8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x980` | `0x988` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3b88` | `0x3b90` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x470` | `0x474` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-279.3.1.2.0
+282.0.0.0.0

-  Functions: 5442
-  Symbols:   4038
-  CStrings:  1309
+  Functions: 5446
+  Symbols:   4045
+  CStrings:  1310
Symbols:
+ +[FARequestConfigurator addLanguageHeadersToHeaderDictionary:]
+ -[FAInviteContext flowType]
+ -[FAInviteContext setFlowType:]
+ _OBJC_IVAR_$_FAInviteContext._flowType
+ __OBJC_$_CLASS_METHODS_FARequestConfigurator
+ ___50-[FARequestConfigurator addLocalHeadersToRequest:]_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24ls32l8
CStrings:
+ "settings-navigation://com.apple.Settings.Family/members/"
+ "settings-navigation://com.apple.Settings.Family/subscriptions"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
- "settings-navigation://com.apple.Settings.Family?familyPath=/members/"
- "settings-navigation://com.apple.Settings.Family?familyPath=/subscriptions"
```
