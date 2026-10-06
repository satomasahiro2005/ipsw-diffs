## AppleAccountTransparency

> `/System/Library/PrivateFrameworks/AppleAccountTransparency.framework/AppleAccountTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f2fc` | `0x50778` | **`+0x147c`** |
| `__DATA_DIRTY.__data` | `0x20` | `0xa48` | **`+0xa28`** |
| `__DATA_DIRTY.__bss` | `—` | `0x980` | **`+0x980`** |
| `__DATA.__bss` | `0x2080` | `0x1800` | **`-0x880`** |
| `__AUTH.__data` | `0x9d8` | `0x268` | **`-0x770`** |
| `__TEXT.__cstring` | `0x1689` | `0x1929` | **`+0x2a0`** |
| `__TEXT.__const` | `0x2ac0` | `0x2d00` | **`+0x240`** |
| `__AUTH_CONST.__const` | `0x2208` | `0x2438` | **`+0x230`** |
| `__DATA.__data` | `0x778` | `0x5b8` | **`-0x1c0`** |
| `__AUTH.__objc_data` | `0x4f8` | `0x370` | **`-0x188`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x188` | **`+0x188`** |
| `__TEXT.__eh_frame` | `0x44b8` | `0x43c0` | **`-0xf8`** |
| `__TEXT.__oslogstring` | `0x2beb` | `0x2cdc` | **`+0xf1`** |
| `__TEXT.__constg_swiftt` | `0xce8` | `0xdbc` | **`+0xd4`** |
| `__TEXT.__swift5_typeref` | `0x1007` | `0x10d7` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0xab2` | `0xb72` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0xafc` | `0xbb4` | **`+0xb8`** |
| `__DATA.__common` | `0x70` | `0x8` | **`-0x68`** |
| `__DATA_DIRTY.__common` | `—` | `0x68` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x1f0` | `0x190` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x18d0` | `0x1908` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x708` | `0x734` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x9c8` | `0x9f0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1478` | `0x14a0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x440` | `0x450` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x150` | `0x160` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x1a0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x50` | `0x54` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Other Changes

```diff

-442.0.0.0.0
+444.0.0.0.0

