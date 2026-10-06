## GenerativeModelsFoundation

> `/System/Library/PrivateFrameworks/GenerativeModelsFoundation.framework/GenerativeModelsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x586f0` | `0x5f114` | **`+0x6a24`** |
| `__DATA.__bss` | `0x10600` | `0x12780` | **`+0x2180`** |
| `__TEXT.__const` | `0xae48` | `0xbeb8` | **`+0x1070`** |
| `__AUTH_CONST.__const` | `0x5ce0` | `0x6568` | **`+0x888`** |
| `__TEXT.__eh_frame` | `0x2f30` | `0x3258` | **`+0x328`** |
| `__TEXT.__unwind_info` | `0x2740` | `0x2a48` | **`+0x308`** |
| `__DATA.__data` | `0x1b00` | `0x1df0` | **`+0x2f0`** |
| `__TEXT.__swift5_typeref` | `0x263c` | `0x2924` | **`+0x2e8`** |
| `__TEXT.__constg_swiftt` | `0x2114` | `0x2348` | **`+0x234`** |
| `__TEXT.__swift5_fieldmd` | `0x2198` | `0x23c8` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0xd73` | `0xec3` | **`+0x150`** |
| `__TEXT.__swift5_proto` | `0x9ac` | `0xab8` | **`+0x10c`** |
| `__TEXT.__cstring` | `0x12b7` | `0x13a7` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x1433` | `0x14f3` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0xdd8` | `0xe50` | **`+0x78`** |
| `__TEXT.__swift5_types` | `0x310` | `0x354` | **`+0x44`** |
| `__TEXT.__swift5_assocty` | `0x1f8` | `0x228` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x320` | `0x340` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1010` | `0x1018` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x23c` | `0x244` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x124` | `0x12c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x90` | `0x94` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x74` | **`+0x4`** |

### Other Changes

```diff

-291.6.0.5.102
+297.6.0.5.0

+  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

-  Functions: 4060
-  Symbols:   236
-  CStrings:  166
+  Functions: 4381
+  Symbols:   243
+  CStrings:  178
Symbols:
+ _MKBDeviceUnlockedSinceBoot
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _notify_cancel
+ _notify_register_dispatch
+ _swift_bridgeObjectRetain_n
+ _swift_continuation_await
+ _swift_continuation_init
CStrings:
+ "FirstUnlockGate: device already unlocked, invoking handler"
+ "FirstUnlockGate: device locked, registering handler to run on first unlock"
+ "FirstUnlockGate: notify_register_dispatch failed (%{public}u); firing handlers inline"
+ "FirstUnlockGate: received first_unlock notification, draining all the waiting handlers"
+ "awaitFirstUnlock()"
+ "com.apple.GenerativeModels.firstUnlockGate"
+ "com.apple.mobile.keybagd.first_unlock"
+ "contentSafetyMode"
+ "inputPolicies"
+ "outputPolicies"
+ "outputProcessingPolicies"
+ "promptInjectionUntrustedContent"
```
