## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143f5c` | `0x14376c` | **`-0x7f0`** |
| `__AUTH_CONST.__objc_const` | `0x10390` | `0x10130` | **`-0x260`** |
| `__TEXT.__objc_methlist` | `0x813c` | `0x8074` | **`-0xc8`** |
| `__DATA.__data` | `0x39a0` | `0x38e0` | **`-0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x12c0` | `0x1204` | **`-0xbc`** |
| `__AUTH.__objc_data` | `0x3ac8` | `0x3a28` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x1a60` | `0x19c8` | **`-0x98`** |
| `__TEXT.__cstring` | `0xb5d8` | `0xb558` | **`-0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d18` | `0x4ca0` | **`-0x78`** |
| `__TEXT.__unwind_info` | `0x5db0` | `0x5d40` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x45c0` | `0x4560` | **`-0x60`** |
| `__TEXT.__eh_frame` | `0x6edc` | `0x6eac` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x9bf8` | `0x9bd8` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x16d0` | `0x16b8` | **`-0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0xc0` | `0xd8` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x22cc` | `0x22b4` | **`-0x18`** |
| `__AUTH.__data` | `0x18d0` | `0x18c0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x10b0` | `0x10a0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x5b0` | `0x5a0` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x2d8` | `0x2c8` | **`-0x10`** |
| `__TEXT.__const` | `0x13f74` | `0x13f64` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x704` | `0x6fc` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x360` | `0x358` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x508` | `0x500` | **`-0x8`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 8210
-  Symbols:   6575
-  CStrings:  1354
+  Functions: 8193
+  Symbols:   6515
+  CStrings:  1350
Symbols:
+ -[_ASWebsiteNameProvider _initWithShouldLoadQuirksDatabase:]
+ -[_ASWebsiteNameProvider test_waitUntilBuiltInWebsiteNamesAreLoaded]
+ GCC_except_table22
+ GCC_except_table23
+ GCC_except_table28
+ GCC_except_table31
+ GCC_except_table48
+ GCC_except_table49
+ GCC_except_table51
+ GCC_except_table55
+ GCC_except_table58
+ GCC_except_table61
+ _OBJC_IVAR_$__ASAgentCredentialUpdateListenerProxy._connectionLock
+ __CLASS_METHODS_ASPasswordSavingManager
+ ___60-[_ASWebsiteNameProvider _initWithShouldLoadQuirksDatabase:]_block_invoke
+ ___60-[_ASWebsiteNameProvider _initWithShouldLoadQuirksDatabase:]_block_invoke_2
+ ___68-[_ASWebsiteNameProvider test_waitUntilBuiltInWebsiteNamesAreLoaded]_block_invoke
- +[_ASWebsiteNameDictionary sanitizedDataFromDeserializedData:]
- -[_ASWebsiteNameDictionary .cxx_destruct]
- -[_ASWebsiteNameDictionary description]
- -[_ASWebsiteNameDictionary initWithSnapshotData:error:]
- -[_ASWebsiteNameDictionary snapshotData]
- -[_ASWebsiteNameDictionary websiteNameForDomain:]
- -[_ASWebsiteNameDictionarySnapshotTransformer objectFromData:]
- -[_ASWebsiteNameProvider _initWithShouldLoadQuirksList:]
- -[_ASWebsiteNameProvider beginLoadingBuiltInAndRemotelyUpdatableWebsiteNames]
- -[_ASWebsiteNameProvider prepareForTermination]
- -[_ASWebsiteNameProvider test_initWithWebsiteNameDictionary:]
- -[_ASWebsiteNameProvider test_waitUntilBuiltInAndRemotelyUpdatableWebsiteNamesAreLoaded]
- GCC_except_table1
- GCC_except_table37
- GCC_except_table40
- GCC_except_table41
- GCC_except_table43
- GCC_except_table44
- GCC_except_table46
- GCC_except_table47
- GCC_except_table64
- GCC_except_table65
- GCC_except_table66
- GCC_except_table68
- GCC_except_table73
- GCC_except_table74
- GCC_except_table76
- GCC_except_table78
- GCC_except_table85
- GCC_except_table86
- GCC_except_table87
- _OBJC_CLASS_$_NSFileManager
- _OBJC_CLASS_$_WBSConfigurationDataTransformer
- _OBJC_CLASS_$_WBSRemotelyUpdatableDataController
- _OBJC_CLASS_$__ASWebsiteNameDictionary
- _OBJC_CLASS_$__ASWebsiteNameDictionarySnapshotTransformer
- _OBJC_IVAR_$__ASWebsiteNameDictionary._websiteNameDictionary
- _OBJC_IVAR_$__ASWebsiteNameProvider._remotelyUpdatableDataController
- _OBJC_IVAR_$__ASWebsiteNameProvider._websiteNameDictionary
- _OBJC_METACLASS_$_WBSConfigurationDataTransformer
- _OBJC_METACLASS_$__ASWebsiteNameDictionary
- _OBJC_METACLASS_$__ASWebsiteNameDictionarySnapshotTransformer
- __OBJC_$_CLASS_METHODS__ASWebsiteNameDictionary
- __OBJC_$_INSTANCE_METHODS__ASWebsiteNameDictionary
- __OBJC_$_INSTANCE_METHODS__ASWebsiteNameDictionarySnapshotTransformer
- __OBJC_$_INSTANCE_VARIABLES__ASWebsiteNameDictionary
- __OBJC_$_PROP_LIST__ASWebsiteNameDictionary
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WBSRemotelyUpdatableDataControllerDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_WBSRemotelyUpdatableDataSnapshot
- __OBJC_$_PROTOCOL_METHOD_TYPES_WBSRemotelyUpdatableDataControllerDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_WBSRemotelyUpdatableDataSnapshot
- __OBJC_$_PROTOCOL_REFS_WBSRemotelyUpdatableDataControllerDelegate
- __OBJC_$_PROTOCOL_REFS_WBSRemotelyUpdatableDataSnapshot
- __OBJC_CLASS_PROTOCOLS_$__ASWebsiteNameDictionary
- __OBJC_CLASS_RO_$__ASWebsiteNameDictionary
- __OBJC_CLASS_RO_$__ASWebsiteNameDictionarySnapshotTransformer
- __OBJC_LABEL_PROTOCOL_$_WBSRemotelyUpdatableDataControllerDelegate
- __OBJC_LABEL_PROTOCOL_$_WBSRemotelyUpdatableDataSnapshot
- __OBJC_METACLASS_RO_$__ASWebsiteNameDictionary
- __OBJC_METACLASS_RO_$__ASWebsiteNameDictionarySnapshotTransformer
- __OBJC_PROTOCOL_$_WBSRemotelyUpdatableDataControllerDelegate
- __OBJC_PROTOCOL_$_WBSRemotelyUpdatableDataSnapshot
- __ZSt9terminatev
- ___56-[_ASWebsiteNameProvider _initWithShouldLoadQuirksList:]_block_invoke
- ___56-[_ASWebsiteNameProvider _initWithShouldLoadQuirksList:]_block_invoke_2
- ___62+[_ASWebsiteNameDictionary sanitizedDataFromDeserializedData:]_block_invoke
- ___77-[_ASWebsiteNameProvider beginLoadingBuiltInAndRemotelyUpdatableWebsiteNames]_block_invoke
- ___77-[_ASWebsiteNameProvider beginLoadingBuiltInAndRemotelyUpdatableWebsiteNames]_block_invoke_2
- ___88-[_ASWebsiteNameProvider test_waitUntilBuiltInAndRemotelyUpdatableWebsiteNamesAreLoaded]_block_invoke
- ___88-[_ASWebsiteNameProvider test_waitUntilBuiltInAndRemotelyUpdatableWebsiteNamesAreLoaded]_block_invoke_2
- ___block_descriptor_32_e34_v16?0"_ASWebsiteNameDictionary"8l
- ___block_descriptor_40_ea8_32r_e15_v32?0816^B24lr32l8
- ___block_descriptor_40_ea8_32s_e34_v16?0"_ASWebsiteNameDictionary"8ls32l8
- ___block_descriptor_48_ea8_32s40s_e5_v8?0ls32l8s40l8
- ___clang_call_terminate
- ___cxa_begin_catch
- _swift_retain_x1
CStrings:
- "<%@: %p; count(websiteNameDictionary) = %zu>"
- "WebsiteNameProviderLastUpdateTime"
- "v16@?0@\"_ASWebsiteNameDictionary\"8"
- "v32@?0@8@16^B24"
```
