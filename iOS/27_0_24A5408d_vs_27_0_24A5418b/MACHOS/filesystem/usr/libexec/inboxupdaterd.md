## inboxupdaterd

> `/usr/libexec/inboxupdaterd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x90c2` | `0x9040` | **`-0x82`** |
| `__DATA.__objc_const` | `0x9a28` | `0x99e8` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x89a0` | `0x8960` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0xa882` | `0xa8b7` | **`+0x35`** |
| `__TEXT.__text` | `0x8cd98` | `0x8cdcc` | **`+0x34`** |
| `__DATA_CONST.__const` | `0xf2d0` | `0xf2f0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4184` | `0x4164` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x2760` | `0x2750` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1f98` | `0x1f90` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x454` | `0x450` | **`-0x4`** |
| `__TEXT.__cstring` | `0x5510` | `0x550d` | **`-0x3`** |
| `__TEXT.__objc_methtype` | `0x1795` | `0x1792` | **`-0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-274.2.1.0.0
+274.2.2.0.0

-  Functions: 4272
+  Functions: 4271

-  CStrings:  3766
+  CStrings:  3764
CStrings:
+ "$"
+ "@52@0:8q16B24@28@36@44"
+ "Personalization shutdown timestamp set to %{public}@"
+ "initWithStatus:personalizationComplete:workflowID:orderID:assetExpiryTimestamp:"
- "%"
- "@60@0:8q16B24@28@36@44@52"
- "T@\"NSDate\",&,N,V_shutdownTimestamp"
- "T@\"NSDate\",R,C,N,V_shutdownTimestamp"
- "initWithStatus:personalizationComplete:workflowID:orderID:shutdownTimestamp:assetExpiryTimestamp:"
- "setShutdownTimestamp:"
```
