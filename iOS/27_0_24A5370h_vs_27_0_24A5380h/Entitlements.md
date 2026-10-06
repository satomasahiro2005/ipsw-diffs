## 🔑 Entitlements

### filesystem

### Campo

> `/Applications/Campo.app/Campo`

```diff

+		<string>kTCCServiceReminders</string>

-	<key>com.apple.private.tcc.manager.read.access</key>
-	<array>
-		<string>kTCCServiceAll</string>
-	</array>

-		<string>/Library/WebClips</string>
+		<string>/Library/WebClips/</string>

+		<string>com.apple.remindd</string>
+		<string>com.apple.remindd.userInteractive</string>

```
### ClockAngel

> `/Applications/ClockAngel.app/ClockAngel`

```diff

+	<key>com.apple.springboard.sceneaccessory.highlight</key>
+	<true/>

```
### CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

```diff

-			<integer>-45</integer>
+			<integer>-48</integer>
+			<key>companionSetupFilters</key>
+			<array>
+				<dict>
+					<key>rssi</key>
+					<integer>-45</integer>
+				</dict>
+			</array>

```
### Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

```diff

+	<key>com.apple.keystore.device</key>
+	<true/>
+	<key>com.apple.keystore.device.verify</key>
+	<true/>

+	<key>com.apple.private.CoreAuthentication.SPI</key>
+	<true/>
+	<key>com.apple.private.LocalAuthentication.PasscodeServices</key>
+	<true/>
+	<key>com.apple.private.LocalAuthentication.SaveExtractableCredential</key>
+	<true/>

```
### Diagnostic-7004

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-7004.appex/Diagnostic-7004`

```diff

+		<string>com.apple.cameraispd</string>

```
### Diagnostic-8264

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8264.appex/Diagnostic-8264`

```diff

+		<string>AppleGasGaugeBeadsUpdateUserClient</string>
+		<string>AppleGasGaugeBeadsUpdate</string>

```
### Family

> `/Applications/Family.app/Family`

```diff

+	<key>com.apple.springboard-ui.client</key>
+	<true/>

```
### FamilyOutOfProcessUIExtension

> `/Applications/FamilyExtensionHost.app/Extensions/FamilyOutOfProcessUIExtension.appex/FamilyOutOfProcessUIExtension`

```diff

+	<key>com.apple.authkit.birthday</key>
+	<true/>
+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

```
### FamilyExtensionHost

> `/Applications/FamilyExtensionHost.app/FamilyExtensionHost`

```diff

+	<true/>
+	<key>com.apple.private.ageRange</key>

```
### InCallService

> `/Applications/InCallService.app/InCallService`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### FaceTimeShareExtension

> `/Applications/InCallService.app/PlugIns/FaceTimeShareExtension.appex/FaceTimeShareExtension`

```diff

-	<key>com.apple.developer.auto-elect-plugin</key>
-	<true/>

-	<key>com.apple.security.app-sandbox</key>
-	<true/>
-	<key>com.apple.security.files.user-selected.read-write</key>
-	<true/>
-	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>

-		<string>com.apple.CloudSharing.SPIHelper</string>
+		<string>com.apple.CloudSharing.SPIHelper-iOS</string>

```
### MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

```diff

+	<key>com.apple.idle-timer-services</key>
+	<true/>

```
### MessagesViewService

> `/Applications/MessagesViewService.app/MessagesViewService`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### MobilePhone

> `/Applications/MobilePhone.app/MobilePhone`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### MusicRecognition

> `/Applications/MusicRecognition.app/MusicRecognition`

```diff

+	<key>com.apple.mediaremote.request-bless</key>
+	<true/>

```
### PeopleMessageService

> `/Applications/PeopleMessageService.app/PeopleMessageService`

```diff

+		<string>com.apple.servicesanalytics.xpc</string>

```
### PosterBoard

> `/Applications/PosterBoard.app/PosterBoard`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.mobilecal</string>
+	</array>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+	<key>com.apple.accessibility.axassets</key>
+	<true/>

+	<key>com.apple.generativeexperiences.agentSessionStore</key>
+	<true/>

+		<string>Intelligence.Usage</string>

+		<string>group.com.apple.TVRemote</string>

+		<string>com.apple.generativeexperiences.agentSessionStore</string>

+	<key>com.apple.sharing.airdrop.readonly</key>
+	<true/>

```
### SafariViewService

> `/Applications/SafariViewService.app/SafariViewService`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### ScreenTimeWidgetExtension

> `/Applications/Screen Time.app/PlugIns/ScreenTimeWidgetExtension.appex/ScreenTimeWidgetExtension`

```diff

+		<string>Intelligence.Usage</string>

```
### ScreenshotServicesService

> `/Applications/ScreenshotServicesService.app/ScreenshotServicesService`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
+	<key>com.apple.accounts.idms.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.client.private</key>
+	<true/>

```
### ServicesPaymentAngel

> `/Applications/ServicesPaymentAngel.app/ServicesPaymentAngel`

```diff

+	<key>com.apple.private.jetpackassetd</key>
+	<true/>

+		<string>com.apple.jetpackassetd.xpc</string>

```
### StoreKitUISceneService

> `/Applications/StoreKitUISceneService.app/StoreKitUISceneService`

```diff

+	<key>com.apple.surfboard-ui.client</key>
+	<true/>
+	<key>com.apple.surfboard.allow-scene-requests-while-backgrounded</key>
+	<true/>
+	<key>com.apple.surfboard.placement-client</key>
+	<true/>
+	<key>com.apple.surfboard.scenesession-updates</key>
+	<true/>

```
### iCloud

> `/Applications/iCloud.app/iCloud`

```diff

+	<key>com.apple.developer.icloud-extended-share-access</key>
+	<array>
+		<string>InProcessShareAccessRequests</string>
+	</array>

```
### AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

```diff

+		<string>com.apple.Feedback.DraftingExtension.viewservice</string>

```
### GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

```diff

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.servicesintelligenced</string>
+	</array>

```
### PhotosViewService

> `/System/Library/CoreServices/PhotosViewService.app/PhotosViewService`

```diff

+	<key>com.apple.private.photos.restrictedresources.read</key>
+	<true/>

```
### SpringBoard

