## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3d90` | `0x1c40e0` | **`+0x350`** |
| `__TEXT.__cstring` | `0x75c31` | `0x75dc8` | **`+0x197`** |
| `__TEXT.__objc_stubs` | `0x15040` | `0x150a0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x1b3fd` | `0x1b455` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x7c48` | `0x7c80` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x1c920` | `0x1c900` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x29b8` | `0x29d8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x63b8` | `0x63d0` | **`+0x18`** |
| `__DATA.__common` | `0x68` | `0x60` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1400` | `0x1408` | **`+0x8`** |
| `__TEXT.__const` | `0xe6b` | `0xe73` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.32.0.0.0
+2029.6.0.0.0

+  - /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard

+  - /System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics

+  - /System/Library/PrivateFrameworks/WirelessPerception.framework/WirelessPerception
+  - /System/Library/PrivateFrameworks/WirelessPerceptionRuntime.framework/WirelessPerceptionRuntime

-  Functions: 8814
-  Symbols:   1348
-  CStrings:  17375
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 8779
+  Symbols:   1356
+  CStrings:  17384
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ _kWAMessageKeyPrivateMacHomeNetwork
CStrings:
+ "%s: %@ just transient-joined; skipping re-queue (SeamlessSSIDList not yet updated)"
+ "%s: CarPlay join already in progress on channel %lu, not updating shared state"
+ "%s: No CA prefs on incoming network %@, preserving existing CA=%d"
+ "%s: dropped %ld own-SoftAP beacon entr%s from \"%@\" scan results (MIS broadcasting, userInteractive=%d)"
+ "%s: incoming network %@ carries explicit CA=%d; downstream record swap will apply it over existing %@"
+ "%s: phyMode 0x%x, %s bandWidth %d"
+ "AppleTV"
+ "WiFiManager-2029.6 Sep  4 2026 22:08:44"
+ "WiFiManager-2029.6 Sep  4 2026 22:09:36"
+ "WiFiNetworkHasConnectivityAssistPreference"
+ "WiFiSiriIsCompanionDevice: boot-arg override - allowing HomePod companion devices\n"
+ "reduce to"
+ "restore to"
+ "setPreviousJoinDate:"
+ "setPrivateMacNetworkTypeHome:"
+ "updateCellularWRMScore:forInterface:"
- "%s: dropped %ld own-SoftAP beacon entr%s from client scan results (MIS broadcasting)"
- "%s: phyMode 0x%x, bandWidth %d"
- "WiFiManager-2027.32 Aug 27 2026 20:53:32"
- "WiFiManager-2027.32 Aug 27 2026 20:54:22"
- "WiFiSiriIsCompanionDevice: boot-arg override - allowing Home companion devices"
- "iPad12,1"
- "iPad12,2"
```
