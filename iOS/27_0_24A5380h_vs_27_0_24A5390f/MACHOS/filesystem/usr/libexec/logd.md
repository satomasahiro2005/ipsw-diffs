## logd

> `/usr/libexec/logd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2737c` | `0x27694` | **`+0x318`** |
| `__TEXT.__cstring` | `0x4895` | `0x4a0a` | **`+0x175`** |
| `__TEXT.__objc_stubs` | `0x5e0` | `0x640` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x3e2` | `0x428` | **`+0x46`** |
| `__TEXT.__auth_stubs` | `0x1b90` | `0x1bc0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2378` | `0x2398` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x190` | `0x1a8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xdd0` | `0xde8` | **`+0x18`** |
| `__DATA.__bss` | `0xeb68` | `0xeb78` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x160` | `0x168` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x690` | `0x698` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1965.0.0.0.0
+1966.0.6.0.0

+  - /System/Library/Frameworks/SecureConfigDB.framework/SecureConfigDB

-  Functions: 514
-  Symbols:   496
-  CStrings:  624
+  Functions: 515
+  Symbols:   500
+  CStrings:  633
Symbols:
+ _CFBooleanGetValue
+ _OBJC_CLASS_$_SecureConfigParameters
+ __os_trace_prefscachedir_path
+ _objc_opt_class
CStrings:
+ "Failed to check REM status. Enforcing logging privacy for this boot. (errno: %d)"
+ "Failed to create prefscachedir %s"
+ "Failed to load SecureConfigParameters; enforcing logging privacy for this boot. Error %ld - %s: %s"
+ "SecureConfig present but not in REM. No logging privacy enforcement for this boot."
+ "loadContentsAndReturnError:"
+ "localizedDescription"
+ "logFilteringEnforced"
+ "logFilteringEnforced: %d"
+ "security.mac.amfi.restricted_execution_mode_status"
```
