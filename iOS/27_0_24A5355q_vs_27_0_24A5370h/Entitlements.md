## 🔑 Entitlements

### filesystem

### AccessorySetupUI

> `/Applications/AccessorySetupUI.app/AccessorySetupUI`

```diff

+	<key>com.apple.QuartzCore.secure-mode</key>
+	<true/>

+		<string>com.apple.SharingServices</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.springboard</string>

+	<key>com.apple.sharing.Client</key>
+	<true/>

```
### ActivityMessagesExtension

> `/Applications/ActivityMessagesApp.app/PlugIns/ActivityMessagesExtension.appex/ActivityMessagesExtension`

```diff

+		<string>com.apple.spaceattributiond</string>

+	<key>com.apple.spaceattribution.private</key>
+	<true/>

```
### AskPermissionUI

> `/Applications/AskPermissionUI.app/AskPermissionUI`

```diff

+	<key>keychain-access-groups</key>
+	<array>
+		<string>apple</string>
+	</array>

```
### AskToUIHost

> `/Applications/AskToUIHost.app/AskToUIHost`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
+	<dict>
+		<key>type</key>
+		<string>bundleID</string>
+		<key>value</key>
+		<string>com.apple.MobileSMS</string>
+	</dict>
+</dict>
+</plist>

```
### AuthorizationPromptService

> `/Applications/AuthorizationPromptService.app/AuthorizationPromptService`

```diff

+	<key>com.apple.QuartzCore.secure-mode</key>
+	<true/>

+	<key>com.apple.frontboardservices.display-layout-monitor</key>
+	<true/>

```
### Campo

> `/Applications/Campo.app/Campo`

```diff

+	<key>com.apple.devicesharing.guest-user-mode-client</key>
+	<true/>

+	<key>com.apple.feedbackd.remote-evaluation</key>
+	<true/>

+	<key>com.apple.private.WebClips.read-write</key>
+	<true/>

+		<string>Intelligence.Usage</string>

+				<string>SiriTranscriptConversation</string>

+	<key>com.apple.private.siriappintentsd.orchestrator</key>
+	<true/>

+		<string>/Media/PhotoData/OutgoingTemp/</string>

+		<string>/Library/Application Support/CampoUIInternal/</string>

+		<string>/Media/PhotoData/PhotoCloudSharingData/Caches/</string>

-		<string>com.apple.siriappintentsd.orchestrator</string>
+		<string>com.apple.private.siriappintentsd.orchestrator</string>

+		<string>com.apple.devicesharing.guestusermodeservice</string>

+		<string>com.apple.feedbackd.centralized-feedback</string>
+		<string>com.apple.iconservices</string>

-	<key>com.apple.siriappintentsd.orchestrator</key>
-	<true/>

-	<key>com.apple.surfboard-prevent-homeui-from-hiding-when-launching</key>
+	<key>com.apple.surfboard.allow-scene-requests-while-backgrounded</key>

+	<key>com.apple.surfboard.force-quit-suppression</key>
+	<true/>

+	<key>com.apple.surfboard.sharing-mode-launch-allowed</key>
+	<true/>

```
### CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

```diff

+			<key>resetTriggers</key>
+			<array>
+				<string>WiFiConnected</string>
+			</array>

+	<key>com.apple.developer.icloud-container-identifiers</key>
+	<array>
+		<string>com.apple.container.HeadBoard</string>
+	</array>

+	<key>com.apple.developer.sensitivecontentanalysis.client</key>
+	<array>
+		<string>analysis</string>
+	</array>

+		<string>BluetoothAddress</string>
+		<string>EthernetMacAddress</string>

+		<string>WifiAddress</string>
+		<string>WifiAddressData</string>

+	<key>com.apple.private.biome.read-write</key>
+	<array>
+		<string>Discoverability.Signals</string>
+	</array>

+	<key>com.apple.private.cloudkit.masquerade</key>
+	<true/>

+	<key>com.apple.private.cloudkit.setEnvironment</key>
+	<true/>

+	<key>com.apple.private.rtcreportingd</key>
+	<true/>

+	<key>com.apple.runningboard.terminateprocess</key>
+	<true/>

+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>

+		<string>com.apple.Accessibility</string>

```
### CompanionViewService

> `/Applications/CompanionViewService.app/CompanionViewService`

```diff

+		<string>kTCCServicePhotos</string>

```
### CredentialSharingUIViewService

> `/Applications/CredentialSharingUIViewService.app/CredentialSharingUIViewService`

```diff

+	<key>com.apple.nfcd.hwmanager</key>
+	<true/>

```
### CustomerEngagementUIService

> `/Applications/CustomerEngagementUIService.app/CustomerEngagementUIService`

```diff

+		<string>com.apple.iconservices</string>
+		<string>com.apple.iconservices.store</string>

```
### Diagnostic-9006

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9006.appex/Diagnostic-9006`

```diff

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+	</array>

+		<string>/private/var/hardware/FactoryData/</string>

```
### Diagnostic-9008

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9008.appex/Diagnostic-9008`

```diff

+		<string>/private/var/hardware/FactoryData/</string>

```
### Diagnostic-9010

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9010.appex/Diagnostic-9010`

```diff

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+	</array>

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/hardware/FactoryData/</string>
+	</array>

```
### Enhanced Logging

> `/Applications/Enhanced Logging.app/Enhanced Logging`

```diff

+	<key>com.apple.developer.associated-domains</key>
+	<array/>

+	<key>com.apple.private.swc.system-app</key>
+	<true/>

```
### FinanceUIService

> `/Applications/FinanceUIService.app/FinanceUIService`

```diff

+	<key>com.apple.cards.all-access</key>
+	<true/>

```
### FindMyRemoteUIService

> `/Applications/FindMyRemoteUIService.app/FindMyRemoteUIService`

```diff

+	<key>com.apple.appleaccount.identity.read</key>
+	<true/>

+		<string>com.apple.aa.identity.xpc</string>

```
### InCallService

> `/Applications/InCallService.app/InCallService`

```diff

+		<string>CommApps.CallIntelligence.CallContextCardsFedStats</string>

+		<string>com.apple.symptom_diagnostics</string>

```
### FaceTimeShareExtension

> `/Applications/InCallService.app/PlugIns/FaceTimeShareExtension.appex/FaceTimeShareExtension`

```diff

+	<key>com.apple.developer.auto-elect-plugin</key>
+	<true/>

-	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<key>com.apple.security.app-sandbox</key>
+	<true/>
+	<key>com.apple.security.files.user-selected.read-write</key>
+	<true/>
+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>

-		<string>com.apple.CloudSharing.SPIHelper-iOS</string>
+		<string>com.apple.CloudSharing.SPIHelper</string>

```
### InputUI

> `/Applications/InputUI.app/InputUI`

```diff

+	<key>com.apple.authentication-services-core.allow-querying-credential-providers</key>
+	<true/>

+		<string>com.apple.AuthenticationServicesCore.AuthenticationServicesAgent</string>

```
### PassbookUISceneService

> `/Applications/PassbookUISceneService.app/PassbookUISceneService`

```diff

+	<key>com.apple.private.applemediaservices</key>
+	<true/>

+		<string>com.apple.xpc.amsaccountsd</string>

+	<key>fairplay-client</key>
+	<integer>87750944</integer>

```
### PassbookUIService

> `/Applications/PassbookUIService.app/PassbookUIService`

```diff

+	<key>com.apple.private.corewifi</key>
+	<true/>

```
### PeerPaymentMessagesExtension

> `/Applications/PassbookUIService.app/PlugIns/PeerPaymentMessagesExtension.appex/PeerPaymentMessagesExtension`

```diff

-	<key>com.apple.modelcatalog.full-access</key>
-	<true/>
-	<key>com.apple.modelmanager.inference</key>
-	<true/>

-	<key>com.apple.private.assets.accessible-asset-types</key>
-	<array>
-		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>
-		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
-	</array>

-	<key>com.apple.private.biome.read-write</key>
-	<array>
-		<string>GenerativeModels.GenerativeFunctions.SystemInstrumentation</string>
-		<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>
-	</array>

-	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
-	<true/>

-	<key>com.apple.privatecloudcompute.admin</key>
-	<true/>

-		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>
-		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
-		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
-		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
-		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
-		<string>/private/var/mobile/Library/com.apple.modelcatalog/sideload/</string>

-		<string>com.apple.modelcatalog.catalog</string>
-		<string>com.apple.biome.access.user</string>
-		<string>com.apple.siri.uaf.service</string>
-		<string>com.apple.mobileasset.autoasset</string>
-		<string>com.apple.mobileassetd.v2</string>
-		<string>com.apple.modelmanager</string>

-	<key>com.apple.security.exception.shared-preference.read-only</key>
-	<array>
-		<string>com.apple.UnifiedAssetFramework</string>
-		<string>com.apple.modelcatalog.ajax</string>
-		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
-		<string>kCFPreferencesAnyApplication</string>
-	</array>

```
### PhotosUIService

> `/Applications/PhotosUIService.app/PhotosUIService`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+		<string>group.com.apple.feedback</string>

+		<string>group.com.apple.feedback</string>

+		<string>/private/var/db/com.apple.countryd/</string>

+		<string>com.apple.CommCenter</string>
+		<string>com.apple.MobileSMS</string>

+		<string>com.apple.natvoc</string>

```
### RemoteiCloudQuotaUI

> `/Applications/RemoteiCloudQuotaUI.app/RemoteiCloudQuotaUI`

```diff

+	<key>com.apple.private.appstorecomponents.small-offer-button</key>
+	<true/>

```
### SIMSetupUIService

> `/Applications/SIMSetupUIService.app/SIMSetupUIService`

```diff

-		<string>public-cellular-plan</string>

+		<string>public-cellular-plan</string>
+		<string>public-esim-qr-code</string>

```
### SafariViewService

> `/Applications/SafariViewService.app/SafariViewService`

```diff

+		<string>/Library/Safari/PasswordBreachStore.plist</string>

```
### Setup

> `/Applications/Setup.app/Setup`

```diff

+		<string>public-esim-qr-code</string>

-	<key>com.apple.private.safefinancing</key>
-	<true/>

