## eligibilityd

> `/usr/libexec/eligibilityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43ab4` | `0x45bb0` | **`+0x20fc`** |
| `__TEXT.__cstring` | `0x709a` | `0x745a` | **`+0x3c0`** |
| `__DATA_CONST.__objc_arraydata` | `0xc690` | `0xc8f0` | **`+0x260`** |
| `__DATA_CONST.__objc_dictobj` | `0xb400` | `0xb5e0` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x32bf` | `0x344f` | **`+0x190`** |
| `__DATA_CONST.__cfstring` | `0x5620` | `0x57a0` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x2768` | `0x28e6` | **`+0x17e`** |
| `__DATA.__objc_const` | `0x3760` | `0x38b0` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x1f34` | `0x2084` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x2a40` | `0x2b80` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x29c8` | `0x2a70` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x1058` | `0x10f0` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0x1d8` | `0x24c` | **`+0x74`** |
| `__DATA.__objc_data` | `0xe20` | `0xe90` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0xc00` | `0xc60` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x78b` | `0x7e3` | **`+0x58`** |
| `__DATA.__data` | `0x1300` | `0x1350` | **`+0x50`** |
| `__DATA_CONST.__objc_arrayobj` | `0x3030` | `0x3060` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x1a50` | `0x1a70` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x57e` | `0x59e` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x2e8` | `0x300` | **`+0x18`** |
| `__DATA.__bss` | `0x2df0` | `0x2e00` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xd38` | `0xd48` | **`+0x10`** |
| `__TEXT.__const` | `0x2720` | `0x2730` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcc` | `0xd0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-446.2.3.0.0
+446.40.34.502.1

-  Functions: 1402
-  Symbols:   643
-  CStrings:  2020
+  Functions: 1440
+  Symbols:   645
+  CStrings:  2071
Symbols:
+ _$s3XPC0A10_TYPE_BOOLs13OpaquePointerVvg
+ _MobileGestalt_get_containsCellularRadioCapability
CStrings:
+ " (OVERRIDDEN)"
+ "$Harpalus Countries"
+ "%s: Failed to copy input overrides plist path"
+ "%s: Failed to copy input plist path"
+ "%s: Input plist %@ doesn't exist yet: %@"
+ "%s: No forced input overrides loaded from disk: %@"
+ "%s: Process %@ not entitled to send reset all inputs message"
+ "%s: Process %@ not entitled to send reset input message"
+ "%s: Process %@ not entitled to send setInput with forced Input message"
+ "-[EligibilityEngine setInput:to:status:forced:fromProcess:withError:]"
+ "-[EligibilityEngine setInput:to:status:forced:fromProcess:withError:]_block_invoke"
+ "-[InputManager _loadInputsAtPath:withError:]"
+ "-[InputManager _loadOverridesWithError:]"
+ "-[InputManager _onQueue_saveInputs:atPath:withError:]"
+ "-[InputManager _onQueue_saveOverridesWithError:]"
+ "-[InputManager resetInput:withError:]"
+ "-[InputManager setInput:forced:withError:]"
+ "/private/var/db/eligibilityd/eligibility_input_overrides.plist"
+ "20:45:39"
+ "446.40.34.502.1"
+ "@32@0:8*16^@24"
+ "B36@0:8@\"EligibilityInput\"16B24^@28"
+ "B36@0:8@16B24^@28"
+ "B40@0:8@16*24^@32"
+ "B60@0:8Q16@24Q32B40@44^@52"
+ "CellularCapableDevice input is wrong data type: %s"
+ "CellularCapableDeviceInput"
+ "CellularCapableDeviceOrWatchOnChinaSKU"
+ "ChinaIneligibleBilling"
+ "ChinaSKU"
+ "Harpalus Countries"
+ "InEURegionBillingFallbackToLocationWithShortGracePeriod"
+ "LocationInEUShort"
+ "OS_ELIGIBILITY_INPUT_CELLULAR_CAPABLE_DEVICE"
+ "OS_ELIGIBILITY_STATE_DUMP_INPUT_OVERRIDES"
+ "Sep  9 2026"
+ "T@\"NSDictionary\",C,N,V_inputOverrides"
+ "TB,N,R,VcellularCapableDevice"
+ "[CellularCapableDeviceInput cellularCapableDevice="
+ "__ObjC.CellularCapableDeviceInput"
+ "_inputOverrides"
+ "_loadInputsAtPath:withError:"
+ "_onQueue_saveInputs:atPath:withError:"
+ "_onQueue_saveOverridesWithError:"
+ "cellularCapableDevice"
+ "com.apple.private.eligibilityd.resetAllInputs"
+ "com.apple.private.eligibilityd.resetInput"
+ "copy_eligibility_domain_input_overrides_plist_path"
+ "forced"
+ "iOSInEURegionBillingFallbackToLocationWithShortGracePeriod"
+ "iPhoneIneligibleInEUFallbackToLocation"
+ "initWithBool:status:process:"
+ "inputOverrides"
+ "overridesDebugDictionary"
+ "resetAllInputsWithError:"
+ "resetInput:withError:"
+ "setInput:forced:withError:"
+ "setInput:to:status:forced:fromProcess:withError:"
+ "setInputOverrides:"
+ "stringByAppendingString:"
- "%s: Failed to copy input manager plist path"
- "-[EligibilityEngine setInput:to:status:fromProcess:withError:]"
- "-[EligibilityEngine setInput:to:status:fromProcess:withError:]_block_invoke"
- "-[InputManager setInput:withError:]"
- "21:03:58"
- "446.2.3"
- "Aug 12 2026"
- "B56@0:8Q16@24Q32@40^@48"
- "setInput:to:status:fromProcess:withError:"
```
