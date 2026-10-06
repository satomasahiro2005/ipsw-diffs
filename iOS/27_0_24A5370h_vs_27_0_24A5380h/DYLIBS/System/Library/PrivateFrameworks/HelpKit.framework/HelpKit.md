## HelpKit

> `/System/Library/PrivateFrameworks/HelpKit.framework/HelpKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ab28` | `0x2c478` | **`+0x1950`** |
| `__AUTH_CONST.__objc_const` | `0x5148` | `0x5658` | **`+0x510`** |
| `__TEXT.__objc_methlist` | `0x3534` | `0x383c` | **`+0x308`** |
| `__AUTH_CONST.__cfstring` | `0x2b20` | `0x2e20` | **`+0x300`** |
| `__DATA_CONST.__objc_selrefs` | `0x25b8` | `0x2788` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x1bcf` | `0x1d1f` | **`+0x150`** |
| `__AUTH.__objc_data` | `0xe08` | `0xef8` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0xb50` | `0xbc0` | **`+0x70`** |
| `__DATA.__objc_ivar` | `0x3f8` | `0x43c` | **`+0x44`** |
| `__DATA_CONST.__got` | `0x540` | `0x578` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xef8` | `0xf18` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0x110` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xae4` | `0xb00` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x160` | **`+0x18`** |

### Other Changes

