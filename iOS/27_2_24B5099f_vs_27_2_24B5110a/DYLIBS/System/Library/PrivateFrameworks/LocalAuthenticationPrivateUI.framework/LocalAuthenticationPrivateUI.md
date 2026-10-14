## LocalAuthenticationPrivateUI

> `/System/Library/PrivateFrameworks/LocalAuthenticationPrivateUI.framework/LocalAuthenticationPrivateUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3182c` | `0x31b24` | **`+0x2f8`** |
| `__AUTH_CONST.__objc_const` | `0x3c10` | `0x3cb8` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x3804` | `0x3868` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x19bc` | `0x1a1c` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x51d` | `0x570` | **`+0x53`** |
| `__AUTH.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x16d0` | `0x1700` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x14b8` | `0x14e8` | **`+0x30`** |
| `__DATA.__bss` | `0x100` | `0xe8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-2319.40.43.0.0
+2319.42.1.0.0

-  Functions: 1000
-  Symbols:   1954
-  CStrings:  169
+  Functions: 1006
+  Symbols:   1972
+  CStrings:  170
Symbols:
+ +[LAUIPhysicalButtonGeometry sharedInstance]
+ -[LAUIPhysicalButtonGeometry _displayIndexForWindowScene:]
+ -[LAUIPhysicalButtonGeometry _isMultiSurfaceDevice]
+ -[LAUIPhysicalButtonGeometry _normalizedRect]
+ -[LAUIPhysicalButtonGeometry _rectFromAnswer:]
+ -[LAUIPhysicalButtonGeometry normalizedRectForWindowScene:]
+ GCC_except_table13
+ _CFDataGetLength
+ _LAUIPhysicalButtonNormalizedFrameForWindowScene
+ _MGCopyAnswerForDisplayAtIndex
+ _OBJC_CLASS_$_LAUIPhysicalButtonGeometry
+ _OBJC_METACLASS_$_LAUIPhysicalButtonGeometry
+ __OBJC_$_CLASS_METHODS_LAUIPhysicalButtonGeometry
+ __OBJC_$_CLASS_PROP_LIST_LAUIPhysicalButtonGeometry
+ __OBJC_$_INSTANCE_METHODS_LAUIPhysicalButtonGeometry
+ __OBJC_CLASS_RO_$_LAUIPhysicalButtonGeometry
+ __OBJC_METACLASS_RO_$_LAUIPhysicalButtonGeometry
+ __ZZ44+[LAUIPhysicalButtonGeometry sharedInstance]E14sharedInstance
+ __ZZ44+[LAUIPhysicalButtonGeometry sharedInstance]E9onceToken
+ __ZZ51-[LAUIPhysicalButtonGeometry _isMultiSurfaceDevice]E18multiSurfaceDevice
+ __ZZ51-[LAUIPhysicalButtonGeometry _isMultiSurfaceDevice]E9onceToken
+ ___44+[LAUIPhysicalButtonGeometry sharedInstance]_block_invoke
+ ___46-[LAUIPhysicalButtonView _purgeExportedHandle]_block_invoke
+ ___51-[LAUIPhysicalButtonGeometry _isMultiSurfaceDevice]_block_invoke
+ _kMGDisplayIndexedQueryUserIntentPhysicalButtonNormalizedCGRect
- __Z37LAUIPhysicalButtonHasMultipleDisplaysv
- __ZZ33LAUIPhysicalButtonNormalizedFrameE5frame
- __ZZ33LAUIPhysicalButtonNormalizedFrameE9onceToken
- __ZZ37LAUIPhysicalButtonHasMultipleDisplaysvE19hasMultipleDisplays
- __ZZ37LAUIPhysicalButtonHasMultipleDisplaysvE9onceToken
- ___LAUIPhysicalButtonNormalizedFrame_block_invoke
- ____Z37LAUIPhysicalButtonHasMultipleDisplaysv_block_invoke
CStrings:
+ "MG: no button rect for display %ld (error %d); falling back to the primary surface"
```
