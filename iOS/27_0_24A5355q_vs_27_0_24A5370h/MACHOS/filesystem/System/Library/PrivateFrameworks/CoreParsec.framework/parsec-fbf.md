## parsec-fbf

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsec-fbf`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xffb68` | `0x100880` | **`+0xd18`** |
| `__DATA_CONST.__const` | `0xad10` | `0xafa0` | **`+0x290`** |
| `__TEXT.__swift5_capture` | `0x173c` | `0x183c` | **`+0x100`** |
| `__TEXT.__cstring` | `0x6101` | `0x61b1` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x3fed` | `0x403d` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x60d0` | `0x60a0` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x3c02` | `0x3bd2` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x4190` | `0x41b8` | **`+0x28`** |
| `__DATA.__data` | `0x8180` | `0x8190` | **`+0x10`** |
| `__TEXT.__const` | `0xc1e0` | `0xc1d0` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x3cae` | `0x3cbc` | **`+0xe`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.53.23.1.2
+3600.56.7.0.0

-  Functions: 6878
+  Functions: 6915

-  CStrings:  2005
+  CStrings:  2008
CStrings:
+ "%s batch housekeeping: nothing purged."
+ "BatchHousekeepingMaxPurgeCount"
+ "Failed to collect batch telemetry: %s [%@]"
+ "GROUP BY s.batchId ORDER BY s.rowid LIMIT "
+ "GROUP BY s.batchId;"
+ "com.apple.safari.startpage.favorites"
+ "com.apple.safari.startpage.icloud"
+ "com.apple.safari.startpage.recentlyclosedtabs"
+ "com.apple.safari.startpage.recentsearches"
+ "com.apple.safari.startpage.suggestions"
+ "doBatchesHousekeepingWithLimit:"
+ "pegasusKitContextAndPATFetch"
- "%s batch housekeeping complete: did nothing."
- "Failed to initialize database: %s [%@]"
- "Failed to process batch telemetry: %s [%@]"
- "com.apple.startpage.favorites"
- "com.apple.startpage.icloud"
- "com.apple.startpage.recentlyclosedtabs"
- "com.apple.startpage.recentsearches"
- "com.apple.startpage.suggestions"
- "doBatchesHousekeeping"
```
