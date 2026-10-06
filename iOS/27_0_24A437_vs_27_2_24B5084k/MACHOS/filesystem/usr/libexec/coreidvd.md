## coreidvd

> `/usr/libexec/coreidvd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f8be4` | `0x6fddc0` | **`+0x51dc`** |
| `__TEXT.__unwind_info` | `0x16678` | `0x16b10` | **`+0x498`** |
| `__DATA.__bss` | `0x385b0` | `0x38930` | **`+0x380`** |
| `__TEXT.__const` | `0x32b20` | `0x32d70` | **`+0x250`** |
| `__TEXT.__cstring` | `0x299da` | `0x29b6a` | **`+0x190`** |
| `__DATA.__data` | `0x183d8` | `0x18540` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x2ee39` | `0x2ef69` | **`+0x130`** |
| `__TEXT.__swift5_typeref` | `0xc13c` | `0xc225` | **`+0xe9`** |
| `__TEXT.__auth_stubs` | `0xd3d0` | `0xd450` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0xe644` | `0xe6c0` | **`+0x7c`** |
| `__DATA_CONST.__const` | `0x254f0` | `0x25560` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0xdb3c` | `0xdba8` | **`+0x6c`** |
| `__DATA_CONST.__got` | `0x42c0` | `0x4320` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xdcc6` | `0xdc76` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x69f8` | `0x6a38` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x4abe` | `0x4a7e` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x6500` | `0x64cc` | **`-0x34`** |
| `__TEXT.__swift5_reflstr` | `0xc1ae` | `0xc1cd` | **`+0x1f`** |
| `__TEXT.__swift5_proto` | `0x1e34` | `0x1e50` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x2420` | `0x2438` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x3844` | `0x3830` | **`-0x14`** |
| `__TEXT.__swift_as_entry` | `0x1338` | `0x1324` | **`-0x14`** |
| `__TEXT.__swift_as_ret` | `0x1c64` | `0x1c50` | **`-0x14`** |
| `__TEXT.__objc_methlist` | `0x214c` | `0x213c` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0xc34` | `0xc44` | **`+0x10`** |
| `__DATA.__common` | `0x722` | `0x730` | **`+0xe`** |
| `__DATA.__objc_const` | `0x11890` | `0x11888` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x25c8` | `0x25c0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-9.42.0.0.0
+9.104.0.0.0

