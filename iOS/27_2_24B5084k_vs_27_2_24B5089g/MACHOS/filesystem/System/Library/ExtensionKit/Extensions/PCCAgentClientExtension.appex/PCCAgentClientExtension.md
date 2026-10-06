## PCCAgentClientExtension

> `/System/Library/ExtensionKit/Extensions/PCCAgentClientExtension.appex/PCCAgentClientExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37d94` | `0x38ffc` | **`+0x1268`** |
| `__TEXT.__oslogstring` | `0x2023` | `0x2133` | **`+0x110`** |
| `__TEXT.__auth_stubs` | `0x17a0` | `0x1870` | **`+0xd0`** |
| `__DATA_CONST.__auth_got` | `0xbd8` | `0xc40` | **`+0x68`** |
| `__TEXT.__cstring` | `0x88d` | `0x8ad` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x348` | `0x350` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62.0.0.0.0
+63.0.0.0.0

-  Functions: 528
+  Functions: 529

-  CStrings:  224
+  CStrings:  227
CStrings:
+ "Emitted InferenceEnvironmentResponse diagnostics"
+ "InferenceEnvironmentResponse"
+ "baseModel=%{public}s/%{public}s adapter=%{public}s/%{public}s draftModel=%{public}s/%{public}s tokenizer=%{public}s/%{public}s cloudosVersion=%{public}s cloudosEnvironment=%{public}s routingReason=%{public}s"
```
