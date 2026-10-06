## iCalendar

> `/System/Library/PrivateFrameworks/iCalendar.framework/iCalendar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b30c` | `0x2b374` | **`+0x68`** |

### Other Changes

```diff

-1177.0.0.0.0
+1178.0.0.0.0
Functions:
~ -[NSData(VCSEncodings) VCSDecodeBase64] : 924 -> 908
~ -[NSData(VCSEncodings) VCSConvert8bitBufferToUTF8From:] : 288 -> 304
~ -[NSData(VCSEncodings) VCSDecodeQuotedPrintableForText:] : 476 -> 460
~ -[ICSComponent validate:] : 268 -> 264
~ -[ICSComponent ICSStringWithOptions:appendingToString:] : 1708 -> 1704
~ -[ICSComponent(Private) setExrule:] : 356 -> 352
~ -[ICSComponent(Private) exrule] : 348 -> 344
~ -[ICSComponent(Private) setRrule:] : 356 -> 352
~ -[ICSComponent(Private) rrule] : 348 -> 344
~ +[ICSTimeZone(TimeZoneGeneration) blocksAfterDate:untilDate:forTimeZone:] : 4440 -> 4436
~ -[ICSTimeZone(TimeZoneGeneration) initWithSystemTimeZone:] : 524 -> 520
~ -[ICSTimeZone(TimeZoneGeneration) initWithTimeZone:fromDate:options:] : 412 -> 408
~ -[ICSTimeZone(TimeZoneGeneration) relevantTimeZoneBlocks:fromDate:options:] : 928 -> 920
~ -[ICSTimeZone(TimeZoneGeneration) lastTransitionDatesInBlocks:] : 1072 -> 1068
~ -[ICSTimeZone(TimeZoneGeneration) mostRecentTransitionDatesInBlocks:lastTransitionDates:onOrBeforeDate:] : 560 -> 548
~ -[ICSTimeZone(TimeZoneGeneration) mostRecentTransitionDateFromRDateOf:onOrBeforeDate:] : 404 -> 400
~ +[ICSCalendar(Debug) calendarWithKnownTimeZones] : 368 -> 364
~ -[ICSCalendar _addTimeZonesInComponent:toSet:] : 744 -> 736
~ -[ICSCalendar _addTimeZonesInComponent:toDictionary:] : 816 -> 808
~ -[ICSCalendar _timeZonesForComponents:options:] : 844 -> 836
~ -[ICSCalendar setComponents:options:] : 484 -> 480
~ +[VCSParser endVCSEntity:withParseState:] : 1200 -> 1196
~ -[ICSCalendar(RepairProperties) fixPropertiesInheritance] : 432 -> 428
~ -[ICSCalendar(RepairProperties) fixEntities] : 252 -> 248
~ -[ICSComponent(RepairPropertiesPrivate) fixPropertiesInheritance:] : 436 -> 432
~ -[ICSComponent(RepairPropertiesPrivate) fixAlarms] : 780 -> 776
~ -[ICSComponent(RepairPropertiesPrivate) fixRelatedTo] : 544 -> 540
~ -[ICSComponent(RepairPropertiesPrivate) fixAttachments] : 412 -> 408
~ -[ICSComponent(RepairPropertiesPrivate) fixRecurrenceRules] : 444 -> 440
~ -[ICSComponent(RepairPropertiesPrivate) fixRecurrenceDates] : 420 -> 416
~ -[ICSComponent(RepairPropertiesPrivate) fixExceptionRules] : 444 -> 440
~ -[ICSComponent(RepairPropertiesPrivate) fixExceptionDates] : 420 -> 416
~ -[ICSEvent(RepairPropertiesPrivate) fixComponent] : 1424 -> 1420
~ -[ICSPushbackStream peek] : 184 -> 180
~ -[ICSPushbackStream read] : 112 -> 108
~ -[ICSEvent isDefaultAlarmDeleted] : 344 -> 340
~ -[ICSUserAddress sanitizeAddressString:] : 420 -> 416
~ -[NSArray(ICSWriter) _ICSStringsForPropertyValuesWithOptions:appendingToString:] : 332 -> 328
~ -[ICSProperty(ICSWriter) _ICSStringWithOptions:appendingToString:additionalParameters:] : 1380 -> 1376
~ -[NSArray(VCSUtilities) VCS_map:] : 408 -> 404
~ -[NSString(VCSUtilities) VCS_uncommentedAddress] : 736 -> 744
~ -[NSString(VCSUtilities) VCS_isPhoneNumber] : 444 -> 440
~ -[ICSDocument validateParsedCalendar:] : 740 -> 732
~ +[ICSDuration(iCalendarImport) durationFromRFC2445UTF8String:] : 648 -> 652
~ -[ICSParser createPropertyType:component:withName:fatalError:] : 3528 -> 3512
~ +[ICSParser entitiesFromNSData:options:] : 856 -> 852
~ _ICSRedactBytes : 360 -> 384
~ __pictureForByte : 28 -> 52
~ _ICSAppendEmoji : 168 -> 180
~ -[ICSTimeZoneBlock setRrule:] : 356 -> 352
~ -[ICSTimeZoneBlock rrule] : 332 -> 328
~ -[ICSTimeZoneBlock tzname] : 332 -> 328
~ -[ICSTimeZoneBlock setTzname:] : 356 -> 352
~ -[ICSTimeZone(Internal) getNSTimeZoneFromDate:toDate:] : 1980 -> 1972
~ -[ICSTimeZone(ICSTranslation) computeTimeZoneChangeListFromDate:toDate:] : 1388 -> 1376
~ -[ICSTimeZoneBlock(ICSTranslation) computeTimeZoneChangeListFromDate:toDate:] : 1292 -> 1284
~ -[VCSEvent ensureDurationAlarms] : 280 -> 276
~ -[ICSLazyDigestUIDGenerator _digest] : 272 -> 268
~ +[ICSAlternateTimeProposal _parseICSString:] : 460 -> 456
~ -[VCSRecurrenceRule initWithString:] : 572 -> 588
~ -[VCSRecurrenceRule decodeWeekly:] : 112 -> 120
~ -[VCSRecurrenceRule decodeMonthlyByPos:] : 172 -> 188
~ -[VCSRecurrenceRule decodeMonthlyByDay:] : 128 -> 136
~ -[VCSRecurrenceRule decodeYearlyByMonth:] : 128 -> 136
~ -[VCSRecurrenceRule decodeYearlyByDay:] : 128 -> 136
~ -[VCSRecurrenceRule decodeWeekdayList:] : 308 -> 304
~ _ICSDecodeBase64 : 456 -> 452
~ _ICSEncodeBase64 : 480 -> 492
~ -[VCSParserInputStream loadLineBuffer] : 216 -> 208
~ +[VCSDate dateListFromData:] : 408 -> 412
~ -[VCSParsedLine loadFromCString:withParseState:] : 1300 -> 1324
~ -[ICSProperty(ICSiCalConversions) setValueAsProperty:withRawValue:options:] : 2660 -> 2644
~ -[ICSRecurrenceRule(Internal) occurrencesForStartDate:fromDate:toDate:inTimeZone:] : 2540 -> 2532
~ +[ICSRecurrenceRule(Internal) recurrenceRuleFromICSCString:withTokenizer:] : 4084 -> 4336
~ -[VCSPropertyValue dictify] : 524 -> 520
~ -[VCSProperty initKeywordListProperty:withParseState:property:] : 316 -> 320
~ -[ICSTokenizer consumeParamValue] : 976 -> 968
```
