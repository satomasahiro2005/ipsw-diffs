## AppleKeyStore

> `/System/Library/PrivateFrameworks/AppleKeyStore.framework/AppleKeyStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58558` | `0x62958` | **`+0xa400`** |
| `__TEXT.__eh_frame` | `0x1a20` | `0x1d30` | **`+0x310`** |
| `__TEXT.__swift5_typeref` | `0x794` | `0x9ac` | **`+0x218`** |
| `__DATA.__data` | `0x1320` | `0x1478` | **`+0x158`** |
| `__TEXT.__const` | `0x10ee3` | `0x11013` | **`+0x130`** |
| `__TEXT.__cstring` | `0x32df` | `0x33ef` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x1650` | `0x1738` | **`+0xe8`** |
| `__AUTH_CONST.__auth_got` | `0xc00` | `0xcb0` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x16f6` | `0x1744` | **`+0x4e`** |
| `__TEXT.__swift5_reflstr` | `0xaa8` | `0xab8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1174` | `0x1180` | **`+0xc`** |

### Other Changes

```diff

-2369.0.0.0.7
+2383.0.6.0.1

-  Functions: 2761
-  Symbols:   2596
-  CStrings:  740
+  Functions: 2829
+  Symbols:   2627
+  CStrings:  747
Symbols:
+ _CTParseLeafSPKI
+ _swift_coroFrameAlloc
+ _swift_release_x8
+ _symbolic Sny_____ySi_GG 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV
+ _symbolic Sny_____y______GG 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt32V
+ _symbolic Sny_____y______GG 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt64V
+ _symbolic _____ySiG 17SwiftASN1Internal22IntegerBytesCollectionV
+ _symbolic _____ySi_G 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV
+ _symbolic _____ySi_G5lower_AB5uppert 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV
+ _symbolic _____ySi_GSg 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV
+ _symbolic _____y_____G 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt32V
+ _symbolic _____y_____G 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt64V
+ _symbolic _____y_____G s10ArraySliceV s5UInt8V
+ _symbolic _____y______G 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt32V
+ _symbolic _____y______G 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt64V
+ _symbolic _____y______G5lower_AC5uppert 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt32V
+ _symbolic _____y______G5lower_AC5uppert 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt64V
+ _symbolic _____y______GSg 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt32V
+ _symbolic _____y______GSg 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt64V
+ _symbolic _____y______G_Sit SR8IteratorV s5UInt8V
+ _symbolic _____y_____ySiGG s5SliceV 17SwiftASN1Internal22IntegerBytesCollectionV
+ _symbolic _____y_____ySi_GG s16PartialRangeFromV 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV
+ _symbolic _____y_____y_____GG s16IndexingIteratorV 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt32V
+ _symbolic _____y_____y_____GG s16IndexingIteratorV 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt64V
+ _symbolic _____y_____y_____GG s5SliceV 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt32V
+ _symbolic _____y_____y_____GG s5SliceV 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt64V
+ _symbolic _____y_____y______GG s16PartialRangeFromV 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt32V
+ _symbolic _____y_____y______GG s16PartialRangeFromV 17SwiftASN1Internal22IntegerBytesCollectionV5IndexV s6UInt64V
+ _symbolic _____y_____y_____ySiGGG s16IndexingIteratorV s5SliceV 17SwiftASN1Internal22IntegerBytesCollectionV
+ _symbolic _____y_____y_____y_____GGG s16IndexingIteratorV s5SliceV 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt32V
+ _symbolic _____y_____y_____y_____GGG s16IndexingIteratorV s5SliceV 17SwiftASN1Internal22IntegerBytesCollectionV s6UInt64V
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "INTEGER encoded with constructed encoding"
+ "INTEGER encoded with top bit set!"
+ "INTEGER encoded with zero bytes"
+ "INTEGER not encoded in fewest number of octets"
+ "SwiftASN1Internal/ASN1Integer.swift"
+ "generate_wrapping_key_curve25519"
```
