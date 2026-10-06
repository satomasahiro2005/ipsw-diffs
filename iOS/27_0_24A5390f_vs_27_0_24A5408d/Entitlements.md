## 🔑 Entitlements

### filesystem

### AXUIViewService

> `/Applications/AXUIViewService.app/AXUIViewService`

```diff

-	<false/>
+	<true/>

```
### AuthorizationPromptService

> `/Applications/AuthorizationPromptService.app/AuthorizationPromptService`

```diff

+		<string>com.apple.nehelper</string>

```
### Campo

> `/Applications/Campo.app/Campo`

```diff

+	<key>com.apple.intelligenceflow.imageretrieval</key>
+	<true/>

-		<string>path</string>
+		<string>bundleID</string>

-		<string>/Applications/Spotlight.app</string>
+		<string>com.apple.SiriApp</string>

+	<key>com.apple.realitysimulation.render-on-top-spi</key>
+	<true/>

+		<string>/Library/UserConfigurationProfiles/</string>

+		<string>com.apple.surfboard.lockscreenservice</string>

+		<string>com.apple.UIKit.LTSScrolling</string>

+	<key>com.apple.surfboard-prevent-homeui-from-hiding-when-launching</key>
+	<true/>

+	<key>com.apple.surfboard.lock-screen-client</key>
+	<true/>

```
### CarPlaySettings

> `/Applications/CarPlaySettings.app/CarPlaySettings`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

```
### CheckerBoard

> `/Applications/CheckerBoard.app/CheckerBoard`

```diff

+	<key>com.apple.private.exclaves.indicator_min_on_time</key>
+	<true/>

```
### CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

```diff

+			<key>companionSetupFilters</key>
+			<array>
+				<dict>
+					<key>rssi</key>
+					<integer>-45</integer>
+				</dict>
+			</array>

```
### HDSViewService

> `/Applications/HDSViewService.app/HDSViewService`

```diff

-	<key>com.apple.private.ProvInfoIOKitUserClient.access</key>
-	<true/>

```
### HeadphoneProxService

> `/Applications/HeadphoneProxService.app/HeadphoneProxService`

```diff

+		<string>com.apple.siri.ssrvtuitrainingservice.xpc</string>

```
### HearingWidgetExtension

> `/Applications/HearingApp.app/PlugIns/HearingWidgetExtension.appex/HearingWidgetExtension`

```diff

-	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<key>com.apple.security.exception.shared-preference.read-write</key>

```
### LimitedModeShieldApp

> `/Applications/LimitedModeShieldApp.app/LimitedModeShieldApp`

```diff

+	<key>com.apple.QuartzCore.secure-mode</key>
+	<true/>

```
### MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.Accessibility</string>
+	</array>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>
+		<string>com.apple.akd</string>
+		<string>com.apple.accountsd.accountmanager</string>

```
### MediaRemoteUI

> `/Applications/MediaRemoteUI.app/MediaRemoteUI`

```diff

+	<key>com.apple.mediaremote.system-volume-control</key>
+	<true/>

```
### MediaRemoteUIService

> `/Applications/MediaRemoteUIService.app/MediaRemoteUIService`

```diff

+	<key>com.apple.mediaremote.system-volume-control</key>
+	<true/>

```

### 🆕 SettingsImportExtension

> `/Applications/Preferences.app/PlugIns/SettingsImportExtension.appex/SettingsImportExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.Settings.extension.host</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.Preferences.SettingsImportExtension</string>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
	<key>com.apple.linkd.registry</key>
	<true/>
	<key>com.apple.linkd.transcript.privileged</key>
	<true/>
	<key>com.apple.locationd.effective_bundle</key>
	<true/>
	<key>com.apple.locationd.usage_oracle</key>
	<true/>
	<key>com.apple.private.appintents.extension-host</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.corespotlight.internal</key>
	<true/>
	<key>com.apple.private.corespotlight.search.internal</key>
	<true/>
	<key>com.apple.private.linkd.observationStatusRegistry</key>
	<true/>
	<key>com.apple.runningboard.assertions.siri</key>
	<true/>
	<key>com.apple.runningboard.launchprocess</key>
	<true/>
	<key>com.apple.runningboard.process-state</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.linkd.extension</string>
		<string>com.apple.linkd.registry</string>
		<string>com.apple.linkd.transcript</string>
		<string>com.apple.linkd.mediator</string>
	</array>
	<key>com.apple.security.files.user-selected.read-only</key>
	<true/>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.locationd.synchronous</string>
		<string>com.apple.frontboard.systemappservices</string>
		<string>com.apple.linkd.extension</string>
		<string>com.apple.linkd.registry</string>
		<string>com.apple.linkd.mediator</string>
		<string>com.apple.linkd.transcript</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.systemsettings.extensions</string>
	</array>
</dict>
</plist>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+	<key>com.apple.icloud.FindMyDevice.RepairDevice.access</key>
+	<true/>

+	<key>com.apple.icloud.searchparty.beaconManager.repairdeviceaccess</key>
+	<true/>

+	<key>com.apple.private.iokit.battery-shipping-charge-limit</key>
+	<true/>

+	<key>com.apple.private.iokit.powermanagement.read-assertions</key>
+	<true/>

+	<key>com.apple.private.mobilerepair.shipmode</key>
+	<true/>

+		<string>com.apple.installcoordinationd.PersonaLifecycle</string>

```
### SOSBuddy

> `/Applications/SOSBuddy.app/SOSBuddy`

```diff

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

```
### ScreenTimeSettingsShield

> `/Applications/ScreenTimeSettingsShield.app/ScreenTimeSettingsShield`

```diff

+	<key>com.apple.managedconfiguration.profiled-access</key>
+	<true/>

```
### ServicesPaymentAngel

> `/Applications/ServicesPaymentAngel.app/ServicesPaymentAngel`

```diff

+	<key>com.apple.managedconfiguration.profiled-access</key>
+	<true/>

```
### Setup

> `/Applications/Setup.app/Setup`

```diff

+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>

+		<string>com.apple.aa.accountService.xpc</string>

```
### ShortcutsUI

> `/Applications/ShortcutsUI.app/ShortcutsUI`

```diff

+	<key>com.apple.developer.healthkit</key>
+	<true/>

+	<key>com.apple.private.healthkit</key>
+	<true/>
+	<key>com.apple.private.healthkit.source.identities</key>
+	<array>
+		<string>com.apple.shortcuts</string>
+	</array>

```
### Siri

> `/Applications/Siri.app/Siri`

```diff

+	<key>com.apple.powerexperience.powermode.update</key>
+	<true/>

+		<string>/Applications/</string>

+		<string>com.apple.powerexperienced.resourceusage</string>

```
### StickersUltraExtension

> `/Applications/StickersUltra.app/PlugIns/StickersUltraExtension.appex/StickersUltraExtension`

```diff

+		<string>com.apple.visualintelligence.visual-action-prediction</string>

```
### StickersUltra

> `/Applications/StickersUltra.app/StickersUltra`

```diff

+		<string>com.apple.visualintelligence.visual-action-prediction</string>

```
### WidgetRenderer_Activities

> `/Applications/WidgetRenderer_Activities.app/WidgetRenderer_Activities`

