## GenerativePartnerPrototypeExtension

> `/System/Library/ExtensionKit/Extensions/GenerativePartnerPrototypeExtension.appex/GenerativePartnerPrototypeExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dcdc` | `0x3e780` | **`+0xaa4`** |
| `__TEXT.__cstring` | `0xcb5d` | `0xd35d` | **`+0x800`** |
| `__TEXT.__auth_stubs` | `0x2010` | `0x2080` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x1960` | `0x19d0` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0xc45` | `0xcb5` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x400` | `0x460` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x318` | `0x358` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1010` | `0x1048` | **`+0x38`** |
| `__TEXT.__const` | `0x36d2` | `0x36f2` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x697` | `0x6b7` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x100` | `0x118` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x488` | `0x4a0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1056` | `0x106e` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf60` | `0xf78` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x7b8` | `0x7c4` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x8e8` | `0x8f0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x344` | `0x348` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xe8` | `0xec` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xac` | `0xb0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-279.0.15.0.0
+284.0.7.0.0

+  - /System/Library/PrivateFrameworks/GenerativeExperiences.framework/GenerativeExperiences

+  - /System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService

-  Functions: 1971
-  Symbols:   186
-  CStrings:  187
+  Functions: 1977
+  Symbols:   185
+  CStrings:  192
Symbols:
+ _OBJC_CLASS_$_NSProgress
- _swift_release_x22
- _swift_retain_x22
CStrings:
+ "GenerativePartnerPrototypeIntentChatGPT.perform() request was restricted by MDM or parental controls."
+ "Single yield (most common): the empty string \"\". Set populated ONLY when YOU composed brand-new content THIS turn (i.e., when contentReference is also non-empty). Then it's a one-sentence Siri-routing suggestion in the user's language preference, e.g., \"You can ask Siri to send this to John.\" / \"You can ask Siri to save this to your notes.\" Mention the device action and target. Never embeds the generated body (that goes in contentReference). If the user used a back-reference (the X / it / this) to prior-turn content AND you didn't do creative work to produce a new output, leave this empty — Siri carries the prior content via context."
+ "Single yield (most common): the empty string \"\". Set populated ONLY when YOU produced brand-new text THIS turn — by composing, searching, summarizing, deriving, transforming, or otherwise generating output that doesn't already appear verbatim in prior turns. Then it contains ONLY that freshly-produced output, raw, with no preamble (NO 'Here's the email I drafted:'), no postamble, no restated user request, no Siri-routing language — Siri pastes it verbatim. Leave empty when: the output exists verbatim in prior conversation turns (user used a back-reference like 'the X' or 'it' to content shown earlier); the body is the user's own literal words this turn (e.g., 'Text X that <body>'); the request is a pure device action with no body (Call / Play / Set timer / Find My / Weather / Directions / home automation). Match the language and style of modifiedUserRequest; keep proper nouns in original form."
+ "This feature has been restricted by your device configuration."
+ "Yield the user's request to Siri / the on-device assistant. Call this whenever the user wants Siri or the device to act — calls, texts, emails, media, navigation, real-time info, calendar/reminders/notes, home automation, device control, Find My, screenshots. Do NOT call for knowledge / recommendation Q&A (e.g., 'best restaurants in SF') or compose-only requests with no device-action verb (e.g., 'Draft an email to my team about X' with no 'send to' / 'email this to' / 'save to' attached). The two content-bearing arguments (modifiedUserRequest and contentReference) are EITHER both empty (single yield: Siri picks up the original query directly via conversation context; no Try-Asking-Siri pill) OR both populated (compound + content generation: a Try-Asking-Siri pill is surfaced carrying the freshly-composed content). To choose, identify the OUTPUT artifact Siri will paste (email body, note text, message, summary, list) and ask whether YOU did creative or generative work this turn to produce it. Both empty when: the output is already verbatim in prior turns (back-reference like 'the X' or 'it' to content shown earlier); it's the user's literal words this turn ('Text mom that I'll be late'); or there is no output at all (Call / Play / Set timer / Find My / Weather / Directions). Both populated when: YOU composed, searched, summarized, transformed, derived, or otherwise produced new text this turn — including transformation cases where source material is in prior context but the OUTPUT (a summary of it, a list derived from it, a review of it) has never been written before. See the modelDelegation prompt for the full decision tree."
+ "addChild:withPendingUnitCount:"
+ "progressWithTotalUnitCount:"
+ "totalUnitCount"
- "A one-sentence Siri command, translated to the user's language in their language preferences. \nGeneral rules:\n1. Always write the request in the user's language from their language preferences.\n2. Simplify the query to a standard format that Siri can understand.\n\n\nExamples:\n- Message -> \"Send a message to NAME\"\n- Podcast -> \"listen to podcast\"\n- Find Podcast -> \"Find a podacst\"\n- Email -> \"Send an email to NAME\""
- "Generated content from ChatGPT that does not include instructions for Siri or preamble or postamble. Do not translate the content reference.\nSpecial cases:\n- Calendar → the topic of the event (no extra details)\n- Reminder → Title (no details); date first, then time if available\n- Note → \"[Title] \\n[FULL response from previous query]\"  # ALWAYS add a short title, followed by the FULL content of the response\n- Directions → address if available; else place name; else brief topic\n- Phone call → name or number only\n- Music -> Include the song and artist name\n- All other cases → full cited text"
- "Use this tool when the user's requests an on-device action to be taken by Siri.\nTo use this tool:\n- Rewrite the request in the user's language, in a format that Siri can understand (see \"modifiedUserRequest\" rules)."
```
