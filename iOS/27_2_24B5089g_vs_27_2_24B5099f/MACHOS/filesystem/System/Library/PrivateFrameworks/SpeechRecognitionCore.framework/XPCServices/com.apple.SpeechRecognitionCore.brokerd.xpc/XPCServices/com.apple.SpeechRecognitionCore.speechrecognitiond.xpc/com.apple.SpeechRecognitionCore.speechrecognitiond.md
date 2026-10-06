## com.apple.SpeechRecognitionCore.speechrecognitiond

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/XPCServices/com.apple.SpeechRecognitionCore.speechrecognitiond.xpc/com.apple.SpeechRecognitionCore.speechrecognitiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1cc0` | `0x1ca0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x34c2` | `0x34a2` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x3dc0` | `0x3de0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2970` | `0x2960` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x5195` | `0x51a5` | **`+0x10`** |
| `__TEXT.__text` | `0xcdb64` | `0xcdb58` | **`-0xc`** |
| `__DATA.__bss` | `0x4a0` | `0x498` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x1380` | `0x1388` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x14d8` | `0x14d0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-41.1.1.0.0
+41.1.3.0.0

-  Symbols:   1162
+  Symbols:   1161
Symbols:
- _IOPMAssertionDeclareUserActivity
Functions:
~ __ZN6RDPeer15KeepSystemAwakeEv : 24 -> 12
CStrings:
+ "declareCommandMatched"
- "Speech Recognition Successful"
```
