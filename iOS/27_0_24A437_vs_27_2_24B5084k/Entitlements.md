## 🔑 Entitlements

### filesystem

### AAUIViewService

> `/Applications/AAUIViewService.app/AAUIViewService`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### AMSEngagementViewService

> `/Applications/AMSEngagementViewService.app/AMSEngagementViewService`

```diff

+	<key>com.apple.private.fairplay.FPDI</key>
+	<dict>
+		<key>capabilities</key>
+		<array>
+			<integer>4014732562</integer>
+		</array>
+		<key>client-identifier</key>
+		<string>com.apple.AMSEngagementViewService</string>
+	</dict>

+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Library/Caches/com.apple.AppleMediaServices/</string>
+	</array>

+		<string>com.apple.fairplaydeviceidentityd</string>

```
### AXUIViewService

> `/Applications/AXUIViewService.app/AXUIViewService`

```diff

+		<string>com.apple.Preferences</string>

```
### AirDropUI

> `/Applications/AirDropUI.app/AirDropUI`

```diff

+	<key>com.apple.private.airdrop.client</key>
+	<true/>
+	<key>com.apple.private.airdrop.settings</key>
+	<true/>

```
### AppDistributionLaunchAngel

> `/Applications/AppDistributionLaunchAngel.app/AppDistributionLaunchAngel`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### AuthKitUIService

> `/Applications/AuthKitUIService.app/AuthKitUIService`

```diff

+	<key>com.apple.QuartzCore.secure-mode</key>
+	<true/>

+	<key>com.apple.cdp.statemachine</key>
+	<true/>
+	<key>com.apple.cdp.utility</key>
+	<true/>
+	<key>com.apple.cdp.walrus</key>
+	<true/>

+		<string>com.apple.telephonyutilities.callservicesdaemon.callstatecontroller</string>
+		<string>com.apple.telephonyutilities.callservicesdaemon.callcapabilities</string>

```
### ClockAngel

> `/Applications/ClockAngel.app/ClockAngel`

```diff

+	<key>com.apple.private.menubar.allow-scene-override-associated-apps</key>
+	<true/>

```
### Diagnostics

> `/Applications/Diagnostics.app/Diagnostics`

```diff

+	<key>com.apple.springboard.sceneaccessory.prototyping</key>
+	<true/>

```
### Family

> `/Applications/Family.app/Family`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### FamilyOutOfProcessUIExtension

> `/Applications/FamilyExtensionHost.app/Extensions/FamilyOutOfProcessUIExtension.appex/FamilyOutOfProcessUIExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### Feedback Assistant iOS

> `/Applications/Feedback Assistant iOS.app/Feedback Assistant iOS`

```diff

+	<key>com.apple.appprotectiond.guard.access</key>
+	<true/>
+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>
+	<key>com.apple.appprotectiond.write.access</key>
+	<true/>

+		<string>com.apple.appprotectiond.read</string>
+		<string>com.apple.appprotectiond.write</string>
+		<string>com.apple.appprotectiond.guard</string>

```
### GameCenterUIService

> `/Applications/GameCenterUIService.app/GameCenterUIService`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### HDSViewService

> `/Applications/HDSViewService.app/HDSViewService`

```diff

+	<key>com.apple.private.application-service-browse</key>
+	<true/>

+		<string>com.apple.mobileactivationd</string>

+		<string>com.apple.MobileStoreDemo.test</string>

```
### HomeControlService

> `/Applications/HomeControlService.app/HomeControlService`

```diff

+	<key>com.apple.developer.icloud-container-identifiers</key>
+	<array/>
+	<key>com.apple.developer.icloud-services</key>
+	<array>
+		<string>CloudKit</string>
+	</array>
+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.Home</string>

+	<key>com.apple.findmy.findmylocate.settings</key>
+	<true/>

+	<key>com.apple.private.cloudkit.serviceNameForContainerMap</key>
+	<dict>
+		<key>com.apple.homeapp.config</key>
+		<string>com.apple.homekit</string>
+		<key>com.apple.homekit.camera.clips</key>
+		<string>com.apple.homekit</string>
+		<key>com.apple.homekit.events</key>
+		<string>com.apple.homekit</string>
+	</dict>
+	<key>com.apple.private.cloudkit.setEnvironment</key>
+	<true/>
+	<key>com.apple.private.cloudkit.spi</key>
+	<true/>

+	<key>com.apple.private.homekit.cameraclips</key>
+	<true/>

+	<key>com.apple.private.security.storage.Home</key>
+	<true/>
+	<key>com.apple.private.security.storage.HomeKit</key>
+	<true/>
+	<key>com.apple.private.system-keychain</key>
+	<true/>

+		<string>com.apple.ProductKitService</string>

+		<string>com.apple.ProductKitService</string>

+	<key>keychain-access-groups</key>
+	<array>
+		<string>apple</string>
+	</array>

```
### HomeUIService

> `/Applications/HomeUIService.app/HomeUIService`

```diff

+	<key>com.apple.appprotectiond.guard.access</key>
+	<true/>
+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

+	<key>com.apple.frontboard.launchapplications</key>
+	<true/>

+	<key>com.apple.linkd.registry</key>
+	<true/>
+	<key>com.apple.linkd.transcript.privileged</key>
+	<true/>

+	<key>com.apple.locationd.usage_oracle</key>
+	<true/>

+	<key>com.apple.private.appintents.connection</key>
+	<true/>
+	<key>com.apple.private.appintents.exception.background-task-allowed</key>
+	<true/>
+	<key>com.apple.private.appintents.extension-host</key>
+	<true/>

+	<key>com.apple.runningboard.launchprocess</key>
+	<true/>
+	<key>com.apple.runningboard.process-state</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.PrivacyDisclosure/</string>
+	</array>

+		<string>com.apple.appprotectiond.guard</string>
+		<string>com.apple.appprotectiond.read</string>

+		<string>com.apple.linkd.extension</string>
+		<string>com.apple.linkd.mediator</string>
+		<string>com.apple.linkd.registry</string>
+		<string>com.apple.linkd.transcript</string>

+	<key>com.apple.security.temporary-exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.PrivacyDisclosure/</string>
+	</array>

+		<string>com.apple.appprotectiond.guard</string>
+		<string>com.apple.appprotectiond.read</string>

+		<string>com.apple.linkd.extension</string>
+		<string>com.apple.linkd.mediator</string>
+		<string>com.apple.linkd.registry</string>
+		<string>com.apple.linkd.transcript</string>

```
### ImagePlaygroundPosterExtension

> `/Applications/ImagePlaygroundPosterApp.app/Extensions/ImagePlaygroundPosterExtension.appex/ImagePlaygroundPosterExtension`

```diff

+	<key>com.apple.springboard.fetchDisplayConfigs</key>
+	<true/>

+	<key>com.apple.springboard.wallpaper.display-configuration</key>
+	<true/>

```
### InCallService

> `/Applications/InCallService.app/InCallService`

```diff

+	<key>com.apple.developer.conversation-accessibility</key>
+	<true/>

+	<key>com.apple.private.ids.messaging</key>
+	<array>
+		<string>com.apple.private.alloy.nameandphoto</string>
+		<string>com.apple.madrid</string>
+	</array>
+	<key>com.apple.private.ids.messaging.urgent-priority</key>
+	<array>
+		<string>com.apple.private.alloy.nameandphoto</string>
+	</array>

+	<key>com.apple.private.ids.registration</key>
+	<array>
+		<string>com.apple.private.alloy.nameandphoto</string>
+	</array>

+		<string>accessibility-interpreter</string>

```
### LimitedModeShieldApp

> `/Applications/LimitedModeShieldApp.app/LimitedModeShieldApp`

```diff

+	<key>com.apple.frontboard.launchapplications</key>
+	<true/>

```
### LocalAuthenticationUIService

> `/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService`

```diff

+	<key>com.apple.backboardd.displayTraits</key>
+	<true/>

```
### MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

```diff

+	<key>com.apple.private.translation</key>
+	<true/>

+		<string>com.apple.translationd</string>

```
### MomentsUIService

> `/Applications/MomentsUIService.app/MomentsUIService`

```diff

+		<string>Intelligence.Usage</string>
+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.DeviceActivity</string>
+	</array>

```
### NetworkEndpointPickerUI

> `/Applications/NetworkEndpointPickerUI.app/NetworkEndpointPickerUI`

```diff

+	<key>com.apple.private.airdrop.client</key>
+	<true/>

```
### PASViewService

> `/Applications/PASViewService.app/PASViewService`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

+	<key>com.apple.generativeexperiences.ExternalProviderService</key>
+	<true/>

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

+		<string>com.apple.generativeexperiences.ExternalProviderService</string>
+		<string>com.apple.generativeexperiences.ExternalProviderTCCManagingXPC</string>

```
### SIMSetupUIService

> `/Applications/SIMSetupUIService.app/SIMSetupUIService`

```diff

+	<key>com.apple.system.diagnostics.iokit-properties</key>
+	<true/>

```
### ScreenTimeWidgetExtension

> `/Applications/Screen Time.app/PlugIns/ScreenTimeWidgetExtension.appex/ScreenTimeWidgetExtension`

```diff

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

```
### ScreenTimeSettingsShield

> `/Applications/ScreenTimeSettingsShield.app/ScreenTimeSettingsShield`

```diff

+	<key>com.apple.private.screen-time</key>
+	<true/>

+		<string>com.apple.ScreenTimeAgent.private</string>

```
### SharingViewService

> `/Applications/SharingViewService.app/SharingViewService`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

+	<key>com.apple.private.airdrop.client</key>
+	<true/>

```
### ShortcutsUI

> `/Applications/ShortcutsUI.app/ShortcutsUI`

```diff

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

