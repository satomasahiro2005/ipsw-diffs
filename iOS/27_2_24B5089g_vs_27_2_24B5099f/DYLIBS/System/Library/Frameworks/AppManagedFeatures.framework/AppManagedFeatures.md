## AppManagedFeatures

> `/System/Library/Frameworks/AppManagedFeatures.framework/AppManagedFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7751c` | `0x7a228` | **`+0x2d0c`** |
| `__TEXT.__eh_frame` | `0x7ed8` | `0x8018` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0x34d8` | `0x35e8` | **`+0x110`** |
| `__TEXT.__const` | `0x74f0` | `0x75d0` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x2890` | `0x2918` | **`+0x88`** |
| `__DATA.__bss` | `0x7000` | `0x7080` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2753` | `0x27c3` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x106c` | `0x10dc` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xf7c` | `0xfec` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x175b` | `0x177b` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x940` | `0x958` | **`+0x18`** |
| `__DATA.__data` | `0xb30` | `0xb48` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x5b0` | `0x5c8` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x1218` | `0x1230` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x2a8` | `0x2c0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x50` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x3e0` | `0x3e4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x134` | `0x138` | **`+0x4`** |

### Other Changes

```diff

-58.40.9.0.0
+58.40.13.0.0

-  Functions: 2215
-  Symbols:   654
-  CStrings:  272
+  Functions: 2240
+  Symbols:   659
+  CStrings:  277
Symbols:
+ ___swift_memcpy272_8
+ ___swift_memcpy88_8
+ _associated conformance 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeysOSHAASQ
+ _associated conformance 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeysOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeysOs0H3KeyAAs28CustomDebugStringConvertible
+ _symbolic SS13versionString_t
+ _symbolic _____ 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeysO
+ _symbolic _____ So24NSOperatingSystemVersiona
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeysO
+ _type_layout_string So24NSOperatingSystemVersiona
- ___swift_memcpy256_8
- ___swift_memcpy72_8
- _associated conformance 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeys33_1DFD69DCE6326EDAB2196E2287FAEFFBLLOSHAASQ
- _associated conformance 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeys33_1DFD69DCE6326EDAB2196E2287FAEFFBLLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeys33_1DFD69DCE6326EDAB2196E2287FAEFFBLLOs0H3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeys33_1DFD69DCE6326EDAB2196E2287FAEFFBLLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeys33_1DFD69DCE6326EDAB2196E2287FAEFFBLLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 18AppManagedFeatures18CloudConfigurationV18UnderwriterDetailsV10CodingKeys33_1DFD69DCE6326EDAB2196E2287FAEFFBLLO
CStrings:
+ " has restricted access to some apps and functionality."
+ "' is not a valid version string."
+ ". Your device has been removed from their financing program."
+ "Minimum OS version '"
+ "apps"
+ "icons"
+ "minimum-os-version"
+ "minimumOSVersion"
- " for assistance."
- " has restricted access to some apps and functionality on your device. Contact "
- ". You can now use your device without restrictions."
```