```
### SharingViewService

> `/Applications/SharingViewService.app/SharingViewService`

```diff

+	<key>com.apple.nfcd.hwmanager</key>
+	<true/>
+	<key>com.apple.nfcd.session.cardmigration</key>
+	<true/>

+		<string>com.apple.passd.payment</string>

+		<string>com.apple.PassbookUISceneService.remote-ui</string>
+		<string>com.apple.nfcd.hwmanager</string>

+	<key>com.apple.springboard.hardware-button-service.button-associated-hint-view</key>
+	<true/>

+	<key>com.apple.wallet.banner</key>
+	<true/>

```
### SoftwareUpdateUIService

> `/Applications/SoftwareUpdateUIService.app/SoftwareUpdateUIService`

```diff

+	<key>application-identifier</key>
+	<string>com.apple.susuiservice</string>

+	<key>keychain-access-groups</key>
+	<array>
+		<string>apple</string>
+		<string>appleaccount</string>
+		<string>com.apple.certificates</string>
+		<string>com.apple.identities</string>
+	</array>

```
### Spotlight

> `/Applications/Spotlight.app/Spotlight`

```diff

-	<key>com.apple.private.tcc.manager.read.access</key>
+	<key>com.apple.private.tcc.manager.access.read</key>

```

### 🆕 SupportFlowSpotlightIndex

> `/Applications/SupportFlow.app/PlugIns/SupportFlowSpotlightIndex.appex/SupportFlowSpotlightIndex`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.SupportFlow.SpotlightIndexExtension</string>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.tipsd</string>
	</array>
	<key>com.apple.security.hardened-process</key>
	<true/>
	<key>com.apple.security.hardened-process.checked-allocations</key>
	<true/>
	<key>com.apple.tipsd.access</key>
	<true/>
</dict>
</plist>

```
### Tamale

> `/Applications/Tamale.app/Tamale`

```diff

-	<key>com.apple.developer.healthkit</key>
-	<true/>

-	<key>com.apple.private.UIKit.UIScene.allow-host-context-propagation</key>
-	<true/>

-	<key>com.apple.private.health.scene-hosting</key>
-	<true/>
-	<key>com.apple.private.healthkit</key>
-	<true/>
-	<key>com.apple.private.healthkit.authorization_manager</key>
-	<array>
-		<string>read</string>
-		<string>write</string>
-	</array>
-	<key>com.apple.private.healthkit.source.identities</key>
-	<array>
-		<string>com.apple.siri</string>
-	</array>

```
### extensionFilter

> `/Applications/Text Message Filter.app/PlugIns/extensionFilter.appex/extensionFilter`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/MobileAsset/AssetsV2/</string>
+	</array>

```
### WebContentRestrictionsUI

> `/Applications/WebContentRestrictionsUI.app/WebContentRestrictionsUI`

```diff

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>

```
### WidgetRenderer_Activities

> `/Applications/WidgetRenderer_Activities.app/WidgetRenderer_Activities`

```diff

+		<string>kTCCServiceMotion</string>

```
### WidgetRenderer_CarPlay

> `/Applications/WidgetRenderer_CarPlay.app/WidgetRenderer_CarPlay`

```diff

+		<string>kTCCServiceMotion</string>

```
### WidgetRenderer_Default

> `/Applications/WidgetRenderer_Default.app/WidgetRenderer_Default`

```diff

+		<string>kTCCServiceMotion</string>

```
### WidgetRenderer_Snapshots

> `/Applications/WidgetRenderer_Snapshots.app/WidgetRenderer_Snapshots`

```diff

+		<string>kTCCServiceMotion</string>

```
### WidgetRenderer_WatchFaces

> `/Applications/WidgetRenderer_WatchFaces.app/WidgetRenderer_WatchFaces`

```diff

+		<string>kTCCServiceMotion</string>

```
### WritingToolsUIService

> `/Applications/WritingToolsUIService.app/WritingToolsUIService`

```diff

+	<key>com.apple.generativeexperiences.ExternalProviderService</key>
+	<true/>

+		<string>com.apple.generativeexperiences.ExternalProviderService</string>
+		<string>com.apple.generativeexperiences.ExternalProviderTCCManagingXPC</string>

```
### AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

```diff

+	<key>com.apple.private.accessibility.visuals</key>
+	<true/>

-		<string>com.apple.Preferences</string>

+		<string>com.apple.Preferences</string>

```
### PhotosViewService

> `/System/Library/CoreServices/PhotosViewService.app/PhotosViewService`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### SpringBoard

> `/System/Library/CoreServices/SpringBoard.app/SpringBoard`

```diff

+	<key>com.apple.Pasteboard.allowed-metadata-keys</key>
+	<array>
+		<string>SBUIRequiredApplicationBundleIdentifier</string>
+		<string>SBUIPreferredApplicationBundleIdentifier</string>
+		<string>SBUIIgnore</string>
+	</array>

+	<key>com.apple.mkb.usersession.load</key>
+	<true/>

+	<key>com.apple.mkb.usersession.switch</key>
+	<true/>

+		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>
+		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>
+		<string>com.apple.MobileAsset.UAF.IF.Planner</string>
+		<string>com.apple.MobileAsset.UAF.IF.PlannerOverrides</string>
+		<string>com.apple.MobileAsset.UAF.Shortcuts.Generator</string>
+		<string>com.apple.MobileAsset.UAF.Siri.AnswerSynthesis</string>
+		<string>com.apple.MobileAsset.UAF.Siri.DialogAssets</string>
+		<string>com.apple.MobileAsset.UAF.Siri.FindMyConfigurationFiles</string>
+		<string>com.apple.MobileAsset.UAF.Siri.TextToSpeech</string>
+		<string>com.apple.MobileAsset.UAF.Siri.Understanding</string>
+		<string>com.apple.MobileAsset.UAF.Siri.UnderstandingASRHammer</string>
+		<string>com.apple.MobileAsset.UAF.Siri.UnderstandingNLOverrides</string>
+		<string>com.apple.MobileAsset.UAF.Translation.MMAssets</string>

+	<key>com.apple.private.assets.bypass-asset-types-check</key>
+	<true/>

+		<string>com.apple.mobileasset.autoasset</string>

```
### vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

```diff

+		<string>com.apple.TextInput.rdt</string>

+		<string>com.apple.Preferences</string>

```
### ASRFullPayloadCorrection

> `/System/Library/ExtensionKit/Extensions/ASRFullPayloadCorrection.appex/ASRFullPayloadCorrection`

```diff

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.icl</string>
+	</array>

```
### AssetMetrics

> `/System/Library/ExtensionKit/Extensions/AssetMetrics.appex/AssetMetrics`

```diff

+		<string>AssetDelivery.UAF.AssetSetStatus</string>
+		<string>AssetDelivery.UAF.DailyScheduledAssetStatus</string>
+		<string>AssetDelivery.UAF.AssetSetAlterActivity</string>

+				<string>AssetDelivery.UAF.AssetSetStatus</string>
+				<string>AssetDelivery.UAF.DailyScheduledAssetStatus</string>
+				<string>AssetDelivery.UAF.AssetSetAlterActivity</string>

```

### 🆕 BackgroundSecurityImprovementSettingsIntents

> `/System/Library/ExtensionKit/Extensions/BackgroundSecurityImprovementSettingsIntents.appex/BackgroundSecurityImprovementSettingsIntents`

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
### ExclavesInferenceProvider

> `/System/Library/ExtensionKit/Extensions/ExclavesInferenceProvider.appex/ExclavesInferenceProvider`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.UAF.Speech.AutomaticSpeechRecognition</string>
+	</array>

+	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
+	<true/>
+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_Speech_AutomaticSpeechRecognition/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_Speech_AutomaticSpeechRecognition/</string>
+	</array>

```
### FedStatsPluginDynamic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginDynamic.appex/FedStatsPluginDynamic`

```diff

+	<key>com.apple.private.healthkit</key>
+	<true/>
+	<key>com.apple.private.healthkit.read_authorization_bypass</key>
+	<array>
+		<string>HKCharacteristicTypeIdentifierDateOfBirth</string>
+		<string>HKQuantityTypeIdentifierStepCount</string>
+		<string>HKCharacteristicTypeIdentifierBiologicalSex</string>
+		<string>HKQuantityTypeIdentifierVO2Max</string>
+		<string>HKActivitySummaryTypeIdentifier</string>
+	</array>

+		<key>Change-PW-for-Me-Recommendations</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Passwords.SecurityRecommendations</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		<key>FedStats-Safari-Link-Tracking-Protection</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Safari.Navigations</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		<key>Wallet-Order-Extraction</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>TrustKit.Decisioning.TKWalletOrderExtractionDomains</key>
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

+	<key>com.apple.private.healthkit</key>
+	<true/>
+	<key>com.apple.private.healthkit.read_authorization_bypass</key>
+	<array>
+		<string>HKCharacteristicTypeIdentifierDateOfBirth</string>
+		<string>HKQuantityTypeIdentifierStepCount</string>
+		<string>HKCharacteristicTypeIdentifierBiologicalSex</string>
+		<string>HKQuantityTypeIdentifierVO2Max</string>
+		<string>HKActivitySummaryTypeIdentifier</string>
+	</array>

+		<key>Change-PW-for-Me-Recommendations</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Passwords.SecurityRecommendations</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		<key>FedStats-Safari-Link-Tracking-Protection</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Safari.Navigations</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		<key>Wallet-Order-Extraction</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>TrustKit.Decisioning.TKWalletOrderExtractionDomains</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

```
### GPUIExtension

> `/System/Library/ExtensionKit/Extensions/GPUIExtension.appex/GPUIExtension`

```diff

+	<key>com.apple.developer.private-cloud-compute</key>
+	<true/>

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

```
### GenerativePartnerPrototypeExtension

> `/System/Library/ExtensionKit/Extensions/GenerativePartnerPrototypeExtension.appex/GenerativePartnerPrototypeExtension`

```diff

+	<key>com.apple.private.network.system-token-fetch</key>
+	<true/>

+	<key>keychain-access-groups</key>
+	<array>
+		<string>apple</string>
+		<string>com.apple.openai</string>
+	</array>

```

