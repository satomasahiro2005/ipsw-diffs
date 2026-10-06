## PhoneNumberResolver

> `/System/Library/PrivateFrameworks/PhoneNumberResolver.framework/PhoneNumberResolver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ebc` | `0x5eac` | **`-0x10`** |

### Other Changes

```text
Functions:
~ -[PNRStringsFileReaderResult separatorForLanguage:] : 424 -> 420
~ -[PNRStringsFileReaderResult shouldOrderCityFirstForLanguage:] : 276 -> 272
~ -[PNRResourceManager _bestStringForInCountryPhoneNumber:slice:countryOfDevice:countryTrieData:countryStrings:logId:resultBlock:] : 4040 -> 4024
~ -[PNRResourceManager _lookupString:inTrieMemory:value:] : 300 -> 316
~ -[PNRResourceManager _URLForInstalledResourceOfType:logId:resultBlock:] : 1776 -> 1772
~ -[PNRPhoneNumberResolver resolvePhoneNumbers:queue:handler:] : 1248 -> 1244
```
