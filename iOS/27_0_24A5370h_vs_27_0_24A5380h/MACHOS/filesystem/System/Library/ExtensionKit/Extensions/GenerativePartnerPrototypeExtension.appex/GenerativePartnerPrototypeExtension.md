## GenerativePartnerPrototypeExtension

> `/System/Library/ExtensionKit/Extensions/GenerativePartnerPrototypeExtension.appex/GenerativePartnerPrototypeExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e780` | `0x3ddcc` | **`-0x9b4`** |
| `__DATA_CONST.__const` | `0x18b8` | `0x15e8` | **`-0x2d0`** |
| `__TEXT.__swift5_capture` | `0x348` | `0x228` | **`-0x120`** |
| `__TEXT.__cstring` | `0xd35d` | `0xd3ed` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x2080` | `0x20f0` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x1048` | `0x1080` | **`+0x38`** |
| `__TEXT.__const` | `0x36f2` | `0x3722` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xcb5` | `0xce5` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x19d0` | `0x19a8` | **`-0x28`** |
| `__DATA.__data` | `0x1278` | `0x1270` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x8f0` | `0x8f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x498` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xec` | `0xe4` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xbc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xb0` | `0xa8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xf78` | `0xf70` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x106e` | `0x106a` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-284.0.7.0.0
+287.0.6.0.0

-  Functions: 1977
-  Symbols:   185
-  CStrings:  192
+  Functions: 1937
+  Symbols:   183
+  CStrings:  195
Symbols:
+ _swift_getErrorValue
- _swift_retain_x8
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Failed to decode WritingTools JSON: "
+ "GPPE received early ContinuationURL: %{private}s"
+ "Received text token %s, %ld chars"
+ "Received writing tools token %s, %ld chars"
+ "The generated model response stream does not produce a completion event"
- "Received text token %s, %{public}ld characters"
- "Received writing tools text token %s, %{public}ld characters"
```
