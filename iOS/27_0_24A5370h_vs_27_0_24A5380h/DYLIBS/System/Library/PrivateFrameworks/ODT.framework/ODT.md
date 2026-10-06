## ODT

> `/System/Library/PrivateFrameworks/ODT.framework/ODT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x522cf8` | `0x4ef2d0` | **`-0x33a28`** |
| `__TEXT.__gcc_except_tab` | `0x23d08` | `0x239ec` | **`-0x31c`** |
| `__TEXT.__eh_frame` | `0xd90` | `0xc20` | **`-0x170`** |
| `__TEXT.__const` | `0x2dca8` | `0x2db68` | **`-0x140`** |
| `__TEXT.__unwind_info` | `0xd350` | `0xd240` | **`-0x110`** |
| `__DATA.__common` | `0x80` | `0x120` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x1a370` | `0x1a408` | **`+0x98`** |
| `__DATA.__bss` | `0xe98` | `0xe28` | **`-0x70`** |
| `__TEXT.__cstring` | `0x11ca2` | `0x11cdb` | **`+0x39`** |
| `__AUTH_CONST.__auth_got` | `0xfd0` | `0xff0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x348` | `0x368` | **`+0x20`** |

### Other Changes

```diff

-24.6.0.0.0
+25.2.0.0.0

-  Functions: 10720
-  Symbols:   735
-  CStrings:  1675
+  Functions: 10674
+  Symbols:   743
+  CStrings:  1645
Symbols:
+ __ZNKSt3__119bad_expected_accessIvE4whatEv
+ __ZTINSt3__119bad_expected_accessIvEE
+ _e5rt_io_port_is_surface
+ _e5rt_io_port_retain_surface_desc
+ _e5rt_surface_desc_get_custom_row_strides
+ _e5rt_surface_desc_get_height
+ _e5rt_surface_desc_get_plane_count
+ _e5rt_surface_desc_get_width
+ _e5rt_surface_desc_release
- _cblas_strmm$NEWLAPACK
CStrings:
+ " : "
+ "(null)"
+ "-"
+ "NEON requires half_patch_width (chroma row) to be a multiple of 4"
+ "NEON requires patch height to be multiple of 4"
+ "NEON requires patch width to be multiple of 4"
+ "cameraIntrinsics_in0"
+ "cameraIntrinsics_in1"
+ "cameraIntrinsics_out0"
+ "cameraIntrinsics_out1"
+ "coords_0x"
+ "coords_1x"
+ "half_patch_width % 4 == 0"
+ "image_cb"
+ "image_cr"
+ "it != name_to_key.end()"
+ "radialDistortion0"
+ "radialDistortion1"
- " "
- " : %.*s"
- "%s: %s:%d"
- "1"
- "A"
- "B"
- "Columnwise"
- "Copy not supported yet."
- "DLASQ2"
- "E"
- "EPS"
- "Epsilon"
- "F"
- "Forward"
- "H"
- "O"
- "P"
- "Precision"
- "Q"
- "Rowwise"
- "SBDSQR"
- "SGEBD2"
- "SGEBRD"
- "SGELQ2"
- "SGELQF"
- "SGEQR2"
- "SGEQRF"
- "SGESVD"
- "SLASCL"
- "SLASQ1"
- "SLASQ2"
- "SLASR "
- "SLASRT"
- "SORG2R"
- "SORGBR"
- "SORGL2"
- "SORGLQ"
- "SORGQR"
- "SORM2R"
- "SORMBR"
- "SORML2"
- "SORMLQ"
- "SORMQR"
- "Safe minimum"
- "Unit"
- "V"
- "cblas_srot"
- "cblas_strmv"
```
