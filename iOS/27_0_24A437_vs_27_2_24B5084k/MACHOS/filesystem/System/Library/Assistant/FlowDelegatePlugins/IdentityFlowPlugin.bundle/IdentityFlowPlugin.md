## IdentityFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/IdentityFlowPlugin.bundle/IdentityFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xe8` | `0x108` | **`+0x20`** |
| `__TEXT.__text` | `0x12f0` | `0x1304` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.5.1.0.0
+3605.2.1.0.0
Functions:
~ sub_12c0 : 492 -> 512
CStrings:
+ "SiriIdentity supports only NLv3, NLv4, USO & direct-invocation parse."
- "SiriIdentity supports only NLv3 & NLv4 parse."
```
