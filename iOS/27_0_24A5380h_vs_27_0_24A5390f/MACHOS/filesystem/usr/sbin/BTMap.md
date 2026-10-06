## BTMap

> `/usr/sbin/BTMap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4344` | `0x44e4` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x37a` | `0x44b` | **`+0xd1`** |
| `__TEXT.__auth_stubs` | `0x600` | `0x610` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x310` | `0x318` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2700.35.0.0.0
+2700.38.0.0.0

-  Symbols:   153
-  CStrings:  333
+  Symbols:   154
+  CStrings:  336
Symbols:
+ _objc_retain_x22
Functions:
~ sub_1000046c4 : 1096 -> 1512
CStrings:
+ "serializeIMChats: bestIMHandle is nil; omitting local participant from chat %@"
+ "serializeIMChats: nil participant handle (raw ID %@) in chat %@; skipping"
+ "serializeIMChats: no IMChat for identifier %@; skipping"
```
