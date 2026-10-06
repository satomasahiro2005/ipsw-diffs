## com.apple.sbd

> `/System/Library/PrivateFrameworks/CloudServices.framework/Helpers/com.apple.sbd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x7bc1` | `0x7c49` | **`+0x88`** |
| `__TEXT.__text` | `0x4ef68` | `0x4eff0` | **`+0x88`** |
| `__DATA.__objc_const` | `0x5440` | `0x5470` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x70c0` | `0x70e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x30a8` | `0x30b8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2038` | `0x2040` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2d0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-747.0.1.0.0
+747.0.2.502.1

-  Functions: 1419
+  Functions: 1420

-  CStrings:  2877
+  CStrings:  2880
CStrings:
+ "TB,R,N,V_preventCylonUsage"
+ "_preventCylonUsage"
+ "decodedEscrowRecordFromData:stingray:env:duplicate:preventCylonUsage:error:"
+ "preventCylonUsage"
+ "rootBaseVersionsForRootType:altDSID:inEnvironment:duplicate:preventCylonUsage:"
+ "rootTrustedVersionsForRootType:altDSID:inEnvironment:duplicate:preventCylonUsage:"
+ "verifyCertData:withCert:withPubKey:stingray:enroll:altDSID:env:duplicate:preventCylonUsage:sigVerification:error:"
- "decodedEscrowRecordFromData:stingray:env:duplicate:error:"
- "rootBaseVersionsForRootType:altDSID:inEnvironment:duplicate:"
- "rootTrustedVersionsForRootType:altDSID:inEnvironment:duplicate:"
- "verifyCertData:withCert:withPubKey:stingray:enroll:altDSID:env:duplicate:sigVerification:error:"
```
