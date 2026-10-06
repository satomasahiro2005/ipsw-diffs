## 🔑 Entitlements

### filesystem

### AAUIViewService

> `/Applications/AAUIViewService.app/AAUIViewService`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### AccessorySetupUI

> `/Applications/AccessorySetupUI.app/AccessorySetupUI`

```diff

+	<key>com.apple.app-distribution.private</key>
+	<true/>

+		<string>com.apple.AppDistributionLaunchAngel</string>
+		<string>com.apple.managedappdistributiond.xpc</string>

```
### AuthenticationServicesUI

> `/Applications/AuthenticationServicesUI.app/AuthenticationServicesUI`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### Campo

> `/Applications/Campo.app/Campo`

```diff

+		<string>/private/var/db/com.apple.countryd/</string>

+		<string>/Library/Caches/com.apple.countryd/</string>

```
### CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

```diff

-			<key>companionSetupFilters</key>
-			<array>
-				<dict>
-					<key>rssi</key>
-					<integer>-45</integer>
-				</dict>
-			</array>

```
### Diagnostic-4153

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4153.appex/Diagnostic-4153`

```diff

+	<key>com.apple.developer.avfoundation.multitasking-camera-access</key>
+	<true/>

```

### 🆕 Diagnostic-6027

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6027.appex/Diagnostic-6027`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticsKit.extension</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/db/accessoryupdater/uarpd/sysdiagnose/assets/metrics/</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.Diagnostics</string>
	</array>
	<key>com.apple.security.system-groups</key>
	<array>
		<string>systemgroup.com.apple.DiagnosticsKit</string>
	</array>
</dict>
</plist>

```
### InputUI

> `/Applications/InputUI.app/InputUI`

```diff

+	<key>com.apple.generativeexperiences.availabilityService</key>
+	<true/>
+	<key>com.apple.generativeexperiences.availabilityService.waitlistStatus</key>
+	<true/>

+	<key>com.apple.modelcatalog.full-access</key>
+	<true/>

+	<key>com.apple.private.LocalAuthentication.CallerName</key>
+	<true/>

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>
+		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
+		<string>com.apple.MobileAsset.UAF.FM.Visual</string>
+	</array>

+	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
+	<true/>
+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+		<string>/private/var/db/eligibilityd/eligibility.plist</string>
+		<string>/private/var/db/assetsubscriptiond/</string>
+		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Visual/purpose_auto/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Visual/</string>
+		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
+		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
+		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Visual/</string>
+		<string>/private/var/mobile/Library/com.apple.modelcatalog/sideload/</string>
+		<string>/private/var/mobile/Library/Application Support/com.apple.VisualGeneration/</string>

+		<string>com.apple.generativeexperiences.availabilityService</string>
+		<string>com.apple.modelcatalog.catalog</string>
+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>
+		<string>com.apple.modelmanager</string>
+		<string>com.apple.siri.uaf.service</string>
+		<string>com.apple.siri.uaf.subscription.service</string>

+		<string>com.apple.gms.availability</string>
+		<string>com.apple.UnifiedAssetFramework</string>
+		<string>com.apple.modelcatalog.ajax</string>

```
### MessagesViewService

> `/Applications/MessagesViewService.app/MessagesViewService`

```diff

+	<key>com.apple.springboard.homeScreenIconStyle</key>
+	<true/>

```
### MobilePhone

> `/Applications/MobilePhone.app/MobilePhone`

```diff

+	<key>com.apple.private.sharing.paired-contacts</key>
+	<true/>

```
### NewDeviceSetupUIService

> `/Applications/NewDeviceSetupUIService.app/NewDeviceSetupUIService`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### PassbookUIService

> `/Applications/PassbookUIService.app/PassbookUIService`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

-		<string>com.apple.cdp.daemon</string>

```
### PhotosUIService

> `/Applications/PhotosUIService.app/PhotosUIService`

```diff

+		<string>com.apple.mobileslideshow</string>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+	<key>com.apple.private.CallHistory.read-write</key>
+	<true/>

+	<key>com.apple.private.security.storage.CallHistory</key>
+	<true/>

```
### ScreenTimeSettingsShield

> `/Applications/ScreenTimeSettingsShield.app/ScreenTimeSettingsShield`

```diff

+	<key>com.apple.app-distribution.private</key>
+	<true/>

+		<string>com.apple.AppDistributionLaunchAngel</string>

```
### ScreenshotServicesService

> `/Applications/ScreenshotServicesService.app/ScreenshotServicesService`

```diff

+		<string>com.apple.mobileslideshow</string>

+	<key>com.apple.telephonyutilities.callservicesd</key>
+	<array>
+		<string>access-call-capabilities</string>
+		<string>access-call-providers</string>
+		<string>access-calls</string>
+	</array>

```
### ServicesPaymentAngel

> `/Applications/ServicesPaymentAngel.app/ServicesPaymentAngel`

```diff

+	<key>com.apple.frontboardservices.display-layout-monitor</key>
+	<true/>

-		<string>com.apple.ServicesPaymentAngel</string>
-		<string>com.apple.xpc.amsaccountsd</string>

+		<string>com.apple.ServicesPaymentAngel</string>

+		<string>com.apple.xpc.amsaccountsd</string>

+	<key>com.apple.springboard.biometricUnlockSuppression</key>
+	<true/>

```
### Setup

> `/Applications/Setup.app/Setup`

```diff

-		<string>com.apple.MobileAsset.SetupAssistantNewFeaturesIntroduction</string>

```
### SupportFlow

> `/Applications/SupportFlow.app/SupportFlow`

```diff

-	<array>
-		<string>kTCCServiceFaceID</string>
-	</array>
-	<key>com.apple.private.tcc.allow-or-regional-prompt</key>

+		<string>kTCCServiceFaceID</string>

```
### assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

