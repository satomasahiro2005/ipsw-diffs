## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x185c50` | `0x186190` | **`+0x540`** |
| `__AUTH_CONST.__cfstring` | `0xc640` | `0xc700` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0xfe60` | `0xfef4` | **`+0x94`** |
| `__TEXT.__cstring` | `0xd690` | `0xd720` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x83a7` | `0x83f7` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x123e0` | `0x12418` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1bdf4` | `0x1be24` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x2c720` | `0x2c748` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2728` | `0x2740` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x14a8` | `0x14b8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x9290` | `0x92a0` | **`+0x10`** |

### Other Changes

```diff

-625.2.7.1.0
+625.2.8.10.4

+  - /System/Library/PrivateFrameworks/AppIntentsServices.framework/AppIntentsServices

-  Functions: 9315
-  Symbols:   17552
-  CStrings:  2574
+  Functions: 9321
+  Symbols:   17560
+  CStrings:  2581
Symbols:
+ +[SFContentBlockerManager(SFPrivate) compiledBytecodeForEnabledContentBlockersInDefaultProfile]
+ +[_SFSearchEngineController postRemoteAppIntentsNotificationForSearchEngineChange]
+ -[_SFSearchEngineController defaultSearchEnginePlist]
+ _OBJC_CLASS_$_SFContentBlockerManagerProxy
+ _OBJC_CLASS_$_SFSearchEngineControllerWrapper
+ _OBJC_CLASS_$_WBSPair
+ __SFContentBlockerStateURL
+ __ZL49postContentBlockerExtensionsDidChangeNotificationv
CStrings:
+ "BrowserChoiceConfirmButton"
+ "BrowserChoiceListCell-"
+ "BrowserChoiceShowMoreButton"
+ "ChooseCurrentDefaultButton"
+ "ContentRuleList-%@"
+ "SetUpLaterButton"
+ "Unable to seralize search engine dictionary representation into a plist: %{public}@"
```
