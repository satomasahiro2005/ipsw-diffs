## Sidecar

> `/Applications/Sidecar.app/Sidecar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd7c` | `0x1c1b4` | **`+0x438`** |
| `__TEXT.__auth_stubs` | `0xd30` | `0xd90` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xa60` | `0xac0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x14c` | `0x184` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x6a0` | `0x6d0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x710` | `0x728` | **`+0x18`** |
| `__DATA.__data` | `0xc38` | `0xc48` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0xabf` | `0xacf` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5a8` | `0x5b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-400.34.0.0.0
+400.37.0.0.0

-  Functions: 797
-  Symbols:   346
-  CStrings:  509
+  Functions: 801
+  Symbols:   354
+  CStrings:  512
Symbols:
+ _$sSa034_makeUniqueAndReserveCapacityIfNotB0yyFyXl_Ts5
+ _$sSa16_createNewBuffer14bufferIsUnique15minimumCapacity13growForAppendySb_SiSbtFyXl_Ts5
+ _$sSa37_appendElementAssumeUniqueAndCapacity_03newB0ySi_xntFyXl_Ts5
+ _$sSh8IteratorV6_cocoaAByx_Gs10__CocoaSetVAACn_tcfC
+ _$ss10__CocoaSetV12makeIteratorAB0D0CyF
+ _$ss10__CocoaSetV8IteratorC4nextyXlSgyF
+ _OBJC_CLASS_$_UIApplication
+ _OBJC_CLASS_$_UIScene
+ _objc_retain_x27
- _objc_retain_x26
CStrings:
+ "EffectiveGeometry Orientation: %{public}s (extension mask %lx)"
+ "connectedScenes"
+ "effectiveGeometry"
+ "interfaceOrientation"
+ "sharedApplication"
- "Orientation: %{public}s (extension mask %lx)"
- "statusBarOrientation"
```
