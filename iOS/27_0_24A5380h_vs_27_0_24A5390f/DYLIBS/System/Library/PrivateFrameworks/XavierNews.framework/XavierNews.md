## XavierNews

> `/System/Library/PrivateFrameworks/XavierNews.framework/XavierNews`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3a88` | `0xd54d4` | **`+0x1a4c`** |
| `__TEXT.__cstring` | `0x5374` | `0x5584` | **`+0x210`** |
| `__TEXT.__eh_frame` | `0x3b14` | `0x3bbc` | **`+0xa8`** |
| `__TEXT.__const` | `0x13c70` | `0x13cf0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x4958` | `0x49d8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x7c` | `—` | **`-0x7c`** |
| `__TEXT.__swift5_typeref` | `0x69ee` | `0x6a52` | **`+0x64`** |
| `__TEXT.__swift5_fieldmd` | `0x563c` | `0x569c` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xac0` | `0xa68` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x3bf0` | `0x3c28` | **`+0x38`** |
| `__DATA.__data` | `0x2d78` | `0x2da0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xebb0` | `0xeb98` | **`-0x18`** |

### Other Changes

```diff

-5923.0.0.0.0
+5926.0.0.0.0

-  Functions: 8832
-  Symbols:   2535
-  CStrings:  587
+  Functions: 8840
+  Symbols:   2533
+  CStrings:  591
Symbols:
+ ___swift_memcpy120_8
+ ___swift_memcpy137_8
+ ___swift_memcpy176_8
+ ___swift_memcpy216_8
+ _swift_release_x10
+ _symbolic SDySS_____G s5Int32V
+ _symbolic _____ s5Int32V
+ _symbolic _____8headline______6reasonSb11wasRejectedtSg 10XavierNews17GroupableHeadlineV AA7ClassicV0D9ClustererV16AcceptanceReasonO
+ _symbolic _____ySS_____G s18_DictionaryStorageC s5Int32V
+ _symbolic _____y_____3key_Shy_____G5valuetG s23_ContiguousArrayStorageC 10XavierNews12GroupableTagV AC0F8HeadlineV
- ___swift_destroy_boxed_opaque_existential_0
- ___swift_memcpy113_8
- ___swift_memcpy168_8
- ___swift_memcpy89_8
- __os_log_impl
- _objc_release_x20
- _objc_release_x23
- _objc_release_x25
- _objc_release_x8
- _swift_getObjectType
- _swift_unknownObjectRetain
- _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
CStrings:
+ "More For You group formation failed with %{public}@ candidates: %{public}@"
+ "Unknown error during rule evaluation for headline %{public}@: %{public}@"
+ "cluster: inputTags=%{public}@ (topic=%{public}@ channel=%{public}@) bucketedTags=%{public}@ moreForYouCandidates=%{public}@ maxGroups=%{public}@ buckets=[%{public}@]"
+ "cluster: tag %{public}@ (kind=%{public}@, candidates=%{public}@) did not form a group, items go to More For You: %{public}@"
+ "publisherContentRating"
+ "publisherRelevanceRating"
+ "topicContentRatings"
+ "topicRelevanceRatings"
- "HeadlineClusterer"
- "More For You group formation failed with %ld candidates: %s"
- "Unknown error during rule evaluation for headline %s: %s"
- "com.apple.news.xavier"
```