### 🆕 HomeKitNFCBackgroundTagReadingExtension

> `/System/Library/ExtensionKit/Extensions/HomeKitNFCBackgroundTagReadingExtension.appex/HomeKitNFCBackgroundTagReadingExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.nfcd.background.tag.reading.extension.nonui</key>
	<true/>
	<key>com.apple.nfcd.background.tag.reading.extension.urls</key>
	<array>
		<string>X-HM:</string>
		<string>x-hm:</string>
		<string>MT:</string>
		<string>mt:</string>
		<string>CH:</string>
		<string>ch:</string>
	</array>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.homed.xpc.nfc.tag</string>
	</array>
</dict>
</plist>

```
### LighthouseASRReplay

> `/System/Library/ExtensionKit/Extensions/LighthouseASRReplay.appex/LighthouseASRReplay`

```diff

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.icl</string>
+	</array>

```
### ODDFeatureDigestsExtension

> `/System/Library/ExtensionKit/Extensions/ODDFeatureDigestsExtension.appex/ODDFeatureDigestsExtension`

```diff

-	<string>com.apple.ODDFeatureDigestsExtension</string>
+	<string>com.apple.siri.ODDFeatureDigestsExtension</string>
+	<key>com.apple.assistant.settings</key>
+	<true/>
+	<key>com.apple.private.assistant.settings</key>
+	<true/>

-	<string>com.apple.ODDFeatureDigestsExtension</string>
+	<string>com.apple.siri.ODDFeatureDigestsExtension</string>

+	<key>com.apple.private.logging.diagnostic</key>
+	<true/>
+	<key>com.apple.private.logging.stream</key>
+	<true/>

-		<string>com.apple.ODDFeatureDigestsExtension</string>
-		<string>com.apple.poirot.poirot_tool</string>
+		<string>com.apple.siri.ODDFeatureDigestsExtension</string>

+		<string>com.apple.siri.analytics.assistant</string>

+		<string>com.apple.assistant.settings</string>

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.assistant</string>
+		<string>com.apple.assistant.support</string>
+		<string>com.apple.assistant.backedup</string>
+	</array>

-		<string>com.apple.ODDFeatureDigestsExtension</string>
+		<string>com.apple.siri.ODDFeatureDigests.worker</string>

+		<string>com.apple.siri.analytics.assistant</string>
+		<string>com.apple.assistant.settings</string>

+	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.assistant</string>
+		<string>com.apple.assistant.support</string>
+		<string>com.apple.assistant.backedup</string>
+	</array>

-		<string>com.apple.ODDFeatureDigestsExtension</string>
+		<string>com.apple.siri.ODDFeatureDigests.worker</string>

```
### PhotoPicker

> `/System/Library/ExtensionKit/Extensions/PhotoPicker.appex/PhotoPicker`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### PhotosMessagesApp

> `/System/Library/ExtensionKit/Extensions/PhotosMessagesApp.appex/PhotosMessagesApp`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### PhotosPicker

> `/System/Library/ExtensionKit/Extensions/PhotosPicker.appex/PhotosPicker`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### PhotosPosterProvider

> `/System/Library/ExtensionKit/Extensions/PhotosPosterProvider.appex/PhotosPosterProvider`

```diff

+	<key>com.apple.developer.sensitivecontentanalysis.client</key>
+	<array>
+		<string>analysis</string>
+	</array>

+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>

```
### SCARemoteView Appex

> `/System/Library/ExtensionKit/Extensions/SCARemoteView Appex.appex/SCARemoteView Appex`

```diff

+	<key>com.apple.family.ageRange</key>
+	<true/>

+		<string>com.apple.family.ageRange.xpc</string>

+		<string>com.apple.family.ageRange.xpc</string>

```

### 🆕 SearchPartnerInferenceProvider

> `/System/Library/ExtensionKit/Extensions/SearchPartnerInferenceProvider.appex/SearchPartnerInferenceProvider`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.external.searchpartner</string>
	<key>com.apple.private.network.system-token-fetch</key>
	<true/>
	<key>com.apple.private.xpc.launchd.per-user-lookup</key>
	<true/>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.tokengeneration</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.tokengeneration</string>
	</array>
</dict>
</plist>

```
### SiriVideoAppIntents

> `/System/Library/ExtensionKit/Extensions/SiriVideoAppIntents.appex/SiriVideoAppIntents`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.appintents-attribution-override</key>
+	<true/>
+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations</key>
+	<true/>
+</dict>
+</plist>

```
### TGOnDeviceInferenceProviderService

> `/System/Library/ExtensionKit/Extensions/TGOnDeviceInferenceProviderService.appex/TGOnDeviceInferenceProviderService`

```diff

+		<string>AppleIntelligence.Reporting.Invocation.Step</string>

```

### 🆕 AppleThunderboltSAT

> `/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.developer.device-information.user-assigned-device-name</key>
	<true/>
	<key>com.apple.private.kernel.get-kext-info</key>
	<true/>
</dict>
</plist>

```

### 🆕 VTL

> `/System/Library/Extensions/VTLAdapter.kext/PlugIns/VTL.plugin/VTL`

- No entitlements *(yet)*
### appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

```diff

+	<key>com.apple.private.InstallCoordination.allowed</key>
+	<true/>

+		<string>com.apple.installcoordinationd</string>

```
### assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

```diff

-	<key>com.apple.private.cmphoto.decodeallowlist</key>
-	<dict>
-		<key>DICOM</key>
-		<array>
-			<integer>1684237600</integer>
-		</array>
-		<key>HEIF</key>
-		<array>
-			<integer>1635148593</integer>
-			<integer>1752589105</integer>
-			<integer>1635135537</integer>
-			<integer>1634743416</integer>
-			<integer>1634743400</integer>
-			<integer>1634755432</integer>
-			<integer>1634755438</integer>
-			<integer>1634755443</integer>
-			<integer>1634755439</integer>
-			<integer>1634759278</integer>
-			<integer>1634759272</integer>
-			<integer>1634742888</integer>
-			<integer>1634742376</integer>
-			<integer>1634759276</integer>
-			<integer>1936484717</integer>
-			<integer>1835821411</integer>
-			<integer>1785750887</integer>
-		</array>
-		<key>JFIF</key>
-		<array>
-			<integer>1785750887</integer>
-		</array>
-		<key>JPEG-XL</key>
-		<array>
-			<integer>1786276963</integer>
-			<integer>1786276896</integer>
-		</array>
-	</dict>

-	<key>com.apple.private.nsurlsession.set-discretionary-override-value</key>
-	<true/>

```
### BrowserEngineKit.Intermediary

> `/System/Library/Frameworks/BrowserEngineKit.framework/XPCServices/BrowserEngineKit.Intermediary.xpc/BrowserEngineKit.Intermediary`

```diff

-		<string>com.apple.DeviceConfigurationAgent.consumer.async</string>
-		<string>com.apple.DeviceConfigurationAgent.publisher</string>

```
### CoreTelephonyDiagnosticExtension

> `/System/Library/Frameworks/CoreTelephony.framework/PlugIns/CoreTelephonyDiagnosticExtension.appex/CoreTelephonyDiagnosticExtension`

```diff

-	<key>com.apple.security.exception.files.absolute-path.read-only</key>
-	<array>
-		<string>/var/wireless/Library/Databases/</string>
-	</array>

```
### CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

```diff

+	<key>com.apple.locationd.use-wireless-client-info</key>
+	<true/>

+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

```
### CommCenterMobileHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterMobileHelper`

```diff

+		<string>com.apple.CoreRepairCoreXPCService</string>

+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

```
### CommCenterRootHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterRootHelper`

```diff

+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

```
### fileproviderd

> `/System/Library/Frameworks/FileProvider.framework/Support/fileproviderd`

```diff

+	<key>com.apple.private.FileIndexer.client</key>
+	<true/>

+		<string>/private/var/mobile/Library/UserConfigurationProfiles/Truth.plist</string>

```
### FinanceImageProcessingService

> `/System/Library/Frameworks/FinanceKit.framework/XPCServices/FinanceImageProcessingService.xpc/FinanceImageProcessingService`

```diff

+		<string>com.apple.biome.access.user</string>

```
### financed

> `/System/Library/Frameworks/FinanceKit.framework/financed`

```diff

+		<string>FINANCE_RECEIPT_LINKING</string>

```

### 🆕 com.apple.HealthKit.HealthKitTCCNotificationExtension

> `/System/Library/Frameworks/HealthKit.framework/PlugIns/com.apple.HealthKit.HealthKitTCCNotificationExtension.appex/com.apple.HealthKit.HealthKitTCCNotificationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.developer.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_bypass</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_manager</key>
	<array>
		<string>read</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.healthd.server</string>
	</array>
</dict>
</plist>

```
### healthd

> `/System/Library/Frameworks/HealthKit.framework/healthd`

```diff

+	<key>com.apple.private.tcc.manager.access.delete</key>
+	<array>
+		<string>kTCCServiceHealthAccessReminder</string>
+	</array>

+		<string>kTCCServiceHealthAccessReminder</string>

+	<key>com.apple.private.tcc.manager.access.report</key>
+	<array>
+		<string>kTCCServiceHealthAccessReminder</string>
+	</array>

+		<string>com.apple.powerlogd</string>

```
### managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UserConfigurationProfiles/</string>
+	</array>

```

### 🆕 NearFieldPrivateServiceLocation

> `/System/Library/LocationBundles/NearFieldPrivateServiceLocation.bundle/NearFieldPrivateServiceLocation`

- No entitlements *(yet)*

### 🆕 SpotlightIndexingProgressSettings

> `/System/Library/PreferenceBundles/SpotlightIndexingProgressSettings.bundle/SpotlightIndexingProgressSettings`

- No entitlements *(yet)*
### BundledIntentHandler

> `/System/Library/PrivateFrameworks/ActionKit.framework/PlugIns/BundledIntentHandler.appex/BundledIntentHandler`

```diff

+	<key>com.apple.private.corewifi.mac-addr</key>
+	<true/>

```
### agentstored

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/agentstored`

