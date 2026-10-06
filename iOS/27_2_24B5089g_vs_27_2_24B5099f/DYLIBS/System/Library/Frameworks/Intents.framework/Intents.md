## Intents

> `/System/Library/Frameworks/Intents.framework/Intents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x16a80` | `0x15388` | **`-0x16f8`** |
| `__DATA_DIRTY.__objc_data` | `0x3160` | `0x4858` | **`+0x16f8`** |
| `__TEXT.__text` | `0x461570` | `0x4615a0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x21bc` | `0x21c4` | **`+0x8`** |

### Other Changes

```diff

-4016.1.8.0.0
+4016.1.13.0.0
Symbols:
+ __CFBundleGetBundleWithIdentifierAndLibraryName
- _CFBundleGetBundleWithIdentifier
Functions:
~ -[INStringLocalizer bundleWithIdentifier:fileURL:] : 952 -> 988
~ _INCSLocalizedString : 748 -> 760
```
