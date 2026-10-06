## com.apple.PrintKit.PrinterTool

> `/System/Library/PrivateFrameworks/PrintKit.framework/XPCServices/com.apple.PrintKit.PrinterTool.xpc/com.apple.PrintKit.PrinterTool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c044` | `0x5c10c` | **`+0xc8`** |
| `__TEXT.__objc_methname` | `0x6a4a` | `0x6ae1` | **`+0x97`** |
| `__DATA.__objc_const` | `0x57f8` | `0x5858` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0xeca0` | `0xece0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x6800` | `0x6840` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2e48` | `0x2e78` | **`+0x30`** |
| `__TEXT.__cstring` | `0x94be` | `0x94ec` | **`+0x2e`** |
| `__TEXT.__gcc_except_tab` | `0xaa10` | `0xaa34` | **`+0x24`** |
| `__DATA.__objc_selrefs` | `0x1e08` | `0x1e28` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x3e4` | `0x3ec` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xed60` | `0xed68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-327.0.0.0.0
+327.1.0.0.0

-  Functions: 1629
+  Functions: 1634

-  CStrings:  4131
+  CStrings:  4141
Symbols:
+ __Z16PKPromptAuthInfoP8NSStringS0_bb
+ __Z16PKPromptAuthInfoP8NSStringS0_bbU13block_pointerFvP15NSURLCredentialE
- __Z16PKPromptAuthInfoP8NSStringS0_b
- __Z16PKPromptAuthInfoP8NSStringS0_bU13block_pointerFvP15NSURLCredentialE
CStrings:
+ "PK_LEVEL_AUTHENTICATION_CHECKACCESS"
+ "Password"
+ "T@\"NSString\",&,V_msgWhence"
+ "T@?,C,V_credentialCallback"
+ "User Name"
+ "User name placeholder text"
+ "_credentialCallback"
+ "_msgWhence"
+ "credentialCallback"
+ "msgWhence"
+ "setCredentialCallback:"
+ "setMsgWhence:"
- "Username placeholder text"
- "user name"
```
