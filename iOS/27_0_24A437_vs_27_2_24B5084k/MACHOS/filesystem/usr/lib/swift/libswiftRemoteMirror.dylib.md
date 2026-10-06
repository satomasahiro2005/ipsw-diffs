## libswiftRemoteMirror.dylib

> `/usr/lib/swift/libswiftRemoteMirror.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x7148` | `0x7122` | **`-0x26`** |
| `__TEXT.__text` | `0xdccf0` | `0xdccd0` | **`-0x20`** |

### Same-size Content Changes

- `__AUTH_CONST.__const`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6.4.0.31.5
+6.4.0.34.1

-  CStrings:  1644
+  CStrings:  1643
Functions:
~ __ZN5swift10reflection26ExistentialTypeInfoBuilder5buildEPNS_6remote16TypeInfoProviderE : 1276 -> 1260
~ __ZN5swift10reflection26ExistentialTypeInfoBuilder16examineProtocolsEv : 676 -> 684
~ __ZN5swift10reflection26ExistentialTypeInfoBuilder13buildMetatypeEPNS_6remote16TypeInfoProviderE : 652 -> 628
CStrings:
- "@objc existential with witness tables"
```
