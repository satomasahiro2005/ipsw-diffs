## IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xdd` | `0x241` | **`+0x164`** |
| `__TEXT.__text` | `0xa98` | `0xa64` | **`-0x34`** |
| `__DATA_CONST.__cfstring` | `0xc0` | `0xa0` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x380` | `0x360` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x2f0` | `0x2de` | **`-0x12`** |
| `__TEXT.__auth_stubs` | `0x230` | `0x220` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x100` | `0xf8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x120` | `0x118` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x70` | `0x68` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  Symbols:   60
-  CStrings:  58
+  Symbols:   58
+  CStrings:  56
Symbols:
- _OBJC_CLASS_$_NSString
- _objc_release_x27
Functions:
~ sub_1000010d8 : 832 -> 780
CStrings:
+ "subsystem == \"com.apple.Messages\" OR subsystem == \"com.apple.MessagesEvents\" OR (subsystem == \"com.apple.IDS\" AND category == \"Delivery\") OR (subsystem == \"com.apple.IDS\" AND category == \"GUIDTRACE\") OR (subsystem == \"com.apple.IDS\" AND category == \"FaceTime\") OR (subsystem == \"com.apple.apsd\" AND category == \"courier\") OR (subsystem == \"com.apple.apsd\" AND category == \"courier-oversized\")"
- "com.apple.Messages"
- "stringWithFormat:"
- "subsystem == \"%@\""
```
