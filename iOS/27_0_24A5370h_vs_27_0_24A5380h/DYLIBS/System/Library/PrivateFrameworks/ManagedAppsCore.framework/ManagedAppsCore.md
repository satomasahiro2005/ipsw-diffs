## ManagedAppsCore

> `/System/Library/PrivateFrameworks/ManagedAppsCore.framework/ManagedAppsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ec6c` | `0x80e8c` | **`+0x2220`** |
| `__AUTH_CONST.__objc_const` | `0x1938` | `0x1a70` | **`+0x138`** |
| `__TEXT.__eh_frame` | `0x4a14` | `0x4b44` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x1b98` | `0x1cb8` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x16c2` | `0x17e2` | **`+0x120`** |
| `__AUTH.__data` | `0x1858` | `0x1950` | **`+0xf8`** |
| `__TEXT.__const` | `0x4ca0` | `0x4d90` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x11fc` | `0x1294` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x5d0` | `0x650` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1910` | `0x1988` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0xb38` | `0xbac` | **`+0x74`** |
| `__TEXT.__swift5_reflstr` | `0x99b` | `0x9eb` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x1635` | `0x167b` | **`+0x46`** |
| `__TEXT.__swift_as_cont` | `0x3b4` | `0x3d4` | **`+0x20`** |
| `__DATA.__data` | `0xe58` | `0xe70` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xbb0` | `0xbc0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x158` | `0x164` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-107.0.0.0.0
+111.0.0.0.0

-  Functions: 2065
-  Symbols:   698
-  CStrings:  241
+  Functions: 2105
+  Symbols:   713
+  CStrings:  245
Symbols:
+ __DATA__TtC15ManagedAppsCore17CachedSecKeyProxy
+ __IVARS__TtC15ManagedAppsCore17CachedSecKeyProxy
+ __METACLASS_DATA__TtC15ManagedAppsCore17CachedSecKeyProxy
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.36Tm
+ _symbolic SDySS_____G 15ManagedAppsCore17CachedSecKeyProxyC
+ _symbolic Say_____G 15ManagedAppsCore17CachedSecKeyProxyC19PendingConnectTimer33_41C1CB599C3135FFADE217305E5B2B7FLLV
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic So11SecKeyProxyC
+ _symbolic _____ 15ManagedAppsCore17CachedSecKeyProxyC
+ _symbolic _____ 15ManagedAppsCore17CachedSecKeyProxyC19PendingConnectTimer33_41C1CB599C3135FFADE217305E5B2B7FLLV
+ _symbolic _____ s8DurationV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 15ManagedAppsCore17CachedSecKeyProxyC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15ManagedAppsCore17CachedSecKeyProxyC19PendingConnectTimer33_41C1CB599C3135FFADE217305E5B2B7FLLV
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
+ _type_layout_string 15ManagedAppsCore17CachedSecKeyProxyC19PendingConnectTimer33_41C1CB599C3135FFADE217305E5B2B7FLLV
- _symbolic SDySSSo11SecKeyProxyCG
- _symbolic _____ySSSo11SecKeyProxyCG s18_DictionaryStorageC
CStrings:
+ "Connection timeout for %s; decrementing leaked in-flight count (likely client createIdentity failed)"
+ "SecKeyProxy cache HIT for %{public}s"
+ "SecKeyProxy cache MISS, creating new proxy for %{public}s"
+ "Skipping eviction of %s; %ld in-flight use(s) still pending"
```
