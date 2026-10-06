## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bb776c` | `0x1bc3b64` | **`+0xc3f8`** |
| `__TEXT.__const` | `0x23e0b4` | `0x23fd24` | **`+0x1c70`** |
| `__TEXT.__objc_methtype` | `0x590f3` | `0x5a333` | **`+0x1240`** |
| `__TEXT.__gcc_except_tab` | `0x1db998` | `0x1dc6fc` | **`+0xd64`** |
| `__DATA_CONST.__const` | `0x16dd70` | `0x16ea30` | **`+0xcc0`** |
| `__TEXT.__oslogstring` | `0x190e3a` | `0x19183e` | **`+0xa04`** |
| `__TEXT.__unwind_info` | `0xb0768` | `0xb0d88` | **`+0x620`** |
| `__TEXT.__cstring` | `0x853dc` | `0x856ec` | **`+0x310`** |
| `__DATA.__objc_const` | `0x13538` | `0x135f0` | **`+0xb8`** |
| `__TEXT.__eh_frame` | `0x1915c` | `0x191b4` | **`+0x58`** |
| `__DATA.__objc_data` | `0x4578` | `0x45c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xc58c` | `0xc5c4` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x15590` | `0x155c0` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x2a8e0` | `0x2a900` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xaae8` | `0xab00` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5aa8` | `0x5ab8` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x31ee` | `0x31fe` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x700` | `0x708` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x60c` | `0x614` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x884` | `0x888` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x270` | `0x26c` | **`-0x4`** |
| `__TEXT.__swift5_typeref` | `0x4c44` | `0x4c42` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-13494.0.0.0.0
+13496.3.0.0.0

-  Functions: 135163
-  Symbols:   9279
-  CStrings:  59234
+  Functions: 135481
+  Symbols:   9284
+  CStrings:  59290
Symbols:
+ _$s15SecureMessaging15KDSRegistrationO12EncryptedRCSO25PhoneAuthenticationResultO19needsReprovisioningyA2GmFWC
+ _$s15SecureMessaging15KDSRegistrationO33RefreshCredentialProcessedContextVMa
+ _$s15SecureMessaging15KDSRegistrationO6ClientC17refreshCredentialAC07RefreshF16ProcessedContextVyYaKFTjTu
+ __ZNSt3__14stolERKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEPmi
+ _os_eligibility_get_domain_answer
CStrings:
+ "\" value=\""
+ "%{public}s for %{public}s"
+ "/cc/events/lazuli_push_credentials_watchdog_interval_override"
+ "<?xml version=\"1.0\"?>\n<wap-provisioningdoc version=\"1.1\">\n\t<characteristic type=\"VERS\">\n\t\t<parm name=\"version\" value=\"-3\"/>\n\t\t<parm name=\"validity\" value=\"86400\"/>\n\t</characteristic>\n</wap-provisioningdoc>"
+ "@48@0:8{LazuliPhoneAuthResult={variant<LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>={__impl<LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=(__union<std::__variant_detail::_Trait::_Available, 0UL, LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=c{__alt<0UL, LazuliPhoneAuthResult::Proof>={Proof={basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}}}(__union<std::__variant_detail::_Trait::_Available, 1UL, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=c{__alt<1UL, LazuliPhoneAuthResult::Throttle>={Throttle=q}}(__union<std::__variant_detail::_Trait::_Available, 2UL, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=c{__alt<2UL, LazuliPhoneAuthResult::NeedsReprovision>={NeedsReprovision=}}(__union<std::__variant_detail::_Trait::_Available, 3UL, LazuliPhoneAuthResult::Failure>=c{__alt<3UL, LazuliPhoneAuthResult::Failure>={Failure={basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}}}(__union<std::__variant_detail::_Trait::_Available, 4UL>=)))))I}}}16"
+ "Already in process to show alert for %s"
+ "Already re-provisioned once for missing PushURL/VAPID - stopping until next watchdog cycle"
+ "CellularPolicyInterface, AppAuthenticationService, and QuickSwitchStateController all unavailable"
+ "Clearing push-credentials watchdog interval override, reverting to default"
+ "DEFAULT server has unexpired Banned/Unauthorized/UserInteractionRequired XML"
+ "Either PushURL or VAPID is missing."
+ "Failed to rudimentary-parse validity from PersistentNotAllowed.xml"
+ "Failed to set policy for %{public}s when migrating from %{public}s"
+ "Found Banned XML (-1): [version: %ld, validity: %ld]"
+ "Found PersistentNotAllowed XML: [version: %ld, validity: %ld]"
+ "Got %lu policies.  Expected 1."
+ "Lazuli Push Credentials Watchdog"
+ "LazuliPhoneAuthResultObjc"
+ "NetworkAccessPolicyController_wifiOnlyDevice"
+ "Not processing network access denied callback due to event type: %s{public}"
+ "Overriding push-credentials watchdog interval to %d second(s) (QA/debug)"
+ "PersistentNotAllowed.xml"
+ "Provisioning controller unavailable for push-credentials watchdog check"
+ "Purging stale missing-push-credentials re-provision attempt timestamp (older than 24h)"
+ "Push credentials watchdog tick - checking %zu model(s)"
+ "Push disabled, VAPID is present."
+ "Push enabled, VAPID is missing."
+ "Push is disabled on Watch."
+ "Push-based RCS already established (VAPID+PushURL present), but Config.XML no longer signals pushNotification=1 - UE policy blocks reverting to persistent-connection RCS; blocking registration for up to 24h"
+ "PushSecret is missing"
+ "REDIRECTION server: [%{public}s] has unexpired Banned/Unauthorized/UserInteractionRequired XML"
+ "Showing alert for %{public}s"
+ "Successfully migrated from %{public}s to %{public}s"
+ "The correct policy was not returned.  Expected %{public}s"
+ "UE policy blocked revert from Push RCS to persistent RCS (pushNotification disabled/missing)."
+ "Unable to migrate from %{public}s to %{public}s"
+ "Using parent bundleId %{public}s for network access denied callback of %{public}s"
+ "Vapid and PushURL are missing, and Config.XML does not request Push yet - will wait for refresh to upgrade to Push"
+ "Vapid not received during refresh (expected, Push enabled)."
+ "Vapid/PushURL inconsistent with Config.XML Push expectations - request re-provisioning"
+ "Watchdog: VAPID/PushURL inconsistent with Config.XML Push expectations - forcing one re-provisioning attempt"
+ "Watchdog: VAPID/PushURL inconsistent, but server has unexpired provisioning-halt XML - skipping recovery"
+ "[%s] Push enabled but no VAPID received on first provisioning - halting for up to 24h"
+ "[%s] Subscribing to push - Vapid %s"
+ "[%s] Vapid not received during refresh - reusing valid cached VAPID (PushURL still present)"
+ "[%s] Vapid not received during refresh, and no valid cached VAPID+PushURL on disk - possible malformed/empty XML"
+ "[%{public}s] Disposing of stale/expired PersistentNotAllowed.xml before re-recording"
+ "[%{public}s] Erasing PersistentNotAllowed.xml"
+ "[%{public}s] Failed to write PersistentNotAllowed.xml"
+ "[%{public}s] UE policy blocks reverting from Push-based RCS to persistent-connection RCS"
+ "[%{public}s] Wrote PersistentNotAllowed.xml [validity: %ld]"
+ "[PersistentNotAllowed] ->"
+ "intervalSeconds"
+ "missing_push_credentials_reprovision_attempted_at"
+ "no active prov callback to reprovision (pending=%s)"
+ "rcs::pushCredWatchdogInterval"
+ "rcs::pushCredWatchdogInterval command invoked"
+ "requesting to re-prov for key=%s"
+ "reused from disk"
+ "v16@?0@\"LazuliPhoneAuthResultObjc\"8"
+ "v28@?0@\"NSString\"8B16@?<v@?@\"LazuliPhoneAuthResultObjc\">20"
+ "{LazuliPhoneAuthResult=\"fResult\"{variant<LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=\"__impl_\"{__impl<LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=\"__data\"(__union<std::__variant_detail::_Trait::_Available, 0UL, LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=\"__dummy\"c\"__head\"{__alt<0UL, LazuliPhoneAuthResult::Proof>=\"__value\"{Proof=\"fProof\"{basic_string<char, std::char_traits<char>, std::allocator<char>>=\"\"{?=\"__rep_\"(__rep=\"__s\"{__short=\"__data_\"[23c]\"__size_\"b7\"__is_long_\"b1}\"__l\"{__long=\"__data_\"*\"__size_\"Q\"__cap_\"b63\"__is_long_\"b1})}}}}\"__tail\"(__union<std::__variant_detail::_Trait::_Available, 1UL, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=\"__dummy\"c\"__head\"{__alt<1UL, LazuliPhoneAuthResult::Throttle>=\"__value\"{Throttle=\"fRetryAfterSeconds\"q}}\"__tail\"(__union<std::__variant_detail::_Trait::_Available, 2UL, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=\"__dummy\"c\"__head\"{__alt<2UL, LazuliPhoneAuthResult::NeedsReprovision>=\"__value\"{NeedsReprovision=}}\"__tail\"(__union<std::__variant_detail::_Trait::_Available, 3UL, LazuliPhoneAuthResult::Failure>=\"__dummy\"c\"__head\"{__alt<3UL, LazuliPhoneAuthResult::Failure>=\"__value\"{Failure=\"fErrorMessage\"{basic_string<char, std::char_traits<char>, std::allocator<char>>=\"\"{?=\"__rep_\"(__rep=\"__s\"{__short=\"__data_\"[23c]\"__size_\"b7\"__is_long_\"b1}\"__l\"{__long=\"__data_\"*\"__size_\"Q\"__cap_\"b63\"__is_long_\"b1})}}}}\"__tail\"(__union<std::__variant_detail::_Trait::_Available, 4UL>=)))))\"__index\"I}}}"
+ "{LazuliPhoneAuthResult={variant<LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>={__impl<LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=(__union<std::__variant_detail::_Trait::_Available, 0UL, LazuliPhoneAuthResult::Proof, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=c{__alt<0UL, LazuliPhoneAuthResult::Proof>={Proof={basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}}}(__union<std::__variant_detail::_Trait::_Available, 1UL, LazuliPhoneAuthResult::Throttle, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=c{__alt<1UL, LazuliPhoneAuthResult::Throttle>={Throttle=q}}(__union<std::__variant_detail::_Trait::_Available, 2UL, LazuliPhoneAuthResult::NeedsReprovision, LazuliPhoneAuthResult::Failure>=c{__alt<2UL, LazuliPhoneAuthResult::NeedsReprovision>={NeedsReprovision=}}(__union<std::__variant_detail::_Trait::_Available, 3UL, LazuliPhoneAuthResult::Failure>=c{__alt<3UL, LazuliPhoneAuthResult::Failure>={Failure={basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}}}(__union<std::__variant_detail::_Trait::_Available, 4UL>=)))))I}}}16@0:8"
- "AppAuthenticationService and QuickSwitchStateController both unavailable"
- "Either PushURL or VAPID is missing - persistent connection RCS is not supported. Bailing."
- "Failed to obtain phone number information"
- "[%s] Subscribing to push - Vapid received"
- "[%s] Vapid not received during refresh - possible malformed/empty XML"
- "v28@?0@\"NSString\"8B16@?<v@?@\"NSString\"@\"NSNumber\"@\"NSError\">20"
- "v32@?0@\"NSString\"8@\"NSNumber\"16@\"NSError\"24"
```
