## LinkMetadata

> `/System/Library/PrivateFrameworks/LinkMetadata.framework/LinkMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13d514` | `0x13d7c8` | **`+0x2b4`** |
| `__AUTH_CONST.__objc_const` | `0x106c8` | `0x107e0` | **`+0x118`** |
| `__AUTH.__data` | `0xb50` | `0xbf8` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0xc670` | `0xc718` | **`+0xa8`** |
| `__TEXT.__const` | `0x13154` | `0x131d4` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x3164` | `0x31d4` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x44e0` | `0x4548` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x50fc` | `0x5154` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x619c` | `0x6154` | **`-0x48`** |
| `__TEXT.__cstring` | `0xbbf6` | `0xbc3c` | **`+0x46`** |
| `__DATA.__data` | `0x4120` | `0x4150` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x2dd8` | `0x2e00` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x8ae4` | `0x8b0c` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x1ea9` | `0x1ed0` | **`+0x27`** |
| `__AUTH_CONST.__cfstring` | `0x6a60` | `0x6a80` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x2770` | `0x2790` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5e00` | `0x5e20` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xe98` | `0xeb0` | **`+0x18`** |
| `__DATA.__bss` | `0x1dc90` | `0x1dca0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe28` | `0xe38` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x540` | `0x548` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4f4` | `0x4fc` | **`+0x8`** |

### Other Changes

```diff

-301.0.45.4.101
+301.0.51.1.102

-  Functions: 10062
-  Symbols:   9146
-  CStrings:  1583
+  Functions: 10087
+  Symbols:   9162
+  CStrings:  1585
Symbols:
+ +[LNSystemProtocol callingProtocol]
+ -[LNActionMetadata(Private_Testing) metadataByReplacingEffectiveBundleIdentifiers:]
+ GCC_except_table2422
+ GCC_except_table2423
+ GCC_except_table2464
+ GCC_except_table2805
+ GCC_except_table2837
+ _LNSystemProtocolIdentifierCalling
+ _OBJC_CLASS_$_NSMapTable
+ __DATA__TtC12LinkMetadata19UniqueBundleHashMap
+ __IVARS__TtC12LinkMetadata19UniqueBundleHashMap
+ __METACLASS_DATA__TtC12LinkMetadata19UniqueBundleHashMap
+ __OBJC_$_INSTANCE_METHODS_LNActionMetadata(Private_Testing|Deprecated|Private_Deprecated)
+ ___35+[LNSystemProtocol callingProtocol]_block_invoke
+ _callingProtocol.onceToken
+ _callingProtocol.value
+ _symbolic So14LSBundleRecordCSg
+ _symbolic _____ 12LinkMetadata19UniqueBundleHashMapC
+ _symbolic _____ 12LinkMetadata29LNBundleValidationInformationC10BundleInfoV
+ _symbolic _____Sg 12LinkMetadata29LNBundleValidationInformationC10BundleInfoV
+ _symbolic _____ySo10NSMapTableCySo5NSURLCSo8NSBundleCGG 15Synchronization5MutexVAARi_zrlE
+ _type_layout_string 12LinkMetadata29LNBundleValidationInformationC10BundleInfoV
- GCC_except_table2420
- GCC_except_table2421
- GCC_except_table2462
- GCC_except_table2803
- GCC_except_table2835
- __OBJC_$_INSTANCE_METHODS_LNActionMetadata(Private_Testing|Private_Testing|Deprecated|Private_Deprecated)
CStrings:
+ "AppIntents._CallingIntent"
+ "LinkProgrammaticInterface-301.0.51.1.102"
+ "com.apple.link.systemProtocol.Calling"
- "LinkProgrammaticInterface-301.0.45.4.101"
```
