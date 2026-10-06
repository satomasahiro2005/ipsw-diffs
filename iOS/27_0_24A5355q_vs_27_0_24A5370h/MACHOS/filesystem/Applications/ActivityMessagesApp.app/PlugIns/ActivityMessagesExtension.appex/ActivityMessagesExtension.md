## ActivityMessagesExtension

> `/Applications/ActivityMessagesApp.app/PlugIns/ActivityMessagesExtension.appex/ActivityMessagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd178` | `0xd7f8` | **`+0x680`** |
| `__TEXT.__cstring` | `0x656` | `0x716` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0xbf0` | `0xc50` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x460` | `0x4c0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3b8` | `0x408` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x740` | `0x790` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x600` | `0x630` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x220` | `0x238` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__const` | `0x434` | `0x444` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1bb` | `0x1cb` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xd0` | `0xe0` | **`+0x10`** |
| `__DATA.__data` | `0x378` | `0x380` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x308` | `0x310` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.11.0.0
+2027.0.12.0.0

+  - /System/Library/PrivateFrameworks/SpaceAttribution.framework/SpaceAttribution

-  Functions: 203
-  Symbols:   156
-  CStrings:  156
+  Functions: 210
+  Symbols:   161
+  CStrings:  163
Symbols:
+ _NSSearchPathForDirectoriesInDomains
+ _OBJC_CLASS_$_SAPathInfo
+ _OBJC_CLASS_$_SAPathManager
+ _objc_retain_x26
+ _swift_getErrorValue
CStrings:
+ "Error registering caches directory (%@) for space attribution: %@"
+ "Successfully registered caches directory (%@) for space attribution"
+ "com.apple.Fitness"
+ "defaultManager"
+ "initWithURL:"
+ "registerPaths:forBundleID:completionHandler:"
+ "v16@?0@\"NSError\"8"
```
