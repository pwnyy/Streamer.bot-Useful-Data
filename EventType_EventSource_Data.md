## List of current EventSources and EventTypes
### C# Usage in Streamer.Bot Example:
Make sure to click "Find Refs" first in the Code window.
```csharp
using System;
using Streamer.bot.Common.Events;

public class CPHInline
{
	public bool Execute()
	{
		EventType eventType = CPH.GetEventType();
		EventSource eventSource = CPH.GetSource();
		//Check what kind of EventType (or use if)
		switch(eventType)
		{
			case EventType.TwitchSub :
				//Do the Twitch Subscription thing
				break;
			case EventType.TwitchReSub :
				//Do the Twitch Re-Subscription thing
				break;
		}
		//Check what kind of EventSource (or use if)
		switch(eventSource)
		{
			case EventSource.Twitch :
				//Do the Twitch thing
				break;
			case EventSource.YouTube :
				//Do the YouTube thing
				break;
		}
		return true;
	}
}
```


EventTypes marked by * still need confirmation.
| EventSource  | EventType |
| ------------- | ------------- |
|Custom               |Custom                                          |
|Application          |ApplicationActionAdded                          |
|Application          |ApplicationActionDeleted                        |
|Application          |ApplicationActionUpdated                        |
|Command              |CommandCooldown                                 |
|Command              |CommandTriggered                                |
|CrowdControl         |CrowdControlEffectFailure                       |
|CrowdControl         |CrowdControlEffectRequest                       |
|CrowdControl         |CrowdControlEffectSuccess                       |
|CrowdControl         |CrowdControlGameSessionEnd                      |
|CrowdControl         |CrowdControlGameSessionStart                    |
|CrowdControl         |CrowdControlTimedEffectEnded                    |
|CrowdControl         |CrowdControlTimedEffectStarted                  |
|CrowdControl         |CrowdControlTimedEffectUpdated                  |
|Custom               |CustomCodeEvent                                 |
|Custom               |CustomEvent                                     |
|DonorDrive           |DonorDriveDonation                              |
|DonorDrive           |DonorDriveIncentive                             |
|DonorDrive           |DonorDriveProfileUpdated                        |
|Elgato               |ElgatoCameraHubConnected                        |
|Elgato               |ElgatoCameraHubDisconnected                     |
|Elgato               |ElgatoCameraHubPrompterAutoScrollChapterDisabled|
|Elgato               |ElgatoCameraHubPrompterAutoScrollChapterEnabled |
|Elgato               |ElgatoCameraHubPrompterAutoScrollDisabled       |
|Elgato               |ElgatoCameraHubPrompterAutoScrollEnabled        |
|Elgato               |ElgatoCameraHubPrompterBackgroundColorChanged   |
|Elgato               |ElgatoCameraHubPrompterBrightnessChanged        |
|Elgato               |ElgatoCameraHubPrompterChannelsChanged          |
|Elgato               |ElgatoCameraHubPrompterConnected                |
|Elgato               |ElgatoCameraHubPrompterContrastChanged          |
|Elgato               |ElgatoCameraHubPrompterCrosshairColorChanged    |
|Elgato               |ElgatoCameraHubPrompterCrosshairDisabled        |
|Elgato               |ElgatoCameraHubPrompterCrosshairEnabled         |
|Elgato               |ElgatoCameraHubPrompterCrosshairImageChanged    |
|Elgato               |ElgatoCameraHubPrompterDisconnected             |
|Elgato               |ElgatoCameraHubPrompterFontChanged              |
|Elgato               |ElgatoCameraHubPrompterFontColorChanged         |
|Elgato               |ElgatoCameraHubPrompterFontSizeChanged          |
|Elgato               |ElgatoCameraHubPrompterHorizontalMarginChanged  |
|Elgato               |ElgatoCameraHubPrompterLineSpacingChanged       |
|Elgato               |ElgatoCameraHubPrompterModeChanged              |
|Elgato               |ElgatoCameraHubPrompterOpacityChanged           |
|Elgato               |ElgatoCameraHubPrompterScrollSpeedChanged       |
|Elgato               |ElgatoCameraHubPrompterSelectedChannelChanged   |
|Elgato               |ElgatoCameraHubPrompterSelectedChapterChanged   |
|Elgato               |ElgatoCameraHubPrompterSelectedScriptChanged    |
|Elgato               |ElgatoCameraHubPrompterVerticalMarginChanged    |
|Elgato               |ElgatoCameraHubSelectedWebcamChanged            |
|Elgato               |ElgatoCameraHubTiltChanged                      |
|Elgato               |ElgatoCameraHubWebcamARLensChanged              |
|Elgato               |ElgatoCameraHubWebcamActivated                  |
|Elgato               |ElgatoCameraHubWebcamAntiFlickerChanged         |
|Elgato               |ElgatoCameraHubWebcamAutoExposureDisabled       |
|Elgato               |ElgatoCameraHubWebcamAutoExposureEnabled        |
|Elgato               |ElgatoCameraHubWebcamAutoFocusDisabled          |
|Elgato               |ElgatoCameraHubWebcamAutoFocusEnabled           |
|Elgato               |ElgatoCameraHubWebcamAutoWhiteBalanceDisabled   |
|Elgato               |ElgatoCameraHubWebcamAutoWhiteBalanceEnabled    |
|Elgato               |ElgatoCameraHubWebcamBitrateChanged             |
|Elgato               |ElgatoCameraHubWebcamBrightnessChanged          |
|Elgato               |ElgatoCameraHubWebcamConnected                  |
|Elgato               |ElgatoCameraHubWebcamContrastChanged            |
|Elgato               |ElgatoCameraHubWebcamDeactivated                |
|Elgato               |ElgatoCameraHubWebcamDeviceOrientationChanged   |
|Elgato               |ElgatoCameraHubWebcamExposureAutoLockDisabled   |
|Elgato               |ElgatoCameraHubWebcamExposureAutoLockEnabled    |
|Elgato               |ElgatoCameraHubWebcamFlashDisabled              |
|Elgato               |ElgatoCameraHubWebcamFlashEnabled               |
|Elgato               |ElgatoCameraHubWebcamFlipped                    |
|Elgato               |ElgatoCameraHubWebcamFocusChanged               |
|Elgato               |ElgatoCameraHubWebcamISOChanged                 |
|Elgato               |ElgatoCameraHubWebcamLensChanged                |
|Elgato               |ElgatoCameraHubWebcamLiveISOChanged             |
|Elgato               |ElgatoCameraHubWebcamLiveShutterSpeedChanged    |
|Elgato               |ElgatoCameraHubWebcamLiveWhiteBalanceChanged    |
|Elgato               |ElgatoCameraHubWebcamLiveWhiteBalanceTintChanged|
|Elgato               |ElgatoCameraHubWebcamMirrored                   |
|Elgato               |ElgatoCameraHubWebcamNoiseReductionDisabled     |
|Elgato               |ElgatoCameraHubWebcamNoiseReductionEnabled      |
|Elgato               |ElgatoCameraHubWebcamOverscanChanged            |
|Elgato               |ElgatoCameraHubWebcamPanChanged                 |
|Elgato               |ElgatoCameraHubWebcamSaturationChanged          |
|Elgato               |ElgatoCameraHubWebcamSharpnessChanged           |
|Elgato               |ElgatoCameraHubWebcamShutterSpeedChanged        |
|Elgato               |ElgatoCameraHubWebcamSnapshotTaken              |
|Elgato               |ElgatoCameraHubWebcamWhiteBalanceChanged        |
|Elgato               |ElgatoCameraHubWebcamWhiteBalanceTintChanged    |
|Elgato               |ElgatoCameraHubWebcamZoomChanged                |
|Elgato               |ElgatoCameraHubWebcamrDisconnected              |
|Elgato               |ElgatoWaveLinkConnected                         |
|Elgato               |ElgatoWaveLinkDisconnected                      |
|Elgato               |ElgatoWaveLinkFilterAdded                       |
|Elgato               |ElgatoWaveLinkFilterBypassStateChanged          |
|Elgato               |ElgatoWaveLinkFilterChanged                     |
|Elgato               |ElgatoWaveLinkFilterDeleted                     |
|Elgato               |ElgatoWaveLinkInputLevelMeterChanged            |
|Elgato               |ElgatoWaveLinkInputMuteChanged                  |
|Elgato               |ElgatoWaveLinkInputNameChanged                  |
|Elgato               |ElgatoWaveLinkInputVolumeChanged                |
|Elgato               |ElgatoWaveLinkMicrophoneBalanceChanged          |
|Elgato               |ElgatoWaveLinkMicrophoneGainChanged             |
|Elgato               |ElgatoWaveLinkMicrophoneMuteChanged             |
|Elgato               |ElgatoWaveLinkMicrophoneOutputVolumeChanged     |
|Elgato               |ElgatoWaveLinkMicrophoneSettingChanged          |
|Elgato               |ElgatoWaveLinkOutputLevelMeterChanged           |
|Elgato               |ElgatoWaveLinkOutputMuteChanged                 |
|Elgato               |ElgatoWaveLinkOutputSwitched                    |
|Elgato               |ElgatoWaveLinkOutputVolumeChanged               |
|Elgato               |ElgatoWaveLinkSelectedOutputChanged             |
|FileTail             |FileTailChanged                                 |
|FileWatcher          |FileWatcherChanged                              |
|FileWatcher          |FileWatcherCreated                              |
|FileWatcher          |FileWatcherDeleted                              |
|FileWatcher          |FileWatcherRenamed                              |
|Fourthwall           |FourthwallDonation                              |
|Fourthwall           |FourthwallGiftPurchase                          |
|Fourthwall           |FourthwallOrderPlaced                           |
|Fourthwall           |FourthwallOrderUpdated                          |
|Fourthwall           |FourthwallProductCreated                        |
|Fourthwall           |FourthwallProductUpdated                        |
|Fourthwall           |FourthwallSubscriptionChanged                   |
|Fourthwall           |FourthwallSubscriptionExpired                   |
|Fourthwall           |FourthwallSubscriptionPurchased                 |
|HotKey               |HotKeyPress                                     |
|HypeRate             |HypeRateHeartRatePulse                          |
|Kofi                 |KofiCommission                                  |
|Kofi                 |KofiDonation                                    |
|Kofi                 |KofiResubscription                              |
|Kofi                 |KofiShopOrder                                   |
|Kofi                 |KofiSubscription                                |
|Midi                 |MidiMessage                                     |
|Misc                 |ApplicationImport                               |
|Misc                 |ChatWindowAction                                |
|Misc                 |GlobalVariableUpdated                           |
|Misc                 |ProcessStarted                                  |
|Misc                 |ProcessStopped                                  |
|Misc                 |StreamerbotExiting                              |
|Misc                 |StreamerbotStarted                              |
|Misc                 |Test                                            |
|Misc                 |TimedAction                                     |
|Misc                 |ToastActivation                                 |
|Misc                 |UserGlobalVariableUpdated                       |
|Obs                  |ObsConnected                                    |
|Obs                  |ObsDisconnected                                 |
|Obs                  |ObsEvent                                        |
|Obs                  |ObsRecordingStarted                             |
|Obs                  |ObsRecordingStopped                             |
|Obs                  |ObsSceneChanged                                 |
|Obs                  |ObsStreamingStarted                             |
|Obs                  |ObsStreamingStopped                             |
|Patreon              |PatreonFollowCreated                            |
|Patreon              |PatreonFollowDeleted                            |
|Patreon              |PatreonPledgeCreated                            |
|Patreon              |PatreonPledgeDeleted                            |
|Patreon              |PatreonPledgeUpdated                            |
|Pulsoid              |PulsoidHeartRatePulse                           |
|Quote                |QuoteAdded                                      |
|Quote                |QuoteShow                                       |
|Raw                  |RawAction                                       |
|Raw                  |RawActionCompleted                              |
|Raw                  |RawSubAction                                    |
|Shopify              |ShopifyOrderCreated                             |
|Shopify              |ShopifyOrderPaid                                |
|SpeakerBot           |SpeakerBotConnected                             |
|SpeakerBot           |SpeakerBotDisconnected                          |
|SpeechToText         |SpeechToTextCommand                             |
|SpeechToText         |SpeechToTextDictation                           |
|StreamDeck           |StreamDeckAction                                |
|StreamDeck           |StreamDeckConnected                             |
|StreamDeck           |StreamDeckDisconnected                          |
|StreamDeck           |StreamDeckInfo                                  |
|StreamElements       |StreamElementsAuthenticated                     |
|StreamElements       |StreamElementsConnected                         |
|StreamElements       |StreamElementsDisconnected                      |
|StreamElements       |StreamElementsMerch                             |
|StreamElements       |StreamElementsTip                               |
|Streamlabs           |StreamlabsCharityDonation                       |
|Streamlabs           |StreamlabsConnected                             |
|Streamlabs           |StreamlabsDisconnected                          |
|Streamlabs           |StreamlabsDonation                              |
|Streamlabs           |StreamlabsMerchandise                           |
|StreamlabsDesktop    |StreamlabsDesktopConnected                      |
|StreamlabsDesktop    |StreamlabsDesktopDisconnected                   |
|StreamlabsDesktop    |StreamlabsDesktopRecordingStarted               |
|StreamlabsDesktop    |StreamlabsDesktopRecordingStopped               |
|StreamlabsDesktop    |StreamlabsDesktopSceneChanged                   |
|StreamlabsDesktop    |StreamlabsDesktopStreamingStarted               |
|StreamlabsDesktop    |StreamlabsDesktopStreamingStopped               |
|ThrowingSystem       |ThrowingSystemConnected                         |
|ThrowingSystem       |ThrowingSystemEventsConnected                   |
|ThrowingSystem       |ThrowingSystemEventsDisconnected                |
|ThrowingSystem       |ThrowingSystemItemHit                           |
|ThrowingSystem       |ThrowingSystemTriggerActivated                  |
|ThrowingSystem       |ThrowingSystemTriggerEnded                      |
|ThrowingSystem       |ThrowingSystemWebsocketConnected                |
|ThrowingSystem       |ThrowingSystemWebsocketDisconnected             |
|TipeeeStream         |TipeeeStreamDonation                            |
|TreatStream          |TreatStreamTreat                                |
|Trovo                |TrovoBroadcasterAuthenticated                   |
|Trovo                |TrovoBroadcasterChatConnected                   |
|Trovo                |TrovoBroadcasterChatDisconnected                |
|Trovo                |TrovoChatMessage                                |
|Trovo                |TrovoCustomSpellCast                            |
|Trovo                |TrovoFirstWords                                 |
|Trovo                |TrovoFollow                                     |
|Trovo                |TrovoGiftSubscription                           |
|Trovo                |TrovoMassGiftSubscription                       |
|Trovo                |TrovoPresentViewers                             |
|Trovo                |TrovoRaid                                       |
|Trovo                |TrovoResubscription                             |
|Trovo                |TrovoSpellCast                                  |
|Trovo                |TrovoStreamOffline                              |
|Trovo                |TrovoStreamOnline                               |
|Trovo                |TrovoSubscription                               |
|Twitch               |TwitchAdMidRoll                                 |
|Twitch               |TwitchAdRun                                     |
|Twitch               |TwitchAnnouncement                              |
|Twitch               |TwitchBetterTTVEmoteAdded                       |
|Twitch               |TwitchBetterTTVEmoteRemoved                     |
|Twitch               |TwitchBotChatConnected                          |
|Twitch               |TwitchBotChatDisconnected                       |
|Twitch               |TwitchBotWhisper                                |
|Twitch               |TwitchBroadcastUpdate                           |
|Twitch               |TwitchBroadcasterAuthenticated                  |
|Twitch               |TwitchBroadcasterChatConnected                  |
|Twitch               |TwitchBroadcasterChatDisconnected               |
|Twitch               |TwitchBroadcasterEventSubConnected              |
|Twitch               |TwitchBroadcasterEventSubDisconnected           |
|Twitch               |TwitchBroadcasterPubSubConnected                |
|Twitch               |TwitchBroadcasterPubSubDisconnected             |
|Twitch               |TwitchCharityCompleted                          |
|Twitch               |TwitchCharityDonation                           |
|Twitch               |TwitchCharityProgress                           |
|Twitch               |TwitchCharityStarted                            |
|Twitch               |TwitchChatCleared                               |
|Twitch               |TwitchChatEmoteModeOff                          |
|Twitch               |TwitchChatEmoteModeOn                           |
|Twitch               |TwitchChatFollowerModeChanged                   |
|Twitch               |TwitchChatFollowerModeOff                       |
|Twitch               |TwitchChatFollowerModeOn                        |
|Twitch               |TwitchChatMessage                               |
|Twitch               |TwitchChatMessageDeleted                        |
|Twitch               |TwitchChatSlowModeChanged                       |
|Twitch               |TwitchChatSlowModeOff                           |
|Twitch               |TwitchChatSlowModeOn                            |
|Twitch               |TwitchChatSubscriberModeOff                     |
|Twitch               |TwitchChatSubscriberModeOn                      |
|Twitch               |TwitchChatUniqueModeOff                         |
|Twitch               |TwitchChatUniqueModeOn                          |
|Twitch               |TwitchCheer                                     |
|Twitch               |TwitchCoinCheer                                 |
|Twitch               |TwitchCommunityGoalContribution                 |
|Twitch               |TwitchCommunityGoalEnded                        |
|Twitch               |TwitchFirstWord                                 |
|Twitch               |TwitchFollow                                    |
|Twitch               |TwitchGiftBomb                                  |
|Twitch               |TwitchGiftSub                                   |
|Twitch               |TwitchGoalBegin                                 |
|Twitch               |TwitchGoalEnd                                   |
|Twitch               |TwitchGoalProgress                              |
|Twitch               |TwitchGuestStarGuestUpdate                      |
|Twitch               |TwitchGuestStarSessionBegin                     |
|Twitch               |TwitchGuestStarSessionEnd                       |
|Twitch               |TwitchGuestStarSettingsUpdate                   |
|Twitch               |TwitchGuestStarSlotUpdate                       |
|Twitch               |TwitchHypeChat                                  |
|Twitch               |TwitchHypeChatLevel                             |
|Twitch               |TwitchHypeTrainEnd                              |
|Twitch               |TwitchHypeTrainLevelUp                          |
|Twitch               |TwitchHypeTrainStart                            |
|Twitch               |TwitchHypeTrainUpdate                           |
|Twitch               |TwitchModeratorAdded                            |
|Twitch               |TwitchModeratorRemoved                          |
|Twitch               |TwitchPollCompleted                             |
|Twitch               |TwitchPollCreated                               |
|Twitch               |TwitchPollTerminated                            |
|Twitch               |TwitchPollUpdated                               |
|Twitch               |TwitchPredictionCanceled                        |
|Twitch               |TwitchPredictionCompleted                       |
|Twitch               |TwitchPredictionCreated                         |
|Twitch               |TwitchPredictionLocked                          |
|Twitch               |TwitchPredictionUpdated                         |
|Twitch               |TwitchPresentViewers                            |
|Twitch               |TwitchPyramidBroken                             |
|Twitch               |TwitchPyramidSuccess                            |
|Twitch               |TwitchRaid                                      |
|Twitch               |TwitchRaidCancelled                             |
|Twitch               |TwitchRaidSend                                  |
|Twitch               |TwitchRaidStart                                 |
|Twitch               |TwitchReSub                                     |
|Twitch               |TwitchRewardCreated                             |
|Twitch               |TwitchRewardDeleted                             |
|Twitch               |TwitchRewardRedemption                          |
|Twitch               |TwitchRewardRedemptionUpdated                   |
|Twitch               |TwitchRewardUpdated                             |
|Twitch               |TwitchSevenTVEmoteAdded                         |
|Twitch               |TwitchSevenTVEmoteRemoved                       |
|Twitch               |TwitchShieldModeBegin                           |
|Twitch               |TwitchShieldModeEnd                             |
|Twitch               |TwitchShoutoutCreated                           |
|Twitch               |TwitchShoutoutReceived                          |
|Twitch               |TwitchStreamOffline                             |
|Twitch               |TwitchStreamOnline                              |
|Twitch               |TwitchStreamUpdate                              |
|Twitch               |TwitchStreamUpdateGameOnConnect                 |
|Twitch               |TwitchSub                                       |
|Twitch               |TwitchSubCounterRollover                        |
|Twitch               |TwitchUpcomingAd                                |
|Twitch               |TwitchUserBanned                                |
|Twitch               |TwitchUserTimedOut                              |
|Twitch               |TwitchUserUntimedOut                            |
|Twitch               |TwitchViewerCountUpdate                         |
|Twitch               |TwitchVipAdded                                  |
|Twitch               |TwitchWhisper                                   |
|VStream              |VStreamBroadcasterAuthenticated                 |
|VStream              |VStreamBroadcasterChatConnected                 |
|VStream              |VStreamBroadcasterChatDisconnected              |
|VStream              |VStreamChatDeleted                              |
|VStream              |VStreamChatMessage                              |
|VStream              |VStreamFirstWords                               |
|VStream              |VStreamMeteorShower                             |
|VStream              |VStreamNewFollower                              |
|VStream              |VStreamPresentViewers                           |
|VStream              |VStreamResubscription                           |
|VStream              |VStreamStreamOffline                            |
|VStream              |VStreamStreamOnline                             |
|VStream              |VStreamSubscription                             |
|VStream              |VStreamSubscriptionGifted                       |
|VStream              |VStreamSubscriptionsGifted                      |
|VStream              |VStreamUpliftingChat                            |
|VTubeStudio          |VTubeStudioBackgroundChanged                    |
|VTubeStudio          |VTubeStudioConnected                            |
|VTubeStudio          |VTubeStudioDisconnected                         |
|VTubeStudio          |VTubeStudioHotkeyTriggered                      |
|VTubeStudio          |VTubeStudioItemEvent                            |
|VTubeStudio          |VTubeStudioModelAnimation                       |
|VTubeStudio          |VTubeStudioModelClicked                         |
|VTubeStudio          |VTubeStudioModelConfigChanged                   |
|VTubeStudio          |VTubeStudioModelLoaded                          |
|VTubeStudio          |VTubeStudioModelUnloaded                        |
|VTubeStudio          |VTubeStudioTrackingStatusChanged                |
|WebsocketClient      |WebsocketClientClose                            |
|WebsocketClient      |WebsocketClientMessage                          |
|WebsocketClient      |WebsocketClientOpen                             |
|WebsocketCustomServer|WebsocketCustomServerClose                      |
|WebsocketCustomServer|WebsocketCustomServerMessage                    |
|WebsocketCustomServer|WebsocketCustomServerOpen                       |
|YouTube              |YouTubeBroadcastEnded                           |
|YouTube              |YouTubeBroadcastStarted                         |
|YouTube              |YouTubeBroadcastUpdated                         |
|YouTube              |YouTubeFirstWords                               |
|YouTube              |YouTubeGiftMembershipReceived                   |
|YouTube              |YouTubeMemberMileStone                          |
|YouTube              |YouTubeMembershipGift                           |
|YouTube              |YouTubeMessage                                  |
|YouTube              |YouTubeMessageDeleted                           |
|YouTube              |YouTubeNewSponsor                               |
|YouTube              |YouTubeNewSponsorOnlyEnded                      |
|YouTube              |YouTubeNewSponsorOnlyStarted                    |
|YouTube              |YouTubeNewSubscriber                            |
|YouTube              |YouTubePresentViewers                           |
|YouTube              |YouTubeStatisticsUpdated                        |
|YouTube              |YouTubeSuperChat                                |
|YouTube              |YouTubeSuperSticker                             |
|YouTube              |YouTubeUserBanned                               |