```diff

+	<key>com.apple.private.mediaexperience.setsilentmode.allow</key>
+	<true/>

+		<string>com.apple.mediaexperience.endpoint.xpc</string>

```
### GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

```diff

+	<key>com.apple.frontboardservices.display-layout-monitor</key>
+	<true/>

```
### SpringBoard

> `/System/Library/CoreServices/SpringBoard.app/SpringBoard`

```diff

+	<key>com.apple.accessibility.axassets</key>
+	<true/>

+	<true/>
+	<key>com.apple.private.iokit.battery-shipping-charge-limit</key>

```
### scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

```diff

+	<key>com.apple.hid.manager.user-access-privileged</key>
+	<true/>

```
### settings

> `/System/Library/DataClassMigrators/PreferencesMigrator.migrator/settings`

```diff

+	<key>com.apple.private.settings-search-reindex</key>
+	<true/>

```
### BiomeSELFIngestor

> `/System/Library/ExtensionKit/Extensions/BiomeSELFIngestor.appex/BiomeSELFIngestor`

```diff

-				<string>IntelligenceFlow.Transcript.Datastream</string>

```
### ComposeReviewExtension

> `/System/Library/ExtensionKit/Extensions/ComposeReviewExtension.appex/ComposeReviewExtension`

```diff

-	<key>com.apple.security.iokit-user-client-class</key>
-	<string>com_apple_driver_FairPlayIOKitUserClient</string>

```
### FedStatsPluginDynamic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginDynamic.appex/FedStatsPluginDynamic`

```diff

+		<string>HKCharacteristicTypeIdentifierFitzpatrickSkinType</string>
+		<string>HKQuantityTypeIdentifierBodyMassIndex</string>

+		<string>HKQuantityTypeIdentifierAppleExerciseTime</string>

+		<key>Pcc-Recitation-Block-Rate</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>PrivateMLClient.RecitationMetrics</key>
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

+		<string>HKCharacteristicTypeIdentifierFitzpatrickSkinType</string>
+		<string>HKQuantityTypeIdentifierBodyMassIndex</string>

+		<string>HKQuantityTypeIdentifierAppleExerciseTime</string>

+		<key>Pcc-Recitation-Block-Rate</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>PrivateMLClient.RecitationMetrics</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

```
### IntelligencePlatformDataActionsAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/IntelligencePlatformDataActionsAppIntentsExtension.appex/IntelligencePlatformDataActionsAppIntentsExtension`

```diff

+		<string>Intelligence.Usage</string>

```
### OBCEngagePlugin

> `/System/Library/ExtensionKit/Extensions/OBCEngagePlugin.appex/OBCEngagePlugin`

```diff

+		<string>Location.Semantic</string>

+				<string>Location.Semantic</string>

```
### ODDFeatureDigestsExtension

> `/System/Library/ExtensionKit/Extensions/ODDFeatureDigestsExtension.appex/ODDFeatureDigestsExtension`

```diff

+		<string>Siri.ODDI.ODDAssistantLLMSiriDigests</string>

```

### 🆕 PSECollectionExtension

> `/System/Library/ExtensionKit/Extensions/PSECollectionExtension.appex/PSECollectionExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.lighthouse.PSECollectionExtension</string>
	<key>com.apple.assistant.settings</key>
	<true/>
	<key>com.apple.coreduetd.allow</key>
	<true/>
	<key>com.apple.coreduetd.context</key>
	<true/>
	<key>com.apple.coreduetd.knowledge</key>
	<true/>
	<key>com.apple.modelcatalog.full-access</key>
	<true/>
	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.private.biome.client-identifier</key>
	<string>com.apple.lighthouse.PSECollectionExtension</string>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Photos.Engagement</string>
		<string>Photos.Edit</string>
		<string>Photos.Search</string>
		<string>Photos.Favorite</string>
		<string>Photos.Share</string>
		<string>Photos.Picker</string>
		<string>Photos.Delete</string>
		<string>Photos.Memories.Viewed</string>
		<string>Photos.Memories.Shared</string>
		<string>IntelligenceFlow.Transcript.Datastream</string>
		<string>App.Install</string>
		<string>App.Intent</string>
		<string>Siri.UI</string>
		<string>Media.NowPlaying</string>
		<string>Notification</string>
		<string>Clock.Alarm</string>
		<string>App.InFocus</string>
		<string>App.Intents.Transcript</string>
		<string>Siri.Execution</string>
		<string>HomeKit.Client.AccessoryControl</string>
		<string>Siri.SELFProcessedEvent</string>
	</array>
	<key>com.apple.private.biome.read-write</key>
	<array>
		<string>Siri.PostSiriEngagement</string>
	</array>
	<key>com.apple.private.biome.writer</key>
	<array>
		<string>Lighthouse.Ledger.TaskCustomEvent</string>
	</array>
	<key>com.apple.private.coreservices.cangetcurrentactivityinfo</key>
	<true/>
	<key>com.apple.private.coreservices.canopenactivity</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>LighthouseInference</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>IntelligenceFlow.Transcript.Datastream</string>
			</array>
		</dict>
		<key>MLHostTelemetry</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>Lighthouse.Ledger.TaskCustomEvent</string>
			</array>
		</dict>
	</dict>
	<key>com.apple.private.security.no-sandbox</key>
	<true/>
	<key>com.apple.private.security.storage.CoreKnowledge</key>
	<true/>
	<key>com.apple.rootless.storage.coreduet_knowledge_store</key>
	<true/>
	<key>com.apple.rootless.storage.coreknowledge</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-write</key>
	<array>
		<string>/var/mobile/Library/com.apple.internal.ck/</string>
		<string>/private/var/mobile/Library/Logs/com.apple.FeatureStore/biomeStream/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Logs/com.apple.FeatureStore/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.PublicStreamAccessService</string>
		<string>com.apple.siri.analytics.assistant</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.siri.analytics.assistant</string>
		<string>com.apple.biome.PublicStreamAccessService</string>
		<string>com.apple.siriknowledged</string>
		<string>com.apple.siri-distributed-evaluation</string>
		<string>com.apple.coreduetd.context</string>
		<string>com.apple.coreduetd</string>
		<string>com.apple.coreduetd.knowledge</string>
		<string>com.apple.coreduetd.people</string>
		<string>com.apple.analyticsd</string>
	</array>
	<key>com.apple.siriknowledged</key>
	<true/>
</dict>
</plist>

```
### PhotosAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/PhotosAppIntentsExtension.appex/PhotosAppIntentsExtension`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.mobileslideshow</string>
+	</array>