```diff

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.agentsessionstore</string>

+		<string>com.apple.kvsd</string>

```
### AppIntentsRunnerXPCService

> `/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService`

```diff

+	<key>com.apple.private.update-any-appshortcutsprovider</key>
+	<true/>

+		<string>com.apple.linkd.application-service</string>

```
### appstored

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstored`

```diff

+		<string>InternalBuild</string>

```

### 🆕 appleaccounttransparencyd

> `/System/Library/PrivateFrameworks/AppleAccountTransparency.framework/appleaccounttransparencyd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.appleaccounttransparencyd</string>
	<key>com.apple.accounts.appleaccount.fullaccess</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.appleaccounttransparencyd</string>
	<key>com.apple.authkit.client.internal</key>
	<true/>
	<key>com.apple.cdp.telemetry</key>
	<true/>
	<key>com.apple.duet.activityscheduler.allow</key>
	<true/>
	<key>com.apple.private.accounts.allaccounts</key>
	<true/>
	<key>com.apple.private.sandbox.profile:embedded</key>
	<string>temporary-sandbox</string>
	<key>com.apple.private.security.daemon-container</key>
	<true/>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.appleaccounttransparencyd</string>
	</array>
	<key>com.apple.security.hardened-process</key>
	<true/>
	<key>com.apple.security.hardened-process.checked-allocations</key>
	<true/>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.ts.daemon-container</key>
	<true/>
	<key>com.apple.security.ts.tmpdir</key>
	<string>com.apple.appleaccounttransparencyd</string>
	<key>com.apple.transparencyd.aet</key>
	<true/>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.appleaccounttransparency</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### AppleCredentialManagerDaemon

> `/System/Library/PrivateFrameworks/AppleCredentialManager.framework/AppleCredentialManagerDaemon`

```diff

+	<key>com.apple.private.applecredentialmanager.daemon.allow</key>
+	<true/>

```

### 🆕 FakeAPNSServerTests

> `/System/Library/PrivateFrameworks/ApplePushService.framework/FakeAPNSServerTests.xctest/FakeAPNSServerTests`

- No entitlements *(yet)*
### apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

```diff

-	<key>com.apple.private.power.notifications</key>
-	<true/>

+		<string>systemgroup.com.apple.safetyalerts</string>

```
### assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

```diff

+		<string>group.com.apple.assistant.shared.backedup</string>

+		<string>group.com.apple.assistant.shared.backedup</string>

+		<string>com.apple.siri.scda</string>

+	<key>com.apple.siri.scda</key>
+	<true/>

-		<string>SIRI_AUDIO_APP_SELECTION_HOMEACCESSORY</string>

```
### deleted_helper

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper`

```diff

+	<key>com.apple.private.security.datavault.controller</key>
+	<true/>

```
### callintelligenced

> `/System/Library/PrivateFrameworks/CallIntelligence.framework/callintelligenced`

```diff

+	<key>com.apple.TextUnderstanding.process</key>
+	<true/>

+	<key>com.apple.generativeexperiences.agentSessionStore</key>
+	<true/>

+		<string>com.apple.TextUnderstanding.process</string>
+		<string>com.apple.generativeexperiences.agentSessionStore</string>

```
### SetStoreUpdateService

> `/System/Library/PrivateFrameworks/CascadeSets.framework/XPCServices/SetStoreUpdateService.xpc/SetStoreUpdateService`

```diff

+	<key>com.apple.security.ts.mobile-keybag-access</key>
+	<true/>

```
### assistant_cdmd

> `/System/Library/PrivateFrameworks/ContinuousDialogManagerService.framework/assistant_cdmd`

```diff

+	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
+	<true/>

+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_IF_PlannerOverrides/purpose_auto/</string>

```
### analyticsagent

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent`

```diff

+	<key>com.apple.locationd.activity</key>
+	<true/>
+	<key>com.apple.locationd.clearauthorizations</key>
+	<true/>
+	<key>com.apple.locationd.effective_bundle</key>
+	<true/>
+	<key>com.apple.locationd.spectator</key>
+	<true/>
+	<key>com.apple.locationd.status</key>
+	<true/>

+		<string>com.apple.locationd.desktop.agent</string>
+		<string>com.apple.locationd.desktop.registration</string>
+		<string>com.apple.locationd.desktop.synchronous</string>
+		<string>com.apple.locationd.desktop.spi</string>

+	<key>com.apple.security.personal-information.location</key>
+	<true/>

```
### analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

```diff

+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>

```
### com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

```diff

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.icl</string>
+	</array>

```
### CorePrescriptionService

> `/System/Library/PrivateFrameworks/CorePrescription.framework/XPCServices/CorePrescriptionService.xpc/CorePrescriptionService`

```diff

+	<key>com.apple.mkb.usersession.info</key>
+	<true/>

+	<key>com.apple.purplebuddy.budd.access</key>
+	<true/>

+	<key>com.apple.security.exception.iokit-user-client-class</key>
+	<array>
+		<string>AppleKeyStoreUserClient</string>
+	</array>

+		<string>com.apple.mobile.keybagd.xpc</string>
+		<string>com.apple.purplebuddy.budd.xpc</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.musebuddy</string>
+		<string>com.apple.musebuddy.notbackedup</string>
+		<string>com.apple.purplebuddy</string>

```
### corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

```diff

+	<key>com.apple.polaris.client</key>
+	<true/>

+		<string>/Library/Caches/com.apple.speechmaintenanced/ranked_entity_cache/</string>

+		<string>com.apple.polaris.cache</string>

+		<string>com.apple.icl</string>

```
### speechmodeltrainingd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/speechmodeltrainingd`

```diff

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.icl</string>
+	</array>

```
### threadradiod

> `/System/Library/PrivateFrameworks/CoreThreadRadio.framework/threadradiod`

```diff

+		<string>/private/var/db/com.apple.countryd/</string>

+		<string>com.apple.countryd</string>

```
### DTServiceHub

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DTServiceHub`

```diff

+		<string>com.apple.springboard</string>

+	<key>modify-anchor-certificates</key>
+	<true/>

```
### IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

```diff

+	<key>com.apple.private.security.storage.Messages</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/SMS/com.apple.imdpersistence.IMDIndexingThrottleHistory.plist</string>
+	</array>

```
### ScreenTimeDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ScreenTimeDiagnosticExtension.appex/ScreenTimeDiagnosticExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### EnergyKitService

> `/System/Library/PrivateFrameworks/EnergyKitInternal.framework/XPCServices/EnergyKitService.xpc/EnergyKitService`

```diff

+		<string>UniqueDeviceID</string>

+	<key>com.apple.system.diagnostics.iokit-properties</key>
+	<true/>

```
### DraftingExtension-iOS

> `/System/Library/PrivateFrameworks/Feedback.framework/PlugIns/DraftingExtension-iOS.appex/DraftingExtension-iOS`

```diff

+	<key>com.apple.private.siriappintentsd.orchestrator</key>
+	<true/>

-	<key>com.apple.siriappintentsd.orchestrator</key>
-	<true/>

```

### 🆕 FileBrowsingPathResolver

> `/System/Library/PrivateFrameworks/FileBrowsingServices.framework/XPCServices/FileBrowsingPathResolver.xpc/FileBrowsingPathResolver`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.FileBrowsingServices.PathResolver</string>
	<key>com.apple.application-identifier</key>
	<string>com.apple.FileBrowsingServices.PathResolver</string>
	<key>com.apple.developer.icloud-container-identifiers</key>
	<array>
		<string>com.apple.CloudDocs</string>
	</array>
	<key>com.apple.fileprovider.enumerate</key>
	<true/>
	<key>com.apple.fileprovider.fetch-url</key>
	<true/>
	<key>com.apple.private.MobileContainerManager.lookup</key>
	<dict>
		<key>appGroup</key>
		<array>
			<string>group.com.apple.FileProvider.LocalStorage</string>
			<string>group.com.apple.FileProvider.DomainCaching</string>
		</array>
	</dict>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.librarian.unrestricted-container-access</key>
	<true/>
	<key>com.apple.private.sandbox.profile:embedded</key>
	<string>temporary-sandbox</string>
	<key>com.apple.private.security.no-container</key>
	<true/>
	<key>com.apple.private.security.storage.FileProvider</key>
	<true/>
	<key>com.apple.private.security.storage.MobileDocuments</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>group.com.apple.FileProvider.LocalStorage</string>
		<string>group.com.apple.FileProvider.DomainCaching</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/Mobile Documents/</string>
		<string>/Library/CloudStorage/</string>
		<string>/Library/LiveFiles/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.FileProvider</string>
		<string>com.apple.fileproviderd</string>
		<string>com.apple.FileCoordination</string>
		<string>com.apple.CoreServices.coreservicesd</string>
		<string>com.apple.coreservices.launchservicesd</string>
		<string>com.apple.coreservices.quarantine-resolver</string>
		<string>com.apple.lsd.mapdb</string>
		<string>com.apple.lsd.modifydb</string>
		<string>com.apple.bird</string>
		<string>com.apple.containermanagerd</string>
		<string>com.apple.SystemConfiguration.configd</string>
		<string>com.apple.FSEvents</string>
		<string>com.apple.iconservices</string>
		<string>com.apple.filesystems.fskitd</string>
		<string>com.apple.diskarbitrationd</string>
		<string>com.apple.mobile.keybagd.xpc</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### FitnessIntelligenceInferenceService

> `/System/Library/PrivateFrameworks/FitnessIntelligenceDaemonCore.framework/XPCServices/FitnessIntelligenceInferenceService.xpc/FitnessIntelligenceInferenceService`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/generativeexperiencesd`

```diff

+	<key>com.apple.private.mobileinstall.allowedSPI</key>
+	<array>
+		<string>GetSystemAppMigrationStatus</string>
+	</array>

+		<string>/private/var/installd/Library/MobileInstallation/</string>

+		<string>com.apple.mobile.installd</string>
+		<string>com.apple.mobile.usermanagerd.xpc</string>

+		<string>com.apple.mobile.installation</string>

```
### homeenergyd

> `/System/Library/PrivateFrameworks/HomeEnergyDaemon.framework/Support/homeenergyd`

