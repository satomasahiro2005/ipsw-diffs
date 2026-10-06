## libcryptex_core.dylib

> `/usr/lib/libcryptex_core.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x160d4` | `0x168e8` | **`+0x814`** |
| `__TEXT.__oslogstring` | `0x2c25` | `0x2d81` | **`+0x15c`** |
| `__TEXT.__cstring` | `0x1b9a` | `0x1c11` | **`+0x77`** |
| `__AUTH_CONST.__auth_got` | `0x720` | `0x770` | **`+0x50`** |
| `__TEXT.__const` | `0x130` | `0x140` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x498` | `0x4a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x270` | `0x278` | **`+0x8`** |

### Other Changes

```diff

-746.0.0.0.0
+757.0.0.0.0

-  Functions: 425
-  Symbols:   810
-  CStrings:  552
+  Functions: 429
+  Symbols:   825
+  CStrings:  564
Symbols:
+ _Img4DecodeGetObjectPropertyData
+ _Img4DecodeInitManifest
+ _Img4EncodeCreateManifest
+ _Img4EncodeItemBegin
+ _Img4EncodeItemCopyBuffer
+ _Img4EncodeItemDestroy
+ _Img4EncodeItemEnd
+ _Img4EncodeItemPropertyBool
+ _Img4EncodeItemPropertyData
+ __str24cc
+ _generate_manifest
+ _generate_objects
+ _kImg4DecodeSecureBootRsa3kSha384
+ _null_signature
+ _os_variant_is_darwinos
CStrings:
+ "%{public}s: couldn't generate cryptex fingerprint"
+ "757"
+ "@(#)VERSION:Darwin Cryptex Core Interface Version 2.0.0: Sat Jun 13 08:36:08 PDT 2026; root:libcryptex-757~412/libcryptex_core/RELEASE_ARM64E"
+ "Darwin Cryptex Core Interface Version 2.0.0: Sat Jun 13 08:36:08 PDT 2026; root:libcryptex-757~412/libcryptex_core/RELEASE_ARM64E"
+ "acdc"
+ "com.apple.security.cryptex.image4encode"
+ "com.apple.security.cryptex.libder"
+ "couldn't allocate object digests for fingerprinting %{darwin.errno}d"
+ "couldn't compute fingerprint digest"
+ "couldn't create manifest for fingerprinting"
+ "couldn't decode generated manifest for fingerprinting"
+ "couldn't decode manifest for fingerprinting"
+ "couldn't get object property %X for fingerprinting"
+ "cryptex_sigtool_fingerprint_create"
+ "ginc"
- "746"
- "@(#)VERSION:Darwin Cryptex Core Interface Version 2.0.0: Thu May 21 08:14:44 PDT 2026; root:libcryptex-746~413/libcryptex_core/RELEASE_ARM64E"
- "Darwin Cryptex Core Interface Version 2.0.0: Thu May 21 08:14:44 PDT 2026; root:libcryptex-746~413/libcryptex_core/RELEASE_ARM64E"
```
