## ManagedAppDistribution

> `/System/Library/Frameworks/ManagedAppDistribution.framework/ManagedAppDistribution`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bfc8` | `0x8cf38` | **`+0xf70`** |
| `__DATA.__bss` | `0x16780` | `0x16a80` | **`+0x300`** |
| `__DATA_DIRTY.__bss` | `0x6600` | `0x6480` | **`-0x180`** |
| `__AUTH_CONST.__const` | `0x89a8` | `0x8a88` | **`+0xe0`** |
| `__TEXT.__const` | `0xf414` | `0xf4e4` | **`+0xd0`** |
| `__TEXT.__cstring` | `0xef4` | `0xf74` | **`+0x80`** |
| `__DATA.__data` | `0x1dd0` | `0x1e20` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x272b` | `0x2757` | **`+0x2c`** |
| `__DATA_DIRTY.__data` | `0x17e0` | `0x17b8` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x2cf8` | `0x2d20` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x2654` | `0x2678` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0xa88` | `0xaa0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xe6c` | `0xe78` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x420` | `0x424` | **`+0x4`** |

### Other Changes

```diff

-4.0.44.0.0
+4.1.9.0.0

-  Functions: 4197
-  Symbols:   1241
-  CStrings:  179
+  Functions: 4213
+  Symbols:   1249
+  CStrings:  183
Symbols:
+ ___swift_closure_destructor.9Tm
+ _associated conformance 22ManagedAppDistribution19MessageRegistrationO011MarketplaceB17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 22ManagedAppDistribution19MessageRegistrationO011MarketplaceB17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 22ManagedAppDistribution19MessageRegistrationO0aB17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 22ManagedAppDistribution19MessageRegistrationO0aB17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _swift_retain_x26
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic _____y_____G s22KeyedDecodingContainerV 22ManagedAppDistribution19MessageRegistrationO011MarketplaceE17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 22ManagedAppDistribution19MessageRegistrationO0dE17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 22ManagedAppDistribution19MessageRegistrationO011MarketplaceE17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 22ManagedAppDistribution19MessageRegistrationO0dE17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLO
- ___swift_closure_destructor.4Tm
- _associated conformance 22ManagedAppDistribution19MessageRegistrationO0B17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLOs0G3KeyAAs23CustomStringConvertible
- _associated conformance 22ManagedAppDistribution19MessageRegistrationO0B17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLOs0G3KeyAAs28CustomDebugStringConvertible
- _symbolic _____y_____G s22KeyedDecodingContainerV 22ManagedAppDistribution19MessageRegistrationO0E17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 22ManagedAppDistribution19MessageRegistrationO0E17CatalogCodingKeys33_46EDEA3828F7BDBC459A335C1553C4F2LLO
CStrings:
+ "Managed app catalog changed"
+ "Marketplace app catalog changed"
+ "duplicateConfiguredPackage"
+ "marketplaceAppCatalog"
+ "newerVersionInstalled"
- "App catalog changed"
```
