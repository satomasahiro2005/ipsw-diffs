## Photos

> `/System/Library/Frameworks/Photos.framework/Photos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dbfe0` | `0x2dbf9c` | **`-0x44`** |
| `__AUTH_CONST.__cfstring` | `0x2d660` | `0x2d680` | **`+0x20`** |
| `__TEXT.__const` | `0x1778` | `0x1758` | **`-0x20`** |
| `__TEXT.__cstring` | `0x327f6` | `0x32803` | **`+0xd`** |
| `__TEXT.__gcc_except_tab` | `0x96a8` | `0x969c` | **`-0xc`** |

### Other Changes

```diff

-912.0.111.0.0
+912.0.232.0.0

-  CStrings:  8866
+  CStrings:  8867
Functions:
~ ___95-[PHServerResourceRequestRunner makeResourceAvailableWithRequest:library:clientBundleID:reply:]_block_invoke_3 : 4608 -> 4592
~ -[PHServerResourceRequestRunner chooseVideoWithRequest:library:clientBundleID:reply:] : 1344 -> 1340
~ ___85-[PHServerResourceRequestRunner chooseVideoWithRequest:library:clientBundleID:reply:]_block_invoke_3 : 4764 -> 4728
~ -[PHSuggestionChangeRequest validateMutationsToManagedObject:] : 772 -> 776
~ _PHSuggestionTypeForCPLSuggestionType : 44 -> 16
~ _CPLSuggestionTypeForPHSuggestionType : 44 -> 16
~ _PHSuggestionSubtypeForCPLSuggestionSubtype : 288 -> 308
~ _CPLSuggestionSubtypeForPHSuggestionSubtype : 288 -> 308
~ -[PHSuggestion initWithFetchDictionary:propertyHint:photoLibrary:] : 1244 -> 1220
~ _PHSuggestionStringWithSubtype : 1088 -> 1112
CStrings:
+ "Ambient Face"
```
