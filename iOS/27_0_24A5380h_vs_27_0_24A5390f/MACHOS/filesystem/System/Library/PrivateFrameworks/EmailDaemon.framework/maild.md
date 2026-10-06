## maild

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/maild`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x154490` | `0x154840` | **`+0x3b0`** |
| `__TEXT.__gcc_except_tab` | `0x19640` | `0x196d0` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x1ce25` | `0x1cea5` | **`+0x80`** |
| `__DATA.__objc_const` | `0x13080` | `0x130b0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x4169` | `0x4199` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x163e0` | `0x16400` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x6ff8` | `0x7008` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1928` | `0x1930` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xaff4` | `0xaffc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb90` | `0xb94` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  - /System/Library/PrivateFrameworks/GenerativeSearch.framework/GenerativeSearch
-  - /System/Library/PrivateFrameworks/GenerativeSearchAdapter.framework/GenerativeSearchAdapter

-  Functions: 5876
-  Symbols:   1592
-  CStrings:  7539
+  Functions: 5878
+  Symbols:   1593
+  CStrings:  7544
Symbols:
+ _OBJC_CLASS_$_EDFeatureSettingsAnalyticsCollector
CStrings:
+ "@\"EDFeatureSettingsAnalyticsCollector\""
+ "T@\"EDFeatureSettingsAnalyticsCollector\",R,N,V_featureSettingsAnalyticsCollector"
+ "_featureSettingsAnalyticsCollector"
+ "featureSettingsAnalyticsCollector"
+ "initWithAnalyticsCollector:"
+ "mui_personSuggestionForEmailAddresses:displayName:alternateDisplayNames:contactIdentifier:contactScope:userTypedText:currentSuggestion:"
+ "runBootstrapWithCompletion:"
- "mui_personSuggestionForEmailAddresses:displayName:alternateDisplayNames:contactScope:userTypedText:currentSuggestion:"
- "runTurboBackFillWithCompletion:"
```
