## SoftwareUpdateUIMobile

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIMobile.framework/SoftwareUpdateUIMobile`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f0d0` | `0x7fc64` | **`+0xb94`** |
| `__TEXT.__gcc_except_tab` | `0x149c` | `0x15a4` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x8558` | `0x85c8` | **`+0x70`** |
| `__TEXT.__cstring` | `0x52f7` | `0x5327` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x20a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x918` | `0x920` | **`+0x8`** |

### Other Changes

```diff

-772.40.11.0.0
+772.40.12.0.0

-  Symbols:   2035
-  CStrings:  772
+  Symbols:   2036
+  CStrings:  775
Symbols:
+ _kCFNull
Functions:
~ -[SUUIMobileAnalyticsReporter toSUAnalyticsEvent:] : 692 -> 1184
~ -[SUUIMobileAnalyticsReporter eventNameFor:] : 156 -> 188
~ _SUUIMobileDescriptorAgreementTypeToString : 184 -> 248
~ -[SUUIMobileDescriptorAgreementStatusRegistry agreementStatusForType:descriptor:] : 1324 -> 1372
~ -[SUUIMobileDescriptorAgreementStatusRegistry description] : 1904 -> 2584
~ -[SUUIMobileDescriptorAgreementStatusRegistry initWithCoder:] : 936 -> 2584
CStrings:
+ "%s: Could not assign the SUAnalyticsEvent user interaction type - %{public}@ does not map to a known interaction."
+ "-[SUUIMobileAnalyticsReporter toSUAnalyticsEvent:]"
+ "<unknown %@: %lld>"
+ "type"
- "suUserInteraction != nil"
```
