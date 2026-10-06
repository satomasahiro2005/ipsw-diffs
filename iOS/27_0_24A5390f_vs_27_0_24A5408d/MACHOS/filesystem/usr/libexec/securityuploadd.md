## securityuploadd

> `/usr/libexec/securityuploadd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12cf4` | `0x13210` | **`+0x51c`** |
| `__TEXT.__cstring` | `0xfd8` | `0x107e` | **`+0xa6`** |
| `__DATA_CONST.__cfstring` | `0x1500` | `0x15a0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0xdf5` | `0xe38` | **`+0x43`** |
| `__TEXT.__objc_methname` | `0x2391` | `0x23c8` | **`+0x37`** |
| `__TEXT.__objc_methtype` | `0x5ed` | `0x616` | **`+0x29`** |
| `__DATA_CONST.__const` | `0xc20` | `0xc48` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x27c` | `0x290` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x8e8` | `0x8fc` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x408` | `0x418` | **`+0x10`** |
| `__DATA.__objc_const` | `0xe38` | `0xe40` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xa40` | `0xa48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  Functions: 328
+  Functions: 331

-  CStrings:  768
+  CStrings:  779
CStrings:
+ "62460.2.1"
+ "No such topic: %@"
+ "Resetting collected metrics for topic: %@"
+ "enumerateEventsWithLimit:usingBlock:"
+ "private/TrustStore.sqlite3"
+ "private/TrustStore.sqlite3-journal"
+ "private/TrustStore.sqlite3-shm"
+ "private/TrustStore.sqlite3-wal"
+ "reset"
+ "reset: no such topic: %@"
+ "resetMetricsForTopic:reply:"
+ "v16@?0@\"NSDictionary\"8"
+ "v32@0:8@\"NSString\"16@?<v@?B@\"NSError\">24"
- "62460.0.55.0.1"
- "allEvents"
```
