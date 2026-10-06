## TextUnderstandingRuntime

> `/System/Library/PrivateFrameworks/TextUnderstandingRuntime.framework/TextUnderstandingRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21641c` | `0x21b5f8` | **`+0x51dc`** |
| `__DATA.__bss` | `0x1b040` | `0x19b30` | **`-0x1510`** |
| `__DATA_DIRTY.__bss` | `0x2900` | `0x3480` | **`+0xb80`** |
| `__DATA_DIRTY.__data` | `0x2df0` | `0x3650` | **`+0x860`** |
| `__TEXT.__eh_frame` | `0x13758` | `0x13fa0` | **`+0x848`** |
| `__AUTH_CONST.__const` | `0xe758` | `0xe0d0` | **`-0x688`** |
| `__TEXT.__const` | `0x123e8` | `0x11de8` | **`-0x600`** |
| `__DATA.__data` | `0x30d0` | `0x2c40` | **`-0x490`** |
| `__AUTH_CONST.__objc_const` | `0x25a0` | `0x29e8` | **`+0x448`** |
| `__TEXT.__swift5_fieldmd` | `0x4014` | `0x3cfc` | **`-0x318`** |
| `__TEXT.__swift_as_cont` | `0xab4` | `0xc1c` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x8eea` | `0x904a` | **`+0x160`** |
| `__AUTH.__data` | `0xf38` | `0xe00` | **`-0x138`** |
| `__TEXT.__cstring` | `0xcd02` | `0xcbd2` | **`-0x130`** |
| `__TEXT.__swift5_capture` | `0x1bac` | `0x1cdc` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x6ea8` | `0x6fc8` | **`+0x120`** |
| `__DATA.__common` | `0x288` | `0x178` | **`-0x110`** |
| `__AUTH_CONST.__auth_got` | `0x3f68` | `0x4018` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x1c0` | `0x120` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x498` | `0x538` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x494f` | `0x49eb` | **`+0x9c`** |
| `__TEXT.__swift5_assocty` | `0xf10` | `0xe80` | **`-0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0xe28` | `0xea8` | **`+0x80`** |
| `__DATA_DIRTY.__common` | `0x2b0` | `0x330` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x2e8c` | `0x2e1c` | **`-0x70`** |
| `__TEXT.__swift5_proto` | `0xfe0` | `0xf94` | **`-0x4c`** |
| `__TEXT.__swift_as_ret` | `0x698` | `0x6dc` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0xa0` | `0xe0` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x4e4` | `0x520` | **`+0x3c`** |
| `__TEXT.__objc_methlist` | `0x6f0` | `0x728` | **`+0x38`** |
| `__DATA_CONST.__objc_protolist` | `0xa8` | `0xc8` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x494` | `0x478` | **`-0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x138` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x118` | **`-0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x58` | `0x68` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x3520` | `0x352c` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x84` | `0x88` | **`+0x4`** |

### Other Changes

