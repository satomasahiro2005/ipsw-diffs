## PhoneKit

> `/System/Library/PrivateFrameworks/PhoneKit.framework/PhoneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19d04` | `0x19f40` | **`+0x23c`** |
| `__AUTH_CONST.__objc_const` | `0x16e8` | `0x1778` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x70` | `0xc0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x10d4` | `0x110c` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x11c0` | `0x11f0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xcc0` | `0xce0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1c8` | `0x1e8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x993` | `0x9b3` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__DATA.__bss` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x670` | `0x680` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x520` | `0x528` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |

### Other Changes

```diff

-147.100.5.2.1
+153.100.1.2.7

-  Functions: 524
-  Symbols:   1043
-  CStrings:  189
+  Functions: 530
+  Symbols:   1060
+  CStrings:  191
Symbols:
+ -[PHBootSession getBootSessionUUID]
+ -[PHBootSession isInDifferentBootSession]
+ -[PHBootSession lastKnownBootSessionID]
+ -[PHBootSession persistBootSessionID]
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_CLASS_$_PHBootSession
+ _OBJC_METACLASS_$_PHBootSession
+ _PHLastBootUUIDKey
+ _TUBundleIdentifierMobilePhoneApplication
+ __OBJC_$_INSTANCE_METHODS_PHBootSession
+ __OBJC_CLASS_RO_$_PHBootSession
+ __OBJC_METACLASS_RO_$_PHBootSession
+ ___35-[PHBootSession getBootSessionUUID]_block_invoke
+ _getBootSessionUUID.bootUUID
+ _getBootSessionUUID.onceToken
+ _objc_opt_new
+ _sysctlbyname
CStrings:
+ "PHLastBootUUIDKey"
+ "kern.bootsessionuuid"
```
