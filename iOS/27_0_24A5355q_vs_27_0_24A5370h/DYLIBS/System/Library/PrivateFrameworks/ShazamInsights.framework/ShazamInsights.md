## ShazamInsights

> `/System/Library/PrivateFrameworks/ShazamInsights.framework/ShazamInsights`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x394c` | `0x393c` | **`-0x10`** |

### Other Changes

```diff

-427.0.33.0.0
+427.0.36.0.0
Functions:
~ -[CLLocation(Geohash) sh_geoHashToCoordinates:] : 472 -> 476
~ -[SHTimeAndPlaceAffinityGroup geohashKeyedRegions] : 424 -> 420
~ -[SHTimeAndPlaceAffinityGroup regionsForGeohash:] : 532 -> 528
~ ___101-[SHTimeAndPlaceController affinityGroupsFromData:atLocation:onDate:configuration:completionHandler:]_block_invoke : 484 -> 480
~ +[SHTimeAndPlaceServerResponseParser regionAffinityGroupsFromServerData:error:] : 1148 -> 1140
```
