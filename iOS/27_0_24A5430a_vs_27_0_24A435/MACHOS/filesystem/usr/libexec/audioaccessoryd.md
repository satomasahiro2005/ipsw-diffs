## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25b990` | `0x25c384` | **`+0x9f4`** |
| `__TEXT.__cstring` | `0x590e3` | `0x59303` | **`+0x220`** |
| `__DATA_CONST.__cfstring` | `0xbaa0` | `0xbb80` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0xce38` | `0xce80` | **`+0x48`** |
| `__TEXT.__const` | `0x4d80` | `0x4da0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1f420` | `0x1f440` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x72c0` | `0x72d0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-40.41.1.1.7
+40.41.1.1.10

-  Functions: 12091
+  Functions: 12102

-  CStrings:  16411
+  CStrings:  16432
CStrings:
+ "%@-Seed-mov"
+ "-[BTServicesDaemon _audioQualityShowBanner:title:deviceAddressString:messageKey:messageArgs:timeoutSeconds:]_block_invoke"
+ "-[BTServicesDaemon openRadarforAudioQuality]"
+ "1551854"
+ "815886"
+ "Bluetooth Audio Quality Feedback"
+ "CoreBluetooth - HFP Audio | iOS"
+ "Device1,8240"
+ "Device1,8242"
+ "Device1,8245"
+ "Device1,8246"
+ "Device1,8247"
+ "Device1,8248"
+ "Keywords"
+ "Performance"
+ "audioQuality - File Radar"
+ "audioQuality banner timeout"
+ "audioQuality user click, openradar"
+ "audioQuality user dismiss"
+ "audioQuality: banner action: %s, %{error}"
+ "audioQuality: banner error for device %@"
```
