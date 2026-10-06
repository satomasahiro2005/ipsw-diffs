## get-network-info

> `/System/Library/Frameworks/SystemConfiguration.framework/get-network-info`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13ae4` | `0x149a8` | **`+0xec4`** |
| `__DATA.__bss` | `0xa90` | `0x790` | **`-0x300`** |
| `__TEXT.__const` | `0x810` | `0x6a2` | **`-0x16e`** |
| `__TEXT.__cstring` | `0x18d3` | `0x17b3` | **`-0x120`** |
| `__TEXT.__objc_stubs` | `0x300` | `0x220` | **`-0xe0`** |
| `__TEXT.__objc_methname` | `0x591` | `0x4d6` | **`-0xbb`** |
| `__TEXT.__auth_stubs` | `0x1080` | `0x1110` | **`+0x90`** |
| `__DATA_CONST.__const` | `0xca0` | `0xc50` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x848` | `0x890` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x160` | `0x128` | **`-0x38`** |
| `__TEXT.__eh_frame` | `0x2b0` | `0x278` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x30` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x190` | `0x168` | **`-0x28`** |
| `__TEXT.__objc_classname` | `0x113` | `0xef` | **`-0x24`** |
| `__TEXT.__swift5_fieldmd` | `0x1cc` | `0x1b0` | **`-0x1c`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x3c` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0x29d` | `0x2b2` | **`+0x15`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x14` | **`-0x14`** |
| `__TEXT.__swift5_typeref` | `0x381` | `0x36d` | **`-0x14`** |
| `__DATA.__data` | `0x840` | `0x830` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x230` | `0x220` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x278` | `0x270` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x18` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-1438.0.0.0.0
-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
+1441.0.0.0.0

-  Functions: 230
-  Symbols:   426
-  CStrings:  229
+  Functions: 217
+  Symbols:   432
+  CStrings:  218
Symbols:
+ _$s6System14FileDescriptorV9_writeAllys6ResultOySiAA5ErrnoVGxSTRzs5UInt8V7ElementRtzlF
+ _$s6System8FilePathV2eeoiySbAC_ACtFZ
+ _$s6System8FilePathVSHAAMc
+ _$s6System8FilePathVSQAAMc
+ _$sSH13_rawHashValue4seedS2i_tFTj
+ _$sSQ2eeoiySbx_xtFZTj
+ _$sSS10FoundationE4data8encodingSSSgAA4DataVh_SSAAE8EncodingVtcfC
+ _$sSS7cStringSSSPys4Int8VG_tcfC
+ _$sSS8UTF8ViewVN
+ _$sSS8UTF8ViewVSTsMc
+ _$sSo12NSFileHandleC10FoundationE9readToEndAC4DataVSgyKF
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _$ss9_typeName_9qualifiedSSypXp_SbtF
+ _copyfile
+ _strerror
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_getDynamicType
+ _swift_release_x12
+ _swift_release_x28
+ _swift_release_x9
+ _swift_retain_x8
- _$s10Foundation3URLV15fileURLWithPath10relativeToACSSh_ACSghtcfC
- _$s10Foundation3URLV15fileURLWithPathACSSh_tcfC
- _$s10Foundation3URLV19_bridgeToObjectiveCSo5NSURLCyF
- _$s10Foundation4DataVAA0B8ProtocolAAMc
- _$s10Foundation4DataVN
- _$sSS10FoundationE14contentsOfFile8encodingS2Sh_SSAAE8EncodingVtKcfC
- _$sSS10FoundationE4data5using20allowLossyConversionAA4DataVSgSSAAE8EncodingV_SbtF
- _$sSo12NSFileHandleC10FoundationE5write10contentsOfyx_tKAC12DataProtocolRzlF
- _$ss10ArraySliceVMn
- _$ss10ArraySliceVyxGSKsMc
- _$ss11CommandLineO9argumentsSaySSGvgZ
- _NSFileType
- _NSFileTypeSymbolicLink
- _OBJC_CLASS_$_NSUserDefaults
- _objc_retain_x1
- _objc_retain_x19
CStrings:
+ "_TtCC16get_network_info19GNISubprocessRunner19GNIOutputTargetFile"
+ "createdOutputPaths"
+ "initWithFileDescriptor:closeOnDealloc:"
+ "safeReadString failed for '"
- "/System/Library/Frameworks/SystemConfiguration.framework/deprecated-get-network-info"
- "ERROR: couldn't run script /System/Library/Frameworks/SystemConfiguration.framework/deprecated-get-network-info"
- "_TtCC16get_network_info19GNISubprocessRunnerP33_3186E59FE02BFB660D06ACCD2EEE6E6019GNIOutputTargetFile"
- "boolForKey:"
- "closeAndReturnError:"
- "copyItemAtURL:toURL:error:"
- "destinationOfSymbolicLinkAtPath:error:"
- "failed closing '"
- "failed creating file handle for "
- "fileHandle"
- "fileHandleForUpdatingAtPath:"
- "fileHandleForWritingAtPath:"
- "get-network-info.use-old-gni"
- "seekToEndOfFile"
- "standardUserDefaults"
```
