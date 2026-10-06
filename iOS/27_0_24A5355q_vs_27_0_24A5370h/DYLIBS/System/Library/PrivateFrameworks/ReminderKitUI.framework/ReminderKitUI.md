## ReminderKitUI

> `/System/Library/PrivateFrameworks/ReminderKitUI.framework/ReminderKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d9c` | `0xb5d0` | **`+0x3834`** |
| `__DATA.__bss` | `0x400` | `0xa00` | **`+0x600`** |
| `__AUTH_CONST.__const` | `0x458` | `0x7b1` | **`+0x359`** |
| `__TEXT.__const` | `0x568` | `0x85c` | **`+0x2f4`** |
| `__DATA.__data` | `0x390` | `0x550` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x9b8` | `0xb40` | **`+0x188`** |
| `__AUTH_CONST.__auth_got` | `0x3f0` | `0x550` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x368` | `0x480` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x1ed` | `0x302` | **`+0x115`** |
| `__TEXT.__oslogstring` | `0x1c0` | `0x2d0` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0x40` | `0x148` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x540` | `0x638` | **`+0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0x204` | `0x2f8` | **`+0xf4`** |
| `__TEXT.__swift5_typeref` | `0x22c` | `0x309` | **`+0xdd`** |
| `__TEXT.__constg_swiftt` | `0x2fc` | `0x3b4` | **`+0xb8`** |
| `__AUTH.__data` | `0x1e0` | `0x260` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x18` | `0x98` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x278` | `0x2d8` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x478` | `0x4d8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xe0` | `0x130` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x14` | `0x60` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0x148` | `0x178` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x2c` | `0x5c` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x38` | `0x58` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x38` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x50` | `0x68` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x24` | `0x38` | **`+0x14`** |
| `__TEXT.__cstring` | `0x340` | `0x332` | **`-0xe`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0

-  Functions: 345
-  Symbols:   410
-  CStrings:  31
+  Functions: 461
+  Symbols:   484
+  CStrings:  37
Symbols:
+ +[NSXPCInterface(REMRemindersShareSheetViewServiceInterfaces) _rem_applyReminderCreationServiceViewControllerClasses:]
+ +[NSXPCInterface(REMRemindersShareSheetViewServiceInterfaces) _rem_applyShareSheetRemoteViewControllerClasses:]
+ +[NSXPCInterface(REMRemindersShareSheetViewServiceInterfaces) _rem_applyShareSheetServiceViewControllerClasses:]
+ +[NSXPCInterface(REMRemindersShareSheetViewServiceInterfaces) rem_combinedViewServicesRemoteViewControllerInterface]
+ +[NSXPCInterface(REMRemindersShareSheetViewServiceInterfaces) rem_combinedViewServicesServiceViewControllerInterface]
+ +[REMRemindersShareSheetEmbedder embedShareSheetInHostViewController:publicViewController:reminderStorages:changedKeys:destinationPreference:specificListID:configurationData:setupCompletion:]
+ -[REMReminderCreationRemoteViewController setShareSheetPublicViewController:]
+ -[REMReminderCreationRemoteViewController shareSheetPublicViewController]
+ -[REMReminderCreationRemoteViewController shareSheetViewServiceViewController]
+ -[REMReminderCreationRemoteViewController viewServiceDidCommitWithReminderIDs:]
+ _CGSizeZero
+ _OBJC_CLASS_$_REMReminderChangeItem
+ _OBJC_CLASS_$_REMReminderStorage
+ _OBJC_CLASS_$_REMRemindersShareSheetEmbedder
+ _OBJC_IVAR_$_REMReminderCreationRemoteViewController._shareSheetPublicViewController
+ _OBJC_METACLASS_$_REMRemindersShareSheetEmbedder
+ __OBJC_$_CLASS_METHODS_REMRemindersShareSheetEmbedder
+ __OBJC_$_INSTANCE_METHODS__TtC13ReminderKitUI36REMRemindersShareSheetViewController(ReminderKitUI)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_REMRemindersShareSheetPublicViewController
+ __OBJC_$_PROTOCOL_METHOD_TYPES_REMRemindersShareSheetPublicViewController
+ __OBJC_$_PROTOCOL_REFS_REMReminderViewServicesCombinedRemoteViewController
+ __OBJC_$_PROTOCOL_REFS_REMReminderViewServicesCombinedServiceViewController
+ __OBJC_CLASS_PROTOCOLS_$__TtC13ReminderKitUI36REMRemindersShareSheetViewController(ReminderKitUI)
+ __OBJC_CLASS_RO_$_REMRemindersShareSheetEmbedder
+ __OBJC_LABEL_PROTOCOL_$_REMReminderViewServicesCombinedRemoteViewController
+ __OBJC_LABEL_PROTOCOL_$_REMReminderViewServicesCombinedServiceViewController
+ __OBJC_LABEL_PROTOCOL_$_REMRemindersShareSheetPublicViewController
+ __OBJC_METACLASS_RO_$_REMRemindersShareSheetEmbedder
+ __OBJC_PROTOCOL_$_REMReminderViewServicesCombinedRemoteViewController
+ __OBJC_PROTOCOL_$_REMReminderViewServicesCombinedServiceViewController
+ __OBJC_PROTOCOL_$_REMRemindersShareSheetPublicViewController
+ __OBJC_PROTOCOL_REFERENCE_$_REMReminderViewServicesCombinedRemoteViewController
+ __OBJC_PROTOCOL_REFERENCE_$_REMReminderViewServicesCombinedServiceViewController
+ ___191+[REMRemindersShareSheetEmbedder embedShareSheetInHostViewController:publicViewController:reminderStorages:changedKeys:destinationPreference:specificListID:configurationData:setupCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e30_v32?0"NSError"8{CGSize=dd}16lr40l8s32l8
+ ___block_descriptor_48_e8_32s40r_e77_v32?0"<NSCopying>"8"REMReminderCreationRemoteViewController"16"NSError"24lr40l8s32l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72bs80r_e77_v32?0"<NSCopying>"8"REMReminderCreationRemoteViewController"16"NSError"24lr80l8s72l8s32l8s40l8s48l8s56l8s64l8
+ ___swift__destructor
+ ___swift_closure_destructorTm
+ ___swift_memcpy48_8
+ ___swift_project_boxed_opaque_existential_1
+ __swiftEmptyDictionarySingleton
+ __swiftImmortalRefCount
+ _associated conformance 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV0I11LayoutStyleOSHAASQ
+ _associated conformance 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV10CodingKeysOSHAASQ
+ _associated conformance 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV10CodingKeysOs0U3KeyAAs23CustomStringConvertible
+ _associated conformance 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV10CodingKeysOs0U3KeyAAs28CustomDebugStringConvertible
+ _bzero
+ _memmove
+ _objc_moveWeak
+ _objc_retain_x21
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x28
+ _objc_retain_x9
+ _swift_beginAccess
+ _swift_dynamicCastObjCClass
+ _swift_getForeignTypeMetadata
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x26
+ _swift_retain_x26
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic SDySo11REMObjectIDCShySSGG
+ _symbolic SS
+ _symbolic SaySo18REMReminderStorageCG
+ _symbolic ShySSG
+ _symbolic So11REMObjectIDCSg
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 13ReminderKitUI36REMRemindersShareSheetViewControllerC11WirePayload33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV
+ _symbolic _____ 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV
+ _symbolic _____ 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV0I11LayoutStyleO
+ _symbolic _____ 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV10CodingKeysO
+ _symbolic _____ So43REMRemindersShareSheetDestinationPreferenceV
+ _symbolic _____Sg 13ReminderKitUI36REMRemindersShareSheetViewControllerC11WirePayload33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV
+ _symbolic _____SgXw 13ReminderKitUI36REMRemindersShareSheetViewControllerC
+ _symbolic ______pSg s5ErrorP
+ _symbolic _____ySo11REMObjectIDCShySSGG s18_DictionaryStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 13ReminderKitUI36REMRemindersShareSheetViewControllerC17WireConfiguration33_3CC6A07B062BDB4E67ED93B4E9DD37C6LLV10CodingKeysO
- _NSLocalizedDescriptionKey
- _OBJC_CLASS_$_NSError
- __INSTANCE_METHODS__TtC13ReminderKitUI36REMRemindersShareSheetViewController
- ___block_descriptor_48_e8_32s40r_e77_v32?0"<NSCopying>"8"REMReminderCreationRemoteViewController"16"NSError"24ls32l8r40l8
- _objc_retain_x26
- _swift_once
- _swift_release_x24
- _swift_retain_n
- _swift_retain_x24
- _symbolic SS_ypt
- _symbolic _____ySSypG s18_DictionaryStorageC
CStrings:
+ "REMRemindersShareSheetEmbedder: _UIResilientRemoteViewContainerViewController initialized (%@)"
+ "REMRemindersShareSheetEmbedder: extension lookup failed"
+ "REMRemindersShareSheetEmbedder: extension lookup failed %@"
+ "REMRemindersShareSheetEmbedder: loading extension %@"
+ "REMRemindersShareSheetEmbedder: remote view controller error: %@"
+ "editingAndSelection"
+ "selectionOnly"
- "REMRemindersShareSheetViewController: Phase 2 view-service wiring is not yet implemented. See rdar://176800523."
```
