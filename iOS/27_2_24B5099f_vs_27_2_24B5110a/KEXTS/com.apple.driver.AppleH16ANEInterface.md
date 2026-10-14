## com.apple.driver.AppleH16ANEInterface

> `com.apple.driver.AppleH16ANEInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x15bb10` | `0x15bb54` | **`+0x44`** |
| `__TEXT.__os_log` | `0x3e23b` | `0x3e239` | **`-0x2`** |

### Other Changes

```diff

-10.102.3.0.0
+10.102.4.0.0
Functions:
~ sub_fffffe0008d5f348 -> sub_fffffe0008d61448 : 240 -> 244
~ __ZN11ANEResource6createIL15ANEResourceType4EEENSt3__110shared_ptrIS_EEP14ANEHWInterfaceRK25ANEResourceCreationParamsPK21ANEThreadNameRegistry : 1000 -> 1008
~ __ZNK11ANEResource10readAdviseEv : 988 -> 1020
~ __ZNK11ANEResource10createCopyEv : 440 -> 460
~ __ZN11ANEResource5_wireEj : 460 -> 464
CStrings:
+ "%s: %s: read advise vnode: %p fileOffset: %lld fileSize: 0x%llx\n"
+ "[ERROR] %s: %s: vnode read advise failed, ret=%d\n"
- "%s: %s: vnode_rdadvise vnode: %p fileOffset: %lld fileSize: 0x%llx\n"
- "[INFO] %s: %s: vnode read advise failed, ret=%d\n"
```
