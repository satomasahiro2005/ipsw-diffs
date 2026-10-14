## IFFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/IFFlowPlugin.bundle/IFFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6edec` | `0x70290` | **`+0x14a4`** |
| `__TEXT.__oslogstring` | `0x3890` | `0x39f0` | **`+0x160`** |
| `__TEXT.__auth_stubs` | `0x31d0` | `0x3230` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x18f0` | `0x1920` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xd08` | `0xd30` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0xce0` | `0xd00` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xcf8` | `0xd18` | **`+0x20`** |
| `__DATA.__data` | `0x12a0` | `0x12b0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x818` | `0x828` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x400` | `0x408` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xcf8` | `0xd00` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.25.1.0.0
+3605.26.1.11.1

+  - /System/Library/PrivateFrameworks/ResponseUI.framework/ResponseUI

-  Functions: 842
-  Symbols:   243
-  CStrings:  516
+  Functions: 844
+  Symbols:   246
+  CStrings:  524
Symbols:
+ _AFIsWaffleiron
+ _OBJC_CLASS_$__SFPBCard
+ _objc_retain_x24
CStrings:
+ "#RGPluginModel: Setting Plugin model from pluginModel data"
+ "Cannot capture the output as pluginSnippet"
+ "Card Layout available"
+ "Expandable Card Layout available"
+ "Failed to decode pluginModelData. Error=%@"
+ "Falling back to protobuf card. Failed to create layout from model. Error=%s"
+ "Truncated Card Layout available"
+ "initWithFacade:"
```
