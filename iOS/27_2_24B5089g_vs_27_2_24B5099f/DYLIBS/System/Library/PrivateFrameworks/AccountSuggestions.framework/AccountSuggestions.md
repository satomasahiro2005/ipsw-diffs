## AccountSuggestions

> `/System/Library/PrivateFrameworks/AccountSuggestions.framework/AccountSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b01c` | `0x1c808` | **`+0x17ec`** |
| `__TEXT.__const` | `0x69a` | `0x78c` | **`+0xf2`** |
| `__TEXT.__constg_swiftt` | `0x390` | `0x450` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x2cf` | `0x32c` | **`+0x5d`** |
| `__TEXT.__oslogstring` | `0x479` | `0x4c9` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x618` | `0x660` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x5b0` | `0x5f8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x4a0` | `0x4e8` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x1ac` | `0x1d8` | **`+0x2c`** |
| `__DATA.__common` | `—` | `0x28` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x210` | `0x230` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x3f0` | `0x410` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x618` | `0x608` | **`-0x10`** |
| `__DATA.__data` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x60` | `0x50` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x272` | `0x262` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x130` | `0x128` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-112.0.0.0.0
+113.0.0.0.0

-  Functions: 454
-  Symbols:   278
-  CStrings:  34
+  Functions: 478
+  Symbols:   282
+  CStrings:  35
Symbols:
+ ___swift_closure_destructor.94Tm
+ _swift_allocBox
+ _symbolic $s18AccountSuggestions010SuggestionA9ProvidingP
+ _symbolic $s18AccountSuggestions23SuggestionKeyValueStoreP
+ _symbolic ______p 18AccountSuggestions010SuggestionA9ProvidingP
+ _symbolic ______pSg 18AccountSuggestions23SuggestionKeyValueStoreP
+ _symbolic _____yc 10Foundation4DateV
+ _symbolic x
- ___swift_closure_destructor.86Tm
- _objc_retain_x22
- _objc_retain_x27
- _symbolic So25NSUbiquitousKeyValueStoreCSg
CStrings:
+ "Suggestion %s of type %s had properties we never update, removing them"
```
