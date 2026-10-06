## StatusKit

> `/System/Library/PrivateFrameworks/StatusKit.framework/StatusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x456c0` | `0x458f4` | **`+0x234`** |
| `__TEXT.__oslogstring` | `0x5469` | `0x5529` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x2128` | `0x2168` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0xe68` | `0xe90` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x3850` | `0x3868` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xf28` | `0xf40` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x234` | `0x244` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x7f0` | `0x800` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1558` | `0x1560` | **`+0x8`** |

### Other Changes

```diff

-154.100.1.0.0
+154.200.11.0.0

-  Functions: 1704
-  Symbols:   3454
-  CStrings:  538
+  Functions: 1709
+  Symbols:   3462
+  CStrings:  541
Symbols:
+ -[SKPresence presenceDaemonConnectionDidInterrupt:]
+ -[SKStatusPublishingService publishingDaemonConnectionDidInterrupt:]
+ -[SKStatusSubscriptionService subscriptionDaemonConnectionDidInterrupt:]
+ GCC_except_table145
+ GCC_except_table151
+ GCC_except_table156
+ GCC_except_table159
+ GCC_except_table57
+ GCC_except_table62
+ _$sSo10SecTaskRefa9StatusKitE07currentB0ABSgvgZTf4d_n
+ _$sSo10SecTaskRefa9StatusKitE21codeSigningIdentifierSSSgvg
+ _$ss9UnmanagedVMn
+ ___swift__destructor
+ ___swift_closure_destructor.33Tm
+ _symbolic _____y_____GSg s9UnmanagedV So10CFErrorRefa
- GCC_except_table144
- GCC_except_table149
- GCC_except_table155
- GCC_except_table158
- GCC_except_table55
- _$s9StatusKit21SKPresenceXPCListenerC35currentProcessCodeSigningIdentifier33_B8CF45FBD8FB9DEE23DFD917EA1AC8D3LLSSSgvgZTf4d_n
- ___swift_closure_destructor.31Tm
CStrings:
+ "Asked to reconnect yet we already have a connection (likely interrupted)"
+ "_delegateLock presenceDaemonConnectionDidInterrupt locked"
+ "_delegateLock presenceDaemonConnectionDidInterrupt unlocked"
+ "_delegateLock presenceDaemonConnectionDidInterrupt waiting"
- "Tried to reconnect, but we already have a connection"
```