> `/System/Library/CoreServices/SpringBoard.app/SpringBoard`

```diff

+	<key>com.apple.private.iokit.preventSystemSleepSecurityIndicator</key>
+	<true/>

```
### vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

```diff

+	<key>com.apple.carousel.backlightcommand</key>
+	<true/>

```

### 🆕 AgeVerificationExtension

> `/System/Library/ExtensionKit/Extensions/AgeVerificationExtension.appex/AgeVerificationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/tmp/com.apple.AppleMediaServices/</string>
	</array>
</dict>
</plist>

```
### AskPermissionAskToResponseExtension

> `/System/Library/ExtensionKit/Extensions/AskPermissionAskToResponseExtension.appex/AskPermissionAskToResponseExtension`

```diff

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

-		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### AssetMetricsExtension

> `/System/Library/ExtensionKit/Extensions/AssetMetricsExtension.appex/AssetMetricsExtension`

```diff

+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.assistant.shared</string>
+	</array>

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.assistant.shared</string>
+	</array>

```
### FamilyOutOfProcessUIExtension

> `/System/Library/ExtensionKit/Extensions/FamilyOutOfProcessUIExtension.appex/FamilyOutOfProcessUIExtension`

```diff

+	<key>com.apple.authkit.birthday</key>
+	<true/>
+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

```
### FedAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/FedAutoEvalPlugin.appex/FedAutoEvalPlugin`

```diff

+		<string>Siri.SELFProcessedEvent</string>
+		<string>IntelligenceFlow.Transcript.Datastream</string>

```
### FedStatsPluginDynamic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginDynamic.appex/FedStatsPluginDynamic`

```diff

+		<key>Call-Context-Cards</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>CommApps.CallIntelligence.CallContextCardsFedStats</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

```
### FedStatsPluginStatic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginStatic.appex/FedStatsPluginStatic`

```diff

+		<key>Call-Context-Cards</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>CommApps.CallIntelligence.CallContextCardsFedStats</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

```
### FinanceDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/FinanceDiagnosticExtension.appex/FinanceDiagnosticExtension`

```diff

-	<key>com.apple.finance.private</key>
+	<key>com.apple.finance.internal.read</key>

```
### MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

```diff

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.Maps.MapsSync.store</string>
+		<string>com.apple.Maps.MapsSync.service</string>
+	</array>

```
### OrderExtractionDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/OrderExtractionDiagnosticExtension.appex/OrderExtractionDiagnosticExtension`

```diff

-	<key>com.apple.finance.private</key>
+	<key>com.apple.finance.internal.read</key>

```
### PhotoPicker

> `/System/Library/ExtensionKit/Extensions/PhotoPicker.appex/PhotoPicker`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.mobileslideshow</string>
+		<string>com.apple.communicationSafetySettings</string>
+	</array>

-	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
-	<array>
-		<string>com.apple.communicationSafetySettings</string>
-	</array>

```
### PhotosPicker

> `/System/Library/ExtensionKit/Extensions/PhotosPicker.appex/PhotosPicker`

```diff

+		<string>com.apple.mobileslideshow</string>

```
### ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

```diff

+	<key>com.apple.developer.background-tasks.continued-processing.inference</key>
+	<true/>

```
### ReceiptsExtractionDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/ReceiptsExtractionDiagnosticExtension.appex/ReceiptsExtractionDiagnosticExtension`

```diff

-	<key>com.apple.finance.private</key>
+	<key>com.apple.finance.internal.read</key>

```

### 🆕 SafariSearchUploadWorker

> `/System/Library/ExtensionKit/Extensions/SafariSearchUploadWorker.appex/SafariSearchUploadWorker`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>abs-client</key>
	<string>1821501079</string>
	<key>application-identifier</key>
	<string>com.apple.unilog.SafariSearchUploadWorker</string>
	<key>com.apple.developer.networking.multipath_extended</key>
	<true/>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Unilog.SafariSearch.Aggregation</string>
	</array>
	<key>com.apple.private.intelligenceplatform.client-identifier</key>
	<string>com.apple.unilog.datacollector.SafariSearchUploadWorker</string>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>UnilogSafariSearchAggregation</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Unilog.SafariSearch.Aggregation</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
			</dict>
		</dict>
		<key>com.apple.aiml.unilog.healthTelemetry</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Unilog.HealthAggregatedSummary</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
				<key>Unilog.HealthTelemetry</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>com.apple.SafariSearchUploadWorker</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.SafariSearchUploadWorker</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.SafariSearchUploadWorker</string>
	</array>
	<key>fairplay-client</key>
	<string>511712240</string>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.siri.osprey</string>
	</array>
</dict>
</plist>

```

### 🆕 SafariUsageRetentionExtension

> `/System/Library/ExtensionKit/Extensions/SafariUsageRetentionExtension.appex/SafariUsageRetentionExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.safari.SafariUsageRetentionExtension</string>
	<key>com.apple.private.intelligenceplatform.client-identifier</key>
	<string>com.apple.safari.SafariUsageRetentionExtension</string>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>SafariUsageRetention</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Lighthouse.Ledger.TaskCustomEvent</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
				<key>Unilog.SafariSearch.Aggregation</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
				<key>Unilog.SafariSearch.LongTermAggregationId</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
				<key>Unilog.SafariSearch.Stage</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.private.mlhost.allowedDictionaryGroups</key>
	<array>
		<string>SafariUsageRetention</string>
	</array>
	<key>com.apple.private.mlhost.dictionaryDelete</key>
	<true/>
	<key>com.apple.private.mlhost.dictionaryRead</key>
	<true/>
	<key>com.apple.private.mlhost.dictionaryWrite</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.mlhostd.xpc</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.mlhostd.xpc</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.assistant.support</string>
	</array>
</dict>
</plist>

```
### ScreenTimeAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeAppIntentsExtension.appex/ScreenTimeAppIntentsExtension`

```diff

+		<string>Intelligence.Usage</string>

```
### SiriAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/SiriAutoEvalPlugin.appex/SiriAutoEvalPlugin`

```diff

+		<string>IntelligenceFlow.Transcript.Datastream</string>

```
### SubscribePageExtension

> `/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension`

```diff

+	<key>com.apple.developer.background-tasks.continued-processing.inference</key>
+	<true/>

```

