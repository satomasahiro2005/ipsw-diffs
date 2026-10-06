## com.apple.SpeechRecognitionCore.speechrecognitiond

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/XPCServices/com.apple.SpeechRecognitionCore.speechrecognitiond.xpc/com.apple.SpeechRecognitionCore.speechrecognitiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcdf70` | `0xcdbe8` | **`-0x388`** |
| `__TEXT.__cstring` | `0x3542` | `0x34c2` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x611e` | `0x618e` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x1d00` | `0x1cc0` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x7a20` | `0x79e0` | **`-0x40`** |
| `__DATA.__bss` | `0x4c8` | `0x4a0` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x810` | `0x820` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2980` | `0x2970` | **`-0x10`** |
| `__TEXT.__const` | `0x62c5` | `0x62d5` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4bc0` | `0x4bb0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x14e0` | `0x14d8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0xabd8` | `0xabd4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-37.0.0.0.0
+38.0.0.0.0

-  Functions: 3733
-  Symbols:   1164
-  CStrings:  2260
+  Functions: 3726
+  Symbols:   1162
+  CStrings:  2257
Symbols:
- _CFPreferencesAppSynchronize
- __ZN6RDPeer14KeywordChangedEv
CStrings:
+ "Called the callback with final results = %{sensitive}@"
+ "Called the callback with partial results = %{sensitive}@"
+ "Got recognition results from audio file %{sensitive}s"
+ "PeerConnection: received addLeadingContext: %{sensitive}s"
+ "PeerConnection: received addOtherContext: %{sensitive}s"
+ "PeerConnection: received client update : %{sensitive}@"
+ "PeerConnection: received legacy message %{sensitive}@"
- "Called the callback with final results = %@"
- "Called the callback with partial results = %@"
- "Got recognition results from audio file %s"
- "PeerConnection: received addLeadingContext: %s"
- "PeerConnection: received addOtherContext: %s"
- "PeerConnection: received client update : %@"
- "PeerConnection: received legacy message %@"
- "RDKeyword"
- "com.apple.speech.recognition.AppleSpeechRecognition.KeywordChanged"
- "com.apple.speech.recognition.AppleSpeechRecognition.prefs"
```