```diff

+		<string>com.apple.health.shared</string>

```
### WidgetRenderer_CarPlay

> `/Applications/WidgetRenderer_CarPlay.app/WidgetRenderer_CarPlay`

```diff

+		<string>com.apple.health.shared</string>

```
### WidgetRenderer_Default

> `/Applications/WidgetRenderer_Default.app/WidgetRenderer_Default`

```diff

+		<string>com.apple.health.shared</string>

```
### WidgetRenderer_Snapshots

> `/Applications/WidgetRenderer_Snapshots.app/WidgetRenderer_Snapshots`

```diff

+		<string>com.apple.health.shared</string>

```

### 🆕 WidgetRenderer_StandBy

> `/Applications/WidgetRenderer_StandBy.app/WidgetRenderer_StandBy`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.chrono.WidgetRenderer-Default</string>
	<key>aps-connection-initiate</key>
	<true/>
	<key>com.apple.QuartzCore.secure-mode</key>
	<true/>
	<key>com.apple.chrono.event-service-publisher</key>
	<true/>
	<key>com.apple.chrono.widgetRenderer</key>
	<true/>
	<key>com.apple.coreduet.knowledge</key>
	<true/>
	<key>com.apple.coreduetd.allow</key>
	<true/>
	<key>com.apple.coreduetd.context</key>
	<true/>
	<key>com.apple.developer.device-information.user-assigned-device-name</key>
	<true/>
	<key>com.apple.duet.activityscheduler.allow</key>
	<true/>
	<key>com.apple.heartratecoordinator.spi.heartrate</key>
	<true/>
	<key>com.apple.lightsourcesupport.listener</key>
	<true/>
	<key>com.apple.lightsourcesupport.motion</key>
	<true/>
	<key>com.apple.localizationswitcher</key>
	<true/>
	<key>com.apple.locationd.effective_bundle</key>
	<true/>
	<key>com.apple.nano.nanoregistry</key>
	<true/>
	<key>com.apple.nano.nanoregistry.generalaccess</key>
	<true/>
	<key>com.apple.private.MobileContainerManager.lookup</key>
	<dict>
		<key>appData</key>
		<true/>
	</dict>
	<key>com.apple.private.MobileContainerManager.otherIdLookup</key>
	<true/>
	<key>com.apple.private.appmanagedfeatures.configuration</key>
	<true/>
	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
	<dict>
		<key>type</key>
		<string>path</string>
		<key>value</key>
		<string>/Applications/WidgetRenderer_StandBy.app/WidgetRenderer_StandBy</string>
	</dict>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Carousel.Connection.Companion</string>
	</array>
	<key>com.apple.private.chrono-extension-host</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.graphics-restart-no-kill</key>
	<true/>
	<key>com.apple.private.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_bypass</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>DuetActivitySchedulerWidgetRefresh</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Widgets.Viewed</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.private.iokit.batterydataprecise</key>
	<true/>
	<key>com.apple.private.iokit.batteryhealthstate</key>
	<true/>
	<key>com.apple.private.iokit.charging-iconography</key>
	<true/>
	<key>com.apple.private.memorystatus</key>
	<true/>
	<key>com.apple.private.photos.XPCStoreOptIn</key>
	<true/>
	<key>com.apple.private.security.restricted-application-groups</key>
	<string>group.com.apple.chronod</string>
	<key>com.apple.private.security.storage.AppDataContainers</key>
	<true/>
	<key>com.apple.private.security.storage.chronod</key>
	<true/>
	<key>com.apple.private.sessionkit.listener</key>
	<true/>
	<key>com.apple.private.sessionkit.presentationAssertionRequester</key>
	<true/>
	<key>com.apple.private.sessionkit.sessionFinisher</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServicePhotos</string>
		<string>kTCCServiceSystemPolicyAppData</string>
		<string>kTCCServiceMotion</string>
	</array>
	<key>com.apple.rootless.storage.coreduet_knowledge_store</key>
	<true/>
	<key>com.apple.runningboard.assertions.chronod</key>
	<true/>
	<key>com.apple.runningboard.assertions.widgetRenderer</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/Applications/</string>
		<string>/System/Library/CoreServices/</string>
		<string>/AppleInternal/Applications/</string>
		<string>/private/var/containers/Bundle/Application/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/chronod/</string>
		<string>/Library/Fonts/AddedFontCache.plist</string>
		<string>/Library/UserConfigurationProfiles/EffectiveUserSettings.plist</string>
		<string>/Library/UserFonts/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Caches/com.apple.chronod/</string>
		<string>/Library/Caches/com.apple.chrono/</string>
	</array>
	<key>com.apple.security.exception.iokit-user-client-class</key>
	<string>IOHIDLibUserClient</string>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.chronoservices</string>
		<string>com.apple.backboard.hid.services</string>
		<string>com.apple.backboard.display.services</string>
		<string>com.apple.iohideventsystem</string>
		<string>com.apple.frontboard.systemappservices</string>
		<string>com.apple.CARenderServer</string>
		<string>com.apple.UIKit.KeyboardManagement.hosted</string>
		<string>com.apple.duetactivityscheduler</string>
		<string>com.apple.iphone.axserver-systemwide</string>
		<string>com.apple.accessibility.AXBackBoardServer</string>
		<string>com.apple.proactive.infoSuggestion.xpc</string>
		<string>com.apple.powerlog.plxpclogger.xpc</string>
		<string>com.apple.locationd.registration</string>
		<string>com.apple.PointerUI.pointeruid.service</string>
		<string>com.apple.fontservicesd</string>
		<string>com.apple.backboard.hid-services.xpc</string>
		<string>com.apple.springboard.services</string>
		<string>com.apple.locationd.synchronous</string>
		<string>com.apple.backlightd</string>
		<string>com.apple.symptom_diagnostics</string>
		<string>com.apple.localizationswitcherd</string>
		<string>com.apple.sessionservices</string>
		<string>com.apple.coremedia.compressionsession</string>
		<string>com.apple.coremedia.decompressionsession</string>
		<string>com.apple.mobile.keybagd.xpc</string>
		<string>com.apple.mobile.keybagd.UserManager.xpc</string>
		<string>com.apple.mobile.usermanagerd.xpc</string>
		<string>com.apple.chrono.event-service.gamed</string>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.biome.access.system</string>
		<string>com.apple.lightsourcesupport.lightstate</string>
		<string>com.apple.heartratecoordinatord.requestor</string>
		<string>com.apple.appmanagedfeatures.configuration</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.local-name</key>
	<array>
		<string>com.apple.iphone.axserver</string>
	</array>
	<key>com.apple.security.exception.mach-register.global-name</key>
	<array>
		<string>com.apple.chrono.widgetcenterconnection</string>
		<string>com.apple.chronod.gsEvents</string>
		<string>com.apple.chronoservices</string>
	</array>
	<key>com.apple.security.exception.mach-register.local-name</key>
	<array>
		<string>com.apple.iphone.axserver</string>
	</array>
	<key>com.apple.security.exception.process-info</key>
	<true/>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.springboard</string>
		<string>com.apple.chronod</string>
		<string>com.apple.uikitservices.userInterfaceStyleMode</string>
		<string>com.apple.BatteryCenter.BatteryWidget</string>
		<string>com.apple.Preferences</string>
		<string>com.apple.coremedia</string>
		<string>com.apple.UIKit</string>
		<string>com.apple.keyboard</string>
		<string>com.apple.da</string>
		<string>com.apple.SpeakSelection</string>
		<string>com.apple.coreanimation</string>
		<string>com.apple.duetexpertd</string>
		<string>com.apple.frontboardservices.device_emulation</string>
		<string>com.apple.health.shared</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.network.server</key>
	<true/>
	<key>com.apple.security.ts.mach-task-name</key>
	<true/>
	<key>com.apple.security.ts.opengl-or-metal</key>
	<true/>
	<key>com.apple.security.ts.power-assertions</key>
	<true/>
	<key>com.apple.security.ts.render-images</key>
	<true/>
	<key>com.apple.security.ts.tmpdir</key>
	<string>com.apple.chrono</string>
	<key>com.apple.sessionservices</key>
	<true/>
	<key>com.apple.symptom_diagnostics.report</key>
	<true/>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### WidgetRenderer_WatchFaces

