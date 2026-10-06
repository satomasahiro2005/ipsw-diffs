## HeartRateSettings

> `/System/Library/NanoPreferenceBundles/Applications/HeartRateSettings.bundle/HeartRateSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x3ea2` | `0x3e52` | **`-0x50`** |
| `__TEXT.__objc_stubs` | `0x2a80` | `0x2a40` | **`-0x40`** |
| `__TEXT.__text` | `0xe0bc` | `0xe08c` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0xfc8` | `0xfb8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x410` | `0x408` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

-  - /System/Library/PrivateFrameworks/NanoResourceGrabber.framework/NanoResourceGrabber

-  Symbols:   308
-  CStrings:  829
+  Symbols:   307
+  CStrings:  827
Symbols:
- _OBJC_CLASS_$_UIApplication
Functions:
~ sub_5688 : 152 -> 148
~ sub_5720 -> sub_571c : 152 -> 148
~ sub_57b8 -> sub_57b0 : 152 -> 148
~ sub_58d0 -> sub_58c4 : 152 -> 148
~ sub_7578 -> sub_7568 : 148 -> 144
~ sub_760c -> sub_75f8 : 128 -> 124
~ sub_7ce8 -> sub_7cd0 : 116 -> 112
~ sub_7d5c -> sub_7d40 : 176 -> 172
~ sub_84fc -> sub_84dc : 116 -> 112
~ sub_8d34 -> sub_8d10 : 108 -> 104
~ sub_95dc -> sub_95b4 : 108 -> 104
~ sub_9db4 -> sub_9d88 : 108 -> 104
CStrings:
+ "hk_asyncOpenURL:"
- "initWithFeatureIdentifier:healthStore:countryCodeSource:"
- "openURL:withCompletionHandler:"
- "sharedApplication"
```
