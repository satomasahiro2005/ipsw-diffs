## AudioCodecs

> `/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6967ec` | `0x69689c` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x1bbc3` | `0x1bc49` | **`+0x86`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-  Functions: 9826
+  Functions: 9827

-  CStrings:  3599
+  CStrings:  3600
Functions:
~ __ZN14APACHOADecoder10InitializeERK11ACParamListN4apac12observer_ptrINS3_10IASCConfigEEE : 7448 -> 7552
+ sub_1bd17e528
~ __ZN17HOASpatialDecoder11DeserializeER16TBitstreamReaderIjE : 6516 -> 6580
CStrings:
+ "%25s:%-5d  Failed to initialize: mNumHOAcoeffs exceeds kMaxNumSCs_DynSelSCs4EachSB array dimension in HOASpatialDecoder::Initialize()"
+ "17:02:43"
- "22:15:45"
```