> `/Applications/WidgetRenderer_WatchFaces.app/WidgetRenderer_WatchFaces`

```diff

+		<string>com.apple.health.shared</string>

```
### AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

+	<key>com.apple.private.automatic-assessment-configuration.restrictor</key>
+	<true/>

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.Accessibility</string>
+	</array>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>com.apple.siri.assessment-mode-restriction</string>

+		<string>com.apple.akd</string>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>

+	<key>com.apple.springboard.secure-indicator-elevation</key>
+	<true/>

```
### assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

```diff

+	<key>com.apple.springboard.secure-indicator-elevation</key>
+	<true/>

```
### CommandAndControl

> `/System/Library/CoreServices/CommandAndControl.app/CommandAndControl`

```diff

+	<key>com.apple.springboard.secure-indicator-elevation</key>
+	<true/>

```
### PhotosViewService

> `/System/Library/CoreServices/PhotosViewService.app/PhotosViewService`

```diff

+	<key>com.apple.private.tcc.allow-or-regional-prompt</key>
+	<array>
+		<string>kTCCServiceAddressBook</string>
+	</array>

```
### SpringBoard

> `/System/Library/CoreServices/SpringBoard.app/SpringBoard`

```diff

+		<string>com.apple.powerd.coresmartpowernap</string>

```
### vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.Accessibility</string>
+	</array>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>
+		<string>com.apple.akd</string>
+		<string>com.apple.accountsd.accountmanager</string>

```
### AgeVerificationExtension

> `/System/Library/ExtensionKit/Extensions/AgeVerificationExtension.appex/AgeVerificationExtension`

```diff

+	<key>com.apple.private.applemediaservices</key>
+	<true/>

```
### AppManagedFeaturesDemoExtension

> `/System/Library/ExtensionKit/Extensions/AppManagedFeaturesDemoExtension.appex/AppManagedFeaturesDemoExtension`

```diff

+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.safefinancing.demoextension</string>
+	</array>
+	<key>com.apple.security.network.client</key>
+	<true/>

```
### AssetMetricsExtension

> `/System/Library/ExtensionKit/Extensions/AssetMetricsExtension.appex/AssetMetricsExtension`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/Application Support/com.apple.appleintelligencereporting.processing/</string>
+	</array>

```
### FedAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/FedAutoEvalPlugin.appex/FedAutoEvalPlugin`

```diff

+		<string>PrivateMLClient.SafetyMetrics</string>

+		<key>SiriSafety</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>PrivateMLClient.SafetyMetrics</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

```
### FedStatsPluginDynamic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginDynamic.appex/FedStatsPluginDynamic`

```diff

+		<key>MAD-TextUnderstanding-ProcessingResults</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>MediaAnalysis.TextUnderstanding.ProcessingResults</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		</dict>
+		<key>PCC-Safety-Metrics</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>PrivateMLClient.SafetyMetrics</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>

```
### FedStatsPluginStatic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginStatic.appex/FedStatsPluginStatic`

```diff

+		<key>MAD-TextUnderstanding-ProcessingResults</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>MediaAnalysis.TextUnderstanding.ProcessingResults</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		</dict>
+		<key>PCC-Safety-Metrics</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>PrivateMLClient.SafetyMetrics</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>

```
### GPUIExtension

> `/System/Library/ExtensionKit/Extensions/GPUIExtension.appex/GPUIExtension`

```diff

+		<string>/private/var/containers/Bundle/Application/</string>
+		<string>/Applications/</string>

```

### 🆕 MacinTalkAUSP

> `/System/Library/ExtensionKit/Extensions/MacinTalkAUSP.appex/MacinTalkAUSP`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.accessibility.systemvoiceprovider</key>
	<true/>
	<key>com.apple.coreaudio.allow-opus-codec</key>
	<true/>
	<key>com.apple.private.assets.accessible-asset-types</key>
	<array>
		<string>com.apple.MobileAsset.TTSAXResourceModelAssets</string>
	</array>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_TTSAXResourceModelAssets/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Accessibility/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.audio.AudioConverterService</string>
		<string>com.apple.logd</string>
		<string>com.apple.system.notification_center</string>
		<string>com.apple.audio.AudioComponentRegistrar</string>
		<string>com.apple.audio.AudioUnitServer</string>
		<string>com.apple.mobileassetd.v2</string>
		<string>com.apple.SiriTTSService.TrialProxy</string>
		<string>com.apple.accessibility.voices</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.voiceservices</string>
		<string>com.apple.SpeakSelection</string>
	</array>
	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
	<array>
		<string>/Library/Caches/TTSResourceCache.plist</string>
	</array>
	<key>com.apple.security.temporary-exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Accessibility/</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.audio.AudioConverterService</string>
		<string>com.apple.logd</string>
		<string>com.apple.system.notification_center</string>
		<string>com.apple.audio.AudioComponentRegistrar</string>
		<string>com.apple.audio.AudioUnitServer</string>
		<string>com.apple.mobileassetd.v2</string>
		<string>com.apple.SiriTTSService.TrialProxy</string>
		<string>com.apple.accessibility.voices</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.SpeakSelection</string>
		<string>com.apple.voiceservices</string>
	</array>
	<key>com.apple.security.ts.ipc-posix-shm</key>
	<array>
		<string>apple.shm.notification_center</string>
	</array>
</dict>
</plist>

```
### MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

```diff

+	<key>com.apple.nano.nanoregistry.generalaccess</key>
+	<true/>

```
### MediaRemoteAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/MediaRemoteAppIntentsExtension.appex/MediaRemoteAppIntentsExtension`

```diff

+	<key>com.apple.mediaremote.system-volume-control</key>
+	<true/>

```

### 🆕 Celosia.metallib

> `/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/Celosia.metallib`

- No entitlements *(yet)*
### PhotosFileProvider

> `/System/Library/ExtensionKit/Extensions/PhotosFileProvider.appex/PhotosFileProvider`

```diff

+	<key>com.apple.private.photos.restrictedresources.read</key>
+	<true/>

```
### PhotosMessagesApp

> `/System/Library/ExtensionKit/Extensions/PhotosMessagesApp.appex/PhotosMessagesApp`

