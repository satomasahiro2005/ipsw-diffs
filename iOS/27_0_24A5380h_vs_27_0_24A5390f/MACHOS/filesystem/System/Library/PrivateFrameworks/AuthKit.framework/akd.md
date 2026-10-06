## akd

> `/System/Library/PrivateFrameworks/AuthKit.framework/akd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31ea0c` | `0x31f164` | **`+0x758`** |
| `__DATA.__objc_const` | `0x309d0` | `0x30d38` | **`+0x368`** |
| `__TEXT.__objc_methname` | `0x291f5` | `0x292a5` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x1d640` | `0x1d6c0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xcfc4` | `0xd02c` | **`+0x68`** |
| `__DATA.__data` | `0x5cc0` | `0x5d20` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x8341` | `0x8381` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x88e8` | `0x8918` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x3042` | `0x3062` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8b10` | `0x8b20` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x468` | `0x470` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__dlopen_cstrs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-554.0.0.0.0
+555.0.0.0.0

-  Functions: 10519
+  Functions: 10526

-  CStrings:  11433
+  CStrings:  11442
CStrings:
+ "@\"<AKAuthenticationSettingsLauncherProtocol>\""
+ "AKAuthenticationSettingsLauncherProtocol"
+ "B32@0:8@\"AKAppleIDAuthenticationContext\"16@\"NSUUID\"24"
+ "T@\"<AKAuthenticationSettingsLauncherProtocol>\",&,N,V_settingsLauncher"
+ "T@\"AKAuthenticationSurrogateManager\",&,N"
+ "_addPendingRequest:"
+ "_removePendingRequest:"
+ "clientForConnection:"
+ "setSettingsLauncher:"
+ "setXpcConnection:"
+ "settingsLauncher"
- "@\"AKAuthenticationSettingsLauncher\""
- "T@\"AKAuthenticationSurrogateManager\",R,N"
```
