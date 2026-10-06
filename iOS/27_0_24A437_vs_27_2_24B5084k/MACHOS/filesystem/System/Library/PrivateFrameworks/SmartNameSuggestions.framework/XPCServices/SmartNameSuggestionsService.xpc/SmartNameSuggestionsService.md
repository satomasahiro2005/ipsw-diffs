## SmartNameSuggestionsService

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/XPCServices/SmartNameSuggestionsService.xpc/SmartNameSuggestionsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a360` | `0x1b75c` | **`+0x13fc`** |
| `__TEXT.__eh_frame` | `0xad0` | `0xc10` | **`+0x140`** |
| `__DATA.__objc_const` | `0x888` | `0x960` | **`+0xd8`** |
| `__DATA.__data` | `0xa98` | `0xb40` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x511` | `0x5a1` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x1630` | `0x1690` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x4e0` | `0x540` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x4f0` | `0x540` | **`+0x50`** |
| `__TEXT.__const` | `0xd68` | `0xdb8` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x20b` | `0x24b` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x494` | `0x4c8` | **`+0x34`** |
| `__TEXT.__objc_classname` | `0x29f` | `0x2d3` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0xb20` | `0xb50` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x96b` | `0x99b` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2cc` | `0x2f4` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0xac` | `0xcc` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x4d2` | `0x4ec` | **`+0x1a`** |
| `__DATA_CONST.__got` | `0x278` | `0x288` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1f0` | `0x200` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x3c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x44` | `0x48` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-24.0.0.0.0
+24.1.3.0.0

-  Functions: 344
+  Functions: 358

-  CStrings:  196
+  CStrings:  204
Symbols:
+ _objc_retain_x24
+ _objc_retain_x28
+ _swift_retain_x22
- _objc_retain_x22
- _swift_continuation_throwingResume
- _swift_continuation_throwingResumeWithError
CStrings:
+ "Model returned a suggestion ending in '.': '%s'"
+ "Suggestion ends in '.'"
+ "Suggestion ends in '.': '"
+ "_TtC27SmartNameSuggestionsService15ProcessActivity"
+ "_createCheckedThrowingContinuation(_:)"
+ "ended"
+ "maxSuggestionLimit"
+ "token"
```