```diff

+		<string>UniqueDeviceID</string>

+	<key>com.apple.system.diagnostics.iokit-properties</key>
+	<true/>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Library/Caches/com.apple.AppleMediaServices/sap-setup-cert.txt</string>
+		<string>/Library/Caches/com.apple.AppleMediaServices/Metrics/</string>
+		<string>/Library/Caches/com.apple.AppleMediaServices/PersistedBags/</string>
+		<string>/Library/com.apple.AppleMediaServices/Metrics/</string>
+		<string>/Library/com.apple.AppleMediaServices/PersistedBags/</string>
+	</array>

```
### IDSBlastDoorService

> `/System/Library/PrivateFrameworks/IDSBlastDoorSupport.framework/XPCServices/IDSBlastDoorService.xpc/IDSBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

```diff

+		<string>com.apple.asktod</string>

+	<key>com.apple.asktod</key>
+	<true/>

```
### IMDPersistenceAgent

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/XPCServices/IMDPersistenceAgent.xpc/IMDPersistenceAgent`

```diff

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### intelligencecontextd

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd`

```diff

+		<string>com.apple.linkd.mediator</string>

+		<string>com.apple.linkd.mediator</string>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd`

```diff

+	<key>com.apple.CommCenter.fine-grained</key>
+	<array>
+		<string>cellular-plan</string>
+		<string>internal</string>
+		<string>notify-all</string>
+		<string>spi</string>
+		<string>data-usage</string>
+		<string>identity</string>
+		<string>phone</string>
+		<string>dm</string>
+	</array>

+	<key>com.apple.fileprovider.fetch-url</key>
+	<true/>

+	<key>com.apple.linkd.registry</key>
+	<true/>

+	<key>com.apple.private.generativesearch.client.search</key>
+	<true/>

-	<dict/>
+	<dict>
+		<key>Dormancy</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Dormancy.Feature.UserInteraction</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

+	<key>com.apple.private.memorystatus</key>
+	<true/>

+	<key>com.apple.runningboard.assertions.siri</key>
+	<true/>

+	<key>com.apple.runningboard.process-state</key>
+	<true/>

+		<string>com.apple.linkd.extension</string>
+		<string>com.apple.linkd.mediator</string>

+		<string>com.apple.FileProvider</string>

+	<key>com.apple.security.exception.sysctl.read-only</key>
+	<array>
+		<string>kern.memorystatus_vm_pressure_level</string>
+	</array>

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>
+	<key>com.apple.springboard.openurlinbackground</key>
+	<true/>

+	<key>vm-pressure-level</key>
+	<true/>

```
### lockdownmoded

> `/System/Library/PrivateFrameworks/LockdownMode.framework/lockdownmoded`

```diff

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.lockdownmoded.contact-exemptions</string>
+	</array>

```
### MapsBlastDoorService

> `/System/Library/PrivateFrameworks/MapsBlastDoorSupport.framework/XPCServices/MapsBlastDoorService.xpc/MapsBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### mediaanalysisd

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd`

```diff

+	<key>com.apple.modelmanager.query</key>
+	<true/>

+	<key>com.apple.private.biome.read-only</key>
+	<array>
+		<string>App.Intent</string>
+	</array>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>

+		<string>com.apple.intents.intents-helper</string>

```
### mediaanalysisd-service

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd-service`

```diff

+	<key>com.apple.modelmanager.query</key>
+	<true/>

+	<key>com.apple.private.biome.read-only</key>
+	<array>
+		<string>App.Intent</string>
+	</array>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>

+		<string>com.apple.intents.intents-helper</string>

```
### MediaAnalysisBlastDoorService

> `/System/Library/PrivateFrameworks/MediaAnalysisBlastDoorSupport.framework/XPCServices/MediaAnalysisBlastDoorService.xpc/MediaAnalysisBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### com.apple.photos.ImageConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.ImageConversionService.xpc/com.apple.photos.ImageConversionService`

```diff

-	<key>com.apple.private.cmphoto.decodeallowlist</key>
-	<dict>
-		<key>DICOM</key>
-		<array>
-			<integer>1684237600</integer>
-		</array>
-		<key>HEIF</key>
-		<array>
-			<integer>1635148593</integer>
-			<integer>1752589105</integer>
-			<integer>1635135537</integer>
-			<integer>1634743416</integer>
-			<integer>1634743400</integer>
-			<integer>1634755432</integer>
-			<integer>1634755438</integer>
-			<integer>1634755443</integer>
-			<integer>1634755439</integer>
-			<integer>1634759278</integer>
-			<integer>1634759272</integer>
-			<integer>1634742888</integer>
-			<integer>1634742376</integer>
-			<integer>1634759276</integer>
-			<integer>1936484717</integer>
-			<integer>1835821411</integer>
-			<integer>1785750887</integer>
-		</array>
-		<key>JFIF</key>
-		<array>
-			<integer>1785750887</integer>
-		</array>
-		<key>JPEG-XL</key>
-		<array>
-			<integer>1786276963</integer>
-			<integer>1786276896</integer>
-		</array>
-	</dict>

```
### mstreamd

> `/System/Library/PrivateFrameworks/MediaStream.framework/Support/mstreamd`

```diff

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

```
### HubbleBlastDoorService

> `/System/Library/PrivateFrameworks/MessagesBlastDoorSupport.framework/XPCServices/HubbleBlastDoorService.xpc/HubbleBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

+		<string>com.apple.gpumemd.check_in_request</string>

```
### MessagesAirlockService

> `/System/Library/PrivateFrameworks/MessagesBlastDoorSupport.framework/XPCServices/MessagesAirlockService.xpc/MessagesAirlockService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### MessagesBlastDoorService

> `/System/Library/PrivateFrameworks/MessagesBlastDoorSupport.framework/XPCServices/MessagesBlastDoorService.xpc/MessagesBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### UnknownSendersBlastDoorService

> `/System/Library/PrivateFrameworks/MessagesBlastDoorSupport.framework/XPCServices/UnknownSendersBlastDoorService.xpc/UnknownSendersBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### medialibraryd

> `/System/Library/PrivateFrameworks/MusicLibrary.framework/Support/medialibraryd`

```diff

+		<string>com.apple.NanoMusic</string>

```
### nanosystemsettingsd

> `/System/Library/PrivateFrameworks/NanoSystemSettings.framework/nanosystemsettingsd`

```diff

+	<key>com.apple.nanoregistry.F47B90E6-F2D5-49D0-A8F2-C880AA3FED19</key>
+	<true/>

```

### 🆕 NFReportingService

> `/System/Library/PrivateFrameworks/NearFieldPrivateServices.framework/XPCServices/NFReportingService.xpc/NFReportingService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.authkit.client.private</key>
	<true/>
	<key>com.apple.mobileactivationd.device-identifiers</key>
	<true/>
	<key>com.apple.mobileactivationd.spi</key>
	<true/>
</dict>
</plist>

```
### searchtoold

> `/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold`

```diff

+	<key>com.apple.private.network.system-token-fetch</key>
+	<true/>

+		<string>/private/var/mobile/tmp/com.apple.searchtoold/</string>

+		<string>com.apple.networkserviceproxy.fetch-token</string>

+		<string>com.apple.networkserviceproxy.fetch-token</string>

```
### amsondevicestoraged

> `/System/Library/PrivateFrameworks/OnDeviceStorage.framework/Support/amsondevicestoraged`

```diff

+		<string>com.apple.spaceattributiond</string>

+	<key>com.apple.spaceattribution.private</key>
+	<true/>

```
### com.apple.PerformanceTrace.PerformanceTraceService

> `/System/Library/PrivateFrameworks/PerformanceTrace.framework/XPCServices/com.apple.PerformanceTrace.PerformanceTraceService.xpc/com.apple.PerformanceTrace.PerformanceTraceService`

```diff

+	<key>com.apple.private.AppleProcessorTrace.Trace</key>
+	<true/>

+	<key>com.apple.private.kernel.get-kernel-info</key>
+	<true/>

+		<string>AppleProcessorTraceUserClient</string>
+		<string>RTBuddyUserClient</string>

+	<key>com.apple.system-task-ports.read</key>
+	<true/>

```
### remotemanagementd

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/remotemanagementd`

```diff

+	<key>com.apple.private.security.storage.ManagedConfiguration</key>
+	<true/>

```
### SESDiagnosticExtension

> `/System/Library/PrivateFrameworks/SEService.framework/PlugIns/SESDiagnosticExtension.appex/SESDiagnosticExtension`

```diff

+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.seserviced</string>
+		<string>com.apple.MobileBluetooth.debug</string>
+	</array>

```
### ScreenTimeSettingsAgent

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsAgent`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-write</key>
+	<array>
+		<string>/private/var/tmp/ScreenTimeDiagnostics/</string>
+	</array>

```
### searchd

> `/System/Library/PrivateFrameworks/Search.framework/searchd`

```diff

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### servicesintelligenced

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/servicesintelligenced`

```diff

+	<key>application-identifier</key>
+	<string>com.apple.servicesintelligenced</string>
+	<key>com.apple.application-identifier</key>
+	<string>com.apple.servicesintelligenced</string>
+	<key>com.apple.developer.healthkit.background-delivery</key>
+	<true/>

+	<key>com.apple.private.healthkit</key>
+	<true/>
+	<key>com.apple.private.healthkit.read_authorization_bypass</key>
+	<array>
+		<string>HKWorkoutTypeIdentifier</string>
+	</array>

+		<string>com.apple.healthd.server</string>

```
### fitcored

> `/System/Library/PrivateFrameworks/SeymourServices.framework/fitcored`

```diff

+	<key>com.apple.private.security.daemon-container</key>
+	<true/>

```
### AirDropAlertUI

> `/System/Library/PrivateFrameworks/Sharing.framework/PlugIns/AirDropAlertUI.appex/AirDropAlertUI`

```diff

-	<key>com.apple.private.security.no-sandbox</key>
-	<true/>

-	<array>
-		<string>/private/var/mobile/Containers/Data/PluginKitPlugin/</string>
-		<string>/private/</string>
-		<string>/</string>
-	</array>
+	<array/>

```
### siriappintentsd

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/siriappintentsd`

```diff

