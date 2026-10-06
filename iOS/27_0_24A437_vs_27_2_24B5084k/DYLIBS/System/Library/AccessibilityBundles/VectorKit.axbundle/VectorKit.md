## VectorKit

> `/System/Library/AccessibilityBundles/VectorKit.axbundle/VectorKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27ff8` | `0x29664` | **`+0x166c`** |
| `__AUTH_CONST.__cfstring` | `0x2780` | `0x2be0` | **`+0x460`** |
| `__TEXT.__gcc_except_tab` | `0x4e48` | `0x510c` | **`+0x2c4`** |
| `__TEXT.__cstring` | `0x238b` | `0x24d8` | **`+0x14d`** |
| `__DATA_CONST.__objc_selrefs` | `0x2168` | `0x2210` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x1340` | `0x13c0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2b90` | `0x2bf0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x8c0` | `0x8e8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x5b0` | `0x5b8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 881
-  Symbols:   2024
-  CStrings:  401
+  Functions: 894
+  Symbols:   2049
+  CStrings:  436
Symbols:
+ -[VKMapViewAccessibility _axMapAltitude]
+ -[VKMapViewAccessibility _axMapAutomationValue]
+ -[VKMapViewAccessibility _axMapCameraDistance]
+ -[VKMapViewAccessibility _axMapCameraValue]
+ -[VKMapViewAccessibility _axMapCenterValue]
+ -[VKMapViewAccessibility _axMapPitch]
+ -[VKMapViewAccessibility _axMapRegionCorners:]
+ -[VKMapViewAccessibility _axMapRegionIgnoringEdgeInsets:]
+ -[VKMapViewAccessibility _axMapRegionValue:]
+ GCC_except_table540
+ GCC_except_table544
+ GCC_except_table545
+ GCC_except_table546
+ GCC_except_table547
+ GCC_except_table551
+ GCC_except_table555
+ GCC_except_table561
+ GCC_except_table573
+ GCC_except_table575
+ GCC_except_table576
+ GCC_except_table577
+ GCC_except_table579
+ GCC_except_table580
+ GCC_except_table582
+ GCC_except_table583
+ GCC_except_table594
+ GCC_except_table599
+ GCC_except_table600
+ GCC_except_table601
+ GCC_except_table603
+ GCC_except_table604
+ GCC_except_table606
+ GCC_except_table620
+ GCC_except_table621
+ GCC_except_table622
+ GCC_except_table623
+ GCC_except_table624
+ GCC_except_table625
+ GCC_except_table644
+ GCC_except_table645
+ GCC_except_table646
+ GCC_except_table660
+ GCC_except_table665
+ GCC_except_table666
+ GCC_except_table676
+ GCC_except_table677
+ GCC_except_table680
+ GCC_except_table681
+ GCC_except_table682
+ GCC_except_table683
+ GCC_except_table684
+ GCC_except_table686
+ GCC_except_table687
+ GCC_except_table688
+ GCC_except_table719
+ GCC_except_table723
+ GCC_except_table748
+ GCC_except_table749
+ GCC_except_table750
+ GCC_except_table752
+ GCC_except_table753
+ GCC_except_table787
+ GCC_except_table788
+ GCC_except_table789
+ GCC_except_table817
+ GCC_except_table824
+ GCC_except_table826
+ GCC_except_table827
+ GCC_except_table828
+ GCC_except_table829
+ GCC_except_table832
+ GCC_except_table844
+ GCC_except_table850
+ GCC_except_table851
+ GCC_except_table854
+ GCC_except_table855
+ GCC_except_table856
+ GCC_except_table859
+ GCC_except_table860
+ GCC_except_table861
+ GCC_except_table862
+ GCC_except_table865
+ GCC_except_table866
+ GCC_except_table882
+ _OBJC_CLASS_$_NSDecimalNumber
+ __ZL18AXMapRoundedNumberdi
+ ___37-[VKMapViewAccessibility _axMapPitch]_block_invoke
+ ___40-[VKMapViewAccessibility _axMapAltitude]_block_invoke
+ ___46-[VKMapViewAccessibility _axMapCameraDistance]_block_invoke
+ ___57-[VKMapViewAccessibility _axMapRegionIgnoringEdgeInsets:]_block_invoke
+ ___block_descriptor_49_ea8_32s40r_e5_v8?0lr40l8s32l8
+ _fmod
- -[VKMapViewAccessibility _axMapStyleAutomationValue]
- GCC_except_table541
- GCC_except_table550
- GCC_except_table552
- GCC_except_table556
- GCC_except_table557
- GCC_except_table558
- GCC_except_table560
- GCC_except_table564
- GCC_except_table566
- GCC_except_table568
- GCC_except_table586
- GCC_except_table587
- GCC_except_table588
- GCC_except_table590
- GCC_except_table593
- GCC_except_table607
- GCC_except_table608
- GCC_except_table609
- GCC_except_table611
- GCC_except_table612
- GCC_except_table631
- GCC_except_table632
- GCC_except_table633
- GCC_except_table634
- GCC_except_table635
- GCC_except_table639
- GCC_except_table640
- GCC_except_table649
- GCC_except_table650
- GCC_except_table651
- GCC_except_table654
- GCC_except_table655
- GCC_except_table656
- GCC_except_table657
- GCC_except_table658
- GCC_except_table673
- GCC_except_table706
- GCC_except_table710
- GCC_except_table735
- GCC_except_table736
- GCC_except_table737
- GCC_except_table739
- GCC_except_table740
- GCC_except_table774
- GCC_except_table775
- GCC_except_table776
- GCC_except_table796
- GCC_except_table797
- GCC_except_table798
- GCC_except_table800
- GCC_except_table802
- GCC_except_table803
- GCC_except_table804
- GCC_except_table805
- GCC_except_table806
- GCC_except_table807
- GCC_except_table808
- GCC_except_table812
- GCC_except_table814
- GCC_except_table837
- GCC_except_table839
- GCC_except_table840
- GCC_except_table841
- GCC_except_table842
- GCC_except_table843
- GCC_except_table869
CStrings:
+ "%.*f"
+ "GEOLatLng"
+ "GEOMapRegion"
+ "VKCameraController"
+ "altitude"
+ "camera"
+ "cameraController"
+ "center"
+ "corners"
+ "distanceFromCenterCoordinate"
+ "east"
+ "eastLng"
+ "fullRegion"
+ "hasEastLng"
+ "hasNorthLat"
+ "hasSouthLat"
+ "hasWestLng"
+ "lat"
+ "latSpan"
+ "lng"
+ "lon"
+ "lonSpan"
+ "mapRegion"
+ "mapRegionIgnoringEdgeInsets"
+ "north"
+ "northLat"
+ "pitch"
+ "region"
+ "south"
+ "southLat"
+ "vertexs"
+ "west"
+ "westLng"
+ "yaw"
+ "zoom"
```