```diff

+	<key>com.apple.mediaanalysisd.client</key>
+	<true/>

```
### PrivateMLClientInferenceProviderService

> `/System/Library/ExtensionKit/Extensions/PrivateMLClientInferenceProviderService.appex/PrivateMLClientInferenceProviderService`

```diff

+		<string>PrivateMLClient.RecitationMetrics</string>
+		<string>PrivateMLClient.SafetyMetrics</string>

```
### ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

```diff

+	<key>com.apple.private.amsondevicestoraged</key>
+	<true/>

+	<key>com.apple.private.servicesintelligence</key>
+	<true/>

+		<string>com.apple.servicesintelligenced</string>
+		<string>com.apple.amsondevicestoraged.xpc</string>

+		<string>com.apple.storeservices.itfe</string>

```
### ReceiptsExtractionDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/ReceiptsExtractionDiagnosticExtension.appex/ReceiptsExtractionDiagnosticExtension`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>
+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>

```
### ScreenTimeSettingsResponseExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeSettingsResponseExtension.appex/ScreenTimeSettingsResponseExtension`

```diff

+	<key>adi-client</key>
+	<string>2463478364</string>

+	<key>com.apple.authkit.client.private</key>
+	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
+	<key>com.apple.private.applemediaservices</key>
+	<true/>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>

+		<string>com.apple.accountsd.accountmanager</string>
+		<string>com.apple.adid</string>
+		<string>com.apple.ak.auth.xpc</string>
+		<string>com.apple.fairplayd.versioned</string>

+		<string>com.apple.iconservices</string>

+		<string>com.apple.xpc.amsaccountsd</string>
+		<string>com.apple.xpc.amsengagementd</string>
+	</array>
+	<key>fairplay-client</key>
+	<string>511712240</string>
+	<key>keychain-access-groups</key>
+	<array>
+		<string>apple</string>
+		<string>appleaccount</string>
+		<string>com.apple.certificates</string>
+		<string>com.apple.identities</string>
+		<string>com.apple.preferences</string>

```

### 🆕 SiriSetupSettingsIntents

> `/System/Library/ExtensionKit/Extensions/SiriSetupSettingsIntents.appex/SiriSetupSettingsIntents`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
	<string>com.apple.Preferences</string>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>com.apple.voicetrigger</string>
		<string>com.apple.assistant.settings</string>
		<string>com.apple.assistant.backedup</string>
		<string>com.apple.siri</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.assistant.settings</string>
	</array>
</dict>
</plist>

```
### SubscribePageExtension

> `/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension`

```diff

+	<key>com.apple.private.amsondevicestoraged</key>
+	<true/>

+	<key>com.apple.private.servicesintelligence</key>
+	<true/>

+		<string>com.apple.servicesintelligenced</string>
+		<string>com.apple.amsondevicestoraged.xpc</string>

+		<string>com.apple.storeservices.itfe</string>

```
### apfs_checkdigest

> `/System/Library/Filesystems/apfs.fs/apfs_checkdigest`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### apfs_computedigest

> `/System/Library/Filesystems/apfs.fs/apfs_computedigest`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### apfs_iosd

> `/System/Library/Filesystems/apfs.fs/apfs_iosd`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### sm_stats

> `/System/Library/Filesystems/apfs.fs/sm_stats`

```diff

+	<key>com.apple.private.apfs.get-dstreams</key>
+	<true/>
+	<key>com.apple.private.apfs.get-file-exts</key>
+	<true/>

```
### accountsd

> `/System/Library/Frameworks/Accounts.framework/accountsd`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

```diff

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.configurationprofiles</string>
+	</array>

```
### spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

```diff

+	<key>com.apple.private.corespotlight.allowcarplayapps</key>
+	<true/>

```
### CommCenterMobileHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterMobileHelper`

```diff

+		<string>systemgroup.com.apple.regulatory_images</string>

```
### financed

> `/System/Library/Frameworks/FinanceKit.framework/financed`

```diff

+	<key>com.apple.devicecheck.private.certificate.validity</key>
+	<integer>2628000</integer>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>kTCCServiceSiriAccess</string>

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>

```
### ManagedSettingsAgent

> `/System/Library/Frameworks/ManagedSettings.framework/ManagedSettingsAgent`

```diff

+		<string>com.apple.Accessibility</string>

```
### RemotePlayerService

> `/System/Library/Frameworks/MediaPlayer.framework/XPCServices/RemotePlayerService.xpc/RemotePlayerService`

```diff

+	<key>com.apple.private.appintents.exception.allow-foreign-bundle-identifiers</key>
+	<true/>

```
### ScreenTimeWebExtension

> `/System/Library/Frameworks/ScreenTime.framework/PlugIns/ScreenTimeWebExtension.appex/ScreenTimeWebExtension`

```diff

+	<key>com.apple.private.managed-settings.effective-read</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>
+	</array>

+		<string>com.apple.ManagedSettingsAgent</string>
+		<string>com.apple.ManagedSettingsAgent.publisher</string>

```
### XPCAcmeService

> `/System/Library/Frameworks/Security.framework/XPCServices/XPCAcmeService.xpc/XPCAcmeService`

```diff

-	<key>com.apple.security.exception.files.absolute-path.read-write</key>
-	<array>
-		<string>/private/var/tmp/com.apple.security.XPCAcmeService</string>
-		<string>/private/var/tmp/com.apple.security.XPCAcmeService/</string>
-		<string>/private/var/mobile/Library/Caches/com.apple.security.XPCAcmeService</string>
-		<string>/private/var/mobile/Library/Caches/com.apple.security.XPCAcmeService/</string>
-		<string>/private/var/mobile/Library/HTTPStorages/com.apple.security.XPCAcmeService</string>
-		<string>/private/var/mobile/Library/HTTPStorages/com.apple.security.XPCAcmeService/</string>
-		<string>/private/var/root/Library/Caches/com.apple.security.XPCAcmeService</string>
-		<string>/private/var/root/Library/Caches/com.apple.security.XPCAcmeService/</string>
-		<string>/private/var/root/Library/HTTPStorages/com.apple.security.XPCAcmeService</string>
-		<string>/private/var/root/Library/HTTPStorages/com.apple.security.XPCAcmeService/</string>
-	</array>
-	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
-	<array>
-		<string>/Library/Caches/com.apple.security.XPCAcmeService</string>
-		<string>/Library/Caches/com.apple.security.XPCAcmeService/</string>
-		<string>/Library/HTTPStorages/com.apple.security.XPCAcmeService</string>
-		<string>/Library/HTTPStorages/com.apple.security.XPCAcmeService/</string>
-	</array>

```
### translationd

> `/System/Library/Frameworks/Translation.framework/translationd`

```diff

+		<string>com.apple.MobileAsset.UAF.Translation.MMAssets</string>

+		<string>/System/Library/PreinstalledAssetsV2/RequiredByOs/com_apple_MobileAsset_UAF_Translation_MMAssets/</string>

```
### wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

```diff

+		<string>com.apple.iohideventsystem</string>

```

### 🆕 AuthenticationServicesDeveloperSettings

> `/System/Library/PreferenceBundles/AuthenticationServicesDeveloperSettings.bundle/AuthenticationServicesDeveloperSettings`

- No entitlements *(yet)*

