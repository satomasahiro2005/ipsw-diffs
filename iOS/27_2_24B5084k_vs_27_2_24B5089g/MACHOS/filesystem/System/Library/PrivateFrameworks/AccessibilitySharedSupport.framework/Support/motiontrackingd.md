## motiontrackingd

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Support/motiontrackingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bb9c` | `0x2be28` | **`+0x28c`** |
| `__DATA.__objc_const` | `0x4ce8` | `0x4da8` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x269e` | `0x2741` | **`+0xa3`** |
| `__TEXT.__objc_methname` | `0x9c7f` | `0x9cf3` | **`+0x74`** |
| `__DATA.__objc_ivar` | `0x3f8` | `0x410` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xa20` | `0xa30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x520` | `0x528` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa78` | `0xa70` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-591.4.1.0.0
+591.4.2.0.0

-  Functions: 1083
-  Symbols:   307
-  CStrings:  2280
+  Functions: 1084
+  Symbols:   308
+  CStrings:  2288
Symbols:
+ _dispatch_block_create_with_qos_class
CStrings:
+ "AXMTHIDBasedLookAtPointTracker: %.0f ms gap between HID gaze reports"
+ "AXMTHIDBasedLookAtPointTracker: eye-tracking pointer update delayed %.0f ms on the main queue"
+ "_lastDeliveryLagLogMach"
+ "_lastReceiptLogMach"
+ "_lastReceiptMach"
+ "_pendingDrainScheduled"
+ "_pendingPoint"
+ "_pendingPointLock"
+ "\xb1Q"
- "AQ"
```
