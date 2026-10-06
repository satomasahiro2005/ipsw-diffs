## HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2473c` | `0x25eb4` | **`+0x1778`** |
| `__DATA_CONST.__cfstring` | `0x23a0` | `0x29a0` | **`+0x600`** |
| `__TEXT.__oslogstring` | `0x4cd3` | `0x503b` | **`+0x368`** |
| `__TEXT.__cstring` | `0x1bec` | `0x1ef6` | **`+0x30a`** |
| `__TEXT.__objc_stubs` | `0x3aa0` | `0x3d60` | **`+0x2c0`** |
| `__TEXT.__objc_methname` | `0x3ed3` | `0x3fe8` | **`+0x115`** |
| `__DATA.__objc_selrefs` | `0x12f8` | `0x13a8` | **`+0xb0`** |
| `__TEXT.__ustring` | `—` | `0x54` | **`+0x54`** |
| `__DATA_CONST.__const` | `0x838` | `0x878` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x990` | `0x9b0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x748` | `0x760` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x4d8` | `0x4e8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1493.1.5.1.1
+1514.0.0.0.1

-  Functions: 628
-  Symbols:   301
-  CStrings:  1598
+  Functions: 634
+  Symbols:   303
+  CStrings:  1683
Symbols:
+ _HMAccessoryTransportTypesToString
+ _HMResidentDeviceStatusDescription
CStrings:
+ "\nNo homes found.\n"
+ "      - \"%@\" [%@] %@%@\n"
+ "    - \"%@\" %@%@ status=%@ enabled=%@\n"
+ "    Blocked: %@\n"
+ "    Bridged: %@\n"
+ "    Category: %@ (%@)\n"
+ "    Device ID: %@\n"
+ "    Firmware: %@\n"
+ "    Identifier: %@\n"
+ "    Manufacturer: %@\n"
+ "    Matter Node ID: %@\n"
+ "    Model: %@\n"
+ "    Reachable Transports: %@ (0x%lX)\n"
+ "    Reachable: %@\n"
+ "    Room: %@\n"
+ "    Serial: %@\n"
+ "    Services (%lu):\n"
+ "    Transport Types: %@ (0x%lX)\n"
+ "  Accessories: %lu\n"
+ "  Accessory: \"%@\"\n"
+ "  Hub State: %@\n"
+ "  Identifier: %@\n"
+ "  Primary: %@\n"
+ "  Residents (%lu):\n"
+ "  Rooms: %lu\n"
+ "  ✓ Home app Spotlight donations collected"
+ "  ✓ homed Spotlight donations collected"
+ "  ✓ homeutil mini dump collected"
+ "  ✗ Failed to collect Home app Spotlight donations"
+ "  ✗ Failed to collect homed Spotlight donations"
+ " (primary)"
+ "%@ / 0x%llX"
+ "%@-spotlight-donations.txt"
+ "(unknown)"
+ "<private>"
+ "AirPlay"
+ "BLE"
+ "Connected"
+ "Disconnected"
+ "Failed to write homeutil mini dump: %@"
+ "Generated: %@\n"
+ "Home App Spotlight Donation"
+ "Home: \"%@\"\n"
+ "IP"
+ "Not Available"
+ "Refusing homeutil mini dump on non-customer/SEED build"
+ "Refusing homeutil mini dump without user consent"
+ "Resident"
+ "STEP %lu/%lu: Collecting Home app Spotlight Donations"
+ "STEP %lu/%lu: Collecting homed Spotlight Donations"
+ "Unknown (%lu)"
+ "[%{public}@]   ✓ Home app Spotlight donations collected"
+ "[%{public}@]   ✓ homed Spotlight donations collected"
+ "[%{public}@]   ✓ homeutil mini dump collected"
+ "[%{public}@]   ✗ Failed to collect Home app Spotlight donations"
+ "[%{public}@]   ✗ Failed to collect homed Spotlight donations"
+ "[%{public}@] Failed to write homeutil mini dump: %@"
+ "[%{public}@] Refusing homeutil mini dump on non-customer/SEED build"
+ "[%{public}@] Refusing homeutil mini dump without user consent"
+ "[%{public}@] STEP %lu/%lu: Collecting Home app Spotlight Donations"
+ "[%{public}@] STEP %lu/%lu: Collecting homed Spotlight Donations"
+ "[%{public}@] customerOS / SEED build: consent=%@"
+ "[CURRENT] "
+ "[PRIMARY] "
+ "accessories"
+ "category"
+ "categoryType"
+ "customerOS / SEED build: consent=%@"
+ "firmwareVersion"
+ "homeHubState"
+ "homed Spotlight Donation"
+ "homeutil Mini Dump"
+ "homeutil Mini Dump\n"
+ "homeutil-mini-dump.txt"
+ "isBlocked"
+ "isBridged"
+ "isEnabled"
+ "isPrimary"
+ "isPrimaryService"
+ "isReachable"
+ "localizedDescription"
+ "manufacturer"
+ "matterNodeID"
+ "model"
+ "reachableTransports"
+ "rooms"
+ "search -b com.apple.%@ -A"
+ "serialNumber"
+ "serviceType"
+ "services"
+ "transportTypes"
+ "uniqueIdentifier"
+ "|"
+ "════════════════════════════════════════\n"
- "  ✓ Spotlight donations collected"
- "  ✗ Failed to collect Spotlight donations"
- "STEP %lu/%lu: Collecting Spotlight Donations"
- "Spotlight Donation"
- "[%{public}@]   ✓ Spotlight donations collected"
- "[%{public}@]   ✗ Failed to collect Spotlight donations"
- "[%{public}@] STEP %lu/%lu: Collecting Spotlight Donations"
- "homed-spotlight-donations.txt"
- "search -b com.apple.homed -A"
```