```
### PhotosFileProvider

> `/System/Library/ExtensionKit/Extensions/PhotosFileProvider.appex/PhotosFileProvider`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.mobileslideshow</string>
+	</array>

```
### PhotosMessagesApp

> `/System/Library/ExtensionKit/Extensions/PhotosMessagesApp.appex/PhotosMessagesApp`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.mobileslideshow</string>
+	</array>

```
### ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

```diff

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.pisco.suinfo</string>
+	</array>

```
### SafariUsageRetentionExtension

> `/System/Library/ExtensionKit/Extensions/SafariUsageRetentionExtension.appex/SafariUsageRetentionExtension`

```diff

+				<key>Unilog.SafariSearch.Stage</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+		<key>UnilogInstrumentation.IdentifierProvider</key>
+		<dict>
+			<key>Streams</key>
+			<dict>

-				<key>Unilog.SafariSearch.Stage</key>
+			</dict>
+		</dict>
+		<key>com.apple.aiml.unilog.healthTelemetry</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Unilog.HealthTelemetry</key>

-					<string>read-only</string>
+					<string>read-write</string>

```
### ScreenTimeAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeAppIntentsExtension.appex/ScreenTimeAppIntentsExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### SearchToolExtension

> `/System/Library/ExtensionKit/Extensions/SearchToolExtension.appex/SearchToolExtension`

```diff

-		<string>com.apple.MobileAsset.UAF.Siri.AnswerSynthesis</string>

-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Siri_AnswerSynthesis/purpose_auto/</string>

-		<string>UAF_AB_ANSWER_SYNTHESIS</string>
-		<string>SEARCH_TOOL_ANSWER_SYNTHESIS</string>

```
### SiriSuggestionsLightHousePlugin

> `/System/Library/ExtensionKit/Extensions/SiriSuggestionsLightHousePlugin.appex/SiriSuggestionsLightHousePlugin`

```diff

+		<string>group.com.apple.siri.inference</string>

```
### SubscribePageExtension

> `/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension`

```diff

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.pisco.suinfo</string>
+	</array>

```
### TGOnDeviceInferenceProviderService

> `/System/Library/ExtensionKit/Extensions/TGOnDeviceInferenceProviderService.appex/TGOnDeviceInferenceProviderService`

```diff

+		<string>com.apple.MobileAsset.UAF.Translation.MMAssets</string>

```

### 🆕 TVRemoteSettingsAppIntents

> `/System/Library/ExtensionKit/Extensions/TVRemoteSettingsAppIntents.appex/TVRemoteSettingsAppIntents`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
	<string>com.apple.Preferences</string>
	<key>com.apple.security.app-sandbox</key>
	<true/>
</dict>
</plist>

```

### 🆕 TrackpadAndMouseSettingsIntents

> `/System/Library/ExtensionKit/Extensions/TrackpadAndMouseSettingsIntents.appex/TrackpadAndMouseSettingsIntents`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
	<string>com.apple.Preferences</string>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.UIKit</string>
		<string>kCFPreferencesAnyApplication</string>
	</array>
</dict>
</plist>

```
### contactsd

> `/System/Library/Frameworks/Contacts.framework/Support/contactsd`

```diff

+	<key>com.apple.private.contacts</key>
+	<true/>

```

### 🆕 CardioFitnessDiagnostic

> `/System/Library/Frameworks/CoreMotion.framework/PlugIns/CardioFitnessDiagnostic.appex/CardioFitnessDiagnostic`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.locationd.cardiohealthdata-read</key>
	<true/>
</dict>
</plist>

```
### spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

```diff

+	<key>com.apple.private.cascade.donation-requester</key>
+	<true/>

```
### CommCenterMobileHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterMobileHelper`

```diff

+		<string>Library/Preferences/com.apple.CommCenter.plist</string>

+		<string>com.apple.CommCenter</string>

```
### financed

> `/System/Library/Frameworks/FinanceKit.framework/financed`

```diff

-		<string>com.apple.pay.finance.dropbox.development</string>

-		<string>com.apple.pay.finance.dropbox</string>

```
### healthd

> `/System/Library/Frameworks/HealthKit.framework/healthd`

```diff

+	<key>com.apple.fitnessintelligenced</key>
+	<true/>

+		<string>com.apple.fitnessintelligenced</string>

```
### coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

```diff

+	<key>com.apple.private.applecredentialmanager.thumbandpay.allow</key>
+	<true/>

```
### MediaPlayerDiagnosticExtension

> `/System/Library/Frameworks/MediaPlayer.framework/PlugIns/MediaPlayerDiagnosticExtension.appex/MediaPlayerDiagnosticExtension`

```diff

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.musicd</string>
+	</array>

```
### SpeechEncryptedLogsDiagnostic

> `/System/Library/Frameworks/Speech.framework/PlugIns/SpeechEncryptedLogsDiagnostic.appex/SpeechEncryptedLogsDiagnostic`

```diff

+	<key>com.apple.security.app-sandbox</key>
+	<true/>

```

### 🆕 NanoControlCenterBridgeSettings

> `/System/Library/NanoPreferenceBundles/General/NanoControlCenterBridgeSettings.bundle/NanoControlCenterBridgeSettings`