```

### 🆕 Siri AI

> `/Applications/Siri AI.app/Siri AI`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.campo</string>
	<key>aps-connection-initiate</key>
	<true/>
	<key>aps-environment</key>
	<string>development</string>
	<key>com.apple.CommCenter.fine-grained</key>
	<array>
		<string>spi</string>
		<string>phone</string>
	</array>
	<key>com.apple.Contacts.database-allow</key>
	<true/>
	<key>com.apple.CoreRoutine.Application</key>
	<true/>
	<key>com.apple.CoreRoutine.LocationOfInterest</key>
	<true/>
	<key>com.apple.Pasteboard.background-access</key>
	<true/>
	<key>com.apple.QuartzCore.global-capture</key>
	<true/>
	<key>com.apple.QuartzCore.secure-mode</key>
	<true/>
	<key>com.apple.StatusKit.subscribe.types</key>
	<array>
		<string>com.apple.focus.status</string>
		<string>com.apple.availability</string>
	</array>
	<key>com.apple.SystemConfiguration.SCPreferences-write-access</key>
	<array>
		<string>com.apple.radios.plist</string>
	</array>
	<key>com.apple.TapToRadarKit.service-access</key>
	<true/>
	<key>com.apple.UIKit.vends-view-services</key>
	<true/>
	<key>com.apple.accounts.appleaccount.fullaccess</key>
	<true/>
	<key>com.apple.apfs.unlock</key>
	<true/>
	<key>com.apple.app-distribution.private</key>
	<true/>
	<key>com.apple.appprotectiond.guard.access</key>
	<true/>
	<key>com.apple.appprotectiond.read.access</key>
	<true/>
	<key>com.apple.appprotectiond.write.access</key>
	<true/>
	<key>com.apple.arkit.camera-access-private-formats.allow</key>
	<true/>
	<key>com.apple.assistant.analytics-observation</key>
	<true/>
	<key>com.apple.assistant.cdm.client</key>
	<true/>
	<key>com.apple.assistant.client</key>
	<true/>
	<key>com.apple.assistant.security</key>
	<true/>
	<key>com.apple.assistant.settings</key>
	<true/>
	<key>com.apple.assistant.uibridge-service</key>
	<true/>
	<key>com.apple.assistantd.odeon-remote</key>
	<true/>
	<key>com.apple.assistantisland.client</key>
	<true/>
	<key>com.apple.assistantisland.stage-scene</key>
	<true/>
	<key>com.apple.authkit.client.private</key>
	<true/>
	<key>com.apple.avfoundation.allow-identifying-output-device-details</key>
	<true/>
	<key>com.apple.avfoundation.allow-system-wide-context</key>
	<true/>
	<key>com.apple.avfoundation.allows-set-output-device</key>
	<true/>
	<key>com.apple.backboard.displaybrightness</key>
	<true/>
	<key>com.apple.backboardd.cancelsTouchesInHostedContent</key>
	<true/>
	<key>com.apple.backboardd.hostCanRequireTouchesFromHostedContent</key>
	<true/>
	<key>com.apple.backlight.disable_wake_gesture_assertion</key>
	<true/>
	<key>com.apple.backlight.force_active_assertion</key>
	<true/>
	<key>com.apple.backlight.prevent_idle_assertion</key>
	<true/>
	<key>com.apple.bannerkit.post</key>
	<true/>
	<key>com.apple.bluetooth.system</key>
	<true/>
	<key>com.apple.bulletinboard.observer</key>
	<true/>
	<key>com.apple.bulletinboard.settings</key>
	<true/>
	<key>com.apple.caraccessoryframework.gatekeeper</key>
	<true/>
	<key>com.apple.carousel.flashlight.access</key>
	<true/>
	<key>com.apple.chrono.controlcenter</key>
	<true/>
	<key>com.apple.chrono.controls</key>
	<true/>
	<key>com.apple.chrono.widgetRenderer</key>
	<true/>
	<key>com.apple.chronoservices</key>
	<true/>
	<key>com.apple.clarityboard.shows-scene</key>
	<true/>
	<key>com.apple.coreaudio.allow-amr-decode</key>
	<true/>
	<key>com.apple.coreduetd.allow</key>
	<true/>
	<key>com.apple.coreduetd.context</key>
	<true/>
	<key>com.apple.coreduetd.people</key>
	<true/>
	<key>com.apple.coremedia.allow-mpeg4streaming</key>
	<true/>
	<key>com.apple.coremedia.allow-protected-content-playback</key>
	<true/>
	<key>com.apple.corespeech.corespeechd.xpc</key>
	<true/>
	<key>com.apple.corespotlight.privateindex.unsandboxed</key>
	<true/>
	<key>com.apple.developer.arkit.main-camera-access.allow</key>
	<true/>
	<key>com.apple.developer.carplay-voice-based-conversation</key>
	<true/>
	<key>com.apple.developer.declared-age-range</key>
	<true/>
	<key>com.apple.developer.extension-host.widget-extension</key>
	<true/>
	<key>com.apple.developer.icloud-container-environment</key>
	<string>Production</string>
	<key>com.apple.developer.icloud-container-identifiers</key>
	<array>
		<string>com.apple.notes</string>
	</array>
	<key>com.apple.developer.icloud-services</key>
	<true/>
	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
	<string>com.apple.campo</string>
	<key>com.apple.devicesharing.guest-user-mode-client</key>
	<true/>
	<key>com.apple.duet.activityscheduler.allow</key>
	<true/>
	<key>com.apple.duet.expertcenter.consumer</key>
	<true/>
	<key>com.apple.duetexpertd.assistant-actions</key>
	<true/>
	<key>com.apple.facetimemessagestored.service</key>
	<array>
		<string>access-facetime-messaging</string>
	</array>
	<key>com.apple.familycircle.agent</key>
	<true/>
	<key>com.apple.feedbackd.remote-evaluation</key>
	<true/>
	<key>com.apple.filederivatives.derive</key>
	<true/>
	<key>com.apple.filederivatives.list</key>
	<true/>
	<key>com.apple.fileprovider.enumerate</key>
	<true/>
	<key>com.apple.fileprovider.extension-host</key>
	<true/>
	<key>com.apple.fileprovider.fetch-url</key>
	<true/>
	<key>com.apple.findmy.findmylocate.friendshipservice</key>
	<true/>
	<key>com.apple.findmy.findmylocate.locationservice</key>
	<true/>
	<key>com.apple.findmy.findmylocate.settings</key>
	<true/>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
	<key>com.apple.frontboard.systemappservices</key>
	<true/>
	<key>com.apple.frontboardservices.display-layout-monitor</key>
	<true/>
	<key>com.apple.generativeexperiences.ExternalPartnerCredentialStorage</key>
	<true/>
	<key>com.apple.generativeexperiences.ExternalProviderService</key>
	<true/>
	<key>com.apple.generativeexperiences.agentMediaStore</key>
	<true/>
	<key>com.apple.generativeexperiences.agentSessionStore</key>
	<true/>
	<key>com.apple.generativeexperiences.availabilityService</key>
	<true/>
	<key>com.apple.generativeexperiences.corefollowup</key>
	<true/>
	<key>com.apple.geoanalyticsd.telemetry</key>
	<true/>
	<key>com.apple.icloud.fmfd.access</key>
	<true/>
	<key>com.apple.icloud.searchpartyd.securelocations.access</key>
	<true/>
	<key>com.apple.intelligenceflow.context</key>
	<true/>
	<key>com.apple.intelligenceflow.contextIntelligence</key>
	<true/>
	<key>com.apple.intelligenceflow.contextTool</key>
	<true/>
	<key>com.apple.intelligenceflow.imageretrieval</key>
	<true/>
	<key>com.apple.intelligenceflow.internal</key>
	<true/>
	<key>com.apple.intelligenceflow.orchestrator</key>
	<true/>
	<key>com.apple.intelligenceflow.orchestrator.features</key>
	<array>
		<string>executable-session</string>
		<string>debugging</string>
		<string>side-channel-debugging</string>
		<string>transcript-manipulation</string>
	</array>
	<key>com.apple.intelligenceflow.querydecoration</key>
	<true/>
	<key>com.apple.intelligenceflow.toolbox</key>
	<true/>
	<key>com.apple.intelligenceflow.transcript-entity-querying</key>
	<true/>
	<key>com.apple.intelligenceflow.transcript-entity-querying.query-all-groups</key>
	<true/>
	<key>com.apple.intelligenceflow.uiContext</key>
	<true/>
	<key>com.apple.intelligenceplatform.EntityResolution</key>
	<true/>
	<key>com.apple.intelligenceplatform.Knosis</key>
	<true/>
	<key>com.apple.intelligenceplatform.View</key>
	<true/>
	<key>com.apple.intelligenceplatform.knosis.indexes.read-only</key>
	<array>
		<string>stableGraphIndex</string>
		<string>eventGraphIndex</string>
		<string>liveGlobalKnowledgeIndex</string>
		<string>staticGlobalKnowledgeIndex</string>
		<string>ontologyIndex</string>
	</array>
	<key>com.apple.intents.extension.discovery</key>
	<true/>
	<key>com.apple.intents.intents-image-service</key>
	<true/>
	<key>com.apple.intents.uiextension.discovery</key>
	<true/>
	<key>com.apple.itunesstored.lookup</key>
	<true/>
	<key>com.apple.itunesstored.private</key>
	<true/>
	<key>com.apple.keystore.allow.background-processing-assertions</key>
	<true/>
	<key>com.apple.keystore.device</key>
	<true/>
	<key>com.apple.keystore.lockassertion</key>
	<true/>
	<key>com.apple.linkd.registry</key>
	<true/>
	<key>com.apple.linkd.transcript.privileged</key>
	<true/>
	<key>com.apple.locationd.authorizeapplications</key>
	<true/>
	<key>com.apple.locationd.effective_bundle</key>
	<true/>
	<key>com.apple.locationd.time_zone</key>
	<true/>
	<key>com.apple.locationd.usage_oracle</key>
	<true/>
	<key>com.apple.mediaanalysisd.client</key>
	<true/>
	<key>com.apple.mediaremote.remote-control-discovery</key>
	<true/>
	<key>com.apple.mkb.usersession.info</key>
	<true/>
	<key>com.apple.mobileassetd.v2</key>
	<true/>
	<key>com.apple.mobilemail.mailservices</key>
	<true/>
	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.nano.nanoregistry.generalaccess</key>
	<true/>
	<key>com.apple.nano.nanoresourcegrabber</key>
	<true/>
	<key>com.apple.pegasus.context</key>
	<true/>
	<key>com.apple.photos.bourgeoisie</key>
	<true/>
	<key>com.apple.powerd.lowpowermode.allow</key>
	<true/>
	<key>com.apple.powerexperience.powermode.update</key>
	<true/>
	<key>com.apple.private.CacheDelete</key>
	<array>
		<string>CLIENT_ENTITLEMENT</string>
		<string>PURGE_ENTITLEMENT</string>
		<string>CANCEL_PURGE_ENTITLEMENT</string>
	</array>
	<key>com.apple.private.CallHistory.read</key>
	<true/>
	<key>com.apple.private.ClipServices</key>
	<true/>
	<key>com.apple.private.CoreAuthentication.BackgroundUI</key>
	<true/>
	<key>com.apple.private.InstallCoordination.allowed</key>
	<true/>
	<key>com.apple.private.MobileContainerManager.allowed</key>
	<true/>
	<key>com.apple.private.MobileContainerManager.otherIdLookup</key>
	<true/>
	<key>com.apple.private.Safari.History</key>
	<true/>
	<key>com.apple.private.WebClips.read-write</key>
	<true/>
	<key>com.apple.private.accounts.allaccounts</key>
	<true/>
	<key>com.apple.private.appintents-attribution-override</key>
	<true/>
	<key>com.apple.private.appintents-bundle-absolute-paths</key>
	<array>
		<string>/System/Library/PrivateFrameworks/SpotlightUIShared.framework</string>
		<string>/System/Library/PrivateFrameworks/SearchUI.framework</string>
		<string>/System/Library/PrivateFrameworks/SiriSharedUI.framework/</string>
	</array>
	<key>com.apple.private.appintents.extension-host</key>
	<true/>
	<key>com.apple.private.appintents.trusted-entity-identifier</key>
	<true/>
	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
	<true/>
	<key>com.apple.private.applemediaservices</key>
	<true/>
	<key>com.apple.private.application-service-browse</key>
	<true/>
	<key>com.apple.private.appstorecomponents</key>
	<true/>
	<key>com.apple.private.appstorecomponents.media-client-id</key>
	<string>com.apple.Siri.app</string>
	<key>com.apple.private.appstorecomponents.media-client-version</key>
	<string>1</string>
	<key>com.apple.private.arkit.authorization</key>
	<array>
		<string>eyeTracking</string>
		<string>handTracking</string>
	</array>
	<key>com.apple.private.assets.accessible-asset-types</key>
	<array>
		<string>com.apple.MobileAsset.TempMorphunData</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingNL</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingNLOverrides</string>
		<string>com.apple.MobileAsset.SpotlightResources</string>
		<string>com.apple.MobileAsset.LinguisticData</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingAttentionAssets</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriDictationAssets</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingAsrHammer</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriExperienceCam</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriInferredHelpfulness</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriTextToSpeech</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingAsrAssistant</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriFindMyConfigurationFiles</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingAsrUaap</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingMorphun</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriDialogAssets</string>
		<string>com.apple.MobileAsset.UAF.Siri.TextToSpeech</string>
	</array>
	<key>com.apple.private.assets.bypass-asset-types-check</key>
	<true/>
	<key>com.apple.private.attentionawareness</key>
	<true/>
	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
	<dict>
		<key>type</key>
		<string>bundleID</string>
		<key>value</key>
		<string>com.apple.SiriApp</string>
	</dict>
	<key>com.apple.private.biome.client-identifier</key>
	<string>com.apple.CampoApp</string>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Accessibility.ReduceMotion</string>
		<string>Accessibility.ReduceTransparency</string>
		<string>Accessibility.ColorFilters</string>
		<string>Accessibility.SmartInvert</string>
		<string>Accessibility.VoiceOver</string>
		<string>Accessibility.Zoom</string>
		<string>Accessibility.VoiceControl</string>
		<string>Accessibility.Contrast</string>
		<string>Accessibility.ClassicInvert</string>
		<string>Accessibility.WhitePoint</string>
		<string>App.InFocus</string>
		<string>App.Install</string>
		<string>AskToBuy</string>
		<string>CarPlay.Connected</string>
		<string>Clock.Alarm</string>
		<string>Family.ScreenTime.ChildState</string>
		<string>Device.Display.AlwaysOn</string>
		<string>Device.Display.Appearance</string>
		<string>Device.Display.NightShift</string>
		<string>Device.ScreenLocked</string>
		<string>Device.SilentMode</string>
		<string>Device.Display.TrueTone</string>
		<string>Device.Power.EnergyMode</string>
		<string>Device.Wireless.AirplaneMode</string>
		<string>Device.Wireless.BluetoothPowerEnabled</string>
		<string>Device.Wireless.CellularDataEnabled</string>
		<string>Device.Wireless.WiFiAvailabilityStatus</string>
		<string>Media.NowPlaying</string>
		<string>Motion.Activity</string>
		<string>ScreenTimeRequest</string>
		<string>UserFocus.ComputedMode</string>
		<string>UserFocusComputedMode</string>
		<string>IntelligenceFlow.Transcript.Datastream</string>
		<string>SiriExecution</string>
		<string>AppLaunch</string>
		<string>AppIntent</string>
	</array>
	<key>com.apple.private.biome.read-write</key>
	<array>
		<string>Siri.PostSiriEngagement</string>
		<string>PostSiriEngagement</string>
		<string>Motion.ObservedBehavior</string>
		<string>Motion.TripSegment</string>
		<string>Siri.FeedbackLearning.UserInteractions</string>
		<string>IntelligenceEngine.Interaction.Donation</string>
		<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>
		<string>GenerativeModels.GenerativeFunctions.Events</string>
		<string>GenerativeModels.GenerativeFunctions.ModelIO</string>
		<string>AppleIntelligence.Reporting.Invocation.Step</string>
		<string>IntelligenceFlow.Telemetry</string>
		<string>IntelligenceFlow.ResponseGeneration</string>
		<string>IntelligenceFlow.ExecutorTelemetry</string>
		<string>Intelligence.Usage</string>
	</array>
	<key>com.apple.private.bmk.allow</key>
	<true/>
	<key>com.apple.private.calendar.allow-integrations</key>
	<true/>
	<key>com.apple.private.calendar.allow-suggestions</key>
	<true/>
	<key>com.apple.private.canGetAppLinkInfo</key>
	<true/>
	<key>com.apple.private.contacts</key>
	<true/>
	<key>com.apple.private.contactsui</key>
	<true/>
	<key>com.apple.private.coreaudio.borrowaudiosession.allow</key>
	<true/>
	<key>com.apple.private.corerecents</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.coreservices.canopenactivity</key>
	<true/>
	<key>com.apple.private.corespotlight.internal</key>
	<true/>
	<key>com.apple.private.corespotlight.search.internal</key>
	<true/>
	<key>com.apple.private.corespotlight.sender</key>
	<true/>
	<key>com.apple.private.corewifi</key>
	<true/>
	<key>com.apple.private.dmd.emergency-mode</key>
	<true/>
	<key>com.apple.private.dmd.policy</key>
	<true/>
	<key>com.apple.private.donotdisturb.mode.assertion.client-identifiers</key>
	<array>
		<string>com.apple.siri.Settings</string>
	</array>
	<key>com.apple.private.donotdisturb.mode.assertion.user-requested.client-identifiers</key>
	<array>
		<string>com.apple.siri.Settings</string>
	</array>
	<key>com.apple.private.donotdisturb.state.request.client-identifiers</key>
	<array>
		<string>com.apple.siri.Settings</string>
	</array>
	<key>com.apple.private.donotdisturb.state.updates.client-identifiers</key>
	<array>
		<string>com.apple.siri.Settings</string>
	</array>
	<key>com.apple.private.externalaccessory.showallaccessories</key>
	<true/>
	<key>com.apple.private.familycircle</key>
	<true/>
	<key>com.apple.private.feedback.centralized-feedback</key>
	<true/>
	<key>com.apple.private.feedback.drafting</key>
	<true/>
	<key>com.apple.private.generativesearch.client.search</key>
	<true/>
	<key>com.apple.private.hid.client.event-dispatch.internal</key>
	<true/>
	<key>com.apple.private.hid.client.event-monitor</key>
	<true/>
	<key>com.apple.private.imcore.imagent</key>
	<true/>
	<key>com.apple.private.imcore.imdpersistence.database-access</key>
	<true/>
	<key>com.apple.private.imcore.spi.database-access</key>
	<true/>
	<key>com.apple.private.ind.client</key>
	<true/>
	<key>com.apple.private.intelligenceflow.group-identifier</key>
	<string>com.apple.intelligenceflow</string>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>SpotlightEngagementData</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>App.InFocus</string>
				<string>App.Intent</string>
				<string>SystemSettings.SearchTerms</string>
				<string>Media.NowPlaying</string>
			</array>
		</dict>
		<key>com.apple.spotlightui</key>
		<dict>
			<key>Search</key>
			<array>
				<string>Global</string>
				<string>SiriTranscript</string>
				<string>SiriTranscriptConversation</string>
				<string>Mail</string>
				<string>DraftMail</string>
				<string>MailAttachment</string>
			</array>
		</dict>
		<key>generativesearch</key>
		<dict>
			<key>Search</key>
			<array>
				<string>SiriTranscript</string>
				<string>SiriTranscriptConversation</string>
				<string>UnknownEntityType</string>
			</array>
		</dict>
		<key>iftool.dump-stream</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>IntelligenceFlow.Telemetry</string>
				<string>IntelligenceFlow.ResponseGeneration</string>
				<string>IntelligenceFlow.ExecutorTelemetry</string>
			</array>
		</dict>
	</dict>
	<key>com.apple.private.intelligenceplatform.views.read-only</key>
	<array>
		<string>siriRemembers</string>
		<string>visualIdentifier</string>
		<string>nerdSummary</string>
		<string>behavioralPopularitySignals</string>
		<string>nerdEmbeddingsPeopleTable</string>
		<string>peopleAliasECR</string>
		<string>entitySummary</string>
		<string>entityAliasECR</string>
		<string>entitySubgraph</string>
		<string>peopleSubgraph</string>
		<string>appleMusicEventSubgraph</string>
		<string>appleMusicEventMap</string>
		<string>people</string>
		<string>eventSubgraph</string>
		<string>relevance</string>
		<string>inferenceFeaturesECR</string>
		<string>appEntityRelevanceRanking</string>
		<string>personEntityRelevanceRanking</string>
		<string>loiEntityRelevanceRanking</string>
		<string>defaultResolverInteractions</string>
		<string>bundleIdMap</string>
		<string>ifContextSubgraph</string>
		<string>entitySimilarityFeatures</string>
	</array>
	<key>com.apple.private.iokit.powersource-control</key>
	<true/>
	<key>com.apple.private.kernel.override-cpumon</key>
	<true/>
	<key>com.apple.private.librarian.container-proxy</key>
	<true/>
	<key>com.apple.private.logging.diagnostic</key>
	<true/>
	<key>com.apple.private.managed-settings.effective-read</key>
	<true/>
	<key>com.apple.private.metadata.exattrs</key>
	<true/>
	<key>com.apple.private.mobileinstall.allowedSPI</key>
	<array>
		<string>UninstallForLaunchServices</string>
	</array>
	<key>com.apple.private.mobiletimerd</key>
	<true/>
	<key>com.apple.private.multiuserservices.session-claim.implicit-redemption</key>
	<true/>
	<key>com.apple.private.network.socket-delegate</key>
	<true/>
	<key>com.apple.private.network.system-token-fetch</key>
	<true/>
	<key>com.apple.private.nsurlsession.set-task-priority</key>
	<true/>
	<key>com.apple.private.parsec.default-client</key>
	<string>com.apple.campo</string>
	<key>com.apple.private.persona.read</key>
	<true/>
	<key>com.apple.private.photos.allowcollectionshare</key>
	<true/>
	<key>com.apple.private.photos.allowlibraryupgrade</key>
	<true/>
	<key>com.apple.private.photos.service.internal.cloud</key>
	<true/>
	<key>com.apple.private.photos.service.librarymanagement</key>
	<true/>
	<key>com.apple.private.remindd</key>
	<dict>
		<key>userInteractive</key>
		<true/>
	</dict>
	<key>com.apple.private.replay-kit</key>
	<true/>
	<key>com.apple.private.safariviewcontroller.custom-network-attribution-capable</key>
	<true/>
	<key>com.apple.private.sandbox.profile:embedded</key>
	<string>temporary-sandbox</string>
	<key>com.apple.private.screen-time</key>
	<true/>
	<key>com.apple.private.screen-time-settings</key>
	<true/>
	<key>com.apple.private.screentime-downtime</key>
	<true/>
	<key>com.apple.private.screentime-setup</key>
	<true/>
	<key>com.apple.private.security.arkit</key>
	<array>
		<string>allowImmersiveExemption</string>
	</array>
	<key>com.apple.private.security.no-container</key>
	<true/>
	<key>com.apple.private.security.restricted-application-groups</key>
	<array>
		<string>group.com.apple.intelligenceflow</string>
	</array>
	<key>com.apple.private.security.storage.AppDataContainers</key>
	<true/>
	<key>com.apple.private.security.storage.IntelligencePlatform</key>
	<true/>
	<key>com.apple.private.security.storage.Messages</key>
	<true/>
	<key>com.apple.private.security.storage.MessagesMetaData</key>
	<true/>
	<key>com.apple.private.security.storage.MobileDocuments</key>
	<true/>
	<key>com.apple.private.security.storage.Notes</key>
	<true/>
	<key>com.apple.private.security.storage.PhotosLibraries</key>
	<true/>
	<key>com.apple.private.security.storage.SiriInference</key>
	<true/>
	<key>com.apple.private.security.storage.SiriVocabulary</key>
	<true/>
	<key>com.apple.private.security.storage.Spotlight</key>
	<true/>
	<key>com.apple.private.security.storage.Weather</key>
	<true/>
	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
	<true/>
	<key>com.apple.private.security.storage.triald</key>
	<true/>
	<key>com.apple.private.sessionkit.listener</key>
	<true/>
	<key>com.apple.private.sessionkit.presentationObserver</key>
	<true/>
	<key>com.apple.private.sessionkit.prominentPresentationAssertionRequester</key>
	<true/>
	<key>com.apple.private.sharing.unlock-manager</key>
	<true/>
	<key>com.apple.private.siriappintentsd.orchestrator</key>
	<true/>
	<key>com.apple.private.sleepd</key>
	<true/>
	<key>com.apple.private.sociallayer.highlights</key>
	<true/>
	<key>com.apple.private.sportskit.client</key>
	<true/>
	<key>com.apple.private.subscriptionservice.all-sources.read-only</key>
	<true/>
	<key>com.apple.private.subscriptionservice.internal</key>
	<true/>
	<key>com.apple.private.suggestions.contacts</key>
	<true/>
	<key>com.apple.private.suggestions.events</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceAddressBook</string>
		<string>kTCCServiceCalendar</string>
		<string>kTCCServiceCamera</string>
		<string>kTCCServiceFaceID</string>
		<string>kTCCServiceMediaLibrary</string>
		<string>kTCCServiceMicrophone</string>
		<string>kTCCServiceReminders</string>
		<string>kTCCServicePhotos</string>
		<string>kTCCServicePhotosAdd</string>
		<string>kTCCServiceWillow</string>
	</array>
	<key>com.apple.private.tcc.allow.overridable</key>
	<array>
		<string>kTCCServiceCalendar</string>
		<string>kTCCServiceAddressBook</string>
		<string>kTCCServiceReminders</string>
	</array>
	<key>com.apple.private.tcc.manager.access.modify</key>
	<array>
		<string>kTCCServiceSiri</string>
	</array>
	<key>com.apple.private.tcc.manager.access.read</key>
	<array>
		<string>kTCCServiceAll</string>
	</array>
	<key>com.apple.private.ubiquity-additional-kvstore-identifiers</key>
	<array>
		<string>com.apple.weather</string>
	</array>
	<key>com.apple.private.usernotifications.bundle-identifiers</key>
	<array>
		<string>com.apple.siri.NotificationSource</string>
	</array>
	<key>com.apple.private.usernotifications.settings</key>
	<array>
		<string>read</string>
	</array>
	<key>com.apple.private.userprofiles.read</key>
	<true/>
	<key>com.apple.private.vfs.open-by-id</key>
	<true/>
	<key>com.apple.private.wakeboard.display.tap.access</key>
	<true/>
	<key>com.apple.private.xpc.domain-extension</key>
	<true/>
	<key>com.apple.private.xpc.domain-extension.proxy</key>
	<true/>
	<key>com.apple.private.xpc.launchd.per-user-lookup</key>
	<true/>
	<key>com.apple.proactive.ActionPrediction.predictions</key>
	<true/>
	<key>com.apple.proactive.AppPrediction.predictions</key>
	<true/>
	<key>com.apple.proactive.PersonalizationPortrait.Contact</key>
	<true/>
	<key>com.apple.proactive.PersonalizationPortrait.NamedEntity.readOnly</key>
	<true/>
	<key>com.apple.proactive.PersonalizationPortrait.Topic.readOnly</key>
	<true/>
	<key>com.apple.proactive.eventtracker</key>
	<true/>
	<key>com.apple.realitysimulation.render-on-top-spi</key>
	<true/>
	<key>com.apple.rootless.storage.coreduet_knowledge_store</key>
	<true/>
	<key>com.apple.rootless.storage.proactivepredictions</key>
	<true/>
	<key>com.apple.rootless.storage.remotemanagementd</key>
	<true/>
	<key>com.apple.rootless.storage.shortcuts</key>
	<true/>
	<key>com.apple.routined.registration</key>
	<true/>
	<key>com.apple.roya.capture</key>
	<array>
		<string>system</string>
	</array>
	<key>com.apple.runningboard.assertions.angeltarget</key>
	<true/>
	<key>com.apple.runningboard.assertions.angeltarget.campo</key>
	<true/>
	<key>com.apple.runningboard.assertions.frontboard</key>
	<true/>
	<key>com.apple.runningboard.assertions.shortcuts</key>
	<true/>
	<key>com.apple.runningboard.assertions.siri</key>
	<true/>
	<key>com.apple.runningboard.launchprocess</key>
	<true/>
	<key>com.apple.runningboard.posterkit.host</key>
	<true/>
	<key>com.apple.runningboard.process-state</key>
	<true/>
	<key>com.apple.runningboard.terminateprocess</key>
	<true/>
	<key>com.apple.screenshotservices.ssuiservice.showscreenshotui</key>
	<true/>
	<key>com.apple.searchd.appservice</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>group.com.apple.weather.internal</string>
		<string>group.tvappservices.container</string>
		<string>group.com.apple.intelligenceflow</string>
		<string>group.com.apple.Maps</string>
		<string>group.com.apple.icloud.fm</string>
		<string>group.com.apple.notes</string>
		<string>group.com.apple.sports</string>
	</array>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/Applications/</string>
		<string>/Library/WebClips/</string>
		<string>/private/var/containers/Bundle/Application/</string>
		<string>/private/var/MobileAsset/</string>
		<string>/private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles/Library/ConfigurationProfiles/MDMAppManagement.plist</string>
		<string>/private/var/db/assetsubscriptiond/</string>
		<string>/private/var/db/com.apple.countryd/</string>
		<string>/private/var/db/os_eligibility/eligibility.plist</string>
		<string>/private/var/preferences/FeatureFlags/</string>
		<string>/Library/Audio/Tunings/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/CallHistoryDB/</string>
		<string>/Library/com.apple.WatchListKit/</string>
		<string>/Library/ContactsMetadata/</string>
		<string>/Library/DuetExpertCenter/</string>
		<string>/Library/Preferences/com.apple.mobilephone.speeddial.plist</string>
		<string>/Library/SMS/</string>
		<string>/Media/PhotoData/</string>
		<string>/Library/com.apple.ManagedSettings/</string>
		<string>/Library/UserConfigurationProfiles/</string>
		<string>/Library/com.apple.PrivacyDisclosure/</string>
		<string>/Library/Caches/com.apple.countryd/</string>
		<string>/Library/Caches/com.apple.keyboards/</string>
		<string>/Library/Caches/GeoServices/</string>
		<string>/Library/WebClips/</string>
		<string>/Library/Logs/CrashReporter/Assistant/</string>
		<string>/Library/Logs/CrashReporter/VoiceTrigger/</string>
		<string>/Library/com.apple.PrivacyDisclosure/</string>
		<string>/Media/</string>
		<string>/Library/Trial/</string>
		<string>/Library/Mobile Documents/</string>
		<string>/Containers/Shared/AppGroup/</string>
		<string>/Library/MessagesMetaData/</string>
		<string>/Library/DeviceRegistry.state/ActiveDeviceMiniStore.plist</string>
		<string>/Library/Caches/com.apple.itunesstored/url-resolution.plist</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Media/PhotoData/OutgoingTemp/</string>
		<string>/Library/DeviceRegistry/</string>
		<string>/Library/Application Support/SNLUOverrides.sqlite</string>
		<string>/Library/AddressBook/</string>
		<string>/Library/Application Support/IntelligenceFlow/</string>
		<string>/Library/Application Support/CampoUIInternal/</string>
		<string>/Library/Application Support/SNLUOverrides.sqlite-shm</string>
		<string>/Library/Application Support/SNLUOverrides.sqlite-wal</string>
		<string>/Library/Application Support/SNLUOverrides.sqlite</string>
		<string>/Library/Assistant/</string>
		<string>/Library/Caches/com.apple.AgentCanvasUICore/</string>
		<string>/Library/Caches/com.apple.AppleMediaServices/</string>
		<string>/Library/Caches/com.apple.campo/</string>
		<string>/Library/Caches/com.apple.CampoUIInternal/</string>
		<string>/Library/Caches/com.apple.notes.autoincrement.lock</string>
		<string>/Library/Caches/com.apple.notes.objectcreation.lock</string>
		<string>/Library/Caches/com.apple.Pasteboard/</string>
		<string>/Library/Caches/com.apple.siri.SiriGuideUpdateCache.plist</string>
		<string>/Library/Caches/Saved Application State/com.apple.campo.savedState/</string>
		<string>/Library/Carrier Bundles/</string>
		<string>/Library/Cookies/</string>
		<string>/Library/com.apple.siri.inference/</string>
		<string>/Library/com.apple.WatchListKit/</string>
		<string>/Library/HTTPStorages/com.apple.campo/</string>
		<string>/Library/IntelligencePlatform/</string>
		<string>/Library/LanguageModeling/</string>
		<string>/Library/Logs/com.apple.FeatureStore/</string>
		<string>/Library/Logs/CrashReporter/Assistant/</string>
		<string>/Library/Logs/CrashReporter/VoiceServices/</string>
		<string>/Library/Logs/MediaServices/</string>
		<string>/Library/Metadata/CoreSpotlight/</string>
		<string>/Library/Notes/</string>
		<string>/Library/Saved Application State/com.apple.campo.savedState/</string>
		<string>/Library/Shortcuts/</string>
		<string>/Library/Spotlight/</string>
		<string>/Library/DuetExpertCenter/</string>
		<string>/Library/Weather/</string>
		<string>/Library/com.apple.AppleMediaServices/</string>
		<string>/tmp/</string>
		<string>/Library/com.apple.siri-replay/</string>
		<string>/Media/PhotoData/PhotoCloudSharingData/Caches/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.ind.xpc</string>
		<string>com.apple.assistantd.odeon-remote</string>
		<string>com.apple.companiond.xpc</string>
		<string>com.apple.quicklook.UIExtension.viewservice</string>
		<string>com.apple.private.siriappintentsd.orchestrator</string>
		<string>com.apple.generativesearch.server.search</string>
		<string>com.apple.generativeexperiences.corefollowup</string>
		<string>com.apple.generativeexperiences.ExternalProviderService</string>
		<string>com.apple.ManagedSettingsAgent</string>
		<string>com.apple.ManagedSettingsAgent.publisher</string>
		<string>com.apple.thermalMonitor.siriEnabledNote</string>
		<string>com.apple.Feedback.DraftingExtension.viewservice</string>
		<string>com.apple.iCloudQuotaUI.RemoteiCloudQuotaUI.viewservice</string>
		<string>com.apple.internal.SpotlightAutomationTester</string>
		<string>com.apple.carousel.flashlightxpcservice</string>
		<string>com.apple.realitysystemsupport.hid_server_backboard</string>
		<string>com.apple.remindd</string>
		<string>com.apple.remindd.userInteractive</string>
		<string>com.apple.surfboard.entityinteractionservice</string>
		<string>com.apple.surfboard.lockscreenservice</string>
		<string>com.apple.devicesharing.guestusermodeservice</string>
		<string>com.apple.calendar.EventKitUIRemoteUIExtension.viewservice</string>
		<string>com.apple.feedbackd.centralized-feedback</string>
		<string>com.apple.iconservices</string>
		<string>com.apple.linkd.registry</string>
		<string>com.apple.userprofiles</string>
	</array>
	<key>com.apple.security.exception.mach-register.global-name</key>
	<array>
		<string>com.apple.siri.app</string>
	</array>
	<key>com.apple.security.exception.mach-register.local-name</key>
	<array>
		<string>com.apple.iphone.axserver</string>
		<string>com.apple.assistant.contextprovider.com.apple.campo</string>
	</array>
	<key>com.apple.security.exception.process-info</key>
	<true/>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.AppSupport</string>
		<string>com.apple.cloud.quota</string>
		<string>com.apple.DocumentManager.defaults</string>
		<string>com.apple.DuetExpertCenter.AppPredictionExpert</string>
		<string>com.apple.duetexpertd</string>
		<string>com.apple.EmojiPreferences</string>
		<string>com.apple.GenerativeFunctions.GenerativeFunctionsInstrumentation</string>
		<string>com.apple.generativesearch</string>
		<string>com.apple.gms.availability</string>
		<string>com.apple.ids</string>
		<string>com.apple.imessage.bag</string>
		<string>com.apple.ImageIO</string>
		<string>com.apple.messages</string>
		<string>com.apple.messages.nicknames</string>
		<string>com.apple.mobilecal</string>
		<string>com.apple.mobilesafarishared</string>
		<string>com.apple.mobileslideshow</string>
		<string>com.apple.MobileSMS</string>
		<string>com.apple.nano</string>
		<string>com.apple.parsecd</string>
		<string>com.apple.powerlogd</string>
		<string>com.apple.preferences.sounds</string>
		<string>com.apple.purplebuddy</string>
		<string>com.apple.raisetospeak</string>
		<string>com.apple.SocialLayer</string>
		<string>com.apple.suggestions</string>
		<string>com.apple.SwiftUI</string>
		<string>com.apple.TelephonyUtilities</string>
		<string>com.apple.TTY</string>
		<string>com.apple.UIKit</string>
		<string>com.apple.UpdateCycle</string>
		<string>com.apple.weather.internal</string>
		<string>com.apple.ZoomTouch</string>
		<string>NSArgumentDomain</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.Accessibility</string>
		<string>com.apple.anvil</string>
		<string>com.apple.AppPredictionWidget.defaults</string>
		<string>com.apple.AppStoreComponents</string>
		<string>com.apple.assistant.backedup</string>
		<string>com.apple.assistant.campo</string>
		<string>com.apple.assistant.logging</string>
		<string>com.apple.assistant.public</string>
		<string>com.apple.assistant.settings</string>
		<string>com.apple.assistant.support</string>
		<string>com.apple.assistant</string>
		<string>com.apple.camera</string>
		<string>com.apple.campo</string>
		<string>com.apple.DataDeliveryServices</string>
		<string>com.apple.generativepartnerservicesettings</string>
		<string>com.apple.Gestures</string>
		<string>com.apple.intelligenceplatform</string>
		<string>com.apple.intelligenceflow</string>
		<string>com.apple.itunescloud</string>
		<string>com.apple.keyboard.preferences</string>
		<string>com.apple.keyboard</string>
		<string>com.apple.mobilemail</string>
		<string>com.apple.mobilenotes</string>
		<string>com.apple.mobileslideshow</string>
		<string>com.apple.remindd</string>
		<string>com.apple.searchd</string>
		<string>com.apple.siri.CarBluetooth</string>
		<string>com.apple.siri.generativeassistantsettings</string>
		<string>com.apple.siri.internal</string>
		<string>com.apple.siri.textinput</string>
		<string>com.apple.siri</string>
		<string>com.apple.siri.audio</string>
		<string>com.apple.Music</string>
		<string>com.apple.itunescloud.internal</string>
		<string>com.apple.SiriViewService</string>
		<string>com.apple.Spotlight</string>
		<string>com.apple.SpotlightFoundation</string>
		<string>com.apple.SpotlightResources.Defaults</string>
		<string>com.apple.spotlightui</string>
		<string>com.apple.UIKit.LTSScrolling</string>
		<string>com.apple.voiceservices</string>
		<string>com.apple.PencilKit</string>
		<string>kCFPreferencesAnyApplication</string>
	</array>
	<key>com.apple.security.hardened-process</key>
	<true/>
	<key>com.apple.security.hardened-process.checked-allocations</key>
	<true/>
	<key>com.apple.security.iokit-user-client-class</key>
	<array>
		<string>AGXCommandQueue</string>
		<string>AGXDevice</string>
		<string>AGXDeviceUserClient</string>
		<string>AGXSharedUserClient</string>
		<string>AppleJPEGDriverUserClient</string>
		<string>H11ANEInDirectPathClient</string>
		<string>AppleVirtIONeuralEngineDeviceUserClient</string>
		<string>IOAccelContext</string>
		<string>IOAccelContext2</string>
		<string>IOAccelDevice</string>
		<string>IOAccelDevice2</string>
		<string>IOAccelSharedUserClient</string>
		<string>IOAccelSharedUserClient2</string>
		<string>IOAccelSubmitter2</string>
		<string>IOGPUDeviceUserClient</string>
		<string>IOHIDEventServiceFastPathUserClient</string>
		<string>IOMobileFramebufferUserClient</string>
		<string>IOSurfaceAcceleratorClient</string>
		<string>IOSurfaceRootUserClient</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.personal-information.addressbook</key>
	<true/>
	<key>com.apple.security.personal-information.calendars</key>
	<true/>
	<key>com.apple.security.ts.geoservices</key>
	<true/>
	<key>com.apple.security.ts.ipc-posix-sem</key>
	<array>
		<string>hangtelemetryd.onceatboot</string>
	</array>
	<key>com.apple.sharesheet.allow-custom-view</key>
	<true/>
	<key>com.apple.shortcuts.background-running</key>
	<true/>
	<key>com.apple.shortcuts.stepwise-execution</key>
	<true/>
	<key>com.apple.shortcuts.variable-injection</key>
	<true/>
	<key>com.apple.siri.VoiceShortcuts.xpc</key>
	<true/>
	<key>com.apple.siri.activation.service</key>
	<true/>
	<key>com.apple.siri.analytics.assistant</key>
	<array>
		<string>stream.unifiedMessageStream.readonly</string>
	</array>
	<key>com.apple.siri.audiopowerupdate.xpc</key>
	<true/>
	<key>com.apple.siri.client_lite</key>
	<true/>
	<key>com.apple.siri.inference.EntityMatcher.admin</key>
	<true/>
	<key>com.apple.siri.location</key>
	<true/>
	<key>com.apple.siri.orchestration.prescribedaction</key>
	<true/>
	<key>com.apple.siriinferenced</key>
	<true/>
	<key>com.apple.siriknowledged</key>
	<true/>
	<key>com.apple.sirisuggestions.allow</key>
	<true/>
	<key>com.apple.sirisuggestions.application-id</key>
	<string>com.apple.siri</string>
	<key>com.apple.spotlight.entitledattributes</key>
	<true/>
	<key>com.apple.spotlight.photos.entitledattributes</key>
	<true/>
	<key>com.apple.springboard-ui.client</key>
	<true/>
	<key>com.apple.springboard.SBSRequestSpotlightActivationEntitlement</key>
	<true/>
	<key>com.apple.springboard.addApplicationIcon</key>
	<true/>
	<key>com.apple.springboard.addWidgetToTodayView</key>
	<true/>
	<key>com.apple.springboard.allowIconVisibilityChanges</key>
	<true/>
	<key>com.apple.springboard.app-drag</key>
	<true/>
	<key>com.apple.springboard.appbackgroundstyle</key>
	<true/>
	<key>com.apple.springboard.dimSumService</key>
	<true/>
	<key>com.apple.springboard.display-lookup</key>
	<true/>
	<key>com.apple.springboard.hardware-button-service.event-consumption</key>
	<true/>
	<key>com.apple.springboard.homeScreenIconStyle</key>
	<true/>
	<key>com.apple.springboard.iconTintColor</key>
	<true/>
	<key>com.apple.springboard.lookupFolderPathForIcon</key>
	<true/>
	<key>com.apple.springboard.lowDensityIconLayout</key>
	<true/>
	<key>com.apple.springboard.multitaskingshortcut.performAction</key>
	<true/>
	<key>com.apple.springboard.multiwindow.triggerShowAllWindows</key>
	<true/>
	<key>com.apple.springboard.opensensitiveurl</key>
	<true/>
	<key>com.apple.springboard.openurlinbackground</key>
	<true/>
	<key>com.apple.springboard.openurlswhenlocked</key>
	<true/>
	<key>com.apple.springboard.remote-alert</key>
	<true/>
	<key>com.apple.springboard.shortcutitems.fullaccess</key>
	<true/>
	<key>com.apple.springboard.topButtonFrames</key>
	<true/>
	<key>com.apple.surfboard-prevent-homeui-from-hiding-when-launching</key>
	<true/>
	<key>com.apple.surfboard.allow-scene-requests-while-backgrounded</key>
	<true/>
	<key>com.apple.surfboard.application-service-client</key>
	<true/>
	<key>com.apple.surfboard.chrome-customization</key>
	<true/>
	<key>com.apple.surfboard.disable-auto-show-homeui-when-closed</key>
	<true/>
	<key>com.apple.surfboard.disables-scene-snapshots</key>
	<true/>
	<key>com.apple.surfboard.entity-interaction-client</key>
	<true/>
	<key>com.apple.surfboard.entity-interaction-observer</key>
	<true/>
	<key>com.apple.surfboard.force-quit-suppression</key>
	<true/>
	<key>com.apple.surfboard.immersion-client</key>
	<true/>
	<key>com.apple.surfboard.immersive-scene-dismissal</key>
	<true/>
	<key>com.apple.surfboard.launcherservice.client</key>
	<true/>
	<key>com.apple.surfboard.lock-screen-client</key>
	<true/>
	<key>com.apple.surfboard.opts-out-of-shared-coordinate-origin</key>
	<true/>
	<key>com.apple.surfboard.placement-client</key>
	<true/>
	<key>com.apple.surfboard.please-dont-kill-me-via-cmd-q</key>
	<true/>
	<key>com.apple.surfboard.scene-rendering-not-clipped</key>
	<true/>
	<key>com.apple.surfboard.scenesession-homeui-auto-show</key>
	<true/>
	<key>com.apple.surfboard.scenesession-updates</key>
	<true/>
	<key>com.apple.surfboard.sharing-mode-launch-allowed</key>
	<true/>
	<key>com.apple.surfboard.should-ignore-if-last-scene-for-auto-show-homeui</key>
	<true/>
	<key>com.apple.surfboard.system-elements-assertion-immersive-visible</key>
	<true/>
	<key>com.apple.symptom_analytics.query</key>
	<true/>
	<key>com.apple.symptoms.NetworkOfInterest</key>
	<true/>
	<key>com.apple.telephonyutilities.callservicesd</key>
	<array>
		<string>access-call-providers</string>
	</array>
	<key>com.apple.telephonyutilities.callservicesdaemon.callprovidermanager</key>
	<true/>
	<key>com.apple.trial.client</key>
	<array>
		<string>332</string>
		<string>333</string>
		<string>334</string>
		<string>335</string>
		<string>336</string>
		<string>337</string>
		<string>409</string>
		<string>753</string>
		<string>755</string>
		<string>321</string>
		<string>322</string>
		<string>371</string>
		<string>372</string>
		<string>401</string>
		<string>405</string>
		<string>406</string>
		<string>407</string>
		<string>408</string>
		<string>425</string>
		<string>750</string>
		<string>751</string>
		<string>752</string>
		<string>754</string>
		<string>757</string>
		<string>910</string>
		<string>961</string>
		<string>1000</string>
		<string>1350</string>
		<string>1460</string>
	</array>
	<key>com.apple.trial.status</key>
	<true/>
	<key>com.apple.trial.status.deployment-environment.allow</key>
	<array>
		<integer>0</integer>
	</array>
	<key>com.apple.trial.status.namespace-name.allow</key>
	<array>
		<string>SIRI_AUDIO_LAPSED_MUSIC_USER</string>
	</array>
	<key>com.apple.usermanagerd.persona.fetch</key>
	<true/>
	<key>com.apple.usermanagerd.persona.observer</key>
	<true/>
	<key>com.apple.vfx-provider</key>
	<true/>
	<key>com.apple.visualvoicemail.client</key>
	<true/>
	<key>com.apple.voiceservices.tts.customvoice</key>
	<true/>
	<key>com.apple.voicetrigger.voicetriggerservice</key>
	<true/>
	<key>com.apple.watchlist.private</key>
	<true/>
	<key>com.apple.wifi.manager-access</key>
	<true/>
	<key>fairplay-client</key>
	<string>511712240</string>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.Spotlight</string>
		<string>apple</string>
		<string>com.apple.openai</string>
		<string>appleaccount</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### SleepWidgetExtension

> `/Applications/SleepWidgetContainer.app/PlugIns/SleepWidgetExtension.appex/SleepWidgetExtension`

```diff

