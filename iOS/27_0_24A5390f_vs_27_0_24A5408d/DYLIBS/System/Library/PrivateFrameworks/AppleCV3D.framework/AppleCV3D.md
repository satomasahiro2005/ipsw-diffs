## AppleCV3D

> `/System/Library/PrivateFrameworks/AppleCV3D.framework/AppleCV3D`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ec328c` | `0x1ece274` | **`+0xafe8`** |
| `__TEXT.__cstring` | `0xb7822` | `0xb83f2` | **`+0xbd0`** |
| `__TEXT.__const` | `0x16a160` | `0x1696a0` | **`-0xac0`** |
| `__AUTH_CONST.__const` | `0x7c1e8` | `0x7c8e8` | **`+0x700`** |
| `__TEXT.__gcc_except_tab` | `0x107d70` | `0x108394` | **`+0x624`** |
| `__TEXT.__unwind_info` | `0x41c90` | `0x41f60` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x12c9b` | `0x12e9b` | **`+0x200`** |
| `__DATA_CONST.__const` | `0x3590` | `0x3650` | **`+0xc0`** |
| `__DATA.__bss` | `0x14138` | `0x141e8` | **`+0xb0`** |
| `__DATA.__data` | `0x8a28` | `0x8aa8` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x16d8` | `0x1728` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1ca0` | `0x1cc0` | **`+0x20`** |
| `__DATA.__common` | `0x2378` | `0x2368` | **`-0x10`** |

### Other Changes

```diff

-9.26.6.16.5
+9.26.7.9.0

-  Functions: 49604
-  Symbols:   2068
-  CStrings:  13772
+  Functions: 49712
+  Symbols:   2087
+  CStrings:  13822
Symbols:
+ __SparseGetOptionsFromNumericFactor_Double
+ __SparseRefactorLU_Double
+ __SparseRefactorQR_Double
+ __SparseRefactorSymmetric_Double
+ __ZNSt3__113basic_istreamIcNS_11char_traitsIcEEED0Ev
+ __ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEED0Ev
+ __ZNSt3__114basic_iostreamIcNS_11char_traitsIcEEED0Ev
+ __ZNSt3__114basic_iostreamIcNS_11char_traitsIcEEED1Ev
+ __ZTINSt3__113basic_istreamIcNS_11char_traitsIcEEEE
+ __ZTINSt3__113basic_ostreamIcNS_11char_traitsIcEEEE
+ __ZTINSt3__114basic_iostreamIcNS_11char_traitsIcEEEE
+ __ZThn16_NSt3__114basic_iostreamIcNS_11char_traitsIcEEED0Ev
+ __ZThn16_NSt3__114basic_iostreamIcNS_11char_traitsIcEEED1Ev
+ __ZTv0_n24_NSt3__113basic_istreamIcNS_11char_traitsIcEEED0Ev
+ __ZTv0_n24_NSt3__113basic_istreamIcNS_11char_traitsIcEEED1Ev
+ __ZTv0_n24_NSt3__113basic_ostreamIcNS_11char_traitsIcEEED0Ev
+ __ZTv0_n24_NSt3__113basic_ostreamIcNS_11char_traitsIcEEED1Ev
+ __ZTv0_n24_NSt3__114basic_iostreamIcNS_11char_traitsIcEEED0Ev
+ __ZTv0_n24_NSt3__114basic_iostreamIcNS_11char_traitsIcEEED1Ev
CStrings:
+ " (track_index.size="
+ "%s does not match that used for symbolic factorization stored in %s.\n"
+ ", track_ids.size="
+ ". Cannot find track of same ID in track index."
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleCV3D/library/VIO/DataSource/src/DataSample/OdometryTrajectorySampleUtil.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleCV3D/library/VIO/DataSource/src/DataSample/OdometryTrajectorySampleUtil.cpp:56"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleCV3D/library/VIO/DataSource/src/Stream/MessagePackSerializeStream.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleCV3D/library/VIO/DataSource/src/Stream/MessagePackSerializeStream.cpp:42"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleCV3D/library/VIO/DataSource/src/Stream/MessagePackSerializeStream.cpp:44"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleCV3D/library/VIO/DataSource/src/Stream/MessagePackSerializeStream.cpp:52"
+ "CM:Merge: hot merge vs visual reloc diff: %f m | %f rad | user %llu"
+ "Factored->symbolicFactorization"
+ "Factorization does not hold a completed matrix factorization.\n"
+ "Factorization does not hold a valid symbolic matrix factorization.\n"
+ "Failed to allocate workspace of size %ld."
+ "Failed to open file %s"
+ "FrontEndOdometryConfig.lpse_odometry_trajectory_path"
+ "Ill Conditioned Rotation"
+ "Invalid output stream."
+ "Matrix"
+ "MessagePackSerializeStream: Associated stream has reached end-of-file."
+ "MessagePackSerializeStream: Error has occurred on the associated stream."
+ "Non Finite State"
+ "Path for LPSE odometry trajectory output in msgpack format (empty = disabled)."
+ "Problem opening "
+ "VIO::MATH::CenterDataPolyFit: Ill-conditioned/singular normal matrix. Return 0 poly coeffs."
+ "[ClassifyAllPostBA] tracks=%u untri=%u outlier=%u inlier=%u smallRes=%u totalRes=%u\n"
+ "[LPSE] Failed to save trajectory to '%s'."
+ "[LPSE] Failed to save trajectory to '%s': %s."
+ "[LPSE] Saved {} poses to {}"
+ "filename != nullptr"
+ "ill-conditioned predicted rotation at %f"
+ "kAvgVergenceAngleCos"
+ "kHealthEstimate"
+ "kInitializedHealthily"
+ "kInlierTrackPercentage"
+ "kLatestStateTimestamp"
+ "kOldestStateIsStationary"
+ "kOldestStateVelocity"
+ "kRatioSmallResiduals"
+ "kShortTrackPercentage"
+ "kStepSize"
+ "kTotalNumberOfResiduals"
+ "kTotalNumberOfTracks"
+ "non-finite predicted state at %f"
+ "out_->good()"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::cv::CVImageBuffer<img::Format::Two16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::vio::mapping_types::MapAnalyticsMetricName::kLargeRotationDiffHotMergeAndVisualReloc]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::vio::mapping_types::MapAnalyticsMetricName::kLargeTranslationDiffBetweenHotMergeAndVisualReloc]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::vio::mapping_types::MapAnalyticsMetricName::kRotationDifferenceBetweenHotMergeAndVisualReloc]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::vio::mapping_types::MapAnalyticsMetricName::kTranslationDifferenceBetweenHotMergeAndVisualReloc]"
+ "{:.12f} {:.12f} {:.12f} {:.12f} {:.12f} {:.12f} {:.12f}\n"
- ". Cannot find track of same ID in track index.\n"
- "VIO::MATH::CenterDataPolyFit: High condition number.  Return 0 poly coeffs."
```
