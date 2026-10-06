## HybridSearchAdapter

> `/System/Library/PrivateFrameworks/HybridSearchAdapter.framework/HybridSearchAdapter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x195b68` | `0x199124` | **`+0x35bc`** |
| `__DATA.__bss` | `0x7ef0` | `0x87f0` | **`+0x900`** |
| `__TEXT.__const` | `0x12fd4` | `0x13734` | **`+0x760`** |
| `__TEXT.__unwind_info` | `0x4e80` | `0x5408` | **`+0x588`** |
| `__AUTH_CONST.__const` | `0x10158` | `0x10538` | **`+0x3e0`** |
| `__TEXT.__swift5_fieldmd` | `0x302c` | `0x31fc` | **`+0x1d0`** |
| `__TEXT.__swift5_reflstr` | `0x2377` | `0x2507` | **`+0x190`** |
| `__DATA.__data` | `0x31a0` | `0x3318` | **`+0x178`** |
| `__AUTH.__data` | `0x2f08` | `0x3038` | **`+0x130`** |
| `__TEXT.__constg_swiftt` | `0x2524` | `0x2630` | **`+0x10c`** |
| `__TEXT.__oslogstring` | `0x13bd` | `0x14bd` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0xd82c` | `0xd8ac` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x1198` | `0x1210` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x463e` | `0x46b4` | **`+0x76`** |
| `__TEXT.__swift5_proto` | `0x4a0` | `0x4e8` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x2640` | `0x2680` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3311` | `0x32f1` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x370` | `0x38c` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0xb78` | `0xb94` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x248` | `0x260` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x6f8` | `0x6e8` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x540` | `0x530` | **`-0x10`** |
| `__TEXT.__swift5_types2` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-67.0.0.0.0
+73.2.0.0.0

-  Functions: 7998
-  Symbols:   234
-  CStrings:  504
+  Functions: 8125
+  Symbols:   235
+  CStrings:  507
Symbols:
+ _swift_initStructMetadata
CStrings:
+ "MailSearchClient.%s: Request %s completed with initial count %ld. Elapsed time: %s."
+ "MailSearchClient.liveDistinctMessageCount"
+ "MailSearchClient.liveQuery: app-visibility suppression %{public}s"
+ "MailSearchClient.resolveContactEmails"
+ "TranscriptSearchFilter.merge: mismatched filter types (%s, %s)"
+ "[ContactNameSearcher] findContactsByName: %ld recalled, %ld matched name"
+ "draftMail"
+ "liveDistinctMessageCount(filter:configuration:)"
+ "liveQuery(query:configuration:)"
+ "mail"
+ "mailAttachment"
- "%s"
- "MailSearchClient.retrieveIdentifiers"
- "MailSearchClient.search() called with empty queries"
- "MailSearchClient.search(queries:)"
- "MailSearchClient.search(static)"
- "[ContactNameSearcher] findContactsByName: found %ld contacts"
- "liveQuery(query:)"
- "search(queries:configuration:)"
```
