## seld

> `/usr/libexec/seld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x273b8` | `0x271dc` | **`-0x1dc`** |
| `__DATA_CONST.__cfstring` | `0x2420` | `0x22e0` | **`-0x140`** |
| `__TEXT.__cstring` | `0x4551` | `0x444d` | **`-0x104`** |
| `__TEXT.__objc_methname` | `0x3996` | `0x38b5` | **`-0xe1`** |
| `__TEXT.__objc_stubs` | `0x33e0` | `0x33a0` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0xf98` | `0xf68` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x238` | `0x258` | **`+0x20`** |
| `__TEXT.__const` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x440` | `0x448` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  Symbols:   222
-  CStrings:  1735
+  Symbols:   221
+  CStrings:  1719
Symbols:
- _OBJC_CLASS_$_NSAssertionHandler
CStrings:
- "Invalid parameter not satisfying: %@"
- "NFRemoteAdminConnectionHTTP.m"
- "NFRemoteAdminReaderSession.m"
- "NFRemoteAdminRedirectSession.m"
- "NFRemoteAdminStorage.m"
- "Out of resources"
- "Unknown result: %lu"
- "_NFRemoteAdminManager.m"
- "_connectToServer:oneTimeConnection:secureElementManagerSession:"
- "_getSessionWithProprietaryHeaders"
- "currentHandler"
- "handleFailureInMethod:object:file:lineNumber:description:"
- "networkCallbackQueue is nil"
- "redirectStateForIdentifier:"
- "serverStateForIdentifier:"
- "theIdentifier != nil"
```
