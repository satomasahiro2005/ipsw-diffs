## Books

> `/private/var/staged_system_apps/Books.app/Books`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e4660` | `0x7e66d8` | **`+0x2078`** |
| `__TEXT.__oslogstring` | `0x20b00` | `0x20f00` | **`+0x400`** |
| `__TEXT.__swift5_typeref` | `0x596b0` | `0x5939c` | **`-0x314`** |
| `__DATA.__data` | `0x2e5b0` | `0x2e700` | **`+0x150`** |
| `__DATA.__objc_const` | `0x56ea8` | `0x56f88` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x131b0` | `0x13290` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x17c90` | `0x17d24` | **`+0x94`** |
| `__TEXT.__eh_frame` | `0x16c9c` | `0x16d2c` | **`+0x90`** |
| `__TEXT.__const` | `0x409e0` | `0x40a60` | **`+0x80`** |
| `__DATA.__objc_data` | `0x1aa50` | `0x1aac0` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x1051c` | `0x10588` | **`+0x6c`** |
| `__TEXT.__objc_methname` | `0x72580` | `0x725e0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1a2d0` | `0x1a330` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x13ce4` | `0x13c94` | **`-0x50`** |
| `__DATA.__bss` | `0x3276c` | `0x3279c` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x11ce0` | `0x11d10` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x46b8` | `0x46e8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2c5c8` | `0x2c598` | **`-0x30`** |
| `__DATA_CONST.__cfstring` | `0xf120` | `0xf100` | **`-0x20`** |
| `__TEXT.__cstring` | `0x2cbc9` | `0x2cba9` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x427c0` | `0x427a0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x8e88` | `0x8ea0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x5fd0` | `0x5fe8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x15ed0` | `0x15ec0` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x30990` | `0x309a0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xa389` | `0xa399` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x5ed8` | `0x5ee0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1728` | `0x1730` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x92b0` | `0x92b8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1428` | `0x142c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x9cc` | `0x9d0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6647.0.0.0.0
+6655.0.0.0.0

-  Functions: 39882
-  Symbols:   2116
-  CStrings:  26080
+  Functions: 39914
+  Symbols:   2119
+  CStrings:  26086
Symbols:
+ _OBJC_CLASS_$_BKWindow
+ _OBJC_METACLASS_$_BKWindow
+ _OBJC_METACLASS_$_UIWindow
CStrings:
+ "About to delete all past results because of client state change (v%lu, extraConfig='%{public}@')"
+ "BKWindow"
+ "No prior client state - performing initial full index"
+ "[DRMTrace][open] %s %s request failed to %s computer (by DSID). %@"
+ "[DRMTrace][open] %s %s request failed to %s computer (by account name). %@"
+ "[DRMTrace][open] %s Beginning %{public}s"
+ "[DRMTrace][open] %s Successfully performed %{public}s by DSID"
+ "[DRMTrace][open] %s Successfully performed %{public}s by account name"
+ "[DRMTrace][open] Asset %@ did not open, error=%@ underlying=%@ retry=%{BOOL}d assetState=%ld isLocal=%{BOOL}d isCloud=%{BOOL}d isDownloading=%{BOOL}d logID=%{public}@.  Fetching scene controller"
+ "[DRMTrace][open] Attempting automatic reopen of asset %@ following auth"
+ "[DRMTrace][open] Attempting to authorize/refetch keys for user %{private}@ assetID=%@ logID=%{public}@"
+ "[DRMTrace][open] Finished automatic reopen of asset %@ following auth, error %@"
+ "[DRMTrace][open] audiobook error-leg domain=%{public}@ code=%ld refetchRequired=%{BOOL}d assetID=%@ logID=%{public}@"
+ "[DRMTrace][open] gate(audiobook): dsidZero=%{BOOL}d credentialEmpty=%{BOOL}d credential=%{private}@ assetID=%@ logID=%{public}@ assetState=%ld isLocal=%{BOOL}d isCloud=%{BOOL}d isDownloading=%{BOOL}d"
+ "[DRMTrace][open] minifiedFlowControllerHandleAssetPresentationError: Error refetching keybag: %@"
+ "[DRMTrace][open] perform(dsid): dsidZero=%{bool,public}d authorizeReason=keybagRefetch resolvedAccount=%{bool,public}d"
+ "_primaryViewWidth"
+ "arrangementView"
+ "cardStackTransitioningCoverHostDidEndTransition"
+ "credential"
+ "primaryArrangedView"
+ "primaryViewWidth"
+ "primaryViewWidthSubject"
+ "reindex pass complete (%lu requested, %lu covers pending retry, watermark=%{private}@)"
+ "reindex: fetched %lu asset(s) to index (full=%{BOOL}d, retry=%lu)"
- "%s %s request failed to %s computer (by DSID). %@"
- "%s %s request failed to %s computer (by account name). %@"
- "%s Beginning %s"
- "%s Successfully performed %s by DSID"
- "%s Successfully performed %s by account name"
- "@\"UIBarButtonItem\"16@0:8"
- "@\"UIBarButtonItem\"24@0:8@\"UIViewController<AEAssetViewController>\"16"
- "About to delete all past results because of client state change"
- "Asset %@ did not open, error=%@ retry=%{BOOL}d.  Fetching scene controller"
- "Attempting automatic reopen of asset %@ following auth"
- "Attempting to authorize/refetch keys for user %@"
- "BKPictureBookViewController"
- "Finished automatic reopen of asset %@ following auth, error %@"
- "_indexPathForCollection:"
- "_topToolbar"
- "_updatePreferredLayoutStyleWithSize:"
- "assetViewControllerMinifiedBarButtonItem:"
- "minifiedFlowControllerHandleAssetPresentationError: Error refetching keybag: %@"
- "minifiedPresenterBarButtonItem"
```
