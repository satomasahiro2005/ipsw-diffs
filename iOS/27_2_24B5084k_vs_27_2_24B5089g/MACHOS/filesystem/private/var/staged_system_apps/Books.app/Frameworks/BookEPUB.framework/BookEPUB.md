## BookEPUB

> `/private/var/staged_system_apps/Books.app/Frameworks/BookEPUB.framework/BookEPUB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x281fe0` | `0x2831b4` | **`+0x11d4`** |
| `__DATA_CONST.__const` | `0x15c80` | `0x15d50` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x9191` | `0x9231` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x145e8` | `0x14648` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xaa60` | `0xaac0` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x24fc` | `0x2558` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x7038` | `0x7090` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x534c` | `0x5394` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0xc963` | `0xc9a3` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x668e` | `0x66ce` | **`+0x40`** |
| `__DATA.__data` | `0xce78` | `0xce98` | **`+0x20`** |
| `__DATA.__objc_const` | `0x10d48` | `0x10d68` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3e60` | `0x3e80` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x44e4` | `0x4504` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x42c0` | `0x42d8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1f48` | `0x1f58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xdf8` | `0xe08` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x6a7d` | `0x6a8d` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x5d68` | `0x5d74` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6713.0.0.0.0
+6715.0.0.0.0

-  Functions: 11410
-  Symbols:   1473
-  CStrings:  5840
+  Functions: 11429
+  Symbols:   1475
+  CStrings:  5851
Symbols:
+ _OBJC_CLASS_$_UIDeferredMenuElement
+ _OBJC_CLASS_$_UIMenuElement
CStrings:
+ " WKContentViewHasAnimations:"
+ " WKScrollViewHasAnimations:"
+ "#PaginationOperation: %s ordinal:%ld waiting for stable presentation update -- %s"
+ "#unhandled_tap Unable to delegate to interactor because the view is not in any window"
+ ":root[__ibooks_reading_mode=\"paged\"] {\n    --background-color: "
+ "BookEPUB/NavigationHistoryMenu.swift"
+ "DeleteRequest #staleCache resulted in %ld deletions for %s"
+ "Failed to look up existing cache row for Document %ld | %s - %@"
+ "animationKeys"
+ "configurationKey "
+ "elementWithUncachedProvider:"
+ "inMemoryOnly"
+ "key BEGINSWITH %@"
+ "matchesRequestedLayoutSize:"
+ "setFetchLimit:"
+ "setIncludesPropertyValues:"
+ "v16@?0@?<v@?@\"NSArray\">8"
- "#PaginationOperation: %s ordinal:%ld waiting for stable presentation update"
- "#unhandled_tap Unable to delegate to interactor because the view is not in any window. How did we get here?"
- ";\n}\n:root[__ibooks_reading_mode=\"paged\"] {\n    --background-color: "
- "DeleteRequest #staleCache resulted in %s deletions"
- "key contains[cd] %@"
- "performBlockAndWait:"
```
