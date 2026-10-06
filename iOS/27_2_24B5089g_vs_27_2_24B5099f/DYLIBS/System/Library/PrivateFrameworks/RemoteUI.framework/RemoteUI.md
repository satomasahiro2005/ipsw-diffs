## RemoteUI

> `/System/Library/PrivateFrameworks/RemoteUI.framework/RemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x151638` | `0x152fe4` | **`+0x19ac`** |
| `__AUTH_CONST.__objc_const` | `0xefd0` | `0xf230` | **`+0x260`** |
| `__AUTH_CONST.__const` | `0x89d8` | `0x8af0` | **`+0x118`** |
| `__TEXT.__objc_methlist` | `0x8f5c` | `0x9064` | **`+0x108`** |
| `__DATA_CONST.__objc_selrefs` | `0x56f8` | `0x57a0` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x3fe0` | `0x4030` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5988` | `0x59c8` | **`+0x40`** |
| `__DATA.__data` | `0x4ae0` | `0x4b10` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x81c` | `0x848` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x1678` | `0x16a0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xa3ec` | `0xa412` | **`+0x26`** |
| `__TEXT.__swift5_reflstr` | `0x2cba` | `0x2cda` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3ac8` | `0x3ae0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2210` | `0x2220` | **`+0x10`** |
| `__DATA.__bss` | `0x13888` | `0x13898` | **`+0x10`** |
| `__TEXT.__const` | `0xfd54` | `0xfd64` | **`+0x10`** |
| `__TEXT.__cstring` | `0x56fd` | `0x570d` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x7e8` | `0x7f8` | **`+0x10`** |
| `__AUTH.__data` | `0x3310` | `0x3308` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1288` | `0x1290` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x458` | `0x460` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Other Changes