+		<string>/private/var/db/com.apple.countryd/</string>

```
### StoreDemoViewService

> `/Applications/StoreDemoViewService.app/StoreDemoViewService`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.MobileStoreDemo.test</string>
+	</array>

```
### WorkoutRemoteViewService

> `/Applications/WorkoutRemoteViewService.app/WorkoutRemoteViewService`

```diff

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>
+	<key>com.apple.springboard.openurlinbackground</key>
+	<true/>

```
### usbaudiod

> `/System/Library/Audio/Plug-Ins/usbaudio.bundle/usbaudiod`

```diff

+	<key>com.apple.private.audio.driver.extrinsic.registration</key>
+	<true/>

```
### AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

```diff

+	<key>com.apple.private.device-configuration.provider.allowed-provider-ids</key>
+	<array>
+		<string>com.apple.accessibility.GuidedAccess</string>
+	</array>

+	<key>com.apple.runningboard.process-state</key>
+	<true/>

+	<key>com.apple.springboard.system-component-restriction</key>
+	<true/>

```
### assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

```diff

+		<string>com.apple.Accessibility</string>

```
### CarPlay

> `/System/Library/CoreServices/CarPlay.app/CarPlay`

```diff

+	<key>com.apple.private.InstallCoordination.GetAppReplacementSource</key>
+	<true/>

+		<string>com.apple.installcoordinationd</string>

```
### ClarityBoard