```diff

-167.1.0.0.0
+173.0.0.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 11597
-  Symbols:   573
-  CStrings:  950
+  Functions: 11608
+  Symbols:   586
+  CStrings:  944
Symbols:
+ _CFPreferencesCopyAppValue
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_deviceClassNumber
+ _OBJC_CLASS_$_ECEmailAddress
+ _OBJC_CLASS_$_EMMessageListItemPredicates
+ _OBJC_CLASS_$_EMQuery
+ _OBJC_CLASS_$_NSCompoundPredicate
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_CLASS_$_NSSortDescriptor
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get_throwing
+ _swift_release_x6
CStrings:
+ "ActionItemsProcessor: PCC extraction using instructionsPrefix %{public}s for documentKind %{public}s"
+ "AppCanShowSiriSuggestionsBlacklist"
+ "CarKeyDataPipeline: Siri Suggestions are disabled in Wallet settings"
+ "EventsPipeline: device not eligible for Apple Intelligence, geocoding regex events and returning"
+ "EventsProcessor: PCC extraction using instructionsPrefix %{public}s for documentKind %{public}s"
+ "MailSmartRepliesProfileProcessor: Error fetching content for pair: %@"
+ "MailSmartRepliesProfileProcessor: Error fetching emails: %@"
+ "MailSmartRepliesProfileProcessor: Failed to fetch mail messages: %@"
+ "MailSmartRepliesProfileProcessor: Fetched %ld emails from Spotlight, %ld from Mail"
+ "MailSmartRepliesProfileProcessor: Fetching content for message %{sensitive}s"
+ "MailSmartRepliesProfileProcessor: Not enough hydratable email pairs with %{sensitive}s, skipping"
+ "MailSmartRepliesProfileProcessor: Querying Mail for recent emails between the following participants: %{sensitive}s"
+ "MailSmartRepliesProfileProcessor: claiming in-flight slot for %{private}s"
+ "MailSmartRepliesProfileProcessor: extraction already in-flight for %{private}s: skipping"
+ "MailSmartRepliesProfileProcessor: releasing in-flight slot for %{private}s"
+ "MessagesSmartRepliesProfileProcessor: claiming in-flight slot for %{private}s"
+ "MessagesSmartRepliesProfileProcessor: conversation has a recently updated profile, skipping smartRepliesProfiles request"
+ "MessagesSmartRepliesProfileProcessor: conversation is a group chat, skipping smartRepliesProfiles request"
+ "MessagesSmartRepliesProfileProcessor: document %{private}s has no conversation identifier"
+ "MessagesSmartRepliesProfileProcessor: extraction already in-flight for %{private}s: skipping"
+ "MessagesSmartRepliesProfileProcessor: failed to fetch conversation for %{private}s: %@"
+ "MessagesSmartRepliesProfileProcessor: fetched %{private}ld items for %{private}s"
+ "MessagesSmartRepliesProfileProcessor: invoked SR profile processor"
+ "MessagesSmartRepliesProfileProcessor: releasing in-flight slot for %{private}s"
+ "Pipeline: document language '%{private}s' is not supported"
+ "Pipeline: language support check failed, treating as bypass: %@"
+ "The Digital Key feature allows a user to pair (also referred to as create or add) a digital key on their phone. manufacturer message contains the details needed to set up the key. Extract those details according to the schema, paying special attention to language that indicates the key is already paired with a device, which determines the is_already_paired field."
+ "The name of the person that received this communication from the car company"
+ "com.apple.oee.event.generic.v1"
+ "com.apple.oee.reminder.generic.v1"
+ "passcode or activation code to use for car key provisioning or pairing"
+ "set to true if the message indicates that the digital key is already paired with a device. set to false for all other cases."
+ "textunderstandingd - fetch emails"
- "<Processor: ConversationFetchingProcessor>"
- "ConversationFetchingProcessor: conversation has a recently updated profile, skipping smartRepliesProfiles request"
- "ConversationFetchingProcessor: conversation is a group chat, skipping smartRepliesProfiles request"
- "ConversationFetchingProcessor: document %{private}s has nil conversation identifier"
- "ConversationFetchingProcessor: failed to fetch conversation for %{private}s: %@"
- "ConversationFetchingProcessor: fetched %{private}ld items for %{private}s"
- "ConversationFetchingProcessor: unsupported document type: "
- "EventsProcessor: V2 prompt template not found, falling back to V1"
- "Extract information necessary for car key provisioning. Especially whether the car key is already paired or not."
- "LanguageIdentificationProcessor: document language %s is not supported"
- "MailSmartRepliesProfileProcessor: Error fetching EMMessage for email with identifier %{sensitive}s: %@"
- "MailSmartRepliesProfileProcessor: Error fetching HTML body for email with identifier %{sensitive}s: %@"
- "MailSmartRepliesProfileProcessor: Error fetching email content for message with ID %{sensitive}s: %@"
- "MailSmartRepliesProfileProcessor: Error fetching email identifiers from Spotlight: %@"
- "MailSmartRepliesProfileProcessor: Error while fetching message for identifier %{sensitive}s: %@"
- "MailSmartRepliesProfileProcessor: Failed to cast result from messageFuture.async() to EMMessage for identifier %{sensitive}s"
- "MailSmartRepliesProfileProcessor: Fetched %ld emails from Spotlight"
- "MessagesSmartRepliesProfileProcessor conversation identifier not found - cannot extract profile"
- "MessagesSmartRepliesProfileProcessor invoked SR profile processor"
- "MessagesSmartRepliesProfileProcessor: ConversationFetchingProcessor must return non-nil fetchedConversation or throw, but nil fetchedConversation was returned"
- "OrdersPipeline: document language '%{private}s' is not supported by Wallet"
- "OrdersPipeline: failed to fetch supported languages from FinanceKit: %@"
- "ReceiptsPipeline: document language '%{private}s' is not supported by Wallet"
- "ReceiptsPipeline: document language is nil"
- "ReceiptsPipeline: failed to fetch supported languages from FinanceKit: %@"
- "TextUnderstandingRuntime/ConversationFetchingProcessor.swift"
- "The name of the person that received this communication from car company"
- "cancel_reservation"
- "com.apple.textComposition.OpenEndedExtract.eventwithsmartactions"
- "com.apple.textComposition.OpenEndedExtract.eventwithsmartactions.flight"
- "flight_seat_number"
- "manage_reservation"
- "passcode or activation code to use for provisioning purpose"
- "reservation_check_in"
- "reservation_management_actions"
- "reservation_phone"
- "support_url_text"
- "true if car key successfully provisioned on this device. false otherwise"
- "view_reservation"
```
