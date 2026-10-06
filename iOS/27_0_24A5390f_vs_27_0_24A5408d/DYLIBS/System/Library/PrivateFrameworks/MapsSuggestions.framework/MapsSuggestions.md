## MapsSuggestions

> `/System/Library/PrivateFrameworks/MapsSuggestions.framework/MapsSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x193e64` | `0x193f6c` | **`+0x108`** |
| `__AUTH_CONST.__cfstring` | `0xe020` | `0xe060` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x11624` | `0x1164c` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x1762f` | `0x1764f` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2c130` | `0x2c140` | **`+0x10`** |

### Other Changes

```diff

-2972.30.6.12.32
+2972.30.6.12.54

-  Functions: 6677
+  Functions: 6678

-  CStrings:  5452
+  CStrings:  5455
Functions:
~ -[MapsSuggestionsMapsSync _createEntryFromRecentHistoryPlace:] : 732 -> 896
~ -[_RealPKPassFlightFieldReader departureAirportCode] : 2160 -> 2212
~ -[_RealPKPassFlightFieldReader arrivalAirportCode] : 2160 -> 2116
+ -[MapsSuggestionsMapsSync _createEntryFromRecentHistoryPlace:].cold.3
CStrings:
+ "16:33:40"
+ "Aug  4 2026"
+ "We did not get a mepitem for %@"
+ "boardPoint"
+ "offPoint"
- "23:33:39"
- "Jul 13 2026"
```