### 🆕 WritingToolsAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/WritingToolsAppIntentsExtension.appex/WritingToolsAppIntentsExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.WritingTools.WritingToolsAppIntentsExtension</string>
	<key>com.apple.application-identifier</key>
	<string>com.apple.WritingTools.WritingToolsAppIntentsExtension</string>
	<key>com.apple.feedbackd.remote-evaluation</key>
	<true/>
	<key>com.apple.generativeexperiences.availabilityService</key>
	<true/>
	<key>com.apple.generativeexperiences.generativeexperiencessession</key>
	<true/>
	<key>com.apple.generativeexperiences.summarization</key>
	<true/>
	<key>com.apple.generativeexperiences.textcomposition</key>
	<true/>
	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.private.appintents.extend-timeout-on-progress-updates</key>
	<true/>
	<key>com.apple.private.feedback.drafting</key>
	<true/>
	<key>com.apple.rootless.storage.shortcuts</key>
	<true/>
	<key>com.apple.sage.summarization</key>
	<true/>
	<key>com.apple.sage.textcomposition</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Shortcuts/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.sage.summarization</string>
		<string>com.apple.modelmanager</string>
		<string>com.apple.sage.textcomposition</string>
		<string>com.apple.generativeexperiences.generativeexperiencessession</string>
		<string>com.apple.generativeexperiences.textcomposition</string>
		<string>com.apple.generativeexperiences.summarization</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.siri.generativeassistantsettings</string>
		<string>com.apple.generativepartnerservicesettings</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.generativeexperiences.textcomposition</string>
		<string>com.apple.generativeexperiences.summarization</string>
		<string>com.apple.feedbackd.centralized-feedback</string>
		<string>com.apple.familycircle.agent</string>
		<string>com.apple.extensionkitservice</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.modelcatalog.catalog</string>
		<string>com.apple.gms.availability</string>
	</array>
	<key>com.apple.shortcuts.stepwise-execution</key>
	<true/>
	<key>com.apple.shortcuts.variable-injection</key>
	<true/>
	<key>com.apple.siri.VoiceShortcuts.xpc</key>
	<true/>
</dict>
</plist>

```
### accountsd

> `/System/Library/Frameworks/Accounts.framework/accountsd`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

```diff

+	<key>com.apple.symptom_diagnostics.report</key>
+	<true/>

```
### assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

```diff

+	<key>com.apple.private.imcore.imdpersistence.database-access</key>
+	<true/>

```
### ContactViewViewService

> `/System/Library/Frameworks/ContactsUI.framework/PlugIns/ContactViewViewService.appex/ContactViewViewService`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### ContactsViewService

> `/System/Library/Frameworks/ContactsUI.framework/PlugIns/ContactsViewService.appex/ContactsViewService`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### financed

> `/System/Library/Frameworks/FinanceKit.framework/financed`

```diff

+	<key>com.apple.developer.devicecheck.appattest-environment</key>
+	<string>production</string>

+	<key>com.apple.devicecheck.daemon-client</key>
+	<true/>

+		<string>com.apple.devicecheckd</string>

+		<string>com.apple.AppAttest.client</string>

```
### RemotePlayerService

> `/System/Library/Frameworks/MediaPlayer.framework/XPCServices/RemotePlayerService.xpc/RemotePlayerService`

```diff

+		<string>com.apple.fairplayd</string>
+		<string>com.apple.fpsd</string>

+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.fpsd</string>
+		<string>com.apple.fairplayd</string>
+		<string>com.apple.fairplayd.xpc</string>
+	</array>

```
### TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

```diff

+	<key>com.apple.private.security.protected-system-container</key>
+	<true/>

```

### 🆕 SpeechEncryptedLogsDiagnostic

> `/System/Library/Frameworks/Speech.framework/PlugIns/SpeechEncryptedLogsDiagnostic.appex/SpeechEncryptedLogsDiagnostic`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.private.logging.admin</key>
	<true/>
	<key>com.apple.private.logging.diagnostic</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/Logs/</string>
		<string>/Library/Logs/CrashReporter/Assistant/</string>
		<string>/Library/Logs/CrashReporter/VoiceTrigger/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.logd.admin</string>
	</array>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.icl</string>
	</array>
</dict>
</plist>

```
### localspeechrecognition

> `/System/Library/Frameworks/Speech.framework/XPCServices/localspeechrecognition.xpc/localspeechrecognition`

```diff

+	<key>com.apple.private.biome.client-identifier</key>
+	<string>com.apple.speech.localspeechrecognition</string>

+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>com.apple.AppleIntelligence.Reporting.Invocation.Step</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>AppleIntelligence.Reporting.Invocation.Step</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

```
### wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

```diff

+	<key>com.apple.private.corespotlight.internal</key>
+	<true/>
+	<key>com.apple.private.corespotlight.search.internal</key>
+	<true/>

```
### DeviceActivityReportService

> `/System/Library/Frameworks/_DeviceActivity_SwiftUI.framework/PlugIns/DeviceActivityReportService.appex/DeviceActivityReportService`

```diff

+		<string>Intelligence.Usage</string>

```

### 🆕 binary.metallib

> `/System/Library/PrivateFrameworks/AgentCanvasUICore.framework/binary.metallib`

- No entitlements *(yet)*
### appconduitd

> `/System/Library/PrivateFrameworks/AppConduit.framework/Support/appconduitd`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/mobile/Library/UserConfigurationProfiles/Truth.plist</string>
+		<string>/private/var/mobile/Library/UserConfigurationProfiles/EffectiveUserSettings.plist</string>
+	</array>

```
### amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/amsaccountsd`

```diff

+	<key>com.apple.coreidvd.digital-presentment.firstpartyclient</key>
+	<true/>

+	<key>com.apple.developer.in-app-identity-presentment</key>
+	<dict>
+		<key>document-types</key>
+		<array>
+			<string>jp-national-id-card</string>
+			<string>photo-id</string>
+			<string>us-drivers-license</string>
+		</array>
+		<key>elements</key>
+		<array>
+			<string>age</string>
+			<string>given-name</string>
+			<string>family-name</string>
+			<string>address</string>
+			<string>issuing-authority</string>
+			<string>document-expiration-date</string>
+			<string>document-issue-date</string>
+			<string>document-number</string>
+			<string>driving-privileges</string>
+			<string>date-of-birth</string>
+		</array>
+	</dict>
+	<key>com.apple.developer.in-app-identity-presentment.merchant-identifiers</key>
+	<array>
+		<string>com.apple.ams-identity-verification</string>
+		<string>com.apple.asa-identity-verification</string>
+	</array>

+	<key>com.apple.private.screen-time</key>
+	<true/>

+		<string>com.apple.coreidvd.digital-presentment.xpc</string>

```