- No entitlements *(yet)*

### 🆕 SiriComplication

> `/System/Library/NanoTimeKit/ComplicationBundles/SiriComplication.bundle/SiriComplication`

- No entitlements *(yet)*
### AAUIFollowUpExtension

> `/System/Library/PrivateFrameworks/AppleAccountUI.framework/PlugIns/AAUIFollowUpExtension.appex/AAUIFollowUpExtension`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

```
### amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/amsaccountsd`

```diff

+		<string>/Library/Caches/com.apple.nsurlsessiond/Downloads/com.apple.amsaccountsd/</string>

```
### assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

```diff

+	<key>com.apple.private.corewifi</key>
+	<true/>
+	<key>com.apple.private.corewifi.readonly</key>
+	<true/>

```
### akd

> `/System/Library/PrivateFrameworks/AuthKit.framework/akd`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>
+	<key>com.apple.cdp.recovery</key>
+	<true/>

```
### AKFollowUpExtension

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/PlugIns/AKFollowUpExtension.appex/AKFollowUpExtension`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

```
### bookdatastored

> `/System/Library/PrivateFrameworks/BookDataStore.framework/Support/bookdatastored`

```diff

+		<string>com.apple.servicesanalytics.xpc</string>

```
### bookassetd

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd`

```diff

+		<string>com.apple.servicesanalytics.xpc</string>

```
### analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

```diff

+		<string>com.apple.iohideventsystem</string>

```
### CDPFollowUpExtension

> `/System/Library/PrivateFrameworks/CoreCDPUI.framework/PlugIns/CDPFollowUpExtension.appex/CDPFollowUpExtension`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>
+	<key>com.apple.cdp.recovery</key>
+	<true/>

+	<key>com.apple.cdp.statemachine</key>
+	<true/>
+	<key>com.apple.cdp.telemetry</key>
+	<true/>
+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### speechmaintenanced

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmaintenanced`

```diff

+	<key>com.apple.linkd.registry</key>
+	<true/>

```
### followupd

> `/System/Library/PrivateFrameworks/CoreFollowUp.framework/followupd`

```diff

+		<string>com.apple.Siri.FollowUp</string>

```
### corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

```diff

+	<key>com.apple.CompanionLink</key>
+	<true/>

+	<key>com.apple.developer.homekit</key>
+	<true/>

+	<key>com.apple.private.homekit</key>
+	<true/>
+	<key>com.apple.private.homekit.allow-access-without-prompting</key>
+	<true/>

+		<string>kTCCServiceWillow</string>

+		<string>kTCCServiceHomeKit</string>

+		<string>/Library/Caches/com.apple.HomeKit.configurations</string>
+		<string>/Library/Caches/com.apple.HomeKit</string>

+		<string>com.apple.homed.xpc</string>
+		<string>com.apple.CompanionLink</string>

```
### com.apple.migrationpluginwrapper

> `/System/Library/PrivateFrameworks/DataMigration.framework/XPCServices/com.apple.migrationpluginwrapper.xpc/com.apple.migrationpluginwrapper`

```diff

+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

+		<string>kTCCServiceSiriAccess</string>

+		<string>com.apple.appprotectiond.read</string>

```
### IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

```diff

+	<key>com.apple.private.logging.diagnostic</key>
+	<true/>

```
### FilesystemMetadataSnapshotService

> `/System/Library/PrivateFrameworks/DiskSpaceDiagnostics.framework/XPCServices/FilesystemMetadataSnapshotService.xpc/FilesystemMetadataSnapshotService`

```diff

+	<key>com.apple.private.vfs.snapshot</key>
+	<true/>

```

### 🆕 ExclavesStats

> `/System/Library/PrivateFrameworks/ExclavesStats.framework/ExclavesStats`

- No entitlements *(yet)*
### familycircled

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/familycircled`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### fileindexerd

> `/System/Library/PrivateFrameworks/FileIndexerDaemon.framework/Support/fileindexerd`

```diff

+		<string>com.apple.revisiond</string>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/generativeexperiencesd`

```diff

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.modelcatalog</string>
+	</array>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>
+		<string>com.apple.DeviceConfigurationAgent.consumer.async</string>
+		<string>com.apple.DeviceConfigurationAgent.publisher</string>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

+	<key>com.apple.frontboardservices.display-layout-monitor</key>
+	<true/>

+	<key>com.apple.private.activitykit.ephemeralActivityRequester</key>
+	<true/>
+	<key>com.apple.private.activitykit.unboundedActivityRequester</key>
+	<true/>
+	<key>com.apple.private.allow-background-haptics</key>
+	<true/>

+	<key>com.apple.private.sessionkit.custom-platter-target</key>
+	<true/>
+	<key>com.apple.private.sessionkit.permitMultipleProcessInputs</key>
+	<true/>
+	<key>com.apple.private.sessionkit.sessionRequest</key>
+	<true/>

+		<string>com.apple.audio.hapticd</string>

+	<key>com.apple.security.exception.sysctl.read-write</key>
+	<array>
+		<string>kern.memorystatus_vm_pressure_send</string>
+	</array>

```
### intelligencecontextd

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd`

```diff

+	<key>com.apple.frontboard.launchapplications</key>
+	<true/>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd`

```diff

+	<key>com.apple.account.dca.fullaccess</key>
+	<true/>

+		<string>kTCCServicePhotos</string>

-		<string>kTCCServicePhotos</string>

-		<string>kTCCServicePhotosAdd</string>

-		<string>kTCCServiceSiri</string>
+		<string>kTCCServiceSiriAccess</string>

+		<string>com.apple.generativesearch.server.search</string>

+		<string>SIRI_INTELLIGENCE_FLOW_PLANNER</string>

```
### IntelligencePlatformComputeService

> `/System/Library/PrivateFrameworks/IntelligencePlatformCompute.framework/XPCServices/IntelligencePlatformComputeService.xpc/IntelligencePlatformComputeService`

```diff

