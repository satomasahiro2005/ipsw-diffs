## SiriAppLaunchSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriAppLaunchSnippetProviderPlugin.bundle/SiriAppLaunchSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5348` | `0x7c2c` | **`+0x28e4`** |
| `__TEXT.__oslogstring` | `0x21a` | `0x3f8` | **`+0x1de`** |
| `__TEXT.__auth_stubs` | `0x570` | `0x660` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x1c0` | `0x278` | **`+0xb8`** |
| `__DATA_CONST.__auth_got` | `0x2b8` | `0x330` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x180` | `0x1e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x92` | `0x51` | **`-0x41`** |
| `__TEXT.__const` | `0x198` | `0x1d0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xb8` | `0xe8` | **`+0x30`** |
| `__DATA.__data` | `0xf0` | `0x118` | **`+0x28`** |
| `__DATA.__common` | `0x18` | `0x38` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x9e` | `0xbc` | **`+0x1e`** |
| `__DATA_CONST.__auth_ptr` | `0xc0` | `0xd0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.8.6.0.0
+3605.5.1.0.0

-  Functions: 95
-  Symbols:   67
-  CStrings:  12
+  Functions: 127
+  Symbols:   72
+  CStrings:  16
Symbols:
+ _objc_release_x21
+ _objc_release_x24
+ _objc_release_x27
+ _swift_arrayDestroy
+ _swift_bridgeObjectRelease_n
+ _swift_release_x23
+ _swift_release_x8
- _swift_release_x21
- _swift_release_x24
CStrings:
+ "AppLaunchResponseHandler deferring %ld apps in inform to per-entity rendering"
+ "AppLaunchResponseHandler registered for MarketplaceApplication handling"
+ "AppLaunchResponseHandler supports(): items=%ld apps=%ld in response type: %s"
+ "MarketplaceAppConverter missing required 'name' property"
+ "[MarketplaceAppConverter] 'iconURL' present but unreadable; shape=%{public}s"
+ "[MarketplaceAppConverter] entity carries neither 'iconURL' nor 'artwork'"
+ "[MarketplaceAppConverter] hydration check: nameLength=%{public}ld iconURLLength=%{public}ld genres=%{public}ld rating=%{bool,public}d reviewCount=%{bool,public}d bundleID=%{bool,public}d"
+ "[MarketplaceAppConverter] legacy artwork is neither string nor entity; shape=%{public}s"
+ "[MarketplaceAppConverter] propertyKeys=%{public}s iconShape=%{public}s"
+ "entityIdentifier"
+ "handle(item:context:) found MarketplaceApplication"
- "AppLaunchResponseHandler found %ld DisplayableMarketplaceApplication(s) in response type: %s"
- "AppLaunchResponseHandler registered for DisplayableMarketplaceApplication handling"
- "DisplayableMarketplaceApplication"
- "MarketplaceAppConverter missing 'result' entity"
- "MarketplaceAppConverter missing required 'name' property in result entity"
- "com.apple.siri.-MarketplaceIntents-AppIntents"
- "handle(item:context:) found DisplayableMarketplaceApplication for disambiguation"
```