### 🆕 ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/ANELargeModelCompilerService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.PerfPowerServices.data-donation</key>
	<true/>
	<key>com.apple.developer.hardened-process</key>
	<true/>
	<key>com.apple.private.coreml.decypt_allowed</key>
	<true/>
	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
	<true/>
	<key>com.apple.rootless.storage.ane_model_cache</key>
	<true/>
	<key>com.apple.rootless.storage.triald</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.powerlog.plxpclogger.xpc</string>
		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.powerlog.plxpclogger.xpc</string>
		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
	</array>
	<key>platform-application</key>
	<true/>
	<key>seatbelt-profiles</key>
	<array>
		<string>ANECompilerService</string>
	</array>
</dict>
</plist>

```
### askpermissiond

> `/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### assistant_service

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistant_service`

```diff

+	<key>com.apple.private.CallHistory.read</key>
+	<true/>

```
### assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

```diff

+	<key>com.apple.account.dca.fullaccess</key>
+	<true/>

+	<key>com.apple.chrono.controls</key>
+	<true/>
+	<key>com.apple.chronoservices</key>
+	<true/>

+	<key>com.apple.eligibilityd</key>
+	<true/>

+		<string>com.apple.chronoservices</string>

+		<string>com.apple.eligibilityd</string>

+		<string>com.apple.applicationaccess</string>

+		<string>com.apple.ironwood.support</string>

```
### bookassetd

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd`

```diff

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+		<string>SerialNumber</string>
+	</array>

+	<key>com.apple.private.sandbox.profile:embedded</key>
+	<string>temporary-sandbox</string>
+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>

+		<string>/Media/ManagedPurchases/</string>
+		<string>/Library/Caches/com.apple.bookassetd/</string>
+		<string>/Library/Caches/com.apple.AppleMediaServices/</string>
+		<string>/Library/HTTPStorages/com.apple.bookassetd/</string>

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.itunesstored</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.bookassetd</string>
+		<string>com.apple.AppleMediaServices</string>
+	</array>

+	<key>com.apple.security.network.client</key>
+	<true/>

+	<key>com.apple.security.ts.tmpdir</key>
+	<string>com.apple.bookassetd</string>

+	<key>platform-application</key>
+	<true/>

```
### cksharingmanagementd

> `/System/Library/PrivateFrameworks/CKSharingManagementDaemon.framework/Support/cksharingmanagementd`

```diff

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### calaccessd

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/Support/calaccessd`

```diff

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.CalendarUI</string>
+	</array>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>
+		<string>com.apple.deviceconfigurationd.consumer</string>

```
### chronod

> `/System/Library/PrivateFrameworks/ChronoCore.framework/Support/chronod`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### cloudd

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Support/cloudd`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### SpeechProfileDiagnostic

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/PlugIns/SpeechProfileDiagnostic.appex/SpeechProfileDiagnostic`

```diff

+		<string>/Library/Assistant/SpeechMaintenance/</string>

```
### suggestd

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/suggestd`

```diff

+		<key>com.apple.proactive.suggestions.SocialHighlights</key>
+		<dict>
+			<key>Views</key>
+			<array>
+				<string>siriRemembers</string>
+			</array>
+		</dict>

```
### CoreThreadCommissionerServiced

> `/System/Library/PrivateFrameworks/CoreThreadCommissionerService.framework/CoreThreadCommissionerServiced`

```diff

+		<string>com.apple.thread.datasetmacos</string>

```
### com.apple.migrationpluginwrapper

> `/System/Library/PrivateFrameworks/DataMigration.framework/XPCServices/com.apple.migrationpluginwrapper.xpc/com.apple.migrationpluginwrapper`

```diff

+	<key>com.apple.private.eligibilityd.bringUpDaemon</key>
+	<true/>

+		<string>kTCCServiceSiri</string>

```
### ScreenTimeDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ScreenTimeDiagnosticExtension.appex/ScreenTimeDiagnosticExtension`

```diff

+		<string>Intelligence.Usage</string>

```
### FilesystemMetadataSnapshotService

> `/System/Library/PrivateFrameworks/DiskSpaceDiagnostics.framework/XPCServices/FilesystemMetadataSnapshotService.xpc/FilesystemMetadataSnapshotService`

```diff

+	<key>com.apple.private.apfs.get-graft-info</key>
+	<true/>

```
### donotdisturbd

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/Support/donotdisturbd`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### SaveToFiles

> `/System/Library/PrivateFrameworks/DocumentManagerUICore.framework/PlugIns/SaveToFiles.appex/SaveToFiles`

```diff

+	<key>com.apple.private.feedback.drafting</key>
+	<true/>

+		<string>com.apple.feedbackd.centralized-feedback</string>

```
### com.apple.DocumentManager.Service

> `/System/Library/PrivateFrameworks/DocumentManagerUICore.framework/PlugIns/com.apple.DocumentManager.Service.appex/com.apple.DocumentManager.Service`

```diff

+	<key>com.apple.private.feedback.drafting</key>
+	<true/>

+		<string>com.apple.feedbackd.centralized-feedback</string>

```
### maild

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/maild`

```diff

+		<string>SERVICE_ENTITLEMENT</string>

```
### healthappd

> `/System/Library/PrivateFrameworks/HealthPluginHost.framework/healthappd`

```diff

+	<key>com.apple.developer.weatherkit</key>
+	<true/>

```
### healthrecordsd

> `/System/Library/PrivateFrameworks/HealthRecordServices.framework/healthrecordsd`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Library/Caches/com.apple.health.records/</string>
+	</array>

```
### heard

> `/System/Library/PrivateFrameworks/HearingCore.framework/heard`

```diff

+		<string>com.apple.TelephonyUtilities</string>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

