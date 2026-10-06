## AudioTranscriptionAnalysis

> `/System/Library/PrivateFrameworks/AudioTranscriptionAnalysis.framework/AudioTranscriptionAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25b14` | `0x25abc` | **`-0x58`** |

### Other Changes

```text
Functions:
~ -[ATAServiceResourceCoordinator _cleanupStaleReservedSessions] : 772 -> 764
~ -[ATAServiceResourceCoordinator _finalizedSessionCountForServiceType:] : 280 -> 276
~ -[_ATATranscriptionClientList _startTranscriptionWhileDispatchedWithReply:] : 716 -> 712
~ -[_ATATranscriptionClientList _stopTranscriptionWhileDispatched] : 612 -> 608
~ -[_ATATranscriptionClientList _pauseTranscriptionWhileDispatched] : 448 -> 444
~ -[_ATATranscriptionClientList _resumeTranscriptionWhileDispatched] : 444 -> 440
~ -[_ATATranscriptionClientList backend:didProduceResult:] : 420 -> 416
~ -[_ATATranscriptionClientList backend:didFinishWithError:] : 396 -> 392
~ -[ATASpeechFrameworkWrapper findSpeechFrameworkPath] : 620 -> 616
~ -[ATATranscriptionConfiguration validateWithError:] : 1144 -> 1140
~ ___85-[_ATATranslationClientList _prefetchPreferredAudioFormatWithSourceLocale:fromClass:]_block_invoke_2 : 772 -> 768
~ -[_ATATranslationClientList _notifyClientsOfTranslationDidResumeWhileDispatched] : 336 -> 332
~ -[_ATATranslationClientList _notifyClientsOfTranslationDidPauseWhileDispatched] : 536 -> 532
~ -[_ATATranslationClientList _notifyClientsOfTranslatorStartWhileDispatchedWithError:] : 524 -> 520
~ -[_ATATranslationClientList _notifyClientsOfTranslationDidStopWhileDispatchedWithError:] : 360 -> 356
~ -[_ATATranslationClientList _transitionToInvalidatedWhileDispatchedAndStopTranslator:withError:] : 492 -> 488
~ ___61-[_ATATranslationClientList translator:producedSpeechResult:]_block_invoke : 588 -> 584
~ ___66-[_ATATranslationClientList translator:producedTranslationResult:]_block_invoke : 664 -> 660
~ ___77-[_ATATranslationClientList translator:willStartTranslatedAudioWithMetadata:]_block_invoke : 600 -> 596
~ ___67-[_ATATranslationClientList translator:didGenerateTranslatedAudio:]_block_invoke : 532 -> 528
~ ___64-[_ATATranslationClientList translatorDidFinishTranslatedAudio:]_block_invoke : 500 -> 496
~ -[ATASpeechTranslationWrapper findSpeechTranslationFrameworkPath] : 704 -> 700
~ -[ATASpeechTranslationWrapper verifyFrameworkClasses] : 324 -> 320
~ ___88-[ATATranslationClient _notifyCompletionHandlers:withSourceFormat:currentlyHoldingLock:]_block_invoke : 256 -> 252
~ -[AVAudioPCMBuffer(ATAAdditions) _ata_serializeBufferWithAllocator:format:] : 872 -> 876
~ +[AVAudioPCMBuffer(ATAAdditions) _ata_createAudioBufferListWithAllocator:serializedData:description:] : 624 -> 632
```
