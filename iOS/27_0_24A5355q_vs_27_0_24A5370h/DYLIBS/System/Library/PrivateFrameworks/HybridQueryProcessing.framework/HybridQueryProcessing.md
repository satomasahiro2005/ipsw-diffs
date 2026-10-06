## HybridQueryProcessing

> `/System/Library/PrivateFrameworks/HybridQueryProcessing.framework/HybridQueryProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcecd8` | `0xd6a24` | **`+0x7d4c`** |
| `__DATA.__bss` | `0x21b0` | `0x2930` | **`+0x780`** |
| `__TEXT.__const` | `0x302c` | `0x353c` | **`+0x510`** |
| `__AUTH_CONST.__const` | `0x61e0` | `0x6628` | **`+0x448`** |
| `__TEXT.__eh_frame` | `0x20a8` | `0x2418` | **`+0x370`** |
| `__TEXT.__oslogstring` | `0x3a82` | `0x3c82` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0xfac` | `0x1120` | **`+0x174`** |
| `__TEXT.__unwind_info` | `0x1528` | `0x1678` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0xbe8` | `0xd2c` | **`+0x144`** |
| `__TEXT.__swift5_typeref` | `0x1648` | `0x1754` | **`+0x10c`** |
| `__DATA.__common` | `0x148` | `0x88` | **`-0xc0`** |
| `__TEXT.__swift5_reflstr` | `0xb9b` | `0xc5b` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xea0` | `0xf50` | **`+0xb0`** |
| `__AUTH.__data` | `0x4c8` | `0x570` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x1078` | `0x1118` | **`+0xa0`** |
| `__DATA.__data` | `0xe18` | `0xeb0` | **`+0x98`** |
| `__TEXT.__swift5_proto` | `0x12c` | `0x16c` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2083` | `0x2053` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0xfc` | `0x120` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x110` | `0x120` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0x74` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x84` | `0x90` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8e8` | `0x8e0` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x149c` | `0x14a4` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x148` | `0x150` | **`+0x8`** |

### Other Changes

```diff

-53.0.0.0.0
+57.0.1.0.0

-  Functions: 3435
-  Symbols:   178
-  CStrings:  510
+  Functions: 3584
+  Symbols:   181
+  CStrings:  514
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ __swiftEmptyDictionarySingleton
+ _swift_getObjCClassFromMetadata
CStrings:
+ "([A-Za-z]):(?=[^\\s/:])"
+ "ASTMailQueryBuilderAbbreviationExpansionEnabled"
+ "Duplicate abbreviation key '%{public}s' in abbreviations.json — keeping first ('%{public}s'), discarding ('%{public}s')"
+ "Extracted %ld U2 token labels"
+ "Failed to load abbreviations.json: %{public}s"
+ "HQP MailDomain: Dropped invalid query (no search terms, predicate, or orderBy) for %s"
+ "HQP Planner Event: unmapped event type arg label %s — query will not be filtered by eventType"
+ "HQP Planner MailDomain: after validation — mail=%ldq draft=%ldq attachment=%ldq"
+ "No rule-based parse found; falling back to all %ld parse(s)"
+ "OnDeviceQueryParser: auto-cooldown after %s of inactivity"
+ "Selecting %ld rule-based parse(s) out of %ld total; dropping %ld U2 parse(s)"
+ "com.apple.HybridQueryProcessing"
+ "com_apple_mail_dateReceived"
+ "kMDItemMailboxes=\"\\*([^\"]+)\""
- "ARG_EVENT_TYPE_APPOINTMENT"
- "ARG_EVENT_TYPE_CAR_RENTAL"
- "ARG_EVENT_TYPE_PARTY"
- "ARG_EVENT_TYPE_TICKET_SHOW"
- "ARG_EVENT_TYPE_TICKET_TRANSPORT"
- "ARG_LOCATION_ARRIVAL"
- "ARG_LOCATION_DEPARTURE"
- "Extracted %ld U2 token labels from first parse"
- "HQP MailDomain: Dropped invalid query (no search terms or predicate) for %s"
- "OnDeviceQueryParser: auto-cooldown after 120s of inactivity"
```
