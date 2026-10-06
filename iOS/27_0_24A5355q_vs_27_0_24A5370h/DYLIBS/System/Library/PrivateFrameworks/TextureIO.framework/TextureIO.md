## TextureIO

> `/System/Library/PrivateFrameworks/TextureIO.framework/TextureIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x99c28` | `0x9a6d4` | **`+0xaac`** |

### Other Changes

```text
Functions:
~ -[TXRArrayElement copyWithZone:] : 368 -> 364
~ -[TXRMipmapLevel copyWithZone:] : 368 -> 364
~ -[TXRTexture copyWithZone:] : 380 -> 376
~ __Z22fastConvertWithOptionsILb1ELb1EEbDv3_j14TXRPixelFormatmmPvS1_mmS2_ : 168452 -> 168864
~ __Z22fastConvertWithOptionsILb1ELb0EEbDv3_j14TXRPixelFormatmmPvS1_mmS2_ : 132388 -> 133856
~ __Z22fastConvertWithOptionsILb0ELb1EEbDv3_j14TXRPixelFormatmmPvS1_mmS2_ : 153284 -> 154112
~ __Z22fastConvertWithOptionsILb0ELb0EEbDv3_j14TXRPixelFormatmmPvS1_mmS2_ : 120500 -> 120548
~ +[TXRAssetCatalogParser exportSet:location:error:] : 3160 -> 3152
~ +[TXRParserKTX handlesData:] : 156 -> 152
~ -[TXRParserKTX determineFormatFromType:format:internalFormat:baseInternalFormat:] : 588 -> 596
~ +[TXRParserKTX exportTexture:url:error:] : 2464 -> 2480
~ _slowConvert : 8860 -> 8836
```
