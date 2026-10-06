## CoreTransparency

> `/System/Library/PrivateFrameworks/CoreTransparency.framework/CoreTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f128` | `0x4655c` | **`+0x7434`** |
| `__AUTH_CONST.__const` | `0x3638` | `0x3a30` | **`+0x3f8`** |
| `__DATA.__bss` | `0x7380` | `0x7080` | **`-0x300`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0x400` | **`+0x300`** |
| `__TEXT.__eh_frame` | `0x1df0` | `0x20d4` | **`+0x2e4`** |
| `__TEXT.__cstring` | `0x9be` | `0xc8e` | **`+0x2d0`** |
| `__TEXT.__swift5_capture` | `—` | `0x150` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x16b0` | `0x17c0` | **`+0x110`** |
| `__AUTH_CONST.__auth_got` | `0x880` | `0x958` | **`+0xd8`** |
| `__DATA_DIRTY.__data` | `0x8` | `0xb0` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x17ca` | `0x1862` | **`+0x98`** |
| `__AUTH.__data` | `0x990` | `0xa10` | **`+0x80`** |
| `__TEXT.__const` | `0x70e4` | `0x7164` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x1b64` | `0x1bd8` | **`+0x74`** |
| `__DATA.__data` | `0x9f0` | `0x9a0` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x1ae8` | `0x1b34` | **`+0x4c`** |
| `__TEXT.__swift5_reflstr` | `0x202d` | `0x2064` | **`+0x37`** |
| `__DATA_CONST.__const` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x15c` | `0x164` | **`+0x8`** |
| `__TEXT.__oslogstring` | `—` | `0x3` | **`+0x3`** |

### Other Changes

```diff

-1766.0.13.0.0
+1766.0.27.0.0

+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 2754
-  Symbols:   692
-  CStrings:  76
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 2837
+  Symbols:   726
+  CStrings:  93
Symbols:
+ ___swift_closure_destructor
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ ___swift_memcpy120_8
+ __os_log_impl
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_CoreTransparency
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_CoreTransparency
+ _objc_release
+ _os_log_type_enabled
+ _swift_arrayDestroy
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
+ _swift_deallocClassInstance
+ _swift_deallocObject
+ _swift_getObjectType
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x25
+ _swift_retain_x22
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x28
+ _swift_setDeallocating
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
+ _symbolic SSIego_
+ _symbolic Si6offset______7elementt 16CoreTransparency19CTEscapableMapProofV
+ _symbolic Si6offset______7elementtSg 16CoreTransparency19CTEscapableMapProofV
+ _symbolic _____ 16CoreTransparency20AETEscapableVerifierV14MapProofResult33_85266BF824721A9CDF7464F5EF259C44LLV
+ _symbolic _____ 16CoreTransparency8CTLoggerV
+ _symbolic _____ 2os6LoggerV
+ _symbolic _____y__________Say_____GG 16CoreTransparency16VerifiedLogEntryV AA23CTEscapableSignedObjectV AA10CTELogHeadV s5UInt8V
+ _symbolic _____yySpy_____Gz_SpySo8NSObjectCSgGSgzSpyypGSgztcG s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic yyc
+ _type_layout_string 16CoreTransparency20AETEscapableVerifierV14MapProofResult33_85266BF824721A9CDF7464F5EF259C44LLV
- _get_type_metadata 16CoreTransparency13RawSpanBufferV noncopyable
- _get_type_metadata 16CoreTransparency16WireFormatReaderV noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ " consistencyResponses="
+ "%s"
+ "com.apple.CoreTransparency"
+ "parseEvents: mapProofs="
+ "verifyConsistencyProofs: count="
+ "verifyConsistencyProofs: failed to verify consistency "
+ "verifyConsistencyProofs: failed to verify endSLH signature: "
+ "verifyConsistencyProofs: failed to verify startSLH signature: "
+ "verifyConsistencyProofs: verified consistency "
+ "verifyConsistencyProofs: verified endSLH "
+ "verifyConsistencyProofs: verified startSLH "
+ "verifyMapProofs: failed to parse map leaf: "
+ "verifyMapProofs: failed to verify map proof: "
+ "verifyMapProofs: mapProofCount="
+ "verifyMapProofs: mismatched PAT heads "
+ "verifyMapProofs: no PAT entry found in any map proof ["
+ "verifyMapProofs: proof["
```