+		<string>SessionResumptionEventBundle</string>
+		<string>SecurityValidationEvent</string>

```
### sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

```diff

+		<string>com.apple.mediaremoted.xpc</string>

```
### SiriHeadlessService

> `/System/Library/PrivateFrameworks/SiriVOX.framework/SiriHeadlessService`

```diff

+	<key>com.apple.assistantd.odeon-remote</key>
+	<true/>

+	<key>com.apple.private.homekit</key>
+	<true/>

+		<string>com.apple.assistantd.odeon-remote</string>
+		<string>com.apple.siri.audiopowerupdate.xpc</string>

+	<key>com.apple.siri.audiopowerupdate.xpc</key>
+	<true/>

```
### sleepd

> `/System/Library/PrivateFrameworks/SleepDaemon.framework/sleepd`

```diff

+		<string>/private/var/mobile/Library/UserConfigurationProfiles/EffectiveUserSettings.plist</string>
+		<string>/private/var/mobile/Library/UserConfigurationProfiles/Truth.plist</string>

```
### tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

```diff

+	<key>com.apple.developer.healthkit</key>
+	<true/>

```
### TelephonyBlastDoorService

> `/System/Library/PrivateFrameworks/TelephonyBlastDoorSupport.framework/XPCServices/TelephonyBlastDoorService.xpc/TelephonyBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

+		<string>CommApps.CallIntelligence.CallContextCardsFedStats</string>

+		<string>/Library/UserConfigurationProfiles/EffectiveUserSettings.plist</string>

```
### ThumbnailsBlastDoorService

> `/System/Library/PrivateFrameworks/ThumbnailsBlastDoorSupport.framework/XPCServices/ThumbnailsBlastDoorService.xpc/ThumbnailsBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### useractivityd

> `/System/Library/PrivateFrameworks/UserActivity.framework/Agents/useractivityd`

```diff

+		<string>/Library/UserConfigurationProfiles/EffectiveUserSettings.plist</string>

```
### vmd

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/vmd`

```diff

+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

```
### siriactionsd

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd`

```diff

+		<string>App.InFocus</string>

+				<key>App.InFocus</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

```
### WalletBlastDoorService

> `/System/Library/PrivateFrameworks/WalletBlastDoorSupport.framework/XPCServices/WalletBlastDoorService.xpc/WalletBlastDoorService`

```diff

+		<string>com.apple.caulk.alloc.rtdump</string>

```
### ShortcutsIntents

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/PlugIns/ShortcutsIntents.appex/ShortcutsIntents`

```diff

+	<key>com.apple.private.corewifi.mac-addr</key>
+	<true/>

```
### BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

```diff

+	<key>com.apple.private.corewifi.mac-addr</key>
+	<true/>

```
### RemoteiCloudQuotaUI

> `/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/Extensions/RemoteiCloudQuotaUI.appex/RemoteiCloudQuotaUI`

```diff

+	<key>com.apple.private.appstorecomponents.small-offer-button</key>
+	<true/>

```
### itunesstored

> `/System/Library/PrivateFrameworks/iTunesStore.framework/Support/itunesstored`

```diff

+	<key>com.apple.odi.internal</key>
+	<true/>

```

### 🆕 ReplayKitScreenRecordingAttribution

> `/System/Library/SystemStatus/Bundles/Attribution/ReplayKitScreenRecordingAttribution.bundle/ReplayKitScreenRecordingAttribution`

- No entitlements *(yet)*
### kbd

> `/System/Library/TextInput/kbd`

```diff

+		<string>com.apple.frontboard.systemappservices</string>

+	<key>com.apple.springboard.remote-alert</key>
+	<true/>

```

### 🆕 com.apple.Dataclass.Siri

> `/System/Library/iCloudSettings/com.apple.Dataclass.Siri.bundle/com.apple.Dataclass.Siri`

- No entitlements *(yet)*
### AppleVisionProApp

> `/private/var/staged_system_apps/AppleVisionProApp.app/AppleVisionProApp`

```diff

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.visionproapp.kvs</string>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+		<string>com.apple.tv</string>

```
### Books

> `/private/var/staged_system_apps/Books.app/Books`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+	<key>com.apple.nanoregistry.F47B90E6-F2D5-49D0-A8F2-C880AA3FED19</key>
+	<true/>

+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>Dormancy</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Dormancy.Feature.RemoteUserInteraction</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### Camera

> `/private/var/staged_system_apps/Camera.app/Camera`

```diff

-	<key>com.apple.private.healthkit.authorization_bypass</key>
-	<true/>

-	<key>com.apple.private.healthkit.source.default</key>
-	<string>com.apple.Health</string>

+		<string>com.apple.camera</string>

-	<key>com.apple.springboard.private.action-button-events</key>
-	<true/>

+	<key>com.apple.tailspin.dump-output</key>
+	<true/>

+		<string>access-call-capabilities</string>
+		<string>access-call-providers</string>

```
### LockScreenCamera

> `/private/var/staged_system_apps/Camera.app/Extensions/LockScreenCamera.appex/LockScreenCamera`

```diff

-	<key>com.apple.private.healthkit.authorization_bypass</key>
-	<true/>

-	<key>com.apple.private.healthkit.source.default</key>
-	<string>com.apple.Health</string>

+		<string>com.apple.camera</string>

-	<key>com.apple.springboard.private.action-button-events</key>
-	<true/>

+	<key>com.apple.tailspin.dump-output</key>
+	<true/>

+		<string>access-call-capabilities</string>
+		<string>access-call-providers</string>

```
### Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

```diff

+	<key>com.apple.communicationtrustd</key>
+	<array>
+		<string>read</string>
+		<string>write</string>
+	</array>

+		<string>com.apple.communicationtrustd.service</string>

+		<string>com.apple.CommunicationTrust</string>

```
### Files

> `/private/var/staged_system_apps/Files.app/Files`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.DocumentsApp</string>

```
### FindMy

> `/private/var/staged_system_apps/FindMy.app/FindMy`

```diff

+	<key>com.apple.appleaccount.identity.read</key>
+	<true/>

+		<string>com.apple.aa.identity.xpc</string>

```
### Home

> `/private/var/staged_system_apps/Home.app/Home`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.Home</string>

+		<string>com.apple.CoreGraphics.CGPDFService</string>

+		<string>com.apple.videoconference.camera</string>

+		<string>com.apple.CoreGraphics.CGPDFService</string>

+		<string>com.apple.videoconference.camera</string>

```
### HomeWidget

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.Home</string>

```
### HomeWidgetLockScreen

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidgetLockScreen.appex/HomeWidgetLockScreen`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.Home</string>

```
### Image Playground

> `/private/var/staged_system_apps/Image Playground.app/Image Playground`

```diff

+	<key>com.apple.developer.private-cloud-compute</key>
+	<true/>

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

```
### Journal

> `/private/var/staged_system_apps/Journal.app/Journal`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

```
### MagnifierExtension

> `/private/var/staged_system_apps/Magnifier.app/Extensions/MagnifierExtension.appex/MagnifierExtension`

```diff

+		<string>com.apple.coremedia.cameraviewfinder</string>
+		<string>com.apple.biome.access.user</string>
+		<string>com.apple.extensionkitservice</string>
+		<string>com.apple.feedbackd.centralized-feedback</string>
+		<string>com.apple.inputservice.keyboardui</string>
+		<string>com.apple.inputservice.input-ui-host</string>
+		<string>com.apple.UIKit.KeyboardManagement.hosted</string>
+		<string>com.apple.TextInput</string>

```
### MobileMail

> `/private/var/staged_system_apps/MobileMail.app/MobileMail`

```diff

+		<string>com.apple.biome.compute.source.user</string>

```
### NotesAppMigrationExtension

> `/private/var/staged_system_apps/MobileNotes.app/Extensions/NotesAppMigrationExtension.appex/NotesAppMigrationExtension`

```diff

+	<key>com.apple.rootless.storage.shortcuts</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Library/Shortcuts/</string>
+	</array>
+	<key>com.apple.shortcuts.stepwise-execution</key>
+	<true/>
+	<key>com.apple.shortcuts.variable-injection</key>
+	<true/>
+	<key>com.apple.siri.VoiceShortcuts.xpc</key>
+	<true/>

```
### MobileNotes

> `/private/var/staged_system_apps/MobileNotes.app/MobileNotes`

```diff

+	<key>com.apple.private.appintents-bundle-absolute-paths</key>
+	<array>
+		<string>/AppleInternal/Library/Frameworks/ContextStagingIntents.framework</string>
+	</array>

```
### com.apple.mobilenotes.QuickLookExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.QuickLookExtension.appex/com.apple.mobilenotes.QuickLookExtension`

```diff

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### MessagesAssistantExtension

> `/private/var/staged_system_apps/MobileSMS.app/PlugIns/MessagesAssistantExtension.appex/MessagesAssistantExtension`

```diff

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### MobileSafari

> `/private/var/staged_system_apps/MobileSafari.app/MobileSafari`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>
+		<string>/Library/Safari/PasswordBreachStore.plist</string>

```

### 🆕 SafariActionExtension

> `/private/var/staged_system_apps/MobileSafari.app/PlugIns/SafariActionExtension.appex/SafariActionExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
</dict>
</plist>

<!-- Launch Constraints (Parent) -->
{
  "appl": 1,
  "ccat": 0,
  "comp": 1,
  "reqs": {
    "is-init-proc": true
  },
  "vers": 1
}

```

### 🆕 SafariShareExtension

> `/private/var/staged_system_apps/MobileSafari.app/PlugIns/SafariShareExtension.appex/SafariShareExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
</dict>
</plist>

<!-- Launch Constraints (Parent) -->
{
  "appl": 1,
  "ccat": 0,
  "comp": 1,
  "reqs": {
    "is-init-proc": true
  },
  "vers": 1
}

```
### Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

```diff

-	<key>com.apple.modelcatalog.full-access</key>
-	<true/>
-	<key>com.apple.modelmanager.inference</key>
-	<true/>

-		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>
-		<string>com.apple.MobileAsset.UAF.FM.Overrides</string>