> `/System/Library/CoreServices/ClarityBoard.app/ClarityBoard`

```diff

+	<key>com.apple.private.InstallCoordination.GetAppReplacementSource</key>
+	<true/>

```
### CoreServicesUIAgent

> `/System/Library/CoreServices/CoreServicesUIAgent.app/CoreServicesUIAgent`

```diff

+	<key>com.apple.appprotectiond.guard.access</key>
+	<true/>
+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>
+	<key>com.apple.private.InstallCoordination.AppReplacementRefused</key>
+	<true/>
+	<key>com.apple.private.InstallCoordination.GetAppReplacementSource</key>
+	<true/>
+	<key>com.apple.private.InstallCoordination.ReplaceApp</key>
+	<true/>
+	<key>com.apple.private.InstallCoordination.allowed</key>
+	<true/>

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.appprotectiond.read</string>
+		<string>com.apple.appprotectiond.guard</string>
+	</array>

+	<key>com.apple.usermanagerd.persona.fetch</key>
+	<true/>

```
### GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

```diff

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### SpringBoard

> `/System/Library/CoreServices/SpringBoard.app/SpringBoard`

```diff

+	<key>com.apple.private.InstallCoordination.GetAppReplacementSource</key>
+	<true/>
+	<key>com.apple.private.InstallCoordination.ReplaceApp</key>
+	<true/>

+		<string>kTCCServiceSiriAccess</string>

```
### SystemIntents

> `/System/Library/CoreServices/SystemIntents.app/SystemIntents`

```diff

+	<key>com.apple.private.multiuserservices.session-claim.implicit-redemption</key>
+	<true/>

```
### scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

```diff

+	<key>com.apple.keyboardservices.textreplacement.allow</key>
+	<true/>

+		<string>com.apple.TextInput.shortcuts</string>

```
### ADAskForExceptionExtension

> `/System/Library/ExtensionKit/Extensions/ADAskForExceptionExtension.appex/ADAskForExceptionExtension`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### ADFollowUpExtension

> `/System/Library/ExtensionKit/Extensions/ADFollowUpExtension.appex/ADFollowUpExtension`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### ASDAgeAssuranceExtension

> `/System/Library/ExtensionKit/Extensions/ASDAgeAssuranceExtension.appex/ASDAgeAssuranceExtension`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```

### 🆕 AccessoryAppMigration

> `/System/Library/ExtensionKit/Extensions/AccessoryAppMigration.appex/AccessoryAppMigration`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.AccessoryAppMigration</string>
	<key>com.apple.DeviceAccess.private</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.DeviceAccess.xpc</string>
	</array>
</dict>
</plist>

```
### AgeVerificationExtension

> `/System/Library/ExtensionKit/Extensions/AgeVerificationExtension.appex/AgeVerificationExtension`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.Vision.AgeEstimation</string>
+		<string>com.apple.MobileAsset.Vision.FaceLiveliness</string>
+	</array>

+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_Vision_AgeEstimation/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_Vision_AgeEstimation/</string>
+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_Vision_FaceLiveliness/</string>
+		<string>/private/var/MobileAsset/PreinstalledAssetsV2/InstallWithOs/com_apple_MobileAsset_Vision_FaceLiveliness/</string>
+	</array>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>
+		<string>com.apple.modelcatalog.catalog</string>

```

### 🆕 AppDataMigrationExtension

> `/System/Library/ExtensionKit/Extensions/AppDataMigrationExtension.appex/AppDataMigrationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.CommCenter.fine-grained</key>
	<array>
		<string>spi</string>
	</array>
</dict>
</plist>

```

### 🆕 AppProtectionAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/AppProtectionAppReplacementExtension.appex/AppProtectionAppReplacementExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.appprotectiond.read.access</key>
	<true/>
	<key>com.apple.appprotectiond.write.access</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.appprotectiond.read</string>
		<string>com.apple.appprotectiond.write</string>
		<string>com.apple.appprotectiond.guard</string>
	</array>
</dict>
</plist>

```

### 🆕 AppReplacement

> `/System/Library/ExtensionKit/Extensions/AppReplacement.appex/AppReplacement`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.tcc.AppReplacement</string>
	<key>com.apple.private.tcc.internal.transfer-authorizations</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.tccd</string>
	</array>
</dict>
</plist>

```
### AppStoreSettingsAppIntents

> `/System/Library/ExtensionKit/Extensions/AppStoreSettingsAppIntents.appex/AppStoreSettingsAppIntents`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### AppleIntelligenceReportingSELFIngestor

> `/System/Library/ExtensionKit/Extensions/AppleIntelligenceReportingSELFIngestor.appex/AppleIntelligenceReportingSELFIngestor`

```diff

-	<key>com.apple.private.biome.read-write</key>
+	<key>com.apple.private.biome.read-only</key>

+		<string>AssetDelivery.UAF.AssetSetAlterActivity</string>
+		<string>AssetDelivery.UAF.AssetSetStatus</string>

+				<key>AssetDelivery.UAF.AssetSetAlterActivity</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+				<key>AssetDelivery.UAF.AssetSetStatus</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

-					<string>read-write</string>
+					<string>read-only</string>

```
### AssetMetrics

> `/System/Library/ExtensionKit/Extensions/AssetMetrics.appex/AssetMetrics`

```diff

+		<string>AppleIntelligence.Reporting.AssetDeliveryLog.Availability</string>

+				<string>AppleIntelligence.Reporting.AssetDeliveryLog.Availability</string>

+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.assistant.shared</string>
+	</array>

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.assistant.shared</string>
+	</array>
+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/Application Support/com.apple.appleintelligencereporting.processing/</string>
+	</array>

```

### 🆕 CGIExtension

> `/System/Library/ExtensionKit/Extensions/CGIExtension.appex/CGIExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.CGIExtension</string>
	<key>com.apple.icloudsubscriptionoptimizerd.xpc.client.entitlement.full-access</key>
	<true/>
	<key>com.apple.private.applemediaservices</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.icloudsubscriptionoptimizerd.xpc.client</string>
	</array>
</dict>
</plist>

```

### 🆕 CLAppMigrationExtension

> `/System/Library/ExtensionKit/Extensions/CLAppMigrationExtension.appex/CLAppMigrationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.locationd.migrateauthorization</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.locationd.synchronous</string>
	</array>
</dict>
</plist>

```

### 🆕 CarPlayAppDataMigration

> `/System/Library/ExtensionKit/Extensions/CarPlayAppDataMigration.appex/CarPlayAppDataMigration`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.chronoservices</key>
	<true/>
	<key>com.apple.private.CarPlayServices.icon-layout</key>
	<true/>
	<key>com.apple.private.carkit</key>
	<true/>
	<key>com.apple.private.installcoordination.app-data-migration.host</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.CarPlayApp.service</string>
		<string>com.apple.carkit.service</string>
		<string>com.apple.chronoservices</string>
	</array>
</dict>
</plist>

```

### 🆕 CoreServicesAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/CoreServicesAppReplacementExtension.appex/CoreServicesAppReplacementExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.coreservices.appmigration.write</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
</dict>
</plist>

```

### 🆕 DoNotDisturbAppReplacement

> `/System/Library/ExtensionKit/Extensions/DoNotDisturbAppReplacement.appex/DoNotDisturbAppReplacement`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.donotdisturb.modeconfiguration.modify.client-identifiers</key>
	<array>
		<string>com.apple.donotdisturb.DoNotDisturbAppReplacement</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.donotdisturb.service</string>
	</array>
</dict>
</plist>

```
### ExclavesInferenceProvider

> `/System/Library/ExtensionKit/Extensions/ExclavesInferenceProvider.appex/ExclavesInferenceProvider`

```diff

+		<string>com.apple.modelmanager.exclaves.test.internal</string>

```
### FamilyOutOfProcessUIExtension

> `/System/Library/ExtensionKit/Extensions/FamilyOutOfProcessUIExtension.appex/FamilyOutOfProcessUIExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### FedStatsMLHostPlugin

> `/System/Library/ExtensionKit/Extensions/FedStatsMLHostPlugin.appex/FedStatsMLHostPlugin`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.LinguisticData</string>
+		<string>com.apple.MobileAsset.UAF.LinguisticData</string>
+	</array>

+		<string>/private/var/MobileAsset/AssetsV2/</string>

+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>

```
### FedStatsMLHostPluginClassA

> `/System/Library/ExtensionKit/Extensions/FedStatsMLHostPluginClassA.appex/FedStatsMLHostPluginClassA`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.LinguisticData</string>
+		<string>com.apple.MobileAsset.UAF.LinguisticData</string>
+	</array>

+		<string>/private/var/MobileAsset/AssetsV2/</string>

+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>

```
### FedStatsMLHostPluginClassB

> `/System/Library/ExtensionKit/Extensions/FedStatsMLHostPluginClassB.appex/FedStatsMLHostPluginClassB`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.LinguisticData</string>
+		<string>com.apple.MobileAsset.UAF.LinguisticData</string>
+	</array>

+		<string>/private/var/MobileAsset/AssetsV2/</string>

+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>

```
### FedStatsPluginDynamic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginDynamic.appex/FedStatsPluginDynamic`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.LinguisticData</string>
+		<string>com.apple.MobileAsset.UAF.LinguisticData</string>
+	</array>

+		<string>/private/var/MobileAsset/AssetsV2/</string>

+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>

```
### FedStatsPluginStatic

> `/System/Library/ExtensionKit/Extensions/FedStatsPluginStatic.appex/FedStatsPluginStatic`

```diff

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.LinguisticData</string>
+		<string>com.apple.MobileAsset.UAF.LinguisticData</string>
+	</array>

+		<string>/private/var/MobileAsset/AssetsV2/</string>

+		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.mobileassetd.v2</string>

```
### FindMyIntentsExtension

> `/System/Library/ExtensionKit/Extensions/FindMyIntentsExtension.appex/FindMyIntentsExtension`

```diff

+	<key>com.apple.locationd.effective_bundle</key>
+	<true/>
+	<key>com.apple.locationd.usage_oracle</key>
+	<true/>

+	<key>com.apple.private.application-service-browse</key>
+	<true/>

+	<key>com.apple.private.userprofiles.read</key>
+	<true/>

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.icloud.fm</string>
+	</array>

+		<string>com.apple.userprofiles</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.findmy</string>

+		<string>com.apple.userprofiles</string>
+		<string>com.apple.locationd.desktop.synchronous</string>
+		<string>com.apple.locationd.desktop.registration</string>
+		<string>com.apple.CoreLocation.agent</string>

```

### 🆕 FontServicesAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/FontServicesAppReplacementExtension.appex/FontServicesAppReplacementExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.FontServices.UserFontManager</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### GenerativeExperiencesSafetyInferenceProvider

> `/System/Library/ExtensionKit/Extensions/GenerativeExperiencesSafetyInferenceProvider.appex/GenerativeExperiencesSafetyInferenceProvider`

```diff

+		<string>/private/var/db/assetsubscriptiond/</string>

```
### PhotosMessagesApp

> `/System/Library/ExtensionKit/Extensions/PhotosMessagesApp.appex/PhotosMessagesApp`

```diff

-	<key>com.apple.developer.hardened-process</key>
-	<true/>

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations</key>
+	<true/>

```
### PhotosPicker

> `/System/Library/ExtensionKit/Extensions/PhotosPicker.appex/PhotosPicker`

```diff

+		<string>group.com.apple.mobileslideshow.SharedAlbums</string>

```
### ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>

```

### 🆕 ProprietaryDefaultsAppDataMigration

> `/System/Library/ExtensionKit/Extensions/ProprietaryDefaultsAppDataMigration.appex/ProprietaryDefaultsAppDataMigration`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.avfoundation.capture.proprietary-defaults-migration</key>
	<true/>
</dict>
</plist>

```

### 🆕 SESAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/SESAppReplacementExtension.appex/SESAppReplacementExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.seserviced.appmigration</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.seserviced.private.appmigration</string>
	</array>
</dict>
</plist>

```

### 🆕 SNCFeaturesPlugin

> `/System/Library/ExtensionKit/Extensions/SNCFeaturesPlugin.appex/SNCFeaturesPlugin`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.priml.pfl.SNCFeaturesPlugin</string>
	<key>com.apple.developer.icloud-container-environment</key>
	<string>production</string>
	<key>com.apple.developer.icloud-container-identifiers</key>
	<array>
		<string>com.apple.priml.dev.container</string>
		<string>com.apple.priml.preprod.container</string>
		<string>com.apple.priml.prod.container</string>
	</array>
	<key>com.apple.developer.icloud-services</key>
	<array>
		<string>CloudKit</string>
	</array>
	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
	<string>com.apple.priml.pfl.plugins</string>
	<key>com.apple.priml.pfl.Morpheus.allowed</key>
	<true/>
	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
	<true/>
	<key>com.apple.private.biome.writer</key>
	<array>
		<string>Lighthouse.Ledger.TaskCustomEvent</string>
	</array>
	<key>com.apple.private.cloudkit.masquerade</key>
	<true/>
	<key>com.apple.private.cloudkit.setEnvironment</key>
	<true/>
	<key>com.apple.private.cloudkit.spi</key>
	<true/>
	<key>com.apple.private.cloudkit.systemService</key>
	<true/>
	<key>com.apple.private.dprivacyd.allow</key>
	<true/>
	<key>com.apple.private.dprivacyd.metadata.allow</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>MLHostTelemetry</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>Lighthouse.Ledger.TaskCustomEvent</string>
			</array>
		</dict>
	</dict>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceLiverpool</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.mlhostd.xpc</string>
		<string>com.apple.cloudd</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.priml.crashrecords</string>
		<string>com.apple.priml.participations</string>
		<string>com.apple.priml.submissioncooldown</string>
	</array>
</dict>
</plist>

```
### ScreenTimeAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeAppIntentsExtension.appex/ScreenTimeAppIntentsExtension`

```diff

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

```

### 🆕 SiriExtensionsDigestExtension

