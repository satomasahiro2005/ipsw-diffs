## FlightUtilitiesCore

> `/System/Library/PrivateFrameworks/FlightUtilitiesCore.framework/FlightUtilitiesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1116c` | `0x111bc` | **`+0x50`** |

### Other Changes

```text
Functions:
~ +[FUUtils convertFlightModel:withError:] : 3120 -> 3112
~ -[FUFlight copyWithZone:] : 528 -> 524
~ -[FUFlight legsAsFlights] : 484 -> 480
~ -[FUFlight status] : 376 -> 372
~ -[FUFlight relevantLeg] : 388 -> 384
~ -[FUFlightStep taxiing] : 68 -> 64
~ ___112+[FUFlightFactory_Parsec loadFlightsWithNumber:airlineCode:date:dateType:userAgent:sessionID:completionHandler:]_block_invoke : 1464 -> 1452
~ sub_25c1d5ff0 -> sub_25d62ffc8 : 1580 -> 1648
~ sub_25c1d7738 -> sub_25d631754 : 856 -> 912
~ sub_25c1d85cc -> sub_25d632620 : 628 -> 624
```
