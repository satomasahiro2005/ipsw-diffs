## FlowToolsSnippetService

> `/System/Library/PrivateFrameworks/FlowToolsSnippetService.framework/FlowToolsSnippetService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf82d0` | `0x107798` | **`+0xf4c8`** |
| `__TEXT.__oslogstring` | `0x6146` | `0x6bb6` | **`+0xa70`** |
| `__AUTH_CONST.__const` | `0xa830` | `0xafd8` | **`+0x7a8`** |
| `__TEXT.__unwind_info` | `0x3ee0` | `0x4338` | **`+0x458`** |
| `__TEXT.__const` | `0xdb06` | `0xde96` | **`+0x390`** |
| `__DATA.__bss` | `0x10780` | `0x109e0` | **`+0x260`** |
| `__TEXT.__eh_frame` | `0x7704` | `0x7960` | **`+0x25c`** |
| `__AUTH.__data` | `0x308` | `0x4d0` | **`+0x1c8`** |
| `__TEXT.__constg_swiftt` | `0x2348` | `0x24fc` | **`+0x1b4`** |
| `__TEXT.__swift5_fieldmd` | `0x28b8` | `0x2a40` | **`+0x188`** |
| `__TEXT.__swift5_capture` | `0x1950` | `0x1a7c` | **`+0x12c`** |
| `__TEXT.__swift5_typeref` | `0x3519` | `0x3613` | **`+0xfa`** |
| `__AUTH_CONST.__auth_got` | `0x1ad0` | `0x1bb8` | **`+0xe8`** |
| `__TEXT.__swift5_reflstr` | `0x1516` | `0x15d6` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x1660` | `0x1718` | **`+0xb8`** |
| `__DATA.__data` | `0xf78` | `0x1030` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x848` | `0x890` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1fed` | `0x202d` | **`+0x40`** |
| `__DATA.__common` | `0x58` | `0x80` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x380` | `0x3a8` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x7110` | `0x70f0` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x3ec` | `0x408` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0x2278` | `0x2290` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xb8c` | `0xba0` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x230` | `0x240` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x368` | `0x374` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x3a0` | `0x3ac` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-3600.65.26.1.1
+3600.65.34.0.0

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

-  Functions: 7036
-  Symbols:   343
-  CStrings:  493
+  Functions: 7297
+  Symbols:   358
+  CStrings:  528
Symbols:
+ _CGImageDestinationAddImage
+ _CGImageDestinationCreateWithData
+ _CGImageDestinationFinalize
+ _CGImageSourceCreateThumbnailAtIndex
+ _CGImageSourceCreateWithURL
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_CLASS_$_PHObject
+ _OBJC_CLASS_$_RFSummaryItemPairCardSection
+ _kCGImageSourceCreateThumbnailFromImageAlways
+ _kCGImageSourceCreateThumbnailWithTransform
+ _kCGImageSourceThumbnailMaxPixelSize
+ _objc_retain_x22
+ _objc_retain_x25
+ _swift_getOpaqueTypeConformance2
CStrings:
+ " Entity is not a PhotoCollectionEntity, AlbumEntity, or GeneratedImageEntity, unsupported"
+ "#EntityOpener: ApplicationEntity → needsAppLaunch bundleId=%s"
+ "#EntityOpener: Tier 1 (system OpenIntent) resolved tool=%s"
+ "#EntityOpener: Tier 2 (%s) resolved tool=%s"
+ "#EntityOpener: Tier 3 (.openEntity) resolved tool=%s"
+ "#EntityOpener: executed tool=%s"
+ "#EntityOpener: execution failed tool=%s domain=%s code=%ld"
+ "#EntityOpener: no open tool for type; Tier 4 needsAppLaunch bundleId=%s"
+ "#EntityOpener: no open tool resolved for type=%s"
+ "#EntityOpener: no tier resolved and no launchable bundle; noOp"
+ "<key_entity id=\\\"[^\\\"]*\\\"\\/>"
+ "AppEntitySnippetHelper: collectionEntitySnippetModel supportsEntitySnippet returned nil, defaulting to .remote"
+ "AppEntitySnippetHelper: createEntitySnippetModel failed — cannot extract member identifier from value"
+ "AppEntitySnippetHelper: createEntitySnippetModel — supportsEntitySnippet returned nil for typeIdentifier=%s bundleIdentifier=%s"
+ "ApplicationEntity"
+ "Creating fallback pluginModel for DisplayRepresentation"
+ "DefaultPhotosHandler: GeneratedImageEntity missing identifier"
+ "DefaultPhotosHandler: makeGeneratedImagesDisplayItem failed to encode photos model"
+ "DefaultPhotosHandler: makePhotosDisplayItem entitySnippetModel=%s"
+ "DisplayRepresentation already contains pluginModel skipping creating decorated fallback"
+ "GeneratedImageEntity"
+ "NavigateToDeviceIntent"
+ "NavigateToHomeIntent"
+ "NavigateToRoomIntent"
+ "OpenMediaAlbumIntent"
+ "OpenReadingListItemIntent"
+ "PhotoCitationCard: failed to encode photos model for %ld photo(s)"
+ "SnippetServicePhotosModel: failed to open custom library container=%s; falling back to system/syndication"
+ "SnippetServicePhotosModel: resolved render identifiers resolved=%ld unresolved=%ld container=%s"
+ "StreamingHandler: enrichUpdate detected Live Activity for entity tag=%{sensitive}s responseId=%{sensitive}s"
+ "StreamingHandler: enrichUpdateWithArtifactFileTags appended <file> tag for entity tag=%{sensitive}s responseId=%{sensitive}s"
+ "StreamingHandler: handleStartStage stripped entity data from start chunk plugin model"
+ "StreamingHandler: updateOutput folded liveActivityAddViewsCount=%ld into stream chunk for Live Activity suppression responseId=%{sensitive}s"
+ "StreamingHandler: updateOutput propagating applicationSessionID=%s responseViewId=%s to manifest for Live Activity suppression responseId=%{sensitive}s"
+ "Yielded attribution view added (addViews) responseId=%{sensitive}s"
+ "Yielded attribution view added (streaming) responseId=%{sensitive}s"
+ "YieldedAttributionViewHelper: created yielded attribution view responseId=%{sensitive}s"
+ "YieldedAttributionViewHelper: not yielded, skipping responseId=%{sensitive}s"
+ "YieldedAttributionViewHelper: unable to create snippet data from model responseId=%{sensitive}s"
+ "[SnippetHidden] SnippetPluginWrapperModel → %{bool,public}d (delegated to SnippetServiceUIPluginModel)"
+ "[SnippetHidden] SnippetPluginWrapperModel → true (unknown bundle=%{public}s)"
+ "[SnippetHidden] inform.snippetHidden → %{bool,public}d (inner case=%{public}s)"
+ "[SnippetHidden] inform.snippetHidden → %{bool,public}d (sfCardItem)"
+ "[SnippetHidden] sfCard hidden: 2 card sections but trailing is '%s', expected RFReferenceCenteredCardSection"
+ "[SnippetHidden] sfCard hidden: card section type '%s' not in allowed list"
+ "[SnippetHidden] sfCard hidden: combined card section has %ld subsections (max 2)"
+ "[SnippetHidden] sfCard hidden: combined subsection type '%s' not in allowed list"
+ "[SnippetHidden] sfCard hidden: expected 1-2 card sections, found %ld"
+ "[SnippetHidden] sfCard hidden: expected at least 1 card section, found %ld"
+ "[SnippetHidden] sfCard hidden: failed to decode SFCard data"
+ "[SnippetHidden] sfCard hidden: resultIdentifier does not match allowed prefixes"
+ "[SnippetHidden] sfCard showing: section type '%s' passed all checks"
+ "[SnippetHidden] → %{bool,public}d (inform on car, itemCount=%ld)"
+ "[SnippetHidden] → %{bool,public}d (sfCard on car)"
+ "[SnippetHidden] → true (case=%{public}s on car)"
+ "[SnippetHidden] → true (markdown on car — not renderable)"
+ "com.apple.GenerativePlayground"
+ "com.apple.GenerativePlaygroundApp"
+ "createItem(_:bundleIdentifier:entityIdentifier:entityType:openAction:entityURL:)"
+ "createItem(_:identifier:type:bundleIdentifierOverride:openAction:entityURL:)"
+ "createItem: image file attachment, using .image item type"
+ "entitySnippet(for:) matched .photos entitySnippetModel=%s"
+ "entitySnippet(for:) multi-item inform (count=%ld) contained no entity snippet"
+ "entitySnippet(for:) multi-item inform contained more than one entity snippet — using first"
+ "entityURL"
+ "isPhotoSources"
+ "messageImageAttachmentRow: showing photo thumbnail on the message row"
+ "yielded_attribution"
- " AppEntity snippet is enabled, deferring to entity snippet rendering"
- " AppEntity snippet location is .remote, deferring to entity snippet rendering"
- " Entity is neither a PhotoCollectionEntity nor an AlbumEntity, unsupported"
- "AppEntitySnippetHelper: Begin create EntitySnippet featureFlag.siriCompanion enabled=%{bool}d"
- "AppEntitySnippetHelper: Entity does not provide an EntitySnippet"
- "AppEntitySnippetHelper: Entity does not provide an EntitySnippet; skipping collection snippet"
- "AppEntitySnippetHelper: EntitySnippet supported location=%s"
- "AppEntitySnippetHelper: Failed to find EntitySnippet (cannot extract member identifier from value)"
- "DefaultHandler: returning undisplayed entity output undisplayedCount=%ld responseId=%{sensitive}s"
- "SharedAlbumEntity"
- "[SnippetHidden] %s allowing 2 card sections: trailing is RFReferenceCenteredCardSection"
- "[SnippetHidden] %s hidden: 2 card sections but trailing is '%s', expected RFReferenceCenteredCardSection"
- "[SnippetHidden] %s hidden: card section type '%s' not in allowed list"
- "[SnippetHidden] %s hidden: combined card section has %ld subsections (max 2)"
- "[SnippetHidden] %s hidden: combined subsection type '%s' not in allowed list"
- "[SnippetHidden] %s hidden: expected 1-2 card sections, found %ld"
- "[SnippetHidden] %s hidden: expected at least 1 card section, found %ld"
- "[SnippetHidden] %s hidden: failed to decode SFCard data"
- "[SnippetHidden] %s hidden: model is not .sfCard"
- "[SnippetHidden] %s hidden: resultIdentifier does not match allowed prefixes"
- "[SnippetHidden] %s showing: section type '%s' passed all checks"
- "[SnippetHidden] inform.snippetHidden → %{bool,public}d (SnippetServiceUIPlugin model)"
- "[SnippetHidden] → %{bool,public}d (inform on car, delegated to inform model)"
- "[SnippetHidden] → false (idiom: %{public}s, not car)"
- "[SnippetHidden] → true (unsupported model case on car)"
- "arrow.uturn.right"
- "carPlaySnippetHidden(for:)"
- "createItem(_:bundleIdentifier:entityIdentifier:entityType:openAction:)"
- "createItem(_:identifier:type:bundleIdentifierOverride:openAction:)"
- "createItem: Detected .png file, using .image item type"
- "explicitInvocation"
- "supportsAppEntitySnippet(_:systemResponse:)"
- "waitForRegistration(timeout:)"
```
