## maphelperservice

> `/System/Library/Frameworks/CoreLocation.framework/XPCServices/maphelperservice.xpc/maphelperservice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11880` | `0x11864` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3164.0.0.0.0
+3169.4.0.0.0
Functions:
~ __ZN18CLFamiliarRoadData21getFamiliarityDataForE12CLMapRoadKeyRKy : 200 -> 208
~ __ZN18CLFamiliarRoadData36trimNeighborsBasedOnFamiliarityIndexENSt3__110shared_ptrI9CLMapRoadEERNS0_6vectorIS3_NS0_9allocatorIS3_EEEE : 576 -> 568
~ sub_100002508 : 960 -> 956
~ sub_1000028c8 -> sub_1000028c4 : 240 -> 232
~ sub_100002ae8 -> sub_100002adc : 724 -> 720
~ __ZN9CLMapRoad23computeSegmentDistancesEv : 296 -> 304
~ __ZN9CLMapRoad22computeSegmentHeadingsEv : 272 -> 280
~ __ZN9CLMapRoad26isParticleOnACurvedSegmentEddb : 648 -> 656
~ __ZN9CLMapRoad17reverseRoadVectorEv : 268 -> 276
~ __ZN9CLMapRoad13isUTurnRoadOfERKNSt3__110shared_ptrIS_EE : 268 -> 272
~ __ZNK9CLMapRoad22startIsConnectedToStopERKNSt3__110shared_ptrIS_EE : 100 -> 104
~ __ZNK9CLMapRoad22stopIsConnectedToStartERKNSt3__110shared_ptrIS_EE : 100 -> 104
~ __ZNK9CLMapRoad21stopIsConnectedToStopERKNSt3__110shared_ptrIS_EE : 100 -> 108
~ __ZN9CLMapRoad11getAsStringEv : 2612 -> 2596
~ sub_100005acc -> sub_100005ae0 : 616 -> 604
~ sub_10000850c -> sub_100008514 : 1760 -> 1752
~ sub_10000949c : 1232 -> 1212
~ sub_10000a730 -> sub_10000a71c : 1060 -> 1056
~ sub_10000ab54 -> sub_10000ab3c : 1332 -> 1320
~ sub_10000b088 -> sub_10000b064 : 572 -> 568
~ sub_10000b2c4 -> sub_10000b29c : 1828 -> 1824
~ sub_10000bb9c -> sub_10000bb70 : 4756 -> 4768
~ sub_10000d514 -> sub_10000d4f4 : 7824 -> 7812
~ sub_1000103a4 -> sub_100010378 : 648 -> 644
~ sub_100010bb8 -> sub_100010b88 : 2824 -> 2848
~ sub_100011a08 -> sub_1000119f0 : 764 -> 760
```
