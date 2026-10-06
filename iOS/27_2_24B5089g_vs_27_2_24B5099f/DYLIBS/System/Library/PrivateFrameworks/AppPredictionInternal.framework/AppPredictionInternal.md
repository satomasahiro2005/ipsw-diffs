## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48f7c8` | `0x48fc34` | **`+0x46c`** |
| `__TEXT.__cstring` | `0x59712` | `0x59872` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x3bcc9` | `0x3bd49` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x3b2c0` | `0x3b300` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bfe0` | `0x1c020` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xc0d0` | `0xc0f8` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x3450` | `0x3468` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x38f2c` | `0x38f3c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xe668` | `0xe678` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x21e0` | `0x21e8` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x83be8` | `0x83bf0` | **`+0x8`** |

### Other Changes

```diff

-675.0.2.0.0
+677.0.2.0.0

+  - /System/Library/PrivateFrameworks/IDS.framework/IDS

-  Functions: 25714
-  Symbols:   36763
-  CStrings:  12407
+  Functions: 25718
+  Symbols:   36769
+  CStrings:  12414
Symbols:
+ -[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ _IDSCopyLocalDeviceUniqueID
+ ___105-[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___105-[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e49_v24?0"ATXWidgetSmartStackResponse"8"NSError"16ls32l8
+ _sharedInstance._pasOnceToken1
CStrings:
+ "%s: Generated %lu smart stacks for paired tvOS device from source %@"
+ "%s: Rejecting smart stack request for non-tvOS client: %@"
+ "-[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]"
+ "-[ATXDefaultWidgetSuggesterServer fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke_2"
+ "ATXDefaultWidgetSuggesterServer"
+ "Only tvOS client requests are supported"
+ "v24@?0@\"ATXWidgetSmartStackResponse\"8@\"NSError\"16"
```
