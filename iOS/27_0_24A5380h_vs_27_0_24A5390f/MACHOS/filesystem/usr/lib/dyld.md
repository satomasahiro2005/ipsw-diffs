## dyld

> `/usr/lib/dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x12497` | `0x12499` | **`+0x2`** |

### Same-size Content Changes

- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`

### Other Changes

```diff

-27059.3.0.0.0
+27060.1.0.0.0
CStrings:
+ "27060.1"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Jul 14 21:12:31 PDT 2026; root:libignition-64~11776/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Tue Jul 14 21:12:31 PDT 2026; root:libignition-64~11776/libignition_core/RELEASE_ARM64E"
- "27059.3"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Jul  1 23:22:14 PDT 2026; root:libignition-64~9224/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Wed Jul  1 23:22:14 PDT 2026; root:libignition-64~9224/libignition_core/RELEASE_ARM64E"
```
