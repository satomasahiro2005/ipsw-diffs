## NTKCustomization

> `/System/Library/AccessibilityBundles/NTKCustomization.axbundle/NTKCustomization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3624` | `0x2e93` | **`-0x791`** |
| `__DATA_CONST.__cfstring` | `0x3da0` | `0x3680` | **`-0x720`** |
| `__TEXT.__text` | `0xf608` | `0xf1ac` | **`-0x45c`** |
| `__DATA.__data` | `0x1a8` | `—` | **`-0x1a8`** |
| `__DATA.__objc_const` | `0x3e78` | `0x3d58` | **`-0x120`** |
| `__DATA.__objc_data` | `0x2260` | `0x21c0` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x25cd` | `0x2569` | **`-0x64`** |
| `__TEXT.__objc_methlist` | `0x18cc` | `0x187c` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x11be` | `0x117c` | **`-0x42`** |
| `__TEXT.__objc_stubs` | `0x1da0` | `0x1d60` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0xa80` | `0xa68` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x370` | `0x360` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x638` | `0x628` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x39c` | `0x390` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x198` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1029.0.0.0.0
+1032.0.0.0.0

-  Functions: 531
-  Symbols:   1534
-  CStrings:  912
+  Functions: 525
+  Symbols:   1514
+  CStrings:  852
Symbols:
+ GCC_except_table220
+ GCC_except_table222
+ GCC_except_table257
+ GCC_except_table282
+ GCC_except_table288
+ GCC_except_table294
+ GCC_except_table356
+ GCC_except_table491
+ GCC_except_table499
+ GCC_except_table521
- +[NTKVideoListingAccessibility _accessibilityPerformValidations:]
- +[NTKVideoListingAccessibility(SafeCategory) safeCategoryBaseClass]
- +[NTKVideoListingAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[NTKClockViewControllerAccessibility celebrationViewControllerStartedAnimation:]
- -[NTKVideoListingAccessibility accessibilityLabel]
- GCC_except_table226
- GCC_except_table232
- GCC_except_table261
- GCC_except_table286
- GCC_except_table296
- GCC_except_table299
- GCC_except_table361
- GCC_except_table503
- GCC_except_table505
- GCC_except_table527
- _AccessibilityClockFaceVideoDescription
- _OBJC_CLASS_$_NTKVideoListingAccessibility
- _OBJC_CLASS_$___NTKVideoListingAccessibility_super
- _OBJC_METACLASS_$_NTKVideoListingAccessibility
- _OBJC_METACLASS_$___NTKVideoListingAccessibility_super
- _UIAccessibilityAnnouncementNotification
- __OBJC_$_CLASS_METHODS_NTKVideoListingAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_NTKVideoListingAccessibility
- __OBJC_CLASS_RO_$_NTKVideoListingAccessibility
- __OBJC_CLASS_RO_$___NTKVideoListingAccessibility_super
- __OBJC_METACLASS_RO_$_NTKVideoListingAccessibility
- __OBJC_METACLASS_RO_$___NTKVideoListingAccessibility_super
- ___107-[NTKFaceLibraryViewControllerAccessibility _accessibilityLabelForPageAtIndex:forPageScrollViewController:]_block_invoke_2
- _objc_msgSend$safeValueForKeyPath:
- _objc_msgSend$validateClass:hasProperty:withType:
CStrings:
- "NCECelebration"
- "NCEClockCelebrationViewController"
- "NCEFireVector"
- "NTKBlackcombFaceViewAccessibility"
- "NTKVideoListing"
- "__NTKVideoListingAccessibility_super"
- "_addableFaceCollection"
- "_titleForAddFacePageAtIndex:"
- "butterfly.video.announcement.Amphitryon"
- "butterfly.video.announcement.Apallonia"
- "butterfly.video.announcement.Atlas"
- "butterfly.video.announcement.Beatifica"
- "butterfly.video.announcement.Blumei"
- "butterfly.video.announcement.Dido"
- "butterfly.video.announcement.Doubledayi"
- "butterfly.video.announcement.Excelsior"
- "butterfly.video.announcement.Hypermnestra"
- "butterfly.video.announcement.Idaeoides"
- "butterfly.video.announcement.Iorquinianus"
- "butterfly.video.announcement.Lechenaulti"
- "butterfly.video.announcement.Leucippe"
- "butterfly.video.announcement.Limborgii"
- "butterfly.video.announcement.Luna"
- "butterfly.video.announcement.Menelaus"
- "butterfly.video.announcement.Myrina"
- "butterfly.video.announcement.Paradisea"
- "butterfly.video.announcement.Rhadama"
- "butterfly.video.announcement.Ripheus"
- "butterfly.video.announcement.Rurina"
- "butterfly.video.announcement.Sangaris"
- "butterfly.video.announcement.Sylvia"
- "butterfly.video.announcement.Timorensis"
- "butterfly.video.announcement.Weiskei"
- "celebration"
- "celebration.balloons"
- "celebration.fireworks"
- "celebration.sparkles"
- "celebrationViewControllerStartedAnimation:"
- "com.apple.watch.celebrations.balloons"
- "com.apple.watch.celebrations.fireworks"
- "com.apple.watch.celebrations.sparkles"
- "currentCelebration"
- "currentCelebration.celebration"
- "flower.video.announcement.Chrysanthemum"
- "flower.video.announcement.Gardenia"
- "flower.video.announcement.PinkDahlia"
- "flower.video.announcement.PinkPeony"
- "flower.video.announcement.PurplePassion"
- "flower.video.announcement.WhiteNigella"
- "flower.video.announcement.Wildflower"
- "flower.video.announcement.YellowPoppy"
- "jellyfish.video.announcement.Blueblubber"
- "jellyfish.video.announcement.Cnidaria"
- "jellyfish.video.announcement.LionsMane"
- "jellyfish.video.announcement.Moon"
- "jellyfish.video.announcement.Nettle"
- "jellyfish.video.announcement.RootMouth"
- "safeValueForKeyPath:"
- "validateClass:hasProperty:withType:"
- "variant"
```
