## shazamd

> `/System/Library/Frameworks/ShazamKit.framework/shazamd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ee50` | `0x4f59c` | **`+0x74c`** |
| `__TEXT.__objc_stubs` | `0xcf60` | `0xd160` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x10b7a` | `0x10d4d` | **`+0x1d3`** |
| `__DATA.__objc_const` | `0xcbb0` | `0xccf0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x4c58` | `0x4d63` | **`+0x10b`** |
| `__TEXT.__objc_methlist` | `0x6094` | `0x615c` | **`+0xc8`** |
| `__DATA_CONST.__cfstring` | `0x25c0` | `0x2680` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x2f50` | `0x2ff0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x2b89` | `0x2c20` | **`+0x97`** |
| `__DATA.__objc_selrefs` | `0x3a98` | `0x3b20` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x14a0` | `0x14d0` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x13a1` | `0x13c8` | **`+0x27`** |
| `__DATA_CONST.__got` | `0x848` | `0x858` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__DATA.__bss` | `0x110` | `0x118` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x370` | `0x378` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x3043` | `0x303d` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-427.0.33.0.0
+427.0.36.0.0

-  Functions: 1869
-  Symbols:   443
-  CStrings:  3888
+  Functions: 1883
+  Symbols:   445
+  CStrings:  3918
Symbols:
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_NSDateComponents
+ _OBJC_CLASS_$_NSTimeZone
- _OBJC_CLASS_$_SHRotatingInstallationID
CStrings:
+ "@32@0:8d16@24"
+ "Dropping malformed entry — installationID: %@, creationDate: %@"
+ "SHInstallationID"
+ "SHInstallationIDEntry"
+ "Skipping rematch storage, client opted out of storing the signature on no match"
+ "T@\"NSDate\",R,C,N,V_creationDate"
+ "UTC"
+ "Using new installation ID: %@ for client: %@ (creationDate: %@)"
+ "_creationDate"
+ "_entryForClientIdentifier:"
+ "_initWithClientIdentifier:clientType:musicalFeaturesConfiguration:"
+ "_setEntry:forClientIdentifier:"
+ "ageInSeconds"
+ "ageInSeconds for installationID: %@ — wallClockAge: %f"
+ "cachedInstallationForDays:clientIdentifier:"
+ "cachedInstallationIDForUTCDayForClientIdentifier:"
+ "cachedInstallationIDWithMaxAge:forClientIdentifier:"
+ "com.apple.shazamd.installation-id"
+ "com.apple.shazamd.installation-id-creation-date"
+ "com.apple.shazamd.installation-ids"
+ "creation-date"
+ "currentCalendar"
+ "dateByAddingComponents:toDate:options:"
+ "defaultCachedInstallationIDForClientIdentifier:"
+ "deleteOldINIDData"
+ "dictionaryForKey:"
+ "dictionaryRepresentation"
+ "entryWithDictionary:"
+ "initWithClientBundleIdentifier:clientType:requestSignatures:"
+ "initWithClientIdentifier:clientType:musicalFeaturesConfiguration:"
+ "initWithInstallationID:creationDate:"
+ "initWithMatcher:notificationScheduler:clientCredentials:networkPathMonitor:remoteConfiguration:"
+ "installation-id"
+ "setDay:"
+ "setTimeZone:"
+ "startOfDayForDate:"
+ "taskForClientBundleID:clientType:signatures:"
+ "timeIntervalSinceNow"
+ "timeZoneWithName:"
- "@48@0:8@16q24@32@40"
- "T@\"NSString\",R,N,V_installationID"
- "_initWithClientIdentifier:clientType:installationID:musicalFeaturesConfiguration:"
- "defaultCachedInstallationID"
- "initWithClientBundleIdentifier:clientType:installationID:requestSignatures:"
- "initWithClientIdentifier:clientType:installationID:"
- "initWithClientIdentifier:clientType:installationID:musicalFeaturesConfiguration:"
- "setInstallationID:"
- "taskForClientBundleID:clientType:signatures:installationID:"
```
