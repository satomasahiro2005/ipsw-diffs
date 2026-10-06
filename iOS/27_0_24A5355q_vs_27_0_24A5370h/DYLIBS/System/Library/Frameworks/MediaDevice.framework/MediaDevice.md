## MediaDevice

> `/System/Library/Frameworks/MediaDevice.framework/MediaDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b830` | `0x2e824` | **`+0x2ff4`** |
| `__TEXT.__oslogstring` | `0xdcb` | `0xeeb` | **`+0x120`** |
| `__TEXT.__const` | `0xe38` | `0xea8` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0xdf0` | `0xe60` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x63c` | `0x686` | **`+0x4a`** |
| `__AUTH_CONST.__auth_got` | `0x808` | `0x850` | **`+0x48`** |
| `__DATA.__data` | `0x4f8` | `0x538` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xa20` | `0xa48` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x40c` | `0x42c` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x359` | `0x379` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x6cc` | `0x6e4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x340` | `0x34c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x248` | `0x250` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x400` | `0x408` | **`+0x8`** |

### Other Changes

```diff

-360.58.1.0.0
+360.63.1.11.2

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 747
-  Symbols:   425
-  CStrings:  166
+  Functions: 763
+  Symbols:   435
+  CStrings:  171
Symbols:
+ _NSOSStatusErrorDomain
+ ___unnamed_3
+ _sandbox_extension_consume
+ _sandbox_extension_release
+ _swift_release_x9
+ _symbolic SDy__________G 10Foundation4UUIDV 11MediaDevice0c6OutputD0V
+ _symbolic _____Sg 7Network10NWEndpointO
+ _symbolic _____Sg 7Network10NWEndpointO4PortV
+ _symbolic _____Sg s5Int64V
+ _symbolic _____Sg_ABt 11MediaDevice0a6OutputB0V
+ _symbolic ___________t 10Foundation4UUIDV 11MediaDevice0c6OutputD0V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 7Network10NWEndpointO
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4UUIDV 11MediaDevice0e6OutputF0V
- ___unnamed_2
- _symbolic Say_____G 11MediaDevice0a6OutputB0V
- _symbolic _____y_____G s23_ContiguousArrayStorageC 11MediaDevice0d6OutputE0V
CStrings:
+ "Consumed BLE token for process lifecycle"
+ "Device %s not in known set, reconstructing from description"
+ "Failed to consume token, got errno %d"
+ "Failed to release token, got %d"
+ "Got unknown type of %hu, dropping token"
+ "Received new BLE token while holding an existing one, dropping old token"
- "Device not found with ID: %s"
```
