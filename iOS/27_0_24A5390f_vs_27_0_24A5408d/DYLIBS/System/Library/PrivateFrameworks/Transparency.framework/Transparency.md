## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x786a4` | `0x7dba8` | **`+0x5504`** |
| `__TEXT.__eh_frame` | `0x2f00` | `0x35b0` | **`+0x6b0`** |
| `__TEXT.__const` | `0x4580` | `0x4a80` | **`+0x500`** |
| `__DATA.__bss` | `0x6e90` | `0x7250` | **`+0x3c0`** |
| `__TEXT.__unwind_info` | `0x2a40` | `0x2c00` | **`+0x1c0`** |
| `__TEXT.__swift5_typeref` | `0xf32` | `0x1050` | **`+0x11e`** |
| `__TEXT.__swift5_fieldmd` | `0xbb8` | `0xcb0` | **`+0xf8`** |
| `__AUTH_CONST.__const` | `0x3d38` | `0x3df8` | **`+0xc0`** |
| `__AUTH.__data` | `0x4b0` | `0x548` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x8ca` | `0x95a` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0xa5c` | `0xad8` | **`+0x7c`** |
| `__TEXT.__swift5_acfuncs` | `0xf0` | `0x168` | **`+0x78`** |
| `__TEXT.__swift_as_cont` | `0x194` | `0x200` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x2fec` | `0x303c` | **`+0x50`** |
| `__DATA.__data` | `0x1050` | `0x1090` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0x120` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0xcc` | `0xfc` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x3aa0` | `0x3a80` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x38c` | `0x3a8` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xc78` | `0xc90` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x638` | `0x650` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4a78` | `0x4a90` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4d8` | `0x4ec` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x1638` | `0x1640` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2028` | `0x2030` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xf0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1766.0.39.0.2
+1766.0.60.0.0

-  Functions: 3694
-  Symbols:   3542
-  CStrings:  765
+  Functions: 3793
+  Symbols:   3565
+  CStrings:  769
Symbols:
+ +[TransparencySettings queryCacheValidityWindow]
+ +[TransparencySettings setQueryCacheValidityWindow:]
+ GCC_except_table6
+ _CFNumberCreate
+ _CFPreferencesAppSynchronize
+ _associated conformance 12Transparency18CKVQueryCacheStatsV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency18CKVQueryCacheStatsV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency18CKVQueryCacheStatsV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _kCFAllocatorDefault
+ _kTransparencyDefaultQueryCacheValidityWindow
+ _kTransparencyOverrideQueryCacheValidityWindow
+ _symbolic Sd
+ _symbolic SdSg
+ _symbolic SdSgx______p_____Rz_____RzlIetMHyTgzo_ s5ErrorP 11Distributed01_B9ActorStubP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic SdSgx______p_____RzlIetWHyTgzo_ s5ErrorP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic _____ 12Transparency18CKVQueryCacheStatsV
+ _symbolic _____ 12Transparency18CKVQueryCacheStatsV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____ySdSgG 11Distributed18RemoteCallArgumentV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency18CKVQueryCacheStatsV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency18CKVQueryCacheStatsV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic x___________p_____Rz_____RzlIetMHgrzo_ 12Transparency18CKVQueryCacheStatsV s5ErrorP 11Distributed01_F9ActorStubP AA21CKVDiagnosticsServiceP
+ _symbolic x___________p_____RzlIetWHgrzo_ 12Transparency18CKVQueryCacheStatsV s5ErrorP AA21CKVDiagnosticsServiceP
+ _symbolic x______p_____Rz_____RzlIetMHgzo_ s5ErrorP 11Distributed01_B9ActorStubP 12Transparency21CKVDiagnosticsServiceP
+ _symbolic x______p_____RzlIetWHgzo_ s5ErrorP 12Transparency21CKVDiagnosticsServiceP
- __CFXPCCreateCFObjectFromXPCObject
CStrings:
+ "Device isn't PCC eligible, disabling software transparency"
+ "clearQueryCache()"
+ "insertsOrUpdates"
+ "overrideQueryCacheValidityWindow"
+ "queryCacheStats()"
+ "setQueryCacheValidityWindow(_:)"
+ "validityWindowSeconds"
- "Device isn't GMS capable, disabling software transparency"
- "OS_ELIGIBILITY_INPUT_GENERATIVE_MODEL_SYSTEM"
- "verify proofs blocked because device is not eligible for GM"
```
