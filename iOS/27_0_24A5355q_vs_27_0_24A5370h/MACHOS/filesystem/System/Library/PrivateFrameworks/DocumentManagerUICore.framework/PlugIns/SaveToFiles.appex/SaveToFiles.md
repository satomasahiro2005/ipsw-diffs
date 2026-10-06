## SaveToFiles

> `/System/Library/PrivateFrameworks/DocumentManagerUICore.framework/PlugIns/SaveToFiles.appex/SaveToFiles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4808` | `0x5454` | **`+0xc4c`** |
| `__TEXT.__objc_stubs` | `0xf80` | `0x1300` | **`+0x380`** |
| `__TEXT.__objc_methname` | `0x138d` | `0x1600` | **`+0x273`** |
| `__TEXT.__cstring` | `0x337` | `0x483` | **`+0x14c`** |
| `__TEXT.__auth_stubs` | `0x6d0` | `0x7d0` | **`+0x100`** |
| `__DATA.__objc_selrefs` | `0x588` | `0x670` | **`+0xe8`** |
| `__DATA.__objc_data` | `0x50` | `0x118` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x4a8` | `0x570` | **`+0xc8`** |
| `__DATA.__objc_const` | `0x448` | `0x4f8` | **`+0xb0`** |
| `__DATA_CONST.__auth_got` | `0x378` | `0x3f8` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x72` | `0xde` | **`+0x6c`** |
| `__DATA.__data` | `0x1f0` | `0x248` | **`+0x58`** |
| `__TEXT.__objc_methtype` | `0x3f2` | `0x445` | **`+0x53`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1e0` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x160` | `0x1a0` | **`+0x40`** |
| `__TEXT.__const` | `0xc4` | `0x104` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x44` | **`+0x34`** |
| `__TEXT.__constg_swiftt` | `0x50` | `0x7c` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0xbb` | `0xdb` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3b4` | `0x3d4` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x19` | **`+0x19`** |
| `__TEXT.__gcc_except_tab` | `0x5c` | `0x74` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4` | `0x8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_capture`

### Other Changes

```diff

-389.2.0.0.0
+392.0.0.0.0

+  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

-  Functions: 112
-  Symbols:   171
-  CStrings:  268
+  Functions: 129
+  Symbols:   191
+  CStrings:  310
Symbols:
+ _OBJC_CLASS_$_DOCSaveToFilesLoadingView
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_UIActivityIndicatorView
+ _OBJC_CLASS_$_UIFont
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$_UIStackView
+ _OBJC_CLASS_$_UIView
+ _OBJC_METACLASS_$_DOCSaveToFilesLoadingView
+ _OBJC_METACLASS_$_UIView
+ _UIFontTextStyleSubheadline
+ __DocumentManagerBundle
+ _dispatch_assert_queue$V2
+ _dispatch_get_global_queue
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_notify
+ _dispatch_queue_create
+ _objc_retain_x24
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x27
+ _objc_retain_x28
+ _objc_sync_enter
+ _objc_sync_exit
- _dispatch_after
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
- _dispatch_time
CStrings:
+ "@\"DOCSaveToFilesLoadingView\""
+ "@24@0:8@16"
+ "@48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "DOCSaveToFilesLoadingView"
+ "Fatal error"
+ "Loading text on the SaveToFiles loading screen (below the spinner)"
+ "SaveToFiles/DOCSaveToFilesLoadingView.swift"
+ "Unable to create temporary directory %@, error: %@"
+ "Using temporary directory instead: %@"
+ "_loadingView"
+ "activity"
+ "centerXAnchor"
+ "centerYAnchor"
+ "clearColor"
+ "com.apple.SaveToFiles.results"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "dealloc"
+ "enumerateObjectsUsingBlock:"
+ "init(coder:) has not been implemented"
+ "initWithArrangedSubviews:"
+ "initWithCoder:"
+ "initWithFrame:"
+ "label"
+ "layoutIfNeeded"
+ "loadItemProvider:completionHandler:"
+ "null"
+ "preferredContentSizeCategory"
+ "preferredFontForTextStyle:"
+ "removeFromSuperview"
+ "safeAreaLayoutGuide"
+ "secondaryLabelColor"
+ "setActive:"
+ "setActivityIndicatorViewStyle:"
+ "setAdjustsFontForContentSizeCategory:"
+ "setAlignment:"
+ "setAutoresizingMask:"
+ "setAxis:"
+ "setFont:"
+ "setObject:atIndexedSubscript:"
+ "setSpacing:"
+ "setText:"
+ "setTextColor:"
+ "stackView"
+ "startAccessingSecurityScopedResource"
+ "startAnimating"
+ "stopAccessingSecurityScopedResource"
+ "temporaryDirectory"
+ "traitCollection"
+ "v16@?0@\"NSError\"8"
+ "v32@?0@\"NSItemProvider\"8Q16^B24"
- "@32@0:8@16^@24"
- "B"
- "__completeRequestWithError:completion:"
- "_didLoadAttachments"
- "copy"
- "loadItemProvider:error:"
- "no input item found"
- "removeObject:"
```
