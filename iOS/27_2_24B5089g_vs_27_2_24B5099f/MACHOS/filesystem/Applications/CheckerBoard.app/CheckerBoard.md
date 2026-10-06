## CheckerBoard

> `/Applications/CheckerBoard.app/CheckerBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69378` | `0x6986c` | **`+0x4f4`** |
| `__TEXT.__objc_methname` | `0x11d91` | `0x11f81` | **`+0x1f0`** |
| `__TEXT.__objc_stubs` | `0xc940` | `0xcaa0` | **`+0x160`** |
| `__DATA.__objc_const` | `0x9048` | `0x90d8` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x5ec4` | `0x5f4c` | **`+0x88`** |
| `__TEXT.__oslogstring` | `0x6c85` | `0x6cf5` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x4348` | `0x43b0` | **`+0x68`** |
| `__TEXT.__eh_frame` | `0x26c` | `0x2cc` | **`+0x60`** |
| `__TEXT.__cstring` | `0x39fe` | `0x3a20` | **`+0x22`** |
| `__DATA_CONST.__cfstring` | `0x24e0` | `0x2500` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1820` | `0x1838` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x538` | `0x544` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xb40` | `0xb48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-294.40.3.0.0
+294.40.6.0.0

+  - /System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities

+  - /usr/lib/libAccessibility.dylib

-  Functions: 2656
-  Symbols:   1031
-  CStrings:  4411
+  Functions: 2669
+  Symbols:   1032
+  CStrings:  4435
Symbols:
+ _OBJC_CLASS_$_AXBackBoardServer
CStrings:
+ "DIAGNOSTICS_MODE_AX_LABEL"
+ "Power button press count window expired. Resetting count from %ld."
+ "Power button press count: %ld"
+ "T@\"CBWindow\",&,N,V_alertWindow"
+ "T@\"NSTimer\",&,N,V_powerButtonPressTimer"
+ "Tq,N,V_powerButtonPressCount"
+ "Triple press detected."
+ "_accessibilityInterposesAsSystemApplication"
+ "_alertWindow"
+ "_handleTriplePress"
+ "_powerButtonPressCount"
+ "_powerButtonPressCountTimerFired:"
+ "_powerButtonPressTimer"
+ "_resetPowerButtonPressCount"
+ "_startPowerButtonPressCountTimer"
+ "alertWindow"
+ "powerButtonPressCount"
+ "powerButtonPressTimer"
+ "server"
+ "setAlertWindow:"
+ "setPowerButtonPressCount:"
+ "setPowerButtonPressTimer:"
+ "tripleClickHomeButtonPress"
+ "\x92"
```
