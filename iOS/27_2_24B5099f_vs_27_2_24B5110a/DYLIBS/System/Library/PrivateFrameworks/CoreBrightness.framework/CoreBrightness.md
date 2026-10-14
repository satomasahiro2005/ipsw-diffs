## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f5a8` | `0x17ffdc` | **`+0xa34`** |
| `__TEXT.__const` | `0x1b6c8` | `0x1b788` | **`+0xc0`** |
| `__DATA_CONST.__objc_arraydata` | `0xcf8` | `0xda8` | **`+0xb0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x550` | `0x5f0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xd3d5` | `0xd475` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x3270` | `0x32d8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0xdf50` | `0xdfb8` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x394c0` | `0x39520` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0xee80` | `0xeec0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5de8` | `0x5e28` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1b59d` | `0x1b5dd` | **`+0x40`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x420` | `0x450` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0xd98` | `0xdc8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x59c8` | `0x59e8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2a40` | `0x2a54` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0xace` | `0xade` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x18b4` | `0x18c0` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x10e8` | `0x10f4` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x3fc0` | `0x3fc8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7f8` | `0x800` | **`+0x8`** |

### Other Changes

```diff

-2300.40.47.0.4
+2300.42.3.0.0

-  Functions: 9138
-  Symbols:   10779
-  CStrings:  4916
+  Functions: 9152
+  Symbols:   10797
+  CStrings:  4925
Symbols:
+ -[CBHIDEventManager addUnfilteredClient:]
+ -[CBIndicatorBrightnessModule canJumpToTargetIndicatorBrightness]
+ -[CBIndicatorBrightnessModule isPipelineStalled]
+ -[CBIndicatorBrightnessModule isThermalPressureCritical]
+ -[CBIndicatorBrightnessModule jumpTo:forReason:withForce:]
+ -[CBIndicatorBrightnessModule recordSwapStall:]
+ -[CBIndicatorBrightnessModule setThermalPressure:]
+ -[CBIndicatorBrightnessModule startMonitoringForSwapStalls]
+ -[CBIndicatorBrightnessModule stopMonitoringForSwapStalls]
+ _OBJC_IVAR_$_CBHIDEventManager._unfilteredClients
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._consecutiveSwapStalledCount
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._swapStallObserverToken
+ ___35-[CBHIDEventManager addHIDService:]_block_invoke_3
+ ___38-[CBHIDEventManager removeHIDService:]_block_invoke_2
+ ___41-[CBHIDEventManager addUnfilteredClient:]_block_invoke
+ ___47-[CBIndicatorBrightnessModule recordSwapStall:]_block_invoke
+ ___52-[CBHIDEventManager hidEventCallbackWithEvent:from:]_block_invoke_2
+ ___59-[CBIndicatorBrightnessModule startMonitoringForSwapStalls]_block_invoke
+ ___block_descriptor_40_e8_32o_e20_v40?0{?=QIBBBffff}8ls32l8
+ ___block_descriptor_40_e8_32o_e36_v24?0"<CBHIDServiceProtocol>"8^B16ls32l8
+ ___block_descriptor_40_e8_32r_e20_v40?0{?=QIBBBffff}8lr32l8
- -[CBIndicatorBrightnessModule jumpTo:]
- GCC_except_table68
- ___block_descriptor_40_e8_32o_e19_v40?0{?=QIBBffff}8ls32l8
CStrings:
+ "Add unfiltered client %@"
+ "Backboardd restarted"
+ "DisplayIntegrated"
+ "Jumping to target indicator brightness: %f for reason: %s (forced=%d)"
+ "Overriding Boot-nits: %.2f -> %.2f nits"
+ "Ramp too long"
+ "Render pipeline stalled"
+ "Swap stall state changed: stalled=%d (%u consecutive)"
+ "Thermal pressure critical"
+ "override-boot-brightness-nits"
+ "v24@?0@\"<CBHIDServiceProtocol>\"8^B16"
+ "v40@?0{?=QIBBBffff}8"
- "Jumping to target indicator brightness: %f"
- "Thermal Pressure Critical! Snapping to target indicator brightness %f"
- "v40@?0{?=QIBBffff}8"
```
