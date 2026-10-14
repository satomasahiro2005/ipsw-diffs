## tvremoted

> `/usr/libexec/tvremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x112d4` | `0x1249c` | **`+0x11c8`** |
| `__TEXT.__oslogstring` | `0x2716` | `0x28ef` | **`+0x1d9`** |
| `__TEXT.__objc_methname` | `0x32e0` | `0x3494` | **`+0x1b4`** |
| `__TEXT.__objc_stubs` | `0x2640` | `0x27e0` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x960` | `0xa00` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0xf7a` | `0xfe3` | **`+0x69`** |
| `__DATA.__objc_selrefs` | `0xcd0` | `0xd38` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0xf54` | `0xfb8` | **`+0x64`** |
| `__DATA.__objc_const` | `0xe60` | `0xe98` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x6f0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x510` | `0x530` | **`+0x20`** |
| `__TEXT.__const` | `0xca` | `0xea` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x340` | `0x358` | **`+0x18`** |
| `__TEXT.__cstring` | `0xb5d` | `0xb4a` | **`-0x13`** |
| `__DATA_CONST.__auth_got` | `0x298` | `0x2a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7c` | `0x80` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-627.10.51.0.0
+627.11.4.0.0

-  Functions: 334
-  Symbols:   164
-  CStrings:  940
+  Functions: 344
+  Symbols:   167
+  CStrings:  970
Symbols:
+ _OBJC_CLASS_$_NSMapTable
+ _dispatch_assert_queue$V2
+ _objc_retain_x25
CStrings:
+ "%{public}@ asked for discovery sources %{public}@"
+ "%{public}@ asked to begin device query with discovery sources %{public}@"
+ "%{public}@ joined the running device query, which only covered %{public}@, and asked for %{public}@; widened it to %{public}@"
+ "%{public}@ left the device query; narrowing it from %{public}@ to %{public}@"
+ "(unknown: 0x%lx)"
+ "@\"NSSet\"32@0:8@\"TVRDClientProcessConnection\"16@\"NSString\"24"
+ "@32@0:8Q16@24"
+ "All"
+ "Companion"
+ "HomeKit"
+ "Q"
+ "Sending %lu of %lu discovered device(s) to %{public}@ (discovery sources %{public}@)"
+ "TQ,N,V_discoverySources"
+ "Union of discovery sources across %lu observer(s): %{public}@"
+ "_closeConnectionToDeviceWithIdentifier:withType:"
+ "_discoverySources"
+ "_sendDiscoveredDevices:toConnection:"
+ "_stateForEachDevice:"
+ "_statesMatchingSources:fromStateForDevice:"
+ "_unionDiscoverySourcesForObservers"
+ "addDiscoverySources:"
+ "beginDeviceQueryWithSources:response:"
+ "clientConnection:identifiersForDeviceWithIdentifier:"
+ "componentsJoinedByString:"
+ "discoverySource"
+ "discoverySources"
+ "objectEnumerator"
+ "removeDiscoverySources:"
+ "setDiscoverySources:"
+ "strongToStrongObjectsMapTable"
+ "v24@0:8Q16"
+ "v32@0:8Q16@?24"
+ "v32@0:8Q16@?<v@?B>24"
+ "|"
- "-[TVRDClientProcessConnection beginDeviceQueryWithResponse:]"
- "beginDeviceQueryWithResponse:"
- "setOfStatesFromDevices:"
- "v24@0:8@?<v@?B>16"
```
