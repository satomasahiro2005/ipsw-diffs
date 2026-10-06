## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xac9158` | `0xad13d4` | **`+0x827c`** |
| `__TEXT.__oslogstring` | `0x8906d` | `0x8a081` | **`+0x1014`** |
| `__DATA_CONST.__cfstring` | `0x366e0` | `0x37460` | **`+0xd80`** |
| `__TEXT.__cstring` | `0x59e2e` | `0x5aa0e` | **`+0xbe0`** |
| `__TEXT.__objc_methname` | `0x7be45` | `0x7c7b5` | **`+0x970`** |
| `__DATA_CONST.__objc_intobj` | `0x1ad0` | `0x2358` | **`+0x888`** |
| `__TEXT.__ustring` | `0x5ac` | `0xca0` | **`+0x6f4`** |
| `__TEXT.__objc_stubs` | `0x4a380` | `0x4a900` | **`+0x580`** |
| `__TEXT.__gcc_except_tab` | `0x243f8` | `0x2494c` | **`+0x554`** |
| `__DATA.__objc_const` | `0x525f8` | `0x52968` | **`+0x370`** |
| `__DATA_CONST.__objc_arraydata` | `0x5c8` | `0x888` | **`+0x2c0`** |
| `__TEXT.__objc_methlist` | `0x2c53c` | `0x2c7c4` | **`+0x288`** |
| `__DATA.__objc_selrefs` | `0x16e88` | `0x17078` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x17110` | `0x17228` | **`+0x118`** |
| `__DATA_CONST.__const` | `0x30f00` | `0x30ff0` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x9175` | `0x91f9` | **`+0x84`** |
| `__TEXT.__objc_methtype` | `0x143f9` | `0x14469` | **`+0x70`** |
| `__DATA.__objc_data` | `0xf810` | `0xf878` | **`+0x68`** |
| `__DATA.__data` | `0x16820` | `0x16870` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x3510` | `0x3550` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x4618` | `0x4658` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x7770` | `0x77b0` | **`+0x40`** |
| `__DATA_CONST.__objc_dictobj` | `0xa0` | `0xc8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x9a58` | `0x9a7c` | **`+0x24`** |
| `__DATA.__bss` | `0x24ea0` | `0x24ec0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3bc8` | `0x3be8` | **`+0x20`** |
| `__DATA.__common` | `0xdf0` | `0xdd8` | **`-0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x348` | `0x360` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x7fcc` | `0x7fe4` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x8980` | `0x8997` | **`+0x17`** |
| `__DATA_CONST.__objc_catlist` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x14c0` | `0x14c8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xbf8` | `0xc00` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xa1f6` | `0xa1f2` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__dlopen_cstrs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2000.100.2.2.1
+2003.100.1.0.0

-  Functions: 32383
-  Symbols:   2951
-  CStrings:  33048
+  Functions: 32460
+  Symbols:   2962
+  CStrings:  33252
Symbols:
+ _IDSMessageContextLocalTraceIdentifierKey
+ _IDSMessageTraceIDKey
+ _IDSRegistrationPropertySupportsDedicatedChannelBaseFilterOverrideOpportunistic
+ _IDSSilenceIfUnknownKey
+ _OBJC_CLASS_$_IDSDeregistrationDailyMetric
+ _OBJC_CLASS_$_IDSSOSLogger
+ _OBJC_CLASS_$_IDSSOSMetric
+ _nw_agent_client_copy_parameters
+ _nw_agent_set_assert_handlers
+ _nw_connection_log_send_state
+ _nw_parameters_set_account_id
CStrings:
+ " => Auto adding vetted emails: %@ to URI set {idsUserID: %@, serviceType: %@}"
+ "%@.spam.txt"
+ "%s: %{bool}d"
+ "%s: Local delivery complete for materialID=%s, gc=%u"
+ "-[IDSDAccount(Registration) _unregisterAccount:]"
+ "09:44:29"
+ "<eja-redacted>"
+ "@\"IDSEnhancedJunkAnalysisController\""
+ "@\"IDSSOSLogger\""
+ "Accept"
+ "Accept (no ship)"
+ "Adding sentinel alias for repair {immediate: %d, uniqueIdentifier: %@, account: %@}"
+ "Adding vetted alias to aliases dictionary: %@ {service: %@, uniqueID: %@, addToCurrentHandlesIfNeeded: %{BOOL}d, forceAdd: %{BOOL}d, status: %ld}"
+ "Apple detected a message from a sender who may be trying to harm your iPhone or compromise your privacy. The most important step you can take to protect yourself and others from similar attacks is to share the message with Apple.\n\nSender: %@"
+ "Are you sure you don't want to share the message with Apple?"
+ "Aug  4 2026"
+ "Cached decision %@ for sender %@"
+ "Captured pending guid %@ (sender=%@, topic=%@, hasPlaintext=%@)"
+ "Deferring sentinel repair until account is authenticated {status: %d, account: %@}"
+ "Don't Report"
+ "Drain complete: %lu guid(s) for sender %@ (decision=%@)"
+ "Drain: cleared %lu pending guid(s) for %@ with decision=%@"
+ "Drain: eja keys       = %@"
+ "Drain: no account for service=%@ toURI=%@ — skipping ship for guid %@"
+ "Drain: nothing pending for sender %@ (decision=%@)"
+ "Drain: remapping adhoc topic %@ -> primary %@ for account lookup"
+ "Drain: shipping %lu top-level key(s) + %lu eja key(s)"
+ "Drain: shipping guid %@ sender=%@ topic=%@ toURI=%@"
+ "Drain: shipping guid %@ sender=%@ topic=%@ toURI=%@ — debug dump at %@"
+ "Drain: top-level keys = %@"
+ "Drain: wireSpam = %@"
+ "Drain: wireSpam.eja = %@"
+ "E7AAB728-60CE-7881-D569-9FF8825F15EA"
+ "EJA"
+ "EJA confirmation alert body"
+ "EJA confirmation alert title"
+ "EJA confirmation-alert destructive button — final dismissal"
+ "EJA first alert body, %@ is the sender URI"
+ "EJA first alert title"
+ "EJA first-alert alternate button — defers the decision"
+ "EJA primary button — shares the message with Apple"
+ "EJADumpSpamToDisk"
+ "EJATestSenders"
+ "Evicting stale sender state for %@ (older than %.0fh)"
+ "Failed to create session because failed to create unauthenticated public identity even though key was present"
+ "Feature disabled by server bag (%@=%@)"
+ "Finished acks for GUID %@ TRACE_ID %@ success: %@ error: %@"
+ "Full response info for GUID %@ TRACE_ID %@ Finished Fanout %@ with result code: %ld error: %@ result dictionary: %@ message body: %@"
+ "Full response info for GUID %@ TRACE_ID %@ Finished MML %@ with result code: %ld error: %@ result dictionary: %@ message body: %@"
+ "GUID %@ TRACE_ID %@ APNS ack received for destination %@"
+ "GUID %@ TRACE_ID %@ Finished Fanout %@ with result code: %ld error: %@"
+ "GUID %@ TRACE_ID %@ Finished MML %@ with result code: %ld error: %@"
+ "GUID %@ TRACE_ID %@ Finished sending to destination %@ { success: %@, code: %ld, error: %@ }"
+ "GUID %@ TRACE_ID %@ Received APNS ack for Fanout %@"
+ "GUID %@ TRACE_ID %@ Received APNS ack for MML %@"
+ "GUID %{private}s Tokens for URI:\n%{private}s"
+ "GUID %{private}s finished token filtering"
+ "IDS-EJA-KillSwitch"
+ "IDSEnhancedJunkAnalysisController"
+ "IDSEnhancedJunkAnalysisLocalizable"
+ "IDSGroupEncryptionController2.publicIdentity: Dropping expired public identity for pushToken: %@"
+ "IDSGroupEncryptionControllerGroupSession[session=%s].desiredMaterials: Cannot generate desired material for %@: lightweight participant does not map to a valid member"
+ "IDSGroupEncryptionControllerGroupSession[session=%s].desiredMaterials: Cannot generate desired material for %@: standard participant does not map to a valid member"
+ "IDSGroupEncryptionControllerGroupSession[session=%s].setRatchetEnabled: %{bool}d forKind: %s"
+ "IDSGroupEncryptionControllerGroup[group=%s].receiveLocalMKM: SUCCESS - material %s for participant %s delivered to session, gc=%u"
+ "IDSGroupEncryptionControllerGroup[group=%s].setRatchetEnabled: setRatchetEnabled: no session for %s"
+ "IDSGroupEncryptionControllerGroup[group=%s].setRatchetEnabled: setRatchetEnabled: unsupported material type %d for session %s"
+ "IMUserNotification creation failed for title=%@"
+ "IMUserNotification response %ld -> result %ld"
+ "INCOMING-APS_DELIVERY:%@ SERVICE:%@ TRACE_ID:%@"
+ "Ignoring duplicate response for already-processed requestID %@, QR sessionID %@."
+ "Init: seeded deviceLocked=%@ (state is RAM-only, lost on daemon restart)"
+ "Malicious Message Detected"
+ "Not re-selecting user-disabled alias on vetted refresh {alias: %@, service: %@, uniqueID: %@, reason: %ld}"
+ "Not updating vetted aliases, no change to process. Current: %@   ID: %@   service: %@   addToCurrentHandlesIfNeeded: %{BOOL}d"
+ "OUTGOING-LOCAL_SEND:%@ SERVICE:%@ TRACE_ID:%@"
+ "OUTGOING-PUSH_FULLY_SENT:%@ SERVICE:%@ TRACE_ID:%@"
+ "OUTGOING-REMOTE_SEND:%@ SERVICE:%@ TRACE_ID:%@"
+ "Posted SOS eja_alert=YES, eja_alert_count=%lu"
+ "Prompt (confirm): dismissed for %@ — leaving pending; next event will retry"
+ "Prompt (first): dismissed for %@ — leaving pending; next event will retry"
+ "Prompt chain re-armed: %lu fresh sender(s) queued during walk"
+ "Prompt kick skipped — device is locked"
+ "Prompt kick: %lu sender(s) need a decision"
+ "Prompt: already in flight for %@ — skipping"
+ "Q20@0:8B16"
+ "Received APNS Ack for GUID %@ TRACE_ID %@"
+ "Received remote message %@ is a duplicate. Ignoring. TRACE_ID:%@"
+ "Report"
+ "Report (ship attempted per record above)"
+ "SOS post succeeded — cleared %lu accumulated alert(s)"
+ "Share with Apple"
+ "Sharing the message will help Apple investigate the attack and protect against future ones."
+ "Skipped capture: at concurrent-sender cap (%lu); dropping guid %@ from sender %@"
+ "Skipped capture: guid %@ already pending for sender %@"
+ "T@\"IDSEnhancedJunkAnalysisController\",R,N,V_enhancedJunkAnalysisController"
+ "T@\"IDSPersistentMap\",&,N,V_deregistrationReasonMap"
+ "T@\"IDSPersistentMap\",&,N,V_deregistrationTimestampMap"
+ "T@\"NSMutableDictionary\",&,N,V_senderState"
+ "T@\"NSMutableDictionary\",&,N,V_serviceNameToAssertionCount"
+ "T@\"NSMutableSet\",&,N,V_inFlightPromptSenders"
+ "TB,N,V_deviceLocked"
+ "TB,N,V_promptChainInFlight"
+ "TB,N,VrequiresSentinelAliasImmediately"
+ "TQ,N,V_unreportedAlertCount"
+ "Unknown(pending)"
+ "Updating vetted aliases to: %@     current: %@   ID: %@   service: %@   addToCurrentHandlesIfNeeded: %{BOOL}d"
+ "Urgent"
+ "[%{private}s] Caller-supplied sendMessagePolicy is set; ignoring legacy registrationProperties on the daemon side."
+ "[%{private}s] Invoking willSend: %{public}ld destinations, %{public}ld skipped, %{public}ld reg-prop entries, policyResult=%{public}s"
+ "[%{private}s] Synthesized capability policy from registrationProperties on the daemon side (requireAll=%{public}ld, lackAll=%{public}ld, interesting=%{public}ld)"
+ "[%{private}s] willSend payload: destinations=%{private}s skipped=%{private}s regProp=%{private}s"
+ "_EJA_forgeSiuIfTestSenderForNiceMessage:topic:"
+ "_EJA_noteIncomingNiceMessage:topLevelPayload:fromURI:service:"
+ "_addPendingForSender:niceMessage:plaintext:"
+ "_cachedDecisionForSender:"
+ "_cleanupLocalAccountsWithReason:"
+ "_currentAccountsSnapshot"
+ "_deregistrationReasonMap"
+ "_deregistrationTimestampMap"
+ "_deviceLocked"
+ "_disableAccountWithUniqueID:reason:"
+ "_drainSender:withDecision:"
+ "_enhancedJunkAnalysisController"
+ "_ensureSenderStateLocked_unsafe:"
+ "_evictExpiredEntriesLocked_unsafe"
+ "_hasAnyPendingLocked_unsafe"
+ "_inFlightPromptSenders"
+ "_keyTransparencyContextsForURIs:service:fromURI:"
+ "_kickPromptQueueIfNeeded"
+ "_postAlertShownTelemetry"
+ "_promptChainDone"
+ "_promptChainInFlight"
+ "_promptNextWithRemaining:"
+ "_recordDecision:forSender:"
+ "_releasePromptForSender:"
+ "_removeAccount:reason:"
+ "_removePrimaryAccount:reason:"
+ "_senderState"
+ "_sendersNeedingPromptLocked_unsafe"
+ "_serviceNameToAssertionCount"
+ "_shipSpamForRecord:sender:"
+ "_sosLogger"
+ "_stateLock"
+ "_submitDeregistrationMetricWithRegistration:reason:"
+ "_traceID"
+ "_tryAcquirePromptForSender:"
+ "_unregisterAccount:"
+ "_unreportedAlertCount"
+ "_updateKTContext:forURI:"
+ "addBlockToAggregatableMessage:forURIs:trackingSet:guid:traceID:"
+ "applyTransparencyToEndpoints:"
+ "arrayForKey:"
+ "browse_handler: Asserting client: %@ with clientUUID: %@ and pid: %d"
+ "browse_handler: Assertion count: %d for service name: %@"
+ "browse_handler: Assertion removed for client: %@ with clientUUID: %@ and pid: %d"
+ "browse_handler: assert handler: NULL account_id for client %@ with pid: %d, skipping"
+ "browse_handler: assert removed handler: NULL account_id for client %@ with pid: %d, skipping"
+ "browse_handler: client %@ NULL application service name, skipping"
+ "browse_handler: stop_browse_handler: NULL application service name for client %@, skipping"
+ "com.apple.identityservices.deregistrationReasons"
+ "com.apple.identityservices.deregistrationTimestamps"
+ "conversation-group-size"
+ "conversation-id"
+ "deactivateRegistration:"
+ "decision"
+ "deregistrationReasonMap"
+ "deregistrationTimestampMap"
+ "deviceDidLock"
+ "deviceDidLock — popups suppressed while locked"
+ "deviceDidUnlock"
+ "deviceDidUnlock — hasPending=%@"
+ "deviceLocked"
+ "eja"
+ "eja-spam"
+ "ejaTestSenders"
+ "eja_alert"
+ "eja_alert_count"
+ "enhancedJunkAnalysisController"
+ "firstSeenAt"
+ "forceRemoveAccount:reason:"
+ "forged siu=EnhancedJunkAnalysis for %@ at entry (matched EJATestSenders)"
+ "getThrottlingThresholdForUTunTTR:"
+ "inFlightPromptSenders"
+ "initWithService:reason:durationMinutes:"
+ "initWithServiceController:accountController:notificationsCenter:serverBag:sosLogger:initiallyLocked:"
+ "initWithVerifierResult:ticket:accountKey:queryResponseTime:verificationDate:ktOptIn:ktOptions:"
+ "is-informal"
+ "is-payment"
+ "is-self"
+ "isAllowedCommand:"
+ "isFeatureGloballyDisabled"
+ "isFeatureGloballyDisabledForServerBag:"
+ "kill switch engaged (server bag %@) — bypassing siu flow for inbound from %@"
+ "localTraceIdentifier"
+ "logMetric:completion:"
+ "message-attachment-info"
+ "message-format-version"
+ "message-has-image"
+ "message-length"
+ "message-service"
+ "message-spam-model-detected-spam"
+ "message-text"
+ "message-type"
+ "metricWithDomain:type:error:bagURL:extras:"
+ "niceMessage"
+ "noteIncomingNiceMessage:sender:plaintext:"
+ "originalUUID"
+ "plaintext"
+ "postAlertWithTitle:body:defaultButton:alternateButton:completion:"
+ "pre-BD decision=%@ for %@"
+ "promptChainInFlight"
+ "q40@0:8@16@24@32"
+ "recipient"
+ "recipient-uri"
+ "reportDailyDeregistrationMetric"
+ "reported-from-blackhole"
+ "reported-from-junk"
+ "requiresSentinelAliasImmediately"
+ "sender-records-and-keys"
+ "sender-shared-name-and-photo"
+ "senderState"
+ "serviceNameToAssertionCount"
+ "setDeregistrationReasonMap:"
+ "setDeregistrationTimestampMap:"
+ "setDeviceLocked:"
+ "setInFlightPromptSenders:"
+ "setPromptChainInFlight:"
+ "setRatchetEnabled:forMaterialType:inSession:"
+ "setRequiresSentinelAliasImmediately:"
+ "setSenderState:"
+ "setServiceNameToAssertionCount:"
+ "setTraceID:"
+ "setUnreportedAlertCount:"
+ "shouldThrottleUTunTTRAfterDiceRoll:"
+ "shouldThrottleUTunTTRAfterDiceRoll: currentServerBagPercentage (%lu), diceRoll (%u) isUrgent (%@)"
+ "skipping EJA for %@ — message is from self"
+ "skipping EJA for %@ — service %@ blocks cross-account"
+ "skipping EJA — command %@ not in allowlist"
+ "submitDeregistrationMetricForAllActiveRegistrationsWithReason:"
+ "time-sensitive"
+ "time-sensitive-evaluated"
+ "traceID"
+ "unregisterInfo:reason:"
+ "unreportedAlertCount"
+ "v24@?0@\"NSObject<OS_nw_agent_client>\"8@?<v@?ii@\"NSObject<OS_dispatch_data>\">16"
+ "v32@0:8B16i20@24"
+ "verificationDate"
- " => Auto adding vetted emails: %@ to URI set"
- "%s: Local delivery complete for materialID=%s"
- "-[IDSDAccount(Registration) _unregisterAccount]"
- "22:11:10"
- "Adding sentinel alias to existing account for repair {uniqueIdentifier: %@, account: %@}"
- "Adding vetted alias to aliases dictionary: %@"
- "Finished acks for GUID %@ success: %@ error: %@"
- "Full response info for GUID %@ Finished Fanout %@ with result code: %ld error: %@ result dictionary: %@ message body: %@"
- "Full response info for GUID %@ Finished MML %@ with result code: %ld error: %@ result dictionary: %@ message body: %@"
- "GUID %@ APNS ack received for destination %@"
- "GUID %@ Finished Fanout %@ with result code: %ld error: %@"
- "GUID %@ Finished MML %@ with result code: %ld error: %@"
- "GUID %@ Finished sending to destination %@ { success: %@, code: %ld, error: %@ }"
- "GUID %@ Received APNS ack for Fanout %@"
- "GUID %@ Received APNS ack for MML %@"
- "GUID %{public}s Tokens for URI:\n%{public}s"
- "GUID %{public}s finished token filtering"
- "IDSGroupEncryptionControllerGroup[group=%s].receiveLocalMKM: SUCCESS - material %s for participant %s delivered to session"
- "INCOMING-APS_DELIVERY:%@ SERVICE:%@"
- "Jul 14 2026"
- "Not re-selecting user-disabled alias on vetted refresh {alias: %@, reason: %ld}"
- "OUTGOING-LOCAL_SEND:%@ SERVICE:%@"
- "OUTGOING-PUSH_FULLY_SENT:%@ SERVICE:%@"
- "OUTGOING-REMOTE_SEND:%@ SERVICE:%@"
- "Received APNS Ack for GUID %@"
- "Received remote message %@ is a duplicate. Ignoring."
- "Updating vetted aliases to: %@     current: %@   ID: %@"
- "[%{public}s] Caller-supplied sendMessagePolicy is set; ignoring legacy registrationProperties on the daemon side."
- "[%{public}s] Invoking willSend: %{public}ld destinations, %{public}ld skipped, %{public}ld reg-prop entries, policyResult=%{public}s"
- "[%{public}s] Synthesized capability policy from registrationProperties on the daemon side (requireAll=%{public}ld, lackAll=%{public}ld, interesting=%{public}ld)"
- "[%{public}s] willSend payload: destinations=%{public}s skipped=%{public}s regProp=%{public}s"
- "_cleanupLocalAccounts"
- "_disableAccountWithUniqueID:"
- "_keyTransparencyVerifierResultForService:fromURI:toURI:"
- "_removePrimaryAccount:"
- "_unregisterAccount"
- "_updateKTContext:forURI:manager:"
- "addBlockToAggregatableMessage:forURIs:trackingSet:guid:"
- "deactivateRegistration"
- "getThrottlingThresholdForUTunTTR"
- "shouldThrottleUTunTTRAfterDiceRoll"
- "shouldThrottleUTunTTRAfterDiceRoll: currentServerBagPercentage (%lu), diceRoll (%u)"
- "unregisterInfo:"
- "updateKeyTransparencyForEndpoints:withKTContext:"
```
