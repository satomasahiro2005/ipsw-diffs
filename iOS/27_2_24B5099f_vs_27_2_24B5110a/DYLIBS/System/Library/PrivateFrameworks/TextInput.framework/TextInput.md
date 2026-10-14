## TextInput

> `/System/Library/PrivateFrameworks/TextInput.framework/TextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80bf0` | `0x80f54` | **`+0x364`** |
| `__AUTH_CONST.__objc_const` | `0x11c60` | `0x11dd0` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0xb680` | `0xb700` | **`+0x80`** |
| `__DATA.__data` | `0xc90` | `0xcf0` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x2670` | `0x26c0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x495be` | `0x495ef` | **`+0x31`** |
| `__AUTH_CONST.__cfstring` | `0x255dc0` | `0x255de0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xd80` | `0xda0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x56c8` | `0x56e0` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x20c0` | `0x20d0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x400` | `0x408` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb7c` | `0xb80` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 4015
-  Symbols:   7666
-  CStrings:  76812
+  Functions: 4023
+  Symbols:   7691
+  CStrings:  76813
Symbols:
+ +[TIPreferencesController _appIntentPreferencesKeys]
+ -[TIUserDirectoryTraderClient .cxx_destruct]
+ -[TIUserDirectoryTraderClient connection]
+ -[TIUserDirectoryTraderClient exportUserDirectoryWithCompletionHandler:]
+ -[TIUserDirectoryTraderClient importUserDirectory:personaID:completionHandler:]
+ -[TIUserDirectoryTraderClient init]
+ -[TIUserDirectoryTraderClient setConnection:]
+ _OBJC_CLASS_$_TIUserDirectoryTraderClient
+ _OBJC_IVAR_$_TIUserDirectoryTraderClient._connection
+ _OBJC_METACLASS_$_TIUserDirectoryTraderClient
+ __OBJC_$_INSTANCE_METHODS_TIUserDirectoryTraderClient
+ __OBJC_$_INSTANCE_VARIABLES_TIUserDirectoryTraderClient
+ __OBJC_$_PROP_LIST_TIUserDirectoryTraderClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TIUserDirectoryTraderProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TIUserDirectoryTraderProtocol
+ __OBJC_$_PROTOCOL_REFS_TIUserDirectoryTraderProtocol
+ __OBJC_CLASS_PROTOCOLS_$_TIUserDirectoryTraderClient
+ __OBJC_CLASS_RO_$_TIUserDirectoryTraderClient
+ __OBJC_LABEL_PROTOCOL_$_TIUserDirectoryTraderProtocol
+ __OBJC_METACLASS_RO_$_TIUserDirectoryTraderClient
+ __OBJC_PROTOCOL_$_TIUserDirectoryTraderProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_TIUserDirectoryTraderProtocol
+ ___52+[TIPreferencesController _appIntentPreferencesKeys]_block_invoke
+ __appIntentPreferencesKeys.__appIntentPreferencesKeys
+ __appIntentPreferencesKeys.__onceToken
CStrings:
+ "com.apple.TextInput.user-directory-trader-server"
```
