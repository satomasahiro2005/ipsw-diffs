## TextUnderstandingRuntime

> `/System/Library/PrivateFrameworks/TextUnderstandingRuntime.framework/TextUnderstandingRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2372c8` | `0x23a3d8` | **`+0x3110`** |
| `__AUTH_CONST.__const` | `0xe898` | `0xfbb8` | **`+0x1320`** |
| `__TEXT.__swift5_capture` | `0x1d9c` | `0x252c` | **`+0x790`** |
| `__TEXT.__oslogstring` | `0x97aa` | `0x93ca` | **`-0x3e0`** |
| `__TEXT.__const` | `0x12a78` | `0x12b98` | **`+0x120`** |
| `__TEXT.__cstring` | `0x4852` | `0x4932` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x3f04` | `0x3fcc` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x2e8c` | `0x2f3c` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x76c0` | `0x7770` | **`+0xb0`** |
| `__AUTH.__data` | `0xe48` | `0xee0` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x3770` | `0x37b8` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x1567c` | `0x15640` | **`-0x3c`** |
| `__TEXT.__swift5_typeref` | `0x4cff` | `0x4d33` | **`+0x34`** |
| `__DATA.__bss` | `0x1b030` | `0x1b050` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x42a8` | `0x4298` | **`-0x10`** |
| `__DATA.__data` | `0x2ef0` | `0x2ee0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf00` | `0xf10` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3778` | `0x3780` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x105c` | `0x1064` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xd10` | `0xd18` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x580` | `0x588` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x90` | `0x94` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x4a4` | `0x4a8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x774` | `0x778` | **`+0x4`** |

### Other Changes

```diff

-187.0.0.0.0
+192.0.0.0.0

-  Functions: 12193
+  Functions: 12418

-  CStrings:  995
+  CStrings:  991
Symbols:
+ _OBJC_CLASS_$_NSLocale
- _swift_release_x15
CStrings:
+ "ReceiptsPipeline: email is a reply"
+ "checkAvailability: GenerativeModelsAvailability returned restricted for use case %s: %s"
+ "checkAvailability: GenerativeModelsAvailability returned unavailable for use case %s: %s"
+ "checkAvailability: GenerativeModelsAvailability returned unknown availability for use case %s"
+ "checkAvailability: Locale does not have a language code for use case %s"
+ "com.apple.oee.event.generic.v2"
+ "com.apple.oee.event.messages.v2"
+ "com.apple.oee.reminder.generic.v2"
+ "com.apple.oee.reminder.messages.v2"
+ "due_date_needs_resolution"
+ "end_date_needs_resolution"
+ "start_date_needs_resolution"
+ "start_date_string"
+ "start_time_string"
+ "textUnderstanding.TextEventExtraction.Mail"
- "CarKeyDataProcessor: language is nil"
- "MessagesProfileExtractionAdapter: GenerativeModelsAvailability check returned restricted: %s"
- "MessagesProfileExtractionAdapter: GenerativeModelsAvailability check returned unavailable: %s"
- "MessagesProfileExtractionAdapter: GenerativeModelsAvailability check returned unknown availability"
- "MessagesProfileExtractionAdapter: Locale does not have a language code"
- "OEEGatingProcessor: Classification failed: %@. Allowing extraction to proceed."
- "OEEGatingProcessor: Failed to initialize 9M classifier adapter: %@. Allowing extraction to proceed."
- "OEEGatingProcessor: LanguageIdentificationProcessor returned nil. Allowing extraction to proceed."
- "OpenEndedExtractionAdapter: GenerativeModelsAvailability check returned restricted: %s"
- "OpenEndedExtractionAdapter: GenerativeModelsAvailability check returned unavailable: %s"
- "OpenEndedExtractionAdapter: GenerativeModelsAvailability check returned unknown availability"
- "OpenEndedExtractionSchemaDetector: GenerativeModelsAvailability check returned restricted: %s"
- "OpenEndedExtractionSchemaDetector: GenerativeModelsAvailability check returned unavailable: %s"
- "OpenEndedExtractionSchemaDetector: GenerativeModelsAvailability check returned unknown availability"
- "OpenEndedExtractionSchemaDetector: Locale does not have a language code"
- "com.apple.oee.event.generic.v1"
- "com.apple.oee.event.v2"
- "com.apple.oee.reminder"
- "com.apple.oee.reminder.generic.v1"
```
