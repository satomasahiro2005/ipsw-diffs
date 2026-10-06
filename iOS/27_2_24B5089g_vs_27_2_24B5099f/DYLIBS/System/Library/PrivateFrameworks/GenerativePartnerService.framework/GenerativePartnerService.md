## GenerativePartnerService

> `/System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9d184` | `0xa3918` | **`+0x6794`** |
| `__AUTH_CONST.__const` | `0x6820` | `0x6de8` | **`+0x5c8`** |
| `__TEXT.__eh_frame` | `0x5248` | `0x5768` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x437d` | `0x47cd` | **`+0x450`** |
| `__DATA.__bss` | `0x46a0` | `0x49a0` | **`+0x300`** |
| `__TEXT.__const` | `0x5658` | `0x58c8` | **`+0x270`** |
| `__TEXT.__swift5_capture` | `0x1444` | `0x1668` | **`+0x224`** |
| `__TEXT.__unwind_info` | `0x2be0` | `0x2d88` | **`+0x1a8`** |
| `__TEXT.__cstring` | `0x26db` | `0x27bb` | **`+0xe0`** |
| `__DATA.__data` | `0xa08` | `0xa98` | **`+0x90`** |
| `__AUTH.__data` | `0x768` | `0x7f0` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x19bb` | `0x1a39` | **`+0x7e`** |
| `__TEXT.__constg_swiftt` | `0x1714` | `0x1780` | **`+0x6c`** |
| `__TEXT.__swift5_fieldmd` | `0x187c` | `0x18cc` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x1691` | `0x16d1` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x404` | `0x444` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1640` | `0x1670` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x388` | `0x3b8` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x1e4` | `0x20c` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x800` | `0x820` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x408` | `0x420` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x310` | `0x328` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1dc` | `0x1f4` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0xb4` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x17d0` | `0x17e0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Other Changes

```diff

-297.8.0.2.0
+297.12.0.1.2

-  Functions: 4824
-  Symbols:   237
-  CStrings:  510
+  Functions: 4985
+  Symbols:   240
+  CStrings:  531
Symbols:
+ _LNMetadataChangedNotificationBundlesKey
+ _LNMetadataChangedNotificationEventKey
+ _OBJC_CLASS_$_AMSFeatureFlagITFE
CStrings:
+ "%{public}s: adding %{public}ld uninstalled supported app(s): %{public}s"
+ "%{public}s: caching %{public}ld supported apps: %{public}s"
+ "%{public}s: disabled by bag key; treating as no supported apps"
+ "%{public}s: expected one platformAttributes entry, got %{public}ld for %{public}s; skipping"
+ "%{public}s: fetch failed; keeping existing cache, will retry"
+ "%{public}s: lookup failed: %{public}@"
+ "%{public}s: returned %{public}ld supported apps: %{public}s"
+ "%{public}s: supported apps unchanged (%{public}ld); skipping rebuild"
+ "%{public}s: supported-apps cache stale or unpopulated"
+ "%{public}s: warm-up populate; kicking supported-apps fetch"
+ "Client process %{public}s is missing the com.apple.generativeexperiences.ExternalProviderService entitlement required to access ExternalProviderService; it should adopt it."
+ "Fast-index app(s) %{public}s are entitled to an AgentIntent"
+ "GenerativePartnerServiceSupportedAppsLookupEnabled"
+ "Immediate ToolKit index failed: %{public}@"
+ "Immediate ToolKit index finished in %{public}ld ms"
+ "Received LNMetadataChanged notification (not a registration)"
+ "fetchSupportedApps()"
+ "installedExternalProviders(matching:)"
+ "refreshSupportedAppsCache()"
+ "refreshSupportedAppsIfStale()"
+ "refreshSupportedAppsOnWarmUp()"
+ "supportsExtendedRouting"
- "installedExternalProviders()"
```
