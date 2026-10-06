## IDS

> `/System/Library/PrivateFrameworks/IDS.framework/IDS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19d788` | `0x1a8bdc` | **`+0xb454`** |
| `__DATA.__bss` | `0x7940` | `0x9770` | **`+0x1e30`** |
| `__TEXT.__const` | `0x4f78` | `0x5d98` | **`+0xe20`** |
| `__TEXT.__eh_frame` | `0x27c8` | `0x2db8` | **`+0x5f0`** |
| `__AUTH_CONST.__const` | `0x4fa0` | `0x54a8` | **`+0x508`** |
| `__AUTH.__objc_data` | `0x1d38` | `0x2058` | **`+0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x1ea0` | `0x1b80` | **`-0x320`** |
| `__TEXT.__unwind_info` | `0x69b8` | `0x6cd8` | **`+0x320`** |
| `__TEXT.__swift5_typeref` | `0x184a` | `0x1ac4` | **`+0x27a`** |
| `__TEXT.__swift5_fieldmd` | `0x13d0` | `0x161c` | **`+0x24c`** |
| `__AUTH.__data` | `0xe30` | `0x1068` | **`+0x238`** |
| `__TEXT.__constg_swiftt` | `0x12d8` | `0x14e4` | **`+0x20c`** |
| `__TEXT.__cstring` | `0x118ba` | `0x11a76` | **`+0x1bc`** |
| `__DATA.__data` | `0x26f0` | `0x2830` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0xc11` | `0xd35` | **`+0x124`** |
| `__TEXT.__swift5_proto` | `0x2cc` | `0x3b4` | **`+0xe8`** |
| `__AUTH_CONST.__auth_got` | `0x1d78` | `0x1dd0` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x1b4c4` | `0x1b514` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0x1f4` | `0x230` | **`+0x3c`** |
| `__TEXT.__swift_as_entry` | `0xec` | `0x110` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1a78` | `0x1a98` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x3a0` | `0x3c0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x23c` | `0x254` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x108` | `0x11c` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x20` | `0x28` | **`+0x8`** |

### Other Changes

```diff

-1996.100.2.2.2
+1998.100.2.0.0

-  Functions: 8979
-  Symbols:   1864
-  CStrings:  3854
+  Functions: 9232
+  Symbols:   1865
+  CStrings:  3868
Symbols:
+ _swift_cvw_initEnumMetadataSingleCaseWithLayoutString
+ _swift_release_x28
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%s: suppressing serverMigration; not an actual migration (relaySessionID=%s)"
+ ") <key bytes redacted>"
+ ", decryptionKeyCount: "
+ ", decryptionKeyIDs: ["
+ ", encryptionKeyID: "
+ "RealTimeGroupSessionCryptor implementation has not yet landed — see rdar://179268110."
+ "RealTimeGroupSessionCryptor(topic: "
+ "]) <key bytes redacted>"
+ "decryptionKeyBytes"
+ "decryptionKeyIDs"
+ "decryptionKeysByKeyID"
+ "encryption"
+ "keyMaterialSource"
+ "strategy"
```
