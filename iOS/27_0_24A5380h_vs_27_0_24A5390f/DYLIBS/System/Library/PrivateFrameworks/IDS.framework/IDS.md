## IDS

> `/System/Library/PrivateFrameworks/IDS.framework/IDS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a8bdc` | `0x1b56ac` | **`+0xcad0`** |
| `__AUTH_CONST.__objc_const` | `0x3d2c0` | `0x3da18` | **`+0x758`** |
| `__AUTH.__data` | `0x1068` | `0x1480` | **`+0x418`** |
| `__TEXT.__eh_frame` | `0x2db8` | `0x3180` | **`+0x3c8`** |
| `__TEXT.__unwind_info` | `0x6cd8` | `0x6f88` | **`+0x2b0`** |
| `__TEXT.__const` | `0x5d98` | `0x5fe8` | **`+0x250`** |
| `__TEXT.__oslogstring` | `0x1b514` | `0x1b6f4` | **`+0x1e0`** |
| `__TEXT.__swift5_fieldmd` | `0x161c` | `0x17d4` | **`+0x1b8`** |
| `__DATA.__bss` | `0x9770` | `0x9910` | **`+0x1a0`** |
| `__TEXT.__swift5_typeref` | `0x1ac4` | `0x1c5c` | **`+0x198`** |
| `__TEXT.__constg_swiftt` | `0x14e4` | `0x1658` | **`+0x174`** |
| `__AUTH.__objc_data` | `0x2058` | `0x2168` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0xdb2c` | `0xdc3c` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0xd35` | `0xe3c` | **`+0x107`** |
| `__AUTH_CONST.__auth_got` | `0x1dd0` | `0x1ec0` | **`+0xf0`** |
| `__DATA.__data` | `0x2830` | `0x2910` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x11a76` | `0x11b36` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x54a8` | `0x5540` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x6cb0` | `0x6d40` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x1a98` | `0x1ac8` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x254` | `0x280` | **`+0x2c`** |
| `__TEXT.__swift5_capture` | `0x174` | `0x19c` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x53f0` | `0x5410` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x230` | `0x250` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x5e0` | `0x5f8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x11c` | `0x134` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x3b4` | `0x3bc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xdf0` | `0xdf4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x110` | `0x114` | **`+0x4`** |

### Other Changes

```diff

-1998.100.2.0.0
+2000.100.2.2.1

-  Functions: 9232
-  Symbols:   1865
-  CStrings:  3868
+  Functions: 9466
+  Symbols:   1874
+  CStrings:  3878
Symbols:
+ _CCDeriveKey
+ _CCKDFParametersCreateHkdf
+ _CCKDFParametersDestroy
+ _OBJC_CLASS_$__IDSCryptorPrimitives
+ _OBJC_CLASS_$__IDSRealTimeGroupSessionCryptorBackend
+ _OBJC_METACLASS_$__IDSCryptorPrimitives
+ _OBJC_METACLASS_$__IDSRealTimeGroupSessionCryptorBackend
+ _swift_dynamicCastObjCClass
+ _swift_release_x10
CStrings:
+ "%s: no cryptor backend available; returning an empty stream (session likely invalidated)"
+ "-[_IDSGroupSession requestMediaKeyMaterialForParticipants:]"
+ "-[_IDSGroupSession session:didReceiveMediaKeyMaterial:]"
+ "-[_IDSGroupSession session:shouldInvalidateMediaKeyMaterialByKeyIndexes:]"
+ "Can't deliver MKM to cryptor backend for session %@"
+ "Group session %@ didReceiveMediaKeyMaterial count=%lu"
+ "Ignoring group session didReceiveMediaKeyMaterial {self:%p, _uniqueID:%@, identifier:%@}"
+ "Ignoring group session shouldInvalidateMediaKeyMaterialByKeyIndexes, session doesn't match %@ vs. %@"
+ "RealTimeGroupSessionCryptor"
+ "cryptors(forTopic:keyMaterialSource:strategy:_:)"
+ "shouldInvalidateMediaKeyMaterialByKeyIndexes for session %@, expiredKeyIndexes: %@"
- "RealTimeGroupSessionCryptor implementation has not yet landed — see rdar://179268110."
```
