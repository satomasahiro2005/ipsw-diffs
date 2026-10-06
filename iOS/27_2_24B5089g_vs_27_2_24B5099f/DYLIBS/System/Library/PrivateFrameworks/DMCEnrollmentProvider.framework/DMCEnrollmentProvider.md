## DMCEnrollmentProvider

> `/System/Library/PrivateFrameworks/DMCEnrollmentProvider.framework/DMCEnrollmentProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50444` | `0x51a84` | **`+0x1640`** |
| `__AUTH_CONST.__objc_const` | `0x114a0` | `0x11fa0` | **`+0xb00`** |
| `__TEXT.__objc_methlist` | `0x7254` | `0x73e4` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x24cf` | `0x25ef` | **`+0x120`** |
| `__TEXT.__cstring` | `0x2f98` | `0x3098` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x1b00` | `0x1bf0` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x30c0` | `0x31a0` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x49c8` | `0x4a98` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x7b4` | `0x83c` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x15b8` | `0x1638` | **`+0x80`** |
| `__DATA.__data` | `0x1458` | `0x14b8` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xef8` | `0xf28` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1218` | `0x1240` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x5f8` | `0x614` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x310` | `0x328` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x250` | `0x268` | **`+0x18`** |
| `__TEXT.__const` | `0x504` | `0x514` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x7c8` | `0x7c0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Other Changes

```diff

-113.40.17.0.0
+113.40.20.0.0

+  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