-	<key>com.apple.private.photos.XPCStoreOptIn</key>
-	<true/>

```
### intelligenceplatformd

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/intelligenceplatformd`

```diff

+		<string>Intelligence.Usage</string>

```
### knowledgeconstructiond

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/knowledgeconstructiond`

```diff

+		<string>Intelligence.Usage</string>

```
### Managed Background Assets Helper Service

> `/System/Library/PrivateFrameworks/ManagedBackgroundAssets.framework/XPCServices/Managed Background Assets Helper Service.xpc/Managed Background Assets Helper Service`

```diff

+	<key>com.apple.private.userprofiles.read</key>
+	<true/>

+		<string>/private/var/mobile/Containers/Data/Application/*/tmp/com.apple.backgroundassets.managed.helper.service/</string>

+		<string>com.apple.mobile.keybagd.UserManager.xpc</string>
+		<string>com.apple.mobile.keybagd.xpc</string>
+		<string>com.apple.mobile.usermanagerd.xpc</string>

+		<string>com.apple.userprofiles</string>

+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.fairplayd</string>
+		<string>com.apple.fairplayd.xpc</string>
+		<string>com.apple.fpsd</string>
+	</array>

+	<key>com.apple.usermanagerd.persona.fetch</key>
+	<true/>

```

### 🆕 Managed Background Assets Relay Service

> `/System/Library/PrivateFrameworks/ManagedBackgroundAssets.framework/XPCServices/Managed Background Assets Relay Service.xpc/Managed Background Assets Relay Service`

- No entitlements *(yet)*
### destinationd

> `/System/Library/PrivateFrameworks/MapsSuggestions.framework/destinationd`

```diff

+		<string>com.apple.NanoHomeScreen.SmartStackSuggestions</string>

```
### nanomapscd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/nanomapscd`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>
+	</array>

```
### navd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/navd`

```diff

+	<key>com.apple.private.appintents.live-entities.read</key>
+	<true/>
+	<key>com.apple.private.appintents.live-entities.write</key>
+	<array>
+		<string>maps.parkedCar</string>
+	</array>

+		<string>com.apple.appintents.LiveEntityService</string>

```
### mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

```diff

+	<key>com.apple.runningboard.terminateprocess</key>
+	<true/>

```
### migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

```diff

+	<key>com.apple.private.ids.idquery-device-flush</key>
+	<true/>

```
### backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

```diff

+	<key>com.apple.storage.nandtaskscheduler</key>
+	<true/>

```
### NFUIService

> `/System/Library/PrivateFrameworks/NearFieldPrivateServices.framework/XPCServices/NFUIService.xpc/NFUIService`

```diff

+	<key>com.apple.private.sandbox.profile:embedded</key>
+	<string>temporary-sandbox</string>
+	<key>com.apple.runningboard.process-state</key>
+	<true/>

+	<false/>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.seserviced.presentment-authorization</string>
+	</array>
+	<key>com.apple.seserviced.presentment-authorization</key>

+	<key>platform-application</key>
+	<true/>

```
### searchtoold

> `/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold`

```diff

+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

-		<string>com.apple.MobileAsset.UAF.Siri.AnswerSynthesis</string>

+		<string>kTCCServiceSiriAccess</string>
+	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>

-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Siri_AnswerSynthesis/purpose_auto/</string>

+		<string>com.apple.tccd</string>

+		<string>com.apple.tccd</string>

-		<string>UAF_AB_ANSWER_SYNTHESIS</string>

```
### passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### PersonalizedSensingService

> `/System/Library/PrivateFrameworks/PersonalizedSensing.framework/XPCServices/PersonalizedSensingService.xpc/PersonalizedSensingService`

```diff

-				<key>Fitness.Guest</key>
-				<dict>
-					<key>mode</key>
-					<string>read-write</string>
-				</dict>

```
### privacyaccountingd

> `/System/Library/PrivateFrameworks/PrivacyAccounting.framework/Versions/A/Resources/privacyaccountingd`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UserConfigurationProfiles/</string>
+	</array>

```
### privatecloudcomputed

> `/System/Library/PrivateFrameworks/PrivateCloudCompute.framework/privatecloudcomputed.app/privatecloudcomputed`

```diff

+	<key>com.apple.private.container.access</key>
+	<dict>
+		<key>daemon</key>
+		<dict>
+			<key>com.apple.privatecloudcomputed</key>
+			<dict>
+				<key>data</key>
+				<dict>
+					<key>access</key>
+					<string>path-only</string>
+					<key>operations</key>
+					<array>
+						<string>delete</string>
+					</array>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

+	<key>com.apple.private.security.protected-system-container</key>
+	<true/>

```
### ScreenTimeSettingsAgent

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsAgent`

```diff

+	<key>com.apple.private.settings-search-reindex</key>
+	<true/>

+		<string>com.apple.SettingsServices.SearchReindexService</string>

```
### servicesintelligenced

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/servicesintelligenced`

```diff

+	<key>com.apple.PerfPowerServices.data-donation</key>
+	<true/>

+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

+		<string>com.apple.appprotectiond.read</string>
+		<string>com.apple.powerlog.plxpclogger.xpc</string>
+		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>

```

### 🆕 SettingsSearchReindexService

> `/System/Library/PrivateFrameworks/SettingsServices.framework/XPCServices/SettingsSearchReindexService.xpc/SettingsSearchReindexService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.SettingsServices.Reindexer</string>
	</array>
</dict>
</plist>

```
### siriinferenced

> `/System/Library/PrivateFrameworks/SiriInference.framework/Support/siriinferenced`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

```diff

+		<string>/private/var/mobile/Library/com.apple.modelcatalog/sideload/</string>

```
### softwareupdateservicesd

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/Support/softwareupdateservicesd`

```diff

+	<key>com.apple.private.allow-susd-helper-service</key>
+	<true/>

+		<string>com.apple.powerd.coresmartpowernap</string>

+		<string>com.apple.sus.SUDaemonHelperService</string>

```

### 🆕 SUDaemonHelperService

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesDaemonFramework.framework/XPCServices/SUDaemonHelperService.xpc/SUDaemonHelperService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.sandbox.profile:embedded</key>
	<string>temporary-sandbox</string>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/MobileSoftwareUpdate/asu_trial/</string>
	</array>
	<key>com.apple.trial.client</key>
	<array>
		<string>APPLE_SOFTWARE_UPDATE_SUSAU</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### STExtractionService.privileged

> `/System/Library/PrivateFrameworks/StreamingExtractor.framework/XPCServices/STExtractionService.privileged.xpc/STExtractionService.privileged`

```diff

+		<string>com.apple.backgroundassets.managed.relay.service</string>

```
### systemstatusd

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/Support/systemstatusd`

```diff

+	<key>com.apple.runningboard.assertions.systemstatusd</key>
+	<true/>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

+	<key>com.apple.DeviceAccess.private</key>
+	<true/>

+		<string>com.apple.DeviceAccess.xpc</string>

```

### 🆕 FollowUp

> `/System/Library/Settings/FollowUp.settings/FollowUp`

- No entitlements *(yet)*

### 🆕 Headphones

> `/System/Library/Settings/Headphones.settings/Headphones`

- No entitlements *(yet)*

### 🆕 TVRemoteSettings

> `/System/Library/Settings/TVRemoteSettings.settings/TVRemoteSettings`

- No entitlements *(yet)*

### 🆕 com.apple.Siri.FollowUp

> `/System/Library/UserNotifications/Bundles/com.apple.Siri.FollowUp.bundle/com.apple.Siri.FollowUp`

- No entitlements *(yet)*
### AppStore

> `/private/var/staged_system_apps/AppStore.app/AppStore`

```diff

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.pisco.suinfo</string>
+	</array>

```
### Books

> `/private/var/staged_system_apps/Books.app/Books`

```diff

+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>CrashReporting</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>OSAnalytics.Stability.Crash</key>
+				<true/>
+			</dict>
+		</dict>
+	</dict>

```
### BooksNotificationContentExtension

> `/private/var/staged_system_apps/Books.app/PlugIns/BooksNotificationContentExtension.appex/BooksNotificationContentExtension`

```diff

+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>CrashReporting</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>OSAnalytics.Stability.Crash</key>
+				<true/>
+			</dict>
+		</dict>
+	</dict>

```
### BooksProductPageExtension

> `/private/var/staged_system_apps/Books.app/PlugIns/BooksProductPageExtension.appex/BooksProductPageExtension`

```diff

+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>CrashReporting</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>OSAnalytics.Stability.Crash</key>
+				<true/>
+			</dict>
+		</dict>
+	</dict>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+		<string>com.apple.siri.ssrvtuitrainingservice.xpc</string>

```
### Camera

> `/private/var/staged_system_apps/Camera.app/Camera`

```diff

+	<key>com.apple.assistant.cdm.client</key>
+	<true/>

+	<key>com.apple.locationd.prompt_content_control</key>
+	<true/>

```
### LockScreenCamera

> `/private/var/staged_system_apps/Camera.app/Extensions/LockScreenCamera.appex/LockScreenCamera`

```diff

+	<key>com.apple.assistant.cdm.client</key>
+	<true/>

+	<key>com.apple.locationd.prompt_content_control</key>
+	<true/>

```
### Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

```diff

+	<key>com.apple.private.sharing.paired-contacts</key>
+	<true/>

```
### FindMy

> `/private/var/staged_system_apps/FindMy.app/FindMy`

```diff

+		<string>cellular-plan</string>

+	<key>com.apple.findmy.secureenvironment.client</key>
+	<true/>

+		<string>com.apple.findmy.FindMySecureEnvironmentXPCService</string>

```
### Freeform

> `/private/var/staged_system_apps/Freeform.app/Freeform`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### Health

> `/private/var/staged_system_apps/Health.app/Health`

```diff

-	<key>com.apple.developer.in-app-payments</key>
-	<array/>

```
### Home

> `/private/var/staged_system_apps/Home.app/Home`

```diff

+	<key>com.apple.rapport.Client</key>
+	<true/>

```
### HomeWidget

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget`

```diff

-	<key>com.apple.developer.declared-age-range</key>
-	<true/>

-	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
-	<string>com.apple.Home</string>

```
### HomeWidgetLockScreen

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidgetLockScreen.appex/HomeWidgetLockScreen`

```diff

-	<key>com.apple.developer.declared-age-range</key>
-	<true/>

-	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
-	<string>com.apple.Home</string>

```
### Maps

> `/private/var/staged_system_apps/Maps.app/Maps`

```diff

+	<key>com.apple.maps.suggestions.signalpipeline</key>
+	<true/>

```
### MobileMail

> `/private/var/staged_system_apps/MobileMail.app/MobileMail`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

```diff

+	<key>com.apple.springboard.homeScreenIconStyle</key>
+	<true/>

```
### MessagesPluginNotificationExtension

> `/private/var/staged_system_apps/MobileSMS.app/PlugIns/MessagesPluginNotificationExtension.appex/MessagesPluginNotificationExtension`

```diff

+	<key>com.apple.springboard.homeScreenIconStyle</key>
+	<true/>

```
### MobileSafari

> `/private/var/staged_system_apps/MobileSafari.app/MobileSafari`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

+		<string>Unilog.SafariSearch.Stage</string>

```
### Passwords

> `/private/var/staged_system_apps/Passwords.app/Passwords`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### PhotosNotificationsUpdates

> `/private/var/staged_system_apps/Photos.app/PlugIns/PhotosNotificationsUpdates.appex/PhotosNotificationsUpdates`

```diff

+		<string>com.apple.mobileslideshow</string>

```
### SequoiaTranslator

> `/private/var/staged_system_apps/SequoiaTranslator.app/SequoiaTranslator`

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
+	<string>com.apple.Translate</string>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

```

### 🆕 TVRemoteSettingsAppIntents

> `/private/var/staged_system_apps/TVRemote.app/PlugIns/TVRemoteSettingsAppIntents.appex/TVRemoteSettingsAppIntents`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
	<string>com.apple.Preferences</string>
	<key>com.apple.security.app-sandbox</key>
	<true/>
</dict>
</plist>

```
### TVRemote

> `/private/var/staged_system_apps/TVRemote.app/TVRemote`

```diff

+		<string>group.com.apple.TVRemote</string>

```
### VoiceMemosIntentsExtension

> `/private/var/staged_system_apps/VoiceMemos.app/PlugIns/VoiceMemosIntentsExtension.appex/VoiceMemosIntentsExtension`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.VoiceMemos</string>

```
### VoiceMemosShareExtension

> `/private/var/staged_system_apps/VoiceMemos.app/PlugIns/VoiceMemosShareExtension.appex/VoiceMemosShareExtension`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.VoiceMemos</string>

```
### VoiceMemos

> `/private/var/staged_system_apps/VoiceMemos.app/VoiceMemos`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.VoiceMemos</string>

```
### launchd

> `/sbin/launchd`

```diff

+	<key>com.apple.private.shared-region.config</key>
+	<true/>

```
### BatteryDischargeService

> `/usr/libexec/BatteryDischargeService`

```diff

-	<key>com.apple.powerui.smartcharging</key>
-	<true/>

```
### announced

> `/usr/libexec/announced`

```diff

-	<key>com.apple.coreaudio.LoadDecodersInProcess</key>
-	<true/>

```
### appleaccountd

> `/usr/libexec/appleaccountd`

```diff

+	<key>com.apple.cdp.recovery</key>
+	<true/>

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### appprotectiond

> `/usr/libexec/appprotectiond`

```diff

+		<string>kTCCServiceSiriAccess</string>

+		<string>kTCCServiceSiriAccess</string>

```
### atc

> `/usr/libexec/atc`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### backboardd

> `/usr/libexec/backboardd`

```diff

+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceAll</string>
+	</array>

+		<string>kern.darkboot</string>

```
### batteryintelligenced

> `/usr/libexec/batteryintelligenced`

```diff

+	<key>com.apple.mobileactivationd.spi</key>
+	<true/>

+		<string>com.apple.mobileactivationd</string>

```
### cameracaptured

> `/usr/libexec/cameracaptured`

```diff

+	<key>com.apple.private.audio.client-audit-token-override</key>
+	<true/>

```
### caraccessoryd

> `/usr/libexec/caraccessoryd`

```diff

+	<key>com.apple.private.carkit.statisticsPublisher</key>
+	<true/>

```

### 🆕 chassisplatformhostd

> `/usr/libexec/chassisplatformhostd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.chassisplatformhostd.cpk.gov.remote</key>
	<true/>
	<key>com.apple.private.RemoteServiceDiscovery.compute-platform</key>
	<true/>
	<key>com.apple.private.RemoteServiceDiscovery.device-admin</key>
	<true/>
	<key>com.apple.private.network.management.data</key>
	<true/>
	<key>com.apple.security.iokit-user-client-class</key>
	<array>
		<string>AppleUSBHostDeviceUserClient</string>
		<string>AppleUSBHostInterfaceUserClient</string>
	</array>
</dict>
</plist>

```
### findmydeviced

> `/usr/libexec/findmydeviced`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### frauddefensed

> `/usr/libexec/frauddefensed`

```diff

+	<key>com.apple.private.cloudkit.setEnvironment</key>
+	<true/>

+				<key>TrustKit.Decisioning.TKWalletOrderExtractionDomains</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>

```
### gamecontrollerd

> `/usr/libexec/gamecontrollerd`

```diff

-	<key>com.apple.developer.game-center</key>
-	<true/>

-	<key>com.apple.private.game-center</key>
-	<array>
-		<string>Account</string>
-	</array>

```
### inboxupdaterd

> `/usr/libexec/inboxupdaterd`

```diff

-	<string>Development</string>
+	<string>Production</string>

+	<key>com.apple.mobileactivationd.device-identifiers</key>
+	<true/>
+	<key>com.apple.mobileactivationd.spi</key>
+	<true/>

+	<key>com.apple.private.diagnosticscheckupd.launch</key>
+	<true/>

+	<key>com.apple.private.system-keychain</key>
+	<true/>

+	<key>com.apple.security.attestation.access</key>
+	<true/>

+		<string>com.apple.diagnosticscheckupd</string>

```
### linkd

> `/usr/libexec/linkd`

```diff

+	<key>com.apple.appprotectiond.guard.access</key>
+	<true/>

+	<key>com.apple.private.dmd.policy</key>
+	<true/>

```
### logd

> `/usr/libexec/logd`

```diff

+	<key>com.apple.private.security.storage.LogdPreferencesCache</key>
+	<true/>

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/secureconfig/</string>
+	</array>

```
### mdmd

> `/usr/libexec/mdmd`

```diff

+	<key>com.apple.private.vfs.snapshot</key>
+	<true/>
+	<key>com.apple.private.vfs.snapshot.user</key>
+	<true/>

```
### nexusd

> `/usr/libexec/nexusd`

```diff

+	<key>com.apple.private.xpc.launchd.event-monitor</key>
+	<true/>

```
### rapportd

> `/usr/libexec/rapportd`

```diff

+	<key>com.apple.private.sharing.paired-contacts</key>
+	<true/>

```
### searchpartyd

> `/usr/libexec/searchpartyd`

```diff

+	<key>com.apple.geoanalyticsd.telemetry</key>
+	<true/>

+	<key>com.apple.icloud.searchpartyd.btFinding.access</key>
+	<true/>

+	<key>com.apple.locationd.activity</key>
+	<true/>

+		<string>com.apple.findmydeviced.btfindingsession</string>

```
### securityd

> `/usr/libexec/securityd`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>
+	<key>com.apple.cdp.statemachine</key>
+	<true/>

```
### softposreaderd

> `/usr/libexec/softposreaderd`

```diff

+	<key>com.apple.security.ts.ipc-posix-sem</key>
+	<string>purplebuddy.sentinel</string>

```
### soundanalysisd

> `/usr/libexec/soundanalysisd`

```diff

+		<string>/dev/exfiltration-adc-soundanalys</string>

```
### spotlightknowledged.graph

> `/usr/libexec/spotlightknowledged.graph`

```diff

+	<key>com.apple.private.cascade.donation-requester</key>
+	<true/>

```
### spotlightknowledged.updater

> `/usr/libexec/spotlightknowledged.updater`

```diff

+	<key>com.apple.private.cascade.donation-requester</key>
+	<true/>

```
### symptomsd

> `/usr/libexec/symptomsd`

```diff

+	<key>com.apple.private.iokit.powermanagement.read-assertions</key>
+	<true/>

+		<string>com.apple.iohideventsystem</string>

```
### symptomsd-helper

> `/usr/libexec/symptomsd-helper`

```diff

+	<key>com.apple.private.iokit.powermanagement.read-assertions</key>
+	<true/>

+		<string>com.apple.iohideventsystem</string>

```
### sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

```diff

+	<key>com.apple.private.container.debug</key>
+	<true/>

```

### 🆕 trustdFileHelper

> `/usr/libexec/trustdFileHelper`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.security.storage.SFAnalytics</key>
	<true/>
	<key>com.apple.private.security.storage.trustd</key>
	<true/>
	<key>com.apple.private.security.storage.trustd-private</key>
	<true/>
</dict>
</plist>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-write</key>
+	<array>
+		<string>/private/var/mobile/Library/tvremoted/</string>
+	</array>

-		<string>/Library/Caches/com.apple.HomeKit.configurations/tvremoted/</string>
-		<string>/Library/Caches/com.apple.HomeKit/tvremoted/</string>
+		<string>/Library/Caches/com.apple.HomeKit/com.apple.tvremoted/</string>

-		<string>/Library/tvremoted/</string>

-		<string>IOHIDUserDeviceCreate</string>
-		<string>IOHIDResourceDeviceUserClient</string>
-		<string>IOHIDUserClient</string>

+		<string>IOHIDResourceDeviceUserClient</string>
+		<string>IOHIDUserClient</string>
+		<string>IOHIDUserDeviceCreate</string>

+		<string>com.apple.rapport</string>

+		<string>com.apple.TVRemoteCore</string>

```
### xpcproxy

> `/usr/libexec/xpcproxy`

```diff

+	<key>com.apple.private.shared-region.config</key>
+	<true/>

```
### BTLEServer

> `/usr/sbin/BTLEServer`

```diff

-	<key>keychain-access-groups</key>
-	<array>
-		<string>apple</string>
-	</array>

```
### bluetoothd

> `/usr/sbin/bluetoothd`

```diff

+	<key>com.apple.developer.homekit</key>
+	<true/>

+	<key>com.apple.homekit.private-spi-access</key>
+	<true/>

+	<key>com.apple.private.homekit.beacon-keybag</key>
+	<true/>

+		<string>kTCCServiceWillow</string>

+		<string>com.apple.homed.beacon-keybag</string>

```


### SystemOS

### com.apple.WebKit.GPU

> `/System/Library/ExtensionKit/Extensions/GPUExtension.appex/com.apple.WebKit.GPU`

```diff

+	<key>com.apple.private.sandbox.profile</key>
+	<string>com.apple.WebKit.GPU</string>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### com.apple.WebKit.Networking

> `/System/Library/ExtensionKit/Extensions/NetworkingExtension.appex/com.apple.WebKit.Networking`

```diff

+	<key>com.apple.private.sandbox.profile</key>
+	<string>com.apple.WebKit.Networking</string>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### com.apple.WebKit.WebContent.CaptivePortal

> `/System/Library/ExtensionKit/Extensions/WebContentCaptivePortalExtension.appex/com.apple.WebKit.WebContent.CaptivePortal`

```diff

+	<key>com.apple.private.sandbox.profile</key>
+	<string>com.apple.WebKit.WebContent</string>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### com.apple.WebKit.WebContent.EnhancedSecurity

> `/System/Library/ExtensionKit/Extensions/WebContentEnhancedSecurityExtension.appex/com.apple.WebKit.WebContent.EnhancedSecurity`

```diff

+	<key>com.apple.private.sandbox.profile</key>
+	<string>com.apple.WebKit.WebContent</string>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### com.apple.WebKit.WebContent

> `/System/Library/ExtensionKit/Extensions/WebContentExtension.appex/com.apple.WebKit.WebContent`

```diff

+	<key>com.apple.private.sandbox.profile</key>
+	<string>com.apple.WebKit.WebContent</string>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### AutoFillHelper

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/XPCServices/AutoFillHelper.xpc/AutoFillHelper`

```diff

+		<string>com.apple.mobilesafari</string>

```


### AppOS

### SafariBookmarksSyncAgent

> `/usr/libexec/SafariBookmarksSyncAgent`

```diff

+	<key>com.apple.private.corespotlight.bundleid</key>
+	<string>com.apple.mobilesafari</string>

```
### webbookmarksd

> `/usr/libexec/webbookmarksd`

```diff

+	<key>com.apple.private.biome.read-write</key>
+	<array>
+		<string>Unilog.SafariSearch.Stage</string>
+	</array>

+		<string>com.apple.biome.access.user</string>

```