-  Functions: 1339
-  Symbols:   651
-  CStrings:  274
+  Functions: 1361
+  Symbols:   674
+  CStrings:  283
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ __DATA__TtC24AppleAccountTransparency34AATSEARForceNotTransparentProvider
+ __IVARS__TtC24AppleAccountTransparency34AATSEARForceNotTransparentProvider
+ __METACLASS_DATA__TtC24AppleAccountTransparency34AATSEARForceNotTransparentProvider
+ ___swift_closure_destructor.113Tm
+ ___swift_closure_destructor.153Tm
+ ___swift_closure_destructor.191Tm
+ ___swift_closure_destructor.27Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.71Tm
+ ___swift_memcpy104_8
+ ___swift_memcpy224_8
+ ___swift_memcpy32_8
+ ___swift_memcpy40_8
+ ___swift_memcpy80_8
+ _associated conformance 24AppleAccountTransparency13AATSyncReasonOSHAASQ
+ _symbolic $s24AppleAccountTransparency23AETransparencyProvidingP
+ _symbolic BA__________SS______pIeNghHgILgyozo_ 12Transparency28AETransparencyRequestContextC s6UInt64V s5ErrorP
+ _symbolic BA_____________________pIeNghHgILggozo_ 12Transparency28AETransparencyRequestContextC AA014AETVerifyProofC0C AA0eF8ResponseC s5ErrorP
+ _symbolic SDy_____SiG 24AppleAccountTransparency18AATEventIdentifierV
+ _symbolic SS_____Ieghgo_ 12Transparency28AETransparencyRequestContextC
+ _symbolic SS______S2StYaYbKYCc s6UInt64V
+ _symbolic _____ 24AppleAccountTransparency13AATSyncReasonO
+ _symbolic _____ 24AppleAccountTransparency21AATEventPagingContextV
+ _symbolic _____ 24AppleAccountTransparency34AATSEARForceNotTransparentProviderC
+ _symbolic _____AA_Say_____G_____SitYbc 24AppleAccountTransparency15AATVerifyResultV AA19AATransparencyEventV AA13AATSyncReasonO
+ _symbolic ___________t 24AppleAccountTransparency18AATEventIdentifierV AA20AATVerificationStateO
+ _symbolic ______p 24AppleAccountTransparency23AETransparencyProvidingP
+ _symbolic ______pSg 24AppleAccountTransparency24AATAnalyticsEventSendingP
+ _symbolic _____y_____SiG s18_DictionaryStorageC 24AppleAccountTransparency18AATEventIdentifierV
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 24AppleAccountTransparency18AATEventIdentifierV AC20AATVerificationStateO
+ _type_layout_string 24AppleAccountTransparency19AATAnalyticsContextV
+ _type_layout_string 24AppleAccountTransparency21AATEventPagingContextV
- ___swift_closure_destructor.125Tm
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.28Tm
- ___swift_closure_destructor.76Tm
- ___swift_memcpy120_8
- ___swift_memcpy90_8
- _symbolic SS______SStYaYbKYCc s6UInt64V
- _symbolic _____ 12Transparency14AETransparencyC
- _symbolic _____10identifier_______p5errort 24AppleAccountTransparency18AATEventIdentifierV s5ErrorP
- _symbolic _____y_____10identifier_______p5errortG s23_ContiguousArrayStorageC 24AppleAccountTransparency18AATEventIdentifierV s5ErrorP
CStrings:
+ "AATEventProvider - Persisting verification results with resolved counts"
+ "AATEventProvider - Verification results persisted"
+ "AATEventProvider - persistVerificationResults failed: %{public}s"
+ "AATForceNotTransparentOverride"
+ "AATransparencyService: QA override %{public}s active — wrapping SEAR with force-not-transparent decorator"
+ "ALTER TABLE transparency_events ADD COLUMN not_transparent_retry_count INTEGER NOT NULL DEFAULT 0"
+ "CREATE TABLE IF NOT EXISTS transparency_events (\n    alt_dsid TEXT NOT NULL,\n    eventId TEXT NOT NULL,\n    event_timestamp INTEGER NOT NULL,\n    event_type INTEGER NOT NULL,\n    metadata TEXT,\n    hash_algo INTEGER NOT NULL,\n    subtitle TEXT,\n    verification_state INTEGER DEFAULT 0,\n    is_from_transparency_log INTEGER DEFAULT 0,\n    not_transparent_retry_count INTEGER NOT NULL DEFAULT 0,\n    PRIMARY KEY (alt_dsid, eventId, event_timestamp, event_type)\n)"
+ "Duplicate values for key: '"
+ "Fatal error"
+ "INSERT OR IGNORE INTO transparency_events (alt_dsid, eventId, event_timestamp, event_type, metadata, hash_algo, subtitle, verification_state, is_from_transparency_log, not_transparent_retry_count) VALUES(?, ?, ?, ?, ?, ?, ?, ?, ?, ?)"
+ "INSERT OR REPLACE INTO version (id, db_version) VALUES (1, 2)"
+ "SELECT alt_dsid, eventId, event_timestamp, event_type, metadata, hash_algo, subtitle, verification_state, is_from_transparency_log, not_transparent_retry_count FROM transparency_events WHERE alt_dsid = ?"
+ "StoreMigratorAdapter - not_transparent_retry_count column already present; skipping v1→v2 ALTER"
+ "Swift/NativeDictionary.swift"
+ "UPDATE transparency_events SET not_transparent_retry_count = ?, verification_state = ? WHERE alt_dsid = ? AND eventId = ? AND event_timestamp = ? AND event_type = ?"
+ "Verification: events promoted to unverified after retry cap"
+ "[AATAnalyticsContext]: pdpState fetch failed; defaulting to .unknown: %{public}@"
+ "[AATEventNotTransparentHandler] %{private,mask.hash}s: count %ld→%ld finalState=%s"
+ "[AATEventNotTransparentHandler]: retry-cap advanced %ld count(s); %ld promoted to .unverified"
+ "[AATEventPagingController]: Persist verification results failed: %{public}@"
+ "[AATEventPagingController]: Verification failed (non-fatal): %{public}@"
+ "[AATSEARForceNotTransparentProvider]: QA override active — forging %ld event(s) to .eventNotTransparent (key=%{public}s)"
+ "[AATVerificationCoordinator]: Verification failed: %@"
+ "not_transparent_retry_count"
+ "not_transparent_retry_count column"
+ "transparency_events"
- "AATEventProvider - Atomic batch update failed: %{public}s"
- "AATEventProvider - Batch update complete: %ld/%ld succeeded"
- "AATEventProvider - Batch updated atomically"
- "AATEventProvider - Batch updating %ld states"
- "AATEventProvider - Partial batch update failure: %{public}s"
- "AATEventProvider - Updated verified tree head"
- "AATEventProvider - Updating verified tree head for altDSID"
- "CREATE TABLE IF NOT EXISTS transparency_events (\n    alt_dsid TEXT NOT NULL,\n    eventId TEXT NOT NULL,\n    event_timestamp INTEGER NOT NULL,\n    event_type INTEGER NOT NULL,\n    metadata TEXT,\n    hash_algo INTEGER NOT NULL,\n    subtitle TEXT,\n    verification_state INTEGER DEFAULT 0,\n    is_from_transparency_log INTEGER DEFAULT 0,\n    PRIMARY KEY (alt_dsid, eventId, event_timestamp, event_type)\n)"
- "INSERT OR IGNORE INTO transparency_events (alt_dsid, eventId, event_timestamp, event_type, metadata, hash_algo, subtitle, verification_state, is_from_transparency_log) VALUES(?, ?, ?, ?, ?, ?, ?, ?, ?)"
- "INSERT OR REPLACE INTO version (id, db_version) VALUES (1, 1)"
- "SELECT alt_dsid, eventId, event_timestamp, event_type, metadata, hash_algo, subtitle, verification_state, is_from_transparency_log FROM transparency_events WHERE alt_dsid = ?"
- "[AATVerificationCoordinator]: Failed to persist log-only events: %@"
- "[AATVerificationCoordinator]: No verification states to update; skipping"
- "[AATVerificationCoordinator]: Persisted %ld log-only event(s)"
- "[AATVerificationCoordinator]: Persisted verified tree head timestamp"
- "[AATVerificationCoordinator]: Updated %ld verification state(s)"
- "[AATVerificationCoordinator]: Verification or persistence failed: %@"
```
