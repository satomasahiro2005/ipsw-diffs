## SiriMailSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriMailSnippetProviderPlugin.bundle/SiriMailSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd84` | `0xc660` | **`+0x8dc`** |
| `__TEXT.__oslogstring` | `0x921` | `0xa11` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0xaa0` | `0xb00` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x130` | `0x170` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1a8` | `0x1e0` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x558` | `0x588` | **`+0x30`** |
| `__DATA.__data` | `0x4c0` | `0x4e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x9d` | `0xbd` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x118` | `0x130` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x15c` | `0x174` | **`+0x18`** |
| `__TEXT.__const` | `0x328` | `0x338` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.23.4.0.0
+3600.23.10.0.0

+  - /System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared

-  Functions: 204
+  Functions: 216

-  CStrings:  95
+  CStrings:  98
CStrings:
+ "#DraftMailSnippetHandler supportsAsync - skipping claim, foreground compose UI handles display mode"
+ "#SiriMailSnippetProviderPlugin handle(item:context:) failed to convert ReadableMailMessageAppEntity to WidgetMessage"
+ "ReadableMailMessageAppEntity"
```
