## imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63d90` | `0x63d00` | **`-0x90`** |
| `__TEXT.__objc_methtype` | `0x3573` | `0x35a3` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x1b40` | `0x1b50` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xdb0` | `0xdb8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Symbols:   626
+  Symbols:   627
Symbols:
+ _IMSharedHelperCurrentRegionForcesFilterUnknownSenders
+ _swift_retain_x24
- _swift_retain_x27
Functions:
~ sub_10003d000 : 1092 -> 1096
~ sub_10004564c -> sub_100045650 : 1116 -> 1080
~ sub_100045b28 -> sub_100045b08 : 552 -> 568
~ sub_100045dc0 -> sub_100045db0 : 1184 -> 1136
~ sub_10004631c -> sub_1000462dc : 804 -> 828
~ sub_100048acc -> sub_100048aa4 : 1212 -> 1156
~ sub_100048f88 -> sub_100048f28 : 1276 -> 1228
CStrings:
+ "00:48:46"
+ "Sep 28 2026"
+ "v132@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSURL\"40B48{IMPreviewConstraints=d{CGSize=dd}dBBBB{CGSize=dd}}52@\"NSString\"108q116@?<v@?@\"IMPreviewGenerationResult\"@\"NSError\">124"
+ "v132@0:8@16@24@32@40B48{IMPreviewConstraints=d{CGSize=dd}dBBBB{CGSize=dd}}52@108q116@?124"
+ "v140@0:8@\"NSString\"16@\"NSURL\"24@\"NSString\"32@\"NSURL\"40B48{IMPreviewConstraints=d{CGSize=dd}dBBBB{CGSize=dd}}52@\"NSString\"108@\"NSString\"116q124@?<v@?@\"IMPreviewGenerationResult\"@\"NSError\">132"
+ "v140@0:8@16@24@32@40B48{IMPreviewConstraints=d{CGSize=dd}dBBBB{CGSize=dd}}52@108@116q124@?132"
- "22:28:59"
- "Sep 13 2026"
- "v116@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSURL\"40B48{IMPreviewConstraints=d{CGSize=dd}dBBB}52@\"NSString\"92q100@?<v@?@\"IMPreviewGenerationResult\"@\"NSError\">108"
- "v116@0:8@16@24@32@40B48{IMPreviewConstraints=d{CGSize=dd}dBBB}52@92q100@?108"
- "v124@0:8@\"NSString\"16@\"NSURL\"24@\"NSString\"32@\"NSURL\"40B48{IMPreviewConstraints=d{CGSize=dd}dBBB}52@\"NSString\"92@\"NSString\"100q108@?<v@?@\"IMPreviewGenerationResult\"@\"NSError\">116"
- "v124@0:8@16@24@32@40B48{IMPreviewConstraints=d{CGSize=dd}dBBB}52@92@100q108@?116"
```
