## fileproviderctl

> `/usr/bin/fileproviderctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff44` | `0x10418` | **`+0x4d4`** |
| `__TEXT.__cstring` | `0x1dd1` | `0x1f01` | **`+0x130`** |
| `__TEXT.__objc_methname` | `0x1cfe` | `0x1d9f` | **`+0xa1`** |
| `__TEXT.__objc_stubs` | `0x1f80` | `0x2020` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0x1900` | `0x1980` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1058` | `0x1098` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x968` | `0x990` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2c8` | **`+0x20`** |
| `__DATA.__bss` | `0x340` | `0x350` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xc60` | `0xc70` | **`+0x10`** |
| `__TEXT.__const` | `0x2da` | `0x2ca` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x468` | `0x478` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x640` | `0x648` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4838.0.29.502.2
+4838.0.70.0.0

-  Functions: 252
-  Symbols:   343
-  CStrings:  661
+  Functions: 256
+  Symbols:   348
+  CStrings:  670
Symbols:
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSISO8601DateFormatter
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _dispatch_once
CStrings:
+ "/var/mobile/Library/Application Support/FileProvider/com.apple.FileProvider.LocalStorage/FPDPurgeableRepairerReport.plist"
+ "====== FPDPurgeableRepairerReport ======\n%@\n====== end FPDPurgeableRepairerReport ======\n"
+ "Couldn't read purgeable-repair report: %@.\n"
+ "Couldn't render purgeable-repair report as JSON: %@.\n"
+ "dataWithContentsOfURL:options:error:"
+ "dataWithJSONObject:options:error:"
+ "dictionaryWithCapacity:"
+ "initWithData:encoding:"
+ "propertyListWithData:options:format:error:"
```
