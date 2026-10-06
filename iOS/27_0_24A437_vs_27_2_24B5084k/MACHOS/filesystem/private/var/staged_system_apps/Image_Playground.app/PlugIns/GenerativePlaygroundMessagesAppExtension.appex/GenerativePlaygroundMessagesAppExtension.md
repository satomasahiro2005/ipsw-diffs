## GenerativePlaygroundMessagesAppExtension

> `/private/var/staged_system_apps/Image Playground.app/PlugIns/GenerativePlaygroundMessagesAppExtension.appex/GenerativePlaygroundMessagesAppExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75c8` | `0x8864` | **`+0x129c`** |
| `__TEXT.__auth_stubs` | `0xa10` | `0xb80` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x10c` | `0x25c` | **`+0x150`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x5c8` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x143` | `0x1aa` | **`+0x67`** |
| `__DATA.__objc_const` | `0x3b0` | `0x3d0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x420` | `0x440` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xe8` | `0x100` | **`+0x18`** |
| `__TEXT.__const` | `0x144` | `0x154` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x860` | `0x870` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x44` | `0x50` | **`+0xc`** |
| `__DATA.__objc_data` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x158` | `0x160` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-198.1.102.0.0
+198.2.7.0.0

-  Functions: 130
-  Symbols:   147
-  CStrings:  135
+  Functions: 131
+  Symbols:   151
+  CStrings:  144
Symbols:
+ __os_signpost_emit_with_name_impl
+ _objc_release_x28
+ _swift_release_n
+ _swift_release_x9
CStrings:
+ "Context summarization assigned %{public}ld concept(s)."
+ "Context summarization failed or returned nothing."
+ "Context summarization produced no concepts."
+ "Context summarization skipped: recipe already present."
+ "Context summarization starting: %{public}ld item(s), precomputedSummary: %{public}s"
+ "ConversationSummarization"
+ "MessagesExtensionLoad"
+ "[Error] Interval already ended"
+ "loadSignpost"
```
