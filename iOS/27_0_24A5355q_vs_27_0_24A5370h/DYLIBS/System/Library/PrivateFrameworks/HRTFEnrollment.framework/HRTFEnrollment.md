## HRTFEnrollment

> `/System/Library/PrivateFrameworks/HRTFEnrollment.framework/HRTFEnrollment`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93d4` | `0x93c0` | **`-0x14`** |

### Other Changes

```diff

-40.28.1.1.2
+40.31.1.0.0
Functions:
~ -[HRTFEnrollmentPoseStatus initWithYawPose:pitchPose:isEarTracking:yawAngle:pitchAngle:] : 924 -> 916
~ -[HRTFEnrollmentPoseStatus remainingYawAngles] : 428 -> 424
~ -[HRTFEnrollmentPoseStatus remainingPitchAngles] : 428 -> 424
~ -[_SerializableCVPixelBuffer initWithCoder:] : 2156 -> 2140
~ ___planarDeallocateHelper : 64 -> 80
~ -[HRTFSyncedCaptureSource _verifyCaptureDevice:] : 1296 -> 1288
~ -[HRTFSyncedCaptureSource _initialize] : 1336 -> 1332
~ -[HRTFSyncedCaptureSource dataOutputSynchronizer:didOutputSynchronizedDataCollection:] : 704 -> 700
~ -[HRTFEnrollmentSession initializeDevice] : 524 -> 520
~ -[HRTFEnrollmentSession _verifyCaptureDevice:] : 1312 -> 1304
~ +[RecordingManager copyBuffer:dst:] : 344 -> 368
```