-	<key>com.apple.private.AppleMediaServices</key>
-	<true/>

+	<key>com.apple.private.applemediaservices</key>
+	<true/>

```
### identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

```diff

+	<key>com.apple.PerfPowerServices.data-donation</key>
+	<true/>

+	<key>com.apple.private.aps-priority-boost</key>
+	<true/>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd`

```diff

+	<key>com.apple.mediasetupd.client</key>
+	<true/>

+	<key>com.apple.private.searchtoold.search</key>
+	<true/>

+	<key>com.apple.private.tcc.manager.access.delete</key>
+	<array>
+		<string>kTCCServiceSiri</string>
+	</array>

+		<string>com.apple.mediasetupd.server</string>

+		<string>com.apple.CoreAuthentication.agent</string>

```
### intelligencetasksd

> `/System/Library/PrivateFrameworks/IntelligenceTasksEngine.framework/Support/intelligencetasksd`

```diff

+	<key>com.apple.private.biome.client-identifier</key>
+	<string>com.apple.intelligencetasksd</string>

```
### mapspushd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/mapspushd`

```diff

+	<key>com.apple.mobileactivationd.spi</key>
+	<true/>

+		<string>com.apple.Maps.mapspushd</string>

```
### com.apple.photos.ImageConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.ImageConversionService.xpc/com.apple.photos.ImageConversionService`

```diff

+	<key>com.apple.private.photos.restrictedresources.read</key>
+	<true/>

```
### migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

```diff

+	<key>com.apple.private.CacheDelete</key>
+	<array>
+		<string>CLIENT_ENTITLEMENT</string>
+		<string>PURGE_ENTITLEMENT</string>
+		<string>PURGE_SPECIAL_CASE_ENTITLEMENT</string>
+	</array>

```
### com.apple.MobileAsset.DownloadService.Builtin

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/XPCServices/com.apple.MobileAsset.DownloadService.Builtin.xpc/com.apple.MobileAsset.DownloadService.Builtin`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read</key>
+	<array>
+		<string>/Library/Preferences/com.apple.networkextension.uuidcache.plist</string>
+	</array>

```
### MBPrebuddyFollowUpExtension

> `/System/Library/PrivateFrameworks/MobileBackup.framework/PlugIns/MBPrebuddyFollowUpExtension.appex/MBPrebuddyFollowUpExtension`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### NPKCompanionAgent

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NPKCompanionAgent`

```diff

+	<key>com.apple.NanoPassbook.IDVRemoteDeviceService.client</key>
+	<true/>

```
### searchtoold

> `/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold`

```diff

+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>

+		<string>com.apple.CloudSubscriptionFeatures.optIn</string>

```
### amsondevicestoraged

> `/System/Library/PrivateFrameworks/OnDeviceStorage.framework/Support/amsondevicestoraged`

```diff

+	<key>com.apple.runningboard.process-state</key>
+	<true/>

+	<key>com.apple.security.exception.process-info</key>
+	<true/>

```
### passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.suggestions</string>
+	</array>

```
### com.apple.PerformanceTrace.PerformanceTraceService

> `/System/Library/PrivateFrameworks/PerformanceTrace.framework/XPCServices/com.apple.PerformanceTrace.PerformanceTraceService.xpc/com.apple.PerformanceTrace.PerformanceTraceService`

```diff

+	<key>com.apple.private.swiftuitracingsupport.record</key>
+	<true/>

```
### com.apple.photos.PCCService

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/XPCServices/com.apple.photos.PCCService.xpc/com.apple.photos.PCCService`

```diff

+	<key>com.apple.private.photos.restrictedresources.read</key>
+	<true/>

```
### ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent`

```diff

+		<string>Intelligence.Usage</string>

```
### ScreenTimeSettingsAgent

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsAgent`

```diff

-		<string>App.MediaUsage</string>
-		<string>App.WebUsage</string>

+		<string>Intelligence.Usage</string>

+		<string>App.MediaUsage</string>
+		<string>App.WebUsage</string>

```
### searchd

> `/System/Library/PrivateFrameworks/Search.framework/searchd`

```diff

-	<key>com.apple.private.tcc.manager.read.access</key>
+	<key>com.apple.private.tcc.events.subscriber</key>
+	<true/>
+	<key>com.apple.private.tcc.manager.access.read</key>

```
### SeymourAppStoreService

> `/System/Library/PrivateFrameworks/SeymourServicesCore.framework/XPCServices/SeymourAppStoreService.xpc/SeymourAppStoreService`

```diff

+	<key>fairplay-client</key>
+	<string>1699554724</string>

```
### SeymourMetricsService

> `/System/Library/PrivateFrameworks/SeymourServicesCore.framework/XPCServices/SeymourMetricsService.xpc/SeymourMetricsService`

```diff

+	<key>fairplay-client</key>
+	<string>1699554724</string>

```
### siriappintentsd

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/siriappintentsd`

```diff

+		<string>TokenGeneration.Inference.Requests</string>

+		<key>SiriHeliosTokenGenerationReplay</key>
+		<dict>
+			<key>Streams</key>
+			<array>
+				<string>TokenGeneration.Inference.Requests</string>
+			</array>
+		</dict>

```
### sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

```diff

+	<key>com.apple.private.personas.propagate</key>
+	<true/>

```
### stickersd

> `/System/Library/PrivateFrameworks/Stickers.framework/Support/stickersd`

```diff

-		<string>com.apple.EmojiPreferences</string>

+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.EmojiPreferences</string>
+	</array>

```

### 🆕 TextToSpeechKonaSupport

> `/System/Library/PrivateFrameworks/TextToSpeechKonaSupport.framework/TextToSpeechKonaSupport`

- No entitlements *(yet)*

### 🆕 UARPAssetManagerServiceiCloud

