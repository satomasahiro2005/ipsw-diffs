## IDS

> `/System/Library/PrivateFrameworks/IDS.framework/IDS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19d38c` | `0x19d788` | **`+0x3fc`** |
| `__TEXT.__oslogstring` | `0x1b3d4` | `0x1b4c4` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x6960` | `0x69b8` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0xdae4` | `0xdb2c` | **`+0x48`** |
| `__DATA.__data` | `0x26c8` | `0x26f0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x6c88` | `0x6cb0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x11893` | `0x118ba` | **`+0x27`** |
| `__AUTH_CONST.__objc_intobj` | `0x570` | `0x588` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0xc00` | `0xc11` | **`+0x11`** |
| `__AUTH_CONST.__objc_const` | `0x3d2b0` | `0x3d2c0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1d70` | `0x1d78` | **`+0x8`** |
| `__TEXT.__const` | `0x4f70` | `0x4f78` | **`+0x8`** |

### Other Changes

```diff

-1992.100.7.2.1
+1996.100.2.2.2

-  Functions: 8972
-  Symbols:   1863
-  CStrings:  3849
+  Functions: 8979
+  Symbols:   1864
+  CStrings:  3854
Symbols:
+ _IMInsertDatasToXPCDictionary
CStrings:
+ "Failed to encode device query flush options: %@"
+ "Failed to unarchive IDSPayloadVerificationResult { error: %@ }"
+ "Sending device query flush { additionalDestinations: %lu }"
+ "flush-device-query"
+ "kClientChannelMetadataType_GroupSessionLeaving: group session leaving"
```
