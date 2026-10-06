## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85664` | `0x85964` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0xf36a` | `0xf4f1` | **`+0x187`** |
| `__DATA_CONST.__const` | `0x2788` | `0x27c8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1940` | `0x1958` | **`+0x18`** |
| `__TEXT.__cstring` | `0x120b3` | `0x120c4` | **`+0x11`** |
| `__DATA.__common` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1650` | `0x1660` | **`+0x10`** |
| `__DATA.__bss` | `0x439` | `0x431` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0xb38` | `0xb40` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2d88` | `0x2d8c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-909.0.0.0.0
+910.0.0.0.0

-  Functions: 2918
-  Symbols:   505
-  CStrings:  5737
+  Functions: 2924
+  Symbols:   506
+  CStrings:  5741
Symbols:
+ __exit
CStrings:
+ "AppleLanguagePreferencesChangedNotification"
+ "Force-exiting tccd: language change drain exceeded grace period."
+ "Handling language change (AppleLanguagePreferencesChangedNotification)..."
+ "Initiating language-change shutdown."
+ "ManagedSettings: ignoring Location profile update for %{private}@ - disclosure already acknowledged, managed_overrides record preserved"
+ "tccd_replica_sync_update_from_ManagedOverrideAction: unknown service %{public}@; cannot notify/kill client"
- "Handling language change..."
- "com.apple.language.changed"
```
