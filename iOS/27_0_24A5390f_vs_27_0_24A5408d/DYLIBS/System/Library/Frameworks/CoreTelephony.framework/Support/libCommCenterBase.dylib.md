## libCommCenterBase.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterBase.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd228c` | `0xd2ff4` | **`+0xd68`** |
| `__TEXT.__oslogstring` | `0x25ef` | `0x2849` | **`+0x25a`** |
| `__TEXT.__gcc_except_tab` | `0x13b38` | `0x13be4` | **`+0xac`** |
| `__TEXT.__const` | `0xd2e0` | `0xd370` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0xc00` | `0xc38` | **`+0x38`** |
| `__TEXT.__cstring` | `0x14a9d` | `0x14ac8` | **`+0x2b`** |
| `__AUTH_CONST.__cfstring` | `0x2cc0` | `0x2ce0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x168` | `0x188` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4e48` | `0x4e60` | **`+0x18`** |
| `__AUTH_CONST.__const` | `0x14470` | `0x14480` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x76d0` | `0x76e0` | **`+0x10`** |
| `__DATA.__data` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-13482.1.0.0.0
+13487.3.0.0.0

-  Functions: 5760
-  Symbols:   9458
-  CStrings:  4486
+  Functions: 5765
+  Symbols:   9472
+  CStrings:  4497
Symbols:
+ __ZN16CSIPacketAddress36getAddressDefaultGatewayForInterfaceEPKciRS_
+ __ZNK16CSIPacketAddress23isPublicRoutableAddressEv
+ __ZNK16CSIPacketAddress28isDefaultGatewayForInterfaceERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEE14__tree_deleterclB9foe220106EPNS_11__tree_nodeIS8_PvEE
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEE7destroyEPNS_11__tree_nodeIS8_PvEE
+ __ZZN12_GLOBAL__N_120isPublicRoutableIPv4EjE9kReserved
+ __ZZN16CSIPacketAddress36getAddressDefaultGatewayForInterfaceEPKciRS_E6rtmSeq
+ _getpid
+ _if_nametoindex
+ _objc_enumerationMutation
+ _objc_release_x27
+ _read
+ _send
+ _strerror
CStrings:
+ "[%s]getAddressDefaultGatewayForInterface: has no default route: %s (%d)"
+ "[%s]getAddressDefaultGatewayForInterface: if_nametoindex failed %s"
+ "[%s]getAddressDefaultGatewayForInterface: ioctl FIONBIO failed %s"
+ "[%s]getAddressDefaultGatewayForInterface: read failed %s (%d)"
+ "[%s]getAddressDefaultGatewayForInterface: route socket setup failed %s"
+ "[%s]getAddressDefaultGatewayForInterface: send failed %s (%d)"
+ "[%s]getAddressDefaultGatewayForInterface: unknown GW: %s (%d)"
+ "[%s]getAddressDefaultGatewayForInterface: unknown IP family1: %s (%d)"
+ "[%s]getAddressDefaultGatewayForInterface: unknown IP family2: %s (%d)"
+ "kPhone"
+ "lastSuccessfulActiveIccidTimestamps"
```
