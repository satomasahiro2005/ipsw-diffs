## libcryptex.dylib

> `/usr/lib/libcryptex.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x250d4` | `0x25c60` | **`+0xb8c`** |
| `__TEXT.__oslogstring` | `0x40f0` | `0x425a` | **`+0x16a`** |
| `__DATA_CONST.__const` | `0x768` | `0x818` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0xc38` | `0xcd4` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x1f58` | `0x1fec` | **`+0x94`** |
| `__TEXT.__const` | `0x7b8` | `0x828` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x140` | `0x1a0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xe18` | `0xe78` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x9f8` | `0xa28` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x180` | `0x160` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x490` | `0x4b0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5f0` | `0x600` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x6c` | `0x74` | **`+0x8`** |

### Other Changes

```diff

-746.0.0.0.0
+757.0.0.0.0

-  Functions: 505
-  Symbols:   986
-  CStrings:  647
+  Functions: 512
+  Symbols:   1006
+  CStrings:  663
Symbols:
+ -[CryptexRemoteService event_queue]
+ -[CryptexRemoteService installEventHandler]
+ -[CryptexRemoteService setInstallEventHandler:]
+ GCC_except_table14
+ GCC_except_table44
+ GCC_except_table55
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table61
+ GCC_except_table69
+ GCC_except_table70
+ GCC_except_table71
+ _OBJC_IVAR_$_CryptexRemoteService._event_queue
+ _OBJC_IVAR_$_CryptexRemoteService._installEventHandler
+ ___cryptex_attr_set_install_event_handler_block_invoke
+ ___cryptex_install2_block_invoke
+ __codex_list_fingerprint
+ __cryptex_attr_get_install_event_handler
+ _cryptex_attr_set_install_event_handler
+ _kCryptexEventInfoFingerprint
+ _kCryptexEventInfoMountpoint
+ _kCryptexEventInfoSubMountDevice
+ _objc_retain_x28
+ _xpc_listener_cancel
+ _xpc_listener_create_anonymous
+ _xpc_listener_create_endpoint
+ _xpc_rich_error_copy_description
+ _xpc_session_activate
+ _xpc_session_set_incoming_message_handler
- GCC_except_table41
- GCC_except_table52
- GCC_except_table54
- GCC_except_table56
- GCC_except_table58
- GCC_except_table60
- GCC_except_table64
- GCC_except_table65
- _objc_retain_x27
CStrings:
+ "%{public}s: Failed to activate install event session: %s:"
+ "%{public}s: Got event mid-install: %llu"
+ "%{public}s: Install event handler got connection"
+ "%{public}s: Install event handler got event: %s"
+ "757"
+ "@(#)VERSION:Darwin Cryptex Interface Version 2.0.0: Sat Jun 13 08:36:15 PDT 2026; root:libcryptex-757~412/libcryptex/RELEASE_ARM64E"
+ "Calling client's install event handler"
+ "Client has no install event handler"
+ "Darwin Cryptex Interface Version 2.0.0: Sat Jun 13 08:36:15 PDT 2026; root:libcryptex-757~412/libcryptex/RELEASE_ARM64E"
+ "Fingerprint"
+ "Install event from device: %llu"
+ "InstallEvents"
+ "Mountpoint"
+ "Peer device does not support device-is-locked notifications"
+ "SubMountDevice"
+ "com.apple.security.libcryptex.remote_service_event"
+ "v16@?0Q8"
+ "v16@?0^v8"
+ "v16@?0^{xpc_session_s=}8"
- "746"
- "@(#)VERSION:Darwin Cryptex Interface Version 2.0.0: Thu May 21 08:14:53 PDT 2026; root:libcryptex-746~413/libcryptex/RELEASE_ARM64E"
- "Darwin Cryptex Interface Version 2.0.0: Thu May 21 08:14:53 PDT 2026; root:libcryptex-746~413/libcryptex/RELEASE_ARM64E"
```
