## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25c384` | `0x25c168` | **`-0x21c`** |
| `__TEXT.__cstring` | `0x59303` | `0x59113` | **`-0x1f0`** |
| `__DATA_CONST.__cfstring` | `0xbb80` | `0xbaa0` | **`-0xe0`** |
| `__TEXT.__objc_stubs` | `0x1f440` | `0x1f3e0` | **`-0x60`** |
| `__TEXT.__eh_frame` | `0x2dc8` | `0x2d90` | **`-0x38`** |
| `__TEXT.__objc_methname` | `0x2d575` | `0x2d555` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x72d0` | `0x72b0` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x9358` | `0x9348` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-40.41.1.1.10
+41.4.0.0.0

-  Functions: 12102
+  Functions: 12095

-  CStrings:  16432
+  CStrings:  16414
CStrings:
+ "CloudSync: Process updated cloud record (%@) modified by device: [%@] is [%@] %@, updateDelegate: %d, creationDate: %@, modifiedDate: %@"
- "%@-Seed-mov"
- "-[BTServicesDaemon _audioQualityShowBanner:title:deviceAddressString:messageKey:messageArgs:timeoutSeconds:]_block_invoke"
- "-[BTServicesDaemon openRadarforAudioQuality]"
- "1551854"
- "815886"
- "Bluetooth Audio Quality Feedback"
- "CloudSync: Process updated cloud record (%@) modified by device: [%@] is [%@] %@, updateDelegate: %d"
- "CoreBluetooth - HFP Audio | iOS"
- "Failed to unarchive record -- creating new support info record"
- "Keywords"
- "Performance"
- "audioQuality - File Radar"
- "audioQuality banner timeout"
- "audioQuality user click, openradar"
- "audioQuality user dismiss"
- "audioQuality: banner action: %s, %{error}"
- "audioQuality: banner error for device %@"
- "encryptedValueStore"
- "resetChangedKeys"
```
