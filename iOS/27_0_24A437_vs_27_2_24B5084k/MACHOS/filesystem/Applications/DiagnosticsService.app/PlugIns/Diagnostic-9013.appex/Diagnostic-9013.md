## Diagnostic-9013

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9013.appex/Diagnostic-9013`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd68` | `0x8e4` | **`-0x484`** |
| `__TEXT.__oslogstring` | `0x10d` | `0x33` | **`-0xda`** |
| `__TEXT.__objc_stubs` | `0x380` | `0x2e0` | **`-0xa0`** |
| `__TEXT.__auth_stubs` | `0x1e0` | `0x180` | **`-0x60`** |
| `__DATA_CONST.__cfstring` | `0x100` | `0xc0` | **`-0x40`** |
| `__TEXT.__cstring` | `0xed` | `0xb8` | **`-0x35`** |
| `__DATA_CONST.__auth_got` | `0xf8` | `0xc8` | **`-0x30`** |
| `__TEXT.__const` | `0x70` | `0x60` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x3da` | `0x3ca` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x98` | `0x88` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1c0` | `0x1b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Functions: 23
-  Symbols:   58
-  CStrings:  122
+  Functions: 19
+  Symbols:   52
+  CStrings:  112
Symbols:
- _objc_release_x23
- _objc_release_x24
- _objc_release_x25
- _objc_release_x26
- _objc_release_x27
- _objc_release_x28
CStrings:
- "Bat GG status converted: %ld"
- "Failed to open gasgauge, error: %@"
- "Failed to probe gasgauge status, error: %@"
- "Gasgauge already locked, exiting..."
- "Gasgauge locking not required, exiting..."
- "Locking gasgauge..."
- "currentGasgaugeLockStatus"
- "doGgLock: %d"
- "numberWithBool:"
- "previousGasgaugeLockStatus"
```
