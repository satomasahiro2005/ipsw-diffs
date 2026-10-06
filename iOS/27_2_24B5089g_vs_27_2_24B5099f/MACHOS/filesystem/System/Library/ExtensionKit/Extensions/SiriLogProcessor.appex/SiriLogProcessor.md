## SiriLogProcessor

> `/System/Library/ExtensionKit/Extensions/SiriLogProcessor.appex/SiriLogProcessor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x27` | `0x39` | **`+0x12`** |
| `__TEXT.__text` | `0x1978` | `0x1980` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2.9.0.0.0
+3.3.0.0.0

-  CStrings:  5
+  CStrings:  6
Functions:
~ sub_100001380 : 132 -> 140
CStrings:
+ "Siri.LogProcessor.Plugin"
+ "com.apple.unilog.processing"
- "com.apple.unilog.siri.SiriLogProcessor"
```
