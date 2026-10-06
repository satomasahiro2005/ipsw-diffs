## feedbackd

> `/usr/libexec/feedbackd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78a8c` | `0x81c48` | **`+0x91bc`** |
| `__DATA_CONST.__const` | `0x1e08` | `0x2438` | **`+0x630`** |
| `__TEXT.__eh_frame` | `0x4478` | `0x4820` | **`+0x3a8`** |
| `__TEXT.__const` | `0x1e08` | `0x218c` | **`+0x384`** |
| `__DATA.__bss` | `0x2010` | `0x2310` | **`+0x300`** |
| `__DATA.__data` | `0x1aa8` | `0x1d18` | **`+0x270`** |
| `__TEXT.__cstring` | `0x2c85` | `0x2e85` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x15e8` | `0x1778` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0xbec` | `0xd54` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x279f` | `0x28ff` | **`+0x160`** |
| `__TEXT.__swift5_fieldmd` | `0x780` | `0x8d8` | **`+0x158`** |
| `__TEXT.__swift5_typeref` | `0xd44` | `0xe78` | **`+0x134`** |
| `__TEXT.__swift5_capture` | `0x734` | `0x848` | **`+0x114`** |
| `__TEXT.__auth_stubs` | `0x1f80` | `0x2090` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x9f2` | `0xb02` | **`+0x110`** |
| `__DATA.__objc_const` | `0x1c28` | `0x1d28` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0xfc8` | `0x1050` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x192d` | `0x198d` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x3f8` | `0x448` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1340` | `0x1380` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x800` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x852` | `0x882` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x450` | `0x474` | **`+0x24`** |
| `__TEXT.__objc_classname` | `0x46c` | `0x48c` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x98` | `0xb4` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x670` | `0x688` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x558` | `0x570` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x100` | `0x118` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__DATA.__objc_data` | `0x880` | `0x890` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x108` | `0x114` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x140` | `0x14c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-240.0.0.0.0
+242.0.0.0.0

-  Functions: 1451
-  Symbols:   870
-  CStrings:  755
+  Functions: 1583
+  Symbols:   895
+  CStrings:  781
Symbols:
+ _$s10Foundation4DateV026timeIntervalSinceReferenceB0ACSd_tcfC
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s10Foundation4UUIDVSHAAMc
+ _$s10Foundation4UUIDVSQAAMc
+ _$s2os21OSAllocatedUnfairLockVMn
+ _$s8Dispatch0A3QoSV0B6SClassO7utilityyA2EmFWC
+ _$s8Dispatch0A3QoSV7utilityACvgZ
+ _$s8Dispatch0A4TimeV3nowACyFZ
+ _$s8Dispatch0A4TimeVMa
+ _$s8Dispatch0A8WorkItemC5flags5blockAcA0abC5FlagsV_yyXBtcfc
+ _$s8Dispatch0A8WorkItemC6cancelyyFTj
+ _$s8Dispatch0A8WorkItemCMa
+ _$s8Dispatch0A8WorkItemCMn
+ _$s8Dispatch1poiyAA0A4TimeVAD_SdtF
+ _$sSdN
+ _$sSo17OS_dispatch_queueC8DispatchE10asyncAfter8deadline7executeyAC0D4TimeV_AC0D8WorkItemCtF
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO7inherityA2EmFWC
+ _$ss13ManagedBufferCMn
+ _$ss21_findStringSwitchCase5cases6stringSiSays06StaticB0VG_SStF
+ _$ss6ResultOMn
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_cvw_instantiateLayoutString
+ _swift_getGenericMetadata
+ _swift_release_x12
+ _swift_retain_x28
- _$s10Foundation4DateVSLAAMc
- _$sSL2geoiySbx_xtFZTj
- _$sSL2leoiySbx_xtFZTj
CStrings:
+ "\"\n    WHERE evaluationUuid IN ("
+ "%{public}s count: %{public}ld"
+ "%{public}s deleted: %{public}ld, notFound: %{public}ld"
+ "%{public}s exceeded its [%{public}f]s deadline"
+ "' as stream,\n        eventTimestamp,\n        json_extract(commonMetadata, '$.evaluationUuid') evaluationUuid\n    FROM \""
+ ")\n    UNION SELECT\n        '"
+ "Bulk delete finished: deleted [%{public}ld], not found [%{public}ld]"
+ "Bulk delete: [%{public}ld] ID(s) not found; skipping enumeration for them"
+ "Bulk deleting [%{public}ld] donation(s)"
+ "Donation stream query"
+ "FeedbackDonationBulkDelete"
+ "SELECT * FROM (\n    SELECT\n        '"
+ "_TtC9feedbackd15CFBBiomeDeleter"
+ "biomeDeleter"
+ "com.apple.feedbackd.donation-stream-query"
+ "deleteDonations(donationIDs:completion:)"
+ "deleteDonationsWithDonationIDs:completion:"
+ "donation-bulk-delete"
+ "doubleValue"
+ "streamQueryWorker"
+ "textImageToImage"
+ "textToImage"
+ "textToText"
+ "timeboxed-worker"
+ "timestamp"
+ "v32@0:8@\"NSArray\"16@?<v@?@\"NSError\">24"
```
