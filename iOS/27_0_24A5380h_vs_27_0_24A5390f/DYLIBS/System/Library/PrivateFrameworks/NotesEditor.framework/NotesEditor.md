## NotesEditor

> `/System/Library/PrivateFrameworks/NotesEditor.framework/NotesEditor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x307f00` | `0x308fbc` | **`+0x10bc`** |
| `__AUTH_CONST.__const` | `0xb800` | `0xb8f0` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x206b8` | `0x20778` | **`+0xc0`** |
| `__TEXT.__const` | `0xbc84` | `0xbd14` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0xf988` | `0xfa08` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x16b7c` | `0x16bdc` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x3490` | `0x34e4` | **`+0x54`** |
| `__TEXT.__gcc_except_tab` | `0x3d48` | `0x3d90` | **`+0x48`** |
| `__AUTH.__data` | `0x2ca0` | `0x2ce0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xb8cb` | `0xb88b` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x9fd0` | `0xa010` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x5c10` | `0x5c40` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x361a8` | `0x361d0` | **`+0x28`** |
| `__DATA.__bss` | `0x5268` | `0x5288` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x5055` | `0x5075` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3970` | `0x3988` | **`+0x18`** |
| `__DATA.__data` | `0x87bc` | `0x87cc` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x4738` | `0x4748` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x30f8` | `0x3108` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1238` | `0x1248` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x39ac` | `0x39b8` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1108` | `0x1110` | **`+0x8`** |

### Other Changes

```diff

-2996.0.0.0.0
+2998.0.0.0.0

-  Functions: 15681
-  Symbols:   14287
-  CStrings:  1903
+  Functions: 15717
+  Symbols:   14299
+  CStrings:  1901
Symbols:
+ -[ICBaseTextView textAreaSafeAreaDistanceFromTop]
+ -[ICTK2TextView _safeAreaInsetsForFrame:inSuperview:]
+ -[ICTK2TextView enforcesMinimumTopSafeAreaInset]
+ -[ICTK2TextView setEnforcesMinimumTopSafeAreaInset:]
+ -[ICTextViewScrollState sectionLinkParagraphID]
+ -[ICTextViewScrollState setSectionLinkParagraphID:]
+ _ICInternalSettingsCloudSharingUISharingExpEnabled
+ _ICTTAttributeNameTimestamp
+ _OBJC_CLASS_$_UIGraphicsImageRendererFormat
+ _OBJC_IVAR_$_ICTK2TextView._enforcesMinimumTopSafeAreaInset
+ _OBJC_IVAR_$_ICTextViewScrollState._sectionLinkParagraphID
+ _keypath_get.6Tm
+ _keypath_set.81Tm
+ _symbolic So30UIGraphicsImageRendererContextCIgg_
- _keypath_get.1Tm
- _keypath_set.76Tm
CStrings:
- "RealtimeCollaboration/Caret"
- "Resume button label"
```
