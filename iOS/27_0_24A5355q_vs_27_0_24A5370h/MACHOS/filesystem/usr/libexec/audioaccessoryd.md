## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x253e64` | `0x25481c` | **`+0x9b8`** |
| `__TEXT.__cstring` | `0x583a3` | `0x58773` | **`+0x3d0`** |
| `__TEXT.__unwind_info` | `0x6ff0` | `0x71d8` | **`+0x1e8`** |
| `__TEXT.__objc_methname` | `0x2d145` | `0x2d205` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x1fde0` | `0x1fe88` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0xe7b4` | `0xe844` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0xb8c0` | `0xb940` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x1f140` | `0x1f1c0` | **`+0x80`** |
| `__DATA.__data` | `0x5ab0` | `0x5b10` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xcbc8` | `0xcbf8` | **`+0x30`** |
| `__TEXT.__const` | `0x4d00` | `0x4d30` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x9290` | `0x92b8` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x41d9` | `0x41f9` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x1133` | `0x1143` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-40.28.1.1.2
+40.31.1.0.0

-  Functions: 11956
+  Functions: 11995

-  CStrings:  16272
+  CStrings:  16305
CStrings:
+ "### performActionsOnConnectionIfNeeded: device identifier not set"
+ "### sendPreferenceEQMessage (V3) failed: %@"
+ "-[AAGeneralMessageManager _performActionsOnConnectionIfNeeded:]"
+ "-[AAGeneralMessageManager _performActionsOnConnectionIfNeeded:]_block_invoke"
+ "-[SRArbitrationManager allowBTHijackWithAudioScore:srWxDevice:context:hijackDeniedReason:]"
+ "3rd party app ringtone shall not hijack non-watch tipi device"
+ "B44@0:8I16@20@28^@36"
+ "EqualizerHigh"
+ "EqualizerLow"
+ "EqualizerMid"
+ "EqualizerMode"
+ "IsSRConnectEligible: allowing low activity iPhone source to connect to Wx %@ which has no source connected and out of case > 5s"
+ "IsSRConnectEligible: skip, iPhone source activity low and Wx already connected to a source, Wx %@"
+ "IsSRConnectEligible: skip, low activity iPhone source but Wx %@ out of case <= 5s"
+ "Preference EQ V3 message sent successfully to: %@"
+ "ReceivedOwnershipLost: Updated otherTipiAudioCategory to relinquish score %u"
+ "SRBTHijackContext"
+ "Sending Preference EQ V3 message on connection to device: %@"
+ "Step1"
+ "Step2"
+ "Step3"
+ "Step4"
+ "Step6"
+ "Step7"
+ "Step8"
+ "Step9"
+ "Version3"
+ "[Hijackv2] Don't allow hijack for score < %d "
+ "[Hijackv2] Wx stream state does not match remote score, fallback to legacy hijack"
+ "[Hijackv2] allowBTHijackWithAudioScore: context is NULL"
+ "[Hijackv2] allowBTHijackWithAudioScore: srWxDevice is NULL"
+ "[Hijackv2] local %u vs remote %u isPhoneCallHijack %s CallCount %lu otherTipi %@ %d.%d prioritizedCall %s"
+ "_performActionsOnConnectionIfNeeded:"
+ "allowBTHijackWithAudioScore:srWxDevice:context:hijackDeniedReason:"
+ "i24@0:8@\"NSString\"16"
+ "performActionsOnConnectionIfNeeded:"
+ "prioritizedCallEnabled"
+ "wxStreamStateForAddress:"
- "-[BTSmartRoutingDaemon allowHijackWithAudioScore:hijackRoute:hijackDeniedReason:]"
- "3rd Party ringtone shall not hijack non-watch tipi device"
- "[Hijackv2] Dont allow hijack for score < %d "
- "[Hijackv2] Wx stream state not matches remote score, fallback to legacy hijack"
- "[Hijackv2] local %u vs remote %u isPhoneCallHijack %s CallCount %d otherTipi %@ %d.%d prioritizedCall %s"
```
