## HomeKitClips

> `/System/Library/PrivateFrameworks/HomeKitClips.framework/HomeKitClips`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c7acc` | `0x2c9574` | **`+0x1aa8`** |
| `__DATA_DIRTY.__bss` | `0x800` | `0xe00` | **`+0x600`** |
| `__TEXT.__const` | `0x14560` | `0x14920` | **`+0x3c0`** |
| `__AUTH_CONST.__const` | `0xc400` | `0xc778` | **`+0x378`** |
| `__DATA_DIRTY.__data` | `0x3510` | `0x3760` | **`+0x250`** |
| `__DATA.__bss` | `0x1adb0` | `0x1af30` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x4159` | `0x42d9` | **`+0x180`** |
| `__TEXT.__swift5_fieldmd` | `0x4ee4` | `0x5038` | **`+0x154`** |
| `__AUTH.__data` | `0x3e50` | `0x3d30` | **`-0x120`** |
| `__TEXT.__eh_frame` | `0x180ec` | `0x1820c` | **`+0x120`** |
| `__TEXT.__cstring` | `0x5c08` | `0x5cd8` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x87e8` | `0x88a8` | **`+0xc0`** |
| `__DATA.__data` | `0x4344` | `0x4290` | **`-0xb4`** |
| `__TEXT.__oslogstring` | `0x7d83` | `0x7e33` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x5364` | `0x53d4` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x6b1c` | `0x6b7a` | **`+0x5e`** |
| `__TEXT.__swift5_proto` | `0xe20` | `0xe5c` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0xcd8` | `0xd08` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x18d0` | `0x18e0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x5dc` | `0x5ec` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1058` | `0x1048` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf0` | `0xaf8` | **`+0x8`** |

### Other Changes

```diff

-1516.0.0.0.0
+1520.2.3.0.2

-  Functions: 9742
-  Symbols:   2890
-  CStrings:  1092
+  Functions: 9806
+  Symbols:   2903
+  CStrings:  1103
Symbols:
+ ___swift_memcpy76_8
+ _associated conformance 12HomeKitClips5HKSV3V15CameraRecordingV9InitiatorOSHAASQ
+ _associated conformance 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV10CodingKeysOSHAASQ
+ _associated conformance 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV10CodingKeysOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV10CodingKeysOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV15InitiatedReasonOSHAASQ
+ _associated conformance 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataVSHAASQ
+ _symbolic _____ 12HomeKitClips5HKSV3V15CameraRecordingV9InitiatorO
+ _symbolic _____ 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV
+ _symbolic _____ 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV10CodingKeysO
+ _symbolic _____ 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV15InitiatedReasonO
+ _symbolic _____Sg 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12HomeKitClips5HKSV3V22CameraRecordingSessionV0I8MetadataV10CodingKeysO
+ _type_layout_string 12HomeKitClips5HKSV3V22CameraRecordingSessionV0F8MetadataV
- ___swift_memcpy73_8
CStrings:
+ " bytes as recording metadata: "
+ "Cannot parse the recording metadata of session %s, error: %@"
+ "[%s] (Playlist) %{public}s"
+ "[%s] Authenticated download complete: %ld bytes in %{public}s"
+ "[%s] Requesting playlist from URL: %{public}s"
+ "[%s] Response status: %{public}ld, x-apple-request-uuid: %{public}s"
+ "camera"
+ "com.apple.encrypted-metadata"
+ "initiatedReason"
+ "isNoActivity"
+ "isSensitiveContent"
+ "isUnsafeContent"
+ "resident"
+ "x-apple-request-uuid"
- "[%s] (Prefix) %s"
- "[%s] (Suffix) %s"
- "[%s] Authenticated download complete: %ld bytes"
```
