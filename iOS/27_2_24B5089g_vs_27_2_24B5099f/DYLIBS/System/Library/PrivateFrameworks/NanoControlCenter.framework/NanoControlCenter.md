## NanoControlCenter

> `/System/Library/PrivateFrameworks/NanoControlCenter.framework/NanoControlCenter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2e70` | `0xe6708` | **`+0x3898`** |
| `__TEXT.__eh_frame` | `0x4874` | `0x4a1c` | **`+0x1a8`** |
| `__TEXT.__const` | `0xc1e8` | `0xc344` | **`+0x15c`** |
| `__TEXT.__oslogstring` | `0x2183` | `0x22c3` | **`+0x140`** |
| `__TEXT.__cstring` | `0x2bbe` | `0x2cbe` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x6198` | `0x6278` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x42e0` | `0x43b0` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x3650` | `0x3720` | **`+0xd0`** |
| `__DATA.__data` | `0x3778` | `0x3838` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x2b09` | `0x2bc9` | **`+0xc0`** |
| `__DATA.__bss` | `0x8948` | `0x89e8` | **`+0xa0`** |
| `__AUTH.__data` | `0x25c0` | `0x2638` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x2940` | `0x29b4` | **`+0x74`** |
| `__TEXT.__constg_swiftt` | `0x30e0` | `0x3140` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x8181` | `0x81b4` | **`+0x33`** |
| `__AUTH_CONST.__auth_got` | `0x1790` | `0x17c0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x5b0` | `0x5d0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc00` | `0xc18` | **`+0x18`** |
| `__AUTH.__objc_data` | `0x1528` | `0x1538` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xd20` | `0xd30` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xea8` | `0xeb8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x140` | `0x14c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x13c` | `0x144` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x4e8` | `0x4ec` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x2b4` | `0x2b8` | **`+0x4`** |

### Other Changes

```diff

-102.0.0.0.0
+104.0.0.0.0

-  Functions: 4730
-  Symbols:   2041
-  CStrings:  440
+  Functions: 4779
+  Symbols:   2053
+  CStrings:  454
Symbols:
+ _OBJC_CLASS_$_ISSymbol
+ _OBJC_CLASS_$_PDRRegistry
+ _PDRDevicePropertyKeyProductType
+ __DATA__TtC17NanoControlCenterP33_97C1173D7B10B69192C85A2D929B770A19ResourceBundleClass
+ __METACLASS_DATA__TtC17NanoControlCenterP33_97C1173D7B10B69192C85A2D929B770A19ResourceBundleClass
+ ___swift_closure_destructor.187Tm
+ ___swift_closure_destructor.414Tm
+ ___unnamed_61
+ _keypath_set.55Tm
+ _keypath_set.79Tm
+ _symbolic ScCySSSg_____G s5NeverO
+ _symbolic _____ 17NanoControlCenter16PhoneSymbolNamesV
+ _symbolic _____ 17NanoControlCenter19ResourceBundleClass33_97C1173D7B10B69192C85A2D929B770ALLC
+ _symbolic _____Sg 22UniformTypeIdentifiers15UTHardwareColorO
+ _symbolic _____Sg 22UniformTypeIdentifiers6UTTypeV
+ _symbolic ypSg
+ _type_layout_string 17NanoControlCenter16PhoneSymbolNamesV
- ___swift_closure_destructor.183Tm
- ___swift_closure_destructor.410Tm
- ___unnamed_60
- _keypath_set.51Tm
- _keypath_set.75Tm
CStrings:
+ "%s.%s Unable to get UTType for productType: %s"
+ "%s.%s companion product type nil or not a string. Returning nil product type."
+ "%s.%s no active device. Can't get phone symbols."
+ ".slash"
+ "Couldn't get UTType for V68"
+ "PingPhoneDynamicIsland"
+ "PingPhoneHomeButton"
+ "Unable to get a symbol name for %s with error: %@"
+ "iphone.duo.slash"
+ "iphone.gen3.radiowaves.left.and.right"
+ "iphone.gen3.slash"
+ "nil string for suffix: %s"
+ "usingCompanionDeviceType(workQueue:)"
+ "usingDeviceType(_:)"
```