```diff

-640.125.2.0.0
+640.125.5.0.0

-  Functions: 8208
-  Symbols:   6667
+  Functions: 8233
+  Symbols:   6714
Symbols:
+ -[RUITableView _installTableHeaderView:]
+ -[RUITableView _loadServerFooterView]
+ -[RUITableView _pageDescribesItsOwnTableHeader:]
+ -[RUITableView externalHeaderFooterDidResize]
+ -[RUITableView externalTableFooterView]
+ -[RUITableView externalTableHeaderView]
+ -[RUITableView externallyManagedHeaderFooter]
+ -[RUITableView loadExternalHeaderAndFooterViews]
+ -[RUITableView setExternalHeaderFooterDidResize:]
+ -[RUITableView setExternallyManagedHeaderFooter:]
+ -[RUITableWelcomeController .cxx_destruct]
+ -[RUITableWelcomeController _headerTopOffset]
+ -[RUITableWelcomeController _hostRUITableView:]
+ -[RUITableWelcomeController _installExternalHeaderFooterIfNeeded]
+ -[RUITableWelcomeController _layoutButtonTray]
+ -[RUITableWelcomeController _restoreTableViewDelegate]
+ -[RUITableWelcomeController _suppressesInternalHeaderPadding]
+ -[RUITableWelcomeController _updateParentPreferredContentSize]
+ -[RUITableWelcomeController headerViewBottomToTableViewTopPadding]
+ -[RUITableWelcomeController initWithHostedTableView:title:detailText:]
+ -[RUITableWelcomeController rendersHeaderContent]
+ -[RUITableWelcomeController setShouldUseCustomButtonTray:]
+ -[RUITableWelcomeController setTableView:]
+ -[RUITableWelcomeController shouldUseCustomButtonTray]
+ -[RUITableWelcomeController viewDidLayoutSubviews]
+ -[RUITableWelcomeController viewDidLoad]
+ -[RUITableWelcomeController viewWillAppear:]
+ GCC_except_table1
+ GCC_except_table105
+ GCC_except_table109
+ GCC_except_table113
+ GCC_except_table137
+ _CGRectEqualToRect
+ _OBJC_CLASS_$_OBTableWelcomeController
+ _OBJC_CLASS_$_RUITableWelcomeController
+ _OBJC_IVAR_$_RUITableView._externalHeaderFooterDidResize
+ _OBJC_IVAR_$_RUITableView._externalTableFooterView
+ _OBJC_IVAR_$_RUITableView._externalTableHeaderView
+ _OBJC_IVAR_$_RUITableView._externallyManagedHeaderFooter
+ _OBJC_IVAR_$_RUITableView._lastPublishedFooterSize
+ _OBJC_IVAR_$_RUITableView._lastPublishedHeaderSize
+ _OBJC_IVAR_$_RUITableWelcomeController._installedFooterView
+ _OBJC_IVAR_$_RUITableWelcomeController._installedHeaderView
+ _OBJC_IVAR_$_RUITableWelcomeController._rendersHeaderContent
+ _OBJC_IVAR_$_RUITableWelcomeController._ruiTableView
+ _OBJC_IVAR_$_RUITableWelcomeController._shouldUseCustomButtonTray
+ _OBJC_METACLASS_$_OBTableWelcomeController
+ _OBJC_METACLASS_$_RUITableWelcomeController
+ __OBJC_$_INSTANCE_METHODS_OBButtonTray(RUI_Internal|RemoteUI|RUITableWelcome)
+ __OBJC_$_INSTANCE_METHODS_RUITableWelcomeController
+ __OBJC_$_INSTANCE_VARIABLES_RUITableWelcomeController
+ __OBJC_$_PROP_LIST_RUITableWelcomeController
+ __OBJC_CLASS_RO_$_RUITableWelcomeController
+ __OBJC_METACLASS_RO_$_RUITableWelcomeController
+ ___47-[RUITableWelcomeController _hostRUITableView:]_block_invoke
+ ___62-[RUITableWelcomeController _updateParentPreferredContentSize]_block_invoke
+ ___block_descriptor_56_e8_32s_e5_v8?0ls32l8
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQOyACyAA03AnyE0VAA012_EnvironmentJ17TransformModifierVySay06RemoteB00E7ContextOGGG_Qo_AA017_AppearanceActionN0VGAaDHPqd__AaDHD2_ASHO_AuA0eN0HPyHCHC
+ _symbolic _____y__________ySay_____GGG 7SwiftUI15ModifiedContentV AA7AnyViewV AA32_EnvironmentKeyTransformModifierV 06RemoteB00F7ContextO
+ _symbolic _____y_____yAAy__________ySay_____GGG_Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQO AA03AnyE0V AA012_EnvironmentJ17TransformModifierV 06RemoteB00E7ContextO AA017_AppearanceActionN0V
+ _symbolic _____y_____y__________ySay_____GGG_Qo_ 7SwiftUI4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQO AA15ModifiedContentV AA03AnyC0V AA012_EnvironmentH17TransformModifierV 06RemoteB00C7ContextO
- -[RUIObjectModel supportedInterfaceOrientationsForRUIPage:]
- -[RUIPage supportedInterfaceOrientations]
- -[RemoteUIController supportedInterfaceOrientationsForObjectModel:page:]
- GCC_except_table100
- GCC_except_table110
- GCC_except_table114
- GCC_except_table132
- GCC_except_table97
- __OBJC_$_INSTANCE_METHODS_OBButtonTray(RUI_Internal|RemoteUI)
- __OBJC_$_PROP_LIST_OBButtonTray_$_RUI_Internal
- _get_witness_table 7SwiftUI15ModifiedContentVyAA4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQOyAE06RemoteB0E06appendE7ContextyQrAI0eM0OFQOyAA03AnyE0V_Qo__Qo_AA25_AppearanceActionModifierVGAaDHPqd__AaDHD2_APHO_ArA0eQ0HPyHCHC
- _symbolic _____y______Qo_ 7SwiftUI4ViewP06RemoteB0E06appendC7ContextyQrAD0cF0OFQO AA03AnyC0V
- _symbolic _____y_____y______Qo__Qo_ 7SwiftUI4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQO AC06RemoteB0E06appendC7ContextyQrAG0cK0OFQO AA03AnyC0V
- _symbolic _____y_____y_____y______Qo__Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQO AE06RemoteB0E06appendE7ContextyQrAI0eM0OFQO AA03AnyE0V AA25_AppearanceActionModifierV
CStrings:
+ "forceHeaderInLeadingColumn"
- "\xf0\xa2"
```
