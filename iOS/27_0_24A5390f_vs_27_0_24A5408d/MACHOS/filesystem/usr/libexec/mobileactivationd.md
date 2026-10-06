## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x5c4d3` | `0x60b63` | **`+0x4690`** |
| `__DATA_CONST.__const` | `0x1c0a8` | `0x1c4f8` | **`+0x450`** |
| `__TEXT.__text` | `0x34c224` | `0x34c2ac` | **`+0x88`** |
| `__TEXT.__cstring` | `0xeea5` | `0xeeb1` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1145.0.1.0.0
+1145.0.1.0.1

-  Symbols:   4028
+  Symbols:   4049
Symbols:
+ _ApplePlatformBootstrapRootCAG1
+ _ApplePlatformBootstrapRootCAG1PublicKey
+ _ApplePlatformBootstrapRootCAG1SKID
+ _ApplePlatformBootstrapRootCAG1SPKI
+ _ApplePlatformBootstrapRootCAG1_public_key
+ _ApplePlatformBootstrapRootCAG1_skid
+ _ApplePlatformBootstrapRootCAG1_spki
+ _ApplePlatformDeveloperRootCAG1
+ _ApplePlatformDeveloperRootCAG1PublicKey
+ _ApplePlatformDeveloperRootCAG1SKID
+ _ApplePlatformDeveloperRootCAG1SPKI
+ _ApplePlatformDeveloperRootCAG1_public_key
+ _ApplePlatformDeveloperRootCAG1_skid
+ _ApplePlatformDeveloperRootCAG1_spki
+ _ApplePlatformMultipurposeRootCAG1
+ _ApplePlatformMultipurposeRootCAG1PublicKey
+ _ApplePlatformMultipurposeRootCAG1SKID
+ _ApplePlatformMultipurposeRootCAG1SPKI
+ _ApplePlatformMultipurposeRootCAG1_public_key
+ _ApplePlatformMultipurposeRootCAG1_skid
+ _ApplePlatformMultipurposeRootCAG1_spki
Functions:
~ _lockcrypto_decode_error : 668 -> 708
~ _lockcrypto_decode_pem : 624 -> 664
~ _lockcrypto_decode_pems : 776 -> 840
~ ___dealwith_activation_block_invoke : 632 -> 624
CStrings:
+ "1145.0.1.0.1"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.0.1.0.1 built on Aug  3 2026 at 22:44:40)"
+ "iOS Device Activator (MobileActivation-1145.0.1.0.1)"
- "1145.0.1"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.0.1 built on Jul 10 2026 at 22:15:12)"
- "iOS Device Activator (MobileActivation-1145.0.1)"
```
