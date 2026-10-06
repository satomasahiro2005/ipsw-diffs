## Trip

> `/Applications/Trip.app/Trip`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x2fc4` | `0x32d4` | **`+0x310`** |
| `__TEXT.__text` | `0x3b9f8` | `0x3bcdc` | **`+0x2e4`** |
| `__TEXT.__objc_methtype` | `0xe63` | `0xd1b` | **`-0x148`** |
| `__DATA.__bss` | `0x1c58` | `0x1d58` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x48c` | `0x38c` | **`-0x100`** |
| `__TEXT.__cstring` | `0xd95` | `0xe77` | **`+0xe2`** |
| `__DATA.__data` | `0x32d0` | `0x3370` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x9e0` | `0x940` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x1b50` | `0x1ac0` | **`-0x90`** |
| `__DATA.__objc_data` | `0x8b0` | `0x830` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x1598` | `0x1614` | **`+0x7c`** |
| `__DATA_CONST.__const` | `0x1518` | `0x1590` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x65c` | `0x5f4` | **`-0x68`** |
| `__TEXT.__swift5_reflstr` | `0xa75` | `0xad5` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x5c8` | `0x578` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xc38` | `0xc84` | **`+0x4c`** |
| `__TEXT.__swift5_typeref` | `0x7672` | `0x76ba` | **`+0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x8d0` | `0x910` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1ec0` | `0x1f00` | **`+0x40`** |
| `__DATA.__objc_const` | `0x1788` | `0x1768` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0xf68` | `0xf88` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x2b8` | `0x2d0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x90` | `0x80` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x393` | `0x383` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xb78` | `0xb68` | **`-0x10`** |
| `__DATA.__common` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x40` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xd4` | `0xd8` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xcc` | `0xd0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-334.0.0.0.0
+337.2.0.0.0

-  - /usr/lib/swift/libswiftCarPlay.dylib

-  Functions: 1120
-  Symbols:   926
-  CStrings:  474
+  Functions: 1144
+  Symbols:   929
+  CStrings:  461
Symbols:
+ _$s10CAFCombine17CAFTripObservableC9sortOrders5UInt8VvgTj
+ _$s10CAFCombine23CAFCarManagerObservableC8observedSo0bC0Cvg
+ _$s13CarAssetUtils21CAUAppUIConfigurationV17TripConfigurationV18tripInfoCardHiddenSbvg
+ _$s13CarAssetUtils21CAUAppUIConfigurationV17TripConfigurationV23tripFlattensCardEntriesSbvg
+ _$s14CarPlayAssetUI21CarouselConfigurationV14AnimationStyleO11fadeThroughyA2EmFWC
+ _$s14CarPlayAssetUI21CarouselConfigurationV14AnimationStyleOMn
+ _$s14CarPlayAssetUI21CarouselConfigurationV5style9direction14platterPadding17alwaysHidePlatter14animationStyle29decorationsVisibilityDuration0pqR8ByItemID15hidePageControlA2C0eO0O_AC15ScrollDirectionO12CoreGraphics7CGFloatVSbAC09AnimationO0OSdSDySSSdGSbtcfC
+ _$s5CAFUI14CAFTripEntriesV5countSivg
+ _$s5CAFUI14CAFTripEntriesV5kindsSayAA0B8CardKindOGvg
+ _$s5CAFUI14CAFTripEntriesVMn
+ _$s5CAFUI15CAFTripCardKindO10infoEnergyyAC10CAFCombine30CAFEnergyConsumptionObservableC_AE011CAFOdometerJ0CSgtcACmFWC
+ _$s5CAFUI15CAFTripCardKindO18standaloneOdometeryAC10CAFCombine21CAFOdometerObservableC_tcACmFWC
+ _$s5CAFUI15CAFTripCardKindO4tripyAC10CAFCombine0B10ObservableC_AE011CAFOdometerG0CtcACmFWC
+ _$s5CAFUI15CAFTripCardKindO7variantSSvg
+ _$s5CAFUI15CAFTripCardKindO8infoFuelyAC10CAFCombine28CAFFuelConsumptionObservableC_AE011CAFOdometerJ0CSgtcACmFWC
+ _$s5CAFUI15CAFTripCardKindOMa
+ _$s5CAFUI18CAFTripCardSourcesC11tripEntries04infoC6Hidden7Combine12AnyPublisherVyAA0bF0Vs5NeverOGAHySbALG_tF
+ _$s5CAFUI18CAFTripCardSourcesC20carManagerObservableAC10CAFCombine06CAFCarfG0C_tcfc
+ _$s5CAFUI18CAFTripCardSourcesCMa
+ _$s5CAFUI18CAFTripCardSourcesCMn
+ _$s7Combine10PublishersO3MapVMn
+ _$s7Combine10PublishersO3MapVy_xq_GAA9PublisherAAMc
+ _$s7Combine9PublisherPAAE010eraseToAnyB0AA0eB0Vy6OutputQz7FailureQzGyF
+ _$s7Combine9PublisherPAAE3mapyAA10PublishersO3MapVy_xqd__Gqd__6OutputQzclF
+ _$sSKsSS7ElementRtzrlE6joined9separatorS2S_tF
+ _$sSayxGSKsMc
+ _$sSvN
+ _$ss15ContiguousArrayV15reserveCapacityyySiFyXl_Ts5
+ _$ss27_diagnoseUnexpectedEnumCase4types5NeverOxm_tlF
+ _$ss5UInt8VN
+ _$ss5UInt8Vs23CustomStringConvertiblesWP
- _$s10CAFCombine16CAFCarObservableC18highVoltageBatterySo07CAFHigheF0CSgvgTj
- _$s10CAFCombine16CAFCarObservableC4fuelSo7CAFFuelCSgvgTj
- _$s10CAFCombine17CAFTripObservableC13$showOdometer7Combine12AnyPublisherVySbSgs5NeverOGvgTj
- _$s14CarPlayAssetUI21CarouselConfigurationV5style9direction14platterPadding17alwaysHidePlatter14animationStyle29decorationsVisibilityDuration15hidePageControlA2C0eO0O_AC15ScrollDirectionO12CoreGraphics7CGFloatVSbAC09AnimationO0OSdSbtcfC
- _$s7Combine10PublishersO16RemoveDuplicatesVMn
- _$s7Combine10PublishersO16RemoveDuplicatesVy_xGAA9PublisherAAMc
- _$s7Combine10PublishersO4DropVMn
- _$s7Combine10PublishersO4DropVy_xGAA9PublisherAAMc
- _$s7Combine9PublisherPAAE9dropFirstyAA10PublishersO4DropVy_xGSiF
- _$s7Combine9PublisherPAASQ6OutputRpzrlE16removeDuplicatesAA10PublishersO06RemoveE0Vy_xGyF
- _$sSbSQsWP
- _$sSo11CAFOdometerC10CAFCombine11CAFObservedACMc
- _$sSo18CAFFuelConsumptionC10CAFCombine11CAFObservedACMc
- _$sSo20CAFEnergyConsumptionC10CAFCombine11CAFObservedACMc
- _$sSo7CAFTripC10CAFCombine11CAFObservedACMc
- _$ss15ContiguousArrayV28_allocateBufferUninitialized15minimumCapacitys01_abD0VyxGSi_tFZ
- _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyXl_Ts5
- _$ss22_minimumMergeRunLengthyS2iF
- _$sxSgSQsSQRzlMc
- _OBJC_CLASS_$_CAFEnergyConsumption
- _OBJC_CLASS_$_CAFFuelConsumption
- _OBJC_CLASS_$_CAFOdometer
- _OBJC_CLASS_$_CAFTrip
- __swift_FORCE_LOAD_$_swiftCarPlay
- _objc_retain_x23
- _objc_retain_x24
- _objc_retain_x26
- _swift_release_n
CStrings:
+ " cards. flattenCardEntries="
+ "): cardmodels empty, skipping selectedTripIndex publish"
+ ". Host should have stamped a variant on this scene."
+ "[FlattenedTripCardView] no card matches sceneVariant="
+ "[FlattenedTripCardView] no sceneVariant and no cards available — nothing to render."
+ "[FlattenedTripCardView] scene has no sceneVariant. Falling back to first card variant="
+ "[TRIP] - init(presentationMode:sceneVariant:)"
+ "[TripCAFManager] init: manager="
+ "[Trip] Not ready for carousel - 0 cards."
+ "[Trip] cluster scene connected with sceneVariant="
+ "[Trip] inserting trip card (sortOrder="
+ "[Trip] sceneWillEnterForeground (variant="
+ "[Trip] sceneWillEnterForeground published selectedTripIndex="
+ "]. Host and Trip schedules are out of sync."
+ "_animationStyle"
+ "_educationTextHasBeenShown"
+ "_flattenCardEntries"
+ "init(carObservable:carManagerObservable:)"
+ "init(cardmodels:sceneVariant:)"
+ "init(presentationMode:sceneVariant:)"
+ "rebuildCardEntries(from:)"
+ "sceneVariant"
+ "sceneWillEnterForeground(_:)"
+ "tripCardSources"
+ "variant"
- " carObservable.fuel, "
- " carObservable.highVoltageBattery."
- " carObservable.tripComputer, "
- " energyConsumption.  "
- " energyConsumption="
- "CAFCarObserver"
- "[TRIP] - init(presentationMode:)"
- "[TripModel] carDidUpdate(_:receivedAllValues:)"
- "[TripModel] carDidUpdateAccessories(_:)"
- "[TripModel] connecting to energyConsumption ..."
- "[TripModel] connecting to fuelConsumption ..."
- "[TripModel] connecting to tripComputer/odometer ..."
- "[Trip] Not ready for carousel - "
- "[Trip] trips.count="
- "carDidNotify:accessory:service:control:withValue:"
- "carDidUpdate(_:receivedAllValues:)"
- "carDidUpdate:accessory:service:characteristic:"
- "carDidUpdate:accessory:service:control:"
- "carDidUpdate:receivedAllValues:"
- "carDidUpdateAccessories(_:)"
- "carDidUpdateAccessories:"
- "connectIfNeeded()"
- "consumption"
- "init(carObservable:)"
- "init(presentationMode:)"
- "registerObserver:"
- "sortOrder"
- "tripComputer"
- "trips"
- "updateTripState()"
- "v24@0:8@\"CAFCar\"16"
- "v28@0:8@\"CAFCar\"16B24"
- "v28@0:8@16B24"
- "v48@0:8@\"CAFCar\"16@\"CAFAccessory\"24@\"CAFService\"32@\"CAFCharacteristic\"40"
- "v48@0:8@\"CAFCar\"16@\"CAFAccessory\"24@\"CAFService\"32@\"CAFControl\"40"
- "v48@0:8@16@24@32@40"
- "v56@0:8@\"CAFCar\"16@\"CAFAccessory\"24@\"CAFService\"32@\"CAFControl\"40@\"NSDictionary\"48"
- "v56@0:8@16@24@32@40@48"
```
