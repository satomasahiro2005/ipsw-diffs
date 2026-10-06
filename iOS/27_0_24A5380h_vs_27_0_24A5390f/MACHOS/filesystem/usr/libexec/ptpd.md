## ptpd

> `/usr/libexec/ptpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x224f0` | `0x22818` | **`+0x328`** |
| `__DATA.__objc_const` | `0x25d8` | `0x26c8` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x4e95` | `0x4f63` | **`+0xce`** |
| `__TEXT.__cstring` | `0x252d` | `0x259a` | **`+0x6d`** |
| `__DATA_CONST.__cfstring` | `0x3200` | `0x3260` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1a30` | `0x1a80` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x4160` | `0x41a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1600` | `0x1628` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3e0` | `0x408` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x280` | `0x284` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-2114.0.0.0.0
+2116.0.0.0.0

-  Functions: 610
+  Functions: 615

-  CStrings:  1577
+  CStrings:  1588
CStrings:
+ "%@\n%@"
+ "Stopping group notifications for storage 0x%x."
+ "Storage torn down -- not re-arming group notifications."
+ "T@\"NSString\",?,R,C,N"
+ "T@\"NSString\",C,N,V_mediaItemIdentifier"
+ "U"
+ "_mediaItemIdentifier"
+ "cameraFileWithAssetIdentifier:"
+ "mediaItemIdentifier"
+ "mediaItemIdentifierForAsset:"
+ "mediaItemWithIdentifier:"
+ "setMediaItemIdentifier:"
+ "stopGroupNotifications"
- "T"
- "objectMatchingAssetHandle:"
```
