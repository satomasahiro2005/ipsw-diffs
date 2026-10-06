## PowerlogFullOperators

> `/System/Library/PrivateFrameworks/PowerlogFullOperators.framework/PowerlogFullOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23a60` | `0x23a00` | **`-0x60`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1
Functions:
~ -[PLAWDDisplay submitDataToAWDServer:withAwdConn:] : 6064 -> 6052
~ -[PLAWDCpuAP submitApDataToAWDServer:withAwdConn:] : 2216 -> 2212
~ -[PLAWDCpuAP submitCpuDataToAWDServer:withAwdConn:] : 1400 -> 1396
~ -[PLPMUAgent init] : 2088 -> 2080
~ -[PLPMUAgent logEventPointSensors] : 480 -> 476
~ -[PLAWDBattery submitDataToAWDServer:withAwdConn:] : 2060 -> 2056
~ -[PLAWDWifiBT submitWiFiDataToAWDServer:withAwdConn:] : 3268 -> 3264
~ -[PLAWDWifiBT submitBtDataToAWDServer:withAwdConn:] : 2292 -> 2288
~ -[PLAWDMetricsService initAWDInterface] : 1404 -> 1400
~ ___39-[PLAWDMetricsService initAWDInterface]_block_invoke.77 : 980 -> 972
~ -[PLAWDCamera submitDataToAWDServer:withAwdConn:] : 1816 -> 1812
~ -[PLAWDBB submitBBLqm:withAwdConn:] : 1804 -> 1792
~ -[PLPersistentConnectionAgent logEventPointCache] : 592 -> 588
~ -[PLAWDAudio submitDataToAWDServer:withAwdConn:] : 1612 -> 1608
~ -[PLBBPowerToolService percentageHistogramFromArray:] : 344 -> 340
~ -[PLBBPowerToolService submitAWD] : 2264 -> 2260
~ -[PLScheduledWakeAgent logEventForwardScheduledEvent] : 1832 -> 1824
```
