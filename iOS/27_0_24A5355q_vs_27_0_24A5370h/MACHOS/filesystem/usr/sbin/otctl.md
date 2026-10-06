## otctl

> `/usr/sbin/otctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18be4` | `0x189a0` | **`-0x244`** |
| `__TEXT.__cstring` | `0x3a9e` | `0x39f9` | **`-0xa5`** |
| `__TEXT.__objc_methname` | `0x3de6` | `0x3d8e` | **`-0x58`** |
| `__TEXT.__objc_stubs` | `0x2660` | `0x2620` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0xa42` | `0xa1f` | **`-0x23`** |
| `__TEXT.__gcc_except_tab` | `0x798` | `0x784` | **`-0x14`** |
| `__DATA.__objc_selrefs` | `0xe98` | `0xe88` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x518` | `0x508` | **`-0x10`** |
| `__TEXT.__const` | `0xa8` | `0xa0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xd74` | `0xd6c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Functions: 343
+  Functions: 341

-  CStrings:  1223
+  CStrings:  1216
CStrings:
- "Error rerolling for stable trusted device ID: %s\n"
- "Reroll PeerID for stable trusted device ID"
- "Reroll for stable trusted device ID successful."
- "operation: reroll-stable-device-id"
- "reroll-stable-device-id"
- "rerollForStableTrustedDeviceID:reply:"
- "rerollForStableTrustedDeviceIDWithArguments:json:"
```
