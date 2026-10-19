## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x272da8` | `0x273eec` | **`+0x1144`** |
| `__TEXT.__oslogstring` | `0x30181` | `0x30404` | **`+0x283`** |
| `__DATA.__objc_const` | `0x23da8` | `0x23ef0` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x15f48` | `0x15fe0` | **`+0x98`** |
| `__DATA_CONST.__cfstring` | `0x1cf20` | `0x1cfa0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x23052` | `0x230c7` | **`+0x75`** |
| `__TEXT.__objc_methname` | `0x2ec67` | `0x2ecbf` | **`+0x58`** |
| `__DATA.__objc_data` | `0x5d98` | `0x5de8` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1dda0` | `0x1dde0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0xb176` | `0xb1b4` | **`+0x3e`** |
| `__DATA_CONST.__objc_intobj` | `0x1440` | `0x1470` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x2559` | `0x2584` | **`+0x2b`** |
| `__TEXT.__unwind_info` | `0x6b00` | `0x6b18` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x99a8` | `0x99b8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1af8` | `0x1b04` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x14b50` | `0x14b58` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x910` | `0x918` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x810` | `0x818` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa0fc` | `0xa104` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 9945
+  Functions: 9957

-  CStrings:  16559
+  CStrings:  16579
CStrings:
+ "<CKKSFixup:KeyMaterialAccessibility (%@)>"
+ "B48@0:8@16^{__CFString=}24^{__CFString=}32^@40"
+ "CDP is enabled, Skipping backing up sync items"
+ "CKKSFixupKeyMaterialAccessibilityOperation"
+ "Fixup %@ is needed, but device is locked; deferring until unlock"
+ "Minimum fixup across all zones is %lu (current is %lu)"
+ "No fixups needed, all zones up to date"
+ "Successfully performed a KeyMaterialAccessibility fixup"
+ "Unable to fetch CDP status: %@"
+ "Unable to fix up AfterFirstUnlock key material because device is locked; will retry after unlock"
+ "Unable to fix up AfterFirstUnlock key material: %@"
+ "Unable to fix up WhenUnlocked key material because device is locked; will retry after unlock"
+ "Unable to fix up WhenUnlocked key material: %@"
+ "Updated zone fixup state to CKKSFixupKeyMaterialAccessibility"
+ "com.apple.security.egoIdentities"
+ "fixup_key_material_accessibility"
+ "getCDPStatusSync:error:"
+ "q32@0:8@16^@24"
+ "sync = 0"
+ "updateKeyMaterialAccessibilityInZone:fromAccessible:toAccessible:error:"
```
