## CoordinationCore

> `/System/Library/PrivateFrameworks/CoordinationCore.framework/CoordinationCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dbe4` | `0x4c6f4` | **`-0x14f0`** |
| `__AUTH_CONST.__objc_const` | `0x8400` | `0x8168` | **`-0x298`** |
| `__TEXT.__objc_methlist` | `0x5248` | `0x5114` | **`-0x134`** |
| `__DATA.__data` | `0xde0` | `0xcc0` | **`-0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x2708` | `0x2630` | **`-0xd8`** |
| `__TEXT.__oslogstring` | `0x430b` | `0x4263` | **`-0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x1f50` | `0x1ed0` | **`-0x80`** |
| `__AUTH.__objc_data` | `0xd20` | `0xcd0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x16d0` | `0x1698` | **`-0x38`** |
| `__DATA_CONST.__const` | `0x1d28` | `0x1d00` | **`-0x28`** |
| `__TEXT.__cstring` | `0x146c` | `0x1452` | **`-0x1a`** |
| `__DATA.__objc_ivar` | `0x56c` | `0x554` | **`-0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x128` | `0x110` | **`-0x18`** |
| `__TEXT.__const` | `0x2b8` | `0x2c8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x230` | `0x228` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1f8` | `0x1f0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x188` | `0x180` | **`-0x8`** |

### Other Changes

```diff

-249.0.0.0.0
+249.0.3.0.0

-  Functions: 1877
-  Symbols:   3159
-  CStrings:  642
+  Functions: 1856
+  Symbols:   3108
+  CStrings:  635
Symbols:
- -[COHomeKitAdapter home:didAddMediaGroup:]
- -[COHomeKitAdapter home:didRemoveMediaGroup:]
- -[COHomeKitAdapter initWithHomeManager:MediaGroupsDaemon:]
- -[COHomeKitAdapter mediaGroupsDaemon]
- -[COHomeKitAdapter mediaGroupsListeners]
- -[COHomeKitAdapter setMediaGroupsListeners:]
- -[_COHomeKitMediaGroupsListener .cxx_destruct]
- -[_COHomeKitMediaGroupsListener controller]
- -[_COHomeKitMediaGroupsListener delegate]
- -[_COHomeKitMediaGroupsListener groups]
- -[_COHomeKitMediaGroupsListener home]
- -[_COHomeKitMediaGroupsListener initWithHome:]
- -[_COHomeKitMediaGroupsListener mediaGroupsController:didReceiveGroup:]
- -[_COHomeKitMediaGroupsListener mediaGroupsController:didRemoveGroup:]
- -[_COHomeKitMediaGroupsListener received]
- -[_COHomeKitMediaGroupsListener setDelegate:]
- GCC_except_table79
- GCC_except_table82
- _OBJC_CLASS_$_HMMediaSystemData
- _OBJC_CLASS_$__COHomeKitMediaGroupsListener
- _OBJC_IVAR_$_COHomeKitAdapter._mediaGroupsDaemon
- _OBJC_IVAR_$_COHomeKitAdapter._mediaGroupsListeners
- _OBJC_IVAR_$__COHomeKitMediaGroupsListener._controller
- _OBJC_IVAR_$__COHomeKitMediaGroupsListener._delegate
- _OBJC_IVAR_$__COHomeKitMediaGroupsListener._home
- _OBJC_IVAR_$__COHomeKitMediaGroupsListener._received
- _OBJC_METACLASS_$__COHomeKitMediaGroupsListener
- __OBJC_$_INSTANCE_METHODS__COHomeKitMediaGroupsListener
- __OBJC_$_INSTANCE_VARIABLES__COHomeKitMediaGroupsListener
- __OBJC_$_PROP_LIST__COHomeKitMediaGroupsListener
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMMediaGroupsControllerDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMMediaGroupsControllerDelegate_Deprecated
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__COHomeKitMediaGroupsListenerDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_HMMediaGroupsControllerDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_HMMediaGroupsControllerDelegate_Deprecated
- __OBJC_$_PROTOCOL_METHOD_TYPES__COHomeKitMediaGroupsListenerDelegate
- __OBJC_$_PROTOCOL_REFS_HMMediaGroupsControllerDelegate
- __OBJC_$_PROTOCOL_REFS_HMMediaGroupsControllerDelegate_Deprecated
- __OBJC_$_PROTOCOL_REFS__COHomeKitMediaGroupsListenerDelegate
- __OBJC_CLASS_PROTOCOLS_$__COHomeKitMediaGroupsListener
- __OBJC_CLASS_RO_$__COHomeKitMediaGroupsListener
- __OBJC_LABEL_PROTOCOL_$_HMMediaGroupsControllerDelegate
- __OBJC_LABEL_PROTOCOL_$_HMMediaGroupsControllerDelegate_Deprecated
- __OBJC_LABEL_PROTOCOL_$__COHomeKitMediaGroupsListenerDelegate
- __OBJC_METACLASS_RO_$__COHomeKitMediaGroupsListener
- __OBJC_PROTOCOL_$_HMMediaGroupsControllerDelegate
- __OBJC_PROTOCOL_$_HMMediaGroupsControllerDelegate_Deprecated
- __OBJC_PROTOCOL_$__COHomeKitMediaGroupsListenerDelegate
- ___76-[COHomeKitAdapter identifiersForAccessoriesAssociatedWithAccessory:inHome:]_block_invoke_2
- ___76-[COHomeKitAdapter identifiersForAccessoriesAssociatedWithAccessory:inHome:]_block_invoke_3
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88s96s_e29_v32?0"HMMediaGroup"8Q16^B24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
CStrings:
+ "249.0.3"
- "%p Added Media Group %@"
- "%p Removed Media Group %@"
- "%p dropping group received %@"
- "%p dropping group removed %@"
- "%p listening for groups in %@"
- "%p subscribing to all groups"
- "249"
- "v32@?0@\"HMMediaGroup\"8Q16^B24"
```
