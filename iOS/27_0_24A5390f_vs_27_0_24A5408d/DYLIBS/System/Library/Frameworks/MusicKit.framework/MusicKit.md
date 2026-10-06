## MusicKit

> `/System/Library/Frameworks/MusicKit.framework/MusicKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53f1c8` | `0x5414b0` | **`+0x22e8`** |
| `__TEXT.__cstring` | `0x10f62` | `0x110b2` | **`+0x150`** |
| `__TEXT.__const` | `0x54be4` | `0x54d24` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x18908` | `0x18a08` | **`+0x100`** |
| `__DATA.__data` | `0xa3a8` | `0xa498` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0xbf6b` | `0xc03b` | **`+0xd0`** |
| `__DATA_DIRTY.__data` | `0xc240` | `0xc300` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x274d8` | `0x27598` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x7050` | `0x70d0` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0xe890` | `0xe908` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0x2a830` | `0x2a880` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1508` | `0x1558` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x224c` | `0x229c` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b18` | `0x1b58` | **`+0x40`** |
| `__DATA.__bss` | `0x61d10` | `0x61d40` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x121ec` | `0x12204` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2074` | `0x2088` | **`+0x14`** |
| `__TEXT.__constg_swiftt` | `0xbf14` | `0xbf24` | **`+0x10`** |
| `__DATA.__common` | `0x188` | `0x190` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-4026.100.89.0.0
+4026.110.2.0.0

-  Functions: 44255
-  Symbols:   11764
-  CStrings:  1754
+  Functions: 44301
+  Symbols:   11777
+  CStrings:  1763
Symbols:
+ -[MusicKit_SoftLinking_CoverArtworkDataSource _loadRepresentationForArtworkCatalog:completionHandler:]
+ -[NSObject(MusicKit_SoftLinking_MPIdentifierSet) musicKit_lyricsAdamID]
+ -[NSObject(MusicKit_SoftLinking_MPModelObject_Artwork) musicKit_editorialArtworkCatalogsForProperty:]
+ __CATEGORY_INSTANCE_METHODS_NSBundle_$_MusicKit
+ __CATEGORY_NSBundle_$_MusicKit
+ __CATEGORY_PROPERTIES_NSBundle_$_MusicKit
+ ___118+[MusicKit_SoftLinking_MPModelObject _createUnderlyingModelObjectWithIdentifierSet:modelObjectType:storageDictionary:]_block_invoke_4
+ ___118+[MusicKit_SoftLinking_MPModelObject _createUnderlyingModelObjectWithIdentifierSet:modelObjectType:storageDictionary:]_block_invoke_5
+ ___block_descriptor_40_e8_32s_e43_v32?0"NSString"8"MPArtworkCatalog"16^B24ls32l8
+ ___block_descriptor_40_e8_32s_e44_"NSMutableDictionary"16?0"MPModelObject"8ls32l8
+ ___getMPModelPropertyRadioStationSubscriptionRequiredSymbolLoc_block_invoke
+ ___swift_memcpy369_8
+ ___swift_memcpy400_8
+ _getMPModelPropertyRadioStationSubscriptionRequiredSymbolLoc.ptr
+ _getMPModelStoreBrowseContentItemClass
+ _symbolic _____ySS_____y_____GG s17_NativeDictionaryV 8MusicKit14CloudAttributeV AC0E7ArtworkV
+ _symbolic yyYbc
- _OUTLINED_FUNCTION_2196
- ___swift_memcpy353_8
- ___swift_memcpy360_8
- ___swift_memcpy384_8
CStrings:
+ "@\"NSMutableDictionary\"16@?0@\"MPModelObject\"8"
+ "MPModelPropertyAlbumEditorialArtworks"
+ "MPModelPropertyPlaylistEditorialArtworks"
+ "MPModelPropertyRadioStationSubscriptionRequired"
+ "Unexpected type: "
+ "campo_snippets"
+ "langthem"
+ "requiresSubscription"
+ "v32@?0@\"NSString\"8@\"MPArtworkCatalog\"16^B24"
```
