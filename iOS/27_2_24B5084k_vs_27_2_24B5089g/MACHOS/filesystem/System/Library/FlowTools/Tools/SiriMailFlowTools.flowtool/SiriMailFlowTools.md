## SiriMailFlowTools

> `/System/Library/FlowTools/Tools/SiriMailFlowTools.flowtool/SiriMailFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c780` | `0x4f004` | **`+0x2884`** |
| `__TEXT.__unwind_info` | `0x1488` | `0x10c0` | **`-0x3c8`** |
| `__TEXT.__oslogstring` | `0x150a` | `0x162a` | **`+0x120`** |
| `__DATA.__bss` | `0x1520` | `0x1620` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x1520` | `0x1620` | **`+0x100`** |
| `__TEXT.__cstring` | `0x2a4` | `0x374` | **`+0xd0`** |
| `__TEXT.__const` | `0x16f0` | `0x17b0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0xba8` | `0xc38` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0xa98` | `0xb18` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x3c8` | `0x428` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x3e20` | `0x3e80` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x780` | `0x7d0` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x624` | `0x664` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x5d9` | `0x619` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x6e8` | `0x722` | **`+0x3a`** |
| `__DATA.__data` | `0xd48` | `0xd70` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x418` | `0x434` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x40` | `0x44` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.13.1.0.0
+3605.14.1.0.0

-  Functions: 1586
+  Functions: 1628

-  CStrings:  201
+  CStrings:  210
CStrings:
+ "#ComposeMailFlowTool draft complete, chaining to send"
+ "#ComposeMailFlowTool required parameter missing (%s), prompting via askUser"
+ "#MailFlowTool foreground is SpringBoard (Home/Lock) in display mode — letting AppIntent execute in foreground so Mail's compose UI opens"
+ "SendDraftMailTool"
+ "What do you want to say?"
+ "What's the subject?"
+ "Who do you want to email?"
+ "Who do you want to forward this to?"
+ "com.apple.springboard"
```
