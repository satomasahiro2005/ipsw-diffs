## FindMyStorage

> `/System/Library/PrivateFrameworks/FindMyStorage.framework/FindMyStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6778` | `0x7c30` | **`+0x14b8`** |
| `__DATA.__bss` | `0x380` | `0x480` | **`+0x100`** |
| `__TEXT.__cstring` | `0x204` | `0x2ea` | **`+0xe6`** |
| `__AUTH_CONST.__auth_got` | `0x408` | `0x4d0` | **`+0xc8`** |
| `__TEXT.__const` | `0x568` | `0x622` | **`+0xba`** |
| `__AUTH.__objc_data` | `—` | `0xb0` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x1f9` | `0x290` | **`+0x97`** |
| `__TEXT.__eh_frame` | `0x440` | `0x4c0` | **`+0x80`** |
| `__DATA.__data` | `0x40` | `0xa0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x238` | `0x298` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x17c` | `0x1cc` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xd8` | `0x120` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x1a1` | `0x1e9` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x20` | `0x60` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xfc` | `0x134` | **`+0x38`** |
| `__AUTH.__data` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0xbc` | `0xce` | **`+0x12`** |
| `__TEXT.__oslogstring` | `0x143` | `0x14e` | **`+0xb`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-106.30.6.14.7
+106.30.6.14.10

-  Functions: 167
-  Symbols:   151
-  CStrings:  23
+  Functions: 192
+  Symbols:   177
+  CStrings:  28
Symbols:
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$__TtC13FindMyStorage26FastCanonicalDateFormatter
+ _OBJC_METACLASS_$_NSDateFormatter
+ _OBJC_METACLASS_$_NSObject
+ _OBJC_METACLASS_$__TtC13FindMyStorage26FastCanonicalDateFormatter
+ __DATA__TtC13FindMyStorage26FastCanonicalDateFormatter
+ __INSTANCE_METHODS__TtC13FindMyStorage26FastCanonicalDateFormatter
+ __METACLASS_DATA__TtC13FindMyStorage26FastCanonicalDateFormatter
+ __swiftEmptySetSingleton
+ _associated conformance 13FindMyStorage26FastCanonicalDateFormatterC6Signal33_FC47ECB60882082A8710C535EBBE9822LLOSHAASQ
+ _bzero
+ _objc_allocWithZone
+ _objc_autoreleaseReturnValue
+ _objc_msgSendSuper2
+ _objc_release_x21
+ _objc_release_x24
+ _objc_retain_x21
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_release_x21
+ _symbolic So15NSDateFormatterC
+ _symbolic _____ 13FindMyStorage26FastCanonicalDateFormatterC
+ _symbolic _____ 13FindMyStorage26FastCanonicalDateFormatterC6Signal33_FC47ECB60882082A8710C535EBBE9822LLO
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic _____Sg 10Foundation8TimeZoneV
+ _symbolic _____y_____G s11_SetStorageC 06FindMyB026FastCanonicalDateFormatterC6Signal33_FC47ECB60882082A8710C535EBBE9822LLO
CStrings:
+ "%{public}s"
+ "FindMyStorage Date decode fell back to DateFormatter (first non-canonical string)."
+ "FindMyStorage fast canonical-Date parse is live (first hit)."
+ "com.apple.icloud.searchpartyd"
+ "yyyy-MM-dd'T'HH:mm:ss.SSS"
```
