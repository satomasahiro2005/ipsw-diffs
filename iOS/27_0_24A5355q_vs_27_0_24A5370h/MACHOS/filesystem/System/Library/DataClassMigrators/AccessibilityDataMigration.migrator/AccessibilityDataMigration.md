## AccessibilityDataMigration

> `/System/Library/DataClassMigrators/AccessibilityDataMigration.migrator/AccessibilityDataMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25a4` | `0x2700` | **`+0x15c`** |
| `__TEXT.__cstring` | `0x927` | `0x988` | **`+0x61`** |
| `__TEXT.__objc_methname` | `0xee0` | `0xf30` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x7c0` | `0x800` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1060` | `0x10a0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x470` | `0x480` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x170` | `0x17c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xf0` | `0xf8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xe0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 32
-  Symbols:   84
-  CStrings:  221
+  Functions: 33
+  Symbols:   87
+  CStrings:  225
Symbols:
+ _CFPreferencesCopyValue
+ _kAXSVoiceOverPreferenceDomain
+ _objc_opt_isKindOfClass
CStrings:
+ "AXSVoiceOverDirectTouchEnabledApps"
+ "_AccessibilityMigration__VoiceOverDirectTouchEnabledApps_27.0"
+ "_raveMigrateVoiceOverDirectTouchEnabledApps"
+ "setVoiceOverDirectTouchEnabledApps:"
```