> `/System/Library/PrivateFrameworks/UARPAssetManager.framework/XPCServices/UARPAssetManagerServiceiCloud.xpc/UARPAssetManagerServiceiCloud`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.MobileAccessoryUpdater.fudHelperAgent</string>
	<key>com.apple.CommCenter.fine-grained</key>
	<array>
		<string>spi</string>
		<string>cellular-plan</string>
		<string>public-cellular-plan</string>
	</array>
	<key>com.apple.developer.icloud-services</key>
	<array>
		<string>CloudKit</string>
	</array>
	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
	<array>
		<string>InverseDeviceID</string>
	</array>
	<key>com.apple.private.cloudkit.setEnvironment</key>
	<true/>
	<key>com.apple.private.cloudkit.systemLaunchDaemonAccess</key>
	<true/>
	<key>com.apple.private.xpc.launchd.per-user-lookup</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-write</key>
	<array>
		<string>/private/var/db/accessoryupdater/</string>
		<string>/private/var/run/</string>
		<string>/private/var/root/Library/Caches/</string>
		<string>/private/var/root/Library/HTTPStorages/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.commcenter.coretelephony.xpc</string>
		<string>com.apple.frontboard.systemappservices</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.ACMobileShim</string>
		<string>com.apple.AUDeveloperSettings</string>
		<string>com.apple.GEO</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.accessoryupdaterd</string>
		<string>com.apple.AUDeveloperSettings</string>
		<string>com.apple.security</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.ts.asset-access</key>
	<true/>
	<key>com.apple.springboard.CFUserNotification</key>
	<true/>
	<key>iCloud Services</key>
	<array>
		<string>CloudKit</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

```diff

+		<string>Intelligence.Usage</string>

+				<string>Intelligence.Usage</string>

```
### usernotificationsd

> `/System/Library/PrivateFrameworks/UserNotificationsCore.framework/Support/usernotificationsd`

```diff

+	<key>com.apple.private.notificationcenter.preferences</key>
+	<true/>

```
### visualintelligenced

> `/System/Library/PrivateFrameworks/VisualIntelligenceServices.framework/visualintelligenced`

```diff

+	<key>com.apple.aned.private.processModelShare.allow</key>
+	<true/>

-	<key>com.apple.private.photos.service.librarymanagement</key>
-	<true/>

```
### voicememod

> `/System/Library/PrivateFrameworks/VoiceMemos.framework/Support/voicememod`

```diff

+	<key>com.apple.private.cloudkit.tccmanager</key>
+	<true/>

```
### siriactionsd

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd`

```diff

+	<key>com.apple.bluetooth.system</key>
+	<true/>

+	<key>com.apple.nfcd.hwmanager</key>
+	<true/>
+	<key>com.apple.nfcd.session.reader.internal</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

+	<key>com.apple.private.corewifi</key>
+	<true/>

+	<key>com.apple.private.generativesearch.client.search</key>
+	<true/>

+				<key>App.Intent</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+		<key>com.apple.shortcuts</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>Mail</string>
+			</array>
+		</dict>

+		<string>com.apple.generativesearch.server.search</string>

+		<string>com.apple.nfcd.hwmanager</string>

+		<string>com.apple.private.corewifi-xpc</string>

+		<string>com.apple.HearingAids</string>
+		<string>com.apple.SoundDetection</string>

+		<string>com.apple.generativesearch</string>

+	<key>com.apple.wifi.manager-access</key>
+	<true/>

```
### matd

> `/System/Library/PrivateFrameworks/WelcomeKit.framework/matd`

```diff

+	<key>com.apple.USBCEntitlement</key>
+	<true/>

+		<string>AppleHPMARM</string>
+		<string>IOAccessoryManagerUserClient</string>

```
### BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

```diff

+	<key>com.apple.private.generativesearch.client.search</key>
+	<true/>

+	<key>com.apple.private.intelligenceplatform.client-identifier</key>
+	<string>com.apple.shortcuts</string>

+		<key>ToolKit.Sync</key>
+		<dict>
+			<key>Sets</key>
+			<dict>
+				<key>App.Intents.IndexedEnum</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+				<key>ToolKit.Tool</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+		<key>com.apple.shortcuts</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>Mail</string>
+			</array>
+		</dict>

+		<string>com.apple.SetStoreUpdateService</string>

+		<string>com.apple.biome.access.system</string>

+		<string>com.apple.generativesearch.server.search</string>

+		<string>com.apple.generativesearch</string>

```

### 🆕 FollowUpTemporary

> `/System/Library/Settings/FollowUpTemporary.settings/FollowUpTemporary`

- No entitlements *(yet)*

### 🆕 MusicRecognitionUIPlugin

> `/System/Library/Snippets/UIPlugins/MusicRecognitionUIPlugin.bundle/MusicRecognitionUIPlugin`

- No entitlements *(yet)*

### 🆕 com.apple.RemotePairing.AuditActivityNotifications

> `/System/Library/UserNotifications/Bundles/com.apple.RemotePairing.AuditActivityNotifications.bundle/com.apple.RemotePairing.AuditActivityNotifications`

- No entitlements *(yet)*
### AppStore

> `/private/var/staged_system_apps/AppStore.app/AppStore`

```diff

+	<key>com.apple.developer.background-tasks.continued-processing.inference</key>
+	<true/>

```
### AppleTV

> `/private/var/staged_system_apps/AppleTV.app/AppleTV`

```diff

-	<key>com.apple.private.internal-style-asam</key>
-	<true/>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

+		<string>com.apple.odi.legacySPIService</string>

```
### Camera

> `/private/var/staged_system_apps/Camera.app/Camera`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.camera</string>

```
### LockScreenCamera

> `/private/var/staged_system_apps/Camera.app/Extensions/LockScreenCamera.appex/LockScreenCamera`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.camera</string>

```
### Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

```
### Files

> `/private/var/staged_system_apps/Files.app/Files`

```diff

+	<key>com.apple.private.feedback.drafting</key>
+	<true/>

+		<string>com.apple.feedbackd.centralized-feedback</string>

```
### Fitness

> `/private/var/staged_system_apps/Fitness.app/Fitness`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### Games

> `/private/var/staged_system_apps/Games.app/Games`

```diff

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.servicesintelligenced</string>
+	</array>

```
### Health

> `/private/var/staged_system_apps/Health.app/Health`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

+	<key>com.apple.locationd.cardiohealthdata-write</key>
+	<true/>

```

### 🆕 HomeCoreSpotlightDelegateExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeCoreSpotlightDelegateExtension.appex/HomeCoreSpotlightDelegateExtension`

- No entitlements *(yet)*
### HomeEnergyWidgetsExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeEnergyWidgetsExtension.appex/HomeEnergyWidgetsExtension`

