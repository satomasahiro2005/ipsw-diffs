## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x10d` | `0x251` | **`+0x144`** |
| `__TEXT.__text` | `0x24fd0` | `0x25048` | **`+0x78`** |
| `__DATA.__objc_const` | `0x3878` | `0x3898` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x6e56` | `0x6e76` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4b60` | `0x4b40` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x13c0` | `0x13d0` | **`+0x10`** |
| `__TEXT.__const` | `0xc80` | `0xc90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x9f0` | `0x9f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9e0` | `0x9d8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1fc` | `0x200` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2475.0.0.0.0
+2478.0.0.0.0

-  Symbols:   413
-  CStrings:  1491
+  Symbols:   414
+  CStrings:  1496
Symbols:
+ _VOTLogLifeCycle
Functions:
~ sub_8a1c : 332 -> 448
~ sub_8d5c -> sub_8dd0 : 272 -> 8
~ sub_8e6c -> sub_8dd8 : 364 -> 444
~ sub_a2e8 -> sub_a2a4 : 652 -> 720
~ sub_12f20 : 336 -> 456
CStrings:
+ "Adding screen curtain view controller for scene (displayID=%@), current commanded state=%d"
+ "Removing screen curtain view controller for scene, commanded state (_screenCurtainEnabled=%d) unchanged"
+ "VOTUIScreenCurtainViewController setEnabled: %d -> %d (animate=%d)"
+ "_handleScreenCurtainEnabled:%d (%lu curtain view controllers)"
+ "_screenCurtainEnabled"
```
