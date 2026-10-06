## BatteryUsageUI

> `/System/Library/PreferenceBundles/BatteryUsageUI.bundle/BatteryUsageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b918` | `0x10bc88` | **`+0x370`** |
| `__TEXT.__objc_methname` | `0xa066` | `0xa176` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0x8680` | `0x8740` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x38a4` | `0x38ec` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x2a80` | `0x2ac0` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x9060` | `0x90a0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x32d5` | `0x3315` | **`+0x40`** |
| `__DATA.__objc_const` | `0x6688` | `0x66b8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x91a9` | `0x91d9` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3220` | `0x3238` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x3bc0` | `0x3bd0` | **`+0x10`** |
| `__TEXT.__const` | `0x8eb4` | `0x8ec4` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xd79` | `0xd89` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1df0` | `0x1df8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x44c` | `0x450` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  Functions: 4975
-  Symbols:   734
-  CStrings:  3869
+  Functions: 4982
+  Symbols:   735
+  CStrings:  3883
Symbols:
+ _OBJC_CLASS_$_NSRegularExpression
+ _objc_autorelease
- _OBJC_CLASS_$_PSBrightnessSettingsDetail
CStrings:
+ "BKEnableALS"
+ "Invalid build string buildA: %{public}@, buildB: %{public}@"
+ "Tq,V_numberOfBatteryPacks"
+ "Trusted Date of First Use is not yet available."
+ "^([0-9]+)([A-Z]+)([0-9]+)([a-z]*)$"
+ "_numberOfBatteryPacks"
+ "compareBuildVersion:withBuildVersion:"
+ "firstMatchInString:options:range:"
+ "numberOfBatteryPacks"
+ "numberOfRanges"
+ "q32@0:8@16@24"
+ "rangeAtIndex:"
+ "regularExpressionWithPattern:options:error:"
+ "setNumberOfBatteryPacks:"
+ "shouldUseSwiftBatteryHealthController"
- "Trusted Date of first use is not available."
```
