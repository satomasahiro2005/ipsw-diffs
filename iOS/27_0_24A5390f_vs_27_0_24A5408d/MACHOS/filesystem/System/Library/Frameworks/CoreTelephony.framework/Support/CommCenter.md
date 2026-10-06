## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b8cdc4` | `0x1ba22c0` | **`+0x154fc`** |
| `__TEXT.__const` | `0x23b124` | `0x23cbe4` | **`+0x1ac0`** |
| `__TEXT.__oslogstring` | `0x18e026` | `0x18fa1e` | **`+0x19f8`** |
| `__TEXT.__gcc_except_tab` | `0x1d8770` | `0x1d9e28` | **`+0x16b8`** |
| `__DATA.__bss` | `0x15160` | `0x15ea0` | **`+0xd40`** |
| `__TEXT.__unwind_info` | `0xae878` | `0xaf180` | **`+0x908`** |
| `__DATA_CONST.__const` | `0x16ce58` | `0x16d368` | **`+0x510`** |
| `__TEXT.__swift5_assocty` | `0x1b88` | `0x1fa0` | **`+0x418`** |
| `__TEXT.__cstring` | `0x84edc` | `0x8528c` | **`+0x3b0`** |
| `__TEXT.__swift5_typeref` | `0x49cc` | `0x4c44` | **`+0x278`** |
| `__DATA.__data` | `0xbed4` | `0xc0dc` | **`+0x208`** |
| `__DATA_CONST.__cfstring` | `0x2a6a0` | `0x2a800` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0x26d8` | `0x27b8` | **`+0xe0`** |
| `__DATA_CONST.__auth_ptr` | `0x1500` | `0x1598` | **`+0x98`** |
| `__TEXT.__swift5_proto` | `0x974` | `0xa04` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x190f4` | `0x19154` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1a0a0` | `0x1a100` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x200e3` | `0x20113` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x1ac8` | `0x1ae8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x154e0` | `0x15500` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x8730` | `0x8748` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5a88` | `0x5aa0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xaa90` | `0xaaa0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x413c` | `0x4148` | **`+0xc`** |
| `__TEXT.__init_offsets` | `0x544` | `0x548` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-13482.1.0.0.0
+13487.3.0.0.0

-  Functions: 133819
-  Symbols:   9254
-  CStrings:  58972
+  Functions: 134211
+  Symbols:   9267
+  CStrings:  59113
Symbols:
+ _$s17BorrowingIterators8IterablePTl
+ _$s7Elements8IterablePTl
+ _$s7Failures25BorrowingIteratorProtocolPTl
+ _$s7Failures8IterablePTl
+ _$sSPyxGs8_PointersMc
+ _$ss25BorrowingIteratorProtocolP4skip2byS2i_t7FailureQzYKFTq
+ _$ss25BorrowingIteratorProtocolP7FailureAB_s5ErrorTn
+ _$ss25BorrowingIteratorProtocolP8nextSpan8maxCounts0E0Vy7ElementQzGSi_t7FailureQzYKFTj
+ _$ss25BorrowingIteratorProtocolP8nextSpan8maxCounts0E0Vy7ElementQzGSi_t7FailureQzYKFTq
+ _$ss25BorrowingIteratorProtocolTL
+ _$ss8IterableMp
+ _$ss8IterableP17BorrowingIteratorAB_s0bC8ProtocolTn
+ _$ss8IterableP19underestimatedCountSivgTq
+ _$ss8IterableP21makeBorrowingIterator0cD0QzyFTq
+ _$ss8IterableP31_customContainsEquatableElementySbSg0E0QzFTq
+ __ZNK16CSIPacketAddress23isPublicRoutableAddressEv
+ __ZNK16CSIPacketAddress28isDefaultGatewayForInterfaceERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
- _$ss17BorrowingSequenceMp
- _$ss25BorrowingIteratorProtocolP4skip2byS2i_tFTq
- _$ss25BorrowingIteratorProtocolP8nextSpan12maximumCounts0E0Vy7ElementQzGSi_tFTj
- _$ss25BorrowingIteratorProtocolP8nextSpan12maximumCounts0E0Vy7ElementQzGSi_tFTq
CStrings:
+ "%s%s%s%sJoined enquiryID(s):%{public}s with existing %@:-> %{public}s"
+ "%s%s%s%sKicking out existing %@ enquiryID(s):%{public}s in favor of %@"
+ "%s%s%s%sKicking out existing %@ enquiryID(s):%{public}s in favor of update %{public}s"
+ "%s%s'%s' is super"
+ "%s%s'%s' lost its super role"
+ "%s%sEnquiryID:%llu, cancelEnquiry removing getSIMStatus consumer"
+ "%s%sEnquiryID:%llu, cancelEnquiry removing setActiveICCID consumer"
+ "%s%sEnquiryID:%llu, unable to setActiveICCID - canceling"
+ "%s%sdecoupling label %s and last owner %s"
+ "%s%shandle getAuthorizationTokens response: Event cause is %s, enquiryID(s):%{public}s"
+ "%s%shandleGetSIMStatusResponse_sync: Event cause is %s, enquiryID(s):%{public}s"
+ "%s%shandleSetActiveICCIDResponse, cannot find callback for EnquiryID:%llu"
+ "%s%shandleSetActiveICCIDResponse: Event cause is %s, enquiryID(s):%{public}s"
+ "%s%sinstall on secondary timed out"
+ "%s%sno localization service, cannot show unlock alert; failing enrollment"
+ "%s%sreceived install_secondary_request, resetting timer, plan state=%s"
+ "%s%sresetting timer for SIM installation"
+ "%s%stimeout in state %s (flowType=%s, planState=%s)"
+ "%s%stimeout in state %s, planState=%s"
+ ", entitlement_status_code="
+ ", oob-provisioned-ts:"
+ ", phase="
+ ", result="
+ "/helper/requests/nal_label"
+ "Activation state changed and device activated with empty cached NAL; re-querying regulatory label"
+ "AllowCarrierSpaceApp"
+ "BCAM %s file handler was not queued"
+ "CLIP absent from CloudKit model - defaulting to enabled (show caller number)"
+ "CLIR absent from CloudKit model - defaulting to Disabled (show number), modifiability unknown"
+ "CW model empty for class=%s - defaulting to enabled (CloudKit not yet seeded by primary)"
+ "Cached NAL: %s"
+ "Canceling in-flight setActiveICCID enquiry (%llu) for (%s)"
+ "Cannot cancel setActiveICCID enquiry (%llu) for (%s): entitlements controller gone"
+ "Cannot cancel setActiveICCID enquiry (%llu) for (%s): entitlements service gone"
+ "Cannot enable back pSIM plan (%s) for transfer - device is in P+E config"
+ "CarrierEntitlements service unavailable — terminating setActiveICCID MM for (%s)"
+ "Checking ePDG address: is a default gateway: %{public}s [%{public}s] [%s]"
+ "Checking ePDG address: is not publicly routable: %{public}s [%{public}s] [%s]"
+ "Checking ePDG address: success: %{public}s [%{public}s] [%s]"
+ "Clearing PNR status for:%s status:%{bool}d"
+ "Config change in progress"
+ "Could not find EACellBroadcastMessageListener class in EmergencyAlerts for preferred language change"
+ "Current sim slot config:%s"
+ "DATA::          fMsgCounters is empty"
+ "DATA::          fMsgCounters.msgID = %llu counter = %llu"
+ "DATA::      fSlot: %s"
+ "Development Signed Carrier Bundles: Not Allowed"
+ "Device not activated yet; deferring NAL query to activation-state notification"
+ "Did not find cached decoder for alertHash: %{public}s"
+ "Display unlocked with first unlock false, polling for state"
+ "Dropping stale setActiveICCID timestamp for (%s): no longer enrolled"
+ "Dynamic sim config not available"
+ "EACellBroadcastMessageListener does not support preferred language change"
+ "Empty preferred languages when forwarding to EmergencyAlerts"
+ "Enable euicc assertion denied"
+ "Enrollment"
+ "Failed to create setActiveICCID monitor mode for (%s)"
+ "Failed to serialize decoder for alert hash %{public}s, cannot cache"
+ "Failed to synchronize QuickSwitch preferences after saving OOB provisioned ts"
+ "Fetching render information for: %{private, mask.hash}s, wid: %{mask.hash}s, ctx: %{mask.hash}s"
+ "First unlock post-powercycle in Active mode — forcing setActiveICCID for (%s)"
+ "First unlock remains false"
+ "First unlock remains true"
+ "Forwarding preferred language change %{public}@ to EmergencyAlerts"
+ "Get EID is in progress"
+ "Get setActiveICCID response for (%s): success=(%{bool}d) status=(%s)"
+ "Got %zu alerts"
+ "IDS timestamp unavailable (error=%d) — using wall-clock %llu for successful setActiveICCID(%s)"
+ "Invalid Bundle Setting type for %s. Not a valid Otherknown bundle."
+ "JOURNALING_SERVICES"
+ "Lining up %zu BCAM config file(s)"
+ "Loaded OOB provisioned ts: %{public}s"
+ "Local Device Info NAL Wait"
+ "Local setActiveICCID claim displaced: remote (%s @ %llu) > local (%s @ %llu) — reissuing setActiveICCID(%s)"
+ "Matched alertHash %{public}s against active alert"
+ "Missing MKBDeviceUnlockedSinceBoot symbol"
+ "NALLabelId"
+ "No Active sim slot config"
+ "No BCAM config files were queued for push"
+ "No BCAM files were queued for push"
+ "No entitlements controller for (%s) — terminating setActiveICCID MM"
+ "Not caching non-geofenced alert %{public}s"
+ "Not polling for first unlock state with display locked"
+ "OOB QS provisioned ts mismatch (cached=%{public}s), forcing GSS"
+ "OOB QS provisioned ts received (unparseable): %{public}s"
+ "OOB QS provisioned ts received, epoch(s): %llu"
+ "OobProvisionedTs"
+ "Otherknown bundle failed verification. Not applying."
+ "Otherknown bundle, not validating the SIMs"
+ "PhoneNumberRegistrationControllerInterface not found; skipped clearing PNR status"
+ "Preferred language changed from %{public}s to %{public}s"
+ "Publishing (from cache) chatbot render information: [expired: %{bool}d, information available: %{bool}d]"
+ "QuickSwitchSuppServicesManager:: LP model empty - CLIP not included in CloudKit upload (not yet fetched from network)"
+ "QuickSwitchSuppServicesManager:: LR model empty - CLIR not included in CloudKit upload (not yet fetched from network)"
+ "QuickSwitchSuppServicesManager:: Secondary joined/changed, triggering CloudKit upload to seed secondary cache"
+ "QuickSwitchSuppServicesManager:: Transitioning to Primary active, triggering initial CloudKit upload for secondary"
+ "QuickSwitchSuppServicesManager:: Transitioning to Primary passive, triggering initial CloudKit upload for secondary"
+ "Received activation state changed notification"
+ "Recording IDS-server timestamp %llu for successful setActiveICCID(%s)"
+ "Restoring validity for: %s, wid = %s, wctx = %s, created_at = %ld"
+ "SIM_CONTINUITY_NOT_SUPPORTED_MESSAGE_%@_%@"
+ "SIM_CONTINUITY_NOT_SUPPORTED_TITLE"
+ "Secondary CF cache serve: no raw param for reason=%d, class=%s - skipping"
+ "Secondary CF cache serve: reason=%d, class=%s, enabled=%{bool}d, number=%{private}s"
+ "Sending reply for request (cid=%lu, rid=%lu): retrieveMessage: identifier=%@, from=%@, secure=%{BOOL}d content=%{sensitive}@, error=%@"
+ "Sending setActiveICCID request for (%s) via monitor mode"
+ "Service %s fetch complete - no QuickSwitch manager registered, skipping CloudKit upload"
+ "Service %s fetch complete - notifying QuickSwitch manager for CloudKit upload"
+ "Skipping displaced-active reissue for (%s): setActiveICCID monitor mode already running"
+ "Skipping setActiveICCID for (%s): not supported by carrier bundle"
+ "Starting render information cache read for %s, handle: %s"
+ "Starting render information search for %s, handle: %s,  opID: %s"
+ "Starting setActiveICCID monitor mode for (%s)"
+ "Successfully queued BCAM %s file handler"
+ "Terminating existing setActiveICCID monitor mode for (%s): %s"
+ "Terminating setActiveICCID monitor mode for (%s): no longer enrolled"
+ "UPDATE chatbot_render_information SET validity = ?, created_at = ? WHERE uri = ?"
+ "Unable to get CFPreferencesInterface, cannot load OOB provisioned ts"
+ "Unable to get CFPreferencesInterface, cannot save OOB provisioned ts"
+ "Unknown fLinkType[%s]: %s (contextType)"
+ "Unknown fLinkType[%s]: %s (transportType)"
+ "Updated CW model: enabled=%d, class=%s (UI only, no baseband I/O)"
+ "ValidateEPDGAddress"
+ "VoWiFi provisioning state changing from null to %{bool}d"
+ "WEA maps not enabled for slot (%s); not returning cached metadata for alertHash: %{public}s"
+ "WEA maps not enabled for slot (%s); not returning metadata for alertHash: %{public}s"
+ "WaitForPhoneNumberDuringActivation"
+ "We do not have supporting traffic descriptors for LLPHS !"
+ "Will use welcome info: identifier=%s, context=%s"
+ "[fetch-chatbot-render-information] start destination: %{private}s, operationID: %{private}s, wid: %s, ctx: %s"
+ "_handoffCurrentReplyToQueue:block:"
+ "before starting a fresh one"
+ "com.apple.MomentsUIService"
+ "com.apple.datausage.journaling"
+ "commCenterCellularPlanPairedRioWatchSummary"
+ "commCenterHardwareSimConfig"
+ "defer install indication for %s: monitor mode not settled yet"
+ "defer install indication for %s: phone number not ready yet"
+ "destroying local label '%s' owned by %s"
+ "epdgIp"
+ "fIsConfigChangeInProgress : %{bool}d"
+ "fProfileChangeInProgress: %{bool}d, fBlockedByProfileUpdate: %{bool}d, fFetchProfilesInProgress: %{bool}d, fGetEidInProgress: %{bool}d, fDeactivationAssertion: %{bool}d, fInstallReplaceOperationAssertion: %{bool}d, fEidVerifed = %{bool}d"
+ "fProfileChangeInProgress: %{bool}d, fBlockedByProfileUpdate: %{bool}d, fFetchProfilesInProgress: %{bool}d, fGetEidInProgress: %{bool}d, fDeactivationAssertion: %{bool}d, fInstallReplaceOperationAssertion: %{bool}d, fEidVerifed = unknown"
+ "failed to format %s message for app: %s"
+ "failed to get %s strings for app: %s"
+ "forward install indication (state=%s) %s"
+ "getLocalDeviceInfo EID:%{private}s IMEI:%{private}s IMEI1:%{private}s IMEI2:%{private}s NAL:%{private}s"
+ "getLocalDeviceInfo: GreenTea device not yet activated but a NAL wait is already in flight; returning current info without holding"
+ "getLocalDeviceInfo: GreenTea device not yet activated; caching callback until NAL is available (max %llds)"
+ "getLocalDeviceInfo: NAL wait timer expired; releasing %zu cached callback(s) with current NAL"
+ "getLocalDeviceInfo: releasing %zu cached callback(s)"
+ "hardwareConfig"
+ "inProgress"
+ "install indication safety timer fired for %s (MM/PNR not settled); sending timeout"
+ "isOnBoardQuickSwitch"
+ "lastSuccessfulActiveIccidTimestamps"
+ "metricCCBadIMSePDGAddress"
+ "mismatch"
+ "missing localization, denying for app: %s"
+ "monitor mode update: source=%s target=%s success=%{bool}d"
+ "no d2d comm; cannot send install_secondary_indication for %s"
+ "not-supported"
+ "not_supported"
+ "oob-provisioned-ts"
+ "oobProvisionedTs"
+ "oobProvisionedTs:'"
+ "operation=enrollment, carrier="
+ "operation=new-device, carrier="
+ "operation=old-primary-sliding, carrier="
+ "pairedRioCount"
+ "passcode state changed, isPasscodeSet:%{bool}d"
+ "preferredLanguageChanged:"
+ "qs ineligible"
+ "qs.install.indication.safety"
+ "qs.install.sim"
+ "qs.mm.saic"
+ "rioActivePlanAssociatedWithQsCount"
+ "rioPlanAssociatedWithQsCount"
+ "routing websheet callback to sliding op. (src=%s target=%s)"
+ "setActiveICCID monitor mode completed for (%s): success=(%s)"
+ "startIPSecConnection: NEIPSecIKESession startConnection failed, trying next address..."
+ "startIPSecConnection: ePDG Address is: %s but the IP address is not acceptable"
+ "startIPSecConnection: ePDG Address is: empty"
+ "startIPSecConnection: ePDG Address is: good: %{public}s"
+ "supplementSimInfos"
+ "support was lost"
+ "unset"
+ "updateCallForwardingModelOnly: reason=%d, class=%s, enabled=%{bool}d, number=%{private}s, timer=%d"
- "%s%s%s go dangling, last owner %s"
- "%s%s%s%sJoined enquiryID(s):%s with existing %@:-> %s"
- "%s%s%s%sKicking out existing %@ enquiryID(s):%s in favor of %@"
- "%s%s%s%sKicking out existing %@ enquiryID(s):%s in favor of update %s"
- "%s%sEnquiryID:%llu, cancelEnquiry removing consumer"
- "%s%sNumber of consumers in setActiveICCID callback list: %ld"
- "%s%sUnable to setActiveICCID"
- "%s%shandle getAuthorizationTokens response: Event cause is %s, enquiryID(s):%s"
- "%s%shandleGetSIMStatusResponse_sync: Event cause is %s, enquiryID(s):%s"
- "%s%shandleSetActiveICCIDResponse: Event cause is %s"
- "%s%slabel %s stopped being super"
- "%s%sno localization service, proceeding directly"
- "%s%sreceived install_secondary_request, resetting timer"
- "%s%stimeout in state %s"
- "%s%stimeout in state %s (flowType=%s)"
- "AAAAAA000000000000000"
- "AllowCarrierAppElevation"
- "Development Signed Carrier Bundles: Allowed"
- "Enable euicc assertion not granted"
- "Fetching render information for: %{private, mask.hash}s"
- "Get setActiveICCID response with: (%{bool}d)"
- "No Saved sim slot config"
- "Publishing (from cache) chatbot render information: [expired: %{bool}d, information available: %s]"
- "QuickSwitchSuppServicesManager:: Transitioning to Primary, ready for uploads"
- "Restoring validity for: %s, wid = %s, wctx = %s"
- "Saved sim slot config:%s"
- "Secondary CF cache serve: no raw param for reason=%d, class=0x%x - skipping"
- "Secondary CF cache serve: reason=%d, class=0x%x, enabled=%{bool}d, number=%{private}s"
- "Sending reply for request (cid=%lu, rid=%lu): retrieveMessage: result=%@, error=%@"
- "Sending setActiveICCID request for (%s)"
- "Service priority: %s, did change since last update: %{bool}d"
- "Starting render information cache read for %s"
- "Starting render information search for %s for %s"
- "Successfully initialized BCAM %s file handler"
- "UPDATE chatbot_render_information SET validity = ? WHERE uri = ?"
- "Updated CW model: enabled=%d, class=0x%x (UI only, no baseband I/O)"
- "Vsim enabled, dynamic sim config not supported"
- "WEA maps not enabled for slot; not returning cached metadata for alertHash: %{public}s"
- "WEA maps not enabled for slot; not returning metadata for alertHash: %{public}s"
- "cannot find primary device info"
- "fProfileChangeInProgress: %{bool}d, fBlockedByProfileUpdate: %{bool}d, fFetchProfilesInProgress: %{bool}d, fDeactivationAssertion: %{bool}d, fInstallReplaceOperationAssertion: %{bool}d, fEidVerifed = %{bool}d"
- "fProfileChangeInProgress: %{bool}d, fBlockedByProfileUpdate: %{bool}d, fFetchProfilesInProgress: %{bool}d, fDeactivationAssertion: %{bool}d, fInstallReplaceOperationAssertion: %{bool}d, fEidVerifed = unknown"
- "failed to format mismatch message for app: %s"
- "failed to get mismatch strings for app: %s"
- "forward install indication %s"
- "sliding transfer monitor mode completed: source=%s target=%s success=%{bool}d"
- "updateCallForwardingModelOnly: reason=%d, class=0x%x, enabled=%{bool}d, number=%{private}s, timer=%d"
```
