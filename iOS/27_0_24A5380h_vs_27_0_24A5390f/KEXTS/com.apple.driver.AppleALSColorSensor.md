## com.apple.driver.AppleALSColorSensor

> `com.apple.driver.AppleALSColorSensor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1546c` | `0x1d928` | **`+0x84bc`** |
| `__TEXT.__cstring` | `0x3844` | `0x490a` | **`+0x10c6`** |
| `__DATA_CONST.__const` | `0x7248` | `0x76d8` | **`+0x490`** |
| `__TEXT_EXEC.__auth_stubs` | `0x330` | `0x690` | **`+0x360`** |
| `__DATA_CONST.__auth_got` | `0x198` | `0x348` | **`+0x1b0`** |
| `__TEXT.__const` | `0x118` | `0x148` | **`+0x30`** |

### Other Changes

```diff

-2300.0.10.0.1
-  Functions: 415
+2300.0.18.502.1
+  Functions: 645

-  CStrings:  411
+  CStrings:  451
CStrings:
+ "\"TB_ASSERT: \" \"(alsdefines_alsreport__decode(msg, &report) == TB_ERROR_SUCCESS) && \\\"failed to decode type: ALSDefines.ALSReport\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(calibrationbufferelement__v_decode(msg, &calib) == TB_ERROR_SUCCESS) && \\\"failed to decode type: ALSDefines.CalibrationBufferElement (aka. UInt8)\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(cmp.encoded) && \\\"completion block must be called before returning\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(err == TB_ERROR_SUCCESS || err == TB_ERROR_USER_FAILURE) && \\\"unexpected tb_error_t returned\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(err == TB_ERROR_SUCCESS) && \\\"failed to wrap packed buffer\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->getmanifest != ((void*)0)) && \\\"implementation for getManifest is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->getsensoranalytics != ((void*)0)) && \\\"implementation for getSensorAnalytics is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->handlepowerevent != ((void*)0)) && \\\"implementation for handlePowerEvent is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->handlereport != ((void*)0)) && \\\"implementation for handleReport is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->isactive != ((void*)0)) && \\\"implementation for isActive is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->setbrightness != ((void*)0)) && \\\"implementation for setBrightness is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->setcalibration != ((void*)0)) && \\\"implementation for setCalibration is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->setintegrationmode != ((void*)0)) && \\\"implementation for setIntegrationMode is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->setreportinterval != ((void*)0)) && \\\"implementation for setReportInterval is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->setsamplingconfig != ((void*)0)) && \\\"implementation for setSamplingConfig is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(server->settrustedreportinterval != ((void*)0)) && \\\"implementation for setTrustedReportInterval is not present\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(vErr == TB_ERROR_SUCCESS) && \\\"tb_message_subrange failed\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid error returned from %s\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid result returned from getManifest\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid result returned from getSensorAnalytics\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid tag in `[ALSDefines.ALSCFSNBufferElement (aka. UInt8)]` metadata: 0x%x\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid tag in `[ALSDefines.CalibrationBufferElement (aka. UInt8)]` metadata: 0x%x\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid value: unexpected case value, %llx\" @%s:%d"
+ "\"TB_FATAL: \" \"overflow detected when adding\" @%s:%d"
+ "\"TB_FATAL: \" \"unrecognized selector: %llu\" @%s:%d"
+ "AppleALSColorSensor_c.c"
+ "AppleSPUCT726::%s: alsreport unmarshal failed (tb_error=%u, size=%u)\n"
+ "AppleSPUCT726::%s: alsreport unmarshal failed (tb_error=%u, size=%zu)\n"
+ "AppleSPUVL628::%s: alsreport unmarshal failed (tb_error=%u, size=%u)\n"
+ "AppleSPUVL628::%s: alsreport unmarshal failed (tb_error=%u, size=%zu)\n"
+ "I12@?0B8"
+ "I12@?0I8"
+ "I16@?0^{tb_message_s=ICQQQQ[4Q]Q^{tb_transport_message_buffer_s}}8"
+ "I60@?0{alsdefines_alsfrontendbase_getsensoranalytics__result_s=C(?=I{alsdefines_sensoranalyticsreport_s=[6{alsdefines_sensorfault_s=II}]})}8"
+ "I72@?0{alsdefines_alscontrol_getmanifest__result_s=C(?=I{alsdefines_alsmanifest_s=II{alscfsnbufferelement_v_s=C(?={?=*Q@?}{?=*QQ}{?=^{tb_message_s}QQQ})}I})}8"
+ "I8@?0"
+ "^{tb_message_s=ICQQQQ[4Q]Q^{tb_transport_message_buffer_s}}24@?0^{tb_connection_s=(?=[97c]^v)}8^{tb_message_s=ICQQQQ[4Q]Q^{tb_transport_message_buffer_s}}16"
+ "getManifest"
+ "getSensorAnalytics"
+ "v240@?0{alsdefines_alsreport_s=IfQQ{alsdefines_vendordata_s=Q(?={?={alsdefines_vendorvd6286_s=I[5i][5i][5s]fIfIIfI[5I]}}{?={alsdefines_vendormorayfamily_s=QQQQ[5f][5f][5f][5f][5f]IfIIffIIII{f32__opt_s=Bf}SSCCCBBB}}{?={alsdefines_vendormorayfamily_s=QQQQ[5f][5f][5f][5f][5f]IfIIffIIII{f32__opt_s=Bf}SSCCCBBB}}{?={alsdefines_vendorct725_s=I[5i][5s]fIII}}{?={alsdefines_vendor2ch_s=[2f][2S]SIIB}}{?={alsdefines_vendor2ch_s=[2f][2S]SIIB}})}CC}8"
```
