## ReplicatorCore

> `/System/Library/PrivateFrameworks/ReplicatorCore.framework/ReplicatorCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7810c` | `0x7b13c` | **`+0x3030`** |
| `__TEXT.__oslogstring` | `0x2306` | `0x2496` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x1e68` | `0x1fe0` | **`+0x178`** |
| `__DATA.__data` | `0x730` | `0x790` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x13a0` | `0x13f8` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x18e8` | `0x1938` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x1ae8` | `0x1b38` | **`+0x50`** |
| `__TEXT.__const` | `0xeb8` | `0xf08` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xc38` | `0xc80` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0xdf7` | `0xe3b` | **`+0x44`** |
| `__TEXT.__objc_methlist` | `0x630` | `0x660` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x68d` | `0x6bd` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x6ec` | `0x704` | **`+0x18`** |
| `__AUTH_CONST.__const` | `0xff8` | `0x1008` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x388` | `0x398` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x758` | `0x768` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0xd2c` | `0xd3c` | **`+0x10`** |

### Other Changes

```diff

-164.0.0.0.0
+168.0.0.0.0

-  Functions: 888
-  Symbols:   618
-  CStrings:  221
+  Functions: 902
+  Symbols:   622
+  CStrings:  228
Symbols:
+ _symbolic _____3key______5valuetSg 10Foundation4UUIDV 16ReplicatorEngine19PairingRelationshipV
+ _symbolic ______pSg 16ReplicatorEngine18PersonaIntroducingP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 18ReplicatorServices13PersonaDeviceV
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4UUIDV 16ReplicatorEngine19PairingRelationshipV
CStrings:
+ "Me device %{public}s is already paired for persona %{public}s"
+ "No relationship found for %{public}s and no me device is available"
+ "No relationship found for %{public}s; sending introductory message to me device %{public}s"
+ "Persona introducer unavailable"
+ "Persona monitor unavailable"
+ "Reintroducing %{public}s"
+ "Unpairing from %{public}s for persona %{public}s"
```
