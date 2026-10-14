## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10bd1c` | `0x10eb04` | **`+0x2de8`** |
| `__DATA.__bss` | `0x1b40` | `0x1f70` | **`+0x430`** |
| `__TEXT.__const` | `0x2334` | `0x2574` | **`+0x240`** |
| `__AUTH_CONST.__objc_const` | `0x2dca0` | `0x2de00` | **`+0x160`** |
| `__AUTH_CONST.__const` | `0x1eb0` | `0x1fd8` | **`+0x128`** |
| `__TEXT.__gcc_except_tab` | `0x23308` | `0x23420` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x83f8` | `0x84e0` | **`+0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0x424` | `0x504` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0xd18` | `0xdc0` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x11104` | `0x11194` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x1070` | `0x10e8` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x388` | `0x3f8` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0xdb40` | `0xdba0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ad8` | `0x7b30` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0xa9e` | `0xaf6` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x3670` | `0x36c0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x8b61` | `0x8bb1` | **`+0x50`** |
| `__DATA.__data` | `0x1c48` | `0x1c88` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x824` | `0x864` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xee0` | `0xf10` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0xa4` | `0xc4` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x378` | `0x390` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x17f4` | `0x1804` | **`+0x10`** |
| `__TEXT.__ustring` | `0x3f6` | `0x406` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2820` | `0x2828` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8d0` | `0x8d8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc0` | `0xc8` | **`+0x8`** |

### Other Changes

```diff

-316.0.0.0.0
+317.0.0.0.0

-  Functions: 6852
-  Symbols:   11697
-  CStrings:  2313
+  Functions: 6926
+  Symbols:   11731
+  CStrings:  2317
Symbols:
+ +[LPMIMETypeRegistry isHomeAccessoryInfoUTI:]
+ -[LPFileMetadata(Transformers) _isAccessoryInfo]
+ -[LPHomeAccessoryInfo .cxx_destruct]
+ -[LPHomeAccessoryInfo contentLine1]
+ -[LPHomeAccessoryInfo contentLine2]
+ -[LPHomeAccessoryInfo iconSymbolName]
+ -[LPHomeAccessoryInfo setContentLine1:]
+ -[LPHomeAccessoryInfo setContentLine2:]
+ -[LPHomeAccessoryInfo setIconSymbolName:]
+ -[LPHomeAccessoryInfo setTitleString:]
+ -[LPHomeAccessoryInfo titleString]
+ _OBJC_CLASS_$_LPHomeAccessoryInfo
+ _OBJC_IVAR_$_LPHomeAccessoryInfo._contentLine1
+ _OBJC_IVAR_$_LPHomeAccessoryInfo._contentLine2
+ _OBJC_IVAR_$_LPHomeAccessoryInfo._iconSymbolName
+ _OBJC_IVAR_$_LPHomeAccessoryInfo._titleString
+ _OBJC_METACLASS_$_LPHomeAccessoryInfo
+ __OBJC_$_INSTANCE_METHODS_LPHomeAccessoryInfo(Swift)
+ __OBJC_$_INSTANCE_VARIABLES_LPHomeAccessoryInfo
+ __OBJC_$_PROP_LIST_LPHomeAccessoryInfo
+ __OBJC_CLASS_RO_$_LPHomeAccessoryInfo
+ __OBJC_METACLASS_RO_$_LPHomeAccessoryInfo
+ ___block_descriptor_49_ea8_32s40s_e15_"NSString"8?0ls32l8s40l8
+ ___swift_memcpy120_8
+ ___swift_memcpy1_1
+ _associated conformance 16LinkPresentation29ShareableAccessorySupportInfoV10CodingKeys028_6FD2513438649C6B6A07B53E0A6N3BA9LLOSHAASQ
+ _associated conformance 16LinkPresentation29ShareableAccessorySupportInfoV10CodingKeys028_6FD2513438649C6B6A07B53E0A6N3BA9LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 16LinkPresentation29ShareableAccessorySupportInfoV10CodingKeys028_6FD2513438649C6B6A07B53E0A6N3BA9LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _symbolic SaySSG
+ _symbolic _____ 16LinkPresentation29ShareableAccessorySupportInfoV
+ _symbolic _____ 16LinkPresentation29ShareableAccessorySupportInfoV10CodingKeys028_6FD2513438649C6B6A07B53E0A6N3BA9LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 16LinkPresentation29ShareableAccessorySupportInfoV10CodingKeys028_6FD2513438649C6B6A07B53E0A6Q3BA9LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 16LinkPresentation29ShareableAccessorySupportInfoV10CodingKeys028_6FD2513438649C6B6A07B53E0A6Q3BA9LLO
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _type_layout_string 16LinkPresentation29ShareableAccessorySupportInfoV
- ___block_descriptor_41_ea8_32s_e15_"NSString"8?0ls32l8
CStrings:
+ "HomeKitAccessoryFile"
+ "com.apple.home.accessoryinfo"
+ "homeHubSoftwareVersion"
+ "\uf8ff\u202fmusic"
+ "\uf8ff\u202fmusic Classical"
- "\uf8ff\u202fMusic Classical"
```
