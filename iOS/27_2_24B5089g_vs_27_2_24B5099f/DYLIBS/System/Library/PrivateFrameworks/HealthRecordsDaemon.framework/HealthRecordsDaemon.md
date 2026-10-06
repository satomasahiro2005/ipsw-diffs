## HealthRecordsDaemon

> `/System/Library/PrivateFrameworks/HealthRecordsDaemon.framework/HealthRecordsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ad360` | `0x1ad994` | **`+0x634`** |
| `__TEXT.__cstring` | `0x2961` | `0x2af1` | **`+0x190`** |
| `__DATA.__bss` | `0x1c030` | `0x1c0b0` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1fd8` | `0x2020` | **`+0x48`** |
| `__TEXT.__const` | `0x148ac` | `0x148ec` | **`+0x40`** |
| `__DATA.__data` | `0x3978` | `0x3988` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1060` | `0x1068` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x101cc` | `0x101c4` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x34c7` | `0x34bf` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x6308` | `0x6310` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x1710` | `0x170c` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0xee4` | `0xee8` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 7152
+  Functions: 7160

-  CStrings:  432
+  CStrings:  438
Symbols:
+ ___swift_closure_destructor.49Tm
+ _associated conformance So17NSHTTPURLResponseC19HealthRecordsDaemonE10CodeErrorsO10Foundation13CustomNSErrorACs5Error
- ___swift_closure_destructor.50Tm
- _symbolic So10NSCalendarC
CStrings:
+ "%04ld-%02ld-%02ld"
+ "HKHealthStore+ClinicalSharingQuery:voltageMeasurements"
+ "HKMCDaySummaryQuery+ClinicalSharingQuery:makeCycleDaySummaryPublisher"
+ "HKUserDomainConceptQuery+ClinicalSharingQuery:makeUserDomainConceptQuery"
+ "HKValueHistogramCollectionQuery+ClinicalSharingQuery:makeHistogramPublisher"
+ "HealthRecordsDaemon/ClinicalSharingQueryDataProviding.swift"
```