> `/System/Library/ExtensionKit/Extensions/SiriExtensionsDigestExtension.appex/SiriExtensionsDigestExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.siri.SiriExtensionsDigestExtension</string>
	<key>com.apple.assistant.settings</key>
	<true/>
	<key>com.apple.private.assistant.settings</key>
	<true/>
	<key>com.apple.private.biome.client-identifier</key>
	<string>com.apple.siri.SiriExtensionsDigestExtension</string>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>Siri.SELFProcessedEvent</string>
	</array>
	<key>com.apple.private.biome.read-write</key>
	<array>
		<string>Lighthouse.Ledger.LighthousePluginEvent</string>
	</array>
	<key>com.apple.private.biome.writer</key>
	<array>
		<string>Lighthouse.Ledger.TaskCustomEvent</string>
	</array>
	<key>com.apple.private.feedbacklogger</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>MLHostTelemetry</key>
		<dict>
			<key>Streams</key>
			<string>Lighthouse.Ledger.TaskCustomEvent</string>
		</dict>
	</dict>
	<key>com.apple.private.logging.diagnostic</key>
	<true/>
	<key>com.apple.private.logging.stream</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>com.apple.siri.SiriExtensionsDigestExtension</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Caches/com.apple.feedbacklogger/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.siri.analytics.assistant</string>
		<string>com.apple.feedbacklogger</string>
		<string>com.apple.biome.access.user</string>
		<string>com.apple.symptom_diagnostics</string>
		<string>com.apple.assistant.settings</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.assistant</string>
		<string>com.apple.assistant.support</string>
		<string>com.apple.assistant.backedup</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.siri.SiriExtensionsDigest.worker</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.siri.analytics.assistant</string>
		<string>com.apple.feedbacklogger</string>
		<string>com.apple.assistant.settings</string>
		<string>com.apple.biome.access.user</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.assistant</string>
		<string>com.apple.assistant.support</string>
		<string>com.apple.assistant.backedup</string>
	</array>
	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.siri.SiriExtensionsDigest.worker</string>
	</array>
</dict>
</plist>

```

### 🆕 SiriLogProcessor

> `/System/Library/ExtensionKit/Extensions/SiriLogProcessor.appex/SiriLogProcessor`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.aiml.siri.SiriLogProcessor</string>
	<key>com.apple.application-identifier</key>
	<string>com.apple.aiml.siri.SiriLogProcessor</string>
	<key>com.apple.private.feedbacklogger</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.client-identifier</key>
	<string>com.apple.aiml.siri.SiriLogProcessor</string>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>SiriLogProcessor</key>
		<dict>
			<key>Streams</key>
			<dict>
				<key>Siri.PrivateLearning.SELFEvent</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
				<key>Siri.SELFProcessedEvent</key>
				<dict>
					<key>mode</key>
					<string>read-write</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Caches/com.apple.feedbacklogger/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.siri.analytics.assistant</string>
		<string>com.apple.feedbacklogger</string>
		<string>com.apple.aiml.siri.OLEOrchestrator</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.siri.analytics.assistant</string>
		<string>com.apple.feedbacklogger</string>
		<string>com.apple.aiml.siri.OLEOrchestrator</string>
	</array>
	<key>com.apple.siri.analytics.assistant</key>
	<array>
		<string>runtime.host</string>
	</array>
</dict>
</plist>

```
### SiriSuggestionsLightHousePlugin

> `/System/Library/ExtensionKit/Extensions/SiriSuggestionsLightHousePlugin.appex/SiriSuggestionsLightHousePlugin`

```diff

+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

+	<key>com.apple.private.tcc.allow</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

+		<string>com.apple.tccd</string>
+		<string>com.apple.appprotectiond.read</string>

+		<string>com.apple.tccd</string>
+		<string>com.apple.appprotectiond.read</string>

```
### StorageSettingsIntentsExtension

> `/System/Library/ExtensionKit/Extensions/StorageSettingsIntentsExtension.appex/StorageSettingsIntentsExtension`

```diff

-	<string>com.apple.Settings</string>
+	<string>com.apple.Preferences</string>

```
### SubscribePageExtension

> `/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>

```

### 🆕 UserNotificationsAppReplacement

> `/System/Library/ExtensionKit/Extensions/UserNotificationsAppReplacement.appex/UserNotificationsAppReplacement`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.usernotifications.accessorynotifications.settings</key>
	<array>
		<string>com.apple.usernotifications.UserNotificationsAppReplacement</string>
	</array>
	<key>com.apple.private.usernotifications.settings</key>
	<array>
		<string>write</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.usernotifications.usernotificationsettingsservice</string>
		<string>com.apple.usernotifications.accessorynotifications</string>
	</array>
</dict>
</plist>

```

### 🆕 WidgetKitAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/WidgetKitAppReplacementExtension.appex/WidgetKitAppReplacementExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.chrono.accessoryLiveActivities.app.migration</key>
	<true/>
	<key>com.apple.private.activitykit.bundleIDReplacer</key>
	<true/>
</dict>
</plist>

```

### 🆕 com.apple.HealthKit.HealthKitAppReplacementExtension

> `/System/Library/ExtensionKit/Extensions/com.apple.HealthKit.HealthKitAppReplacementExtension.appex/com.apple.HealthKit.HealthKitAppReplacementExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.developer.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit.app_replacement</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_manager</key>
	<array>
		<string>read</string>
		<string>write</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.healthd.server</string>
	</array>
</dict>
</plist>

```

### 🆕 frauddefensepfl

> `/System/Library/ExtensionKit/Extensions/frauddefensepfl.appex/frauddefensepfl`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.priml.pfl.frauddefensepfl</string>
	<key>com.apple.developer.icloud-container-environment</key>
	<string>production</string>
	<key>com.apple.developer.icloud-container-identifiers</key>
	<array>
		<string>com.apple.priml.dev.container</string>
		<string>com.apple.priml.preprod.container</string>
		<string>com.apple.priml.prod.container</string>
	</array>
	<key>com.apple.developer.icloud-services</key>
	<array>
		<string>CloudKit</string>
	</array>
	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
	<string>com.apple.priml.pfl.plugins</string>
	<key>com.apple.priml.pfl.Morpheus.allowed</key>
	<true/>
	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
	<true/>
	<key>com.apple.private.biome.writer</key>
	<array>
		<string>Lighthouse.Ledger.TaskCustomEvent</string>
	</array>
	<key>com.apple.private.cloudkit.masquerade</key>
	<true/>
	<key>com.apple.private.cloudkit.setEnvironment</key>
	<true/>
	<key>com.apple.private.cloudkit.spi</key>
	<true/>
	<key>com.apple.private.cloudkit.systemService</key>
	<true/>
	<key>com.apple.private.dprivacyd.allow</key>
	<true/>
	<key>com.apple.private.dprivacyd.metadata.allow</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>MLHostTelemetry</key>
		<dict>
			<key>Streams</key>
			<array>
				<string>Lighthouse.Ledger.TaskCustomEvent</string>
			</array>
		</dict>
	</dict>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceLiverpool</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.mlhostd.xpc</string>
		<string>com.apple.cloudd</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.priml.crashrecords</string>
		<string>com.apple.priml.participations</string>
		<string>com.apple.priml.submissioncooldown</string>
	</array>
</dict>
</plist>

```
### apfs_checkdigest

> `/System/Library/Filesystems/apfs.fs/apfs_checkdigest`

```diff

-	<key>com.apple.private.apfs.lock-container-load</key>
-	<true/>

```
### apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

```diff

-	<key>com.apple.private.apfs.lock-container-load</key>
-	<true/>

```
### apfs_computedigest

> `/System/Library/Filesystems/apfs.fs/apfs_computedigest`

```diff

-	<key>com.apple.private.apfs.lock-container-load</key>
-	<true/>

```
### apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

```diff

-	<key>com.apple.private.apfs.lock-container-load</key>
-	<true/>

```
### fsck_apfs

> `/System/Library/Filesystems/apfs.fs/fsck_apfs`

```diff

-	<key>com.apple.private.apfs.lock-container-load</key>
-	<true/>

```
### sm_stats

> `/System/Library/Filesystems/apfs.fs/sm_stats`

```diff

-	<key>com.apple.private.apfs.lock-container-load</key>
-	<true/>

```

### 🆕 CrisisResourceResponsePlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/CrisisResourceResponsePlugin.bundle/CrisisResourceResponsePlugin`

- No entitlements *(yet)*

### 🆕 SiriFindMySnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriFindMySnippetProviderPlugin.bundle/SiriFindMySnippetProviderPlugin`

- No entitlements *(yet)*

### 🆕 SiriFindMyFlowTools

> `/System/Library/FlowTools/Tools/SiriFindMyFlowTools.flowtool/SiriFindMyFlowTools`

- No entitlements *(yet)*
### accountsd

> `/System/Library/Frameworks/Accounts.framework/accountsd`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

```
### appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

```diff

+		<string>UniqueDeviceID</string>

```
### assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

```diff

-	<key>com.apple.developer.hardened-process</key>
-	<true/>

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations</key>
+	<true/>

```
### ContactViewViewService

> `/System/Library/Frameworks/ContactsUI.framework/PlugIns/ContactViewViewService.appex/ContactViewViewService`

```diff

+		<string>com.apple.familycircle.agent</string>

```
### ContactsViewService

> `/System/Library/Frameworks/ContactsUI.framework/PlugIns/ContactsViewService.appex/ContactsViewService`

```diff

+		<string>com.apple.familycircle.agent</string>

```
### spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

```diff

+				<key>AmbientSensing.Activity</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<key>GenerativeLearningPlatform.Insight</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<key>Health.Measurement</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

```
### FinanceImageProcessingService

> `/System/Library/Frameworks/FinanceKit.framework/XPCServices/FinanceImageProcessingService.xpc/FinanceImageProcessingService`

```diff

+	<key>com.apple.developer.usersafety.client</key>
+	<string>analysis</string>

+	<key>com.apple.private.biome.read-write</key>
+	<array>
+		<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>
+	</array>

```
### financed

> `/System/Library/Frameworks/FinanceKit.framework/financed`

```diff

-	<key>com.apple.private.corespotlight.bundleid</key>
-	<string>com.apple.Passbook</string>

```
### com.apple.HealthKit.HealthDiagnosticExtension

> `/System/Library/Frameworks/HealthKit.framework/PlugIns/com.apple.HealthKit.HealthDiagnosticExtension.appex/com.apple.HealthKit.HealthDiagnosticExtension`

```diff

+		<string>com.apple.healthcontentd</string>

```
### healthd

> `/System/Library/Frameworks/HealthKit.framework/healthd`

```diff

+	<key>com.apple.private.memorystatus</key>
+	<true/>

+		<string>com.apple.healthcontentd</string>

```
### applicensedeliveryd

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/applicensedeliveryd`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### CircleJoinRequested

> `/System/Library/Frameworks/Security.framework/CircleJoinRequested/CircleJoinRequested`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

```diff

+	<key>com.apple.maps.suggestions.sources</key>
+	<true/>

```
### DeviceActivityReportService

> `/System/Library/Frameworks/_DeviceActivity_SwiftUI.framework/PlugIns/DeviceActivityReportService.appex/DeviceActivityReportService`

```diff

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

```

### 🆕 HIDSecureInputSessionFilter

> `/System/Library/HIDPlugins/SessionFilters/HIDSecureInputSessionFilter.plugin/HIDSecureInputSessionFilter`

- No entitlements *(yet)*

### 🆕 HealthClinicalPrioritizationDiagnosticExtensionPlugin

> `/System/Library/Health/DiagnosticExtensionPlugins/HealthClinicalPrioritizationDiagnosticExtensionPlugin.bundle/HealthClinicalPrioritizationDiagnosticExtensionPlugin`

- No entitlements *(yet)*

### 🆕 EvaluationsHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/EvaluationsHealthAppPlugin.healthplugin/EvaluationsHealthAppPlugin`

- No entitlements *(yet)*

### 🆕 HealthContentAppPluginBundle

> `/System/Library/Health/FeedItemPlugins/HealthContentAppPluginBundle.healthplugin/HealthContentAppPluginBundle`

- No entitlements *(yet)*

### 🆕 HealthIntelligenceAppPlugin

> `/System/Library/Health/FeedItemPlugins/HealthIntelligenceAppPlugin.healthplugin/HealthIntelligenceAppPlugin`

- No entitlements *(yet)*

### 🆕 HealthPlansAppPluginBundle

> `/System/Library/Health/FeedItemPlugins/HealthPlansAppPluginBundle.healthplugin/HealthPlansAppPluginBundle`

- No entitlements *(yet)*

### 🆕 HealthReportAppDaemonPlugin

> `/System/Library/Health/FeedItemPlugins/HealthReportAppDaemonPlugin.healthplugin/HealthReportAppDaemonPlugin`

- No entitlements *(yet)*

### 🆕 MulberryHealthAppPluginBundle

> `/System/Library/Health/FeedItemPlugins/MulberryHealthAppPluginBundle.healthplugin/MulberryHealthAppPluginBundle`

- No entitlements *(yet)*

### 🆕 HealthEvaluationsHealthDaemonPlugin

> `/System/Library/Health/Plugins/HealthEvaluationsHealthDaemonPlugin.bundle/HealthEvaluationsHealthDaemonPlugin`

- No entitlements *(yet)*

### 🆕 HealthFactsDaemonPlugin

> `/System/Library/Health/Plugins/HealthFactsDaemonPlugin.bundle/HealthFactsDaemonPlugin`

- No entitlements *(yet)*

### 🆕 HealthHistoryDaemonPlugin

> `/System/Library/Health/Plugins/HealthHistoryDaemonPlugin.bundle/HealthHistoryDaemonPlugin`

- No entitlements *(yet)*

### 🆕 HealthReportHealthDaemonPlugin

> `/System/Library/Health/Plugins/HealthReportHealthDaemonPlugin.bundle/HealthReportHealthDaemonPlugin`

- No entitlements *(yet)*

### 🆕 LabKitDaemonPlugin

> `/System/Library/Health/Plugins/LabKitDaemonPlugin.bundle/LabKitDaemonPlugin`

- No entitlements *(yet)*

### 🆕 SurveyKitDaemonPlugin

> `/System/Library/Health/Plugins/SurveyKitDaemonPlugin.bundle/SurveyKitDaemonPlugin`

- No entitlements *(yet)*
### agentstored

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/agentstored`

```diff

+		<string>com.apple.linkd.application-service</string>

```
### AirPlaySenderService

> `/System/Library/PrivateFrameworks/AirPlaySenderKit.framework/XPCServices/AirPlaySenderService.xpc/AirPlaySenderService`

```diff

+	<key>com.apple.private.darwin-notification.restrict-post.AirPlay.DACP.mutetoggle</key>
+	<true/>
+	<key>com.apple.private.darwin-notification.restrict-post.AirPlay.DACP.volumedown</key>
+	<true/>
+	<key>com.apple.private.darwin-notification.restrict-post.AirPlay.DACP.volumeup</key>
+	<true/>

```
### AppIntentsRunnerXPCService

> `/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService`

```diff

+	<key>com.apple.private.dmd.policy</key>
+	<true/>

```
### ASDFollowUpExtension

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/PlugIns/ASDFollowUpExtension.appex/ASDFollowUpExtension`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### ASDUserNotificationExtension

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/PlugIns/ASDUserNotificationExtension.appex/ASDUserNotificationExtension`

```diff

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### appstored

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstored`

```diff

+	<key>com.apple.private.appmanagedfeatures.configuration</key>
+	<true/>

+		<string>App.ExtensionUsage</string>

+		<string>com.apple.appmanagedfeatures.configuration</string>

+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>
+	<true/>

-	<key>com.apple.security.hardened-process.enhanced-security-version</key>
-	<integer>1</integer>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>

```
### appleaccounttransparencyd

> `/System/Library/PrivateFrameworks/AppleAccountTransparency.framework/appleaccounttransparencyd`

```diff

+	<key>aps-connection-initiate</key>
+	<true/>

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.apsd</string>
+	</array>

```
### AAUIFollowUpExtension

> `/System/Library/PrivateFrameworks/AppleAccountUI.framework/PlugIns/AAUIFollowUpExtension.appex/AAUIFollowUpExtension`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>
+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### AppleIntelligenceReportingProcessingService

> `/System/Library/PrivateFrameworks/AppleIntelligenceReportingProcessing.framework/XPCServices/AppleIntelligenceReportingProcessingService.xpc/AppleIntelligenceReportingProcessingService`

```diff

-	<key>com.apple.private.biome.read-write</key>
+	<key>com.apple.private.biome.read-only</key>

+		<string>AssetDelivery.UAF.AssetSetAlterActivity</string>
+		<string>AssetDelivery.UAF.AssetSetStatus</string>

+				<key>AssetDelivery.UAF.AssetSetAlterActivity</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+				<key>AssetDelivery.UAF.AssetSetStatus</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

-					<string>read-write</string>
+					<string>read-only</string>

```
### amsengagementd

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/amsengagementd`

```diff

-	<key>com.apple.security.hardened-process.dyld-ro</key>
+	<key>com.apple.security.hardened-process.checked-allocations</key>

-	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
-	<string>2</string>
-	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<key>com.apple.security.hardened-process.checked-allocations.enforce-checked-pointer-arithmetic-overflow</key>

-	<key>com.apple.security.hardened-process.platform-restrictions-string</key>
+	<key>com.apple.security.hardened-process.checked-allocations.soft-mode</key>
+	<true/>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>

```
### apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

```diff

+	<key>com.apple.private.ids.region-store</key>
+	<true/>

```
### assistant_service

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistant_service`

```diff

+		<string>kTCCServiceSiriAccess</string>

+		<string>kTCCServiceSiriAccess</string>

```
### assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

```diff

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.modelcatalog</string>
+	</array>

+	<key>com.apple.private.security.storage.PhotosLibraries</key>
+	<true/>

+		<string>com.apple.DeviceConfigurationAgent.consumer</string>
+		<string>com.apple.DeviceConfigurationAgent.consumer.async</string>
+		<string>com.apple.DeviceConfigurationAgent.publisher</string>

-		<string>com.apple.gms.availability</string>

+		<string>com.apple.morphology</string>
+		<string>com.apple.morphology.internal</string>

+		<string>com.apple.gms.availability</string>

+		<string>com.apple.gms.availability</string>

+	<key>com.apple.siri.shared_flow_plugin_service</key>
+	<true/>

```
### akd

> `/System/Library/PrivateFrameworks/AuthKit.framework/akd`

```diff

+	<key>com.apple.appleaccount.transparency.metadata</key>
+	<true/>

+	<key>com.apple.cdp.utility</key>
+	<true/>

+		<string>com.apple.appleaccount.transparency</string>

```
### AKFollowUpExtension

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/PlugIns/AKFollowUpExtension.appex/AKFollowUpExtension`

```diff

+	<key>com.apple.cdp.statemachine</key>
+	<true/>
+	<key>com.apple.cdp.utility</key>
+	<true/>
+	<key>com.apple.cdp.walrus</key>
+	<true/>

```
### biomed

> `/System/Library/PrivateFrameworks/BiomeStreams.framework/Support/biomed`

```diff

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### calaccessd

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/Support/calaccessd`

