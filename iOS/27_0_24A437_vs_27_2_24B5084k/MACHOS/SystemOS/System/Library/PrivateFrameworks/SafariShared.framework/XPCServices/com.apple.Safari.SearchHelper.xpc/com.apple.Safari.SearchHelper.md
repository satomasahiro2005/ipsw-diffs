## com.apple.Safari.SearchHelper

> `/System/Library/PrivateFrameworks/SafariShared.framework/XPCServices/com.apple.Safari.SearchHelper.xpc/com.apple.Safari.SearchHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x16f8` | `0x1736` | **`+0x3e`** |
| `__TEXT.__text` | `0x3e78` | `0x3eac` | **`+0x34`** |
| `__TEXT.__objc_methtype` | `0x621` | `0x634` | **`+0x13`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.29.10.29
+7625.2.4.1.0
Functions:
~ sub_100001f14 : 272 -> 304
~ sub_100002b14 -> sub_100002b34 : 712 -> 736
~ sub_100003550 -> sub_100003588 : 168 -> 160
~ sub_1000038d0 -> sub_100003900 : 1436 -> 1440
CStrings:
+ "URLWithSearchTerms:previousQuery:"
+ "_autocompleteToFirstSuggestionFromResponse:detailedSuggestions:"
+ "updateSuggestionsRequestWithSearchTerms:previousQuery:suggestionsURLTemplate:userAgentString:completionHandler:"
+ "updateSuggestionsRequestWithSearchTerms:previousQuery:userAgentString:completionHandler:"
+ "v56@0:8@\"NSString\"16@\"NSString\"24@\"WBSOpenSearchURLTemplate\"32@\"NSString\"40@?<v@?@\"WBSSearchSuggestionsFetcherResponse\"@\"NSError\">48"
+ "v56@0:8@16@24@32@40@?48"
- "URLWithSearchTerms:"
- "_autocompleteToFirstSuggestionFromResponse:"
- "updateSuggestionsRequestWithSearchTerms:suggestionsURLTemplate:userAgentString:completionHandler:"
- "updateSuggestionsRequestWithSearchTerms:userAgentString:completionHandler:"
- "v40@0:8@16@24@?32"
- "v48@0:8@\"NSString\"16@\"WBSOpenSearchURLTemplate\"24@\"NSString\"32@?<v@?@\"WBSSearchSuggestionsFetcherResponse\"@\"NSError\">40"
```
