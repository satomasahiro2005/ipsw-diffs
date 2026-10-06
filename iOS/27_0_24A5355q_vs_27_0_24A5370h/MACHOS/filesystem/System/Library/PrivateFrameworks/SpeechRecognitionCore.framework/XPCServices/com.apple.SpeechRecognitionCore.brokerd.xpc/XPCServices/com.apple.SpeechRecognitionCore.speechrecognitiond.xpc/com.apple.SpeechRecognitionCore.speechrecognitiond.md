## com.apple.SpeechRecognitionCore.speechrecognitiond

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/XPCServices/com.apple.SpeechRecognitionCore.speechrecognitiond.xpc/com.apple.SpeechRecognitionCore.speechrecognitiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xccb20` | `0xcdf70` | **`+0x1450`** |
| `__TEXT.__const` | `0x5fe5` | `0x62c5` | **`+0x2e0`** |
| `__TEXT.__gcc_except_tab` | `0xaaec` | `0xabd8` | **`+0xec`** |
| `__DATA_CONST.__const` | `0x7970` | `0x7a20` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x606e` | `0x611e` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0x2920` | `0x2980` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x4b80` | `0x4bc0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x14b0` | `0x14e0` | **`+0x30`** |
| `__DATA.__objc_data` | `0x1488` | `0x14a8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xc7c` | `0xc9c` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x32cc` | `0x32ec` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x800` | `0x810` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x66c` | `0x67c` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-34.0.0.0.0
+37.0.0.0.0

-  Functions: 3715
-  Symbols:   1162
-  CStrings:  2256
+  Functions: 3733
+  Symbols:   1164
+  CStrings:  2260
Symbols:
+ _AVAudioSessionPortHeadphones
+ _AVAudioSessionPortUSBAudio
CStrings:
+ "AVC: Audio input type changed - %ld"
+ "GrammarIsLive: invalid grammar ID %zu"
+ "RemoveGrammar: invalid grammar ID %zu"
+ "SpeechDonation: invalid sample range, don't donate"
```
