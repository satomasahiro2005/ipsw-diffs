## ansf.t8140.release.im4p

> `Firmware/ansf.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e3a10` | `0x1e65a0` | **`+0x2b90`** |
| `__TEXT.__cstring` | `0x24db1` | `0x2509e` | **`+0x2ed`** |
| `__TEXT.__const` | `0x5878` | `0x5b28` | **`+0x2b0`** |
| `__DATA.__zerofill` | `0x20f438` | `0x20f638` | **`+0x200`** |
| `__TEXT.shared` | `0xe0a0` | `0xdee8` | **`-0x1b8`** |
| `__TEXT.read` | `0x70a8` | `0x71dc` | **`+0x134`** |
| `__DATA.__data` | `0x5c08` | `0x5c00` | **`-0x8`** |
| `__DATA.core_globals` | `0x161` | `0x162` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__TEXT.__chain_starts`

### Other Changes

```diff

-  Functions: 1959
+  Functions: 1965

-  CStrings:  3942
+  CStrings:  3959
CStrings:
+ " Sanitize_Run -> %ums"
+ "!Sanitize_IsActive()"
+ "222.0.0.0.1"
+ "222.0.0.0.1~166"
+ "Abort Pad: Flow %u , Band: %u"
+ "AppleStorageFirmwareASP3-222.0.0.0.1~166"
+ "BG_TODO_SET(BG.todo.sanitize) was called when host is idle"
+ "Block scan aborted in unexpected state (panicAtAbort enabled by tunnel)"
+ "Buffer too small for pilot scan bands - needed %u bytes, got %u"
+ "Error - no tunnel buffer for pilot scan bands"
+ "GCAD=%3u"
+ "Invalid Sanitize phase %d"
+ "MassScan skipped (too frequent), notifying MSPs"
+ "MassScan_CanGoIdle()"
+ "Sanitize already in progress, phase=%d"
+ "Sanitize started"
+ "Sanitize: Phase 1 complete abort pad"
+ "Sanitize: Phase 2 complete, abort pad done"
+ "Sanitize: Phase 3 complete, marked %u bands with Must"
+ "Sanitize: Phase 4 complete, GC done"
+ "Sanitize: Phase 5 complete, marked %u bands with Must and Special"
+ "Sanitize: Phase 6 complete, GC done"
+ "T : Timestamp\nP : Percent Cmd_DoPreempt\nWL:\n Ops p 0/1/2/3\n SumLatency p 0/1/2/3\n MaxLatency p0/1/2/3\nRL:\n Ops p 0/1/2/3\n SumLatency p 0/1/2/3\n MaxLatency p0/1/2/3\nE: Block Erases\nF: Host Flushes\nHR: Host Reads\nHW: Host Writes\nNR: Nand Reads\nNW: Nand Writes\nNUR: Nand Util Reads\nNUW: Nand Util Writes\nCW: Clog Writes\nIW: Ind Writes\nGC: GC Writes\nSoMx: Maximal number of stepovers per host bandsBND: Minimal number of stepovers per host band\nSoAvg: Average number of stepovers per host band\nHPMM: Maximal number of ASI commands per MSPPR: Prefetch Reads\nPH: Prefetch Hits\nPN: Prefetch fetch next ranges\nAW: Writes that were handled by autowrite HW\nWCD: Write cache dirty percentage\nWCFB: Write cache free buffers percentage\nW : Wear Level Bands\nBI: BLKS(SLC)\nBU: BLKS(MLC/TLC)\nBL: BLKS LVL\nTH: Time in Hysteresis (ms)\nS : Free Segs\nV : IndMem Free\nML: IND_Mem_GetFreeSpace output in percents\nX : Expedite Ok/Fail\nU : Host unmaps\nCmin : Host tags(Min)\nCmax : Host tags(Max)\nBGT: Background task time(us)\nUT: Update Time(us)\nNU: Updated fragmets in indirection\nST: Search Time(us)\nGMT: GC Move Time(us)\nGDF: GC Defrag Time(us)\nNS: Searches\nMB: Cache/Ind MBUs\nIMM: Time Spent in Immediate Cmd (us)\nLHS: Ldefrag host sectors read\nLTS: Ldefrag troll sectors read\nLHF: Ldefrag host fragments read\nLTF: Ldefrag troll fragments read\nCCMB: Segs that were combined on cache level, often after troll read\nWCMB: Segs that were combined on writtenQ level, often after buffer fragmentation\nFDOW: Freagments decrease in indirection, zero if increased\nEX: Extra senses in MSP may slow read perf\nNWSM: Nand writes in SLC mode\nNRSM: Nand reads in SLC mode\nNWTM: Nand writes in TLC mode\nNRTM: Nand reads in TLC mode\nPSRD: Parity subtract reads\nRDS: Sectors read due to RD sampler\nTP: Total padding count\nIP: Immediate padding count\nTEMP: max temperature of all msps\nNWQM: Nand writes in FNC mode\nNRQM: Nand reads in FNC mode\nGCFQ: Force FNC for GC\nTi: IndMem #free tilesDT: delta for +freeTile/-freeTileMTH: IndMem total used mix/highest used mix\nGCS: GC SRC InfoWA: write amplificationGRK: GC src_rk_firstGCST: GC stateGCAD: GC average durationGCMT: GC MustList TopGHCO: GC Host choke offsetGCD: GC DST InfoGM: count GC must bands\nUE num ueccs from nand this time period\nGB: total number GBBs\nRH: total number host reconstructions\nRI: total internal reconstruction\nRR: raid sector reads this period\nOBC: Offline blocks count\nDTB: Dir to TLC bands\nRHM: Raid cache HW miss sectors\nRHM: Raid cache HR miss sectors\nBo: oSLC bands\noSLC SM on stateoSLC voters stateREWS: Raid evict engine write sectors\nRFRS: Raid fetch engine read sectors\nADFH:  AES Write Data Beat received from F2H\nADHF: AES Write Data Beat received from H2F\nVBWR: Num Write Data beats rcvd from Vlane\nVBRR: Num Read Data beats sent to Vlane\nCFDWC: Num Write Data beats rcvd from ANS2 CPU\nCFDRC: Num Read Data beats sent to ANS2 CPU\nDLWD: Num Write Data beats rcvd from apcie_0_m\nDLRD: Num Read Data beats sent to apcie_0_m\nUWDF: Num Write Data Beats rcvd from Data Fabric\nURDF: Num Read Data beats sent to Data Fabric\nDPQBI: Num Barriers pushed into Dispatch Queue\nDPQBO: Num Barriers sent out from Dispatch Queue\n"
+ "expectedAbort set but block scan status was %u (not ABORTED, panicAtAbort enabled by tunnel)"
+ "mark band %u"
+ "mark band %u, isOpen %u"
+ "sanitize cmd drop - configuration not supported"
+ "sanitize cmd drop - during another sanitize phase %u"
+ "sanitize cmd drop - invalid system state: DM %u Clog %u shn %u"
+ "sanitize cmd: sanact %u, cfg 0x%x, op 0x%x"
+ "sanitize.c"
+ "{ 'trace_id': 'SNAPSHOT_MEMBER_8', 'tp_func': %d, 'timestamp': %llu, 'hostWriteBudget': %u, 'bpZone': %u, 'openBlocks': %u, 'tlcFb': %u }\n"
- " Bands_RefreshWorstETBand -> %ums"
- "!BGRefresh.massScan.isScanActive"
- "!BandsTemp_CanEvictETBandsSet()"
- "192.0.0.0.1"
- "192.0.0.0.1~1483"
- "AppleStorageFirmwareASP3-192.0.0.0.1~1483"
- "BG_TODO_SET(BG.todo.findET) was called when host is idle"
- "Cond BDR ALL_DONE state shouldn't get here!"
- "Prores inactive."
- "Prores-type input detected."
- "T : Timestamp\nP : Percent Cmd_DoPreempt\nWL:\n Ops p 0/1/2/3\n SumLatency p 0/1/2/3\n MaxLatency p0/1/2/3\nRL:\n Ops p 0/1/2/3\n SumLatency p 0/1/2/3\n MaxLatency p0/1/2/3\nE: Block Erases\nF: Host Flushes\nHR: Host Reads\nHW: Host Writes\nNR: Nand Reads\nNW: Nand Writes\nNUR: Nand Util Reads\nNUW: Nand Util Writes\nCW: Clog Writes\nIW: Ind Writes\nGC: GC Writes\nSoMx: Maximal number of stepovers per host bandsBND: Minimal number of stepovers per host band\nSoAvg: Average number of stepovers per host band\nHPMM: Maximal number of ASI commands per MSPPR: Prefetch Reads\nPH: Prefetch Hits\nPN: Prefetch fetch next ranges\nAW: Writes that were handled by autowrite HW\nWCD: Write cache dirty percentage\nWCFB: Write cache free buffers percentage\nW : Wear Level Bands\nBI: BLKS(SLC)\nBU: BLKS(MLC/TLC)\nBL: BLKS LVL\nTH: Time in Hysteresis (ms)\nS : Free Segs\nV : IndMem Free\nML: IND_Mem_GetFreeSpace output in percents\nX : Expedite Ok/Fail\nU : Host unmaps\nCmin : Host tags(Min)\nCmax : Host tags(Max)\nBGT: Background task time(us)\nUT: Update Time(us)\nNU: Updated fragmets in indirection\nST: Search Time(us)\nGMT: GC Move Time(us)\nGDF: GC Defrag Time(us)\nNS: Searches\nMB: Cache/Ind MBUs\nIMM: Time Spent in Immediate Cmd (us)\nLHS: Ldefrag host sectors read\nLTS: Ldefrag troll sectors read\nLHF: Ldefrag host fragments read\nLTF: Ldefrag troll fragments read\nCCMB: Segs that were combined on cache level, often after troll read\nWCMB: Segs that were combined on writtenQ level, often after buffer fragmentation\nFDOW: Freagments decrease in indirection, zero if increased\nEX: Extra senses in MSP may slow read perf\nNWSM: Nand writes in SLC mode\nNRSM: Nand reads in SLC mode\nNWTM: Nand writes in TLC mode\nNRTM: Nand reads in TLC mode\nPSRD: Parity subtract reads\nRDS: Sectors read due to RD sampler\nTP: Total padding count\nIP: Immediate padding count\nTEMP: max temperature of all msps\nNWQM: Nand writes in FNC mode\nNRQM: Nand reads in FNC mode\nGCFQ: Force FNC for GC\nTi: IndMem #free tilesDT: delta for +freeTile/-freeTileMTH: IndMem total used mix/highest used mix\nGCS: GC SRC InfoWA: write amplificationGRK: GC src_rk_firstGCST: GC stateGCMT: GC MustList TopGHCO: GC Host choke offsetGCD: GC DST InfoGM: count GC must bands\nUE num ueccs from nand this time period\nGB: total number GBBs\nRH: total number host reconstructions\nRI: total internal reconstruction\nRR: raid sector reads this period\nOBC: Offline blocks count\nDTB: Dir to TLC bands\nRHM: Raid cache HW miss sectors\nRHM: Raid cache HR miss sectors\nBo: oSLC bands\noSLC SM on stateoSLC voters stateREWS: Raid evict engine write sectors\nRFRS: Raid fetch engine read sectors\nADFH:  AES Write Data Beat received from F2H\nADHF: AES Write Data Beat received from H2F\nVBWR: Num Write Data beats rcvd from Vlane\nVBRR: Num Read Data beats sent to Vlane\nCFDWC: Num Write Data beats rcvd from ANS2 CPU\nCFDRC: Num Read Data beats sent to ANS2 CPU\nDLWD: Num Write Data beats rcvd from apcie_0_m\nDLRD: Num Read Data beats sent to apcie_0_m\nUWDF: Num Write Data Beats rcvd from Data Fabric\nURDF: Num Read Data beats sent to Data Fabric\nDPQBI: Num Barriers pushed into Dispatch Queue\nDPQBO: Num Barriers sent out from Dispatch Queue\n"
- "Timeout waiting for GC buffers to be freed"
- "invalid ET state, band %u, isCold %u, isHot %u"
- "invalid band temp %u"
- "{ 'trace_id': 'SNAPSHOT_MEMBER_8', 'tp_func': %d, 'timestamp': %llu, 'hostWriteBudget': %u, 'hostBudgetRatio': %u, 'bpZone': %u, 'openBlockSec': %u }\n"
```