-  Functions: 18915
-  Symbols:   5980
-  CStrings:  8501
+  Functions: 18960
+  Symbols:   6001
+  CStrings:  8512
Symbols:
+ _$s10Foundation12CharacterSetV17controlCharactersACvgZ
+ _$s10Foundation12CharacterSetV5unionyA2CF
+ _$s10Foundation12CharacterSetV8containsySbs7UnicodeO6ScalarVF
+ _$s10Foundation12CharacterSetV8newlinesACvgZ
+ _$s10Foundation12CharacterSetVMn
+ _$s10Foundation4DateVSEAAMc
+ _$s10Foundation4DateVSeAAMc
+ _$s13CoreIDVShared26DaemonInternalDefaultsKeysO20MobileDocumentReaderO023disableFilteringVICALByH4TypeSSvgZ
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO16givenNameUnicodeyA2CmFWC
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO17familyNameUnicodeyA2CmFWC
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO19residentCityUnicodeyA2CmFWC
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO22residentAddressUnicodeyA2CmFWC
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO23issuingAuthorityUnicodeyA2CmFWC
+ _$s13CoreIDVShared30ISO18013_5_1_ElementIdentifierO14residentStreetyA2CmFWC
+ _$s13CoreIDVShared46ReaderAuthenticationAllowableElementsProvidingMp
+ _$s13CoreIDVShared8DIPErrorV4CodeO31webPresentmentInvalidDeviceNameyA2EmFWC
+ _$s20CoreIDVDaemonSupport26AlternativeElementMappingsO11alternative3for10identifierSaySaySS9namespace_SSAFtGGSS_SStFZ
+ _$s7CoreIDV21MobileDocumentElementV0A16IDVDaemonSupportE10namespaces3for26includeNonParsableElements0j10DeprecatedM009allowableM025userDefaultsConfigurationSaySS9namespace_SS10identifiertGAA0cD4TypeV_S2b0A9IDVShared029ReaderAuthenticationAllowableM0VSgAP04UserqR0CtKF
+ _$s7CoreIDV21MobileDocumentElementV0A16IDVDaemonSupportE10namespaces3for26includeNonParsableElements0j10DeprecatedM009allowableM025userDefaultsConfigurationSaySS9namespace_SS10identifiertGAA0cD4TypeV_S2b0A9IDVShared029ReaderAuthenticationAllowableM0VSgAP04UserqR0CtKFfA1_
+ _$s7CoreIDV21MobileDocumentElementV0A16IDVDaemonSupportE10namespaces3for26includeNonParsableElements0j10DeprecatedM009allowableM025userDefaultsConfigurationSaySS9namespace_SS10identifiertGAA0cD4TypeV_S2b0A9IDVShared029ReaderAuthenticationAllowableM0VSgAP04UserqR0CtKFfA3_
+ _$sSS17UnicodeScalarViewV13_foreignIndex6beforeSS0E0VAF_tF
+ _$sSS17UnicodeScalarViewV6appendyys0A0O0B0VF
+ _$sSS17UnicodeScalarViewVySsAAVSnySS5IndexVGcig
+ _$sSSySSSs17UnicodeScalarViewVcfC
- _$s13CoreIDVShared26DaemonInternalDefaultsKeysO20MobileDocumentReaderO013filterVICALByH4TypeSSvgZ
- _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO8rawValueACSgSS_tcfC
- _$s7CoreIDV21MobileDocumentElementV0A16IDVDaemonSupportE10namespaces3for26includeNonParsableElementsSaySS9namespace_SS10identifiertGAA0cD4TypeV_SbtKF
CStrings:
+ "Failed to persist Tap-to-Radar filing record: %{public}@"
+ "Failed to read Tap-to-Radar filing record, resetting it: %{public}@"
+ "Not drafting Tap-to-Radar '%{public}s': already filed the maximum number of times for this credential"
+ "Requesting device name is empty after sanitization, denying request"
+ "TAC contains requisite allowed document types to perform the request"
+ "The operation ID for save records is %{public}s"
+ "account-key-generation"
+ "buildDocumentRequest(with:sessionTranscript:trustedIssuerRoots:logotypeIconData:externalData:allowableElementsProvider:)"
+ "dataForKey:"
+ "device-encryption-key-generation"
+ "documentRequestComponents(trustedIssuerRoots:userDefaultsConfiguration:allowableElementsProvider:includeDeprecatedElements:)"
+ "key-signing-key-generation"
+ "missing-pii-token"
+ "orphaned-wallet-pass-credential"
+ "orphaned-wallet-pass-pii-token"
+ "payload-ingestion"
+ "pii-hash-mismatch"
+ "presentment-key-generation"
+ "proofing-pii-hash-mismatch"
+ "proofingPIIHashMismatch already at its filing limit for this credential, skipping TTR alert and upload"
+ "retained-pii-token-with-wallet-pass"
+ "showTTRAlert(proofingSessionID:credentialIdentifier:encryptedCredentialPII:encryptedNFCPII:)"
+ "tap-to-radar.filing-limit-record"
- "Request contains disallowed elements: "
- "Setting modified global bound ACL"
- "TAC contains requisite allowed document types and elements to perform the request"
- "The operation ID for save records is %s"
- "buildDocumentRequest(with:sessionTranscript:trustedIssuerRoots:logotypeIconData:externalData:)"
- "documentRequestComponents(trustedIssuerRoots:userDefaultsConfiguration:)"
- "setModifiedGlobalAuthACL:externalizedLAContext:completion:"
- "setModifiedGlobalBoundACL(data:externalizedLAContext:)"
- "setModifiedGlobalBoundACLWithData:externalizedLAContext:completionHandler:"
- "showTTRAlert(proofingSessionID:encryptedCredentialPII:encryptedNFCPII:)"
- "v40@0:8@\"NSData\"16@\"NSData\"24@?<v@?@\"NSArray\"@\"NSError\">32"
- "verifyTerminalAuthCertificateAllowedDocumentElements(_:allowableDocumentElements:)"
```
