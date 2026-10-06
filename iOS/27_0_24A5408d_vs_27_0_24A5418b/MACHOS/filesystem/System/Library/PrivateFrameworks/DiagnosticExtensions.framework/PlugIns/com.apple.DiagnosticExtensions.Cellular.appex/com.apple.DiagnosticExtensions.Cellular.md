## com.apple.DiagnosticExtensions.Cellular

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/com.apple.DiagnosticExtensions.Cellular.appex/com.apple.DiagnosticExtensions.Cellular`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2595c` | `0x25834` | **`-0x128`** |
| `__DATA.__data` | `0xf0` | `0xa0` | **`-0x50`** |
| `__DATA.__bss` | `0xc8` | `0x80` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x33b8` | `0x3388` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x7a8` | `0x778` | **`-0x30`** |
| `__TEXT.__cstring` | `0x4cd` | `0x4a6` | **`-0x27`** |
| `__TEXT.__auth_stubs` | `0xbb0` | `0xb90` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x5e8` | `0x5d8` | **`-0x10`** |
| `__TEXT.__init_offsets` | `0x10` | `0x8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 295
-  Symbols:   385
-  CStrings:  249
+  Functions: 290
+  Symbols:   375
+  CStrings:  247
Symbols:
- _CFPreferencesSetValue
- _CFPreferencesSynchronize
- _TelephonyBasebandWatchdogStartWithStackshot
- _TelephonyBasebandWatchdogStop
- __ZN3ctu2cf12convert_copyERPK10__CFStringRKNSt3__112basic_stringIcNS5_11char_traitsIcEENS5_9allocatorIcEEEEjPK13__CFAllocator
- __ZN3ctu2cf13plist_adapterC1EPK10__CFStringS4_
- __ZN3ctu2cf13plist_adapterD1Ev
- __ZN3ctu2cf6assignERNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPKv
- _kCFPreferencesCurrentHost
- _kCFPreferencesCurrentUser
CStrings:
- "Watchdog timed out"
- "boot-args='([^']*)'"
```