-  Functions: 2221
-  Symbols:   4256
-  CStrings:  634
+  Functions: 2258
+  Symbols:   4332
+  CStrings:  647
Symbols:
+ -[DMCBYODEnrollmentFlowUIPresenter _appNetworkAccessItemForBundleID:]
+ -[DMCBYODEnrollmentFlowUIPresenter _appNetworkAccessItemsForCapabilities:]
+ -[DMCBYODEnrollmentFlowUIPresenter _openApplicationWithBundleID:]
+ -[DMCBYODEnrollmentFlowUIPresenter appNetworkAccessCompletionHandler]
+ -[DMCBYODEnrollmentFlowUIPresenter appNetworkAccessViewController:didReceiveUserAction:]
+ -[DMCBYODEnrollmentFlowUIPresenter ensureAppNetworkAccessForCapabilities:completionHandler:]
+ -[DMCBYODEnrollmentFlowUIPresenter setAppNetworkAccessCompletionHandler:]
+ -[DMCEnrollmentAppNetworkAccessItem .cxx_destruct]
+ -[DMCEnrollmentAppNetworkAccessItem actionTitle]
+ -[DMCEnrollmentAppNetworkAccessItem action]
+ -[DMCEnrollmentAppNetworkAccessItem icon]
+ -[DMCEnrollmentAppNetworkAccessItem initWithTitle:icon:actionTitle:action:]
+ -[DMCEnrollmentAppNetworkAccessItem title]
+ -[DMCEnrollmentAppNetworkAccessViewController .cxx_destruct]
+ -[DMCEnrollmentAppNetworkAccessViewController _setupUI]
+ -[DMCEnrollmentAppNetworkAccessViewController delegate]
+ -[DMCEnrollmentAppNetworkAccessViewController dmc_viewControllerHasBeenDismissed]
+ -[DMCEnrollmentAppNetworkAccessViewController initWithDelegate:items:]
+ -[DMCEnrollmentAppNetworkAccessViewController items]
+ -[DMCEnrollmentAppNetworkAccessViewController leftBarButtonTapped:]
+ -[DMCEnrollmentAppNetworkAccessViewController setDelegate:]
+ -[DMCEnrollmentAppNetworkAccessViewController setItems:]
+ -[DMCEnrollmentAppNetworkAccessViewController viewWillAppear:]
+ -[DMCEnrollmentTableViewActionCell _buttonWithTitle:action:]
+ -[DMCEnrollmentTableViewActionCell cellHeight]
+ -[DMCEnrollmentTableViewActionCell cell]
+ -[DMCEnrollmentTableViewActionCell estimatedCellHeight]
+ -[DMCEnrollmentTableViewActionCell initWithTitle:icon:actionTitle:action:]
+ GCC_except_table69
+ GCC_except_table71
+ GCC_except_table89
+ _DMCAuthKitUIUnavailableError
+ _OBJC_CLASS_$_DMCAppNetworkAccessCheck
+ _OBJC_CLASS_$_DMCEnrollmentAppNetworkAccessItem
+ _OBJC_CLASS_$_DMCEnrollmentAppNetworkAccessViewController
+ _OBJC_CLASS_$_DMCEnrollmentTableViewActionCell
+ _OBJC_CLASS_$_FBSOpenApplicationService
+ _OBJC_CLASS_$_UIButtonConfiguration
+ _OBJC_IVAR_$_DMCBYODEnrollmentFlowUIPresenter._appNetworkAccessCompletionHandler
+ _OBJC_IVAR_$_DMCEnrollmentAppNetworkAccessItem._action
+ _OBJC_IVAR_$_DMCEnrollmentAppNetworkAccessItem._actionTitle
+ _OBJC_IVAR_$_DMCEnrollmentAppNetworkAccessItem._icon
+ _OBJC_IVAR_$_DMCEnrollmentAppNetworkAccessItem._title
+ _OBJC_IVAR_$_DMCEnrollmentAppNetworkAccessViewController._delegate
+ _OBJC_IVAR_$_DMCEnrollmentAppNetworkAccessViewController._items
+ _OBJC_METACLASS_$_DMCEnrollmentAppNetworkAccessItem
+ _OBJC_METACLASS_$_DMCEnrollmentAppNetworkAccessViewController
+ _OBJC_METACLASS_$_DMCEnrollmentTableViewActionCell
+ __OBJC_$_INSTANCE_METHODS_DMCEnrollmentAppNetworkAccessItem
+ __OBJC_$_INSTANCE_METHODS_DMCEnrollmentAppNetworkAccessViewController
+ __OBJC_$_INSTANCE_METHODS_DMCEnrollmentTableViewActionCell
+ __OBJC_$_INSTANCE_VARIABLES_DMCEnrollmentAppNetworkAccessItem
+ __OBJC_$_INSTANCE_VARIABLES_DMCEnrollmentAppNetworkAccessViewController
+ __OBJC_$_PROP_LIST_DMCEnrollmentAppNetworkAccessItem
+ __OBJC_$_PROP_LIST_DMCEnrollmentAppNetworkAccessViewController
+ __OBJC_$_PROP_LIST_DMCEnrollmentTableViewActionCell
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_DMCEnrollmentAppNetworkAccessViewControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_DMCEnrollmentAppNetworkAccessViewControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_DMCEnrollmentAppNetworkAccessViewControllerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_DMCEnrollmentAppNetworkAccessViewController
+ __OBJC_CLASS_PROTOCOLS_$_DMCEnrollmentTableViewActionCell
+ __OBJC_CLASS_RO_$_DMCEnrollmentAppNetworkAccessItem
+ __OBJC_CLASS_RO_$_DMCEnrollmentAppNetworkAccessViewController
+ __OBJC_CLASS_RO_$_DMCEnrollmentTableViewActionCell
+ __OBJC_LABEL_PROTOCOL_$_DMCEnrollmentAppNetworkAccessViewControllerDelegate
+ __OBJC_METACLASS_RO_$_DMCEnrollmentAppNetworkAccessItem
+ __OBJC_METACLASS_RO_$_DMCEnrollmentAppNetworkAccessViewController
+ __OBJC_METACLASS_RO_$_DMCEnrollmentTableViewActionCell
+ __OBJC_PROTOCOL_$_DMCEnrollmentAppNetworkAccessViewControllerDelegate
+ ___55-[DMCEnrollmentAppNetworkAccessViewController _setupUI]_block_invoke
+ ___55-[DMCEnrollmentAppNetworkAccessViewController _setupUI]_block_invoke_2
+ ___60-[DMCEnrollmentTableViewActionCell _buttonWithTitle:action:]_block_invoke
+ ___65-[DMCBYODEnrollmentFlowUIPresenter _openApplicationWithBundleID:]_block_invoke
+ ___69-[DMCBYODEnrollmentFlowUIPresenter _appNetworkAccessItemForBundleID:]_block_invoke
+ ___92-[DMCBYODEnrollmentFlowUIPresenter ensureAppNetworkAccessForCapabilities:completionHandler:]_block_invoke
+ ___92-[DMCBYODEnrollmentFlowUIPresenter ensureAppNetworkAccessForCapabilities:completionHandler:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e37_v24?0"BSProcessHandle"8"NSError"16ls32l8w40l8
+ _kDMCTableViewCellHorizontalMargin
- GCC_except_table80
- _objc_retain_x7
CStrings:
+ "Advising the user about network access for %{public}@. State: %lu"
+ "All apps this enrollment needs already have network access."
+ "AuthKitUI is unavailable, cannot authenticate"
+ "Failed to open %{public}@ with error: %{public}@"
+ "Opening %{public}@ so the user can grant it network access."
+ "UI_APP_NETWORK_ACCESS"
+ "UI_APP_NETWORK_ACCESS_DESCRIPTION"
+ "UI_APP_NETWORK_ACCESS_OPEN"
+ "UI_APP_NETWORK_ACCESS_OPEN_FAILED_MESSAGE"
+ "UI_APP_NETWORK_ACCESS_OPEN_FAILED_TITLE_%@"
+ "UNSUPPORTED_FEATURE"
+ "antenna.radiowaves.left.and.right"
+ "v24@?0@\"BSProcessHandle\"8@\"NSError\"16"
```
