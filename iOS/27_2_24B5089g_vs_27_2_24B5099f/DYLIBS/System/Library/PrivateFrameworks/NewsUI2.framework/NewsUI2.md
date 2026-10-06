## NewsUI2

> `/System/Library/PrivateFrameworks/NewsUI2.framework/NewsUI2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14951c4` | `0x149a200` | **`+0x503c`** |
| `__TEXT.__cstring` | `0x5b788` | `0x5bbb8` | **`+0x430`** |
| `__AUTH_CONST.__objc_const` | `0x74a98` | `0x74b70` | **`+0xd8`** |
| `__AUTH.__data` | `0x1b3e8` | `0x1b488` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x86e40` | `0x86ec8` | **`+0x88`** |
| `__DATA.__bss` | `0xb59e8` | `0xb5a68` | **`+0x80`** |
| `__DATA.__data` | `0x1dc78` | `0x1dcf8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x3bf00` | `0x3bf78` | **`+0x78`** |
| `__TEXT.__const` | `0xd7ab4` | `0xd7b24` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x56580` | `0x565f0` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x416d8` | `0x41734` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x159db` | `0x15a2b` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x414c4` | `0x41514` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x42a68` | `0x42aac` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0xfe70` | `0xfeb0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x2eeee` | `0x2ef26` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xd674` | `0xd69c` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x1973c` | `0x19764` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xb9e8` | `0xb9f8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x7cd0` | `0x7ce0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x647e0` | `0x647d0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3368` | `0x3370` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0xb930` | `0xb938` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xabcc` | `0xabd4` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xedc` | `0xee0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x46e4` | `0x46e8` | **`+0x4`** |

### Other Changes

```diff

-5962.0.0.0.0
+5969.0.0.0.0

-  Functions: 81226
-  Symbols:   24341
-  CStrings:  7428
+  Functions: 81260
+  Symbols:   24348
+  CStrings:  7442
Symbols:
+ __DATA__TtC7NewsUI220WelcomeModelProvider
+ __IVARS__TtC7NewsUI220WelcomeModelProvider
+ __METACLASS_DATA__TtC7NewsUI220WelcomeModelProvider
+ _symbolic $s7NewsUI221WelcomeModelProvidingP
+ _symbolic _____ 5TeaUI9CoverViewO9AnimationO
+ _symbolic _____ 7NewsUI220WelcomeModelProviderC
+ _symbolic ______p 7NewsUI221WelcomeModelProvidingP
CStrings:
+ "A subscription unlocks 500+ titles, premium recipes, audio stories, local news, and more."
+ "Apple News personalises your news feed based on your interests from thousands of sources."
+ "Australian Apple News editors keep you up to date on the most important news of the day."
+ "Auto-refresh attempting to check for updated configuration without last publish date"
+ "Auto-refresh is disabled because last update has not exceeded refresh interval; requires config update check, interval=%ld, timeSinceLastUpdate=%ld"
+ "Auto-refresh rapid-refresh allowed because config has been updated, publishDate=%{public}@, lastPublishDate=%{public}@"
+ "Auto-refresh rapid-refresh disallowed because config has NOT been updated, publishDate=%{public}@, lastPublishDate=%{public}@"
+ "Auto-refresh rapid-refresh disallowed because config has no publish date to compare"
+ "Auto-refresh will check for updated config changes against publish date %{public}@..."
+ "Get 500+ premium titles, recipes, audio stories and more with a News+ subscription."
+ "Personalised for You"
+ "Saving last refresh context, createdDate=%{public}s, publishDate=%{public}s"
+ "The description for the 'Even Better with News+' bullet point on the welcome screen, UK (no puzzles)"
+ "The description for the 'Personalised for You' bullet point on the welcome screen, Australia"
+ "The description for the 'Top Stories You Can Trust' bullet point on the welcome screen, Australia"
+ "The description for the 'Unlock More with News+' bullet point on the welcome screen, Australia"
+ "The second bullet point title on the welcome screen, UK/Australia spelling"
+ "The third bullet point title on the welcome screen, Australia"
+ "Unlock More with News+"
- "Auto-refresh is disabled because last update has not exceeded refresh interval, interval=%ld, timeSinceLastUpdate=%ld"
- "Auto-refresh rapid-refresh  enabled because we have a config update, publishDate=%@, and the feed was last updatedDate=%@"
- "Auto-refresh rapid-refresh  failed because the feed config has a publishDate=%@ and the feed was last updatedDate=%@"
- "Auto-refresh rapid-refresh enabled because we have a config update, publishDate=%@, and the feed was last updatedDate=%@"
- "Auto-refresh rapid-refresh failed because the feed config has a publishDate=%@ and the feed was last updatedDate=%@"
```