-		<string>GenerativeModels.GenerativeFunctions.SystemInstrumentation</string>
-		<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>

-	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>
-	<true/>

-	<key>com.apple.privatecloudcompute.admin</key>
-	<true/>

-		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
-		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>
-		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
-		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
-		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_GenerativeModels/</string>
-		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_FM_Overrides/</string>
-		<string>/private/var/mobile/Library/com.apple.modelcatalog/sideload/</string>

-		<string>com.apple.modelcatalog.catalog</string>
-		<string>com.apple.biome.access.user</string>
-		<string>com.apple.siri.uaf.service</string>
-		<string>com.apple.mobileasset.autoasset</string>
-		<string>com.apple.mobileassetd.v2</string>
-		<string>com.apple.modelmanager</string>

-		<string>com.apple.UnifiedAssetFramework</string>
-		<string>com.apple.modelcatalog.ajax</string>
-		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
-		<string>kCFPreferencesAnyApplication</string>

```
### Passwords

> `/private/var/staged_system_apps/Passwords.app/Passwords`

```diff

+		<string>Passwords.SecurityRecommendations</string>

+	<key>com.apple.private.personas.no.inherit</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/Safari/PasswordBreachStore.plist</string>
+	</array>

```
### Photos

> `/private/var/staged_system_apps/Photos.app/Photos`

```diff

-	<key>com.apple.private.cmphoto.decodeallowlist</key>
-	<dict>
-		<key>DICOM</key>
-		<array>
-			<integer>1684237600</integer>
-		</array>
-		<key>HEIF</key>
-		<array>
-			<integer>1635148593</integer>
-			<integer>1752589105</integer>
-			<integer>1635135537</integer>
-			<integer>1634743416</integer>
-			<integer>1634743400</integer>
-			<integer>1634755432</integer>
-			<integer>1634755438</integer>
-			<integer>1634755443</integer>
-			<integer>1634755439</integer>
-			<integer>1634759278</integer>
-			<integer>1634759272</integer>
-			<integer>1634742888</integer>
-			<integer>1634742376</integer>
-			<integer>1634759276</integer>
-			<integer>1936484717</integer>
-			<integer>1835821411</integer>
-			<integer>1785750887</integer>
-		</array>
-		<key>JFIF</key>
-		<array>
-			<integer>1785750887</integer>
-		</array>
-		<key>JPEG-XL</key>
-		<array>
-			<integer>1786276963</integer>
-			<integer>1786276896</integer>
-		</array>
-	</dict>

```
### Podcasts

> `/private/var/staged_system_apps/Podcasts.app/Podcasts`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>243LU875E5.com.apple.podcasts</string>

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>SerialNumber</string>
+		<string>UniqueDeviceID</string>
+	</array>

+	<key>com.apple.private.fairplay.FPDI</key>
+	<dict>
+		<key>capabilities</key>
+		<array>
+			<integer>4014732562</integer>
+		</array>
+		<key>client-identifier</key>
+		<string>com.apple.podcasts</string>
+	</dict>

+		<string>com.apple.fairplaydeviceidentityd</string>

+		<string>com.apple.fairplaydeviceidentityd</string>

```
### Shortcuts

> `/private/var/staged_system_apps/Shortcuts.app/Shortcuts`

```diff

+		<string>com.apple.toolkitd.xpc</string>

+	<key>com.apple.toolkit.request-immediate-indexing.allow</key>
+	<true/>
+	<key>com.apple.toolkit.request-reindex.allow</key>
+	<true/>

```

### 🆕 TVRemoteIntents

> `/private/var/staged_system_apps/TVRemote.app/PlugIns/TVRemoteIntents.appex/TVRemoteIntents`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.QuartzCore.secure-mode</key>
	<true/>
	<key>com.apple.UIKit.vends-view-services</key>
	<true/>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.frontboard.systemappservices</string>
		<string>com.apple.tvremotecore.xpc</string>
	</array>
	<key>com.apple.sharing.Client</key>
	<true/>
	<key>com.apple.springboard.activateRemoteAlert</key>
	<true/>
	<key>com.apple.springboard.launchapplications</key>
	<true/>
	<key>com.apple.springboard.lockScreenContentAssertion</key>
	<true/>
	<key>com.apple.springboard.remote-alert</key>
	<true/>
	<key>com.apple.wifi.manager-access</key>
	<true/>
</dict>
</plist>

```

### 🆕 TVRemoteWidget

> `/private/var/staged_system_apps/TVRemote.app/PlugIns/TVRemoteWidget.appex/TVRemoteWidget`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.TVRemoteApp</string>
</dict>
</plist>

```

### 🆕 BatteryDischargeService

> `/usr/libexec/BatteryDischargeService`

- No entitlements *(yet)*
### NANDTaskScheduler

> `/usr/libexec/NANDTaskScheduler`

```diff

+	<key>com.apple.private.apfs.get-graft-info</key>
+	<true/>

```
### PowerUIAgent

> `/usr/libexec/PowerUIAgent`

```diff

+	<key>com.apple.microlocation.connection</key>
+	<true/>

```
### airplayd

> `/usr/libexec/airplayd`

```diff

-		<string>com.apple.MediaGroups.daemon</string>

```
### aned

> `/usr/libexec/aned`

```diff

+	<key>com.apple.runningboard.process-state</key>
+	<true/>

```
### aonsensed

> `/usr/libexec/aonsensed`

```diff

-	<key>com.apple.polaris.client</key>
-	<true/>

-		<string>com.apple.polaris.daemon_default</string>
-		<string>com.apple.polaris.systemgraph_v2</string>

-		<string>com.apple.polaris.cache</string>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### applekeystored

> `/usr/libexec/applekeystored`

```diff

-	<key>com.apple.rootless.datavault.controller.internal</key>
+	<key>com.apple.rootless.install</key>

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### arkitd

> `/usr/libexec/arkitd`

```diff

-	<key>com.apple.polaris.client</key>
-	<true/>
-	<key>com.apple.polaris.consumer.all-streams</key>
-	<true/>
-	<key>com.apple.polaris.producer.all-streams</key>
-	<true/>

-	<key>com.apple.private.avfoundation.background-camera-access</key>
-	<true/>
-	<key>com.apple.private.avfoundation.capture.allow</key>
-	<true/>
-	<key>com.apple.private.avfoundation.capture.nonstandard-client.allow</key>
-	<true/>

-	<key>com.apple.private.tcc.allow</key>
-	<array>
-		<string>kTCCServiceCamera</string>
-		<string>kTCCServiceMicrophone</string>
-	</array>
-	<key>com.apple.security.exception.mach-lookup.global-name</key>
-	<array>
-		<string>com.apple.coremedia.capturesource</string>
-	</array>
-	<key>com.apple.security.exception.shared-preference.read-only</key>
-	<array>
-		<string>com.apple.coremedia</string>
-		<string>com.apple.avfoundation</string>
-		<string>com.apple.coreaudio</string>
-		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
-	</array>
-	<key>com.apple.security.iokit-user-client-class</key>
-	<array>
-		<string>AGXDeviceUserClient</string>
-		<string>H11ANEInDirectPathClient</string>
-		<string>IOSurfaceAcceleratorClient</string>
-		<string>IOSurfaceRootUserClient</string>
-	</array>

```
### asktod

> `/usr/libexec/asktod`

```diff

+		<string>AskToBuy</string>

```
### audiomxd

> `/usr/libexec/audiomxd`

```diff

-	<key>com.apple.MediaGroups.client</key>
-	<true/>
-	<key>com.apple.MediaGroups.groups</key>
-	<array>
-		<string>com.apple.media-group.solo-HomePodAccessory</string>
-		<string>com.apple.media-group.solo-SpeakerAccessory</string>
-		<string>com.apple.media-group.solo-AudioReceiverAccessory</string>
-		<string>com.apple.media-group.PSG</string>
-		<string>com.apple.media-group.media-system</string>
-		<string>com.apple.media-group.room</string>
-	</array>

-	<key>com.apple.coreaudio.CanRecordPastData</key>
-	<true/>
-	<key>com.apple.coreaudio.CanRecordWithoutSessionActivation</key>
-	<true/>

-		<string>com.apple.MediaGroups.daemon</string>

```
### batteryintelligenced

> `/usr/libexec/batteryintelligenced`

```diff

+	<key>com.apple.private.smcsensor.user-access</key>
+	<true/>

+		<string>/private/var/mobile/Library/Trial/</string>

+		<string>com.apple.batteryintelligenced.thermalcontrol</string>

```
### cameracaptured

> `/usr/libexec/cameracaptured`

```diff

+	<key>com.apple.private.MobileContainerManager.lookup</key>
+	<dict>
+		<key>daemon</key>
+		<array>
+			<string>com.apple.cameracaptured</string>
+		</array>
+	</dict>

+		<string>BootManifestHash</string>

+	<key>com.apple.security.ts.daemon-container</key>
+	<true/>

```
### centaurid

> `/usr/libexec/centaurid`

```diff

+	<key>com.apple.TapToRadarKit.service-access</key>
+	<true/>

```
### companiond

> `/usr/libexec/companiond`

```diff

+	<key>com.apple.findmy.findmylocate.fenceservice</key>
+	<true/>

+		<string>kTCCServiceAddressBook</string>

+		<string>com.apple.Carousel</string>

```
### duetexpertd

> `/usr/libexec/duetexpertd`

```diff

+	<key>com.apple.private.photos.service.internal.cloud</key>
+	<true/>
+	<key>com.apple.private.photos.service.librarymanagement</key>
+	<true/>

+	<key>com.apple.private.security.storage.PhotosLibraries</key>
+	<true/>

+		<string>kTCCServicePhotos</string>

+		<string>com.apple.photos.service</string>

```
### hybridsearchd

> `/usr/libexec/hybridsearchd`

```diff

-				<key>TextUnderstanding.Extracted.Order</key>
+				<key>TextUnderstanding.Extracted.DeliveryTracking</key>

+				<key>TextUnderstanding.Extracted.DeliveryTracking</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>

-				<key>TextUnderstanding.Extracted.Order</key>
-				<dict>
-					<key>mode</key>
-					<string>read-write</string>
-				</dict>

```
### inboxupdaterd

