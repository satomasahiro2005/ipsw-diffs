## FeedbackService

> `/System/Library/PrivateFrameworks/FeedbackService.framework/FeedbackService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1376` | `0x1476` | **`+0x100`** |
| `__TEXT.__text` | `0x96ee0` | `0x96e34` | **`-0xac`** |
| `__TEXT.__eh_frame` | `0x2958` | `0x28f8` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x2b17` | `0x2af3` | **`-0x24`** |
| `__TEXT.__const` | `0xcb24` | `0xcb04` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2738` | `0x2718` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbc0` | `0xbc8` | **`+0x8`** |
| `__DATA.__data` | `0x15f8` | `0x15f0` | **`-0x8`** |

### Other Changes

```diff

-227.0.0.0.0
+229.0.0.0.0

-  Functions: 3906
-  Symbols:   2106
-  CStrings:  463
+  Functions: 3897
+  Symbols:   2103
+  CStrings:  467
Symbols:
- _swift_willThrowTypedImpl
- _symbolic _____ySSSay_____GG s18_DictionaryStorageC 15FeedbackService15FBKSInteractionC16AnnotatedContentV
- _symbolic _____y_____SgG s23_ContiguousArrayStorageC 15FeedbackService15FBKSInteractionC16AnnotatedContentV
CStrings:
+ ".file(url:) attachments can't be used with donation (.id) subjects; URL won't be readable on the receiver"
+ "Cannot get file system representation for URL: %{private}s file %{public}s"
+ "Failed to issue sandbox extension for .file(url:) payload; receiver will fail to read URL"
+ "Issued read sandbox extension for .file(url:) attachment %{public}s"
+ "sandbox_extension_issue_file returned nil for URL: %{private}s file %{public}s"
- "FBKSInteraction: contentRole [%{public}s] is shared by %ld AnnotatedContent values [%{public}s]. contentRole must be unique within a report; relatedFile lookups will be ambiguous."
```