```diff

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.containment.ipc</key>
+	<true/>
+	<key>com.apple.security.hardened-process.dyld-ro</key>
+	<true/>
+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

```
### com.apple.CloudDocs.iCloudDriveFileProviderManaged

> `/System/Library/PrivateFrameworks/CloudDocs.framework/PlugIns/com.apple.CloudDocs.iCloudDriveFileProviderManaged.appex/com.apple.CloudDocs.iCloudDriveFileProviderManaged`

```diff

-	<key>com.apple.private.pluginkit.persona</key>
-	<string>host</string>

```
### cloudd

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Support/cloudd`

```diff

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.sharereportingd</string>
+	</array>

```
### cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

```diff

+		<string>InProcessShareAccessRequests</string>

```
### assistant_cdmd

> `/System/Library/PrivateFrameworks/ContinuousDialogManagerService.framework/assistant_cdmd`

```diff

+		<string>com.apple.assistant.public</string>

```
### analyticsagent

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent`

```diff

+	<key>com.apple.bluetooth.system</key>
+	<true/>

+		<string>com.apple.bluetooth.xpc</string>

```
### cdpd

> `/System/Library/PrivateFrameworks/CoreCDP.framework/cdpd`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>
+	<key>com.apple.cdp.recoverykey</key>
+	<true/>
+	<key>com.apple.cdp.statemachine</key>
+	<true/>
+	<key>com.apple.cdp.telemetry</key>
+	<true/>
+	<key>com.apple.cdp.utility</key>
+	<true/>
+	<key>com.apple.cdp.walrus</key>
+	<true/>
+	<key>com.apple.cdp.walrus.pcskeys</key>
+	<true/>

```
### contextstored

> `/System/Library/PrivateFrameworks/CoreDuetContext.framework/Resources/contextstored`

```diff

+		<string>App.ExtensionUsage</string>

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

```diff

+		<string>com.apple.assistant.public</string>

```
### speechmaintenanced

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmaintenanced`

```diff

+		<string>com.apple.assistant</string>

+		<string>com.apple.assistant.public</string>
+		<string>com.apple.assistant.support</string>

-		<string>com.apple.assistant</string>

```

### 🆕 speechmodeltrainingd

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmodeltrainingd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.siri.speech-model-training</string>
	<key>com.apple.accounts.appleaccount.fullaccess</key>
	<true/>
	<key>com.apple.coreduetd.allow</key>
	<true/>
	<key>com.apple.itunesstored.private</key>
	<true/>
	<key>com.apple.private.assets.accessible-asset-types</key>
	<array>
		<string>com.apple.MobileAsset.Trial.Siri.SiriUnderstandingAsrAssistant</string>
		<string>com.apple.MobileAsset.Trial.Siri.SiriDictationAssets</string>
		<string>com.apple.MobileAsset.UAF.Siri.Understanding</string>
		<string>com.apple.MobileAsset.EmbeddedSpeech</string>
	</array>
	<key>com.apple.private.assets.bypass-asset-types-check</key>
	<true/>
	<key>com.apple.private.biome.read-only</key>
	<array>
		<string>SiriDictation</string>
	</array>
	<key>com.apple.private.dprivacyd.allow</key>
	<true/>
	<key>com.apple.private.dprivacyd.metadata.allow</key>
	<true/>
	<key>com.apple.private.imcore.spi.database-access</key>
	<true/>
	<key>com.apple.private.security.storage.SpeechPersonalizedLM</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceMediaLibrary</string>
	</array>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/MobileAsset/</string>
		<string>/private/var/db/assetsubscriptiond/</string>
	</array>
	<key>com.apple.security.exception.files.absolute-path.read-write</key>
	<array>
		<string>/private/var/tmp/com.apple.siri-distributed-evaluation/</string>
		<string>/private/var/tmp/com.apple.speechmodeltrainingd/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Assistant/</string>
		<string>/Library/DES/</string>
		<string>/Library/Caches/com.apple.siri.speech-model-training/</string>
		<string>/Library/HTTPStorages</string>
		<string>/Library/HTTPStorages/com.apple.siri.speech-model-training/</string>
		<string>/Library/Trial/</string>
		<string>/Library/UnifiedAssetFramework/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.dprivacyd</string>
		<string>com.apple.FileCoordination</string>
		<string>com.apple.mobileasset.autoasset</string>
		<string>com.apple.appleneuralengine</string>
		<string>com.apple.parsecd</string>
		<string>com.apple.medialibraryd.xpc</string>
		<string>com.apple.itunescloudd.xpc</string>
		<string>com.apple.voiceservices.tts</string>
		<string>com.apple.privacyaccountingd</string>
		<string>com.apple.sirittsd</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.DataDeliveryServices</string>
		<string>com.apple.parsecd</string>
		<string>com.apple.medialibrary</string>
		<string>com.apple.assistant</string>
		<string>com.apple.UnifiedAssetFramework</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.itunescloud</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.siri.embeddedspeech</key>
	<true/>
	<key>com.apple.trial.client</key>
	<array>
		<string>372</string>
		<string>401</string>
	</array>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.icl</string>
	</array>
	<key>platform-application</key>
	<true/>
	<key>seatbelt-profiles</key>
	<array>
		<string>temporary-sandbox</string>
	</array>
</dict>
</plist>

```
### corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

```diff

+				<key>MediaLibrary.SharedPlaylist</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+		<string>com.apple.speech.GeoLM</string>

```
### suggestd

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/suggestd`

```diff

+		<string>kTCCServiceSiriAccess</string>

```
### dataaccessd

> `/System/Library/PrivateFrameworks/DataAccess.framework/Support/dataaccessd`

```diff

+	<key>com.apple.private.appintents.allowed-bundle-identifiers</key>
+	<array>
+		<string>com.apple.mobilecal</string>
+	</array>

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.containment.ipc</key>
+	<true/>
+	<key>com.apple.security.hardened-process.dyld-ro</key>
+	<true/>
+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

```
### com.apple.migrationpluginwrapper

> `/System/Library/PrivateFrameworks/DataMigration.framework/XPCServices/com.apple.migrationpluginwrapper.xpc/com.apple.migrationpluginwrapper`

```diff

+	<key>com.apple.private.tcc.manager.access.delete</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```

### 🆕 AirPlayDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/AirPlayDiagnosticExtension.appex/AirPlayDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.avfoundation.allow-system-wide-context</key>
	<true/>
	<key>com.apple.avfoundation.allows-set-output-device</key>
	<true/>
	<key>com.apple.developer.homekit</key>
	<true/>
	<key>com.apple.homekit.private-spi-access</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceWillow</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.coremedia.endpoint.xpc</string>
		<string>com.apple.coremedia.routediscoverer.xpc</string>
		<string>com.apple.coremedia.routingcontext.xpc</string>
		<string>com.apple.airplay.endpoint.xpc</string>
		<string>com.apple.mediaexperience.endpoint.xpc</string>
		<string>com.apple.symptom_analytics</string>
	</array>
	<key>com.apple.symptoms.NetworkDiagnostics</key>
	<true/>
	<key>com.apple.symptoms.NetworkDiagnostics.query</key>
	<true/>
</dict>
</plist>

```
### HomeEnergyDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/HomeEnergyDiagnosticExtension.appex/HomeEnergyDiagnosticExtension`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.EnergyKit</string>
+	</array>

+	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.EnergyKit</string>
+	</array>

```

### 🆕 IDSDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IDSDiagnosticExtension.appex/IDSDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.DiagnosticExtensions.IDSDiagnosticExtension</string>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.DiagnosticExtensions.IDSDiagnosticExtension</string>
	<key>com.apple.private.ids.diagnosticextension</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.identityservicesd.nsxpc</string>
	</array>
</dict>
</plist>

```
### ScreenTimeDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ScreenTimeDiagnosticExtension.appex/ScreenTimeDiagnosticExtension`

```diff

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

```
### donotdisturbd

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/Support/donotdisturbd`

```diff

+	<key>com.apple.appprotectiond.guard.access</key>
+	<true/>
+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

+		<string>com.apple.appprotectiond.read</string>
+		<string>com.apple.appprotectiond.guard</string>

```
### facetimemessagestored

> `/System/Library/PrivateFrameworks/FaceTimeMessageStore.framework/facetimemessagestored`

```diff

+		<string>com.apple.frauddefensed</string>

+	<key>com.apple.trustkit.frauddefensed</key>
+	<true/>

```
### familycircled

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/familycircled`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### UserFontManager

> `/System/Library/PrivateFrameworks/FontServices.framework/XPCServices/UserFontManager.xpc/UserFontManager`

```diff

+	<key>com.apple.fontservices.allow-migrate-fonts</key>
+	<true/>

```
### GameCenterChallengeIssueExtension

> `/System/Library/PrivateFrameworks/GameCenterUI.framework/PlugIns/GameCenterChallengeIssueExtension.appex/GameCenterChallengeIssueExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### GameCenterMatchmakerExtension

> `/System/Library/PrivateFrameworks/GameCenterUI.framework/PlugIns/GameCenterMatchmakerExtension.appex/GameCenterMatchmakerExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/generativeexperiencesd`

```diff

+		<string>com.apple.assistant.public</string>

```
### HangLogsDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension`

```diff

+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.da</string>
+	</array>

```

### 🆕 HealthAgentsDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthAgents.framework/PlugIns/HealthAgentsDiagnosticExtension.appex/HealthAgentsDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>group.com.apple.healthagents.diagnostics</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/Caches/com.apple.healthappd/HealthAgents/DiagnosticLogs/</string>
		<string>/Library/Caches/com.apple.HealthAgents.HealthAgentsTester/HealthAgents/DiagnosticLogs/</string>
	</array>
</dict>
</plist>

```

### 🆕 HealthAgentsRawDataDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthAgents.framework/PlugIns/HealthAgentsRawDataDiagnosticExtension.appex/HealthAgentsRawDataDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.security.application-groups</key>
	<array>
		<string>group.com.apple.healthagents.diagnostics</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/Caches/com.apple.healthappd/HealthAgents/DiagnosticLogs/</string>
		<string>/Library/Caches/com.apple.HealthAgents.HealthAgentsTester/HealthAgents/DiagnosticLogs/</string>
	</array>
</dict>
</plist>

```
### HealthBalanceDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthBalance.framework/PlugIns/HealthBalanceDiagnosticExtension.appex/HealthBalanceDiagnosticExtension`

```diff

+		<string>/private/var/db/com.apple.countryd/</string>

```

### 🆕 healthcontentd

> `/System/Library/PrivateFrameworks/HealthContent.framework/healthcontentd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.healthcontentd</string>
	<key>com.apple.developer.applesignin</key>
	<array>
		<string></string>
	</array>
	<key>com.apple.developer.fairplay-streaming</key>
	<true/>
	<key>com.apple.duet.activityscheduler.allow</key>
	<true/>
	<key>com.apple.itunesstored.lookup</key>
	<true/>
	<key>com.apple.itunesstored.private</key>
	<true/>
	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
	<array>
		<string>SerialNumber</string>
		<string>UniqueDeviceID</string>
	</array>
	<key>com.apple.private.applemediaservices</key>
	<true/>
	<key>com.apple.private.fairplay.FPDI</key>
	<dict>
		<key>capabilities</key>
		<array>
			<integer>4014732562</integer>
		</array>
		<key>client-identifier</key>
		<string>com.apple.healthcontentd</string>
	</dict>
	<key>com.apple.private.network.socket-delegate</key>
	<true/>
	<key>com.apple.private.sandbox.profile:embedded</key>
	<string>temporary-sandbox</string>
	<key>com.apple.private.security.daemon-container</key>
	<true/>
	<key>com.apple.private.security.storage.Health</key>
	<true/>
	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
	<array>
		<string>/Library/Health/</string>
		<string>/Library/Caches/com.apple.healthcontentd/</string>
		<string>/Library/HTTPStorages/com.apple.healthcontentd/</string>
		<string>/tmp/</string>
		<string>/Library/Caches/com.apple.AppleMediaServices/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.fairplaydeviceidentityd</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.healthcontentd</string>
		<string>com.apple.storeservices.itfe</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.ts.daemon-container</key>
	<true/>
	<key>com.apple.security.ts.tmpdir</key>
	<string>com.apple.healthcontentd</string>
	<key>fairplay-client</key>
	<string>511712240</string>
	<key>keychain-access-groups</key>
	<array>
		<string>com.apple.healthcontentd</string>
		<string>com.apple.Health</string>
		<string>apple</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```

### 🆕 HealthPlansDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthPlans.framework/PlugIns/HealthPlansDiagnosticExtension.appex/HealthPlansDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
</dict>
</plist>

```
### healthappd

> `/System/Library/PrivateFrameworks/HealthPluginHost.framework/healthappd`

```diff

+	<key>com.apple.foundationmodels.web-search-entries</key>
+	<true/>

+	<key>com.apple.keystore.allow.background-processing-assertions</key>
+	<true/>

+		<key>health-agents.user-state</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>Global</string>
+				<string>HealthCharacteristics</string>
+				<string>MotivatorInsight</string>
+				<string>BarrierInsight</string>
+				<string>ResourceInsight</string>
+				<string>HealthSummaryInsight</string>
+				<string>RoutineHabitInsight</string>
+				<string>UserActivityInsight</string>
+				<string>SocialActivityInsight</string>
+				<string>FrequentLocation</string>
+				<string>WorkoutPlaceInsight</string>
+				<string>PersonInsight</string>
+				<string>VehicleInsight</string>
+				<string>EmploymentInsight</string>
+				<string>OrganizationInsight</string>
+			</array>
+		</dict>

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>

+		<string>com.apple.healthcontentd</string>

+		<string>com.apple.private.health.HealthReport</string>

+	<key>com.apple.trial.client</key>
+	<array>
+		<string>SSP_HEALTH_CONFIG</string>
+	</array>

```
### com.apple.health.records.legacy-ingestion

> `/System/Library/PrivateFrameworks/HealthRecordServices.framework/XPCServices/com.apple.health.records.legacy-ingestion.xpc/com.apple.health.records.legacy-ingestion`

```diff

+	<key>com.apple.private.healthrecordsd</key>
+	<true/>

```

### 🆕 HealthAgeDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthReport.framework/PlugIns/HealthAgeDiagnosticExtension.appex/HealthAgeDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.nano.nanoregistry.generalaccess</key>
	<true/>
	<key>com.apple.private.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_bypass</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_manager</key>
	<array>
		<string>read</string>
		<string>write</string>
		<string>reset</string>
	</array>
	<key>com.apple.private.healthkit.feature-availability.read-any</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/db/com.apple.countryd/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/DeviceRegistry.state/ActiveDeviceMiniStore.plist</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.health.shared</string>
		<string>com.apple.private.health.age-gating</string>
		<string>com.apple.private.health.feature-availability-requirement-overrides</string>
	</array>
</dict>
</plist>

```

### 🆕 HealthReportDiagnosticExtension

> `/System/Library/PrivateFrameworks/HealthReport.framework/PlugIns/HealthReportDiagnosticExtension.appex/HealthReportDiagnosticExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.nano.nanoregistry.generalaccess</key>
	<true/>
	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
	<array>
		<string>VasUgeSzVyHdB27g2XpN0g</string>
	</array>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_bypass</key>
	<true/>
	<key>com.apple.private.healthkit.authorization_manager</key>
	<array>
		<string>read</string>
		<string>write</string>
		<string>reset</string>
	</array>
	<key>com.apple.private.healthkit.feature-availability.read-any</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles/Library/ConfigurationProfiles/UserSettings.plist</string>
		<string>/private/var/db/com.apple.countryd/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/DeviceRegistry.state/ActiveDeviceMiniStore.plist</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-only</key>
	<array>
		<string>com.apple.health.shared</string>
		<string>com.apple.private.health.age-gating</string>
		<string>com.apple.private.health.feature-availability-requirement-overrides</string>
		<string>com.apple.Carousel</string>
		<string>com.apple.demo-settings</string>
		<string>com.apple.nanolifestyle.privacy</string>
	</array>
</dict>
</plist>

```
### heard

> `/System/Library/PrivateFrameworks/HearingCore.framework/heard`

```diff

+		<string>com.apple.purplebuddy</string>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

-		<string>com.apple.private.alloy.homepod.topcap</string>

-		<string>com.apple.private.alloy.homepod.topcap</string>

-		<string>com.apple.private.alloy.homepod.topcap</string>

-		<string>com.apple.private.alloy.homepod.topcap</string>

-		<string>com.apple.private.alloy.homepod.topcap</string>

+	<key>com.apple.private.sessionkit.backgroundAudioUpdater</key>
+	<true/>

+		<string>com.apple.assistant.public</string>

-	<key>com.apple.systemstatus.activityattribution</key>
-	<true/>

```
### iapd

> `/System/Library/PrivateFrameworks/IAP.framework/Support/iapd`

```diff

-		<string>apple</string>

```
### identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

```diff

+	<key>com.apple.rapport.LaunchListener</key>
+	<true/>

```
### imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

```diff

+		<string>com.apple.sharereportingd</string>

```
### IMDPersistenceAgent

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/XPCServices/IMDPersistenceAgent.xpc/IMDPersistenceAgent`

```diff

+	<key>com.apple.private.communicationsfilter</key>
+	<true/>

```
### installcoordinationd

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd`

```diff

+	<key>com.apple.keystore.lockassertion</key>
+	<true/>

+	<key>com.apple.private.installcoordination.app-data-migration.host</key>
+	<true/>

+		<string>SetAppReplacementStatus</string>
+		<string>RemoveAppReplacementState</string>
+		<string>PrepareAppReplacement</string>
+		<string>SetAppLaunchProhibited</string>

```
### intelligencecontextd

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd`

```diff

+		<string>com.apple.assistant.public</string>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd`

```diff

+	<key>com.apple.announced.client</key>
+	<true/>

-	<key>com.apple.private.assetsd.xpcstore_restricted.access</key>
-	<array>
-		<string>photos.scene</string>
-		<string>photos.person</string>
-		<string>photos.face</string>
-	</array>

+	<key>com.apple.private.homekit.home-location</key>
+	<true/>

+		<key>com.apple.intelligenceflow.mail-enrichment</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>Mail</string>
+				<string>MailAttachment</string>
+			</array>
+			<key>Sets</key>
+			<dict>
+				<key>App.Intents.IndexedEntity</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+				<key>Cascade.CachedDocument</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

-	<key>com.apple.private.photos.XPCStoreOptIn</key>
-	<true/>

+	<key>com.apple.private.security.storage.PhotosLibraries</key>
+	<true/>

