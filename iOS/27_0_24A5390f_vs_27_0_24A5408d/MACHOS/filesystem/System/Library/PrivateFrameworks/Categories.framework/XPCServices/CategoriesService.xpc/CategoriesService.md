## CategoriesService

> `/System/Library/PrivateFrameworks/Categories.framework/XPCServices/CategoriesService.xpc/CategoriesService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x746` | `0x62c` | **`-0x11a`** |
| `__DATA_CONST.__cfstring` | `0x9e0` | `0xac0` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x180` | `0x100` | **`-0x80`** |
| `__TEXT.__objc_methname` | `0xeac` | `0xf12` | **`+0x66`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x58` | **`+0x58`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x394` | `0x3cc` | **`+0x38`** |
| `__DATA.__objc_const` | `0x790` | `0x7c0` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xee0` | `0xec0` | **`-0x20`** |
| `__TEXT.__text` | `0x50d4` | `0x50b4` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x2e8` | `0x2ce` | **`-0x1a`** |
| `__DATA_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__bss` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4a0` | `0x490` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1b8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x420` | `0x410` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x178` | `0x188` | **`+0x10`** |
| `__TEXT.__cstring` | `0x60e` | `0x61c` | **`+0xe`** |
| `__DATA_CONST.__auth_got` | `0x220` | `0x218` | **`-0x8`** |
| `__TEXT.__const` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-56.0.0.0.0
+58.0.1.0.0

+  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices

-  Functions: 87
+  Functions: 88

-  CStrings:  359
+  CStrings:  356
Symbols:
+ _AMSErrorDomain
+ _AMSMediaTaskPlatformAppleTV
+ _AMSMediaTaskPlatformMac
+ _AMSMediaTaskPlatformiPad
+ _AMSMediaTaskPlatformiPhone
+ _OBJC_CLASS_$_AMSMediaTask
+ _OBJC_CLASS_$_AMSProcessInfo
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _objc_retain_x25
- _CTErrorKeyHTTPResponse
- _CTErrorKeyHTTPResponseData
- _MGCopyAnswer
- _OBJC_CLASS_$_NSBundle
- _OBJC_CLASS_$_NSJSONSerialization
- _OBJC_CLASS_$_NSLocale
- _OBJC_CLASS_$_NSMutableURLRequest
- _OBJC_CLASS_$_NSURLComponents
- _OBJC_CLASS_$_NSURLQueryItem
- _OBJC_CLASS_$_NSURLSession
- _objc_autorelease
CStrings:
+ "1"
+ "55"
+ "56"
+ "App Store category: %{private}@ = %@ -> %@"
+ "Corrupt response data item: %{private}@"
+ "Could not resolve app from response data item: %{private}@"
+ "Media API server is overloaded. Caching empty results for: %{private}@"
+ "Not performing Media API lookup for cached bundle IDs: %{private}@"
+ "Performing Media API lookup on behalf of %{private}@: %{private}@"
+ "Q"
+ "Q24@0:8@16"
+ "Response data item is missing a bundle identifier: %{private}@"
+ "Response data item is missing attributes: %{private}@"
+ "SOCIAL_MEDIA"
+ "SOCIAL_MEDIA_AGE_RESTRICTED"
+ "START: Media API lookup on behalf of %{private}@: %{private}@"
+ "TQ,R,V_contentDescriptors"
+ "_bundleIdentifierFromAttributes:"
+ "_contentDescriptorKindToCTContentDescriptorsMap"
+ "_contentDescriptors"
+ "_contentDescriptorsFromAttributes:"
+ "_errorIndicatesServerOverloaded:"
+ "_genreIDsFromResponseDataItem:"
+ "addFinishBlock:"
+ "ageRating"
+ "appStoreSearchResultsWithResponseDataItems:platform:"
+ "appletvos"
+ "attributes"
+ "contentDescriptors"
+ "contentLevels"
+ "createBagForSubProfile"
+ "data"
+ "extend"
+ "genres"
+ "handleMediaResult:error:platform:completionHandler:"
+ "id"
+ "identifier"
+ "initWithBundleIdentifier:"
+ "initWithPrimary:secondary:contentDescriptors:"
+ "initWithResponseDataItem:platform:"
+ "initWithType:clientIdentifier:clientVersion:bag:"
+ "ios"
+ "kind"
+ "osx"
+ "perform"
+ "performMediaAPIQueryWithBundleIDs:deviceFamily:completionHandler:"
+ "platformAttributes"
+ "relationships"
+ "responseDataItems"
+ "secondaryGenreIdentifier"
+ "setAdditionalPlatforms:"
+ "setAdditionalQueryParams:"
+ "setBundleIdentifiers:"
+ "setClientInfo:"
+ "unsignedIntegerValue"
+ "v24@?0@\"AMSMediaResult\"8@\"NSError\"16"
+ "watchos"
+ "xros"
- "%@,%@"
- "%@/%@/%@/%@"
- "@40@0:8@16@24^@32"
- "BuildVersion"
- "Bundle ID must be a NSString. Search result record: %@"
- "CTAppStoreSearchResult results: %{private}@"
- "CTAppStoreSearchResult searchResult: %{private}@"
- "Corrupt result record: %{private}@"
- "Corrupt search record: %{private}@"
- "Corrupt search results: %{private}@"
- "Could not resolve app from search result record: %{private}@"
- "Could not serialize result data with error: %@"
- "Genre ID must be a NSString. Search result record: %@"
- "Genre IDs must be a NSArray. Search result record: %@"
- "JSONObjectWithData:options:error:"
- "Not performing iTunes lookup for cached bundle IDs: %{public}@"
- "Performing iTunes lookup on behalf of %{public}@: %{public}@"
- "START: %{private}@"
- "STORELOOKUP END: %{private}@"
- "STORELOOKUP LOOKUP FAILED: %{private}@"
- "URL"
- "User-Agent"
- "appStoreSearchResultsWithResultData:platform:error:"
- "bundleIdentifier"
- "configuration"
- "country"
- "countryCode"
- "currentLocale"
- "dataTaskWithRequest:completionHandler:"
- "entity"
- "genreIds"
- "handleSearchResultsWithTaskData:platform:error:completionHandler:"
- "https://itunes.apple.com/lookup"
- "iPadSoftware"
- "iTunes server is overloaded. Caching empty results for: %{public}@"
- "initWithDomain:code:userInfo:"
- "initWithFormat:"
- "initWithName:value:"
- "initWithPrimary:secondary:"
- "initWithSearchResultRecord:platform:"
- "initWithString:"
- "initWithURL:"
- "itunes.apple.com AppStore category: %{private}@ = %@ -> %@"
- "macSoftware"
- "mainBundle"
- "marketing-name"
- "media"
- "performiTunesQueryWithURLComponents:queryItems:deviceFamily:completionHandler:"
- "results"
- "setQueryItems:"
- "setTimeoutIntervalForRequest:"
- "setTimeoutIntervalForResource:"
- "setValue:forHTTPHeaderField:"
- "set_sourceApplicationBundleIdentifier:"
- "sharedSession"
- "software"
- "statusCode"
- "tvSoftware"
- "userInfo"
- "v32@?0@\"NSData\"8@\"NSURLResponse\"16@\"NSError\"24"
- "v48@0:8@16@24Q32@?40"
```
