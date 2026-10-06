## asd

> `/usr/libexec/asd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x781b30` | `0x829110` | **`+0xa75e0`** |
| `__TEXT.__const` | `0xcab40` | `0xd0e70` | **`+0x6330`** |
| `__DATA.__objc_const` | `0x8188` | `0x8250` | **`+0xc8`** |
| `__TEXT.__objc_methname` | `0xa2a4` | `0xa334` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x7500` | `0x7580` | **`+0x80`** |
| `__DATA.__objc_data` | `0x2e50` | `0x2ea0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x3574` | `0x35c4` | **`+0x50`** |
| `__DATA.__data` | `0xebf0` | `0xebc0` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x2258` | `0x2280` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0xcb9` | `0xcd9` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3967` | `0x3987` | **`+0x20`** |
| `__DATA.__common` | `0x22c` | `0x244` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4710` | `0x46f8` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x28fc8` | `0x28fd8` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x11c3b` | `0x11c2b` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x6c0` | `0x6c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x280` | `0x284` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 6295
+  Functions: 6303

-  CStrings:  2704
+  CStrings:  2713
CStrings:
+ "ASTrustInsightsCryptoProxy"
+ "TC,N,V_hYwbtgSCyURp3EJR"
+ "_hYwbtgSCyURp3EJR"
+ "authenticateMessageXPC:completion:"
+ "cache cleanup time in use object"
+ "hYwbtgSCyURp3EJR"
+ "isInUseForKey:"
+ "qZgDzsH6tZxglfVB"
+ "setHYwbtgSCyURp3EJR:"
+ "trustInsightsMAC:"
- "zClr2kpkWWOzbRnw"
```
