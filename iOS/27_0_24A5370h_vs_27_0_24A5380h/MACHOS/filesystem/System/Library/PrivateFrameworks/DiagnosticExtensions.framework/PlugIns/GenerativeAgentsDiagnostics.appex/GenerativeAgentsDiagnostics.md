## GenerativeAgentsDiagnostics

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/GenerativeAgentsDiagnostics.appex/GenerativeAgentsDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58bc` | `0x5b24` | **`+0x268`** |
| `__DATA_CONST.__const` | `0x4d0` | `0x598` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0xa30` | `0xaf0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x153` | `0xc3` | **`-0x90`** |
| `__DATA_CONST.__auth_got` | `0x520` | `0x580` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1a4` | `0x1f4` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x1da` | `0x21a` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1e0` | `0x220` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x46e` | `0x49e` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x186` | `0x1b4` | **`+0x2e`** |
| `__TEXT.__const` | `0xf2` | `0x11a` | **`+0x28`** |
| `__DATA.__data` | `0xb8` | `0xd8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x188` | `0x1a8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc8` | `0xe0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-284.0.7.0.0
+287.0.6.0.0

-  Functions: 166
-  Symbols:   117
+  Functions: 177
+  Symbols:   119
Symbols:
+ _OBJC_CLASS_$_NSJSONSerialization
+ _swift_release_n
+ _swift_retain_n
+ _swift_retain_x8
+ _swift_unknownObjectRelease
- _objc_release_x27
- _objc_retain_x22
- _swift_release_x24
CStrings:
+ "GenerativeAgentsDiagnostics: failed to create attachment URL for %s"
+ "GenerativeAgentsDiagnostics: failed to decode TokenGenerationRequest at index %ld"
+ "GenerativeAgentsDiagnostics: failed to write %s: %@"
+ "JSONObjectWithData:options:error:"
+ "dataWithJSONObject:options:error:"
- "GenerativeAgentsDiagnostics: failed to create Token_Generation_Requests_Biome.json URL"
- "GenerativeAgentsDiagnostics: failed to create Token_Generation_Requests_Decoded.json URL"
- "TokenGeneration.Inference.Requests"
- "Token_Generation_Requests_Biome.json"
- "Token_Generation_Requests_Decoded.json"
```
