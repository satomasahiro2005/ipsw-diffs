## mediaanalysisd-service

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd-service`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x239758` | `0x21aba4` | **`-0x1ebb4`** |
| `__TEXT.__cstring` | `0x14134` | `0x108b4` | **`-0x3880`** |
| `__TEXT.__gcc_except_tab` | `0x37f3c` | `0x35c0c` | **`-0x2330`** |
| `__TEXT.__oslogstring` | `0x30b41` | `0x2fb81` | **`-0xfc0`** |
| `__DATA_CONST.__cfstring` | `0xa0c0` | `0x9580` | **`-0xb40`** |
| `__TEXT.__unwind_info` | `0x8a80` | `0x82f0` | **`-0x790`** |
| `__DATA_CONST.__const` | `0x8418` | `0x7ef0` | **`-0x528`** |
| `__TEXT.__objc_stubs` | `0x190a0` | `0x18be0` | **`-0x4c0`** |
| `__TEXT.__objc_methname` | `0x21df5` | `0x21bc9` | **`-0x22c`** |
| `__DATA.__bss` | `0x3bb0` | `0x3990` | **`-0x220`** |
| `__TEXT.__objc_methlist` | `0xb7e8` | `0xb6d0` | **`-0x118`** |
| `__DATA.__objc_selrefs` | `0x6bf0` | `0x6b48` | **`-0xa8`** |
| `__DATA.__data` | `0x1830` | `0x17a8` | **`-0x88`** |
| `__TEXT.__auth_stubs` | `0x38f0` | `0x38c0` | **`-0x30`** |
| `__DATA.__objc_const` | `0x17c00` | `0x17be0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x1c90` | `0x1c78` | **`-0x18`** |
| `__TEXT.__const` | `0x2600` | `0x2610` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x424b` | `0x423b` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2980` | `0x2978` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1524` | `0x1520` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-460.14.1.1.0
+460.14.1.2.0

-  Functions: 7075
-  Symbols:   2342
-  CStrings:  10645
+  Functions: 6433
+  Symbols:   2338
+  CStrings:  10363
Symbols:
+ _objc_retain_x10
- _NSSelectorFromString
- _OBJC_CLASS_$_NSInvocation
- _VCPMADGetReadableMemoryUsageInformation
- __os_crash
- _puts
CStrings:
+ "Daemon appears to be hung; self-terminating"
- "\nUsage:\n\t-f,--full-interval   Interval to schedule full background analysis at (seconds)\n\t-h,--help            Display this usage information and exit\n"
- " %@"
- "#%lu[%.2fs,+%.2fs]"
- "%@ --> rejected person %@"
- "%@ Add face %@ (%lu)"
- "%@ Adding FaceOnly to Gallery"
- "%@ Adding FaceTorso to Gallery"
- "%@ Adding TorsoOnly to Gallery"
- "%@ Adding observation without valid print"
- "%@ BypassMaxFragmentDuration"
- "%@ Client FaceCrop %@"
- "%@ Client asset %@"
- "%@ Custom client prompt: %.100s ..."
- "%@ Deleting unverified person %@ (%@)"
- "%@ Direct client prompt: %.100s ..."
- "%@ DownloadLLMJpegs (internal variant: %@)"
- "%@ DownloadUnsafeCaptions"
- "%@ Entity to update %ld"
- "%@ Face %@ confirms graph verified person %@"
- "%@ Face %@ confirms user verified person %@"
- "%@ Face %@ rejects %lu persons"
- "%@ Face %@ rejects person %@"
- "%@ Gallery indexed FaceCrop %@"
- "%@ Gallery indexed asset %@"
- "%@ Latest bookmark from VU %@"
- "%@ No face for observation %@"
- "%@ Orphan training face %@"
- "%@ Person not in Photos DB (should be according to bookmark %@)"
- "%@ Person not in Photos DB (should be according to bookmark) from bookmark %@ to bookmark %@"
- "%@ Photos post-capture processing"
- "%@ Preset client prompt: %.100s ..."
- "%@ ProcessingOverlay"
- "%@ Returning preset client prompt with locale %@: %.100s ..."
- "%@ Returning preset client prompt: %.100s ..."
- "%@ SkipPCCRequest"
- "%@ Unexpected person update with %lu VU, %lu PhotosDB from bookmark %@ to bookmark %@"
- "%@ UseHistogramHistoryFromDisk"
- "%@ Will merge person %@(%@)(VerifyType-%ld) to person %@(%@)(VerifyType-%ld)"
- "%@ _fragmentSequenceRange={%lu, %lu}, sequenceNumbers=%@"
- "%@ _fragmentTimeRange={start %.2fs, duration %.2fs}, fragments=%@"
- "%@ changeBookmark changed from query %@ to store %@"
- "%@ failed to encode changeBookmark %@"
- "%@ failed to encode currentChangeBookmark %@"
- "%@ failed to encode previousChangeBookmark %@"
- "%@ missing observation: %@"
- "%@: %@"
- "%@[3P] Failed to save avatar to %@"
- "%@[3P] Saved avatar to %@"
- "%@[SkipPCCRequest]   type=%u text=%@"
- "%@[SkipPCCRequest] Could not find previous clip %@ in previousAnalysis; falling back to fresh stub"
- "%@[SkipPCCRequest] Returning fresh stub clip"
- "%@[SkipPCCRequest] Returning stub clip=%@ embeddings=%lu captions:"
- "%@[SkipPCCRequest] Reusing previous clip %@ (embeddings=%lu, captions=%lu) for dedup"
- "%@[UseHistogramHistoryFromDisk] Failed to unarchive previous clip: %@"
- "%@[UseHistogramHistoryFromDisk] Loaded previous clip result (id=%@, histogramTypes=%lu) from %@"
- "%@[UseHistogramHistoryFromDisk] No previous clip found at %@"
- "%lu %@"
- "%lu-day scheduling history (%lu records) for background activity %@:"
- "(Forced) "
- "--full-interval"
- "--help"
- "-> Sequence number %lu"
- "-f"
- "-h"
- "./Utilities/CGUtilities.h"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/Contacts/MADContactsPersonProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/Home/MADHomePersonProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFaceAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFaceFastPassProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosFullAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosOCRAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosPersonProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Background/MADPhotosVisualSearchAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/HomeKit/VCPHomeKitAnalysisServiceTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MADPreheatingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MADVUUtilities.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MADVectorDatabaseUtilities.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/MediaAnalysisDaemon.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Moments/MADMomentsDeferredProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADBiome.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADFullAnalysisResultsSynchronizationTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADFullAssetBatch.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADImageRichCaptionAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosBackupAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosBackupProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosDatabaseMigrationProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosLibraryRestoreTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosRestoreAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADPhotosTelemetryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADProgressManager.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADProgressReporterProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADRichCaptionLibraryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADTUAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADTULibraryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MADVideoRichCaptionAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/MediaAnalysisServiceTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/NSInputStream+VCPRestore.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/PHAssetResourceManager+InMemoryDownload.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/PHPhotoLibrary+MediaAnalysisDaemonAnalysisMigration.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPAssetAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBackgroundProcessingMetrics.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBackupEntryHeader.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBackupFileHeader.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPBatchAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPEditAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPEffectsAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFaceAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFaceLibraryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFaceProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPFailedAssetAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADFullAssetProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADOCRAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPECAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPECLibraryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPECSingleRequestProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotoAssetProcessingTask.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotosFetchProcessingTask.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotosLibraryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADPhotosProcessingTask.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADQuickFaceIDAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADSceneAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADSceneLibraryProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMADVisualSearchAssetBatch.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPMediaTypeAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPausedAnalysis.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosAssetChangeManager.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosAssetProcessingTask.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosCaptureProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosCoreAnalytics.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosFaceIdentificationTask.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPPhotosMaintenanceProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPRestoreDatabaseTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPResumePausedAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPSystemMonitor.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Photos/VCPUnifiedFullAnalysisTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Spotlight/MADSpotlightImageProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/Spotlight/MADSpotlightMovieProcessingTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Daemon/VCPCompoundMADTask.mm"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MediaAnalysis/Service/VCPMADRemoteActivityTask.mm"
- "3P_%@_%@.jpg"
- "Add MAD_WATCHDOG_CRASH_CALLBACK_METHOD to your class - %@"
- "AllowStreaming"
- "AutoCounter "
- "Biome appears to be hung. Reported: %s. Began operation at %@"
- "BlurExposureRotationConcurrentQueueCount"
- "BypassMaxFragmentDuration"
- "Caller provided customized system prompt ..."
- "CaptionFrameCount"
- "CaptionFrameCount = %d (set by user)"
- "CaptionOverride"
- "Compilation of the text encoder. Reported: %s. Began operation at %@"
- "Compilation of the visual encoder. Reported: %s. Began operation at %@"
- "ConcurrentAssetCountFullImage"
- "ConcurrentAssetCountFullLivePhoto"
- "ConcurrentAssetCountFullVideo"
- "ConcurrentFaceAnalysis"
- "ConcurrentPreAnalysis"
- "ConsecutiveEmbeddingThreshold use %@"
- "DAS cancellation %s via default"
- "Daemon appears to be hung (%@); self-terminating"
- "DecodeTargetMaxResolution"
- "DisablePersonChangeBatching"
- "DisablePhotosPostCaptureProcessing"
- "Disabling"
- "Dlib appears to be hung. Began operation at %@"
- "DownloadLLMJpegs"
- "DownloadUnsafeCaptions"
- "EnablePerFrameHomeKitAnalysis"
- "EnableRemoteActivity"
- "Enabling"
- "Error: This option is currently unsupported."
- "FaceAnalysisConcurrentQueueCount"
- "FaceClustering "
- "FaceCropProcessing "
- "FaceDetection "
- "FaceProcessingConcurrentQueueCount"
- "FaceStagingConcurrency"
- "ForceInitialScanNoResource"
- "FrequentProgressReporting"
- "HKSVCustomPrompt"
- "HKSVPromptOverwrite"
- "IgnoreDASCancellation"
- "ImageRichCaptionBypassGating"
- "ImageRichCaptionMaxWordCound"
- "JITCameraFaceOnly"
- "Latest Watchdog petting at %s[%d]"
- "Long movie download timeout set to %0.2f via default"
- "LongMovieDownloadTimeout"
- "MADSave3PContactAvatars"
- "MAD_PET_SHARED_WATCHDOG_WITH_CALLBACK object deallocated - %@"
- "Maintenance"
- "Model initialization appears to be hung. Reported: %s. Began preheat at %@"
- "MomentsGracePeriod"
- "MomentsPriority"
- "No activity"
- "No scheduling history for background activity %@ in database"
- "NoResultStrip"
- "ParseConcurrentAssetCount"
- "Per client scheduled request limit set to %d"
- "PerClientScheduledRequestLimit"
- "Persist full-range signals %@"
- "PersistFullRangeSignals"
- "Person promoting appears to be hung. Reported: %s. Began operation at %@"
- "PersonBuilding "
- "PersonPromoting "
- "Photos appears to be hung. Reported: %s. Began operation at %@"
- "ProcessCapturedFace"
- "ProcessingOverlay"
- "QuickFaceID "
- "Remote DAS activity %s via default"
- "RichCaptionCapRatioImage"
- "RichCaptionCapRatioVideo"
- "SceneNetConcurrentQueueCount"
- "SceneProcessing "
- "Sensitive content"
- "Set ImageRichCaptionBypassGating to %d"
- "Set ImageRichCaptionMaxWordCound to %lu"
- "Set RichCaptionCapRatioImage to %f"
- "Set RichCaptionCapRatioVideo to %f"
- "Set VideoRichCaptionBypassGating to %d"
- "Set VideoRichCaptionMaxWordCound to %lu"
- "SkipPCCRequest"
- "TextUnderstanding appears to be hung. Reported: %s. Began operation at %@"
- "Unknown option \"%@\" specified"
- "Unknown priority %@, default to Maintenance"
- "UseHistogramHistoryFromDisk"
- "UseProModel"
- "Utility"
- "VideoRichCaptionBypassGating"
- "VideoRichCaptionMaxWordCound"
- "Watchdog Timeout"
- "Watchdog disabled"
- "WatchdogTimeoutSeconds"
- "[%@] Concurrent asset count set via defaults (%d)"
- "[%@][PhotosCapture] Persisting matching face %@ with person %@"
- "[%@][PhotosCapture] Persisting unrecognized face %@"
- "[CoreAnalyticManager] %@ %@ days with since Version %llu created %@"
- "[CoreAnalyticManager] %@ invalid taskID %lu (%@); ignore"
- "[CoreAnalyticManager] %@: invalid allowed assets count %lu; ignore"
- "[CoreAnalyticManager] %@: invalid progress %lu%%; ignore"
- "[FaceCrop] Processed %lu facecrop for person %@"
- "[FaceLibraryProcessing] Running with: "
- "[GalleryUpdate] Person change batching %s via default"
- "[GenerativeProcessing][Prompt]"
- "[LOG_ERROR] %s[%d]: code %d\n"
- "[Perf] Memory usage before running the first task: %@"
- "[Perf] Memory usage on finishing all scheduled tasks: %@"
- "[Perf] Memory usage: %@"
- "[QuickFaceID][%@] Persisting matching face %@ with person %@"
- "[QuickFaceID][%@] Persisting unrecognized face %@"
- "[Scene] Defaults to fail initial scan with no resource"
- "[SkipPCCRequest] stub caption - %@"
- "[UserDefaults] UseProModel: %@"
- "[VisualSearch] Concurrent asset count set via default (%d)"
- "_handleSkipPCCRequestWithHistogramHistory:logPrefix:"
- "_loadPreviousClipFromDiskWithLogPrefix:"
- "_memoryUsageMonitor"
- "base64EncodedStringWithOptions:"
- "captureCrashWithKnownTimeoutRisk:"
- "currentTimeoutRiskAndStartTime:"
- "dataWithContentsOfFile:"
- "disabled"
- "dumpBreadcrumps"
- "faceTorsoprint"
- "invocationWithMethodSignature:"
- "invoke"
- "methodSignatureForSelector:"
- "parseCommandLine:argv:"
- "printUsageAndExitWith:andMessage:"
- "setArgument:atIndex:"
- "setSelector:"
- "setTarget:"
- "stringByAppendingFormat:"
- "stringWithCString:encoding:"
- "timeoutCrashWithMessage:"
- "unarchivedObjectOfClasses:fromData:error:"
- "unsignedLongValue"
- "v24@?0@\"NSUUID\"8^B16"
- "v24@?0@\"VUWGalleryEntityIdentifier\"8^B16"
- "v24@?0@8^B16"
- "v28@0:8i16r^*20"
- "v32@?0@\"HMIVideoAnalyzerFragmentResult\"8Q16^B24"
- "v32@?0@\"NSNumber\"8@\"NSMutableSet\"16^B24"
```
