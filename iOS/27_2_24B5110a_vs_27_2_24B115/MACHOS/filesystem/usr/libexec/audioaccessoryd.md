## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25c204` | `0x25c948` | **`+0x744`** |
| `__TEXT.__cstring` | `0x59153` | `0x59333` | **`+0x1e0`** |
| `__DATA_CONST.__cfstring` | `0xbac0` | `0xbba0` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x1f420` | `0x1f440` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x72b8` | `0x72c8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 12098
+  Functions: 12106

-  CStrings:  16419
+  CStrings:  16434
CStrings:
+ "%@-Seed-mov"
+ "-[BTServicesDaemon _audioQualityShowBanner:title:deviceAddressString:messageKey:messageArgs:timeoutSeconds:]_block_invoke"
+ "-[BTServicesDaemon openRadarforAudioQuality]"
+ "1551854"
+ "815886"
+ "Bluetooth Audio Quality Feedback"
+ "CoreBluetooth - HFP Audio | iOS"
+ "Keywords"
+ "Performance"
+ "audioQuality - File Radar"
+ "audioQuality banner timeout"
+ "audioQuality user click, openradar"
+ "audioQuality user dismiss"
+ "audioQuality: banner action: %s, %{error}"
+ "audioQuality: banner error for device %@"
```
