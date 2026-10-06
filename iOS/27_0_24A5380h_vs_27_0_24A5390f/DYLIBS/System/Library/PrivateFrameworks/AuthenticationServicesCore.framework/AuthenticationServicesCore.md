## AuthenticationServicesCore

> `/System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/AuthenticationServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc8508` | `0xc8a6c` | **`+0x564`** |
| `__TEXT.__oslogstring` | `0x40c0` | `0x4150` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x2060` | `0x20c0` | **`+0x60`** |
| `__DATA.__data` | `0x25a0` | `0x2600` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3cd1` | `0x3d11` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3b4c` | `0x3b7c` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x7ea0` | `0x7ec0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ea8` | `0x1ec0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3538` | `0x3548` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x13f8` | `0x1400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8e0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x180` | `0x188` | **`+0x8`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 4997
-  Symbols:   3394
-  CStrings:  786
+  Functions: 5002
+  Symbols:   3405
+  CStrings:  791
Symbols:
+ -[ASCAgent _credentialRequestedForCABLELoginChoice:completionHandler:]
+ -[ASCAgent getSafariPasswordAutoFillSettingWithCompletionHandler:]
+ -[ASCAgentProxy getSafariPasswordAutoFillSettingWithCompletionHandler:]
+ GCC_except_table131
+ GCC_except_table175
+ GCC_except_table178
+ GCC_except_table61
+ GCC_except_table76
+ _WBSOSLogAutoFill
+ _WBSWebExtensionPointIdentifier
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ASCSafariSettingsHelperProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ASCSafariSettingsHelperProtocol
+ __OBJC_$_PROTOCOL_REFS_ASCSafariSettingsHelperProtocol
+ __OBJC_LABEL_PROTOCOL_$_ASCSafariSettingsHelperProtocol
+ __OBJC_PROTOCOL_$_ASCSafariSettingsHelperProtocol
+ ___70-[ASCAgent _credentialRequestedForCABLELoginChoice:completionHandler:]_block_invoke
+ ___70-[ASCAgent _credentialRequestedForCABLELoginChoice:completionHandler:]_block_invoke_2
+ ___71-[ASCAgentProxy getSafariPasswordAutoFillSettingWithCompletionHandler:]_block_invoke
+ ___71-[ASCAgentProxy getSafariPasswordAutoFillSettingWithCompletionHandler:]_block_invoke_2
- -[ASCAgent _credentialRequestedForCABLELoginChoice:]
- GCC_except_table130
- GCC_except_table174
- GCC_except_table177
- GCC_except_table60
- GCC_except_table72
- ___52-[ASCAgent _credentialRequestedForCABLELoginChoice:]_block_invoke
- ___52-[ASCAgent _credentialRequestedForCABLELoginChoice:]_block_invoke_2
CStrings:
+ "AutoFillPasswordsInSafari"
+ "Client process is not allowed to read Safari AutoFill settings"
+ "Failed to get extension record for application identifier with error: %{public}@"
+ "NSExtension"
+ "NSExtensionPointIdentifier"
```
