## ShortcutsSettings

> `/System/Library/PreferenceBundles/ShortcutsSettings.bundle/ShortcutsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30cc` | `0x4b58` | **`+0x1a8c`** |
| `__TEXT.__objc_stubs` | `0x6e0` | `0x1340` | **`+0xc60`** |
| `__TEXT.__objc_methname` | `0xa32` | `0x144c` | **`+0xa1a`** |
| `__DATA.__objc_selrefs` | `0x348` | `0x690` | **`+0x348`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x5e0` | **`+0x280`** |
| `__DATA.__objc_const` | `0x540` | `0x790` | **`+0x250`** |
| `__TEXT.__cstring` | `0x387` | `0x560` | **`+0x1d9`** |
| `__TEXT.__objc_methlist` | `0x3bc` | `0x52c` | **`+0x170`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x280` | **`+0xb8`** |
| `__DATA.__data` | `0x1c0` | `0x258` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x160` | `0x1e8` | **`+0x88`** |
| `__TEXT.__objc_classname` | `0xee` | `0x166` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0x4f0` | `0x560` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x158` | `0x1b0` | **`+0x58`** |
| `__TEXT.__objc_methtype` | `0x223` | `0x277` | **`+0x54`** |
| `__DATA.__objc_data` | `0x140` | `0x190` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x8c` | `0xd0` | **`+0x44`** |
| `__TEXT.__const` | `0x114` | `0x150` | **`+0x3c`** |
| `__DATA_CONST.__auth_got` | `0x280` | `0x2b8` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0xc` | `0x24` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2c` | `0x3c` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x106` | `0x10c` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0

+  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

-  Functions: 82
-  Symbols:   140
-  CStrings:  181
+  Functions: 113
+  Symbols:   178
+  CStrings:  328
Symbols:
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_CLASS_$_NSLayoutConstraint
+ _OBJC_CLASS_$_PSTableCell
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _OBJC_CLASS_$_UIApplication
+ _OBJC_CLASS_$_UIColor
+ _OBJC_CLASS_$_UIControl
+ _OBJC_CLASS_$_UIFont
+ _OBJC_CLASS_$_UIImage
+ _OBJC_CLASS_$_UIImageSymbolConfiguration
+ _OBJC_CLASS_$_UIImageView
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$_UIStackView
+ _OBJC_CLASS_$_VCVoiceShortcutClient
+ _OBJC_CLASS_$_WFEditorExperiencePickerCell
+ _OBJC_CLASS_$_WFGenerativeShortcutsAvailabilityProvider
+ _OBJC_METACLASS_$_PSTableCell
+ _OBJC_METACLASS_$_WFEditorExperiencePickerCell
+ _PSCellClassKey
+ _UIAccessibilityTraitButton
+ _UIAccessibilityTraitSelected
+ _UIFontTextStyleSubheadline
+ _WFEditorExperienceDescribeTitleKey
+ _WFEditorExperienceEditorTitleKey
+ _WFShortcutsDefaultEditorExperienceKey
+ _WFShortcutsEditorTipDismissedKey
+ _WFShortcutsSettingsLocalizedPluralString
+ __NSConcreteStackBlock
+ ___NSDictionary0__struct
+ __dispatch_main_q
+ _dispatch_async
+ _objc_alloc_init
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x2
+ _objc_retain_x20
+ _objc_retain_x8
CStrings:
+ "\n"
+ " "
+ "%@ (Pluralization)"
+ "%ld shortcuts on this device aren't currently in your library."
+ "@\"NSArray\""
+ "@\"UIStackView\""
+ "@28@0:8q16B24"
+ "@40@0:8q16@24@32"
+ "Choose what you see first when you create or open a shortcut. Describe with Apple Intelligence, or start directly in the editor."
+ "DaS_Active"
+ "DaS_Inactive"
+ "Describe a Shortcut"
+ "Editor"
+ "Editor_Active"
+ "Editor_Inactive"
+ "OK"
+ "Open shortcuts to"
+ "Restore"
+ "Restore Failed"
+ "T@\"NSArray\",&,N,V_glyphImageViews"
+ "T@\"NSArray\",&,N,V_optionCards"
+ "T@\"NSArray\",&,N,V_radioImageViews"
+ "T@\"NSArray\",&,N,V_titleLabels"
+ "T@\"UIStackView\",&,N,V_optionsStackView"
+ "Tq,N,V_cachedRecoverableShortcutsCount"
+ "WFEditorExperienceDescribeTitle"
+ "WFEditorExperienceEditorTitle"
+ "WFEditorExperiencePickerCell"
+ "_TtC17ShortcutsSettingsP33_544E422019DC726BD7561CB8654A491A19ResourceBundleClass"
+ "_cachedRecoverableShortcutsCount"
+ "_glyphImageViews"
+ "_optionCards"
+ "_optionsStackView"
+ "_radioImageViews"
+ "_titleLabels"
+ "actionWithTitle:style:handler:"
+ "activateConstraints:"
+ "addAction:"
+ "addSubview:"
+ "addTarget:action:forControlEvents:"
+ "alertControllerWithTitle:message:preferredStyle:"
+ "array"
+ "bottomAnchor"
+ "cachedRecoverableShortcutsCount"
+ "centerYAnchor"
+ "checkmark.circle.fill"
+ "circle"
+ "configurationWithPointSize:weight:"
+ "constraintEqualToAnchor:"
+ "constraintEqualToAnchor:constant:"
+ "constraintEqualToConstant:"
+ "constraintGreaterThanOrEqualToAnchor:constant:"
+ "contentView"
+ "count"
+ "d32@0:8@16@24"
+ "editorExperienceGroupSpecifier"
+ "editorExperiencePickerSpecifier"
+ "fetchRecoverableShortcutsCount"
+ "glyphImageViews"
+ "heightAnchor"
+ "imageNamed:inBundle:withConfiguration:"
+ "initWithArrangedSubviews:"
+ "initWithStyle:reuseIdentifier:specifier:"
+ "integerValue"
+ "isExperienceAvailable"
+ "labelColor"
+ "layoutMarginsGuide"
+ "leadingAnchor"
+ "length"
+ "localizedDescription"
+ "localizedStringWithFormat:"
+ "numberWithInteger:"
+ "objectAtIndexedSubscript:"
+ "openURL:options:completionHandler:"
+ "optionCards"
+ "optionsStackView"
+ "performGetter"
+ "performSetterWithValue:"
+ "preferredFontForTextStyle:"
+ "presentViewController:animated:completion:"
+ "q"
+ "radioImageViews"
+ "recoverMissingShortcutsWithCompletion:"
+ "recoverableShortcutsCountWithCompletion:"
+ "recoveredShortcutsCount"
+ "recoveredShortcutsGroupSpecifier"
+ "refreshCellContentsWithSpecifier:"
+ "reloadSpecifiers"
+ "restoreButtonSpecifier"
+ "restoreRecoveredShortcuts"
+ "setAccessibilityLabel:"
+ "setAccessibilityTraits:"
+ "setActive:"
+ "setAdjustsFontForContentSizeCategory:"
+ "setAdjustsFontSizeToFitWidth:"
+ "setAlignment:"
+ "setAxis:"
+ "setButtonAction:"
+ "setCachedRecoverableShortcutsCount:"
+ "setContentMode:"
+ "setDistribution:"
+ "setFont:"
+ "setGlyphImageViews:"
+ "setImage:"
+ "setIsAccessibilityElement:"
+ "setMinimumScaleFactor:"
+ "setNumberOfLines:"
+ "setOptionCards:"
+ "setOptionsStackView:"
+ "setRadioImageViews:"
+ "setSelected:"
+ "setSelectionStyle:"
+ "setSpacing:"
+ "setSpecifier:"
+ "setTag:"
+ "setText:"
+ "setTextAlignment:"
+ "setTextColor:"
+ "setTintColor:"
+ "setTitleLabels:"
+ "setTranslatesAutoresizingMaskIntoConstraints:"
+ "setUserInteractionEnabled:"
+ "shared"
+ "sharedApplication"
+ "shortcuts://home"
+ "specifier"
+ "specifierAtIndexPath:"
+ "standardClient"
+ "stringByReplacingOccurrencesOfString:withString:"
+ "systemImageNamed:withConfiguration:"
+ "tableView:heightForRowAtIndexPath:"
+ "tag"
+ "tertiaryLabelColor"
+ "text"
+ "tintColor"
+ "tintColorDidChange"
+ "titleLabels"
+ "topAnchor"
+ "trailingAnchor"
+ "v24@0:8q16"
+ "v24@?0q8@\"NSError\"16"
+ "wf_buildCards"
+ "wf_cardTapped:"
+ "wf_illustrationForIndex:selected:"
+ "wf_refreshFromSpecifier"
+ "wf_selectedExperience"
+ "wf_updateSelectionUI:"
```