### 🆕 PasswordsDeveloperSettings

> `/System/Library/PreferenceBundles/PasswordsDeveloperSettings.bundle/PasswordsDeveloperSettings`

- No entitlements *(yet)*
### axassetsd

> `/System/Library/PrivateFrameworks/AXAssetLoader.framework/Support/axassetsd`

```diff

+		<string>com.apple.analyticsd</string>

```
### BundledIntentHandler

> `/System/Library/PrivateFrameworks/ActionKit.framework/PlugIns/BundledIntentHandler.appex/BundledIntentHandler`

```diff

+	<key>com.apple.accessibility.physicalinteraction.client</key>
+	<true/>

```
### agentstored

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/agentstored`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.client.internal</key>
+	<true/>

+	<key>com.apple.mobileactivationd.bridge</key>
+	<true/>
+	<key>com.apple.mobileactivationd.device-identifiers</key>
+	<true/>
+	<key>com.apple.mobileactivationd.spi</key>
+	<true/>

-		<key>com.apple.agentsessionstore</key>
-		<string>com.apple.GenerativeModels.AgentSessionKit</string>
+		<key>com.apple.agentsessionstore.secure</key>
+		<string>com.apple.agentsessionstore.secure</string>

+		<string>/Library/AgentSessionKitBackupStaging/</string>

+		<string>com.apple.mobileactivationd</string>
+		<string>com.apple.ak.auth.xpc</string>

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.cfnetwork</string>
+		<string>apple</string>
+	</array>

```
### amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/amsaccountsd`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

```
### assistant_service

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistant_service`

```diff

+	<key>com.apple.private.corespotlight.allowquerydraintrigger</key>
+	<true/>

```
### assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

```diff

+	<key>com.apple.private.darwin-notification.restrict-post.assistant.speech-request</key>
+	<true/>

+		<string>SIRI_INTELLIGENCE_FLOW_PLANNER</string>

```
### AKAppSSOExtension

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/PlugIns/AKAppSSOExtension.appex/AKAppSSOExtension`

```diff

+	<key>com.apple.private.associated-domains</key>
+	<true/>

+		<string>com.apple.SharedWebCredentials</string>

```
### cksharingmanagementd

> `/System/Library/PrivateFrameworks/CKSharingManagementDaemon.framework/Support/cksharingmanagementd`

```diff

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

```
### SetStoreUpdateService

> `/System/Library/PrivateFrameworks/CascadeSets.framework/XPCServices/SetStoreUpdateService.xpc/SetStoreUpdateService`

```diff

+	<key>com.apple.spaceattribution.private</key>
+	<true/>

```
### clipserviced

> `/System/Library/PrivateFrameworks/ClipServices.framework/clipserviced`

```diff

+		<string>/Library/UserConfigurationProfiles/Truth.plist</string>

```
### cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

```diff

-		<key>com.apple.photos.asc.e2ee</key>
-		<string>com.apple.photos.asc.e2ee</string>
+		<key>com.apple.photos.asc.e2ee.secure</key>
+		<string>com.apple.photos.asc.e2ee.secure</string>

```
### CloudSharingAccessSelectionViewService-iOS

> `/System/Library/PrivateFrameworks/CloudSharingUI.framework/PlugIns/CloudSharingAccessSelectionViewService-iOS.appex/CloudSharingAccessSelectionViewService-iOS`

```diff

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>

```
### com.apple.CloudSharingUI.AddParticipants

> `/System/Library/PrivateFrameworks/CloudSharingUI.framework/PlugIns/com.apple.CloudSharingUI.AddParticipants.appex/com.apple.CloudSharingUI.AddParticipants`

```diff

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>

```
### ACCNowPlayingFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCNowPlayingFeature.xpc/ACCNowPlayingFeature`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>application-identifier</key>
+	<string>com.apple.accessories.now-playing-feature</string>
+	<key>com.apple.private.tcc.allow</key>
+	<array>
+		<string>kTCCServiceMediaLibrary</string>
+	</array>
+	<key>platform-application</key>
+	<true/>
+</dict>
+</plist>

```
### analyticsagent

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent`

```diff

+		<string>Siri.ODDI.ODDAssistantLLMSiriDigests</string>

+		</dict>
+		<key>SELFCommonEventTelemetry</key>
+		<dict>
+			<key>Streams</key>
+			<array>
+				<string>Siri.ODDI.ODDAssistantLLMSiriDigests</string>
+			</array>

```
### analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

```diff

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

+	<key>com.apple.security.exception.iokit-user-client-class</key>
+	<array>
+		<string>AppleSPUHIDDriverUserClient</string>
+	</array>

```
### CoreRepairCoreXPCService

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/XPCServices/CoreRepairCoreXPCService.xpc/CoreRepairCoreXPCService`

```diff

+	<key>com.apple.CheckerBoard.services</key>
+	<true/>

+	<key>com.apple.private.iokit.battery-shipping-charge-limit</key>
+	<true/>

+		<string>com.apple.CheckerBoard.services</string>

```
### corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

```diff

-		<string>path</string>
+		<string>bundleID</string>

-		<string>/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd</string>
+		<string>com.apple.SiriApp</string>

+		<string>/dev/exfiltration-rts_nis_dbg</string>

```
### DTServiceHub

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DTServiceHub`

```diff

+	<key>com.apple.private.cs.debugger.safe</key>
+	<true/>

```
### LeakAgent

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/LeakAgent`

```diff

+	<key>com.apple.private.cs.debugger.safe</key>
+	<true/>

```
### DeviceConfigurationAgent

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfigurationAgent`

```diff

+	<key>com.apple.private.device-configuration.user.private</key>
+	<true/>

+		<string>com.apple.deviceconfigurationd.user.private.async</string>

```
### deviceconfigurationd

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/deviceconfigurationd`

```diff

+	<key>com.apple.mkb.usersession.info</key>
+	<true/>
+	<key>com.apple.private.container.access</key>
+	<dict>
+		<key>protectedSystem</key>
+		<dict>
+			<key>com.apple.DeviceConfigurationAgent</key>
+			<dict>
+				<key>data</key>
+				<dict>
+					<key>access</key>
+					<string>path-only</string>
+					<key>operations</key>
+					<array>
+						<string>delete</string>
+						<string>lookup</string>
+					</array>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.mobile.keybagd.xpc</string>
+	</array>

```
### com.apple.DocumentManagerCore.Rename

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/XPCServices/com.apple.DocumentManagerCore.Rename.xpc/com.apple.DocumentManagerCore.Rename`

```diff

+		<string>com.apple.DesktopServicesHelper</string>
+		<string>com.apple.DesktopServicesHelper.FileService</string>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/generativeexperiencesd`

```diff

+		<string>com.apple.CloudSubscriptionFeatures.gmBypass</string>

```
### heard

> `/System/Library/PrivateFrameworks/HearingCore.framework/heard`

```diff

+	<key>com.apple.private.sleepd</key>
+	<true/>

+		<string>com.apple.sleepd.sleepserver</string>

```
### HearingWidgetExtension

> `/System/Library/PrivateFrameworks/HearingWidgetExtension.appex/HearingWidgetExtension`

```diff

-	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<key>com.apple.security.exception.shared-preference.read-write</key>

```
### intelligencecontextd

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd`

```diff

