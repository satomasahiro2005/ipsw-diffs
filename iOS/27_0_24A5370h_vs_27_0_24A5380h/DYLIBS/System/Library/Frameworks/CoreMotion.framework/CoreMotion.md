## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1180` | `0x3f20` | **`+0x2da0`** |
| `__DATA_DIRTY.__objc_data` | `0x4380` | `0x15e0` | **`-0x2da0`** |
| `__TEXT.__text` | `0x3ac5fc` | `0x3ad4c0` | **`+0xec4`** |
| `__TEXT.__cstring` | `0x455b8` | `0x45640` | **`+0x88`** |
| `__TEXT.__oslogstring` | `0x2cf87` | `0x2d00c` | **`+0x85`** |
| `__AUTH_CONST.__const` | `0x14f50` | `0x14f98` | **`+0x48`** |
| `__DATA.__common` | `0x120` | `0xf8` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x61` | `0x89` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x13520` | `0x13540` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc9c4` | `0xc9e4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xb670` | `0xb690` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x1018` | `0x1028` | **`+0x10`** |
| `__TEXT.__const` | `0xc500` | `0xc510` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xd03c` | `0xd04c` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x3a48` | `0x3a50` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7e0` | `0x7e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5438` | `0x5440` | **`+0x8`** |

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Functions: 12337
-  Symbols:   1769
-  CStrings:  11046
+  Functions: 12347
+  Symbols:   1770
+  CStrings:  11056
Symbols:
+ _CMSidebandSensorFusionImuIndex
CStrings:
+ "-[CMMotionManager setSidebandSensorFusionEnable:measureLatency:imuIndex:withSnoopHandler:]"
+ "21:54:52"
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 242,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 237,invalid element %zu <= %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 243,invalid element %zu <= %zu."
+ "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 196,invalid row %zu > %zu."
+ "CMSidebandSensorFusionImuIndex"
+ "Jun 27 2026"
+ "[SidebandSensorFusion] requesting from framework,enabled,%{public}d,measureLatency,%{public}d,snoop,%{public}d,imuIndex,%{public}d"
+ "[SidebandSensorFusion] setIspDataHandler: imuIndex %{public}d out of range, device has %{public}d IMUs; ignoring"
+ "accelBias0"
+ "accelBias1"
+ "buttonPress"
+ "deltaPositionAltimeterZ"
+ "down"
+ "usage"
+ "usagePage"
+ "void CLIspDataVisitor::setIspDataHandler(CMSidebandSensorFusionSnoopHandler, uint8_t)"
+ "yOffset"
- "-[CMMotionManager setSidebandSensorFusionEnable:measureLatency:withSnoopHandler:]"
- "00:06:48"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 240,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 235,invalid element %zu <= %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 241,invalid element %zu <= %zu."
- "Assertion failed: row < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Oscar/Math/CMFactoredMatrix.h, line 194,invalid row %zu > %zu."
- "Jun 16 2026"
- "[SidebandSensorFusion] requesting from framework,enabled,%{public}d,measureLatency,%{public}d,snoop,%{public}d"
- "void CLIspDataVisitor::setIspDataHandler(CMSidebandSensorFusionSnoopHandler)"
```
