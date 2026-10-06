## sensorkitd

> `/usr/libexec/sensorkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41d94` | `0x41ffc` | **`+0x268`** |
| `__TEXT.__oslogstring` | `0x7098` | `0x7148` | **`+0xb0`** |
| `__DATA.__objc_const` | `0x5fd0` | `0x6038` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x25e4` | `0x264c` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x3880` | `0x38e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x5d22` | `0x5d64` | **`+0x42`** |
| `__TEXT.__objc_methtype` | `0x27e7` | `0x2816` | **`+0x2f`** |
| `__TEXT.__cstring` | `0x2f96` | `0x2fbd` | **`+0x27`** |
| `__DATA_CONST.__cfstring` | `0x3280` | `0x3260` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x1440` | `0x1458` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x30` | `0x48` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x454` | `0x468` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x378` | `0x388` | **`+0x10`** |
| `__DATA.__bss` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__DATA.__common` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa20` | `0xa18` | **`-0x8`** |
| `__TEXT.__objc_classname` | `0x8f5` | `0x8f1` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1025.0.0.0.0
+1027.0.0.0.0

-  Functions: 821
-  Symbols:   324
-  CStrings:  2266
+  Functions: 825
+  Symbols:   326
+  CStrings:  2272
Symbols:
+ _kSecAttrAccessible
+ _kSecAttrAccessibleAfterFirstUnlock
CStrings:
+ "@\"<RDKeychainStoring>\""
+ "@\"RDKeychainCache\""
+ "Attempted add of key %{private}@ to keychain: %{public, bool}d, cache %{public, bool}d"
+ "B32@0:8@\"NSData\"16@\"NSString\"24"
+ "Failed to generate source identifier key: %d"
+ "Failed to persist source identifier key to keychain; cached in memory only for this process lifetime"
+ "Failed to store source identifier key in the keychain. %{public}@"
+ "RDKeychainStoring"
+ "cacheKey:withName:"
+ "cachedKeyDataForName:"
+ "com.apple.sensorkitd.SourceIdentifier"
+ "removeCachedKey:"
+ "sourceIdentifierKey"
- "@\"<RDDatastoreKeyStoring>\""
- "Attempted add to key %{private}@ to keychain: %{public, bool}d, cache %{public, bool}d"
- "Key %{private}@ found in %{public}@"
- "RDDatastoreKeyStoring"
- "cache"
- "dataForKey:"
- "keychain"
```
