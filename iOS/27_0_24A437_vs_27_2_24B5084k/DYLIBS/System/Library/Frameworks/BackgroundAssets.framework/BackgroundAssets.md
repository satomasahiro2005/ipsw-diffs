## BackgroundAssets

> `/System/Library/Frameworks/BackgroundAssets.framework/BackgroundAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa10f4` | `0xa9dc8` | **`+0x8cd4`** |
| `__TEXT.__oslogstring` | `0x5858` | `0x5ee8` | **`+0x690`** |
| `__TEXT.__eh_frame` | `0x4a98` | `0x4ef0` | **`+0x458`** |
| `__AUTH_CONST.__const` | `0x2090` | `0x21d0` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x132d` | `0x144f` | **`+0x122`** |
| `__TEXT.__unwind_info` | `0x1d80` | `0x1e80` | **`+0x100`** |
| `__AUTH_CONST.__auth_got` | `0x10e0` | `0x11c8` | **`+0xe8`** |
| `__TEXT.__const` | `0x3188` | `0x3228` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x7f8` | `0x888` | **`+0x90`** |
| `__DATA.__data` | `0x1408` | `0x1448` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x6c8` | `0x700` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x294` | `0x2c8` | **`+0x34`** |
| `__TEXT.__cstring` | `0x437a` | `0x439a` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x180` | `0x194` | **`+0x14`** |
| `__AUTH.__data` | `0x340` | `0x330` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xba8` | `0xbb8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x148` | `0x154` | **`+0xc`** |

### Other Changes

```diff

-279.0.5.0.0
+279.40.6.0.0

-  Functions: 2101
-  Symbols:   1562
-  CStrings:  650
+  Functions: 2159
+  Symbols:   1576
+  CStrings:  666
Symbols:
+ ___swift_closure_destructor.246Tm
+ ___swift_closure_destructor.257Tm
+ ___swift_closure_destructor.295Tm
+ _symbolic ScCySo10BADownloadCSg_SSSgt______pG s5ErrorP
+ _symbolic ScCySo10BADownloadCSg_SSt______pG s5ErrorP
+ _symbolic So10BADownloadCSg_SSSgt
+ _symbolic So10BADownloadCSg_SSSgt______pIegTrzo_ s5ErrorP
+ _symbolic So10BADownloadCSg_SSSgtyKYTc
+ _symbolic So10BADownloadCSg_SSt
+ _symbolic So10BADownloadCSg_SSt______pIegTrzo_ s5ErrorP
+ _symbolic So10BADownloadCSg_SStyKYTc
+ _symbolic _____ 29ManagedBackgroundAssetsHelper15AssetPackRecordC8GlobalIDV
+ _symbolic _____Sg 10Foundation13URLComponentsV
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation12URLQueryItemV
- ___swift_closure_destructor.267Tm
CStrings:
+ "Checking whether the URL “%{public}s” for the asset pack with the ID “%{public}s” needs to be refreshed…"
+ "MBAURLExpirationBuffer"
+ "Resolve Apple-hosted asset pack: %{public}s from: %{public}s"
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” couldn’t be decomposed into components."
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” doesn’t need to be refreshed because it expires %{public}s."
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” expire%{public}s %{public}s; refreshing it…"
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” has an empty access key."
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” has an expiration component, “%{public}s”, that couldn’t be parsed."
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” has multiple access keys."
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” lacks an access key."
+ "The URL “%{public}s” for the asset pack with the ID “%{public}s” lacks query items."
+ "The asset pack with the ID “%{public}s” couldn’t be moved into the system container; removing the record of it…"
+ "The asset pack with the ID “%{public}s” is absent from the refreshed manifest."
+ "The new URL for the asset pack with the ID “%{public}s” is “%{public}s”."
+ "The record of the asset pack with the ID “%{public}s” couldn’t be removed: %{public}@"
+ "The refreshed asset pack is version %ld, whereas the requested asset pack is version %ld."
```
