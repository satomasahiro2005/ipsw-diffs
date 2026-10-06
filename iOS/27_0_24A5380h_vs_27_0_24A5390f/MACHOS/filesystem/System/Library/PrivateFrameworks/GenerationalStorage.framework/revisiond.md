## revisiond

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/revisiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x283fc` | `0x291c8` | **`+0xdcc`** |
| `__TEXT.__cstring` | `0x5172` | `0x5268` | **`+0xf6`** |
| `__DATA_CONST.__cfstring` | `0x2640` | `0x2720` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x3a38` | `0x3add` | **`+0xa5`** |
| `__TEXT.__objc_stubs` | `0x33a0` | `0x3420` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2a45` | `0x2a8a` | **`+0x45`** |
| `__TEXT.__objc_methtype` | `0x12f6` | `0x1333` | **`+0x3d`** |
| `__DATA.__objc_const` | `0x2e50` | `0x2e80` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x133c` | `0x136c` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1010` | `0x1030` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8e8` | `0x900` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1028` | `0x1030` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x298` | `0x2a0` | **`+0x8`** |
| `__TEXT.__const` | `0x258` | `0x250` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1a8` | `0x1ac` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-403.0.0.0.0
+405.0.0.0.1

-  Functions: 857
-  Symbols:   338
-  CStrings:  1556
+  Functions: 871
+  Symbols:   339
+  CStrings:  1572
Symbols:
+ _SANDBOX_CHECK_NO_REPORT
CStrings:
+ "/.nofollow"
+ "22:09:26"
+ "@36@0:8@16B24^@28"
+ "B32@0:8i16B20^{GSCredential=iII{?=[8I]}}24"
+ "Jul 10 2026"
+ "TB,N,V_canWriteDocument"
+ "[ERROR] Provider-content-version V2 build failed, falling back to V1"
+ "_canWriteDocument"
+ "_checkSandboxAccessToFD:readWrite:credential:"
+ "_validatedPath:needsWriteAccess:error:"
+ "caller doesn't have read access"
+ "caller doesn't have read access to requested location"
+ "caller doesn't have write access to %@"
+ "caller doesn't have write access to requested location"
+ "canWriteDocument"
+ "invalid realpath"
+ "kGSProviderContentVersionPreviousBase"
+ "setCanWriteDocument:"
- "22:03:50"
- "Jun 26 2026"
```
