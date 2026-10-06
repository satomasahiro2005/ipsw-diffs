## ArchiveService

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/XPCServices/ArchiveService.xpc/ArchiveService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d8dc` | `0x2dde8` | **`+0x50c`** |
| `__TEXT.__oslogstring` | `0x1325` | `0x140d` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0x3f68` | `0x4020` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x23d7` | `0x2417` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x10e0` | `0x10c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1b22` | `0x1b42` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xb8f` | `0xbaf` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1d80` | `0x1da0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x11f0` | `0x1208` | **`+0x18`** |
| `__DATA.__bss` | `0x7e0` | `0x7f0` | **`+0x10`** |
| `__TEXT.__const` | `0x8da` | `0x8ea` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x890` | `0x898` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6c4` | `0x6cc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1857.0.0.0.0
+1857.1.4.0.0

-  Functions: 689
-  Symbols:   742
-  CStrings:  817
+  Functions: 691
+  Symbols:   741
+  CStrings:  822
Symbols:
+ __Z31FileProviderInternalErrorDomainv
- __Z19kTStringLiteralDataIJLc104ELc102ELc115EEE
- __ZN23FIProviderDomainFetcherC2Ev
CStrings:
+ "@48@0:8@16B24B28^i32^@40"
+ "Apple Archive extraction failed while closing its streams (extract %d, decode %d)"
+ "B44@?0@\"NSArray\"8@\"NSURL\"16i24@\"NSProgress\"28^@36"
+ "B48@0:8@16@24^@32^@40"
+ "Failed to open temporary directory %{public}@: %{darwin.errno}d"
+ "Lookup of '%{public}@' needed FP's cache, but nothing is monitoring the provider list"
+ "NSFileProviderInternalErrorDomain"
+ "_removePlaceholder:andMoveItemIntoPlace:resultingItem:error:"
+ "_temporaryURLAppropriateForURL:calledFromCLI:calledFromLegacyAPI:rootFD:error:"
- "@40@0:8@16B24B28^@32"
- "B40@?0@\"NSArray\"8@\"NSURL\"16@\"NSProgress\"24^@32"
- "_temporaryURLAppropriateForURL:calledFromCLI:calledFromLegacyAPI:error:"
- "hfs"
```
