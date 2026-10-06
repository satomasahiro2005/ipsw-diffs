## AppleNeuralEngine

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54de8` | `0x569b4` | **`+0x1bcc`** |
| `__TEXT.__oslogstring` | `0xb3d8` | `0xb6c8` | **`+0x2f0`** |
| `__AUTH.__objc_data` | `0x230` | `0x4b0` | **`+0x280`** |
| `__DATA_DIRTY.__objc_data` | `0x9b0` | `0x730` | **`-0x280`** |
| `__TEXT.__gcc_except_tab` | `0x6570` | `0x676c` | **`+0x1fc`** |
| `__AUTH_CONST.__cfstring` | `0x48a0` | `0x4a60` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x36ee` | `0x387b` | **`+0x18d`** |
| `__TEXT.__objc_methlist` | `0x2b0c` | `0x2b8c` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x908` | `0x978` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x3c70` | `0x3cd0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x19d0` | `0x1a18` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x13d0` | `0x1410` | **`+0x40`** |
| `__DATA.__data` | `0x6e8` | `0x710` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x658` | `0x678` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x234` | `0x23c` | **`+0x8`** |

### Other Changes

```diff

-382.9.0.0.0
+382.11.0.0.0

-  Functions: 1698
-  Symbols:   2223
-  CStrings:  1390
+  Functions: 1718
+  Symbols:   2250
+  CStrings:  1421
Symbols:
+ +[_ANECloneHelper bundleContainsSymlinkAtPath:]
+ +[_ANEHashEncoding _hexStringByFeeding:]
+ +[_ANEHashEncoding hexStringForFileAtPath:]
+ +[_ANEHashEncoding verifyBundleAtPath:expectedHashes:error:]
+ +[_ANESandboxingHelper issueSandboxExtensionForWeights:]
+ +[_ANEStrings largeModelCompilerServiceAccessEntitlement]
+ +[_ANEStrings largeModelCompilerServiceBundleID]
+ -[_ANEInMemoryModel perFileHashes]
+ -[_ANEInMemoryModel setPerFileHashes:]
+ -[_ANEInMemoryModelDescriptor perFileHashes]
+ _OBJC_IVAR_$__ANEInMemoryModel._perFileHashes
+ _OBJC_IVAR_$__ANEInMemoryModelDescriptor._perFileHashes
+ ___42+[_ANEHashEncoding hexStringForDataArray:]_block_invoke
+ ___43+[_ANEHashEncoding hexStringForFileAtPath:]_block_invoke
+ ___45+[_ANEHashEncoding hexStringForBytes:length:]_block_invoke
+ ___block_descriptor_40_e8_32s_e41_B16?0^{CC_SHA256state_st=[2I][8I][16I]}8ls32l8
+ ___block_descriptor_44_e8_32s_e41_B16?0^{CC_SHA256state_st=[2I][8I][16I]}8ls32l8
+ ___block_descriptor_48_e41_B16?0^{CC_SHA256state_st=[2I][8I][16I]}8l
+ _close
+ _kANEFCompilerServiceBundleIdentifierKey
+ _kANEFCompilerServiceRUsageAfterKey
+ _kANEFCompilerServiceRUsageBeforeKey
+ _kANEFInMemoryModelFileHashesKey
+ _kANEFInMemoryModelFileNamesKey
+ _lstat
+ _open
+ _read
CStrings:
+ "%@: BEGIN errorIOSurfaceRef=%p errorLength=%llu"
+ "%@: baseAddress=%p IOSurfaceAllocSize=%zu"
+ "%@: bundle entry %@ is a symbolic link; refusing"
+ "%@: contentsOfDirectoryAtPath(%@) failed: %@"
+ "%@: dataOut.success=%d errorDataSize=%llu programHandle=%llu"
+ "%@: decoded errorDescription=%@"
+ "%@: errorData=%p length=%lu"
+ "%@: hostError=%@ (deserialized from %lu bytes)"
+ "%@: input data length=%lu"
+ "%@: loadModelNewInstance FAILED on host: errorDataSize=%llu errorIOSurfaceRef=%p errorIOSID=%u"
+ "%@: lstat(%@) failed errno=%d"
+ "%@: open(%@) failed errno=%d"
+ "%@: refusing model bundle containing a symbolic link: %@"
+ "B16@?0^{CC_SHA256state_st=[2I][8I][16I]}8"
+ "FileConstants"
+ "Path"
+ "_SBExtension"
+ "assetFileName"
+ "assetTransferUUID"
+ "com.apple.ANELargeModelCompilerService"
+ "com.apple.ANELargeModelCompilerService.allow"
+ "hexStringForFileAtPath: read(%@) failed errno=%d"
+ "kANEFCompilerServiceBundleIdentifierKey"
+ "kANEFCompilerServiceRUsageAfterKey"
+ "kANEFCompilerServiceRUsageBeforeKey"
+ "kANEFInMemoryModelFileHashesKey"
+ "kANEFInMemoryModelFileNamesKey"
+ "modelFilePath"
+ "verifyBundleAtPath"
+ "verifyBundleAtPath: %@ missing or not a directory"
+ "verifyBundleAtPath: hash mismatch for %@ in bundle %@ (TOCTOU?)"
```
