## SiriMailFlowTools

> `/System/Library/FlowTools/Tools/SiriMailFlowTools.flowtool/SiriMailFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f004` | `0x4f27c` | **`+0x278`** |
| `__TEXT.__objc_stubs` | `0x5e0` | `0x580` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x162a` | `0x15da` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x6d2` | `0x689` | **`-0x49`** |
| `__TEXT.__auth_stubs` | `0x1620` | `0x1640` | **`+0x20`** |
| `__TEXT.__const` | `0x17b0` | `0x17d0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x3e80` | `0x3e60` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x238` | `0x220` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x428` | `0x440` | **`+0x18`** |
| `__DATA.__data` | `0xd70` | `0xd80` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xb18` | `0xb28` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10c0` | `0x10b0` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x722` | `0x730` | **`+0xe`** |
| `__DATA_CONST.__auth_ptr` | `0x7d0` | `0x7d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
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

-3605.14.1.0.0
+3605.17.1.0.0

-  Functions: 1628
+  Functions: 1630

-  CStrings:  210
+  CStrings:  207
CStrings:
+ "#MailFlowTool foregrounded app %s differs from executing app %s, forcing display mode so the attachment update runs in the foreground"
+ "What’s the subject?"
- "#MailFlowTool foregrounded app %s differs from executing app %s, but composing/sending with attachments in display mode — letting AppIntent execute in foreground so the user can see the attachment in the full UI"
- "What's the subject?"
- "initWithPath:"
- "localizedStringForKey:value:table:"
- "pathForResource:ofType:"
```
