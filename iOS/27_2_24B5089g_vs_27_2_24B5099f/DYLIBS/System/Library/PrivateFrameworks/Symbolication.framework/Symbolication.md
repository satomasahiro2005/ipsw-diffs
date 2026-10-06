## Symbolication

> `/System/Library/PrivateFrameworks/Symbolication.framework/Symbolication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0xd18` | `0x80` | **`-0xc98`** |
| `__DATA_DIRTY.__data` | `0x50` | `0xce8` | **`+0xc98`** |
| `__AUTH.__objc_data` | `0x680` | `—` | **`-0x680`** |
| `__DATA_DIRTY.__objc_data` | `0x17c0` | `0x1e40` | **`+0x680`** |
| `__TEXT.__text` | `0xbc2cc` | `0xbc834` | **`+0x568`** |
| `__TEXT.__cstring` | `0x11308` | `0x113f8` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0xdbc0` | `0xdc20` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xcc20` | `0xcc80` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x6a00` | `0x6a38` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x39f0` | `0x3a10` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5990` | `0x59a8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xdac` | `0xdb4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2dc0` | `0x2dc8` | **`+0x8`** |

### Other Changes

```diff

-64578.100.1.0.0
+64578.132.1.0.0

-  Functions: 3381
-  Symbols:   6147
-  CStrings:  2907
+  Functions: 3387
+  Symbols:   6156
+  CStrings:  2912
Symbols:
+ -[VMUObjectIdentifier libswiftCoreSymbolOwner]
+ -[VMUTask isSimulator]
+ -[VMUTaskMemoryScanner _attemptIdentifySwiftMetadataBlocks]
+ -[VMUTaskMemoryScanner _generateMetadataClassInfoIsaIndexes]
+ -[VMUTaskMemoryScanner _nodeIsPossibleSwiftMetadataHeapBlock:]
+ GCC_except_table123
+ GCC_except_table131
+ GCC_except_table147
+ GCC_except_table161
+ _OBJC_IVAR_$_VMUObjectIdentifier._libswiftCoreSymbolOwner
+ _OBJC_IVAR_$_VMUTaskMemoryScanner._mslLiteZoneIndex
+ _VMUIsTaskSimulator
- GCC_except_table144
- GCC_except_table158
- GCC_except_table86
CStrings:
+ "Could not get current swift metadata allocation pool"
+ "Could not get node for swift metadata allocation pool"
+ "Could not read swift metadata block back pointer"
+ "__swift_debug_allocationPoolBackPointerOffset"
+ "__swift_debug_allocationPoolPointer"
+ "qb"
- "Qb"
```