> `/usr/libexec/inboxupdaterd`

```diff

+	<key>com.apple.rootless.volume.iSCHardware</key>
+	<true/>

```
### keybagd

> `/usr/libexec/keybagd`

```diff

-	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
-	<true/>

```
### locationd

> `/usr/libexec/locationd`

```diff

+		<key>flip</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>

+	<key>com.apple.private.appmanagedfeatures.configuration</key>
+	<true/>

+		<string>com.apple.appmanagedfeatures.configuration</string>

```
### mediaplaybackd

> `/usr/libexec/mediaplaybackd`

```diff

-		<string>/Library/VirtualCaptureCard/</string>

```
### mmaintenanced

> `/usr/libexec/mmaintenanced`

```diff

+	<key>com.apple.private.exclaves.stats-server</key>
+	<true/>

```
### mobile_obliterator

> `/usr/libexec/mobile_obliterator`

```diff

+	<key>com.apple.AppleNVMeSanitize.allow</key>
+	<true/>

+	<key>com.apple.private.iomfb.set-block</key>
+	<true/>

+		<string>IOAVControllerConcreteUserClient</string>

+		<string>AppleNVMeUserClient</string>

```
### nanoregistryd

> `/usr/libexec/nanoregistryd`

```diff

-	<key>com.apple.developer.hardened-process</key>
-	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/UserConfigurationProfiles/</string>
+	</array>

+	<key>com.apple.security.hardened-process</key>
+	<true/>

```
### networkserviceproxy

> `/usr/libexec/networkserviceproxy`

```diff

+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.servicesanalytics.xpc</string>
+	</array>

```
### ospredictiond

> `/usr/libexec/ospredictiond`

```diff

+	<key>com.apple.microlocation.connection</key>
+	<true/>

```

### 🆕 polarisd

> `/usr/libexec/polarisd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.afk.user</key>
	<true/>
	<key>com.apple.camera.iokit-user-access</key>
	<true/>
	<key>com.apple.diagnosticpipeline.request</key>
	<true/>
	<key>com.apple.polaris.client</key>
	<true/>
	<key>com.apple.polaris.consumer.all-streams</key>
	<true/>
	<key>com.apple.polaris.producer.all-streams</key>
	<true/>
	<key>com.apple.private.PolarisSystemTransition.access</key>
	<true/>
	<key>com.apple.private.kernel.panic</key>
	<true/>
	<key>com.apple.private.logging.flush-buffers</key>
	<true/>
	<key>com.apple.private.master-sync-generator.user-access</key>
	<true/>
	<key>com.apple.private.sandbox.profile:embedded</key>
	<string>temporary-sandbox</string>
	<key>com.apple.private.security.daemon-container</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceCamera</string>
		<string>kTCCServicePhotos</string>
		<string>kTCCServiceMotion</string>
	</array>
	<key>com.apple.pst.ApplePayLockDown</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.logd.admin</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.polaris</string>
	</array>
	<key>com.apple.security.iokit-user-client-class</key>
	<array>
		<string>AppleParavirtDeviceUserClient</string>
		<string>IOSurfaceAcceleratorClient</string>
		<string>IOSurfaceRootUserClient</string>
		<string>NBDisplayControlUserClient</string>
		<string>NBCoreUserClient</string>
		<string>NBTimesyncUserClient</string>
		<string>AFKEndpointInterfaceUserClient</string>
		<string>CompanionMgrEPICUserClient</string>
		<string>AppleCCPUUserClient</string>
		<string>CCPUAppEPICUserClient</string>
		<string>CCPUDebugServiceUserClient</string>
		<string>CCPUPmuServiceUserClient</string>
		<string>CCPUExpertUserClient</string>
		<string>CCPURegSamplerUserClient</string>
		<string>CCPUTestEndpointUserClient</string>
		<string>CCPUSMCSamplerUserClient</string>
		<string>RootDomainUserClient</string>
		<string>SCodecUserClient</string>
		<string>VDKManifestAgentUserClient</string>
		<string>PSTDriverServerUserClient</string>
	</array>
	<key>com.apple.security.ts.daemon-container</key>
	<true/>
	<key>com.apple.tailspin.dump-output</key>
	<true/>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### proximitycontrold

> `/usr/libexec/proximitycontrold`

```diff

+		<string>kTCCServiceMotion</string>

+	<key>com.apple.rapport.AdvertisePublicBluetoothAddress</key>
+	<true/>

```
### remoteappintentsd

> `/usr/libexec/remoteappintentsd`

```diff

+	<key>com.apple.private.ids.agent.GroupRestricted</key>
+	<true/>

+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>

```
### riskdatad

> `/usr/libexec/riskdatad`

```diff

+	<key>com.apple.frontboardservices.display-layout-monitor</key>
+	<true/>

```
### sharingd

> `/usr/libexec/sharingd`

```diff

-	<key>com.apple.private.power.notifications-temp</key>
+	<key>com.apple.private.power.notifications</key>

```
### tailspind

> `/usr/libexec/tailspind`

```diff

+	<key>com.apple.computesafeguards.managing.allow</key>
+	<true/>

```
### transparencyd

> `/usr/libexec/transparencyd`

```diff

+	<key>com.apple.cdp.telemetry</key>
+	<true/>

```
### triald

> `/usr/libexec/triald`

```diff

+	<key>com.apple.keystore.sik.access</key>
+	<true/>

```
### triald_system

> `/usr/libexec/triald_system`

```diff

+	<key>com.apple.keystore.sik.access</key>
+	<true/>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

+		<string>com.apple.icloud.findmydeviced.localfindable.tvremote</string>

-		<string>com.apple.icloud.findmydeviced.localfindable.tvremote</string>
-		<string>com.apple.remote-text-editing-legacy</string>

```
### usermanagerd

> `/usr/libexec/usermanagerd`

```diff

+	<key>com.apple.private.routefs-allow</key>
+	<true/>

```
### videocodecd

> `/usr/libexec/videocodecd`

```diff

+	<key>com.apple.private.rtcreportingd</key>
+	<true/>

+		<string>com.apple.rtcreportingd</string>

```
### visioncompaniond

> `/usr/libexec/visioncompaniond`

```diff

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.visionproapp.kvs</string>

+		<string>com.apple.kvsd</string>

```
### wifip2pd

> `/usr/libexec/wifip2pd`

```diff

+	<key>com.apple.private.skywalk.observe-all</key>
+	<true/>
+	<key>com.apple.private.skywalk.observe-stats</key>
+	<true/>

+		<string>/usr/sbin/wifid</string>
+		<string>/usr/sbin/mDNSResponder</string>

-		<string>com.apple.private.skywalk.observe-stats</string>

```
### BTMap

> `/usr/sbin/BTMap`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

```
### WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

```diff

-		<string>/System/Library/Trial/NamespaceDescriptors/com.apple.Trial.NamespaceDescriptor.860.plist</string>
-		<string>/System/Library/Trial/NamespaceDescriptors/com.apple.Trial.NamespaceDescriptor.862.plist</string>
-		<string>/System/Library/Trial/NamespaceDescriptors/com.apple.Trial.NamespaceDescriptor.861.plist</string>
-		<string>/System/Library/Trial/NamespaceDescriptors/com.apple.Trial.NamespaceDescriptor.1920.plist</string>

-		<string>860</string>
-		<string>861</string>
-		<string>862</string>
-		<string>1920</string>
+		<string>TELEPHONY_WIFI_CELLULAR_HANDOVER_POLICY</string>

+		<string>WIRELESS_DATA_ANALYTICS_CELLULAR_PRODUCT_EXPERIMENTATION_INTERNAL</string>

```

### 🆕 bluetoothaudiod

> `/usr/sbin/bluetoothaudiod`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.bluetoothaudiod</string>
	<key>com.apple.BTServer.allowRestrictedServices</key>
	<true/>
	<key>com.apple.BTServer.le.att</key>
	<true/>
	<key>com.apple.accessories.transport.allowauth</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.bluetoothaudiod</string>
	<key>com.apple.bluetooth.custom.properties.writable</key>
	<true/>
	<key>com.apple.bluetooth.pairedInfoSecurity</key>
	<true/>
	<key>com.apple.bluetooth.system</key>
	<true/>
	<key>com.apple.bluetoothaudiod.cb</key>
	<true/>
	<key>com.apple.donotdisturb.service</key>
	<true/>
	<key>com.apple.mediaremote.full-now-playing-read-access</key>
	<true/>
	<key>com.apple.private.donotdisturb.state.request.client-identifiers</key>
	<array>
		<string>com.apple.BTLEServer.ANCS</string>
	</array>
	<key>com.apple.private.siri.activation</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceAddressBook</string>
		<string>kTCCServiceBluetoothPeripheral</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array/>
	<key>com.apple.security.iokit-user-client-class</key>
	<array>
		<string>RootDomainUserClient</string>
	</array>
	<key>com.apple.siri.activation</key>
	<true/>
	<key>com.apple.siri.external_request</key>
	<true/>
	<key>com.apple.symptom_diagnostics.report</key>
	<true/>
	<key>com.apple.telephonyutilities.callservicesd</key>
	<array>
		<string>access-calls</string>
		<string>modify-calls</string>
	</array>
</dict>
</plist>

```


### SystemOS

### adattributiond

> `/System/Library/Frameworks/WebKit.framework/Daemons/adattributiond`

```diff

+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>
+	<key>com.apple.private.networkserviceproxy</key>
+	<true/>

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<dict>
+		<key>0</key>
+		<string>com.apple.networkserviceproxy</string>
+	</dict>

+	<key>com.apple.security.network.client</key>
+	<true/>

```

### 🆕 HybridDatabaseToolUtils

> `/System/Library/PrivateFrameworks/HybridDatabaseToolUtils.framework/HybridDatabaseToolUtils`

- No entitlements *(yet)*


### AppOS

### AuthenticationServicesAgent

> `/usr/libexec/AuthenticationServicesAgent`

```diff

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+	</array>

+	<key>com.apple.private.biome.read-write</key>
+	<array>
+		<string>Passwords.SecurityRecommendations</string>
+	</array>

```