+	<key>com.apple.private.tcc.manager.access.modify</key>
+	<array>
+		<string>kTCCServiceSiri</string>
+	</array>

+		<string>com.apple.team6.buddy.peer</string>

+		<string>com.apple.siri.device_resolution</string>

+		<string>com.apple.siri.local-turn-status</string>

+		<string>com.apple.assistant.public</string>

+		<string>com.apple.suggestions</string>

+	<key>com.apple.siri.device_resolution</key>
+	<true/>

+	<key>com.apple.siri.local-turn-status</key>
+	<true/>

+	<key>com.apple.team6.buddy.peer.profile-read</key>
+	<true/>

+		<string>SIRI_INTELLIGENCE_FLOW_TRAFFIC_CLASSIFIER</string>

```
### destinationd

> `/System/Library/PrivateFrameworks/MapsSuggestions.framework/destinationd`

```diff

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### mediaanalysisd

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd`

```diff

+	<key>com.apple.private.photos.allowcollectionshare</key>
+	<true/>

```
### mediaanalysisd-service

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/mediaanalysisd-service`

```diff

+	<key>com.apple.private.photos.allowcollectionshare</key>
+	<true/>

```
### com.apple.photos.ImageConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.ImageConversionService.xpc/com.apple.photos.ImageConversionService`

```diff

-	<key>com.apple.developer.hardened-process</key>
-	<true/>

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations</key>
+	<true/>

```
### com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.VideoConversionService.xpc/com.apple.photos.VideoConversionService`

```diff

-	<key>com.apple.developer.hardened-process</key>
-	<true/>

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations</key>
+	<true/>

```
### mstreamd

> `/System/Library/PrivateFrameworks/MediaStream.framework/Support/mstreamd`

```diff

-	<key>com.apple.developer.hardened-process</key>
-	<true/>

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocations</key>
+	<true/>

```
### mobiletimerd

> `/System/Library/PrivateFrameworks/MobileTimer.framework/Executables/mobiletimerd`

```diff

+		<string>com.apple.mobiletimer.Alarms</string>

```
### modelcatalogd

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/modelcatalogd`

```diff

+			<key>Sets</key>
+			<dict>
+				<key>ModelCatalog.Subscriptions.RequestedUseCases</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>

-				<key>ModelCatalog.Subscriptions.ExplicitRequests</key>
-				<dict>
-					<key>mode</key>
-					<string>read-only</string>
-				</dict>

+		<string>com.apple.SetStoreUpdateService</string>

```

### 🆕 MomentsAlgorithmsService

> `/System/Library/PrivateFrameworks/MomentsAlgorithms.framework/XPCServices/MomentsAlgorithmsService.xpc/MomentsAlgorithmsService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.MomentsAlgorithmsService</string>
	<key>com.apple.application-identifier</key>
	<string>com.apple.MomentsAlgorithmsService</string>
	<key>com.apple.assistant.cdm.client</key>
	<true/>
	<key>com.apple.developer.foundation-models.allow</key>
	<true/>
	<key>com.apple.developer.private-cloud-compute</key>
	<true/>
	<key>com.apple.intelligenceplatform.EntityResolution</key>
	<true/>
	<key>com.apple.intelligenceplatform.View</key>
	<true/>
	<key>com.apple.modelmanager.inference</key>
	<true/>
	<key>com.apple.private.MobileContainerManager.lookup</key>
	<dict>
		<key>daemon</key>
		<array>
			<string>com.apple.hybridsearchd</string>
		</array>
	</dict>
	<key>com.apple.private.biome.read-write</key>
	<array>
		<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>
	</array>
	<key>com.apple.private.contacts</key>
	<true/>
	<key>com.apple.private.generativesearch.client.search</key>
	<true/>
	<key>com.apple.private.intelligenceplatform.use-cases</key>
	<dict>
		<key>com.apple.generativesearch.gstool</key>
		<dict>
			<key>Search</key>
			<array>
				<string>Global</string>
				<string>Calendar</string>
				<string>Message</string>
				<string>Contact</string>
				<string>SensedContextEvent</string>
				<string>SensedContextPlace</string>
				<string>SensedContextPerson</string>
				<string>SensedContextPattern</string>
				<string>SensedContextAugmentedEvent</string>
				<string>NameInsight</string>
			</array>
			<key>Sets</key>
			<dict>
				<key>App.Intents.IndexedEntity</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
				<key>Cascade.CachedDocument</key>
				<dict>
					<key>mode</key>
					<string>read-only</string>
				</dict>
			</dict>
		</dict>
	</dict>
	<key>com.apple.private.modelcatalog.allow</key>
	<true/>
	<key>com.apple.private.photos.face-detection.access</key>
	<true/>
	<key>com.apple.private.photos.generated-asset-descriptions.access</key>
	<true/>
	<key>com.apple.private.photos.library-access</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServicePhotos</string>
		<string>kTCCServiceAddressBook</string>
	</array>
	<key>com.apple.security.exception.files.absolute-path.read-write</key>
	<array>
		<string>/private/var/mobile/Library/Application Support/ContextAlgorithms/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.modelmanager</string>
		<string>com.apple.modelcatalog.catalog</string>
		<string>com.apple.mobileasset.autoasset</string>
		<string>com.apple.generativesearch.server.search</string>
		<string>com.apple.generativesearch.server.indexing</string>
		<string>com.apple.assistant.cdm</string>
		<string>com.apple.intelligenceplatform.EntityResolution</string>
		<string>com.apple.intelligenceplatform.View</string>
		<string>com.apple.photolibraryd</string>
		<string>com.apple.photoanalysisd</string>
	</array>
</dict>
</plist>

```
### medialibraryd

> `/System/Library/PrivateFrameworks/MusicLibrary.framework/Support/medialibraryd`

```diff

+				<key>MediaLibrary.SharedPlaylist</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>

```
### nanosystemsettingsd

> `/System/Library/PrivateFrameworks/NanoSystemSettings.framework/nanosystemsettingsd`

```diff

+	<key>com.apple.runningboard.process-state</key>
+	<true/>

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>

```
### com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

```diff

+	<key>com.apple.developer.conversation-accessibility</key>
+	<true/>

+		<string>accessibility-interpreter</string>

```
### searchtoold

> `/System/Library/PrivateFrameworks/OmniSearch.framework/searchtoold`

```diff

+	<key>com.apple.developer.healthkit</key>
+	<true/>

+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>

+	<key>com.apple.fitnessintelligenced</key>
+	<true/>

+	<key>com.apple.private.healthkit</key>
+	<true/>
+	<key>com.apple.private.healthkit.authorization_bypass</key>
+	<true/>

+				<string>SiriTranscript</string>
+				<string>SiriTranscriptConversation</string>
+			</array>
+		</dict>
+		<key>generativesearch</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>SiriTranscript</string>
+				<string>SiriTranscriptConversation</string>

+		<string>kTCCServiceHealthKit</string>

+		<string>com.apple.healthd.server</string>
+		<string>com.apple.fitnessintelligenced</string>

+	<key>fairplay-client</key>
+	<string>511712240</string>

```
### amsondevicestoraged

> `/System/Library/PrivateFrameworks/OnDeviceStorage.framework/Support/amsondevicestoraged`

```diff

+	<key>aps-connection-initiate</key>
+	<true/>
+	<key>com.apple.developer.icloud-container-identifiers</key>
+	<array>
+		<string>com.apple.applemediaservices.ondevicestorage</string>
+	</array>
+	<key>com.apple.developer.icloud-services</key>
+	<array>
+		<string>CloudKit</string>
+	</array>

+	<key>com.apple.private.aps-connection-initiate</key>
+	<true/>

+	<key>com.apple.private.icloud-account-access</key>
+	<true/>

+		<string>com.apple.apsd</string>
+		<string>com.apple.cloudd</string>

+		<string>com.apple.aps.amsondevicestoraged</string>

+		<string>com.apple.CloudKit</string>

```
### PhotosDiagnostics

> `/System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PlugIns/PhotosDiagnostics.appex/PhotosDiagnostics`

```diff

+	<key>com.apple.private.tcc.allow</key>
+	<array>
+		<string>kTCCServicePhotos</string>
+	</array>

+		<string>com.apple.photos.service</string>

```
### PerfPowerServicesSignpostService

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/XPCServices/PerfPowerServicesSignpostService.xpc/PerfPowerServicesSignpostService`

```diff

+	<key>com.apple.PerfPowerServices.data-donation</key>
+	<true/>

+		<string>com.apple.powerlog.plxpclogger.xpc</string>
+		<string>com.apple.powerlogHelperd.XPCService.xpc</string>
+		<string>com.apple.PerfPowerTelemetryClientRegistrationService</string>

```
### RemoteManagementAgent

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagementAgent`

```diff

+	<key>com.apple.managedconfiguration.mdmuserd-access</key>
+	<true/>

+		<string>com.apple.managedconfiguration.mdmuserdservice</string>

```
### ManagedStatusSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/ManagedStatusSubscriber.xpc/ManagedStatusSubscriber`

```diff

+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>

+		<string>com.apple.accountsd.accountmanager</string>

+		<string>com.apple.mobile.keybagd.UserManager.xpc</string>
+		<string>com.apple.mobile.keybagd.xpc</string>

```
### ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent`

```diff

+	<key>com.apple.authkit.client.private</key>
+	<true/>
+	<key>com.apple.authkit.deviceList</key>
+	<true/>

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

+		<string>/Library/com.apple.FamilyControlsAgent/Authorizations.plist</string>

```
### ScreenTimeSettingsDeviceActivityMonitorExtension

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/PlugIns/ScreenTimeSettingsDeviceActivityMonitorExtension.appex/ScreenTimeSettingsDeviceActivityMonitorExtension`

```diff

-		<string>com.apple.ScreenTimeSettingsBedtimeNotifications</string>
+		<string>com.apple.ScreenTimeSettingsDowntimeNotifications</string>

```
### ScreenTimeSettingsAgent

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsAgent`

```diff

+	<key>com.apple.chronoservices</key>
+	<true/>

+	<key>com.apple.family.ageRange</key>
+	<true/>

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.FamilyControlsAgent/Authorizations.plist</string>
+	</array>

+		<string>com.apple.chronoservices</string>

```
### searchd

> `/System/Library/PrivateFrameworks/Search.framework/searchd`

```diff

-	<key>com.apple.private.tcc.manager.read.access</key>
+	<key>com.apple.private.tcc.events.subscriber</key>
+	<true/>
+	<key>com.apple.private.tcc.manager.access.read</key>

```
### fitcored

> `/System/Library/PrivateFrameworks/SeymourServices.framework/fitcored`

```diff

+	<key>com.apple.private.servicesintelligence</key>
+	<true/>

+		<string>com.apple.servicesintelligence.xpc.fitness</string>

```
### AirDrop

> `/System/Library/PrivateFrameworks/Sharing.framework/PlugIns/AirDrop.appex/AirDrop`

```diff

+	<key>com.apple.private.airdrop.client</key>
+	<true/>

```
### siriappintentsd

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/siriappintentsd`

```diff

+		<string>SiriTrajectoryInstrumentationEvent</string>

```
### siriinferenced

> `/System/Library/PrivateFrameworks/SiriInference.framework/Support/siriinferenced`

```diff

+		<string>kTCCServiceSiriAccess</string>
+	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>

+		<string>com.apple.tccd</string>

+		<string>com.apple.assistant.public</string>

+		<string>com.apple.tccd</string>

-		<string>351</string>
-		<string>1320</string>
+		<string>SIRI_VALUE_INFERENCE_CONTACT_RESOLUTION</string>
+		<string>SIRI_VALUE_INFERENCE_MESSAGES_SMART_APP_SELECTION</string>

-		<string>1326</string>
-		<string>1327</string>
-		<string>1328</string>
+		<string>SIRI_VALUE_INFERENCE_MEGADOME_ECR</string>
+		<string>SIRI_VALUE_INFERENCE_SIRI_REMEMBERS</string>
+		<string>SIRI_VALUE_INFERENCE_PERVASIVE_ENTITY_RESOLUTION</string>

-		<string>1710</string>
+		<string>TV_SEARCH_APP_ORDERING_SIGNAL_COLLECTION</string>

```

### 🆕 OLEOrchestrator

> `/System/Library/PrivateFrameworks/SiriProcessing.framework/XPCServices/OLEOrchestrator.xpc/OLEOrchestrator`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.lighthouse.host-ole</key>
	<true/>
	<key>com.apple.private.biome.writer</key>
	<array>
		<string>Lighthouse.Ledger.TaskStatus</string>
	</array>
	<key>com.apple.runningboard.process-state</key>
	<true/>
	<key>com.apple.runningboard.terminateprocess</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```
### MusicAppSelectionPFLPlugin

> `/System/Library/PrivateFrameworks/SiriSignals.framework/PlugIns/MusicAppSelectionPFLPlugin.appex/MusicAppSelectionPFLPlugin`

```diff

-		<string>1329</string>
+		<string>SIRI_VALUE_INFERENCE_MUSIC_APP_SELECTION_PFL</string>

```
### SiriSuggestionsBookkeepingService

> `/System/Library/PrivateFrameworks/SiriSuggestionsSupport.framework/XPCServices/SiriSuggestionsBookkeepingService.xpc/SiriSuggestionsBookkeepingService`

```diff

+	<key>com.apple.private.tcc.allow</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>
+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

+		<string>com.apple.tccd</string>

```
### sleepd

> `/System/Library/PrivateFrameworks/SleepDaemon.framework/sleepd`

```diff

+		<string>/private/var/db/com.apple.countryd/</string>

```
### imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

```diff

+	<key>com.apple.springboard.fetchDisplayConfigs</key>
+	<true/>
+	<key>com.apple.springboard.wallpaper.display-configuration</key>
+	<true/>

```
### tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

```diff

+	<key>com.apple.surfboard.CFUserNotification</key>
+	<true/>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

+	<key>com.apple.developer.conversation-accessibility</key>
+	<true/>

-	<key>com.apple.developer.icloud-container-identifiers</key>
-	<array>
-		<string>com.apple.facetime</string>
-	</array>
-	<key>com.apple.developer.icloud-services</key>
-	<array>
-		<string>CloudDocuments</string>
-	</array>
+	<key>com.apple.developer.homekit</key>
+	<true/>

-	<key>com.apple.developer.ubiquity-container-identifiers</key>
-	<array>
-		<string>com.apple.facetime</string>
-	</array>

+	<key>com.apple.homekit.private-spi-access</key>
+	<true/>

-	<key>com.apple.private.clouddocs.auto-accept-share</key>
-	<true/>
-	<key>com.apple.private.clouddocs.sharing.private-interface</key>
-	<true/>

+	<key>com.apple.private.homekit</key>
+	<true/>

-		<string>com.apple.private.alloy.gftaastest.communication</string>

-		<string>com.apple.private.alloy.gftaastest.communication</string>

-		<string>com.apple.private.alloy.gftaastest.communication</string>

-		<string>com.apple.private.alloy.gftaastest.communication</string>

-		<string>com.apple.private.alloy.gftaastest.communication</string>

-		<string>com.apple.private.alloy.gftaastest.communication</string>

-	<key>com.apple.private.librarian.container-proxy</key>
-	<true/>

-	<key>com.apple.private.security.storage.MobileDocuments</key>
-	<true/>

+	<key>com.apple.runningboard.launchprocess</key>
+	<true/>

+		<string>com.apple.homed.xpc</string>
+	</array>
+	<key>com.apple.security.exception.mach-lookup.xpc-service-name</key>
+	<array>
+		<string>com.apple.extensionkitservice</string>

```
### UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

```diff

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

+				<string>Demo.ScreenTime.AppUsage</string>
+				<string>Demo.ScreenTime.MediaUsage</string>
+				<string>Demo.ScreenTime.NowPlaying</string>
+				<string>Demo.ScreenTime.WebUsage</string>

```
### visualintelligenced

> `/System/Library/PrivateFrameworks/VisualIntelligenceServices.framework/visualintelligenced`

```diff

+	<key>com.apple.feedbackd.remote-evaluation</key>
+	<true/>

```
### siriactionsd

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd`

```diff

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

+		<string>com.apple.homed</string>

```
### ShortcutsIntents

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/PlugIns/ShortcutsIntents.appex/ShortcutsIntents`

```diff

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

```
### BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

```diff

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

```
### icloudsubscriptionoptimizerd

> `/System/Library/PrivateFrameworks/iCloudSubscriptionOptimizerDaemon.framework/icloudsubscriptionoptimizerd/icloudsubscriptionoptimizerd`

```diff

+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>

```

### 🆕 CrisisResourceUIPlugin

> `/System/Library/Snippets/UIPlugins/CrisisResourceUIPlugin.bundle/CrisisResourceUIPlugin`

- No entitlements *(yet)*

### 🆕 AppUsageEventPlugin

> `/System/Library/UserEventPlugins/AppUsageEventPlugin.plugin/AppUsageEventPlugin`

- No entitlements *(yet)*

### 🆕 com.apple.ScreenTimeSettingsDowntimeNotifications

> `/System/Library/UserNotifications/Bundles/com.apple.ScreenTimeSettingsDowntimeNotifications.bundle/com.apple.ScreenTimeSettingsDowntimeNotifications`

- No entitlements *(yet)*
### AppStore

> `/private/var/staged_system_apps/AppStore.app/AppStore`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>

+		<string>/private/var/db/os_eligibility/eligibility.plist</string>

```
### Books

> `/private/var/staged_system_apps/Books.app/Books`

```diff

+	<key>com.apple.developer.background-tasks.continued-processing.inference</key>
+	<true/>

+	<key>com.apple.private.biometrickit.allow-connect</key>
+	<true/>

+		<string>/Library/Logs/AppAnalytics/</string>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

+	<key>com.apple.private.device-configuration.effective-configuration-ids.read</key>
+	<array>
+		<string>com.apple.AudioIntelligence</string>
+	</array>

+	<key>com.apple.seserviced.storage-management</key>
+	<true/>

```
### Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

```diff

+		<string>com.apple.familycircle.agent</string>

```
### FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

```diff

+		<string>accessibility-interpreter</string>

```
### FindMy

> `/private/var/staged_system_apps/FindMy.app/FindMy`

```diff

+	<key>com.apple.icloud.searchparty.beaconManager.deviceManageraccess</key>
+	<true/>

```
### FindMyWidgetItems

> `/private/var/staged_system_apps/FindMy.app/PlugIns/FindMyWidgetItems.appex/FindMyWidgetItems`

```diff

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.icloud.fm</string>
+	</array>

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.findmy</string>
+	</array>