```diff

-204.0.0.0.0
+205.0.0.0.0

-  Functions: 1202
-  Symbols:   2248
-  CStrings:  442
+  Functions: 1262
+  Symbols:   2356
+  CStrings:  466
Symbols:
+ +[HLPAnalyticsEventLinkUsed eventWithDestinationURL:linkType:topicID:]
+ +[HLPAnalyticsEventSession eventWithBooksViewed:numSearches:sessionDuration:timeActive:topicsViewed:]
+ -[HLPAnalyticsEventController activeSession]
+ -[HLPAnalyticsEventController setActiveSession:]
+ -[HLPAnalyticsEventLinkUsed .cxx_destruct]
+ -[HLPAnalyticsEventLinkUsed _initWithDestinationURL:linkType:topicID:]
+ -[HLPAnalyticsEventLinkUsed caRepresentation]
+ -[HLPAnalyticsEventLinkUsed destinationURL]
+ -[HLPAnalyticsEventLinkUsed eventName]
+ -[HLPAnalyticsEventLinkUsed linkType]
+ -[HLPAnalyticsEventLinkUsed setDestinationURL:]
+ -[HLPAnalyticsEventLinkUsed setLinkType:]
+ -[HLPAnalyticsEventLinkUsed setTopicID:]
+ -[HLPAnalyticsEventLinkUsed topicID]
+ -[HLPAnalyticsEventSearchUsed log]
+ -[HLPAnalyticsEventSession _initWithBooksViewed:numSearches:sessionDuration:timeActive:topicsViewed:]
+ -[HLPAnalyticsEventSession booksViewed]
+ -[HLPAnalyticsEventSession caRepresentation]
+ -[HLPAnalyticsEventSession eventName]
+ -[HLPAnalyticsEventSession numSearches]
+ -[HLPAnalyticsEventSession sessionDuration]
+ -[HLPAnalyticsEventSession setBooksViewed:]
+ -[HLPAnalyticsEventSession setNumSearches:]
+ -[HLPAnalyticsEventSession setSessionDuration:]
+ -[HLPAnalyticsEventSession setTimeActive:]
+ -[HLPAnalyticsEventSession setTopicsViewed:]
+ -[HLPAnalyticsEventSession timeActive]
+ -[HLPAnalyticsEventSession topicsViewed]
+ -[HLPAnalyticsSession .cxx_destruct]
+ -[HLPAnalyticsSession accumulatedActiveTime]
+ -[HLPAnalyticsSession booksViewed]
+ -[HLPAnalyticsSession clearPersistedSnapshot]
+ -[HLPAnalyticsSession didBecomeActive]
+ -[HLPAnalyticsSession didResignActive]
+ -[HLPAnalyticsSession end]
+ -[HLPAnalyticsSession init]
+ -[HLPAnalyticsSession lastActiveDate]
+ -[HLPAnalyticsSession numSearches]
+ -[HLPAnalyticsSession persistSnapshot]
+ -[HLPAnalyticsSession persistenceKey]
+ -[HLPAnalyticsSession restoreSnapshotIfNeeded]
+ -[HLPAnalyticsSession sessionID]
+ -[HLPAnalyticsSession sessionStartDate]
+ -[HLPAnalyticsSession setAccumulatedActiveTime:]
+ -[HLPAnalyticsSession setBooksViewed:]
+ -[HLPAnalyticsSession setLastActiveDate:]
+ -[HLPAnalyticsSession setNumSearches:]
+ -[HLPAnalyticsSession setSessionID:]
+ -[HLPAnalyticsSession setSessionStartDate:]
+ -[HLPAnalyticsSession setViewedTopicIDs:]
+ -[HLPAnalyticsSession start]
+ -[HLPAnalyticsSession trackBookViewed]
+ -[HLPAnalyticsSession trackSearchUsed]
+ -[HLPAnalyticsSession trackTopicViewed:]
+ -[HLPAnalyticsSession viewedTopicIDs]
+ -[HLPHelpTopicViewController linkTypeForURL:]
+ -[HLPHelpViewController _sceneDidActivate:]
+ -[HLPHelpViewController _sceneWillDeactivate:]
+ -[HLPHelpViewController analyticsSession]
+ -[HLPHelpViewController setAnalyticsSession:]
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table70
+ _HLPAnalyticsLinkTypeAside
+ _HLPAnalyticsLinkTypeOpenIt
+ _HLPAnalyticsLinkTypeTask
+ _HLPAnalyticsLinkTypeTopic
+ _OBJC_CLASS_$_HLPAnalyticsEventLinkUsed
+ _OBJC_CLASS_$_HLPAnalyticsEventSession
+ _OBJC_CLASS_$_HLPAnalyticsSession
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_IVAR_$_HLPAnalyticsEventController._activeSession
+ _OBJC_IVAR_$_HLPAnalyticsEventLinkUsed._destinationURL
+ _OBJC_IVAR_$_HLPAnalyticsEventLinkUsed._linkType
+ _OBJC_IVAR_$_HLPAnalyticsEventLinkUsed._topicID
+ _OBJC_IVAR_$_HLPAnalyticsEventSession._booksViewed
+ _OBJC_IVAR_$_HLPAnalyticsEventSession._numSearches
+ _OBJC_IVAR_$_HLPAnalyticsEventSession._sessionDuration
+ _OBJC_IVAR_$_HLPAnalyticsEventSession._timeActive
+ _OBJC_IVAR_$_HLPAnalyticsEventSession._topicsViewed
+ _OBJC_IVAR_$_HLPAnalyticsSession._accumulatedActiveTime
+ _OBJC_IVAR_$_HLPAnalyticsSession._booksViewed
+ _OBJC_IVAR_$_HLPAnalyticsSession._lastActiveDate
+ _OBJC_IVAR_$_HLPAnalyticsSession._numSearches
+ _OBJC_IVAR_$_HLPAnalyticsSession._sessionID
+ _OBJC_IVAR_$_HLPAnalyticsSession._sessionStartDate
+ _OBJC_IVAR_$_HLPAnalyticsSession._viewedTopicIDs
+ _OBJC_IVAR_$_HLPHelpViewController._analyticsSession
+ _OBJC_METACLASS_$_HLPAnalyticsEventLinkUsed
+ _OBJC_METACLASS_$_HLPAnalyticsEventSession
+ _OBJC_METACLASS_$_HLPAnalyticsSession
+ _UISceneDidActivateNotification
+ _UISceneWillDeactivateNotification
+ __OBJC_$_CLASS_METHODS_HLPAnalyticsEventLinkUsed
+ __OBJC_$_CLASS_METHODS_HLPAnalyticsEventSession
+ __OBJC_$_INSTANCE_METHODS_HLPAnalyticsEventLinkUsed
+ __OBJC_$_INSTANCE_METHODS_HLPAnalyticsEventSession
+ __OBJC_$_INSTANCE_METHODS_HLPAnalyticsSession
+ __OBJC_$_INSTANCE_VARIABLES_HLPAnalyticsEventLinkUsed
+ __OBJC_$_INSTANCE_VARIABLES_HLPAnalyticsEventSession
+ __OBJC_$_INSTANCE_VARIABLES_HLPAnalyticsSession
+ __OBJC_$_PROP_LIST_HLPAnalyticsEventLinkUsed
+ __OBJC_$_PROP_LIST_HLPAnalyticsEventSession
+ __OBJC_$_PROP_LIST_HLPAnalyticsSession
+ __OBJC_CLASS_RO_$_HLPAnalyticsEventLinkUsed
+ __OBJC_CLASS_RO_$_HLPAnalyticsEventSession
+ __OBJC_CLASS_RO_$_HLPAnalyticsSession
+ __OBJC_METACLASS_RO_$_HLPAnalyticsEventLinkUsed
+ __OBJC_METACLASS_RO_$_HLPAnalyticsEventSession
+ __OBJC_METACLASS_RO_$_HLPAnalyticsSession
- GCC_except_table53
- GCC_except_table58
- GCC_except_table68
CStrings:
+ "HLPAnalyticsSession-"
+ "accumulatedActiveTime"
+ "booksViewed"
+ "books_viewed"
+ "destination_url"
+ "guide"
+ "help"
+ "link_type"
+ "link_used"
+ "numSearches"
+ "num_searches"
+ "open_it"
+ "persistedAt"
+ "session"
+ "sessionStartDate"
+ "session_duration"
+ "support.apple.com"
+ "time_active"
+ "topic_id"
+ "topics_viewed"
+ "viewedTopicIDs"
+ "x-apple-tips"
+ "x-apple.systempreferences"
+ "x-help-action"
```