```diff

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+	</array>

+	<key>com.apple.system.diagnostics.iokit-properties</key>
+	<true/>

```
### GenerativePlaygroundAppIntents

> `/private/var/staged_system_apps/Image Playground.app/Extensions/GenerativePlaygroundAppIntents.appex/GenerativePlaygroundAppIntents`

```diff

+	<key>com.apple.generativeexperiences.ExternalPartnerCredentialStorage</key>
+	<true/>
+	<key>com.apple.generativeexperiences.ExternalProviderService</key>
+	<true/>

+		<string>com.apple.generativeexperiences.ExternalProviderService</string>
+		<string>com.apple.generativeexperiences.ExternalProviderTCCManagingXPC</string>

+		<string>com.apple.generativeexperiences.ExternalProviderService</string>
+		<string>com.apple.generativeexperiences.ExternalProviderTCCManagingXPC</string>

```
### Journal

> `/private/var/staged_system_apps/Journal.app/Journal`

```diff

+	<key>com.apple.authkit.client.private</key>
+	<true/>

```
### Measure

> `/private/var/staged_system_apps/Measure.app/Measure`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.birthday</key>
+	<true/>
+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>
+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.measure</string>

```
### MobileCal

> `/private/var/staged_system_apps/MobileCal.app/MobileCal`

```diff

+	<key>com.apple.private.feedback.drafting</key>
+	<true/>

+		<string>com.apple.feedbackd.centralized-feedback</string>

```
### MobileMail

> `/private/var/staged_system_apps/MobileMail.app/MobileMail`

```diff

+	<key>com.apple.private.appintents-bundle-absolute-paths</key>
+	<array>
+		<string>/AppleInternal/Library/Frameworks/ContextStagingIntents.framework</string>
+	</array>
+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+	</array>

+	<key>com.apple.private.cloudkit.spi</key>
+	<true/>

```
### com.apple.mobilenotes.SharingExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.SharingExtension.appex/com.apple.mobilenotes.SharingExtension`

```diff

+	<key>com.apple.private.cloudkit.spi</key>
+	<true/>

```
### MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.MobileAddressBook</string>
+		<string>com.apple.NanoContacts</string>
+	</array>

```
### MobileSafari

> `/private/var/staged_system_apps/MobileSafari.app/MobileSafari`

```diff

+	<key>com.apple.private.intelligenceplatform.client-identifier</key>
+	<string>com.apple.safari</string>
+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>SafariUsageDonation</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Unilog.SafariSearch.Stage</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+		<key>com.apple.aiml.unilog.healthTelemetry</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Unilog.HealthTelemetry</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

```
### Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

```diff

+	<true/>
+	<key>com.apple.private.photos.XPCStoreOptIn</key>

```
### Passwords

> `/private/var/staged_system_apps/Passwords.app/Passwords`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### Photos

> `/private/var/staged_system_apps/Photos.app/Photos`

```diff

+	<key>com.apple.private.photos.restrictedresources.read</key>
+	<true/>

```
### PhotosReliveWidget

> `/private/var/staged_system_apps/Photos.app/PlugIns/PhotosReliveWidget.appex/PhotosReliveWidget`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.mobileslideshow</string>
+	</array>

```
### Podcasts

> `/private/var/staged_system_apps/Podcasts.app/Podcasts`

```diff

+	<key>com.apple.developer.networking.carrier-constrained.app-optimized</key>
+	<false/>
+	<key>com.apple.developer.networking.carrier-constrained.appcategory</key>
+	<string>podcast-8017</string>
+	<key>com.apple.developer.networking.non-terrestrial.app-optimized</key>
+	<false/>
+	<key>com.apple.developer.networking.non-terrestrial.appcategory</key>
+	<string>podcast-8017</string>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>Library/UserConfigurationProfiles/Truth.plist</string>
+	</array>

```
### Reminders

> `/private/var/staged_system_apps/Reminders.app/Reminders`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.birthday</key>
+	<true/>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

```
### Shortcuts

> `/private/var/staged_system_apps/Shortcuts.app/Shortcuts`

```diff

+	<key>com.apple.private.generativesearch.client.search</key>
+	<true/>

+		<key>com.apple.shortcuts</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>Mail</string>
+			</array>
+		</dict>

+		<string>com.apple.generativesearch.server.search</string>

+		<string>com.apple.generativesearch</string>

```
### SiriApp

> `/private/var/staged_system_apps/SiriApp.app/SiriApp`

```diff

+	<key>com.apple.assistantd.odeon-remote</key>
+	<true/>

```
### Tips

> `/private/var/staged_system_apps/Tips.app/Tips`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>
+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.tips</string>

```
### launchd

> `/sbin/launchd`

```diff

+	<key>com.apple.private.endpoint-security.submit.bootstrap</key>
+	<true/>

```
### fileproviderctl

> `/usr/bin/fileproviderctl`

```diff

+	<key>com.apple.private.security.storage.FileProvider</key>
+	<true/>

```
### BackupAgent2

> `/usr/libexec/BackupAgent2`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### BatteryDischargeService

> `/usr/libexec/BatteryDischargeService`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.powerd.lowpowermode.allow</key>
+	<true/>
+	<key>com.apple.powerui.smartcharging</key>
+	<true/>
+	<key>com.apple.private.iokit.battery-shipping-charge-limit</key>
+	<true/>
+	<key>com.apple.private.iokit.powermanagement</key>
+	<true/>
+	<key>com.apple.private.xpc.launchd.mach-service.com.apple.BatteryDischargeService</key>
+	<true/>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.powerd.lowpowermode</string>
+	</array>
+</dict>
+</plist>

```
### ContinuityCaptureAgent

> `/usr/libexec/ContinuityCaptureAgent`

```diff

+	<key>com.apple.networkrelay.devices.read</key>
+	<true/>

```
### adprivacyd

> `/usr/libexec/adprivacyd`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>
+	</array>

```
### aned

> `/usr/libexec/aned`

```diff

+	<key>com.apple.ANELargeModelCompilerService.allow</key>
+	<true/>

```
### betaenrollmentd

> `/usr/libexec/betaenrollmentd`

```diff

+	<key>com.apple.nano.nanoregistry.generalaccess</key>
+	<true/>

```
### biomesyncd

