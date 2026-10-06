## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1857f0` | `0x185c50` | **`+0x460`** |
| `__TEXT.__cstring` | `0xd640` | `0xd690` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x123a8` | `0x123e0` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x7818` | `0x7840` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1bde4` | `0x1bdf4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x9280` | `0x9290` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x2c718` | `0x2c720` | **`+0x8`** |

### Other Changes

```diff

-625.2.5.10.1
+625.2.7.1.0

-  Functions: 9311
-  Symbols:   17547
-  CStrings:  2573
+  Functions: 9315
+  Symbols:   17552
+  CStrings:  2574
Symbols:
+ -[SFWebAppDataProvider _fetchWebClipMedia]
+ -[_SFReaderController setUpReaderWebViewIfNeededWithTimeout:completionHandler:]
+ ___42-[SFWebAppDataProvider _fetchWebClipMedia]_block_invoke
+ ___42-[SFWebAppDataProvider _fetchWebClipMedia]_block_invoke_2
+ ___42-[SFWebAppDataProvider _fetchWebClipMedia]_block_invoke_3
+ ___79-[_SFReaderController setUpReaderWebViewIfNeededWithTimeout:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e72_v48?0"UIImage"8"NSData"16"NSURL"24"NSDictionary"32"NSDictionary"40ls32l8s40l8
- -[_SFReaderController setUpReaderWebViewIfNeededAndPerformBlock:]
- ___65-[_SFReaderController setUpReaderWebViewIfNeededAndPerformBlock:]_block_invoke
CStrings:
+ "v48@?0@\"UIImage\"8@\"NSData\"16@\"NSURL\"24@\"NSDictionary\"32@\"NSDictionary\"40"
```
