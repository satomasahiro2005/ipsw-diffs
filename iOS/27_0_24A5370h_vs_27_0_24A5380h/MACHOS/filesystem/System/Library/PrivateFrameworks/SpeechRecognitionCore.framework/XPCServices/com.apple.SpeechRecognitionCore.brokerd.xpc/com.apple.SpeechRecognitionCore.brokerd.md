## com.apple.SpeechRecognitionCore.brokerd

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/com.apple.SpeechRecognitionCore.brokerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10be4` | `0x10b58` | **`-0x8c`** |
| `__TEXT.__oslogstring` | `0x1513` | `0x1553` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xd80` | `0xd50` | **`-0x30`** |
| `__TEXT.__cstring` | `0xbe3` | `0xbb3` | **`-0x30`** |
| `__DATA_CONST.__cfstring` | `0xf60` | `0xf40` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x6d8` | `0x6c0` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x7a0` | `0x78c` | **`-0x14`** |
| `__TEXT.__const` | `0x162` | `0x152` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4c0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x218` | `0x220` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-37.0.0.0.0
+38.0.0.0.0

-  Symbols:   306
-  CStrings:  543
+  Symbols:   303
+  CStrings:  542
Symbols:
+ __os_log_error_impl
- _CFDataGetBytePtr
- _CFDataGetLength
- _CFStringCreateExternalRepresentation
- _CFStringCreateWithFormatAndArguments
CStrings:
+ "Received invalid recognizer ID in UpdateRecognizer %{public}lld"
- "%.*s"
- "Received invalid recognizer ID in UpdateRecognizer %lld"
```
