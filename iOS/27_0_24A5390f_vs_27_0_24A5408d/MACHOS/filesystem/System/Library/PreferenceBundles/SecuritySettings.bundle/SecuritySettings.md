## SecuritySettings

> `/System/Library/PreferenceBundles/SecuritySettings.bundle/SecuritySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85b0` | `0x92b4` | **`+0xd04`** |
| `__TEXT.__objc_stubs` | `0x1fe0` | `0x21c0` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x2504` | `0x2634` | **`+0x130`** |
| `__DATA.__objc_selrefs` | `0xbc8` | `0xc40` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x5d4` | `0x63f` | **`+0x6b`** |
| `__DATA_CONST.__const` | `0x310` | `0x360` | **`+0x50`** |
| `__TEXT.__cstring` | `0x705` | `0x747` | **`+0x42`** |
| `__DATA_CONST.__cfstring` | `0x7c0` | `0x800` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xa44` | `0xa74` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x250` | `0x270` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x298` | `0x2a8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4a0` | `0x490` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x258` | **`-0x8`** |
| `__TEXT.__const` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1171.0.3.0.0
+1171.0.12.0.0

+  - /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication

-  Functions: 166
+  Functions: 177

-  CStrings:  628
+  CStrings:  649
Symbols:
+ _OBJC_CLASS_$_LAContext
+ _objc_retain_x9
- _objc_retain_x25
- _objc_retain_x26
CStrings:
+ "Developer Mode DPO error: %@"
+ "Refusing to unpair specifier with missing hostKey or identifiers; userInfo=%@"
+ "allRecordIdentifiers"
+ "animateWithDuration:animations:"
+ "backBarButtonItem"
+ "compare:"
+ "evaluatePolicy:options:reply:"
+ "hostKey"
+ "hostKeyForRecord:"
+ "mergedUserInfoForRecords:hostKey:"
+ "mutableCopy"
+ "performDPOCheckWithCallback:onCancel:"
+ "q"
+ "setAlpha:"
+ "setDeveloperModeUIEnabled:"
+ "setEnabled:"
+ "setHidesBackButton:"
+ "setUserInteractionEnabled:"
+ "setWithArray:"
+ "specifierForPairedHost:hostKey:withUserInfo:"
+ "table"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
- "specifierForPairedHost:identifier:withUserInfo:"
```
