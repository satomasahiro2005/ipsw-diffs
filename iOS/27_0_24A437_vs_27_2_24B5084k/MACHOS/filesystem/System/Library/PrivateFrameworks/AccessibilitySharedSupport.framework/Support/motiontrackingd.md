## motiontrackingd

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Support/motiontrackingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b948` | `0x2bb9c` | **`+0x254`** |
| `__TEXT.__objc_methname` | `0x9a7d` | `0x9c7f` | **`+0x202`** |
| `__TEXT.__objc_stubs` | `0x74a0` | `0x7580` | **`+0xe0`** |
| `__TEXT.__const` | `0x3fc` | `0x364` | **`-0x98`** |
| `__TEXT.__oslogstring` | `0x2633` | `0x269e` | **`+0x6b`** |
| `__DATA.__objc_const` | `0x4c88` | `0x4ce8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x307c` | `0x30dc` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x21e0` | `0x2218` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xa20` | `0xa38` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1ef9` | `0x1f04` | **`+0xb`** |
| `__DATA.__objc_ivar` | `0x3f0` | `0x3f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-587.0.3.0.0
+591.4.1.0.0

-  Functions: 1075
+  Functions: 1083

-  CStrings:  2267
+  CStrings:  2280
CStrings:
+ "AXMTCameraBasedLookAtPointTracker: orientation changed; re-seeding pose reference and centering the cursor"
+ "B24@0:8Q16"
+ "TB,N,V__altHeadTrackingSettleAwaitingInterfaceOrientation"
+ "TQ,N,V__altHeadTrackingSettleStartMachTime"
+ "__altHeadTrackingSettleAwaitingInterfaceOrientation"
+ "__altHeadTrackingSettleStartMachTime"
+ "_altHeadTrackingIsSettlingAtMachTime:"
+ "_altHeadTrackingSettleAwaitingInterfaceOrientation"
+ "_altHeadTrackingSettleStartMachTime"
+ "_beginAltHeadTrackingSettleHoldAwaitingInterfaceOrientation:"
+ "_reseedAltHeadTrackingForOrientationChange"
+ "set_altHeadTrackingSettleAwaitingInterfaceOrientation:"
+ "set_altHeadTrackingSettleStartMachTime:"
```
