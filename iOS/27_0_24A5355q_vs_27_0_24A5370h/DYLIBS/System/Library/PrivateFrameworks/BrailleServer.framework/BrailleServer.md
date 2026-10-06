## BrailleServer

> `/System/Library/PrivateFrameworks/BrailleServer.framework/BrailleServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf48e0` | `0xf4e0c` | **`+0x52c`** |
| `__TEXT.__eh_frame` | `0x53cc` | `0x53f8` | **`+0x2c`** |
| `__TEXT.__const` | `0x5638` | `0x5660` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x38c` | `0x378` | **`-0x14`** |
| `__DATA.__data` | `0x2590` | `0x25a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2e48` | `0x2e38` | **`-0x10`** |

### Other Changes

```diff

-455.1.1.0.0
+458.0.0.0.0

-  Functions: 3842
-  Symbols:   10040
+  Functions: 3836
+  Symbols:   10036
Symbols:
+ _$s13BrailleServer0A20AccessControlMessageOIeghy_BAACIeNghHgILy_TRScMTUTY1_
+ _$s13BrailleServer12PlanarWindowC17routingKeyHitTest9cellIndex20shouldPerformActionsAA07RoutingfG4TypeOSgSi_SbtFAiC5State33_FB6754137C144D03503B029BFC8702CCLLVzYuYTXEfU_
+ _$s13BrailleServer17TaskQueueInternal33_53DDD41B6106670812474FEE97FB5895LLC8activateScTyyts5NeverOGyFyyYacfU_TQ3_
+ _$s15Synchronization5MutexVy13BrailleServer12PlanarWindowC5State33_FB6754137C144D03503B029BFC8702CCLLVGWObTm
+ _$s15Synchronization5MutexVy13BrailleServer23FreedomScientificDriverV5StateVGWObTm
+ _$s15Synchronization5MutexVy13BrailleServer9HIDDriverC5StateVGWOb
+ _$s17BrailleFoundation0A14AccessResponseOIeghn_BAACIeNghHgILn_TRScMTUTY1_
+ _$sBA13BrailleServer0A20AccessControlMessageOIeNghHgILy_BAACIeNghHgILn_TRTQ0_
+ _$sBA13BrailleServer11DeviceStateC0A10Foundation18PhysicalPressInputOAD0A6StringVSgIeNghHgILgnr_BAAcfIIeNghHgILnnr_TRTQ0_
+ _$sBAIeNghHgIL_BAytIeNghHgILn_TRTQ0_
+ _$sBAIeNghHgIL_BAytIeNghHgILr_TRTQ0_
+ _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB22LegacySPPDriverWrapperCTG5TQ0_
+ _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9HIDDriverCTG5TQ0_
+ _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9SPPDriverCyAB017FreedomScientificD0V0F0VGTG5TQ0_
+ _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9SPPDriverCyAB04BaumD0V0F0VGTG5TQ0_
+ _$sIeghH_BAytIeNghHgILn_TRTY1_
+ _$sSay17BrailleFoundation0A6DeviceV2IDOGIeghHg_BAAFIeNghHgILn_TRTY1_
- _$s13BrailleServer12LayoutObjectVWOb
- _$s13BrailleServer12PlanarWindowC15RenderedElementVWObTm
- _$s13BrailleServer17TaskQueueInternal33_53DDD41B6106670812474FEE97FB5895LLC8activateScTyyts5NeverOGyFyyYacfU_TQ4_
- _$s13BrailleServer17TaskQueueInternal33_53DDD41B6106670812474FEE97FB5895LLC8activateScTyyts5NeverOGyFyyYacfU_TY3_
- _$sBA13BrailleServer0A20AccessControlMessageOIeNghHgILy_BAACIeNghHgILn_TRTQ1_
- _$sBA13BrailleServer0A20AccessControlMessageOIeNghHgILy_BAACIeNghHgILn_TRTY0_
- _$sBA13BrailleServer11DeviceStateC0A10Foundation18PhysicalPressInputOAD0A6StringVSgIeNghHgILgnr_BAAcfIIeNghHgILnnr_TRTQ1_
- _$sBA13BrailleServer11DeviceStateC0A10Foundation18PhysicalPressInputOAD0A6StringVSgIeNghHgILgnr_BAAcfIIeNghHgILnnr_TRTY0_
- _$sBAIeNghHgIL_BAytIeNghHgILn_TRTQ1_
- _$sBAIeNghHgIL_BAytIeNghHgILn_TRTY0_
- _$sBAIeNghHgIL_BAytIeNghHgILr_TRTQ1_
- _$sBAIeNghHgIL_BAytIeNghHgILr_TRTY0_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB22LegacySPPDriverWrapperCTG5TQ1_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB22LegacySPPDriverWrapperCTG5TY0_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9HIDDriverCTG5TQ1_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9HIDDriverCTG5TY0_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9SPPDriverCyAB017FreedomScientificD0V0F0VGTG5TQ1_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9SPPDriverCyAB017FreedomScientificD0V0F0VGTG5TY0_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9SPPDriverCyAB04BaumD0V0F0VGTG5TQ1_
- _$sBAq_xIeNghHgILnn_BAq__xtIeNghHgILn_s8SendableRz13BrailleServer6DriverR_r0_lTRAB11DeviceStateC_AB9SPPDriverCyAB04BaumD0V0F0VGTG5TY0_
- _$sSi6offset_13BrailleServer12PlanarWindowC15RenderedElementV7elementtWOh
```
