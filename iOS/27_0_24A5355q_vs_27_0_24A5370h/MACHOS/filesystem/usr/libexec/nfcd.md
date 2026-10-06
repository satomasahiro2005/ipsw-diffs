## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e4cac` | `0x1e5bf4` | **`+0xf48`** |
| `__TEXT.__objc_methname` | `0x154d7` | `0x157d0` | **`+0x2f9`** |
| `__TEXT.__objc_stubs` | `0xdbe0` | `0xdde0` | **`+0x200`** |
| `__DATA_CONST.__cfstring` | `0x11620` | `0x11760` | **`+0x140`** |
| `__DATA.__objc_const` | `0x14ab0` | `0x14bd8` | **`+0x128`** |
| `__TEXT.__cstring` | `0x22772` | `0x2287e` | **`+0x10c`** |
| `__TEXT.__objc_methlist` | `0x9be4` | `0x9cd4` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0x4ac8` | `0x4b78` | **`+0xb0`** |
| `__TEXT.__objc_methtype` | `0x4d4c` | `0x4de2` | **`+0x96`** |
| `__TEXT.__oslogstring` | `0x200f6` | `0x2016b` | **`+0x75`** |
| `__TEXT.__unwind_info` | `0x2bc0` | `0x2c30` | **`+0x70`** |
| `__DATA.__objc_ivar` | `0x10e0` | `0x1104` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x9a38` | `0x9a18` | **`-0x20`** |
| `__TEXT.__const` | `0x13dc` | `0x13bc` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0x1d3e` | `0x1d22` | **`-0x1c`** |
| `__DATA_CONST.__objc_arraydata` | `0x1e50` | `0x1e38` | **`-0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x330` | `0x318` | **`-0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x7ba8` | `0x7bc0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x830` | `0x838` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0

-  Functions: 4238
-  Symbols:   665
-  CStrings:  11319
+  Functions: 4257
+  Symbols:   666
+  CStrings:  11378
Symbols:
+ _OBJC_CLASS_$_NFReportingService
CStrings:
+ "\nFailure timestamp: %@\n"
+ " - %@"
+ "%{public}s:%i Failed to configure plasticCardModeForApplet %{public}@: %{public}@"
+ "%{public}s:%i Failed to configure reporter: %{public}@"
+ "%{public}s:%i Failed to decrypt %{public}@ cert: %{public}@"
+ "%{public}s:%i Failed to initialize SMC interface"
+ "%{public}s:%i Failed to notify SMC about power %{public}@, value: 0x%02x"
+ "%{public}s:%i Failed to open SMC client: 0x%x"
+ "%{public}s:%i Failed to open service: 0x%x"
+ "%{public}s:%i Failed to send report - got HTTP Response code %d"
+ "%{public}s:%i Failed to serialize report JSON: %{public}@"
+ "%{public}s:%i Message is dropped%{public}@."
+ "%{public}s:%i Read failed for key '%s' (0x%X, 0x%X)"
+ "%{public}s:%i Report send failed: %{public}@"
+ "%{public}s:%i Report sent, HTTP %d"
+ "%{public}s:%i SMC not initialized"
+ "%{public}s:%i Sending report: %@"
+ "%{public}s:%i Sent notification to SMC about power %{public}@, value: 0x%02x"
+ "%{public}s:%i Unable to find SMC service"
+ "%{public}s:%i Write failed for key '%s' (0x%X, 0x%X)"
+ ", error=%@"
+ "-[NFBackgroundTagReadingManager handleMessage:]_block_invoke"
+ "-[NFPaymentTagReaderDeveloperPresentmentReporter _sendReportToServer:outError:]"
+ "-[NFSMC open]"
+ "-[NFSMC readKey:data:size:]"
+ "-[NFSMC writeKey:data:size:]"
+ "-[NFTemperatureReporter open]"
+ "-[_NFFailForwardCoordinator _triggerMustStopDelegates:]"
+ "@\"NFReportingService\""
+ "@\"NFSMC\""
+ "DisablePaymentReaderDevelopmentServerReporting"
+ "ECC384"
+ "ECDSA384"
+ "ECKA384"
+ "EEE MMM d HH:mm:ss yyyy"
+ "NFC/SE TTR - %@ on %@"
+ "NFCD built from (B&I) Stockholm_Base-370.37"
+ "NFSMC"
+ "T@\"NSString\",R,&,N,V_ecdsa384Cert"
+ "T@\"NSString\",R,&,N,V_ecka384Cert"
+ "_configureReporter"
+ "_disableServerReporting"
+ "_ecdsa384Cert"
+ "_ecdsa384CertificateAsData"
+ "_ecka384Cert"
+ "_ecka384CertificateAsData"
+ "_failureDate"
+ "_isReporterConfigured"
+ "_locationReceivedAfterSessionStart"
+ "_reportingService"
+ "_sendReportToServer:outError:"
+ "_smc"
+ "_smcConnection"
+ "close"
+ "com.apple.stockholm.fault.spmi.primary"
+ "com.apple.stockholm.fault.spmi.secondary"
+ "configureReporterWithSEKeying:"
+ "deleteDeveloperPaymentReportWithID:"
+ "ecdsa384"
+ "ecdsa384Cert"
+ "ecdsa384Certificate"
+ "ecka384"
+ "ecka384Cert"
+ "ecka384Certificate"
+ "en_US_POSIX"
+ "i24@0:8I16C20"
+ "i24@0:8I16I20"
+ "i24@0:8I16S20"
+ "i28@0:8I16*20"
+ "i28@0:8I16^I20"
+ "i28@0:8I16^S20"
+ "i32@0:8@16^@24"
+ "i36@0:8I16^v20Q28"
+ "localeWithLocaleIdentifier:"
+ "postPaymentTagReaderDeveloperPresentmentReportsWithCompletion:"
+ "readKey:data:size:"
+ "readKey:valueU16:"
+ "readKey:valueU32:"
+ "readKey:valueU8:"
+ "sceneService handling completed"
+ "sendReport:outError:"
+ "setLocale:"
+ "stringByAppendingFormat:"
+ "writeKey:data:size:"
+ "writeKey:valueU16:"
+ "writeKey:valueU32:"
+ "writeKey:valueU8:"
+ "\xf0Qa"
- "%{public}s:%i Could not open service: %#x"
- "%{public}s:%i Error unexpected primary delegate state: %@"
- "%{public}s:%i Error unexpected secondary delegate state: %@"
- "%{public}s:%i Failed to configure plasticCardModeForApplet: %{public}@"
- "%{public}s:%i Failed to decrypt ECDSA cert : %s"
- "%{public}s:%i Failed to decrypt ECKA cert : %s"
- "%{public}s:%i Failed to decrypt RSA cert : %s"
- "%{public}s:%i Failed to get AppleSMCSensorDispatcher"
- "%{public}s:%i Failed to notify SMC about power %{public}@, value: 0x%02llx"
- "%{public}s:%i Failed to restore emulation after enabling plastic card mode"
- "%{public}s:%i Failed to write SMC key %s - %x"
- "%{public}s:%i Posting HomeKit Tag notification with UID : %@ for urlText = %@"
- "%{public}s:%i Sent notification to SMC about power %{public}@, value: 0x%02llx"
- "%{public}s:%i Write failed for key '%s' (0x%X, 0x%X)\n"
- "-[NFTagAppProcessorHomeKitAccessory processNDEFMesssage:outputMessage:tag:stopProcessing:]"
- "-[_NFFailForwardCoordinator _triggerMustStopDelegates]"
- "AppleSMCSensorDispatcher"
- "NFCD built from (B&I) Stockholm_Base-370.33.1"
- "NFCUISceneService activate"
- "NFSMCWriteKey"
- "NFTagAppProcessorHomeKitAccessory"
- "_primaryDelegateState == kDelegateStateDidStop"
- "_secondaryDelegateState == kDelegateStateDidStop"
- "_writeSMCKey"
- "ch"
- "com.apple.nfcd.homekit.proxcard"
- "mt"
- "x-hm"
- "\xf0Aa"
```
