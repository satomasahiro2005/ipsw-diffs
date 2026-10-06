## XOJIT

> `/System/Library/PrivateFrameworks/XOJIT.framework/XOJIT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x255d08` | `0x256438` | **`+0x730`** |
| `__TEXT.__cstring` | `0x7ba5b` | `0x7bb02` | **`+0xa7`** |
| `__TEXT.__oslogstring` | `0x16e` | `0x1cd` | **`+0x5f`** |
| `__AUTH_CONST.__auth_got` | `0x948` | `0x968` | **`+0x20`** |
| `__TEXT.__const` | `0x1e79c` | `0x1e7ac` | **`+0x10`** |
| `__DATA_CONST.__orc_runtime` | `0x7b03b8` | `0x7b03b0` | **`-0x8`** |

### Other Changes

```diff

-83.0.0.0.0
+84.0.0.0.0

-  Functions: 8523
-  Symbols:   10284
-  CStrings:  19850
+  Functions: 8524
+  Symbols:   10288
+  CStrings:  19855
Symbols:
+ __ZN4llvm3sys2fs14setPermissionsERKNS_5TwineENS1_5permsE
+ _chmod
+ _geteuid
+ _getpwuid_r
Functions:
~ __ZN4llvm6detail18UniqueFunctionBaseINS_8ExpectedINSt3__110unique_ptrINS_7jitlink20JITLinkMemoryManagerENS3_14default_deleteIS6_EEEEEEJRNS_3orc15SimpleRemoteEPCEEE8CallImplIZN5xojit12createXPCEPCEP17_xpc_connection_sjNS4_INSB_14TaskDispatcherENS7_ISJ_EEEEE3$_0EESA_PvSD_ : 2252 -> 3900
+ __ZN4llvm3sys2fs14setPermissionsERKNS_5TwineENS1_5permsE
CStrings:
+ "\", who will need to log in and run a preview to reset the permissions"
+ "). This directory is owned by user \""
+ "Could not reset permissions on oop-jit code file directory "
+ "Failed to set 0777 permissions on %{public}s: %{public}s"
+ "Failed to stat %{public}s: %{public}s"
```
