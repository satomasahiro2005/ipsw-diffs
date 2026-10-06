## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12bf34` | `0x12bafc` | **`-0x438`** |
| `__TEXT.__cstring` | `0x14ec8` | `0x14d8f` | **`-0x139`** |
| `__AUTH_CONST.__cfstring` | `0x11560` | `0x114e0` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x5898` | `0x58c0` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x24e38` | `0x24e58` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xe8b4` | `0xe8a4` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xad8` | `0xad0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7030` | `0x7028` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x10bc` | `0x10c0` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x8a50` | `0x8a54` | **`+0x4`** |

### Other Changes

```diff

-4780.0.0.502.1
+4838.0.29.502.2

-  CStrings:  4049
+  CStrings:  4045
Symbols:
+ -[NSXPCConnection(FPAdditions) fp_hasOneOfEntitlements:nonSandboxedAccess:logLevel:callerSelector:]
+ _FPReportNonSandboxedBypass
+ _OBJC_IVAR_$_FPFetchThumbnailsOperation._mappedIDs
+ ___block_descriptor_122_e8_32s40s48s56s64s72bs80r88r96w_e22_v16?0"NSInvocation"8lr80l8s32l8s40l8s48l8s56l8w96l8s72l8s64l8r88l8
- -[NSXPCConnection(FPAdditions) fp_hasOneOfEntitlements:]
- -[NSXPCConnection(FPAdditions) fp_hasOneOfEntitlements:logLevel:]
- _SANDBOX_EXTENSION_CANONICAL
- ___block_descriptor_122_e8_32s40s48s56s64s72bs80r88r96w_e22_v16?0"NSInvocation"8ls32l8r80l8s40l8s48l8s56l8w96l8s72l8s64l8r88l8
CStrings:
+ "4838.0.29.502.2"
+ "couldn't issue sandbox extension %s for '%@': %s"
- "4780.0.0.502.1"
- "couldn't issue sandbox extension %s for '%s': %s"
- "couldn't issue sandbox extension %s for '%s'; failed strdup concatenated path"
- "couldn't issue sandbox extension %s for '%s'; failed to build path from parent"
- "couldn't issue sandbox extension %s for '%s'; failed to get realpath for parent: %s"
- "couldn't issue sandbox extension %s for '%s'; failed to get realpath: %s"
```
