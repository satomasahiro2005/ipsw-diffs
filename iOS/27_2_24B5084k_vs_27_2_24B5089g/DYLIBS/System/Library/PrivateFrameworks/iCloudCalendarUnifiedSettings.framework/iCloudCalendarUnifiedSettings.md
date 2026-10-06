## iCloudCalendarUnifiedSettings

> `/System/Library/PrivateFrameworks/iCloudCalendarUnifiedSettings.framework/iCloudCalendarUnifiedSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b00` | `0x2de0` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0xbe` | `0xe9` | **`+0x2b`** |
| `__AUTH_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x148` | `0x160` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2027.0.5.0.0
+2027.1.1.0.0

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 71
-  Symbols:   337
-  CStrings:  10
+  Functions: 72
+  Symbols:   340
+  CStrings:  12
Symbols:
+ _MCCCalendarSystemRootDirectory
+ _UISystemRootDirectory
+ ___CFConstantStringClassReference
+ _objc_claimAutoreleasedReturnValue
- _NSOpenStepRootDirectory
Functions:
+ _MCCCalendarSystemRootDirectory
~ _$s29iCloudCalendarUnifiedSettings01iabcD8ProviderC04loadbD14BundleIfNeeded33_3099D29EDB614C719A1CD4A734422216LLyyFTf4d_n : 384 -> 968
CStrings:
+ "/"
+ "/System/Library/PreferenceBundles/AccountSettings/"
+ "Calendar bundle isn't loaded. Bundle: %s"
- "System/Library/PreferenceBundles/AccountSettings/"
```
