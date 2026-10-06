## localizationswitcherd

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/Support/localizationswitcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca20` | `0xcc24` | **`+0x204`** |
| `__TEXT.__objc_methname` | `0xbc5` | `0xce3` | **`+0x11e`** |
| `__TEXT.__objc_methtype` | `0x2fe` | `0x37e` | **`+0x80`** |
| `__TEXT.__cstring` | `0x502` | `0x562` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xb40` | `0xba0` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x160` | `0x1a0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x78` | `0xa8` | **`+0x30`** |
| `__DATA.__objc_const` | `0x510` | `0x538` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3c8` | `0x3e8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x30c` | `0x32c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x188` | `0x198` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xca0` | `0xcb0` | **`+0x10`** |
| `__TEXT.__const` | `0x162` | `0x172` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x660` | `0x668` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-498.0.0.0.0
+500.1.1.0.0

-  Functions: 160
-  Symbols:   292
-  CStrings:  259
+  Functions: 162
+  Symbols:   295
+  CStrings:  267
Symbols:
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_NSError
+ _objc_retain_x6
CStrings:
+ "Per-app language migration failed"
+ "_migratePreferredLanguageFromBundleID:sourceContainerPath:toBundleID:destinationContainerPath:carriedLanguages:error:"
+ "com.apple.IntlPreferences.PerAppLanguageMigration"
+ "dictionaryWithObjects:forKeys:count:"
+ "errorWithDomain:code:userInfo:"
+ "migratePreferredLanguageFromBundleID:sourceContainerPath:toBundleID:destinationContainerPath:reply:"
+ "v56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@?<v@?@\"NSArray\"@\"NSError\">48"
+ "v56@0:8@16@24@32@40@?48"
```
