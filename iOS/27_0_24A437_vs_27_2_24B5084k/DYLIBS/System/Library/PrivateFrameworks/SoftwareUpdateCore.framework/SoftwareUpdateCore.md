## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/SoftwareUpdateCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaf194` | `0xaf0a0` | **`-0xf4`** |
| `__TEXT.__oslogstring` | `0xcef3` | `0xce93` | **`-0x60`** |
| `__AUTH_CONST.__cfstring` | `0x137a0` | `0x13780` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1620d` | `0x161ed` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x842c` | `0x8444` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a60` | `0x4a70` | **`+0x10`** |

### Other Changes

```diff

-2718.0.18.0.0
+2718.40.13.0.0

-  Functions: 3290
-  Symbols:   5748
-  CStrings:  3300
+  Functions: 3292
+  Symbols:   5750
+  CStrings:  3297
Symbols:
+ -[SUCoreUpdateDownloader _stageDownloadGroups:awaitingAllGroups:withStagingTimeout:reportingProgress:completion:]
+ -[SUCoreUpdateDownloader initWithDelegate:forUpdate:updateUUID:maControl:maControlSplombo:]
CStrings:
+ "2.2.0"
+ "[SPACE] Entitled secured space is taken into account, sharedFreeSpace= %llu, entitledFreeSpace= %llu, freeSpaceAvailableForSoftwareUpdate= %llu, entitledSpaceDisableInSUCore= %{public}@"
- "1.0.6"
- "[POWER_ASSERTION] DISPATCH: created dispatch queue domain(%{public}@)"
- "[SPACE] DISPATCH: created dispatch queue domain(%{public}@)"
- "[SPACE] Entitled secured space is taken into account, sharedFreeSpace= %llu, entitledFreeSpace= %llu, freeSpaceAvailableForSoftwareUpdate= %llu"
- "unable to create dispatch queue domain(%@)"
```