> `/usr/libexec/biomesyncd`

```diff

+	<key>com.apple.private.intelligencetasks.sets.maintenance.client</key>
+	<true/>

-		<string>com.apple.cascade.Maintenance</string>
+		<string>com.apple.intelligencetasksd.sets.Maintenance</string>

```
### cameracaptured

> `/usr/libexec/cameracaptured`

```diff

+		<string>/Media/PhotoData/Photos.sqlite</string>
+		<string>/Media/PhotoData/Photos.sqlite-shm</string>
+		<string>/Media/PhotoData/Photos.sqlite-wal</string>

```
### cameraispd

> `/usr/libexec/cameraispd`

```diff

-		<string>IOUserClient</string>

```
### coreidvd

> `/usr/libexec/coreidvd`

```diff

+	<key>com.apple.TextUnderstanding.process</key>
+	<true/>

+		<string>com.apple.TextUnderstanding.process</string>

```
### dasd

> `/usr/libexec/dasd`

```diff

+	<key>com.apple.private.systemstats.analysis-client</key>
+	<true/>

```
### duetexpertd

> `/usr/libexec/duetexpertd`

```diff

+				<string>SiriTranscriptConversation</string>

```
### findmydeviced

> `/usr/libexec/findmydeviced`

```diff

+		<string>com.apple.pencil.pairing.services</string>

```
### hybridsearchd

> `/usr/libexec/hybridsearchd`

```diff

-		<string>com.apple.GenerativeLearningPlatform.hybridsearchd</string>
+		<string>com.apple.hybridsearchd</string>

-		<string>com.apple.GenerativeLearningPlatform.hybridsearchd</string>
+		<string>com.apple.hybridsearchd</string>

-		<string>com.apple.GenerativeLearningPlatform.hybridsearchd</string>
+		<string>com.apple.hybridsearchd</string>

```
### inputanalyticsd

> `/usr/libexec/inputanalyticsd`

```diff

+		<string>com.apple.keyboard.preferences</string>
+		<string>com.apple.suggestions</string>

```
### keybagd

> `/usr/libexec/keybagd`

```diff

+	<key>com.apple.apfs.wvek</key>
+	<true/>

```
### locationd

> `/usr/libexec/locationd`

```diff

+		<key>devmotion3_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>

+	<key>com.apple.private.CoreRepairCore.repairInfo</key>
+	<true/>

+		<string>com.apple.CoreRepairCoreXPCService</string>

```
### mobile_obliterator

> `/usr/libexec/mobile_obliterator`

```diff

+	<key>com.apple.afk.user</key>
+	<true/>

+		<string>AFKEndpointInterfaceUserClient</string>

```
### mobileassetd

> `/usr/libexec/mobileassetd`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read</key>
+	<array>
+		<string>/Library/Preferences/com.apple.networkextension.uuidcache.plist</string>
+	</array>

```
### mobilerepaird

> `/usr/libexec/mobilerepaird`

```diff

+		<string>com.apple.devicedatareset.DeviceDataResetService</string>

+	<key>com.apple.wipedevice</key>
+	<true/>

```
### momentsd

> `/usr/libexec/momentsd`

```diff

+		<string>Intelligence.Usage</string>

```
### nexusd

> `/usr/libexec/nexusd`

```diff

+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>

```
### passcodenagd

> `/usr/libexec/passcodenagd`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

+	<key>com.apple.private.sandbox.profile:embedded</key>
+	<string>temporary-sandbox</string>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>Library/UserConfigurationProfiles/Truth.plist</string>
+	</array>

-	<key>seatbelt-profiles</key>
-	<array>
-		<string>temporary-sandbox</string>
-	</array>

```
### powerexceptionsd

> `/usr/libexec/powerexceptionsd`

```diff

+	<key>com.apple.geoservices.navigation_info</key>
+	<true/>

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.navigationListener</string>
+	</array>

```
### powerexperienced

> `/usr/libexec/powerexperienced`

```diff

+	<key>com.apple.powerd.extendedbattery</key>
+	<true/>

+		<string>com.apple.powerd.extendedbattery</string>

```
### profiled

> `/usr/libexec/profiled`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### promotedcontentd

> `/usr/libexec/promotedcontentd`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### ptpassivecollectiond

> `/usr/libexec/ptpassivecollectiond`

```diff

+	<key>com.apple.private.systemstats.analysis-client</key>
+	<true/>

```
### ptpd

> `/usr/libexec/ptpd`

```diff

+	<key>com.apple.private.photos.restrictedresources.read</key>
+	<true/>

```
### remotepairingdeviced

> `/usr/libexec/remotepairingdeviced`

```diff

+	<key>com.apple.private.usernotifications.bundle-identifiers</key>
+	<array>
+		<string>com.apple.RemotePairing.AuditActivityNotifications</string>
+	</array>

+		<string>com.apple.usernoted.client</string>
+		<string>com.apple.usernotifications.listener</string>

```
### restorecameraispd

> `/usr/libexec/restorecameraispd`

```diff

-		<string>IOUserClient</string>

```
### seserviced

> `/usr/libexec/seserviced`

```diff

-		<string>com.apple.seservicexctests.credential-events</string>
+		<string>com.apple.seservicetests.credential-events</string>

```
### terminusd

> `/usr/libexec/terminusd`

```diff

+		<string>com.apple.SBUserNotification</string>

```
### transparencyd

> `/usr/libexec/transparencyd`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

-		<string>/Library/</string>
+		<string>/Library/tvremoted/</string>

```
### uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

```diff

+		<string>com.apple.AUDeveloperSettings</string>

```
### uarpd

> `/usr/libexec/uarpd`

```diff

+	<key>com.apple.security.ts.geoservices</key>
+	<true/>

```
### bluetoothd

> `/usr/sbin/bluetoothd`

```diff

-		<string>IOUserClient</string>
+		<string>IOUserUserClient</string>

-		<string>apple</string>

```
### wifid

> `/usr/sbin/wifid`

```diff

+	<key>com.apple.locationd.use-wireless-client-info</key>
+	<true/>

```


### AppOS

### AuthenticationServicesAgent

> `/usr/libexec/AuthenticationServicesAgent`

```diff

+		<string>com.apple.backboard.hid-services.xpc</string>

```


