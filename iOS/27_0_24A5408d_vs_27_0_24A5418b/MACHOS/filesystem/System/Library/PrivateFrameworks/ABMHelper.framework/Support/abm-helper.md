## abm-helper

> `/System/Library/PrivateFrameworks/ABMHelper.framework/Support/abm-helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa00` | `0x8e4` | **`-0x11c`** |
| `__DATA.__data` | `0x54` | `0x4` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x240` | `0x1f0` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x128` | `0x100` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x98` | `0x78` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x50` | `0x34` | **`-0x1c`** |
| `__DATA.__bss` | `0x9` | `0x1` | **`-0x8`** |
| `__TEXT.__init_offsets` | `0x4` | `—` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__got`

### Other Changes

```diff

-  Functions: 12
-  Symbols:   161
+  Functions: 9
+  Symbols:   144
Symbols:
- _CFBooleanGetTypeID
- _CFGetTypeID
- _CFRelease
- _TelephonyBasebandWatchdogStartWithStackshot
- _TelephonyBasebandWatchdogStop
- __ZN12capabilities3abs27kKeySupportsCMHandDetectionE
- __ZN3ctu2cf12MakeCFStringC1EPKc
- __ZN3ctu2cf12MakeCFStringD1Ev
- __ZN3ctu2cf13plist_adapterC1EPK10__CFStringS4_
- __ZN3ctu2cf13plist_adapterD1Ev
- __ZN3ctu2cf6assignERbPK11__CFBoolean
- ___CFConstantStringClassReference
- ___cxa_atexit
- __os_log_default
- _kCFPreferencesCurrentUser
- _pthread_mutex_lock
- _pthread_mutex_unlock
```
