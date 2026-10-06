## UserProfilesCore

> `/System/Library/PrivateFrameworks/UserProfilesCore.framework/UserProfilesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9d4c` | `0xa110` | **`+0x3c4`** |
| `__AUTH_CONST.__objc_const` | `0x2ce0` | `0x2e50` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0x900` | `0x960` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__TEXT.__cstring` | `0x7d7` | `0x827` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xcfc` | `0xd4c` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2d0` | `0x2f8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f0` | `0x910` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x400` | `0x418` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xa8` | `0xb4` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |

### Other Changes

```diff

-299.0.2.0.0
+299.0.7.0.0

-  Functions: 367
-  Symbols:   761
-  CStrings:  119
+  Functions: 377
+  Symbols:   781
+  CStrings:  122
Symbols:
+ -[UPClientRecord .cxx_destruct]
+ -[UPClientRecord auditToken]
+ -[UPClientRecord copyWithZone:]
+ -[UPClientRecord initWithAuditToken:]
+ -[UPClientRecord pid]
+ -[UPClientRecord processName]
+ _BSProcessNameForPID
+ _OBJC_CLASS_$_UPClientRecord
+ _OBJC_IVAR_$_UPClientRecord._auditToken
+ _OBJC_IVAR_$_UPClientRecord._processName
+ _OBJC_IVAR_$_UPClientRecord._processNameOnceToken
+ _OBJC_METACLASS_$_UPClientRecord
+ __OBJC_$_INSTANCE_METHODS_UPClientRecord
+ __OBJC_$_INSTANCE_VARIABLES_UPClientRecord
+ __OBJC_$_PROP_LIST_UPClientRecord
+ __OBJC_CLASS_PROTOCOLS_$_UPClientRecord
+ __OBJC_CLASS_RO_$_UPClientRecord
+ __OBJC_METACLASS_RO_$_UPClientRecord
+ ___29-[UPClientRecord processName]_block_invoke
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
CStrings:
+ "BSAuditToken"
+ "UPClientRecord.m"
+ "[_bs_assert_object isKindOfClass:BSAuditTokenClass]"
```
