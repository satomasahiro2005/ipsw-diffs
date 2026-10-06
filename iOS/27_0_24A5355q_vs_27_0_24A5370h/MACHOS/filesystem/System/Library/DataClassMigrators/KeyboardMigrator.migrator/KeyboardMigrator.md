## KeyboardMigrator

> `/System/Library/DataClassMigrators/KeyboardMigrator.migrator/KeyboardMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5488` | `0x5b34` | **`+0x6ac`** |
| `__DATA_CONST.__cfstring` | `0x1700` | `0x1780` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2c3` | `0x328` | **`+0x65`** |
| `__TEXT.__objc_methname` | `0x8d1` | `0x92e` | **`+0x5d`** |
| `__TEXT.__cstring` | `0xa87` | `0xad8` | **`+0x51`** |
| `__TEXT.__objc_stubs` | `0xcc0` | `0xd00` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x1b0` | `0x1d0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x290` | `0x2b0` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA.__bss` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x340` | `0x350` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x150` | `0x160` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0

-  Functions: 32
-  Symbols:   96
-  CStrings:  318
+  Functions: 37
+  Symbols:   99
+  CStrings:  327
Symbols:
+ _TIGetDefaultInputModesForLanguage
+ _TIKeyboardMigratorTestCantoneseDictation
+ _objc_retain_x8
CStrings:
+ "%s: AppleKeyboards %{public}@ --> %{public}@"
+ "%s: DictationLanguagesEnabled %{public}@ --> %{public}@"
+ "DictationLanguagesEnabled"
+ "MigrateCantoneseDictationLanguage"
+ "setObject:atIndexedSubscript:"
+ "stringByReplacingOccurrencesOfString:withString:options:range:"
+ "yue_Hant"
+ "zh_HK"
+ "zh_TW"
```
