## CommCenterMobileHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterMobileHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x713bc` | `0x708f4` | **`-0xac8`** |
| `__TEXT.__oslogstring` | `0x3957` | `0x36f7` | **`-0x260`** |
| `__TEXT.__gcc_except_tab` | `0x90e8` | `0x9084` | **`-0x64`** |
| `__TEXT.__objc_stubs` | `0x2940` | `0x2900` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x6e60` | `0x6e80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3af0` | `0x3ad0` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0xb88` | `0xb78` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x23c1` | `0x23b1` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-13496.3.0.0.0
+13498.0.0.0.0

-  Functions: 3066
+  Functions: 3051

-  CStrings:  1751
+  CStrings:  1730
CStrings:
- "%@ adding cellular(%lu), roaming(%lu)"
- "%@ is a hidden app"
- "%@ is a remote app"
- "%@ is a system service"
- "%@ is an app"
- "%@ is an uninstalled app"
- "%@ mapped to %@ adding usage cellular(%lu), roaming(%lu)"
- "Found codec in cache: path: %s, id: %u"
- "Hypothesis: %@"
- "Lat/Long of departure airport (%f/%f) & arrival airport (%f/%f) "
- "Loaded codec from path: %s, id: %u"
- "Not adding wifi assist"
- "Process (%@) does not have a bundle name"
- "Received %d bytes, %d bytes total so far"
- "Record %@ progress %f"
- "Removed codec from cache. path: %s, id: %u"
- "Reset context"
- "Restricted prediction to: %@"
- "cellularHome"
- "cellularRoaming"
- "fetch bundle data from url: %s, background: %d"
```
