## libcryptex_interface.dylib

> `/usr/lib/libcryptex_interface.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7438` | `0x752c` | **`+0xf4`** |
| `__TEXT.__cstring` | `0xc5b` | `0xc71` | **`+0x16`** |
| `__DATA_CONST.__got` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x278` | `0x280` | **`+0x8`** |

### Other Changes

```diff

-746.0.0.0.0
+757.0.0.0.0

-  Functions: 177
-  Symbols:   390
-  CStrings:  176
+  Functions: 179
+  Symbols:   393
+  CStrings:  177
Symbols:
+ __rpc_pack_endpoint
+ __rpc_unpack_endpoint
+ __xpc_type_endpoint
Functions:
~ _codex_install_pack : 256 -> 272
~ _codex_install_unpack : 436 -> 480
~ _remote_service_create_install_request : 1292 -> 1284
~ __CFErrorGetTopLevelPosixError : 188 -> 184
~ ___42-[UpgradeInterfaceLock _handleXPCMessage:]_block_invoke : 292 -> 288
+ __rpc_pack_endpoint
+ __rpc_unpack_endpoint
CStrings:
+ "757"
+ "@(#)VERSION:Cryptex IPC Interface Version 2.0.0: Sat Jun 13 08:36:01 PDT 2026; root:libcryptex-757~412/libcryptex_interface/RELEASE_ARM64E"
+ "Cryptex IPC Interface Version 2.0.0: Sat Jun 13 08:36:01 PDT 2026; root:libcryptex-757~412/libcryptex_interface/RELEASE_ARM64E"
+ "enable-install-events"
- "746"
- "@(#)VERSION:Cryptex IPC Interface Version 2.0.0: Thu May 21 08:14:35 PDT 2026; root:libcryptex-746~413/libcryptex_interface/RELEASE_ARM64E"
- "Cryptex IPC Interface Version 2.0.0: Thu May 21 08:14:35 PDT 2026; root:libcryptex-746~413/libcryptex_interface/RELEASE_ARM64E"
```
