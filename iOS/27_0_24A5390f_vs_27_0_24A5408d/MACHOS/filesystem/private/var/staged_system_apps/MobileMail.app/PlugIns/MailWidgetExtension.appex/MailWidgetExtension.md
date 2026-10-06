## MailWidgetExtension

> `/private/var/staged_system_apps/MobileMail.app/PlugIns/MailWidgetExtension.appex/MailWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7779c` | `0x8a3bc` | **`+0x12c20`** |
| `__DATA.__bss` | `0x16c8` | `0x27d8` | **`+0x1110`** |
| `__DATA_CONST.__const` | `0x2f90` | `0x3a58` | **`+0xac8`** |
| `__TEXT.__const` | `0x2204` | `0x2ca4` | **`+0xaa0`** |
| `__DATA.__data` | `0x1f60` | `0x2370` | **`+0x410`** |
| `__TEXT.__auth_stubs` | `0x1850` | `0x1c60` | **`+0x410`** |
| `__TEXT.__swift5_capture` | `0x103c` | `0x1324` | **`+0x2e8`** |
| `__TEXT.__oslogstring` | `0x7d6` | `0xaaa` | **`+0x2d4`** |
| `__TEXT.__swift5_fieldmd` | `0x758` | `0x9f4` | **`+0x29c`** |
| `__TEXT.__swift5_typeref` | `0x3f5e` | `0x4186` | **`+0x228`** |
| `__DATA_CONST.__auth_got` | `0xc30` | `0xe38` | **`+0x208`** |
| `__TEXT.__eh_frame` | `0x428` | `0x624` | **`+0x1fc`** |
| `__TEXT.__unwind_info` | `0xbb8` | `0xd70` | **`+0x1b8`** |
| `__TEXT.__constg_swiftt` | `0xcb8` | `0xe50` | **`+0x198`** |
| `__DATA_CONST.__auth_ptr` | `0x610` | `0x788` | **`+0x178`** |
| `__TEXT.__cstring` | `0x12df` | `0x142f` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x5a2` | `0x6b0` | **`+0x10e`** |
| `__TEXT.__objc_methname` | `0x1c05` | `0x1c95` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x5f0` | `0x678` | **`+0x88`** |
| `__TEXT.__swift5_proto` | `0xc8` | `0x150` | **`+0x88`** |
| `__TEXT.__objc_stubs` | `0xd80` | `0xe00` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x1a0` | `0x200` | **`+0x60`** |
| `__TEXT.__swift5_types` | `0x100` | `0x12c` | **`+0x2c`** |
| `__DATA.__objc_selrefs` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  Functions: 1737
-  Symbols:   214
-  CStrings:  565
+  Functions: 2040
+  Symbols:   217
+  CStrings:  598
Symbols:
+ _EMUserDefaultsMailAppGroup
+ _OBJC_CLASS_$_NSFileManager
+ _swift_getExistentialTypeMetadata
CStrings:
+ "+"
+ "-"
+ "/"
+ "Availability check failed, running fallback for %ld task(s) so their requests still complete"
+ "Cached last-good snapshot for key %{public}s"
+ "Data is available, executing task immediately"
+ "Data is not accessible (since %{public}s), running fallback so the request still completes"
+ "Data is not accessible and no cached snapshot exists; returning error entry"
+ "Data is not accessible, completing fetch messages request with error"
+ "Data is not accessible, completing update mailbox request with error"
+ "Data is not accessible; re-serving cached snapshot"
+ "Failed to cache snapshot: %s"
+ "Failed to load cached snapshot: %s"
+ "Ignoring cached snapshot with schema version %ld (expected %ld)"
+ "Invalid number of keys found, expected one."
+ "Library/Caches/WidgetSnapshots"
+ "Loaded cached snapshot for key %{public}s"
+ "Unable to resolve app-group container for %{public}s; snapshot caching disabled"
+ "_"
+ "availability completion has to run on the main thread"
+ "bucketRawValue"
+ "containerURLForSecurityApplicationGroupIdentifier:"
+ "content"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "dateReceived"
+ "defaultManager"
+ "empty"
+ "fileExistsAtPath:"
+ "id"
+ "isFiltered"
+ "isUnread"
+ "json"
+ "messages"
+ "schemaVersion"
+ "sender"
+ "unreadCount"
- "Availability check failed"
- "Data is available, executing task immediateley"
- "Device is locked (since %{public}s), tasks will be ignored"
```
