## BackgroundAssets

> `/System/Library/Frameworks/BackgroundAssets.framework/BackgroundAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90c34` | `0x91238` | **`+0x604`** |
| `__TEXT.__eh_frame` | `0x41a0` | `0x4168` | **`-0x38`** |
| `__DATA.__data` | `0x13a8` | `0x1380` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0x121f` | `0x120d` | **`-0x12`** |
| `__TEXT.__const` | `0x3028` | `0x3018` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xfa8` | `0xfb0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1ae0` | `0x1ae8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-271.0.0.0.0
+274.0.0.0.0

-  Functions: 1963
-  Symbols:   1512
+  Functions: 1962
+  Symbols:   1509
Symbols:
+ -[BAAgentClientProxy initWithAppBundleIdentifier:downloadManager:]
+ -[BADownloadManager initWithAppBundleIdentifier:]
+ _OBJC_IVAR_$_BADownloadManager._appBundleIdentifier
+ ___49-[BADownloadManager initWithAppBundleIdentifier:]_block_invoke
+ ___swift_closure_destructor.100Tm
+ ___swift_closure_destructor.104Tm
+ ___swift_closure_destructor.78Tm
+ ___swift_closure_destructor.95Tm
+ _swift_unknownObjectRetain_n
- -[BAAgentClientProxy initWithApplicationIdentifier:downloadManager:]
- -[BADownloadManager initWithApplicationIdentifier:]
- _OBJC_IVAR_$_BADownloadManager._applicationIdentifier
- ___51-[BADownloadManager initWithApplicationIdentifier:]_block_invoke
- ___swift_closure_destructor.102Tm
- ___swift_closure_destructor.106Tm
- ___swift_closure_destructor.80Tm
- ___swift_closure_destructor.97Tm
- _get_type_metadata 15Synchronization5MutexVy16BackgroundAssets16AssetPackManagerC21ObjCDelegateReferenceVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation6LocaleV8LanguageVSg6System8FilePathVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo14NSUserDefaultsCG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "App bundle identifier (%@) has invalid app store metadata dictionary."
+ "App bundle identifier (%@) is not a valid bundle identifier."
- "Application identifier (%@) has invalid app store metadata dictionary."
- "Application identifier (%@) is not a valid bundle identifier."
```
