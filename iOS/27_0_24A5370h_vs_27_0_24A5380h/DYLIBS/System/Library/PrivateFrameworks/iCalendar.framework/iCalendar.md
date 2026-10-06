## iCalendar

> `/System/Library/PrivateFrameworks/iCalendar.framework/iCalendar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b374` | `0x2b218` | **`-0x15c`** |

### Other Changes

```text
Functions:
~ -[NSString(VCSUtilities) VCS_uncommentedAddress] : 744 -> 736
~ +[ICSDuration(iCalendarImport) durationFromRFC2445UTF8String:] : 652 -> 660
~ -[VCSRecurrenceRule initWithString:] : 588 -> 572
~ -[VCSRecurrenceRule decodeWeekly:] : 120 -> 108
~ -[VCSRecurrenceRule decodeMonthlyByPos:] : 188 -> 164
~ -[VCSRecurrenceRule decodeMonthlyByDay:] : 136 -> 124
~ -[VCSRecurrenceRule decodeYearlyByMonth:] : 136 -> 124
~ -[VCSRecurrenceRule decodeYearlyByDay:] : 136 -> 124
~ -[VCSRecurrenceRule decodeWeekdayList:] : 304 -> 312
~ _ICSEncodeBase64 : 492 -> 484
~ +[VCSDate dateListFromData:] : 412 -> 404
~ +[ICSRecurrenceRule(Internal) recurrenceRuleFromICSCString:withTokenizer:] : 4336 -> 4084
```
