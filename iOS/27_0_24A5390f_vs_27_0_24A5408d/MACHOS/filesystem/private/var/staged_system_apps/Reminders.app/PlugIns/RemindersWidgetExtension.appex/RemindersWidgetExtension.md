## RemindersWidgetExtension

> `/private/var/staged_system_apps/Reminders.app/PlugIns/RemindersWidgetExtension.appex/RemindersWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3200` | `0xd9290` | **`+0x6090`** |
| `__TEXT.__oslogstring` | `0x122a` | `0x14aa` | **`+0x280`** |
| `__TEXT.__auth_stubs` | `0x3be0` | `0x3d80` | **`+0x1a0`** |
| `__DATA_CONST.__const` | `0x2920` | `0x2a90` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x2838` | `0x2968` | **`+0x130`** |
| `__DATA.__data` | `0x5290` | `0x5398` | **`+0x108`** |
| `__DATA.__bss` | `0xa750` | `0xa650` | **`-0x100`** |
| `__DATA_CONST.__auth_got` | `0x1df8` | `0x1ec8` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x194c` | `0x1a0c` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0xd60` | `0xe00` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0xc4fc` | `0xc594` | **`+0x98`** |
| `__TEXT.__cstring` | `0x39d9` | `0x3a69` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x27b0` | `0x2820` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x2398` | `0x2400` | **`+0x68`** |
| `__TEXT.__const` | `0x9324` | `0x9374` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x10f8` | `0x1120` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x121a` | `0x123a` | **`+0x20`** |
| `__DATA.__common` | `0x380` | `0x368` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1178` | `0x1190` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x63a` | `0x64a` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x258` | `0x264` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x19c` | `0x1a8` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x534` | `0x52c` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x210` | `0x208` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x1d4` | `0x1d8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4043.0.0.0.0
+4046.11.0.0.0

+  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 3331
-  Symbols:   232
-  CStrings:  388
+  Functions: 3373
+  Symbols:   235
+  CStrings:  398
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ _swift_initEnumMetadataMultiPayload
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
CStrings:
+ "TTRNewWidgetInteractor unexpected .nextFiveDays bucket on .regular style"
+ "TTRNewWidgetInteractor unexpected unknown scheduled bucket"
+ "Today view - afternoon section title"
+ "Today view - morning section title"
+ "Today view - tonight section title"
+ "UrgentAlarmReminderView: could not resolve reschedule URL — hiding Later button"
+ "Widget presenter: %ld reminder(s) not attributable to any section boundary"
+ "Widget presenter: custom smart list unavailable (likely transient); showing placeholder instead of the default list {customSmartListID: %{public}@}"
+ "Widget presenter: list unavailable (likely transient — store loading or revalidating); showing placeholder instead of the default list {listID: %{public}@}"
+ "isNoSuchObjectError:forObjectID:"
+ "sectionless-orphaned"
+ "today-beforeToday"
+ "today-todayAllDay"
- "Name of rem object url"
- "Name of urgent alarm snooze live activity's Later button"
- "objectIDWithURL:"
```
