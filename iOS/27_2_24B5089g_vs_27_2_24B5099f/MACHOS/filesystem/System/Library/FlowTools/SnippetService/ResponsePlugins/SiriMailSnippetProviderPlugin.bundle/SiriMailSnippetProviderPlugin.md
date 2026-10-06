## SiriMailSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriMailSnippetProviderPlugin.bundle/SiriMailSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd5fc` | `0xdff8` | **`+0x9fc`** |
| `__TEXT.__oslogstring` | `0xaa1` | `0xb51` | **`+0xb0`** |
| `__DATA.__data` | `0x510` | `0x5b0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x218` | `0x2a8` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x160` | `0x1e0` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0x83` | `0xfd` | **`+0x7a`** |
| `__TEXT.__objc_methname` | `0x286` | `0x2f5` | **`+0x6f`** |
| `__TEXT.__constg_swiftt` | `0xd0` | `0x114` | **`+0x44`** |
| `__TEXT.__const` | `0x3d0` | `0x400` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x118` | `0x138` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdd` | `0xbd` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x8c` | `0xa8` | **`+0x1c`** |
| `__TEXT.__eh_frame` | `0x200` | `0x218` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1ac` | `0x1c0` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x158` | `0x168` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xb60` | `0xb70` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x238` | `0x248` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x2c` | `0x33` | **`+0x7`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.14.1.0.0
+3605.17.1.0.0

-  Functions: 256
-  Symbols:   114
-  CStrings:  100
+  Functions: 253
+  Symbols:   117
+  CStrings:  105
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ _objc_release_x27
+ _swift_deletedMethodError
+ _swift_getObjCClassFromMetadata
+ _swift_release_x28
- _objc_release_x28
- _swift_getTypeByMangledNameInContextInMetadataState2
CStrings:
+ "#DraftMailSnippetHandler supportsAsync - .inform draft is a grouped result-collection member (search/list result), deferring to default handler, returning .unsupported"
+ "_TtC29SiriMailSnippetProviderPluginP33_9F9C9C36B117B745FAA3BB951D42CDD724SnippetPluginBundleToken"
+ "bundleForClass:"
+ "localizations"
+ "preferredLocalizationsFromArray:"
+ "preferredLocalizationsFromArray:forPreferences:"
- "senderAvatarData"
```
