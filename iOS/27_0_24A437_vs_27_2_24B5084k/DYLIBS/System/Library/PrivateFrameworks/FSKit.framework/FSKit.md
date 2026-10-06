## FSKit

> `/System/Library/PrivateFrameworks/FSKit.framework/FSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53b8c` | `0x53dec` | **`+0x260`** |
| `__TEXT.__cstring` | `0x676f` | `0x67df` | **`+0x70`** |
| `__DATA.__data` | `0x1538` | `0x1598` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x3f76` | `0x3fb6` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xb2b8` | `0xb2e8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6348` | `0x6378` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2ae0` | `0x2b00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c18` | `0x2c30` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xe5c` | `0xe64` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1848` | `0x1850` | **`+0x8`** |

### Other Changes

```diff

-974.0.13.0.2
+974.40.11.0.0

-  Functions: 2706
-  Symbols:   4255
-  CStrings:  1099
+  Functions: 2711
+  Symbols:   4263
+  CStrings:  1104
Symbols:
+ +[FSKitConstants(project) FSClientFSCKXPCProtocols]
+ -[FSClient hasFSCKEntitlement]
+ -[FSClient isEntitlementSet:]
+ GCC_except_table39
+ GCC_except_table43
+ GCC_except_table68
+ GCC_except_table78
+ GCC_except_table8
+ _OUTLINED_FUNCTION_25
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_FSClientFSCKXPC
+ __OBJC_$_PROTOCOL_METHOD_TYPES_FSClientFSCKXPC
+ __OBJC_$_PROTOCOL_REFS_FSClientFSCKXPC
+ __OBJC_LABEL_PROTOCOL_$_FSClientFSCKXPC
+ __OBJC_PROTOCOL_$_FSClientFSCKXPC
+ __OBJC_PROTOCOL_REFERENCE_$_FSClientFSCKXPC
- GCC_except_table37
- GCC_except_table41
- GCC_except_table66
- GCC_except_table69
- GCC_except_table76
- GCC_except_table94
- GCC_except_table97
CStrings:
+ "%s: rename flags aren't supported (requested 0x%x). Error = %d."
+ "FSClient setting up %s connection to fskitd"
+ "com.apple.private.security.disk-device-access"
+ "com.apple.rootless.restricted-block-devices"
+ "fsck"
+ "unprivileged"
- "FSClient setting up %@ connection to fskitd"
```
