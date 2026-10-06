## HMFoundation

> `/System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x981c8` | `0x98a74` | **`+0x8ac`** |
| `__TEXT.__const` | `0x3010` | `0x3100` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x3197` | `0x31c7` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x7994` | `0x79c4` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4b60` | `0x4b80` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xe698` | `0xe6b8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3130` | `0x3148` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x31e8` | `0x31f8` | **`+0x10`** |

### Other Changes

```diff

-1490.2.0.1.1
+1493.1.5.1.1

-  Functions: 3664
-  Symbols:   5504
-  CStrings:  1426
+  Functions: 3668
+  Symbols:   5519
+  CStrings:  1427
Symbols:
+ +[NSData(FastEncoding) hmf_fastEncodedDataForObject:]
+ +[NSData(FastEncoding) hmf_fastEncodedSizeForObject:]
+ _HMFFastEncodedSize
+ _HMFProductInfoEclipseBOSVersion
+ _HMFProductInfoEclipsePopOSVersion
+ _HMFProductInfoFizzBOSVersion
+ _HMFProductInfoFizzPopOSVersion
+ _HMFProductInfoLotusBOSVersion
+ _HMFProductInfoLotusPopOSVersion
+ _HMFProductInfoOrchidBOSVersion
+ _HMFProductInfoOrchidPopOSVersion
+ _HMFProductInfoRaveBOSVersion
+ _HMFProductInfoRavePopOSVersion
+ __OBJC_$_PROP_LIST_HMFFastEncodable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMFFastEncodable
CStrings:
+ "Unexpected object type %@ (%@) in fast encoding"
```
