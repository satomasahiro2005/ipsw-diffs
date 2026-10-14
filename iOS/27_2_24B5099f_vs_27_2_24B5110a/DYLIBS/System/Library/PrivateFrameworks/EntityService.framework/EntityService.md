## EntityService

> `/System/Library/PrivateFrameworks/EntityService.framework/EntityService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd235c` | `0xd46a8` | **`+0x234c`** |
| `__TEXT.__eh_frame` | `0x63d8` | `0x6608` | **`+0x230`** |
| `__TEXT.__unwind_info` | `0x2438` | `0x24e8` | **`+0xb0`** |
| `__AUTH.__data` | `0x520` | `0x5b0` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x9c18` | `0x9b98` | **`-0x80`** |
| `__DATA.__data` | `0x420` | `0x480` | **`+0x60`** |
| `__TEXT.__cstring` | `0x22e4` | `0x2344` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__const` | `0x4140` | `0x4180` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xdb8` | `0xd90` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0xe88` | `0xeb0` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x318` | `0x338` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x8d6` | `0x8f3` | **`+0x1d`** |
| `__TEXT.__swift_as_cont` | `0x4b4` | `0x4d0` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xbbc` | `0xbd4` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x3830` | `0x3844` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x10e0` | `0x10e8` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x17e0` | `0x17e8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1ec8` | `0x1ed0` | **`+0x8`** |

### Other Changes

```diff

-3605.21.1.501.4
+3605.22.501.10.0

-  Functions: 5289
+  Functions: 5322
CStrings:
+ "fetchHydratedEntities(type:batch:propertyHydrationSpec:userIdentity:)"
+ "fullHydration(for:useSpotlightPreferred:propertyHydrationSpec:userIdentity:)"
+ "hydrateBatch(type:batch:propertyHydrationSpec:userIdentity:)"
+ "hydrateEntities(values:propertyHydrationSpec:userIdentity:)"
+ "localHydratedEntities(for:propertyHydrationSpec:userIdentity:)"
+ "localHydratedEntities(with:userIdentity:)"
+ "resolveEntityProperties(batch:hydratedLookup:propertyHydrationSpec:deferredResolutionTimeout:session:userIdentity:)"
- "fetchHydratedEntities(type:batch:propertyHydrationSpec:)"
- "fullHydration(for:useSpotlightPreferred:propertyHydrationSpec:)"
- "hydrateBatch(type:batch:propertyHydrationSpec:)"
- "hydrateEntities(values:propertyHydrationSpec:)"
- "localHydratedEntities(for:propertyHydrationSpec:)"
- "localHydratedEntities(with:)"
- "resolveEntityProperties(batch:hydratedLookup:propertyHydrationSpec:deferredResolutionTimeout:session:)"
```
