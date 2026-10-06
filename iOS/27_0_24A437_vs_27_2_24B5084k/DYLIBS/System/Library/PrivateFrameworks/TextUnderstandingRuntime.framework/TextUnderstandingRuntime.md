## TextUnderstandingRuntime

> `/System/Library/PrivateFrameworks/TextUnderstandingRuntime.framework/TextUnderstandingRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x5082` | `0x4852` | **`-0x830`** |
| `__TEXT.__text` | `0x236c74` | `0x2372c8` | **`+0x654`** |
| `__DATA_DIRTY.__bss` | `0x3380` | `0x3100` | **`-0x280`** |
| `__AUTH_CONST.__const` | `0xead8` | `0xe898` | **`-0x240`** |
| `__TEXT.__const` | `0x12b98` | `0x12a78` | **`-0x120`** |
| `__TEXT.__swift5_reflstr` | `0x2f3c` | `0x2e8c` | **`-0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x4208` | `0x42a8` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x3f6c` | `0x3f04` | **`-0x68`** |
| `__AUTH_CONST.__objc_const` | `0x2ac0` | `0x2b20` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x974a` | `0x97aa` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x7718` | `0x76c0` | **`-0x58`** |
| `__DATA_DIRTY.__data` | `0x3528` | `0x34e8` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x4d3b` | `0x4cff` | **`-0x3c`** |
| `__TEXT.__swift5_assocty` | `0xf88` | `0xf58` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x3748` | `0x3770` | **`+0x28`** |
| `__DATA.__data` | `0x2fc0` | `0x2fa0` | **`-0x20`** |
| `__TEXT.__eh_frame` | `0x15694` | `0x1567c` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x106c` | `0x105c` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0xd00` | `0xd10` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf08` | `0xf00` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x76c` | `0x774` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x8c` | `0x90` | **`+0x4`** |

### Other Changes

```diff

-176.3.0.1.0
+186.0.0.0.0

-  Functions: 12208
-  Symbols:   575
-  CStrings:  998
+  Functions: 12193
+  Symbols:   578
+  CStrings:  995
Symbols:
+ _CSEventStatusConfirmed
+ _CSEventStatusUpdated
+ _OBJC_CLASS_$_NSProcessInfo
CStrings:
+ "EventsPipeline: device not eligible for Apple Intelligence, running regex events and returning"
+ "EventsPipeline: document language not supported, running regex events and returning"
+ "IdentificationDocumentEligibilityProcessor: Will skip gating for ID classification: %{bool}d for document kind: %s"
+ "IdentificationDocumentEligibilityProcessor: unsupported request types"
+ "IdentificationDocumentProcessor: Will skip gating for ID classification: %{bool}d for document kind: %s"
+ "OpenEndedExtraction: fixed prompt cost %ld tokens exceeds input budget of %ld tokens; skipping document"
+ "OpenEndedExtractionSchemaDetector: %{public}s missing from adapter metadata; falling back to %{public}s"
+ "Running input safety for use case identifier %s"
+ "Skipping input safety for use case %s since it has already run"
+ "TextUnderstandingRuntime/IdentificationDocumentEligibilityProcessor.swift"
+ "com.apple.textComposition.OpenEndedExtract.applicableactionsmessage"
- "EventsPipeline: device not eligible for Apple Intelligence, geocoding regex events and returning"
- "EventsPipeline: document language not supported, geocoding regex events and returning"
- "IdentificationDocumentProcessor: image dimensions (%ldx%ld) exceed maximum allowed (%ldx%ld), falling back to text-only processing"
- "OEE9MClassifierAdapter: Classification failed: %@"
- "OEE9MClassifierAdapter: Classified document as '%s'"
- "OEE9MClassifierAdapter: applicable actions prompt template unavailable, falling back to legacy classification"
- "OpenEndedExtractionAdapter: Truncated document text from %ld to %ld characters"
- "Task: Classify Content into Structured Information Categories\nObjective:\nAnalyze the following content and classify it into a predefined category based on the presence of structured, actionable information.\nClassification Categories:\n- \"appointment\": Confirmed business appointment with specific date/time\n- \"order_updates\": Order confirmation, purchase receipt, shipping notification\n- \"receipts\": Purchase receipt or transaction confirmation with amount/payment details (no physical delivery)\n- \"invitation\": Event invitation or meeting request\n- \"ticket\": General entertainment or event ticket confirmation\n- \"flight\": Airline booking or flight reservation\n- \"transport_ticket\": Train, bus, or other transportation reservation\n- \"hotel\": Lodging or accommodation reservation\n- \"shipping_updates\": Package tracking or delivery information\n- \"movie\": Specific movie ticket or cinema booking\n- \"restaurant\": Restaurant reservation\n- \"car\": Car rental or automotive service booking\n- \"no_event\": No extractable structured information (marketing emails, newsletters, general promotions)\nClassification Guidelines:\n1. Prioritize specific structured information over generic text\n2. Look for key indicators like:\n   - Dates and times\n   - Ticket/booking references\n   - Reservation details\n   - Explicit event or service confirmations\n   - Transaction amounts and payment details (for receipts)\n3. If no clear structured information is present, default to \"no_event\"\n4. Be cautious of misleading subject lines or promotional language\n5. Receipts differ from orders - receipts are for completed transactions without physical delivery tracking\nOutput:\n- Single lowercase string representing the most appropriate category\n- Examples: \"ticket\", \"flight\", \"receipts\", \"no_event\"\nKey Considerations:\n- Content with ticket purchase language but no concrete booking details should be carefully evaluated\n- Promotional content with ticket-like language should typically be classified as \"no_event\"\n\n[Input Text]"
- "no_event"
- "order_updates"
- "receipts"
- "shipping_updates"
- "transport_ticket"
- "{{ specialToken.chat.role.system }}{{ specialToken.chat.component.turnEnd }}{{ specialToken.chat.role.user }}{{ userContent }}{{ specialToken.chat.component.turnEnd }}{{ specialToken.chat.role.assistant }}"
```
