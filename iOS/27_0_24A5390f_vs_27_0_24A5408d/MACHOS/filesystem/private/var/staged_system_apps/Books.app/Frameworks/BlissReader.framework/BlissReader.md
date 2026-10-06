## BlissReader

> `/private/var/staged_system_apps/Books.app/Frameworks/BlissReader.framework/BlissReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a3a3c` | `0x2a4890` | **`+0xe54`** |
| `__TEXT.__objc_methname` | `0x8e157` | `0x8e3b3` | **`+0x25c`** |
| `__TEXT.__oslogstring` | `0xc0e` | `0xe42` | **`+0x234`** |
| `__TEXT.__objc_stubs` | `0x60780` | `0x60960` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x498cc` | `0x49984` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x5b50` | `0x5bf4` | **`+0xa4`** |
| `__DATA.__objc_selrefs` | `0x1ed88` | `0x1ee20` | **`+0x98`** |
| `__DATA.__objc_const` | `0x7cb20` | `0x7cbb0` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x26ac0` | `0x26b20` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x15fc8` | `0x16018` | **`+0x50`** |
| `__TEXT.__cstring` | `0x36a16` | `0x36a66` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xdf20` | `0xdf70` | **`+0x50`** |
| `__TEXT.__const` | `0xbe10` | `0xbe40` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xaf` | `0x93` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x1c00` | `0x1c10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3e48` | `0x3e54` | **`+0xc`** |
| `__TEXT.__swift5_capture` | `0x8c` | `0x88` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6647.0.0.0.0
+6655.0.0.0.0

-  Functions: 22731
-  Symbols:   7554
-  CStrings:  32253
+  Functions: 22749
+  Symbols:   7556
+  CStrings:  32289
Symbols:
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_UIDeferredMenuElement
+ _swift_release_x23
- _swift_release_x25
CStrings:
+ "@\"UIMenu\"16@?0@\"UIMenu\"8"
+ "Menu"
+ "MenuButton"
+ "T@\"UIBarButtonItem\",&,N,V_readerMenuButtonItem"
+ "T@\"UIView\",&,N,V_emptyInputView"
+ "TB,N,V_readerMenuPresented"
+ "[DRMTrace][open] -> silent keybag refetch dsid=%{private}@ connected=%{BOOL}d"
+ "[DRMTrace][open] Auth needed due to non-existing account for asset at url, username: %@ -- %@"
+ "[DRMTrace][open] Error authenticating account: %@ -- %@"
+ "[DRMTrace][open] Error refetching bag for dsid: %@ -- %@"
+ "[DRMTrace][open] bliss DRM validate failed; domain=%{public}@ code=%ld"
+ "[DRMTrace][open] bliss identity: usernamePresent=%{BOOL}d dsid=%{private}@"
+ "[DRMTrace][open] bliss interactive auth result ok=%{BOOL}d err=%{public}@"
+ "[DRMTrace][open] bliss open failed err=%{public}@ underlying=%{public}@ refetchRequired=%{BOOL}d canRefetch=%{BOOL}d"
+ "[DRMTrace][open] gate(bliss): accountNil=%{BOOL}d credentialEmpty=%{BOOL}d credential=%{private}@"
+ "_contextMenuInteraction"
+ "_emptyInputView"
+ "_readerMenuButtonItem"
+ "_readerMenuPresented"
+ "_scrubberFrameHorizontalOriginY"
+ "contentInsetSafeAreaEdgesToSubtract"
+ "elementWithUncachedProvider:"
+ "ellipsis"
+ "emptyInputView"
+ "footerToolbarHeight"
+ "initWithImage:style:target:action:"
+ "menuRepresentation"
+ "menuWithTitle:children:"
+ "p_buildReaderMenu"
+ "p_readerMenuActuallyVisible"
+ "p_readerMenuChildren"
+ "p_readerMenuElementForBarButtonItem:"
+ "readerMenuButtonItem"
+ "readerMenuPresented"
+ "scrubberHeight"
+ "setEmptyInputView:"
+ "setMenu:"
+ "setReaderMenuButtonItem:"
+ "setReaderMenuPresented:"
+ "updateVisibleMenuWithBlock:"
+ "v16@?0@?<v@?@\"NSArray\">8"
- "Auth needed due to non-existing account for asset at url, username: %@ -- %@"
- "Error authenticating account: %@ -- %@"
- "Error refetching bag for dsid: %@ -- %@"
- "assetViewControllerMinifiedBarButtonItem:"
- "leftBarButtonItem"
```
