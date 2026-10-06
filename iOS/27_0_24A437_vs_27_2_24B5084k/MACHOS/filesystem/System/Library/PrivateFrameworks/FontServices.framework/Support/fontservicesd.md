## fontservicesd

> `/System/Library/PrivateFrameworks/FontServices.framework/Support/fontservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca10` | `0xd448` | **`+0xa38`** |
| `__TEXT.__cstring` | `0x16b4` | `0x1999` | **`+0x2e5`** |
| `__DATA_CONST.__cfstring` | `0x1460` | `0x1660` | **`+0x200`** |
| `__DATA_CONST.__const` | `0xaa8` | `0xaf8` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x244c` | `0x2490` | **`+0x44`** |
| `__TEXT.__gcc_except_tab` | `0x33c` | `0x370` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x370` | `0x3a0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x72f` | `0x75b` | **`+0x2c`** |
| `__TEXT.__objc_stubs` | `0x1da0` | `0x1dc0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x910` | `0x928` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xa10` | `0xa20` | **`+0x10`** |
| `__DATA.__objc_const` | `0x998` | `0x9a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-169.0.0.0.0
+173.0.0.0.0

-  Functions: 225
+  Functions: 231

-  CStrings:  681
+  CStrings:  700
CStrings:
+ ".."
+ "App Replacement: caller \"%@\" %@"
+ "App Replacement: dropped provider preference \"%@\" for \"%@\""
+ "App Replacement: entered migrateIssuedFonts in fontservicesd, \"%@\" -> \"%@\""
+ "App Replacement: invalidated the cached user font info"
+ "App Replacement: migrateIssuedFonts \"%@\" -> \"%@\" (%@)"
+ "App Replacement: migrateIssuedFonts - \"%@\" already had issued font paths; merged"
+ "App Replacement: migrateIssuedFonts refused - caller \"%@\" lacks %s"
+ "App Replacement: migrateIssuedFonts refused - malformed identifier"
+ "App Replacement: migrateIssuedFonts refused - source and destination are the same identifier \"%@\""
+ "App Replacement: re-keyed consumer preference \"%@\""
+ "com.apple.fontservices.allow-migrate-fonts"
+ "containsString:"
+ "is NOT entitled"
+ "is entitled"
+ "migrateIssuedFontsForIdentifier:toIdentifier:reply:"
+ "migrated"
+ "nothing to migrate"
+ "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?B>32"
```