+	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
+	<dict>
+		<key>type</key>
+		<string>bundleID</string>
+		<key>value</key>
+		<string>com.apple.SiriApp</string>
+	</dict>

+		<string>com.apple.coreservices.quarantine-resolver</string>

```

### 🆕 IntelligenceFlowCustomerDiagnostics

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowCustomerDiagnostics.appex/IntelligenceFlowCustomerDiagnostics`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.intelligenceflow.IntelligenceFlowRuntime.IntelligenceFlowCustomerDiagnostics</string>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.intelligenceflow.context</key>
	<true/>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Sage.Transcript</string>
		<string>IntelligenceFlow.Transcript.Datastream</string>
		<string>IntelligenceEngine.Interaction.Donation</string>
	</array>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>com.apple.intelligenceflow.IntelligenceFlowRuntime.IntelligenceFlowCustomerDiagnostics</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>Sage.Transcript</string>
				<string>IntelligenceFlow.Transcript.Datastream</string>
				<string>IntelligenceEngine.Interaction.Donation</string>
			</array>
		</dict>
	</dict>
	<key>com.apple.private.security.storage.SiriFeatureStore</key>
	<true/>
	<key>com.apple.private.siriappintentsd.orchestrator</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/Logs/com.apple.FeatureStore/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.intelligenceflow.context</string>
		<string>com.apple.private.siriappintentsd.orchestrator</string>
	</array>
</dict>
</plist>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd`

```diff

+	<key>com.apple.intelligenceflow.imageretrieval</key>
+	<true/>

+	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
+	<dict>
+		<key>type</key>
+		<string>bundleID</string>
+		<key>value</key>
+		<string>com.apple.SiriApp</string>
+	</dict>

+		<string>com.apple.intelligenceflow.imageretrieval</string>

+		<string>com.apple.toolkitd.xpc</string>
+		<string>com.apple.siriactionsd.xpc</string>

+	<key>com.apple.toolkit.request-immediate-indexing.allow</key>
+	<true/>

```
### Managed Background Assets Helper Service

> `/System/Library/PrivateFrameworks/ManagedBackgroundAssets.framework/XPCServices/Managed Background Assets Helper Service.xpc/Managed Background Assets Helper Service`

```diff

+		<string>com.apple.backgroundassets.managed.relay.service</string>

```
### navd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/navd`

```diff

+	<key>com.apple.private.appintents-attribution-override</key>
+	<true/>
+	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
+	<string>com.apple.Maps</string>

```
### mediaanalysisd

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd`

```diff

+		<string>MediaAnalysis.TextUnderstanding.ProcessingResults</string>

```
### mediaanalysisd-service

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd-service`

```diff

+		<string>MediaAnalysis.TextUnderstanding.ProcessingResults</string>

```
### mediaanalysisd-generation

> `/System/Library/PrivateFrameworks/MediaAnalysisGeneration.framework/XPCServices/mediaanalysisd-generation.xpc/mediaanalysisd-generation`

```diff

+	<key>com.apple.runningboard.assertions.mediaanalysisd-generation</key>
+	<true/>

```
### modelcatalogd

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/modelcatalogd`

```diff

+		<string>/private/var/db/os_eligibility/</string>

```
### searchtoold

> `/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold`

```diff

+	<key>com.apple.private.filebrowsingservices.path-resolver-client</key>
+	<true/>

+		<string>com.apple.FileBrowsingServices.PathResolver</string>

```
### passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

```diff

+		<string>com.apple.visualintelligence.visual-action-prediction</string>

+	<key>com.apple.visualintelligence.private.visual-action-prediction</key>
+	<true/>

```
### photoanalysisd

> `/System/Library/PrivateFrameworks/PhotoAnalysis.framework/Support/photoanalysisd`

```diff

+		<string>com.apple.servicesanalytics.xpc</string>

+	<key>com.apple.springboard.fetchDisplayConfigs</key>
+	<true/>
+	<key>com.apple.springboard.wallpaper.display-configuration</key>
+	<true/>

```
### com.apple.photos.PCCService

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/XPCServices/com.apple.photos.PCCService.xpc/com.apple.photos.PCCService`

```diff

+	<key>com.apple.private.biome.writer</key>
+	<array>
+		<string>PrivateCloudCompute.RequestLog</string>
+	</array>

```
### privatecloudcomputed

> `/System/Library/PrivateFrameworks/PrivateCloudCompute.framework/privatecloudcomputed.app/privatecloudcomputed`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

```
### DeviceConfigurationSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/DeviceConfigurationSubscriber.xpc/DeviceConfigurationSubscriber`

```diff

+		<string>com.apple.DeviceConfigurationAgent.provider.async</string>

```
### ManagedStatusSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/ManagedStatusSubscriber.xpc/ManagedStatusSubscriber`

```diff

+	<key>com.apple.managedconfiguration.mdmuserd-access</key>
+	<true/>

+		<string>/private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles/Library/ConfigurationProfiles/MultiUserDeviceConfiguration.plist</string>

+		<string>com.apple.managedconfiguration.mdmuserdservice</string>

```
### ScreenTimeSettingsAgent

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsAgent`

```diff

+	<key>com.apple.private.appstored</key>
+	<array>
+		<string>AppStore</string>
+	</array>

+	<key>com.apple.private.biome.writer</key>
+	<array>
+		<string>Discoverability.Signals</string>
+	</array>

+		<string>com.apple.appstored.xpc.request</string>

+		<string>com.apple.gms.availability</string>

```
### searchd

> `/System/Library/PrivateFrameworks/Search.framework/searchd`

```diff

-	<key>com.apple.private.tcc.events.subscriber</key>
-	<true/>
-	<key>com.apple.private.tcc.manager.access.read</key>
+	<key>com.apple.private.tcc.manager.read.access</key>

```
### budd

> `/System/Library/PrivateFrameworks/SetupAssistant.framework/budd`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.aa.accountService.xpc</string>

```
### siriappintentsd

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/siriappintentsd`

```diff

+		<string>SecurityValidationProtoSecurityValidationEventPayload</string>

```
### siriinferenced

> `/System/Library/PrivateFrameworks/SiriInference.framework/Support/siriinferenced`

```diff

+		<string>com.apple.servicesanalytics.xpc</string>

```
### imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.applicationaccess</string>
+	</array>

```
### systemstatusd

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/Support/systemstatusd`

```diff

+	<key>com.apple.runningboard.terminateprocess</key>
+	<true/>

```
### PhoneIntentHandler

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/PlugIns/PhoneIntentHandler.appex/PhoneIntentHandler`

```diff

+		<string>com.apple.telephonyutilities.callservicesdaemon.conversationmanager</string>

```
### matd

> `/System/Library/PrivateFrameworks/WelcomeKit.framework/matd`

```diff

+	<key>com.apple.private.security.storage.MessagesEscrow</key>
+	<true/>

```
### BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

```diff

+	<key>com.apple.PerfPowerServices.data-donation</key>
+	<true/>

+		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>

+		<string>com.apple.powerlog.plxpclogger.xpc</string>

```
### bird

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/bird`

```diff

