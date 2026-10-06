## CameraMessagesApp

> `/System/Library/ExtensionKit/Extensions/CameraMessagesApp.appex/CameraMessagesApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6500` | `0x6844` | **`+0x344`** |
| `__TEXT.__oslogstring` | `0x82c` | `0x986` | **`+0x15a`** |
| `__TEXT.__objc_methname` | `0x280a` | `0x28d3` | **`+0xc9`** |
| `__TEXT.__objc_stubs` | `0x1e00` | `0x1ea0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0xba8` | `0xbd8` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x970` | `0x998` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x890` | `0x8a8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xb03` | `0xb13` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x188` | `0x190` | **`+0x8`** |
| `__TEXT.__const` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x54` | `0x58` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4174.0.0.0.0
+4177.22.3.0.0

-  Functions: 167
-  Symbols:   150
-  CStrings:  515
+  Functions: 170
+  Symbols:   152
+  CStrings:  528
Symbols:
+ _OBJC_CLASS_$_NSMutableSet
+ _objc_retain_x21
CStrings:
+ "@\"NSMutableSet\""
+ "Creating photo PHAsset with UUID %{public}@"
+ "Creating video PHAsset with UUID %{public}@"
+ "Handling review completion for asset UUID %{public}@ (action=%ld)"
+ "Ignoring repeat review completion for asset UUID %{public}@; already handled this capture."
+ "T@\"NSMutableSet\",&,N,S_setHandledCompletionAssetUUIDs:,V__handledCompletionAssetUUIDs"
+ "__handledCompletionAssetUUIDs"
+ "_handledCompletionAssetUUIDs"
+ "_setHandledCompletionAssetUUIDs:"
+ "addObject:"
+ "allKeys"
+ "didPerformCompletionAction: action=%ld selectedAssetUUIDs=%{public}@ substituteAssetUUIDs=%{public}@"
+ "set"
```
