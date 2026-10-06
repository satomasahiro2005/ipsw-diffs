## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x197b1c` | `0x198240` | **`+0x724`** |
| `__TEXT.__cstring` | `0x36bb6` | `0x36db6` | **`+0x200`** |
| `__TEXT.__const` | `0x5fa0` | `0x6160` | **`+0x1c0`** |
| `__DATA_CONST.__const` | `0x8448` | `0x8498` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x1c800` | `0x1c840` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x135e0` | `0x13620` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `0x3c0` | `0x3d8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x5e70` | `0x5e80` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xa0c8` | `0xa0d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5968` | `0x5970` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-747.100.2.0.0
+751.100.2.0.0

-  Functions: 8590
+  Functions: 8599

-  CStrings:  10843
+  CStrings:  10854
CStrings:
+ "-[RPServiceDiscoveryClient _cLinkDeviceChanged:]"
+ "-[RPServiceDiscoveryClient _cLinkDeviceChanged:]_block_invoke_2"
+ "-[RPServiceDiscoveryClient _cLinkStart]_block_invoke_7"
+ "Cached peer changed trust %#ll{flags} -> %#ll{flags} for %@\n"
+ "Error reporting change 0x%#lx for %@: %@"
+ "Error retrieving identities for %@: %@"
+ "Established authentication with peer %@"
+ "Ignoring change to unauthenticated peer %@"
+ "Lost authentication with peer %@"
+ "Preserving session paired identity for guest mic-only teardown (rapportId %@ deviceConfirmed %@)\n"
+ "Removing session paired identity for fully-lost device (spID %@ ids %@)\n"
+ "_cLinkDeviceChanged:"
+ "deviceChanged:changes:completionHandler:"
- "-[RPServiceDiscoveryClient _cLinkStart]_block_invoke_6"
- "MockA2DPActivity"
```