+	<key>com.apple.private.container.access</key>
+	<dict>
+		<key>appData</key>
+		<dict>
+			<key>*</key>
+			<dict>
+				<key>systemData</key>
+				<dict>
+					<key>access</key>
+					<string>read-write</string>
+					<key>domains</key>
+					<array>
+						<string>com.apple.bird</string>
+					</array>
+					<key>operations</key>
+					<array>
+						<string>lookup</string>
+						<string>create</string>
+					</array>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

```
### AppStore

> `/private/var/staged_system_apps/AppStore.app/AppStore`

```diff

+	<key>com.apple.private.amsondevicestoraged</key>
+	<true/>

+	<key>com.apple.private.servicesintelligence</key>
+	<true/>

+		<string>com.apple.servicesintelligenced</string>
+		<string>com.apple.amsondevicestoraged.xpc</string>

+		<string>com.apple.storeservices.itfe</string>

```
### AppleTV

> `/private/var/staged_system_apps/AppleTV.app/AppleTV`

```diff

+	<key>com.apple.private.appstorecomponents.small-offer-button</key>
+	<true/>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+	<key>com.apple.NanoPassbook.IDVRemoteDeviceService.session.client</key>
+	<true/>

```
### Fitness

> `/private/var/staged_system_apps/Fitness.app/Fitness`

```diff

+	<key>com.apple.appleaccount.identity.read</key>
+	<true/>

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+		<string>com.apple.aa.identity.xpc</string>

```
### Games

> `/private/var/staged_system_apps/Games.app/Games`

```diff

+	<key>com.apple.private.appstorecomponents.small-offer-button</key>
+	<true/>

+	<key>com.apple.private.coreservices.canopenactivity</key>
+	<true/>

+		<string>com.apple.storeservices.itfe</string>

```
### Home

> `/private/var/staged_system_apps/Home.app/Home`

```diff

+	<key>com.apple.private.LocalAuthentication.SaveExtractableCredential</key>
+	<true/>

+	<key>com.apple.private.ageRange</key>
+	<true/>

```
### HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
+	<key>com.apple.accounts.appleidauthentication.defaultaccess</key>
+	<true/>
+	<key>com.apple.accounts.idms.fullaccess</key>
+	<true/>
+	<key>com.apple.accounts.inactive.fullaccess</key>
+	<true/>
+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+		<string>re6Zb+zwFKJNlkQTUeT+/w</string>
+	</array>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

```
### GenerativePlaygroundAppIntents

> `/private/var/staged_system_apps/Image Playground.app/Extensions/GenerativePlaygroundAppIntents.appex/GenerativePlaygroundAppIntents`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.private.appintents-attribution-override</key>
+	<true/>

```
### Image Playground

> `/private/var/staged_system_apps/Image Playground.app/Image Playground`

```diff

+		<string>/private/var/containers/Bundle/Application/</string>
+		<string>/Applications/</string>

+		<string>com.apple.applicationaccess</string>

+		<string>com.apple.privatecloudcompute</string>

+		<string>com.apple.applicationaccess</string>

```
### GenerativePlaygroundMessagesAppExtension

> `/private/var/staged_system_apps/Image Playground.app/PlugIns/GenerativePlaygroundMessagesAppExtension.appex/GenerativePlaygroundMessagesAppExtension`

```diff

+		<string>/private/var/containers/Bundle/Application/</string>
+		<string>/Applications/</string>

```
### Magnifier

> `/private/var/staged_system_apps/Magnifier.app/Magnifier`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.authkit.client.private</key>
+	<true/>

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.Accessibility</string>
+	</array>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>
+		<string>com.apple.akd</string>
+		<string>com.apple.accountsd.accountmanager</string>

```
### Maps

> `/private/var/staged_system_apps/Maps.app/Maps`

```diff

+	<key>com.apple.private.appintents.exception.continue-in-foreground-no-prompt-allowed</key>
+	<true/>

```
### MobileNotes

> `/private/var/staged_system_apps/MobileNotes.app/MobileNotes`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

```
### MessagesNotificationExtension

> `/private/var/staged_system_apps/MobileSMS.app/PlugIns/MessagesNotificationExtension.appex/MessagesNotificationExtension`

```diff

+		<string>com.apple.suggestions</string>

```
### MessagesTranscriptExtension

> `/private/var/staged_system_apps/MobileSMS.app/PlugIns/MessagesTranscriptExtension.appex/MessagesTranscriptExtension`

```diff

+		<string>com.apple.suggestions</string>

```
### MobileSafari

> `/private/var/staged_system_apps/MobileSafari.app/MobileSafari`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.mobilesafari</string>

+	<key>com.apple.private.ageRange</key>
+	<true/>

+		<string>/AppleInternal/Library/Frameworks/ContextStagingIntents.framework</string>

```
### News

> `/private/var/staged_system_apps/News.app/News`

```diff

+	<key>com.apple.developer.background-tasks.continued-processing.inference</key>
+	<true/>

```
### Weather

> `/private/var/staged_system_apps/Weather.app/Weather`

```diff

+	<key>com.apple.private.ageRange</key>
+	<true/>

```

### 🆕 meminfo

> `/usr/bin/meminfo`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.kernel.get-kext-info</key>
	<true/>
	<key>com.apple.private.memoryinfo</key>
	<true/>
</dict>
</plist>

```
### perfpowermetricd

> `/usr/bin/perfpowermetricd`

```diff

-	<key>com.apple.backboardd.lastUserEventTime</key>
-	<true/>

+	<key>com.apple.private.attentionawareness</key>
+	<true/>

+		<string>com.apple.AttentionAwareness</string>

```
### powerlogHelperd

> `/usr/bin/powerlogHelperd`

```diff

-	<key>com.apple.backboardd.lastUserEventTime</key>
-	<true/>

+	<key>com.apple.private.attentionawareness</key>
+	<true/>

+		<string>com.apple.AttentionAwareness</string>

```
### PerfPowerServices

> `/usr/libexec/PerfPowerServices`

```diff

-	<key>com.apple.backboardd.lastUserEventTime</key>
-	<true/>

+	<key>com.apple.private.attentionawareness</key>
+	<true/>

+		<string>com.apple.AttentionAwareness</string>

```
### PerfPowerServicesExtended

> `/usr/libexec/PerfPowerServicesExtended`

```diff

-	<key>com.apple.backboardd.lastUserEventTime</key>
-	<true/>

+	<key>com.apple.private.attentionawareness</key>
+	<true/>

+		<string>com.apple.AttentionAwareness</string>

```
### aned

> `/usr/libexec/aned`

```diff

+	<key>com.apple.private.MobileContainerManager.allowed</key>
+	<true/>
+	<key>com.apple.private.MobileContainerManager.lookup</key>
+	<dict>
+		<key>app</key>
+		<true/>
+		<key>appData</key>
+		<true/>
+		<key>appGroup</key>
+		<true/>
+	</dict>

```
### appleh16camerad

> `/usr/libexec/appleh16camerad`

```diff

-		<string>IOUserClient</string>

```
### asktod

> `/usr/libexec/asktod`

```diff

-		<string>AskToBuy</string>

```
### assessmentagent

> `/usr/libexec/assessmentagent`

```diff

+	<key>com.apple.private.device-configuration.provider.allowed-provider-ids</key>
+	<array>
+		<string>com.apple.AutomaticAssessmentConfiguration</string>
+	</array>

