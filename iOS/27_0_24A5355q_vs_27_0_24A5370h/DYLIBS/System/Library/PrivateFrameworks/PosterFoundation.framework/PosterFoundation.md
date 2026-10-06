## PosterFoundation

> `/System/Library/PrivateFrameworks/PosterFoundation.framework/PosterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dc78` | `0x5e1e0` | **`+0x568`** |
| `__TEXT.__oslogstring` | `0x471e` | `0x47d1` | **`+0xb3`** |
| `__TEXT.__unwind_info` | `0x1848` | `0x18d8` | **`+0x90`** |
| `__DATA.__data` | `0xd20` | `0xd60` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x800` | `0x838` | **`+0x38`** |
| `__TEXT.__const` | `0x570` | `0x558` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd58` | `0xd68` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4959` | `0x4969` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x610` | `0x608` | **`-0x8`** |

### Other Changes

```diff

-341.0.3.0.0
+344.0.101.0.0

-  Symbols:   3110
-  CStrings:  1010
+  Symbols:   3113
+  CStrings:  1014
Symbols:
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ _swift_retain_n
CStrings:
+ "Calistoga"
+ "Collections extension %s configured but no section descriptors — skipping assertion"
+ "Taking assertion for Collections app %s (extension %s) — section descriptors present"
+ "Taking assertion for app %s (extension %s)"
+ "Taking assertions for %ld extensions: %s"
+ "autoRemovable available set: %s"
+ "autoRemovable filter %s: hasConfigured=%{bool}d hasAssertion=%{bool}d → autoRemovable=%{bool}d"
+ "autoRemovable installed set: %s"
+ "autoRemovableAppBundleIdentifiers query: available=%ld installed=%ld"
+ "autoRemovableAppBundleIdentifiers returning %ld apps: %s"
- "App %s: hasConfigured=%{bool}d, hasAssertion=%{bool}d, autoRemovable=%{bool}d"
- "Checking auto-removable apps from %ld installed downloadable poster apps"
- "Collections extension configured but no section descriptors - skipping assertion"
- "Taking assertion for Collections (has section descriptors)"
- "Taking assertion for app %s (extension: %s)"
- "Taking assertions for extensions: [%s]"
```