```
### FindMyWidgetPeople

> `/private/var/staged_system_apps/FindMy.app/PlugIns/FindMyWidgetPeople.appex/FindMyWidgetPeople`

```diff

+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.icloud.fm</string>
+	</array>

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.findmy</string>
+	</array>

```
### Health

> `/private/var/staged_system_apps/Health.app/Health`

```diff

+	<key>com.apple.developer.in-app-payments</key>
+	<array>
+		<string>merchant.com.apple.health.quest.test</string>
+		<string>merchant.com.apple.health.quest</string>
+	</array>

+	<key>com.apple.fitnesscoachingd</key>
+	<true/>

+		<string>com.apple.MobileAsset.VideoIntelligence</string>

+		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_VideoIntelligence/</string>

+		<string>com.apple.fitnesscoachingd</string>

+		<string>com.apple.health.records.assembler</string>

+		<string>com.apple.nanolifestyle</string>

+		<string>com.apple.private.health.HealthReport</string>

```
### HealthBalanceWidgetExtension

> `/private/var/staged_system_apps/Health.app/PlugIns/HealthBalanceWidgetExtension.appex/HealthBalanceWidgetExtension`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/com.apple.countryd/</string>
+	</array>

```
### HealthMentalHealthWidgetExtension

> `/private/var/staged_system_apps/Health.app/PlugIns/HealthMentalHealthWidgetExtension.appex/HealthMentalHealthWidgetExtension`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/com.apple.countryd/</string>
+	</array>

```
### Home

> `/private/var/staged_system_apps/Home.app/Home`

```diff

+	<key>com.apple.private.application-service-browse</key>
+	<true/>

```
### HomeDiagnosticExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeDiagnosticExtension.appex/HomeDiagnosticExtension`

```diff

+	<key>com.apple.security.temporary-exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/Caches/com.apple.home/</string>
+	</array>

```
### HomeEnergyWidgetsExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeEnergyWidgetsExtension.appex/HomeEnergyWidgetsExtension`

```diff

+	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.Home</string>
+		<string>com.apple.HomeEnergyUI</string>
+		<string>com.apple.sync.NanoHome</string>
+	</array>

```
### HomeFeedbackDiagnosticExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeFeedbackDiagnosticExtension.appex/HomeFeedbackDiagnosticExtension`

```diff

+		<string>/Containers/Data/Application/</string>

+	</array>
+	<key>com.apple.security.temporary-exception.files.home-relative-path.read-only</key>
+	<array>

+		<string>/Library/Caches/com.apple.home/</string>

```
### HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

```diff

-		<string>kTCCServiceWillow</string>
-		<string>kTCCServicePhotos</string>
-		<string>kTCCServiceCamera</string>

+		<string>kTCCServiceCamera</string>

+		<string>kTCCServicePhotos</string>
+		<string>kTCCServiceWillow</string>

```
### HomeWidget

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget`

```diff

-		<string>com.apple.lsd.xpc</string>

+		<string>com.apple.lsd.xpc</string>

+		<string>com.apple.HomeEnergyUI</string>

```
### GenerativePlaygroundAppIntents

> `/private/var/staged_system_apps/Image Playground.app/Extensions/GenerativePlaygroundAppIntents.appex/GenerativePlaygroundAppIntents`

```diff

+		<string>com.apple.applicationaccess</string>

+		<string>com.apple.applicationaccess</string>

```
### Magnifier

> `/private/var/staged_system_apps/Magnifier.app/Magnifier`

```diff

+	<key>com.apple.private.translation</key>
+	<true/>

+		<string>com.apple.translationd</string>

```
### Maps

> `/private/var/staged_system_apps/Maps.app/Maps`

```diff

-	<key>com.apple.AudioAccessoryServices</key>
-	<true/>

+	<key>com.apple.private.jetpackassetd</key>
+	<true/>

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

+	<key>com.apple.runningboard.jetengine</key>
+	<true/>

-		<string>com.apple.AudioAccessoryServices</string>

+		<string>com.apple.jetpackassetd.xpc</string>
+		<string>com.apple.chrono.widgetcenterconnection</string>

+		<string>AD_PLATFORMS_RN_SEARCH_HOME_RN_AA_TEST</string>
+		<string>AD_PLATFORMS_RN_CORE_SEARCH_RN_AA_TEST</string>

```
### CalendarIntentsExtension

> `/private/var/staged_system_apps/MobileCal.app/Extensions/CalendarIntentsExtension.appex/CalendarIntentsExtension`

```diff

+	<key>com.apple.private.suggestions.events</key>
+	<true/>

+		<string>com.apple.suggestd.events</string>

```
### MobileCal

> `/private/var/staged_system_apps/MobileCal.app/MobileCal`

```diff

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.containment.ipc</key>
+	<true/>
+	<key>com.apple.security.hardened-process.dyld-ro</key>
+	<true/>
+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>

+	<key>com.apple.springboard.homeScreenIconStyle</key>
+	<true/>

```
### MobileNotes

> `/private/var/staged_system_apps/MobileNotes.app/MobileNotes`

```diff

+		<string>com.apple.internal.SpotlightAutomationTester</string>

```
### MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

```diff

+	<key>com.apple.businessservicesd.brandLogo</key>
+	<true/>

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### MessagesPluginNotificationExtension

> `/private/var/staged_system_apps/MobileSMS.app/PlugIns/MessagesPluginNotificationExtension.appex/MessagesPluginNotificationExtension`

```diff

+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.asktod</string>
+	</array>

```
### MobileSafari

> `/private/var/staged_system_apps/MobileSafari.app/MobileSafari`

```diff

+		<string>Safari.SearchEngine</string>

+		<string>Unilog.SafariFeature.Stage</string>

+				<key>Unilog.SafariFeature.Stage</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>

```
### Photos

> `/private/var/staged_system_apps/Photos.app/Photos`

```diff

+		<string>group.com.apple.mobileslideshow.SharedAlbums</string>

```

### 🆕 JetIncubation

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/JetIncubation.framework/JetIncubation`

- No entitlements *(yet)*

### 🆕 PodcastsInsights

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsInsights.framework/PodcastsInsights`

- No entitlements *(yet)*

### 🆕 PodcastsLogging

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsLogging.framework/PodcastsLogging`

- No entitlements *(yet)*
### Shortcuts

> `/private/var/staged_system_apps/Shortcuts.app/Shortcuts`

```diff

+	<key>com.apple.privatecloudcompute.knownRateLimits</key>
+	<true/>

+		<string>com.apple.privatecloudcompute</string>

```
### Stocks

> `/private/var/staged_system_apps/Stocks.app/Stocks`

```diff

+	<key>com.apple.developer.background-tasks.continued-processing.inference</key>
+	<true/>

```
### TVRemote

> `/private/var/staged_system_apps/TVRemote.app/TVRemote`

```diff

+	<key>com.apple.PairingManager.HomeKit</key>
+	<true/>
+	<key>com.apple.PairingManager.Read</key>
+	<true/>
+	<key>com.apple.PairingManager.Write</key>
+	<true/>

+	<key>com.apple.nexus</key>
+	<true/>

+		<string>com.apple.nexus</string>
+		<string>com.apple.PairingManager</string>

```
### launchd

> `/sbin/launchd`

```diff

+	<key>com.apple.developer.lockdown-mode.state</key>
+	<true/>

```
### fm

> `/usr/bin/fm`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>

+	<key>com.apple.security.iokit-user-client-class</key>
+	<array>
+		<string>IOSurfaceRootUserClient</string>
+	</array>

```
### modelcatalogdump

> `/usr/bin/modelcatalogdump`

```diff

-		<string>ModelCatalog.Subscriptions.ExplicitRequests</string>

-				<key>ModelCatalog.Subscriptions.ExplicitRequests</key>
-				<dict>
-					<key>mode</key>
-					<string>read-write</string>
-				</dict>

```
### BackupAgent2

> `/usr/libexec/BackupAgent2`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### airplayd

> `/usr/libexec/airplayd`

```diff

+	<key>com.apple.private.audio.driver.extrinsic.registration</key>
+	<true/>

+	<key>com.apple.private.darwin-notification.restrict-post.AirPlay.DACP.mutetoggle</key>
+	<true/>
+	<key>com.apple.private.darwin-notification.restrict-post.AirPlay.DACP.volumedown</key>
+	<true/>
+	<key>com.apple.private.darwin-notification.restrict-post.AirPlay.DACP.volumeup</key>
+	<true/>

```
### appleaccountd

> `/usr/libexec/appleaccountd`

```diff

+	<key>com.apple.cdp.followup</key>
+	<true/>

+	<key>com.apple.cdp.utility</key>
+	<true/>

```

### 🆕 appledepthd

> `/usr/libexec/appledepthd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.security.exception.files.absolute-path.read-only</key>
	<array>
		<string>/private/var/db/assetsubscriptiond/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.siri.uaf.subscription.service</string>
	</array>
</dict>
</plist>

```
### audiomxd

> `/usr/libexec/audiomxd`

```diff

+	<key>com.apple.aop.hid-driver.hid-service.cma</key>
+	<true/>

+	<key>com.apple.security.ts.read-any-bundle</key>
+	<true/>

```
### avconferenced

> `/usr/libexec/avconferenced`

```diff

+	<key>com.apple.private.audio.driver.extrinsic.registration</key>
+	<true/>

-	<key>com.apple.private.speechtranslation.serverhost</key>
-	<true/>

```
### backboardd

> `/usr/libexec/backboardd`

```diff

+	<key>com.apple.private.accessories.transport-client</key>
+	<true/>

```
### cameracaptured

> `/usr/libexec/cameracaptured`

```diff

+		<key>cma</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>

```
### caraccessoryd

> `/usr/libexec/caraccessoryd`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Library/CarPlay/caraccessoryd/</string>
+	</array>

```
### carkitd

> `/usr/libexec/carkitd`

```diff

+	<key>com.apple.private.accessories.transport-client</key>
+	<true/>

```
### ciphermld

> `/usr/libexec/ciphermld`

```diff

+	<key>com.apple.developer.default-data-protection</key>
+	<string>NSFileProtectionCompleteUntilFirstUserAuthentication</string>

```
### coreduetd

> `/usr/libexec/coreduetd`

```diff

+		<string>App.ExtensionUsage</string>

+		<string>App.ExtensionUsage</string>

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### dasd

> `/usr/libexec/dasd`

```diff

+		<string>Device.Wireless.NFCTag</string>
+		<string>Media.NowPlaying</string>
+		<string>CarPlay.Connected</string>
+		<string>Device.Activity.Prediction</string>

```
### diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

```diff

+	<key>com.apple.HomePodDisplay</key>
+	<true/>

+		<string>com.apple.HomePodDisplayService.xpc</string>

```
### gamed

> `/usr/libexec/gamed`

```diff

-	<key>com.apple.private.screen-time</key>
+	<key>com.apple.private.screen-time-settings</key>

-		<string>com.apple.ScreenTimeAgent.exception</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

+	<key>com.apple.symptom_analytics.query</key>
+	<true/>
+	<key>com.apple.symptoms.NetworkOfInterest</key>
+	<true/>

```
### gamesaved

> `/usr/libexec/gamesaved`

```diff

+	<key>com.apple.fileprovider.iwork-collaboration-messaging</key>
+	<true/>

```
### hybridsearchd

> `/usr/libexec/hybridsearchd`

```diff

-	<key>com.apple.Contacts.database-allow</key>
-	<true/>

+		<key>com.apple.GenerativeSearch.FitnessIntelligenceDonationStore</key>
+		<dict>
+			<key>Sets</key>
+			<dict>
+				<key>Fitness.ActivityRings</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+				<key>Fitness.MindfulSession</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+				<key>Fitness.Workout</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+		<key>com.apple.GenerativeSearch.HealthKitDonationStore</key>
+		<dict>
+			<key>Sets</key>
+			<dict>
+				<key>Health.Measurement</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>
+			</dict>
+		</dict>

+				<key>Cascade.CachedDocument</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<string>MotivatorInsight</string>
+				<string>BarrierInsight</string>
+				<string>ResourceInsight</string>
+				<string>FitnessActivityRings</string>
+				<string>FitnessMindfulSession</string>
+				<string>FitnessWorkout</string>
+				<string>HealthCategorySample</string>
+				<string>HealthCharacteristics</string>
+				<string>HealthClassification</string>
+				<string>HealthStatistics</string>
+				<string>HealthSleepDaySummary</string>
+				<string>HealthStateOfMindSample</string>
+				<string>HealthOvernightVitalsSummary</string>
+				<string>WorkoutPlaceInsight</string>
+				<string>HealthSummaryInsight</string>

-		<string>kTCCServiceAddressBook</string>
+		<string>kTCCServiceCalendar</string>

-	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
-	<array>
-		<string>/Library/Application Support/AddressBook/</string>
-		<string>/Library/AddressBook/</string>
-	</array>

-	<key>com.apple.security.personal-information.addressbook</key>
+	<key>com.apple.security.personal-information.calendars</key>

```
### inboxupdaterd

> `/usr/libexec/inboxupdaterd`

```diff

+	<key>com.apple.private.iokit.assertonlidclose</key>
+	<true/>

```
### inputanalyticsd

> `/usr/libexec/inputanalyticsd`

```diff

+	<key>com.apple.private.iokit.batterydataprecise</key>
+	<true/>

+		<string>com.apple.preferences.sounds</string>

```
### logd

> `/usr/libexec/logd`

```diff

+	<key>com.apple.security.exception.iokit-user-client-class</key>
+	<array>
+		<string>AppleThunderboltSATTimeSyncUserClient</string>
+	</array>

```
### manageddeviced

> `/usr/libexec/manageddeviced`

```diff

+	<key>com.apple.surfboard.CFUserNotification</key>
+	<true/>

```

### 🆕 memoryanalyticsd

> `/usr/libexec/memoryanalyticsd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.accounts.appleaccount.fullaccess</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.memoryanalyticsd</string>
	<key>com.apple.diagnosticpipeline.request</key>
	<true/>
	<key>com.apple.private.AuthorizationServices</key>
	<array>
		<string>system.preferences.nvram</string>
	</array>
	<key>com.apple.private.osanalytics.defaults.allow </key>
	<true/>
	<key>com.apple.runningboard.process-state</key>
	<true/>
	<key>com.apple.security.system-groups</key>
	<array>
		<string>systemgroup.com.apple.ReportMemoryException</string>
		<string>systemgroup.com.apple.osanalytics</string>
	</array>
	<key>com.apple.system-task-ports.read</key>
	<true/>
	<key>keychain-access-groups</key>
	<array>
		<string>appleaccount</string>
	</array>
</dict>
</plist>

```
### momentsd

> `/usr/libexec/momentsd`

```diff

+		<string>Demo.ScreenTime.AppUsage</string>
+		<string>Demo.ScreenTime.DisplayBacklight</string>
+		<string>Demo.ScreenTime.MediaUsage</string>
+		<string>Demo.ScreenTime.Notifications</string>
+		<string>Demo.ScreenTime.NowPlaying</string>
+		<string>Demo.ScreenTime.WebUsage</string>

+	<key>com.apple.private.healthkit.database-accessibility-assertion</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>
+	</array>

+		<string>com.apple.MomentsAlgorithmsService</string>

```
### nexusd

> `/usr/libexec/nexusd`

```diff

+	<key>com.apple.developer.device-information.user-assigned-device-name</key>
+	<true/>

```
### remoteappintentsd

> `/usr/libexec/remoteappintentsd`

```diff

+	<key>com.apple.private.dmd.policy</key>
+	<true/>

+	<key>com.apple.private.userprofiles.read</key>
+	<true/>

+		<string>com.apple.userprofiles</string>

```
### riskdatad

> `/usr/libexec/riskdatad`

```diff

+	<key>com.apple.systemstatus.domains</key>
+	<array>
+		<string>background-activities</string>
+	</array>

```
### securityd

> `/usr/libexec/securityd`

```diff

+	<key>com.apple.cdp.utility</key>
+	<true/>

```
### sharingd

> `/usr/libexec/sharingd`

```diff

+	<key>com.apple.private.airdrop.client</key>
+	<true/>

+		<string>com.apple.symptom_diagnostics</string>

+	<key>com.apple.symptom_diagnostics.report</key>
+	<true/>

```
### spotlightknowledged.graph

> `/usr/libexec/spotlightknowledged.graph`

```diff

+				<key>AmbientSensing.Activity</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<key>GenerativeLearningPlatform.Insight</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<key>Health.Measurement</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

```
### spotlightknowledged.updater

> `/usr/libexec/spotlightknowledged.updater`

```diff

+				<key>AmbientSensing.Activity</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<key>GenerativeLearningPlatform.Insight</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

+				<key>Health.Measurement</key>
+				<dict>
+					<key>mode</key>
+					<string>read-only</string>
+				</dict>

```
### sysdiagnosed

> `/usr/libexec/sysdiagnosed`

```diff

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/com.apple.countryd/</string>
+	</array>

```
### textcontextd

> `/usr/libexec/textcontextd`

```diff

-	<key>com.apple.security.exception.shared-preference.read-only</key>
-	<array>
-		<string>com.apple.Archetype</string>
-	</array>

+		<string>com.apple.Archetype</string>

```
### toolkitd

> `/usr/libexec/toolkitd`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.homed</string>
+	</array>

```
### triald

> `/usr/libexec/triald`

```diff

+		<string>Safari.SearchEngine</string>

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.powerlog</string>
+	</array>

```
### triald_system

> `/usr/libexec/triald_system`

```diff

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.powerlog</string>
+	</array>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

+	<key>com.apple.homepodaccessorysettings.client</key>
+	<true/>

+		<string>com.apple.homepodaccessorysettings.server</string>

```
### uarpd

> `/usr/libexec/uarpd`

```diff

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.checked-allocation</key>
+	<true/>
+	<key>com.apple.security.hardened-processs.checked-allocations.soft-mode</key>
+	<true/>

```
### visionhwserverd

> `/usr/libexec/visionhwserverd`

```diff

+	<key>com.apple.locationd.device-impact</key>
+	<true/>

```
### watchdogd

> `/usr/libexec/watchdogd`

```diff

+	<key>com.apple.private.xpc.launchd.system-job-bootstrap</key>
+	<true/>

```
### bluetoothd

> `/usr/sbin/bluetoothd`

```diff

-	<key>com.apple.tailspin.config-apply</key>
-	<true/>
-	<key>com.apple.tailspin.dump-output</key>
-	<true/>

```


