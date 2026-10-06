## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x101170` | `0x101cb8` | **`+0xb48`** |
| `__DATA.__objc_const` | `0x1a400` | `0x1a688` | **`+0x288`** |
| `__TEXT.__oslogstring` | `0x16513` | `0x16612` | **`+0xff`** |
| `__TEXT.__objc_methlist` | `0xdb14` | `0xdbec` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x4f10` | `0x4fb0` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0xc200` | `0xc280` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1c7f1` | `0x1c853` | **`+0x62`** |
| `__TEXT.__cstring` | `0xe274` | `0xe2cb` | **`+0x57`** |
| `__TEXT.__objc_classname` | `0x21b9` | `0x21fc` | **`+0x43`** |
| `__TEXT.__objc_stubs` | `0x110a0` | `0x110e0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3a60` | `0x3a88` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1120` | `0x1140` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5ec0` | `0x5ed8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x4c20` | `0x4c38` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x8a0` | `0x8b0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x7e8` | `0x7f8` | **`+0x10`** |
| `__TEXT.__const` | `0x6aa` | `0x69a` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x11ec` | `0x11f4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1075.12.0.0.0
+1075.15.0.0.0

-  Functions: 5834
-  Symbols:   708
-  CStrings:  8679
+  Functions: 5853
+  Symbols:   710
+  CStrings:  8691
Symbols:
+ _CFPreferencesCopyKeyList
+ _CFPreferencesSynchronize
CStrings:
+ "39"
+ "EPSagaOperandStringArray"
+ "EPSagaTransactionEraseUserDefaultsDomains"
+ "EPSagaTransactionEraseUserDefaultsDomains: cleared %ld key(s) from %@, error=%@"
+ "EPSagaTransactionEraseUserDefaultsDomains: could not resolve %@ for %{public}@, skipping"
+ "EPSagaTransactionEraseUserDefaultsDomains: erased %ld key(s) from %@, synchronized=%d"
+ "NanoRegistry-1075.15"
+ "T@\"NSArray\",R,N,V_strings"
+ "copyKeyList"
+ "initWithDomain:pairingID:pairingDataStore:"
+ "initWithStrings:"
+ "localPairingDataStorePath"
+ "npsPerGizmoDomainsToClear"
+ "userDefaultsDomainsToErase"
- "42"
- "NanoRegistry-1075.12"
```
