## SystemAppMigrator

> `/System/Library/DataClassMigrators/SystemAppMigrator.migrator/SystemAppMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d38` | `0x8454` | **`+0x71c`** |
| `__TEXT.__cstring` | `0x2cb1` | `0x3029` | **`+0x378`** |
| `__DATA_CONST.__cfstring` | `0x1660` | `0x17e0` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x1ec0` | `0x1f99` | **`+0xd9`** |
| `__TEXT.__objc_stubs` | `0x16c0` | `0x1780` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x750` | `0x780` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1b8` | `0x1e4` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x328` | `0x350` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x62c` | `0x644` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x208` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x3cf` | `0x3df` | **`+0x10`** |
| `__TEXT.__const` | `0x80` | `0x78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1663.0.0.0.1
+1673.0.0.0.0

-  Functions: 129
-  Symbols:   182
-  CStrings:  545
+  Functions: 131
+  Symbols:   181
+  CStrings:  564
Symbols:
- _kMISValidationOptionAllowLaunchWarning
CStrings:
+ "B32@0:8^@16^@24"
+ "MISystemAppMigrator: Failed to load internal superseded apps from %@ : %@"
+ "MISystemAppMigrator: Found invalid key type %@ in superseded apps plist's '%@' dictionary"
+ "MISystemAppMigrator: Found invalid value type %@ in superseded apps plist's '%@' dictionary"
+ "MISystemAppMigrator: Internal superseded apps plist had array value for '%@' key that had non-string objects in it"
+ "MISystemAppMigrator: Internal superseded apps plist was malformed"
+ "MISystemAppMigrator: Internal superseded apps plist was missing '%@' key with a dictionary value"
+ "MISystemAppMigrator: Internal superseded apps plist was missing '%@' key with an array value"
+ "MISystemAppMigrator: Internal superseded apps plist was not a dictionary"
+ "MISystemAppMigrator: Using %lu additional superseded apps and %lu replaced apps additions found in internal additions plist"
+ "NULL"
+ "ReplacedAppsRequiringMatchingUninstallState"
+ "SupersededApps"
+ "_copyInternalSupersededAppAdditions:internalReplacedAppsRequiringMachingUninstallState:"
+ "addEntriesFromDictionary:"
+ "dictionaryWithContentsOfURL:error:"
+ "hasInternalContent"
+ "internalSupersededAppAdditionsPlistURL"
+ "unionSet:"
```
