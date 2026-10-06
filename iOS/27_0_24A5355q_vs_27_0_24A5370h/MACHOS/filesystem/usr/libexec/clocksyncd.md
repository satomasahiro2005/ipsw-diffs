## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b080` | `0x3af9c` | **`-0xe4`** |
| `__TEXT.__gcc_except_tab` | `0x1a70` | `0x1ac0` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x5980` | `0x59c0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x9149` | `0x917d` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x920` | `0x948` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x369c` | `0x36b4` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1d80` | `0x1d90` | **`+0x10`** |
| `__TEXT.__const` | `0x121` | `0x129` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xe80` | **`+0x8`** |
| `__TEXT.__cstring` | `0x27e1` | `0x27e0` | **`-0x1`** |
| `__TEXT.__oslogstring` | `0x57ea` | `0x57e9` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1500.96.0.0.0
+1501.1.0.0.0

-  CStrings:  2449
+  CStrings:  2451
CStrings:
+ "%@: Cannot acquire activation lock. Exclusive access given to entity: %@, pid: %i\n"
+ "%@: Cannot acquire activation lock. It is already held.\n"
+ "1501.1"
+ "_dispatchLockState:onlyIfChanged:"
+ "i28@0:8@\"TSDSyncEntity\"16i24"
+ "removeFromStorage"
+ "v24@0:8i16B20"
- "%@: Cannot acquire activation lock. Exclusive access given to entity: %@, pid: %i\n."
- "%@: Cannot acquire activation lock. It is already held\n."
- "1500.96"
- "B28@0:8@\"TSDSyncEntity\"16i24"
- "B28@0:8@16i24"
```