+		<string>com.apple.DeviceConfigurationAgent.provider.async</string>

```
### atc

> `/usr/libexec/atc`

```diff

+	<key>com.apple.private.intelligenceplatform.client-identifier</key>
+	<string>com.apple.atc</string>
+	<key>com.apple.private.intelligenceplatform.use-cases</key>
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

```
### batteryintelligenced

> `/usr/libexec/batteryintelligenced`

```diff

+	<key>com.apple.private.clpc.analysis</key>
+	<true/>

+	<key>com.apple.private.ppm.superclient</key>
+	<true/>

+		<string>ApplePPMUserClient</string>
+		<string>AppleCLPCUserClient</string>

```
### ciphermld

> `/usr/libexec/ciphermld`

```diff

-	<key>com.apple.private.applemediaservices</key>
-	<true/>

-		<string>/Library/Caches/com.apple.AppleMediaServices/</string>

-		<string>com.apple.itunesstored</string>
-		<string>com.apple.jett.switch-itms</string>

```
### corerepaird

> `/usr/libexec/corerepaird`

```diff

+	<key>com.apple.CheckerBoard.services</key>
+	<true/>

+	<key>com.apple.private.iokit.battery-shipping-charge-limit</key>
+	<true/>

+		<string>com.apple.CheckerBoard.services</string>

```
### dasd

> `/usr/libexec/dasd`

```diff

+		<string>Device.KeybagLocked</string>

```
### duetexpertd

> `/usr/libexec/duetexpertd`

```diff

+		<string>kTCCServiceSiriAccess</string>
+	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>

```
### enhancedloggingd

> `/usr/libexec/enhancedloggingd`

```diff

+	<key>com.apple.authkit.client.internal</key>
+	<true/>

+		<string>com.apple.AppleServiceToolkit</string>

+		<string>com.apple.AppleServiceToolkit</string>

```
### feedbackd

> `/usr/libexec/feedbackd`

```diff

+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>FeedbackDonationFetch</key>
+		<dict>
+			<key>Streams</key>
+			<array>
+				<string>Feedback.TextToTextEvaluationData</string>
+				<string>Feedback.TextToImageEvaluationData</string>
+				<string>Feedback.TextImageToImageEvaluationData</string>
+				<string>Feedback.EvaluationResponse</string>
+			</array>
+		</dict>
+		<key>FeedbackDuplicateCheck</key>
+		<dict>
+			<key>Streams</key>
+			<array>
+				<string>Feedback.TextToTextEvaluationData</string>
+			</array>
+		</dict>
+	</dict>

```
### idcredd

> `/usr/libexec/idcredd`

```diff

+	<key>com.apple.payment.all-access</key>
+	<true/>

+		<string>com.apple.passd.library</string>

```
### inputanalyticsd

> `/usr/libexec/inputanalyticsd`

```diff

+	<key>com.apple.backboardd.displayTraits</key>
+	<true/>

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.mail</string>
+	</array>

+		<string>com.apple.backboard.display.services</string>

+		<string>com.apple.assistant.support</string>

```
### linkd

> `/usr/libexec/linkd`

```diff

+	<key>com.apple.PerfPowerServices.data-donation</key>
+	<true/>

+		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>
+		<string>com.apple.powerlog.plxpclogger.xpc</string>

```
### manageddeviced

> `/usr/libexec/manageddeviced`

```diff

+	<key>com.apple.private.persona-read-all</key>
+	<true/>

```
### mediaplaybackd

> `/usr/libexec/mediaplaybackd`

```diff

+	<key>com.apple.translation.can-override-client-pid</key>
+	<true/>

```
### modelmanagerd

> `/usr/libexec/modelmanagerd`

```diff

-	<true/>
-	<key>com.apple.runningboard.terminateprocess</key>

```
### nearbyd

> `/usr/libexec/nearbyd`

```diff

+	<key>com.apple.locationd.use-wireless-client-info</key>
+	<true/>

```
### nsurlsessiond

> `/usr/libexec/nsurlsessiond`

```diff

+	<key>com.apple.private.activityprogress.ui.preserve-failure-subtitle</key>
+	<true/>

```
### powerexperienced

> `/usr/libexec/powerexperienced`

```diff

+	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/Library/Trial/</string>
+	</array>

```
### riskdatad

> `/usr/libexec/riskdatad`

```diff

-	<key>abs-client</key>
-	<string>143531244</string>

```
### runningboardd

> `/usr/libexec/runningboardd`

```diff

+	<key>com.apple.private.xpc.launchd.allow-set-bundle-path</key>
+	<true/>

```
### searchpartyd

> `/usr/libexec/searchpartyd`

```diff

+	<key>com.apple.geoservices.setanydefault</key>
+	<true/>

```
### sharingd

> `/usr/libexec/sharingd`

```diff

+	<key>com.apple.private.attentionawareness</key>
+	<true/>
+	<key>com.apple.private.attentionawareness.poll</key>
+	<true/>

+		<string>com.apple.AttentionAwareness</string>

+	<key>com.apple.trial.client</key>
+	<true/>

```
### spotlightknowledged.graph

> `/usr/libexec/spotlightknowledged.graph`

```diff

+	<key>com.apple.private.corespotlight.allowcarplayapps</key>
+	<true/>

```
### spotlightknowledged.updater

> `/usr/libexec/spotlightknowledged.updater`

```diff

+	<key>com.apple.private.corespotlight.allowcarplayapps</key>
+	<true/>

```
### swtransparencyd

> `/usr/libexec/swtransparencyd`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

```
### symptomsd

> `/usr/libexec/symptomsd`

```diff

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

```
### symptomsd-helper

> `/usr/libexec/symptomsd-helper`

```diff

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

```
### terminusd

> `/usr/libexec/terminusd`

```diff

-		<string>Library/Caches/com.apple.HomeKit.configurations/</string>

-		<string>com.apple.TVOSUpdate</string>

```
### textcontextd

> `/usr/libexec/textcontextd`

```diff

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.mail</string>
+	</array>

+		<string>com.apple.servicesanalytics.xpc</string>

```
### textunderstandingd

> `/usr/libexec/textunderstandingd`

```diff

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.mail</string>
+	</array>

+		<string>com.apple.privatecloudcompute</string>

```
### toolkitd

> `/usr/libexec/toolkitd`

```diff

+	<key>com.apple.PerfPowerServices.data-donation</key>
+	<true/>

+		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>

+		<string>com.apple.powerlog.plxpclogger.xpc</string>

```
### trustd

> `/usr/libexec/trustd`

```diff

+		<string>com.apple.timed.xpc</string>

```
### uarphidd

> `/usr/libexec/uarphidd`

```diff

-	<string>com.apple.uarphidd</string>
+	<string>com.apple.MobileAccessoryUpdater</string>

```
### appleh16camerad

> `/usr/sbin/appleh16camerad`

```diff

-		<string>IOUserClient</string>

```


### ExclaveOS


### 🆕 ACIExclaveProcKit

> `/System/ExclaveKit/System/Library/PrivateFrameworks/ACIExclaveProcKit.framework/ACIExclaveProcKit`

- No entitlements *(yet)*


