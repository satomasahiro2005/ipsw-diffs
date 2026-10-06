## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26c590` | `0x26ccb4` | **`+0x724`** |
| `__TEXT.__objc_stubs` | `0x1d8e0` | `0x1d9c0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x2e5bf` | `0x2e68f` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x23c40` | `0x23cd8` | **`+0x98`** |
| `__DATA_CONST.__cfstring` | `0x1c4a0` | `0x1c520` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x14948` | `0x149b8` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x2fe5c` | `0x2feb3` | **`+0x57`** |
| `__TEXT.__cstring` | `0x2273b` | `0x22791` | **`+0x56`** |
| `__DATA.__objc_data` | `0x5d48` | `0x5d98` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x9858` | `0x98a8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x15e50` | `0x15ea0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0xb01a` | `0xb04a` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x1410` | `0x1428` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x6a58` | `0x6a70` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x2548` | `0x2559` | **`+0x11`** |
| `__TEXT.__auth_stubs` | `0x4350` | `0x4340` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x21b8` | `0x21b0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1528` | `0x1530` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x908` | `0x910` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  Functions: 9910
+  Functions: 9918

-  CStrings:  16392
+  CStrings:  16411
Symbols:
+ _OBJC_CLASS_$_NSURLComponents
- _dispatch_walltime
CStrings:
+ "@40@0:8r*16Q24^@32"
+ "B32@0:8@16Q24"
+ "Deleting non-syncable password-evaluations items from class=%@ with multi-user view=%@"
+ "SecXPCNetworkURL"
+ "allowedURLFromCString:options:error:"
+ "com.apple.password-manager.password-evaluations"
+ "componentsWithString:"
+ "escrowRepairCurrentVersion"
+ "host"
+ "http"
+ "https"
+ "initWithUTF8String:"
+ "isAllowedURL:options:"
+ "isOctagonExcluded:"
+ "lowercaseString"
+ "scheme"
+ "scheme:isAllowedByOptions:"
+ "setError:code:"
+ "v32@0:8^@16q24"
```
