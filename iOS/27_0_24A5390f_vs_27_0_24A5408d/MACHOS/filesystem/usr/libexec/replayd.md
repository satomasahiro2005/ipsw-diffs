## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb7fa0` | `0xb8c4c` | **`+0xcac`** |
| `__TEXT.__oslogstring` | `0x15f42` | `0x1626c` | **`+0x32a`** |
| `__TEXT.__cstring` | `0x1787a` | `0x17a78` | **`+0x1fe`** |
| `__TEXT.__objc_methname` | `0x15c42` | `0x15d0c` | **`+0xca`** |
| `__DATA.__objc_const` | `0x11278` | `0x11310` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0xf000` | `0xf060` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x7378` | `0x73c8` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x43c3` | `0x4403` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x22c0` | `0x22f8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x2a70` | `0x2a98` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x4670` | `0x4690` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x5ca0` | `0x5cc0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xfa4` | `0xfbc` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xd6c` | `0xd7c` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-740.57.1.0.0
+740.63.1.1.0

-  Functions: 3622
+  Functions: 3634

-  CStrings:  7310
+  CStrings:  7335
CStrings:
+ " [ERROR] %{public}s:%d Picker cancelled but pickerConfig is nil - cannot notify app"
+ " [ERROR] %{public}s:%d pickerDidEnd rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d pickerDidUpdate rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d startCapture rejected: filterID=%@ was not vended by the picker for app=%@"
+ " [ERROR] %{public}s:%d startCapture rejected: full-display filterID=%@ consumed or expired for app=%@"
+ " [ERROR] %{public}s:%d validateFilterForStart: missing filterID"
+ " [INFO] %{public}s:%d Control Center host disconnected, clearing presented ScreenCaptureKit picker info"
+ " [INFO] %{public}s:%d Picker cancelled - notifying app"
+ " [INFO] %{public}s:%d Picker state cleared"
+ " [INFO] %{public}s:%d pickerDidDismiss isCancelled=%d stream=%@"
+ " [INFO] %{public}s:%d timerDidUpdate: stale timer tick after recording output removed; skipping"
+ "-[RPClient validateFilterForStart:]"
+ "-[RPConnectionManager pickerDidDismiss:forStream:isCancelled:]_block_invoke"
+ "-[RPConnectionManager pickerDidEnd:withFilter:forStream:]"
+ "-[RPConnectionManager pickerDidUpdate:withFilter:preservedFilter:forStream:completionHandler:]"
+ "-[RPRecordingManager pickerDidDismiss:forStream:isCancelled:]"
+ "The content filter cannot be used to start a stream. A full-display filter obtained from the system picker is single-use and must be re-presented via the picker for each new stream."
+ "Vv36@0:8@\"NSDictionary\"16@\"NSDictionary\"24B32"
+ "Vv36@0:8@16@24B32"
+ "_privacyAlertLock"
+ "_vendedFilterID"
+ "_vendedFilterLock"
+ "_vendedFilterVendTime"
+ "createPrivacyAlertIfNeeded"
+ "pickerDidDismiss:forStream:isCancelled:"
+ "presentPrivacyAlertWithOptions:completionHandler:"
+ "shouldPresentPrivacyAlertWithOptions:"
+ "validateFilterForStart:"
- " [INFO] %{public}s:%d skip notify control center manager for stream with only recording output"
- "T@\"SCPrivacyAlert\",R,N,V_privacyAlert"
- "privacyAlert"
```
