## AccessoryDeveloperSettings

> `/System/Library/PreferenceBundles/AccessoryDeveloperSettings.bundle/AccessoryDeveloperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3840` | `0x3db4` | **`+0x574`** |
| `__TEXT.__objc_stubs` | `0xd40` | `0xf20` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0xec5` | `0x1016` | **`+0x151`** |
| `__DATA_CONST.__cfstring` | `0xc80` | `0xd40` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x9f5` | `0xaa7` | **`+0xb2`** |
| `__DATA.__objc_selrefs` | `0x4b8` | `0x538` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x200` | `0x260` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x36c` | `0x39c` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x148` | `0x170` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x1da` | `0x1f3` | **`+0x19`** |
| `__TEXT.__unwind_info` | `0x140` | `0x158` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-980.71.1.0.0
+980.75.1.0.0

-  Functions: 58
-  Symbols:   118
-  CStrings:  320
+  Functions: 65
+  Symbols:   123
+  CStrings:  345
Symbols:
+ _NSURLCreationDateKey
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSIndexSet
+ _OBJC_CLASS_$_NSURL
+ _OBJC_CLASS_$_UIImageView
CStrings:
+ ".atslite"
+ "/var/mobile/tmp/com.apple.airplayd/CarPlaySnoops"
+ "@32@0:8@16@24"
+ "_carPlaySnoopsFolderURL"
+ "_didSelectShareableFileSpecifier:"
+ "_enumerateCurrentCarPlaySnoopsUsingBlock:"
+ "_shareableFileSpecifierNamed:atURL:"
+ "airplaysnoop_"
+ "carPlayTrafficCaptureEnabled"
+ "compare:"
+ "count"
+ "distantPast"
+ "failed to read CarPlay snoops directory %@: %@"
+ "fileURLWithPath:isDirectory:"
+ "indexSetWithIndexesInRange:"
+ "initWithImage:"
+ "insertObjects:atIndexes:"
+ "key"
+ "objectAtIndex:"
+ "q24@?0@\"NSURL\"8@\"NSURL\"16"
+ "setAccessoryView:"
+ "sortUsingComparator:"
+ "substringFromIndex:"
+ "substringToIndex:"
+ "v20@0:8B16"
+ "viewWillAppear:"
- "_didSelectLogArchiveSpecifier:"
```
