## AppContentHub

> `/private/var/staged_system_apps/Freeform.app/Frameworks/AppContentHub.framework/AppContentHub`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x271270` | `0x270ad0` | **`-0x7a0`** |
| `__TEXT.__cstring` | `0x8aab` | `0x899b` | **`-0x110`** |
| `__DATA_CONST.__const` | `0x14278` | `0x141f8` | **`-0x80`** |
| `__TEXT.__auth_stubs` | `0x6210` | `0x6190` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0xa7a8` | `0xa750` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x8e98` | `0x8e48` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x3118` | `0x30d8` | **`-0x40`** |
| `__TEXT.__const` | `0x1d1f4` | `0x1d1b4` | **`-0x40`** |
| `__DATA.__data` | `0xf300` | `0xf2d0` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x23fe4` | `0x23fc4` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x24e8` | `0x24d0` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x1750` | `0x1740` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x4861` | `0x4851` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x604` | `0x5f4` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x298` | `0x290` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2b0` | `0x2b4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-649.0.0.0.3
+651.0.0.501.2

-  Functions: 12624
-  Symbols:   6474
-  CStrings:  2320
+  Functions: 12605
+  Symbols:   6457
+  CStrings:  2317
Symbols:
+ __swift_closure_destructor.123Tm
+ __swift_closure_destructor.201Tm
+ __swift_closure_destructor.206Tm
+ __swift_closure_destructor.83Tm
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 13AppContentHub17TSCOImageLRUCacheC5State33_B60B7D5EBF8E9261AB0EA4C042764490LLV
+ _symbolic _____y_____yxq_q0__GG 15Synchronization5MutexVAARi_zrlE 13AppContentHub20TSCOThumbnailBatcherC13InternalState33_F0557C137004FB716B7B6A25505AB14CLLV
- _CFDataCreateMutable
- _CGImageDestinationAddImage
- _CGImageDestinationCreateWithData
- _CGImageDestinationFinalize
- _CGImageDestinationSetProperties
- __os_log_fault_impl
- __swift_closure_destructor.125Tm
- __swift_closure_destructor.198Tm
- __swift_closure_destructor.208Tm
- __swift_closure_destructor.85Tm
- _kCFAllocatorDefault
- _kCGImagePropertyPixelHeight
- _kCGImagePropertyPixelWidth
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic ______Sit So11CFStringRefa
- _symbolic _____y_____SiG s18_DictionaryStorageC So11CFStringRefa
- _symbolic _____y______SitG s23_ContiguousArrayStorageC So11CFStringRefa
- get_type_metadata 13AppContentHub21TSCOProviderItemTokenRzs8SendableR_SchR0_r1_l15Synchronization5MutexVyAA20TSCOThumbnailBatcherC13InternalState33_F0557C137004FB716B7B6A25505AB14CLLVyxq_q0__GG noncopyable
- get_type_metadata 15Synchronization5MutexVy13AppContentHub10AssetCacheCG noncopyable
- get_type_metadata 15Synchronization5MutexVy13AppContentHub19AssetReferenceCacheCG noncopyable
- get_type_metadata 15Synchronization5MutexVy13AppContentHub26TSCOObservableQueryResultsC14AsyncTaskState023_31BB62B4B45E09A0914EF3M8F3304082LLOG noncopyable
- get_type_metadata 15Synchronization5MutexVySDy13AppContentHub14TSCOProviderIDVAD0F0_pGG noncopyable
- get_type_metadata SHRzs8SendableRzl15Synchronization5MutexVy13AppContentHub17TSCOImageLRUCacheC5State33_B60B7D5EBF8E9261AB0EA4C042764490LLVyx_GG noncopyable
CStrings:
- "Fatal Assertion failure: %{public}s %{public}s:%d We always need to populate _setupError if _userID is nil"
- "Fatal Assertion failure: %{public}s %{public}s:%d _setupError must be populated if we have a _userID but p_zoneID returns nil"
- "Unable to create image."
```
