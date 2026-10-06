## com.apple.driver.ApplePearlSEPDriver

> `com.apple.driver.ApplePearlSEPDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3f478` | `0x40b64` | **`+0x16ec`** |
| `__TEXT.__cstring` | `0xaf58` | `0xb369` | **`+0x411`** |
| `__DATA_CONST.__const` | `0x2428` | `0x25a8` | **`+0x180`** |
| `__TEXT.__os_log` | `0x4d0d` | `0x4e19` | **`+0x10c`** |
| `__DATA_CONST.__kalloc_type` | `0x600` | `0x640` | **`+0x40`** |
| `__DATA.__common` | `0x238` | `0x260` | **`+0x28`** |

### Other Changes

```diff

-  Functions: 720
+  Functions: 751

-  CStrings:  1718
+  CStrings:  1743
CStrings:
+ "%s: ANE1 power function%s found\n"
+ "(_hasMirage == kBoolFalse) || (_summervilleFWCertInSEP == kBoolTrue)"
+ "121111121222121211212111111111111111111111211211222222221222112222222211112111112122221212111222222222222121122211122222221222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222212222222212212222222221212222222222122212222222222222222121211222222221221222122111122222222112122223111122212212211111111111211222111221"
+ "12112222222222"
+ "ERROR: IOPearlExclaveCameraFrame::%s: AssertMacros: %s (value = 0x%lx), %s file: %s, line: %d\n\n\n"
+ "GetPlatformHasMirage"
+ "GetReferenceFramesInfoRecord"
+ "IOPearlExclaveCameraFrame"
+ "IOPearlExclaveCameraFrame::%s -> result:%d (frameId:[%d:%d], _framesHeldCount:%d)\n"
+ "IOPearlExclaveCameraFrame::%s: frameId:[%d:%d], _framesHeldCount:%d\n"
+ "LoadReferenceFramesInfoRecord"
+ "PSClearSession"
+ "PSEstablishSharedSecret"
+ "PSGenerateHostEphemeralKey"
+ "PSGenerateHostUnwrapData"
+ "PSSetSensorUnwrapData"
+ "ProcessFrameMetadata"
+ "_hasMirage != kBoolNotSet"
+ "_hasMirage == kBoolTrue"
+ "_savageSessionOptions.sensorType == kSavageSensorTypeAries || _savageSessionOptions.sensorType == kSavageSensorTypeHamal"
+ "_summervilleFWCertInSEP == kBoolNotSet"
+ "function-ane1_power_func"
+ "metadata.sequenceNumber == _camera->_frameSequenceCount"
+ "payloadSize >= __builtin_offsetof(cmd_load_ref_frames_info_record_in_v1_t, refFramesInfoRecordData)"
+ "payloadSize >= sizeof(cmd_process_frame_metadata_in_v1_t)"
+ "psd3->hdr.magic == (0x45674567) || (psd3->hdr.magic == (0xdead4567) && isV63p1Psd2MagicAllowed())"
+ "psdHeader->magic == (0x45674567) || (psdHeader->magic == (0xdead4567) && isV63p1Psd2MagicAllowed())"
+ "request->verifyOnly || _refFramesInfoRecordInSEP == kBoolNotSet"
+ "site.IOPearlExclaveCameraFrame"
- "1211111212221212112121111111111111111111112112112222222212221122222222111121111121222212121112222222222221211222111222222212222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222122222222122122222222121222222222212221222222222222222212121122222222122122212211112222222211212222311122212212211111111111211222111221"
- "_savageSessionOptions.sensorType == kSavageSensorTypeAries"
- "psd3->hdr.magic == (0x45674567)"
- "psdHeader->magic == (0x45674567)"
```
