## SiriInferenceRuntimeDiagnostics

> `/System/Library/ExtensionKit/Extensions/SiriInferenceRuntimeDiagnostics.appex/SiriInferenceRuntimeDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f40` | `0x43d0` | **`+0x490`** |
| `__TEXT.__auth_stubs` | `0x830` | `0x880` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x73` | `0xb3` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x251` | `0x291` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x420` | `0x448` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x84` | `0xac` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2e0` | `0x300` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xb4` | `0xd0` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x80` | `0x98` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x14b` | `0x15d` | **`+0x12`** |
| `__TEXT.__const` | `0x25a` | `0x26a` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xa6` | `0xb6` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x36d` | `0x377` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3605.12.1.0.0
+3605.13.1.0.0

-  Functions: 137
-  Symbols:   118
-  CStrings:  98
+  Functions: 149
+  Symbols:   120
+  CStrings:  101
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ ___CFConstantStringClassReference
+ _swift_release_x22
+ _swift_retain_x22
- _swift_release_x28
- _swift_retain_x28
CStrings:
+ "DEExtensionAttachmentsParamConsentProvidedKey"
+ "DEExtensionHostAppKey"
+ "SiriInferenceRuntimeDiagnostics: user did not give consent; skipping attachments. host app: %{public}s"
+ "boolValue"
- "SiriRemembersAttachment: eventDict: %s"
```
