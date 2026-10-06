## RemindersAppIntents

> `/System/Library/PrivateFrameworks/RemindersAppIntents.framework/RemindersAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x262e4c` | `0x272afc` | **`+0xfcb0`** |
| `__TEXT.__eh_frame` | `0xc04c` | `0xeac4` | **`+0x2a78`** |
| `__TEXT.__unwind_info` | `0x7c90` | `0x8400` | **`+0x770`** |
| `__TEXT.__swift_as_cont` | `0xaa4` | `0xd48` | **`+0x2a4`** |
| `__AUTH_CONST.__const` | `0x9230` | `0x9480` | **`+0x250`** |
| `__TEXT.__cstring` | `0xf98a` | `0xfbba` | **`+0x230`** |
| `__TEXT.__const` | `0x154d4` | `0x15644` | **`+0x170`** |
| `__TEXT.__swift_as_ret` | `0x698` | `0x808` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x6773` | `0x66a3` | **`-0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x3edc` | `0x3f78` | **`+0x9c`** |
| `__TEXT.__swift5_typeref` | `0x7ec2` | `0x7f5e` | **`+0x9c`** |
| `__TEXT.__constg_swiftt` | `0x42fc` | `0x4384` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x1200` | `0x1270` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x4a0f` | `0x4a7f` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x2828` | `0x2870` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xc8` | **`+0x3c`** |
| `__TEXT.__swift_as_entry` | `0x760` | `0x79c` | **`+0x3c`** |
| `__TEXT.__swift5_capture` | `0x360` | `0x394` | **`+0x34`** |
| `__DATA.__data` | `0x4df8` | `0x4e28` | **`+0x30`** |
| `__DATA.__bss` | `0x173c0` | `0x173e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1e88` | `0x1ea8` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x1a68` | `0x1a58` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x3e8` | `0x3f4` | **`+0xc`** |

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0

-  Functions: 10443
-  Symbols:   2991
-  CStrings:  1402
+  Functions: 10724
+  Symbols:   3001
+  CStrings:  1409
Symbols:
+ _OBJC_CLASS_$_UIBezierPath
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ _get_witness_table 10AppIntents22IntentParameterSummaryVy09RemindersaB0011CreateGroupaC0VGAA0dE0HPyHC
+ _symbolic So30UIGraphicsImageRendererContextCIgg_
+ _symbolic So7UIColorC
+ _symbolic _____ So6CGRectV
+ _symbolic _____ So6CGSizeV
+ _symbolic _____ So7CGPointV
+ _symbolic _____y_____G 10AppIntents22IntentParameterSummaryV 09RemindersaB0011CreateGroupaC0V
+ _symbolic _____y_____G 10AppIntents22ParameterSummaryStringV 09RemindersaB0011CreateGroupA6IntentV
+ _symbolic _____y______G 10AppIntents22ParameterSummaryStringV0E13InterpolationV 09RemindersaB0011CreateGroupA6IntentV
+ _symbolic _____y__________ySSGG s7KeyPathC 19RemindersAppIntents011CreateGroupD6IntentV 0dE00H9ParameterC
+ _symbolic _____y__________ySay_____GGG s7KeyPathC 19RemindersAppIntents011CreateGroupD6IntentV 0dE00H9ParameterC AC10ListEntityV
- _OBJC_CLASS_$_UIImage
- _OBJC_CLASS_$_UIImageView
- _symbolic _____y______Qo_ 10AppIntents0A6IntentPAAE16parameterSummaryQrvpZQO 09RemindersaB0011CreateGroupaC0V
CStrings:
+ "Also delete the reminders contained in the sections being deleted."
+ "Create Group AppIntent group name parameter description"
+ "Create Group AppIntent group name parameter title"
+ "Create Group AppIntent lists parameter description"
+ "Create Group AppIntent lists parameter title"
+ "Delete Reminders"
+ "Delete Sections AppIntent delete reminders parameter description"
+ "Delete Sections AppIntent delete reminders parameter title"
+ "Lists to add to the new group"
+ "Name of the group to create"
+ "[DeleteSectionsAppIntent] Delete list sections with ids: %{public}s deleteReminders: %{bool,public}d"
+ "[DeleteSectionsAppIntent] Delete smart list sections with ids: %{public}s"
- "AnyListEntityLazyImage.displayRepresentationImage: cannot load group image data"
- "AnyListEntityLazyImage.displayRepresentationImage: cannot load group image: rectangle.stack"
- "Failed to get section entity for reminder: %@ | %s"
- "[DeleteRemindersAppIntent] Delete list sections with ids: %{public}s"
- "[DeleteRemindersAppIntent] Delete smart list sections with ids: %{public}s"
```
