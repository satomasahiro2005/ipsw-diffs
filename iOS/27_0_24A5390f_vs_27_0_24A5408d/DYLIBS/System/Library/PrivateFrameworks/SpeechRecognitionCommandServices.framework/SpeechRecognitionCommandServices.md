## SpeechRecognitionCommandServices

> `/System/Library/PrivateFrameworks/SpeechRecognitionCommandServices.framework/SpeechRecognitionCommandServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11adf8` | `0x11b130` | **`+0x338`** |
| `__TEXT.__cstring` | `0x266fc` | `0x267ec` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x1e668` | `0x1e6e8` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xad6` | `0xb16` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xb9c` | `0xbb4` | **`+0x18`** |
| `__TEXT.__const` | `0x79bb` | `0x79cb` | **`+0x10`** |

### Other Changes

```diff

-34.0.0.0.0
+35.0.0.0.0

-  CStrings:  3451
+  CStrings:  3458
Functions:
~ sub_2ac38a504 -> sub_2ac292504 : 25896 -> 25880
~ sub_2ac3971e0 -> sub_2ac29f1d0 : 71480 -> 72344
~ sub_2ac3dffa4 -> sub_2ac2e82f4 : 107056 -> 106972
~ sub_2ac406ab4 -> sub_2ac30edb0 : 736 -> 768
~ sub_2ac40b598 -> sub_2ac3138b4 : 1196 -> 1220
~ sub_2ac40ba44 -> sub_2ac313d78 : 208 -> 216
~ sub_2ac41e490 -> sub_2ac3267cc : 55656 -> 55652
CStrings:
+ "If multiple items have the same name, say the number next to the item you want to use. If you don’t want to choose a number, say any other command to continue."
+ "Insert [today’s] date"
+ "Open [the] Siri App"
+ "Open the dedicated Siri app."
+ "Show [the] Siri App"
+ "Show all the app’s windows."
+ "System.OpenSiriAIApplication"
+ "This command does nothing if the window doesn’t support full-screen mode."
+ "This command does nothing if the window doesn’t support zoom."
+ "To stop using the window in full-screen mode, say “{System.WindowExitFullScreen}”. To show the menu bar if it isn’t visible, say “{System.MenuBarShow}”."
+ "While recording, say a sequence of commands. To stop recording, say “{System.StopRecordingCommands}”. Once recording stops, you’ll be prompted to name and save your new command.\\nA recorded command is played back as quickly as possible, ignoring any pauses during the recording process. If during playback a recorded command cannot be completed, playback will be stopped and an error alert will be presented."
+ "While recording, say commands that generate gestures or touch the screen to generate gestures. To stop recording, say “{System.StopRecordingGesture}”. Once recording stops, you’ll be prompted to name and save your new command."
+ "openSiriAIApplication"
+ "preventDuringKeyboardDictation"
+ "requiresSiriAIEnabled"
- "If multiple items have the same name, say the number next to the item you want to use. If you don't want to choose a number, say any other command to continue."
- "Insert [today's] date"
- "Show all the app's windows."
- "This command does nothing if the window doesn't support full-screen mode."
- "This command does nothing if the window doesn't support zoom."
- "To stop using the window in full-screen mode, say “{System.WindowExitFullScreen}”. To show the menu bar if it isn't visible, say “{System.MenuBarShow}”."
- "While recording, say a sequence of commands. To stop recording, say “{System.StopRecordingCommands}”. Once recording stops, you'll be prompted to name and save your new command.\\nA recorded command is played back as quickly as possible, ignoring any pauses during the recording process. If during playback a recorded command cannot be completed, playback will be stopped and an error alert will be presented."
- "While recording, say commands that generate gestures or touch the screen to generate gestures. To stop recording, say “{System.StopRecordingGesture}”. Once recording stops, you'll be prompted to name and save your new command."
```
