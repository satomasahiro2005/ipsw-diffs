## wifip2pd

> `/usr/libexec/wifip2pd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x590bb0` | `0x5c7604` | **`+0x36a54`** |
| `__DATA_CONST.__const` | `0x348d8` | `0x38d70` | **`+0x4498`** |
| `__TEXT.__swift5_capture` | `0x62d8` | `0x7c68` | **`+0x1990`** |
| `__TEXT.__oslogstring` | `0x1fa3c` | `0x212dc` | **`+0x18a0`** |
| `__DATA.__bss` | `0x5bad0` | `0x5d050` | **`+0x1580`** |
| `__TEXT.__const` | `0x3e860` | `0x3f500` | **`+0xca0`** |
| `__TEXT.__eh_frame` | `0x1d0b0` | `0x1dc0c` | **`+0xb5c`** |
| `__DATA.__data` | `0x140f8` | `0x148f0` | **`+0x7f8`** |
| `__TEXT.__unwind_info` | `0xfd20` | `0x10380` | **`+0x660`** |
| `__DATA_CONST.__auth_ptr` | `0x7340` | `0x7800` | **`+0x4c0`** |
| `__TEXT.__cstring` | `0xf024` | `0xf468` | **`+0x444`** |
| `__TEXT.__swift5_typeref` | `0xcbd7` | `0xcfe5` | **`+0x40e`** |
| `__TEXT.__constg_swiftt` | `0xfbac` | `0xff84` | **`+0x3d8`** |
| `__TEXT.__swift5_fieldmd` | `0x15ff4` | `0x1630c` | **`+0x318`** |
| `__TEXT.__swift5_reflstr` | `0x14349` | `0x14519` | **`+0x1d0`** |
| `__TEXT.__swift5_proto` | `0x2f1c` | `0x2fe0` | **`+0xc4`** |
| `__DATA.__objc_const` | `0xa590` | `0xa650` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x9e65` | `0x9f05` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x50a0` | `0x50f0` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x2c58` | `0x2ca0` | **`+0x48`** |
| `__DATA.__common` | `0xb08` | `0xb48` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x5a8` | `0x5e4` | **`+0x3c`** |
| `__TEXT.__swift5_types` | `0x1240` | `0x1274` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0x2858` | `0x2880` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x4560` | `0x4580` | **`+0x20`** |
| `__TEXT.__swift5_protos` | `0xf4` | `0x108` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1038` | `0x1028` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x22d7` | `0x22e7` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x150` | `0x160` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1ec` | `0x1f8` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1658` | `0x1660` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-885.62.0.0.0
+885.66.4.1.0

-  Functions: 23756
-  Symbols:   2287
-  CStrings:  5267
+  Functions: 24631
+  Symbols:   2294
+  CStrings:  5381
Symbols:
+ _$s10Foundation4UUIDV1loiySbAC_ACtFZ
+ _$s9CryptoKit12SharedSecretVMn
+ _$sSo12NSDictionaryC10FoundationE12makeIteratorAbCE0D0CyF
+ _$sSo12NSDictionaryC10FoundationE8IteratorC4nextyp3key_yp5valuetSgyF
+ _$ss13DecodingErrorO13dataCorruptedyA2B7ContextVcABmFWC
+ _objc_retain_x11
+ _swift_getTupleTypeMetadata
+ _swift_release_x11
+ _swift_retain_x11
- _swift_release_x12
- _swift_retain_x12
CStrings:
+ " missing pair-setup-enabled and pair-caching attributes"
+ "%@: Clearing discovered peers for %s"
+ "%@: Negotiated Caching Mode: %s handling key commit"
+ "%@: Triggering NIK exchange"
+ "%@: [BLOOM FILTER] Remove for %s"
+ "%@: [Deactivate Pairing Mode] Failed to update SSI: %@"
+ "%@: [Pair Setup] Caching Mode: %s"
+ "%@: [Pair Verify] Caching Mode: %s"
+ "%@: [Publish] [PIK] count: %ld (allowedUUIDs: %s)"
+ "%@: [Subscribe] [PIK] count: %ld (allowedUUIDs: %s)"
+ "%@: pairing caching follow-up frame received but NIK caching is not enabled, ignoring..."
+ "%@: pairing failed: %s"
+ "%@: received: authentication request but no pairing session found: %s"
+ "%@: received: pairing caching follow up but not authenticated state, ignoring..."
+ "%@: resolvedIdentityUUID for %s: %s)"
+ "%@: starting pairing responder timer"
+ "%s %s -> %s"
+ "%s: Authentication frame successfully transmitted to %s"
+ "%s: Authentication frame transmit complete to %s received with failure"
+ "%s: Authentication frame transmit timed out after %ld seconds for frame to %s"
+ "%s: Authentication frame transmit to %s failed with error: %@"
+ "%s: Failed to save PIK: %@"
+ "%s: Indicating auth success to NANDatapathInitiator (Pair Setup)"
+ "%s: No UUID found for PIK in longTermKeyStore to update WiFiAwarePairedDeviceStore"
+ "%s: No pairing metadata available to update WiFiAwarePairedDeviceStore"
+ "%s: PIK post-commit flow failed: %@"
+ "%s: Starting timer to monitor auth transmit"
+ "%s: Updated WiFiAwarePairedDeviceStore with metadata: %s, UUID: %s, DeviceID: %llu"
+ "%s: Updating WiFiAwarePairedDeviceStore with metadata: %s UUID: %s"
+ "%s: triggering core capture..."
+ "2c5e414bd06214341396a4751bed8325e9a5988daae86dad51cfcd9f303ae172"
+ "AWDL schedule changed in non-RTG mode — skipping needsIR re-evaluation"
+ "AWDLDiscoveryTimeout: Disabling AWDL - display off, accumulated %lds >= threshold %lds across repeated short AP wakes. Browse: [%s], Advertise: [%s], Clients: [%s]"
+ "AWDLDiscoveryTimeout: PowerLog framework not available - skipping telemetry donation for: %s"
+ "AWDLDiscoveryTimeout: Wake inactivity check - allowed client present, skipping disable"
+ "AWDLDiscoveryTimeout: Wake inactivity check - display off, accumulator=%lds, threshold=%lds"
+ "AWDLDiscoveryTimeout: Wake inactivity check - excluded service present, skipping disable"
+ "AWDLDiscoveryTimeout: Wake inactivity check - feature disabled, skipping"
+ "AWDLDiscoveryTimeout: Wake inactivity check - not yet timed out (%lds < %lds)"
+ "AWDLDiscoveryTimeout: Wake inactivity check skipped - display turned on since wake"
+ "AWDLDiscoveryTimeout: Wake inactivity check skipped - timer reset %s ago (activity in flight)"
+ "Authentication frame transmit timed out after "
+ "Caching Mode - Self: %s, Peer: [%s], Negotiated: %s"
+ "Cannot create new datapath for %@ to %s[%hhu] because connection mode is %s but unable to establish a pairing session"
+ "Cannot generate a PASN confirmation for the PASN response from %s because DCEA is missing or pikSupported bit is not set"
+ "Cannot generate a PASN confirmation for the PASN response from %s because no IRSA was found"
+ "Cannot generate a PASN confirmation for the PASN response from %s because no valid PTag was found in IRSA"
+ "Cannot generate a PASN response for the PASN request from %s because DCEA is missing or pikSupported bit is not set"
+ "Cannot generate a PASN response for the PASN request from %s because no IRSA was found"
+ "Cannot generate a PASN response for the PASN request from %s because no valid PTag was found in IRSA"
+ "Cannot generate a PASN response for the PASN request from %s because the DCEA is missing"
+ "Cannot generate a PASN response for the PASN request from %s because the peer does not support PIK or NIK caching mode"
+ "Cannot send pairing caching follow-up frame, NIK is nil"
+ "Cannot start pair verify, NIK is nil"
+ "Device identity %s for %s not found in LongTerm Pairing Keystore"
+ "Existing entry found for: %s. Falling back to update."
+ "Failed generate a PASN confirmation for the PASN response from %s: DCEA is not present in the PASN response"
+ "Failed generate a PASN confirmation for the PASN response from %s: peer does not support PIK or NIK caching mode"
+ "Failed to addOrUpdate item for: %s using: %s. Error: %d"
+ "Failed to create NANPMK.ID from nonce and pTag"
+ "Failed to decode paired peer association from keychain data for UUID: %s, error: %@"
+ "Failed to decrement usage count: no paired peer found for account %s"
+ "Failed to delete item for: %s. Error: %d"
+ "Failed to find pairing session for %s"
+ "Failed to increment usage count: no paired peer found for account %s"
+ "Failed to migrate NAN Pairing key store: %@"
+ "Failed to reinstall peer after decrementing usage count — peer may be lost: %@"
+ "Failed to reinstall peer after incrementing usage count — peer may be lost: %@"
+ "Failed to save PIK: "
+ "Invalid PIK key material length: got %ld bytes, expected %ld"
+ "Migrate: Failed to delete legacy paired peer for UUID: %s, error: %s"
+ "Migrate: Failed to delete unmigrateable legacy paired peer for UUID: %s, error: %s"
+ "Migrate: Failed to migrate paired peer association for UUID: %s, deleting from legacy store"
+ "Migrate: Failed to parse keychain results for paired peer migration"
+ "Migrate: Failed to query keychain for paired peer migration, error: %d"
+ "Migrate: Migrated paired peer association for UUID: %s"
+ "Migrate: Migrating paired peers from '%s' to '%s'"
+ "Migrate: No legacy paired peers found in '%s', migration complete"
+ "Migrate: Secure storage provider is not set"
+ "Migrate: error decoding legacy paired peer association for UUID: %s"
+ "Migrate: failed to install peer for UUID: %s: %@"
+ "Migrating legacy paired peer association for UUID: %s to new format"
+ "NANPairingInitiator: Could not start authentication for pair verify"
+ "No TIK found for %s [Paired Device UUIDs: %s]. Cannot start TDS request."
+ "No existing entry for: %s. Added as a new item."
+ "No initiator NIRA in the auth request"
+ "Paired Peer: Cannot save pairing identity since state is not confirmed! state: %s"
+ "Paired Peer: Installing peer PIK"
+ "Paired peer with same key, already exists in LongTerm Pairing Keystore!"
+ "Pairwise PIK Derivation"
+ "Peer %s caching: NIK=%{bool}d PIK=%{bool}d"
+ "PowerLog framework not available - skipping telemetry setup"
+ "Resetting subscribe discovery results for %s"
+ "Retaining pairing session for: %s, UsageCount: %ld"
+ "Setting up a pair setup session using method %hu, pairing caching mode %s for security for the datapath from %@ to %s[%hhu]"
+ "Stored association PIK but frame does not carry IRSA"
+ "Successfully addOrUpdated using query: %s"
+ "Successfully deleted using query: %s"
+ "TDS"
+ "Unknown NANPairedDeviceAssociation discriminator: "
+ "WiFiAware"
+ "WiFiAwarePairing"
+ "WiFiP2P-885.66.4.1 Jun 16 2026 22:06:39"
+ "[%s]: IRSA match found!"
+ "[%s]: NIRA match found!"
+ "[%s]: No cached IRSA"
+ "[%s]: No matching identity found for IRSA: %s"
+ "[%s]: No matching identity found for NIRA"
+ "[ADD] Pruning %ld expired entr(ies) from %s for account %s: %s"
+ "[Create Pairing Initiator] failed. Already paired with publisher (%s):  %s"
+ "[IRSA] %s, Key: %s, MAC: %s, Nonce: %s"
+ "[IRSA] %s, Key: %s, MAC: %s, Nonce: %s, CalculatedTag: %s, OTATag: %s"
+ "[PIK] nmKDK: %s, initiatorAddress: %s, responderAddress: %s -> [PIK] %s NPK: %s"
+ "[SIG PAYLOAD] eleResponder: %s, eleInitiator: %s, scaResponder: %s, scaInitiator: %s, IPK: %s, responderNMI: %s, initiatorNMI: %s -> %s"
+ "_PPSCreateTelemetryIdentifier"
+ "_PPSSendTelemetry"
+ "_usageCounter"
+ "authentication request received but no pairing session found"
+ "bootstrap response status: comeback value is invalid"
+ "bootstrap response status: none"
+ "code"
+ "com.apple.nan.pairing"
+ "d659f84d16924f1c39d80884be5e8f79818a514efd60aabef6020a8d5409d2b1"
+ "doNeedIR inputs: selfInfra=%s peerInfra=%s awdlNonSocial=%s rtgActive=%{bool}d retroMode=%{bool}d"
+ "enablePIKCaching"
+ "initWithExpiration:bootstrappingRecords:"
+ "initiatorKey initiatorNonce responderKey responderNonce "
+ "isPowerLogAvailable"
+ "key nonce "
+ "log"
+ "nanPairingServiceLegacy"
+ "no paired peer association for ID "
+ "no resolved identity UUID for peer "
+ "no responder NIRA in custom attributes"
+ "no valid PTag found in IRSA for "
+ "pairing auth: resolved UUID:%s, forming a new responder instance"
+ "pairingIdentityKey"
+ "pairingIdentityKeys"
+ "received: pairing caching follow up with no SKDA!"
+ "v1"
+ "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"06e308ff17389ec7b619b2d05f93c046207d9d6fc5dbe44a3614b918e32e5e6d\": {\n      \"WiFiAwareServices\": {\n        \"6bf0d3d1e86960827f9c44c2392a16ebffea8d973f9be7e7e3881847be2c932f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6c1855feca311a669da2c5309719a1e05166d793fbc50514533ec13165b2ead3\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"ed590eb71c6522ef82835ed68a56c8a8ab10feb7fe5c9eaa4931eb0d61c6b365\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"44b5cb1a865ac7750879dd00876e31e705419230572d3a10e2746f834b13703c\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"5f979200b5ff8db6111cd34b21b0607f1e014d010da7ebfa412257a6cedbebe2\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"4759c69b5e4b1f261ab93d4d2647d1c0a7a08e29c9769e982e34e3b200773d80\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"cb9bb80e2b152468ecd35a7ac2148a6bf81d000bfdbc1c08213c90f9e3129a3a\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"e617a68f619b9a16ca896750789e19a5f7f13ad585b186ca7456888345d8d757\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"ccfab4fca229ef92196e8799d1ec22dbe0bec4f12622a2c2fbc0fef646a97a91\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"dc18bd71fbb4ce98a8573d9b9fe1bfa42925f8cffa41d07f89afb29a441596e4\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"60a7d55bef29bb20bfbb9445d95cf3fbb5fa2aad3afc9221a468e3ece2dd822b\": {\n      \"WiFiAwareServices\": {\n        \"a7ce03d1841c9ac7ba2a7751d4dab7c41eb464e1f179c61018250a996a05e09e\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"88a10952bca82277b29523b5c7c5a34c7dcee70c1a3fb1bab4610f3fe18af823\": {\n      \"WiFiAwareServices\": {\n        \"9db85231f63b02d86d9e70bff1e141a27e9da33bfd413222bbbae3cf21d58065\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"63b2f8679b75ce4efccffbd9207122825b373b92654423164081d25d4d5e3dd2\": {\n      \"WiFiAwareServices\": {\n        \"f591564cb5eaba2174f7511fad893f35b66c8173bef1225883c3b4ac2a82af05\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e93a83282e900ba125ff4270c119b636d2397ad89c0f332e977af96389711275\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"e441dc3c91e6e344c8f62c1e139c8ed939dafa7bf7c9ef4fa6aab5efe68b6f47\": {\n      \"WiFiAwareServices\": {\n        \"a7ce03d1841c9ac7ba2a7751d4dab7c41eb464e1f179c61018250a996a05e09e\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"8da2555a072651873a964190814e137381a7e7ce7a6b02ece627b7d3bbf6f6ea\": {\n      \"WiFiAwareServices\": {\n        \"9db85231f63b02d86d9e70bff1e141a27e9da33bfd413222bbbae3cf21d58065\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
+ "{\n  \"f9d4647aab00eb631c796b4d67581df1fce4afd8575f1e1039d318ebf97d8501\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"fb00987497584ef1ef5b95d6df6da85203dfe3637ed82c64bbd4c3be9fd615a0\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"79255e637ba59df8e37bdc0abbe4772998b7987a677a71c484dc24f269b4e247\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"3b5d9fed4d072a429700e2fbf5b1e084f3e7e7cc28794973b3c1396ff3f273f7\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"95b04ad82af9b9b1f06786220d3f8436ab8fee3bc4cfb644dc3e067f152536ea\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"3bdd268cfcb15ae333ee8b5f2aceb5ca471e2c7c124e0380c667188c9ea76523\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"0e0b82b0e23029391431af70d5ef0a90ee722acc9b6e600792fafbae95b1602f\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"f672599f6242b6b8b207d86a39365c5c2280b5e0b30a3e178e549f511862cb31\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"b35aabfc609cffa539d8515d821f1c8b68f309e29289b2a4908d46ad98842de4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"2375f0d1d86b521d30842ded4b9d3619c79232f32c08c8dc779d6caff9a93e2a\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"2efa58c641b124eea32d5f15df434872e3cc6338f415effdc87d460bd47f4bf7\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"d56e005815c1118018221a4fc6d8ddd8d1476d4636006610bfd4c1e4f014acb1\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"13e5b90a431dd5fef68ab5b7dab45491fe3d24344e4ebd79e10c2da6e1a10a17\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
- "%@ starting pairing responder timer"
- "%@: Cannot send pairing caching follow-up frame, NIK is nil"
- "%@: Cannot start pair verify, NIK is nil"
- "%@: Pairing responder timer fired."
- "%@: bootstrap response status: comeback value is invalid"
- "%@: bootstrap response status: none"
- "%@: pairing failed"
- "%@: received: authentication request but no pairing session found"
- "%@: received: pairing caching follow up but not authenticated state!"
- "%@: received: pairing caching follow up with no shared key descriptor!"
- "%@: was started for pair verify"
- "3fd8afe8ecaa28976451b914837329795d3b81d5e8c4da910ff538d6837d3da0"
- "8ef06e8b9c4834ccf583109b6af0ba201b487ff02c94993ba9dca67cf6f717b7"
- "Could not start authentication for pair verify"
- "Paired peer with same NIK already exists in LongTerm Pairing Keystore!"
- "Setting up a pair setup session using mode %s, pairing caching %{bool}d for security for the datapath from %@ to %s[%hhu]"
- "WiFiP2P-885.62 May 29 2026 21:05:33"
- "[%s]: No matching identity found for: %s"
- "[Create Pairing Initiator] failed. Already paired with publisher:  %s"
- "[IRSA] %s, Key: %s, OTATag: %s, CalculatedTag: %s"
- "[SIG PAYLOAD] elePub: %s, scaPub: %s, eleSub: %s, scaSub: %s, IPK: %s, PubNMI: %s, SubNMI: %s -> %s"
- "authentication request but no pairing session found"
- "doNeedIR inputs: selfInfra=%s peerInfra=%s awdlNonSocial=%s retroMode=%{bool}d"
- "enableNANPairing"
- "initWithexpiration:bootstrappingRecords:"
- "pairing auth: Cached paired peer UUID:%s was found, forming a new responder instance"
- "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"305e0e65b8035df5812854082da347262a8e61bc5775e94e0617137a821d6de5\": {\n      \"WiFiAwareServices\": {\n        \"e0cff9f2c8474d4ba7b43d3485afd037aeb8a0f93366ad44cc54503cd22556c6\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"27ec253cae9beb7e22141591fef201690e3cf898e566fcb956a74796bc77bc05\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6e89495cf1daca4de96c0f2db191ee3d93cb6bde06e62238ffc71db5fd5642be\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e85c3b65ae30ee31cefd73d83a17061a5331ad9722162ff79d7c53f1a8d7d4d0\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6e8189f9b86299fe9b7f8778e8646398a2cf364a2a16e0e1f9480abc5eb1354b\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"42dd759cec46a0ae87274e5eb9355a088b89108b5c11f6fbd01638f4e667b972\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"e0d2e524127b37fb900f0b59078705affeec0b810652a3b5fd53a3706e24d616\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"e3295d7afd33ca5305bfebb527fe3ea911fed5351e53add620efe8fff4856a90\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"2b992920cca58595be3751541237e569e946b0ac183b502dbb327b2e5ad85db6\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"3138993baebb90df7a2bebb781e52976a4d232569b63e7402ad53d9abbab868c\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"d6842079b7a39215da684a42ed7c1f4bf14c949e6863a95ee143f7b74f47f6aa\": {\n      \"WiFiAwareServices\": {\n        \"5cbdd8d74523775c7ec57d21a958041ccf91ce9d66a30dcc22f4b8215076d3e2\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"3e74f066e059c438925f70bea10fa2fa924468127f4cf3464848b96c408d23d3\": {\n      \"WiFiAwareServices\": {\n        \"57546e8dc5a327715a70feda78e1abb79a51879bc0b6c4e029110a06ac72b1b7\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"d71e0e8a00e3a1aefb3dcacdfa0b8a8dc75b8597ce66a4d0c8505b9bf7f66ba1\": {\n      \"WiFiAwareServices\": {\n        \"b54e8fef5f102116c2db49bb752609ce15c5d9d7e352074d5986034f3c7cc133\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"85f743e10dd07bf60f8e12d76d82b2d04388edf68037eba0cdedadd131925ae7\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"4b0f21cc310143e153f4575c882d37b9e77cb703cabbe6c7d31a686a572a0f5b\": {\n      \"WiFiAwareServices\": {\n        \"5cbdd8d74523775c7ec57d21a958041ccf91ce9d66a30dcc22f4b8215076d3e2\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"4570f4e58b1103dced4c1e45b08d65a35e0e00bf1c227729d15668d2030efacc\": {\n      \"WiFiAwareServices\": {\n        \"57546e8dc5a327715a70feda78e1abb79a51879bc0b6c4e029110a06ac72b1b7\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
- "{\n  \"cc661bac93bac668014c7d896f3faac5fb6062f672bef728581426b4117ce212\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"9ada11881b02e5bcd6bb7d82bbb2221d58669078ddb0c20a03fb33a5c01f23fa\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"e6e85f598f80fdf8f476d6742e770f554186dc98d744d381755a885a8c46ef56\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"c29e2ae5aea053ebf87c430eda32f8c78afbb6383533443788521b3dc4f7a197\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"344a2427ff227c794dea6772e9a74f13ded40ce8427b4dc49e0bdeaeed82ba19\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"ce53480d09e8270925418558c8ddd2f3672ebb3f70306fc0f215c52602c54f68\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"abf23359718a11f50e3eff30332dfd80ffc76930fb14e9efb17ab91f1772ad2a\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"9dc74f57a615b05b0f0f86eb3261c036f99b038b594e8961143544b805942b29\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"d3e58d528668573fb32cb8e6585ea7e948d262c7469ea62a2d4dc4bfd4e19fba\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"d2cdd1269740576a27676c4064c9e14d5b361acf2889c9bade160a98fe2fd208\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"7b3733aede85d85cbec4509929a32adcd8f75034d53c8af41b22d9b327fbf7d5\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"87f8e89cb9f98f831a8daf1b665cec943cc85b60457efa6f12f1124d2ba8e014\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"4d59cc5724227937820972d8cbe5f83ef2f48483761967caae0a4c881fb1f468\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
```
