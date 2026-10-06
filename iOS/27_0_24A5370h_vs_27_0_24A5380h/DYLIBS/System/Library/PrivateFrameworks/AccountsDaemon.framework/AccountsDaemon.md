## AccountsDaemon

> `/System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x98` | `0x368` | **`+0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x12a0` | `0xfd0` | **`-0x2d0`** |
| `__TEXT.__text` | `0x83554` | `0x83788` | **`+0x234`** |
| `__TEXT.__unwind_info` | `0x1ee0` | `0x1f10` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x24d8` | `0x2504` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x1750` | `0x1778` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x4b98` | `0x4bb8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3da3` | `0x3dc3` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xcd0` | `0xcc0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xd80` | `0xd90` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2c4` | `0x2c8` | **`+0x4`** |

### Other Changes

```diff

-1118.0.0.0.0
+1119.0.0.0.0

-  Functions: 2423
-  Symbols:   3213
-  CStrings:  1185
+  Functions: 2424
+  Symbols:   3215
+  CStrings:  1186
Symbols:
+ GCC_except_table212
+ GCC_except_table233
+ GCC_except_table235
+ _OBJC_IVAR_$_ACDAccountStore._fakeRemoteAccountStoreSessionLock
+ ___44-[ACDAccountStore remoteAccountStoreSession]_block_invoke
+ ___block_descriptor_40_e8_32s_e34_"ACRemoteAccountStoreSession"8?0ls32l8
+ _swift_retain_x8
- GCC_except_table232
- GCC_except_table234
- _swift_retain_x22
- _swift_retain_x28
- _swift_willThrowTypedImpl
CStrings:
+ "@\"ACRemoteAccountStoreSession\"8@?0"
```
