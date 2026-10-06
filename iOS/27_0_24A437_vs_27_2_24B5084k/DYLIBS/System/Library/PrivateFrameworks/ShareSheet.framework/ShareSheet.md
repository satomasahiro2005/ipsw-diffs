## ShareSheet

> `/System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc7c84` | `0xc8ab4` | **`+0xe30`** |
| `__AUTH_CONST.__objc_const` | `0x2a388` | `0x2a558` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x11344` | `0x1141c` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x720c` | `0x72be` | **`+0xb2`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c48` | `0x8cf0` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x5a20` | `0x5a80` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x7217` | `0x726d` | **`+0x56`** |
| `__TEXT.__gcc_except_tab` | `0x207c` | `0x20c4` | **`+0x48`** |
| `__TEXT.__dlopen_cstrs` | `0xb4f` | `0xb96` | **`+0x47`** |
| `__DATA_CONST.__const` | `0x28d8` | `0x2918` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3570` | `0x35a8` | **`+0x38`** |
| `__DATA.__bss` | `0xad8` | `0xaf0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x14a4` | `0x14b8` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xfd0` | `0xfe0` | **`+0x10`** |
| `__AUTH.__data` | `0x198` | `0x1a0` | **`+0x8`** |

### Other Changes

```diff

-2131.10.1.2.11
+2131.20.65.2.1

-  Functions: 5906
-  Symbols:   10264
-  CStrings:  1618
+  Functions: 5931
+  Symbols:   10303
+  CStrings:  1622
Symbols:
+ -[SFShareSheetSlotManager performShortcutActivityInHostWithBundleID:singleUseToken:sourceAppIsManaged:]
+ -[SHSheetContentLayoutSpec canAccommodateTopActionsRowForContentWidth:]
+ -[SHSheetInteractor collaborationOptionsDidChangeForSession:]
+ -[SHSheetServiceManager performShortcutActivityInHostWithBundleID:singleUseToken:sourceAppIsManaged:]
+ -[SHSheetSession isPublicCollaborationForActivities]
+ -[SHSheetSession setIsPublicCollaborationForActivities:]
+ -[UIActivityContentViewController _canShowTopActionsRow]
+ -[UIActivityContentViewController _updateAutoExpansionInteractionIfNeeded]
+ -[UIActivityContentViewController autoExpansionInteraction]
+ -[UIActivityContentViewController handleShouldAutoExpand:]
+ -[UIActivityContentViewController setAutoExpansionInteraction:]
+ -[UIActivityContentViewController setShouldAutoExpand:]
+ -[UIActivityContentViewController shouldAutoExpand]
+ -[UICopyToPasteboardActivity .cxx_destruct]
+ -[UICopyToPasteboardActivity _copyDataOwner]
+ -[UICopyToPasteboardActivity isContentManaged]
+ -[UICopyToPasteboardActivity setIsContentManaged:]
+ -[UICopyToPasteboardActivity setSourceApplicationBundleID:]
+ -[UICopyToPasteboardActivity sourceApplicationBundleID]
+ GCC_except_table102
+ GCC_except_table130
+ GCC_except_table84
+ _CloudKitLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_UTType
+ _OBJC_IVAR_$_SHSheetSession._isPublicCollaborationForActivities
+ _OBJC_IVAR_$_UIActivityContentViewController._autoExpansionInteraction
+ _OBJC_IVAR_$_UIActivityContentViewController._shouldAutoExpand
+ _OBJC_IVAR_$_UICopyToPasteboardActivity._isContentManaged
+ _OBJC_IVAR_$_UICopyToPasteboardActivity._sourceApplicationBundleID
+ _SFUIActivityViewControllerConfiguratorFunction
+ _UIFontWeightMedium
+ __OBJC_$_INSTANCE_VARIABLES_UICopyToPasteboardActivity
+ __OBJC_$_PROP_LIST_UICopyToPasteboardActivity
+ __OBJC_CLASS_PROTOCOLS_$_UICopyToPasteboardActivity
+ ___101-[SHSheetServiceManager performShortcutActivityInHostWithBundleID:singleUseToken:sourceAppIsManaged:]_block_invoke
+ ___55-[UICopyToPasteboardActivity prepareWithActivityItems:]_block_invoke_2
+ ___74-[UIActivityContentViewController _updateAutoExpansionInteractionIfNeeded]_block_invoke
+ ___CloudKitLibraryCore_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___getCKAllowedSharingOptionsClass_block_invoke
+ _audit_stringCloudKit
+ _classSFUIActivityViewControllerConfigurator
+ _getCKAllowedSharingOptionsClass.softClass
+ _getSFUIActivityViewControllerConfiguratorClass
+ _initSFUIActivityViewControllerConfigurator
- -[SFShareSheetSlotManager performShortcutActivityInHostWithBundleID:singleUseToken:]
- -[SHSheetServiceManager performShortcutActivityInHostWithBundleID:singleUseToken:]
- GCC_except_table113
- GCC_except_table123
- GCC_except_table126
- ___82-[SHSheetServiceManager performShortcutActivityInHostWithBundleID:singleUseToken:]_block_invoke
CStrings:
+ "CKAllowedSharingOptions"
+ "Not re-filtering activities for collaboration options change, session hasn't started."
+ "SHARE_LINK_ACCESS_REQUESTS_ALREADY_ON_MESSAGE_NO_PUBLIC_SHARING"
+ "SHARE_LINK_ACCESS_REQUESTS_OFF_MESSAGE_NO_PUBLIC_SHARING"
+ "SHARE_LINK_ACCESS_REQUESTS_UNSUPPORTED_MESSAGE_NO_PUBLIC_SHARING"
+ "softlink:r:path:/System/Library/Frameworks/CloudKit.framework/CloudKit"
- "TelephonyUtilities"
- "mochiEnabled"
```
