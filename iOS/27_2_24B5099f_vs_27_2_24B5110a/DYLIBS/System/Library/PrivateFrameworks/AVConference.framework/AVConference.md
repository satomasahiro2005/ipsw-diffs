## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e3170` | `0x7e6e00` | **`+0x3c90`** |
| `__TEXT.__oslogstring` | `0x143a07` | `0x144e5d` | **`+0x1456`** |
| `__TEXT.__cstring` | `0x9f79e` | `0x9fe77` | **`+0x6d9`** |
| `__AUTH_CONST.__objc_const` | `0x6d248` | `0x6d3b8` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0x3ac50` | `0x3ad90` | **`+0x140`** |
| `__DATA_CONST.__objc_selrefs` | `0x18e40` | `0x18ed0` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x125f0` | `0x12678` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x29e40` | `0x29e80` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x7754` | `0x777c` | **`+0x28`** |
| `__TEXT.__const` | `0xc680` | `0xc690` | **`+0x10`** |
| `__DATA.__bss` | `0xf18` | `0xf10` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1dd8` | `0x1de0` | **`+0x8`** |

### Other Changes

```diff

-2260.14.1.0.0
+2260.15.1.0.0

-  Functions: 35511
-  Symbols:   42036
-  CStrings:  34132
+  Functions: 35560
+  Symbols:   42090
+  CStrings:  34195
Symbols:
+ +[VCAVFoundationCapture isZoomSupportedForCaptureDevice:captureSource:]
+ +[VCHardwareSettings supportsClientPreviewPresentationOrientation]
+ -[AVCPreviewCameraSession setPreviewPresentationOrientation:]
+ -[AVConferencePreview setPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture clearPreviewPresentationOrientation]
+ -[VCAVFoundationCapture clearRemotePresentationOrientation]
+ -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture isClientPreviewPresentationOrientationGoverning]
+ -[VCAVFoundationCapture setPreviewPresentationOrientation:]
+ -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]
+ -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]
+ -[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]
+ -[VCMediaRecorder hasConfiguredWriter]
+ -[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]
+ -[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]
+ -[VCRemoteVideoState participantId]
+ -[VCRemoteVideoState setParticipantId:]
+ -[VCSession clearRemotePresentationOrientationOnCaptureServer]
+ -[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]
+ -[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]
+ -[VCVideoCaptureServer clearRemotePresentationOrientation]
+ -[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]
+ -[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]
+ -[VCVideoCaptureServer dispatchedIsClientPreviewPresentationOrientationGoverning]
+ -[VCVideoCaptureServer handleClientPreviewPresentationOrientationMessage:]
+ -[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:]
+ -[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]
+ GCC_except_table112
+ GCC_except_table138
+ GCC_except_table140
+ GCC_except_table142
+ GCC_except_table144
+ GCC_except_table146
+ GCC_except_table164
+ GCC_except_table169
+ GCC_except_table211
+ GCC_except_table213
+ GCC_except_table215
+ GCC_except_table217
+ GCC_except_table235
+ GCC_except_table269
+ GCC_except_table272
+ GCC_except_table275
+ GCC_except_table318
+ _AVErrorDeviceKey
+ _OBJC_IVAR_$_AVConferencePreview._preRegistrationCameraUIDToSession
+ _OBJC_IVAR_$_AVConferencePreview._setPrimarySecondaryInFlightCount
+ _OBJC_IVAR_$_VCAVFoundationCapture._hasPreviewPresentationOrientation
+ _OBJC_IVAR_$_VCAVFoundationCapture._hasVideoPresentationOrientation
+ _OBJC_IVAR_$_VCAVFoundationCapture._previewPresentationOrientation
+ _OBJC_IVAR_$_VCRemoteVideoState._participantId
+ _OBJC_IVAR_$_VCVideoCaptureServer._hasPreviewPresentationOrientationRequest
+ _OBJC_IVAR_$_VCVideoCaptureServer._hasRemotePresentationOrientation
+ _OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequest
+ _OBJC_IVAR_$_VCVideoCaptureServer._previewPresentationOrientationRequestPID
+ _OBJC_IVAR_$_VCVideoCaptureServer._remotePresentationOrientation
+ _OBJC_IVAR_$_VCVideoStream._didDetectSensitiveContentFired
+ _OBJC_IVAR_$_VCVideoStream._didFlushForInterruptedFrameRun
+ _VCImageQueue_Flush
+ _VCMediaRecorderHistory_HasConfiguredWriter
+ _VCRemoteVideoManager_FlushQueuesExceptStreamToken
+ _VCRemoteVideoManager_SetParticipantIdForStreamToken
+ _VCVideoCaptureServer_ClientPIDFromArguments
+ ___57-[AVConferencePreview setPreviewPresentationOrientation:]_block_invoke
+ ___58-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke
+ ___59-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke
+ ___60-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke
+ ___61-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke
+ ___66+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke
+ ___76-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke
+ ___77-[VCVideoCaptureServer copyLocalRecordingScreenAttributesForVideoAttributes:]_block_invoke
+ ___78-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]_block_invoke
+ ___80-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke
+ ___VCMediaRecorderHistory_HasConfiguredWriter_block_invoke
+ ___VCRemoteVideoManager_FlushQueuesExceptStreamToken_block_invoke
+ ___VCRemoteVideoManager_SetParticipantIdForStreamToken_block_invoke
+ _supportsClientPreviewPresentationOrientation.onceToken
+ _supportsClientPreviewPresentationOrientation.resolved
- +[VCHardwareSettings supportsSquarePreviewCapture]
- -[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]
- -[VCAVFoundationCapture squarePreviewAdjustedRequestSizeForCaptureSize:]
- -[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]
- -[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]
- -[VCVideoCaptureServer copyLocalScreenAttributesForVideoAttributes:]
- GCC_except_table111
- GCC_except_table139
- GCC_except_table141
- GCC_except_table143
- GCC_except_table145
- GCC_except_table147
- GCC_except_table168
- GCC_except_table198
- GCC_except_table200
- GCC_except_table210
- GCC_except_table220
- GCC_except_table245
- GCC_except_table254
- GCC_except_table257
- GCC_except_table301
- _OBJC_IVAR_$_VCAVFoundationCapture._clientRequestedSize
- _OBJC_IVAR_$_VCAVFoundationCapture._configuringForCapture
- _OBJC_IVAR_$_VCAVFoundationCapture._squarePreviewOverrideActive
- ___50+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke
- _supportsSquarePreviewCapture.onceToken
- _supportsSquarePreviewCapture.resolved
CStrings:
+ " [%s] %s:%d %@(%p) Skipping, a writer is already composed for"
+ " [%s] %s:%d %@(%p) [FTDC] Primary connections video=%d metadata=%d"
+ " [%s] %s:%d %@(%p) width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d, hasVideoPresentationOrientation=%d, previewPresentationOrientation=%d, hasPreviewPresentationOrientation=%d"
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/VCRemoteVideoManager.m:%d: VCRemoteVideoManager: null object was passed to FlushQueuesExceptStreamToken"
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/VCRemoteVideoManager.m:%d: VCRemoteVideoManager: null object was passed to SetParticipantIdForStreamToken"
+ " [%s] %s:%d No participantId recorded for streamToken=%ld, skipping flush"
+ " [%s] %s:%d Skipping, a writer is already composed for"
+ " [%s] %s:%d VCDTMFToneGenerator[%p] Initialize event=%d, powerLevel=%d, sampleRate=%d, tableAmplitude=%d, amplitude=%d"
+ " [%s] %s:%d VCHardwareSettings: clientPreviewPresentationOrientation support overridden by user default: outOfBox=%d override=%d"
+ " [%s] %s:%d [AR_TX] captureAspectRatio=%@, composeLandscapeOrderedRatio=%d, clientPreviewGoverns=%d, _videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, _previewPresentationOrientation=%d, _hasPreviewPresentationOrientation=%d, _orientation=%d, _deviceOrientationMatchesReceiver=%d, _remotePreferFullBleed=%d, overrideByDefault=%d"
+ " [%s] %s:%d [AR_TX] client preview presentation orientation not honored, the active format cannot vend it. aspectRatio=%@, _previewPresentationOrientation=%d, _orientation=%d"
+ " [%s] %s:%d [AR_TX]_videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, orientation=%d, _deviceOrientationMatchesReceiver=%d"
+ " [%s] %s:%d [FTDC] Primary connections video=%d metadata=%d"
+ " [%s] %s:%d _previewPresentationOrientation=%d, _hasPreviewPresentationOrientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d _previewPresentationOrientation=%d, didChange=%d, _orientation=%d, _videoPresentationOrientation=%d, _hasVideoPresentationOrientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d wasClientGoverning=%d, _orientation=%d, _isPreviewing=%d, _isCapturing=%d"
+ " [%s] %s:%d width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d, hasVideoPresentationOrientation=%d, previewPresentationOrientation=%d, hasPreviewPresentationOrientation=%d"
+ "+[VCHardwareSettings supportsClientPreviewPresentationOrientation]_block_invoke"
+ "-[AVCPreviewCameraSession setPreviewPresentationOrientation:]_block_invoke"
+ "-[AVConferencePreview setPreviewPresentationOrientation:]"
+ "-[VCAVFoundationCapture clearPreviewPresentationOrientation]_block_invoke"
+ "-[VCAVFoundationCapture clearRemotePresentationOrientation]_block_invoke"
+ "-[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:hasVideoPresentationOrientation:previewPresentationOrientation:hasPreviewPresentationOrientation:]"
+ "-[VCAVFoundationCapture setPreviewPresentationOrientation:]_block_invoke"
+ "-[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:captureSource:]"
+ "-[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:]"
+ "-[VCAVFoundationCapture vendableAspectRatio:landscapeOrderedAlternate:captureFormat:clientPreviewGoverns:]"
+ "-[VCMediaRecorderLocal localRecordingScreenAttributesDidChange:]"
+ "-[VCMediaRecorderLocal updateTargetScreenAttributesFromCaptureServer]"
+ "-[VCVideoCaptureServer applyClientPreviewPresentationOrientationArguments:]"
+ "-[VCVideoCaptureServer clearPreviewPresentationOrientationRequestForDiedClient:]_block_invoke"
+ "-[VCVideoCaptureServer clearRemotePresentationOrientation]"
+ "-[VCVideoCaptureServer clearRemotePresentationOrientation]_block_invoke"
+ "-[VCVideoCaptureServer dispatchedClearPreviewPresentationOrientationRequest]"
+ "-[VCVideoCaptureServer dispatchedCopyLocalRecordingScreenAttributesForVideoAttributes:]"
+ "-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]"
+ "-[VCVideoCaptureServer notifyClientsLocalRecordingScreenAttributesDidChange]_block_invoke"
+ "-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_6"
+ "-[VCVideoCaptureServer setPreviewPresentationOrientation:requestingClientPID:]"
+ "2260.15.1"
+ "AVCPreviewCameraSession [%s] %s:%d %@(%p) cameraUID=%@ orientation=%d"
+ "AVCPreviewCameraSession [%s] %s:%d cameraUID=%@ orientation=%d"
+ "AVConferencePreview [%s] %s:%d %@(%p) orientation=%d"
+ "AVConferencePreview [%s] %s:%d orientation=%d"
+ "VCMediaRecorderHistory_HasConfiguredWriter"
+ "VCRemoteVideoManager_FlushQueuesExceptStreamToken"
+ "VCRemoteVideoManager_SetParticipantIdForStreamToken"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Discarding client preview presentation orientation request, unsupported by the hardware rule. previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Invalid previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Missing or non-numeric previewPresentationOrientation, class=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) No local video attributes to derive recording screen attributes from"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Notifying client=%p of class=%@"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Retaining the remote presentation orientation at call end, unsupported by the hardware rule."
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) Retaining the request, the dying client did not make it. diedClientPID=%d, _previewPresentationOrientationRequestPID=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) [AR_RX] videoOrientation=%d, screenOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d, _previewPresentationOrientationRequestPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) _remotePresentationOrientation=%d, _hasRemotePresentationOrientation=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d %@(%p) previewPresentationOrientation=%d, requestingClientPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d Discarding client preview presentation orientation request, unsupported by the hardware rule. previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d Invalid previewPresentationOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d Missing or non-numeric previewPresentationOrientation, class=%@"
+ "VCVideoCaptureServer [%s] %s:%d No local video attributes to derive recording screen attributes from"
+ "VCVideoCaptureServer [%s] %s:%d Notifying client=%p of class=%@"
+ "VCVideoCaptureServer [%s] %s:%d Retaining the remote presentation orientation at call end, unsupported by the hardware rule."
+ "VCVideoCaptureServer [%s] %s:%d Retaining the request, the dying client did not make it. diedClientPID=%d, _previewPresentationOrientationRequestPID=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d [AR_RX] videoOrientation=%d, screenOrientation=%d"
+ "VCVideoCaptureServer [%s] %s:%d _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d, _previewPresentationOrientationRequestPID=%d"
+ "VCVideoCaptureServer [%s] %s:%d _remotePresentationOrientation=%d, _hasRemotePresentationOrientation=%d, _previewPresentationOrientationRequest=%d, _hasPreviewPresentationOrientationRequest=%d"
+ "VCVideoCaptureServer [%s] %s:%d ignoring stale capture failure, failingCameraUID=%@, currentCameraUID=%@"
+ "VCVideoCaptureServer [%s] %s:%d previewPresentationOrientation=%d, requestingClientPID=%d"
+ "VCVideoStream [%s] %s:%d VCVideoStream[%p] sensitive content interrupted frame, flushing other queues, streamToken=%ld"
+ "_VCRemoteVideoManager_DispatchedFlushQueuesExceptStreamToken"
+ "forceClientPreviewPresentationOrientation"
+ "previewPresentationOrientation"
+ "previewSetPresentationOrientation"
+ "secondary camera UID must differ from the primary camera UID"
- " [%s] %s:%d %@(%p) width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d"
- " [%s] %s:%d VCDTMFToneGenerator[%p] Initialize event=%d, powerLevel=%d, sampleRate=%d"
- " [%s] %s:%d VCHardwareSettings: squarePreviewCapture support overridden by user default: outOfBox=%d override=%d"
- " [%s] %s:%d [AR_TX] _deviceOrientationMatchesReceiver=%d, _remotePreferFullBleed=%d, previewOnly=%d, prefersSquarePreview=%d, captureAspectRatio=%@, overrideByDefault=%d"
- " [%s] %s:%d [AR_TX]videoPresentationOrientation=%d, orientation=%d, _deviceOrientationMatchesReceiver=%d"
- " [%s] %s:%d width=%d, height=%d, frameRate=%d, sourceToken=0x%x, cinematicFramingEnabled=%d, orientation=%d, zoomFactor=%f, remoteSupportsFullScreenReceive=%d, videoPresentationOrientation=%d"
- "+[VCHardwareSettings supportsSquarePreviewCapture]_block_invoke"
- "-[VCAVFoundationCapture initWithCaptureServer:protocolFunctions:width:height:frameRate:videoSourceToken:cinematicFramingEnabled:videoOrientation:capturePixelFormat:zoomFactor:remoteSupportsFullScreenReceive:videoPresentationOrientation:]"
- "-[VCAVFoundationCapture updateCameraZoomCapabilityForCaptureDeviceInput:]"
- "-[VCAVFoundationCapture updateDeviceOrientationMatchesReceiver:videoPresentationOrientation:]"
- "-[VCVideoCaptureServer registerBlocksForServer]_block_invoke_5"
- "2260.14.1"
- "forceSquarePreviewCapture"
```
