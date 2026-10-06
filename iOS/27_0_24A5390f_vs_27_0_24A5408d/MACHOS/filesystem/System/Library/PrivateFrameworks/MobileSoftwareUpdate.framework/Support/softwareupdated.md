## softwareupdated

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/softwareupdated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2baa8` | `0x2bcd0` | **`+0x228`** |
| `__DATA_CONST.__cfstring` | `0x9d20` | `0x9d80` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x794` | `0x7f4` | **`+0x60`** |
| `__TEXT.__cstring` | `0xbcb6` | `0xbcf2` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x1978` | `0x19a0` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x3aa0` | `0x3ac0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3c67` | `0x3c80` | **`+0x19`** |
| `__TEXT.__unwind_info` | `0xa30` | `0xa48` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1504` | `0x1514` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x11d0` | `0x11d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-2718.0.12.0.0
+2718.0.18.0.0

-  Functions: 836
-  Symbols:   2310
-  CStrings:  2657
+  Functions: 838
+  Symbols:   2314
+  CStrings:  2661
Symbols:
+ -[UMEventRecorder _getCoalescedSubTargetID]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-47848c4b75f88441f64bf663032c47e0.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-975c7d4158e0ac13103afc2974f458a2.o
+ GCC_except_table19
+ ___block_descriptor_48_e8_32o40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_80_e8_32o40o48o56r64r_e5_v8?0ls32l8s40l8s48l8r56l8r64l8
+ _objc_msgSend$_getCoalescedSubTargetID
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-3706ebc2097927ad32ceb88b9a080fef.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/softwareupdated.build/Objects-normal/arm64e/common-d1673c0c16fe748c195b69493adf3aaf.o
- ___block_descriptor_72_e8_32o40o48o56r_e5_v8?0ls32l8s40l8s48l8r56l8
Functions:
~ _submitRestoreLogFileToLogDir : 2600 -> 2656
~ _handle_create_update_brain_connection : 604 -> 1648
~ ___copy_shared_update_brain_connection_block_invoke : 1472 -> 704
+ __copy_shared_update_brain_connection_block_invoke.243
~ -[UMEventRecorder _recordEvent:getPowerLog:information:callback:] : 2008 -> 2040
+ -[UMEventRecorder _getCoalescedSubTargetID]
+ handle_create_update_brain_connection.cold.2
- __copy_shared_update_brain_connection_block_invoke.cold.2
CStrings:
+ "CoalescedSubTargetID"
+ "_getCoalescedSubTargetID"
+ "coalescedSubTargetID"
+ "target_os_version"
```
