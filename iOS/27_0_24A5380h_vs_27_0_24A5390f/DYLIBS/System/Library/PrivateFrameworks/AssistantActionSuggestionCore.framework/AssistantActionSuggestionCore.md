## AssistantActionSuggestionCore

> `/System/Library/PrivateFrameworks/AssistantActionSuggestionCore.framework/AssistantActionSuggestionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x229328` | `0x232ad8` | **`+0x97b0`** |
| `__TEXT.__eh_frame` | `0xf214` | `0xf6c4` | **`+0x4b0`** |
| `__TEXT.__cstring` | `0x7376` | `0x7646` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x7436` | `0x7656` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x50f0` | `0x52a0` | **`+0x1b0`** |
| `__TEXT.__unwind_info` | `0x4a68` | `0x4ba0` | **`+0x138`** |
| `__AUTH_CONST.__const` | `0x54f0` | `0x55e8` | **`+0xf8`** |
| `__AUTH.__data` | `0xb40` | `0xc20` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x2594` | `0x2674` | **`+0xe0`** |
| `__TEXT.__const` | `0xbac8` | `0xbb68` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x2dbc` | `0x2e50` | **`+0x94`** |
| `__TEXT.__swift5_typeref` | `0x3bf2` | `0x3c7e` | **`+0x8c`** |
| `__DATA.__data` | `0x2100` | `0x2188` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x730` | `0x78c` | **`+0x5c`** |
| `__AUTH.__objc_data` | `0x258` | `0x2a8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x2a54` | `0x2aa4` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x33c8` | `0x33f0` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0xbbc` | `0xbe4` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x528` | `0x544` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x1970` | `0x1988` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x878` | `0x890` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x168` | `0x178` | **`+0x10`** |
| `__DATA.__common` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x200` | `0x208` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x4410` | `0x4408` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x4f0` | `0x4f8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x370` | `0x374` | **`+0x4`** |

### Other Changes

```diff

-664.0.2.1.0
+667.0.0.0.0

-  Functions: 4916
-  Symbols:   1984
-  CStrings:  1154
+  Functions: 4977
+  Symbols:   1995
+  CStrings:  1180
Symbols:
+ __DATA__TtC29AssistantActionSuggestionCore20RecentExecutionStore
+ __IVARS__TtC29AssistantActionSuggestionCore20RecentExecutionStore
+ __METACLASS_DATA__TtC29AssistantActionSuggestionCore20RecentExecutionStore
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic Si_____c 32AssistantActionSuggestionSupport16SemanticIdentityO
+ _symbolic So19ATXAppInFocusStreamC
+ _symbolic _____ 29AssistantActionSuggestionCore20RecentExecutionStoreC
+ _symbolic _____4uuid_SS6clientt 10Foundation4UUIDV
+ _symbolic _____Sg 10Foundation20PersonNameComponentsV
+ _symbolic _____SgXw 29AssistantActionSuggestionCore18CAPESessionManagerC
+ _symbolic _____SgXwz_Xx 29AssistantActionSuggestionCore18CAPESessionManagerC
+ _symbolic _____Sg_SSSgt 32AssistantActionSuggestionSupport13ContactSchemaV6PersonV4NameO
+ _symbolic _____ySiG 11SwiftSQLite11ScalarQueryV
+ _symbolic _____y_____4uuid_SS6clienttG s23_ContiguousArrayStorageC 10Foundation4UUIDV
- _expf
- _symbolic ______Sft 32AssistantActionSuggestionSupport16SemanticIdentityO
- _symbolic _____y_____SfG s18_DictionaryStorageC 32AssistantActionSuggestionSupport16SemanticIdentityO
CStrings:
+ "%s Finished inserting action %s to recently executed database"
+ "%s RecentExecutionStore: failed to record execution for %s: %@"
+ "CALL_DYNAMIC_TITLE_BUSINESS"
+ "CALL_DYNAMIC_TITLE_PERSON"
+ "CAPE session %s handling request for client: %s"
+ "Call action, business name; no person-only honorifics"
+ "Call action, e.g. Call John"
+ "Call action, person name; honorifics OK (e.g. ja さん)"
+ "ComposeFollowupProvider: skipping entry with creationDate %s older than %fs cutoff"
+ "Disposing CAPE session %s (client: %s)"
+ "EMAIL_DYNAMIC_TITLE_BUSINESS"
+ "EMAIL_DYNAMIC_TITLE_PERSON"
+ "Email action, business name; no person-only honorifics"
+ "Email action, e.g. Email Delta"
+ "Email action, person name; honorifics OK (e.g. ja さん)"
+ "Failed to evict stale recent execution entries: %@"
+ "Filtering out action from %s because the app is internal"
+ "InternalAppsIncluded"
+ "Launch-count tiebreak for %s: %s wins (%s=%ld, %s=%ld)"
+ "MESSAGE_DYNAMIC_TITLE_BUSINESS"
+ "MESSAGE_DYNAMIC_TITLE_PERSON"
+ "Message action, business name; no person-only honorifics"
+ "Message action, e.g. Message Delta"
+ "Message action, person name; honorifics OK (e.g. ja さん)"
+ "NoteReminderCoexistence: dropping createNote — reminders=%{public}ld vs notes=%{public}ld, ratio=%{public}f"
+ "NoteReminderCoexistence: dropping createReminder — notes=%{public}ld vs reminders=%{public}ld, ratio=%{public}f"
+ "RecentExecutionStore lookup failed for %{public}s: %@"
+ "RecentExecutionStore: evicted %ld stale execution rows"
+ "RecentExecutions"
+ "RecentExecutions.db"
+ "Removing stale CAPE session %s (client: %s)"
+ "com.apple.appPrediction.recentExecutionStore"
+ "recent_executions"
+ "semantic_identity"
- "Disposing CAPE session with UUID: %s"
- "Dynamic title for call actions, e.g. Call John"
- "Dynamic title for email actions, e.g. Email Delta"
- "Dynamic title for message actions, e.g. Message Delta"
- "NoteReminderCoexistence: filtering out createNote (ratio %{public}fx)"
- "NoteReminderCoexistence: filtering out createReminder (ratio %{public}fx)"
- "NoteReminderCoexistence: softmax scores — reminder=%{public}f, note=%{public}f, ratio=%{public}f, threshold=%{public}f"
- "Removing stale CAPE session with UUID: %s"
```
