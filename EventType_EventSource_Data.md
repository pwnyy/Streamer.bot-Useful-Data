## List of current EventSources and EventTypes.
EventTypes marked by * still need confirmation.
| EventSource  | EventType |
| ------------- | ------------- |
| Misc         | StreamerbotStarted  |
|              | Test  |
|              | TimedAction  |
|              | ProcessStarted |
|              | ProcessStopped |
|              | ToastActivation |
| Command      | CommandTriggered  |
|              | CommandCooldown  |
| FileWatcher  | FileWatcherChanged  |
|              | FileWatcherCreated  |
|              | FileWatcherDeleted  |
|              | FileWatcherRenamed  |
| HotKey       | HotKeyPress  |
| Midi         | MidiMessage  |
| Quote        | QuoteAdded  |
|              | QuoteShow  |
| SpeechToText | SpeechToTextCommand  |
|              | SpeechToTextDictation  |
| WebsocketClient | WebsocketClientMessage  |
|              | WebsocketClientOpen  |
|              | WebsocketClientClose  |
| WebsocketCustomServer | WebsocketCustomServerMessage  |
|              | WebsocketCustomServerOpen  |
|              | WebsocketCustomServerClose  |
| CrowdControl | CrowdControlEffectFailure  |
|              | CrowdControlEffectRequest  |
|              | CrowdControlEffectSuccess  |
|              | CrowdControlGameSessionEnd  |
|              | CrowdControlGameSessionStart  |
|              | CrowdControlTimedEffectEnded  |
|              | CrowdControlTimedEffectStarted  |
|              | CrowdControlTimedEffectUpdated  |
| Custom       | CustomEvent  |
|              | CustomCodeEvent  |
| Obs          | ObsRecordingStarted  |
|              | ObsRecordingStopped  |
|              | ObsStreamingStarted  |
|              | ObsStreamingStopped  |
|              | ObsConnected  |
|              | ObsDisconnected  |
|              | ObsEvent  |
|              | ObsSceneChanged  |
| StreamDeck   | StreamDeckConnected  |
|              | StreamDeckDisconnected  |
|              | StreamDeckInfo  |
| Elgato       | ElgatoWaveLinkConnected  |
|              | ElgatoWaveLinkDisconnected *  |
|              | ElgatoWaveLinkFilterAdded *  |
|              | ElgatoWaveLinkFilterBypassStateChanged *  |
|              | ElgatoWaveLinkFilterChanged *  |
|              | ElgatoWaveLinkFilterDeleted *  |
|              | ElgatoWaveLinkInputMuteChanged *  |
|              | ElgatoWaveLinkInputNameChanged *  |
|              | ElgatoWaveLinkInputVolumeChanged *  |
|              | ElgatoWaveLinkMicrophoneBalanceChanged *  |
|              | ElgatoWaveLinkMicrophoneGainChanged *  |
|              | ElgatoWaveLinkMicrophoneMuteChanged *  |
|              | ElgatoWaveLinkMicrophoneOutputVolumeChanged *  |
|              | ElgatoWaveLinkMicrophoneSettingsChanged *  |
|              | ElgatoWaveLinkOutputLevelMeterChanged *  |
|              | ElgatoWaveLinkOutputMuteChanged *  |
|              | ElgatoWaveLinkOutputSwitched  |
|              | ElgatoWaveLinkOutputVolumeChanged *  |
|              | ElgatoWaveLinkSelectedOutputChanged *  |
| DonorDrive   | DonorDriveDonation *  |
|              | DonorDriveIncentive *  |
|              | DonorDriveProfileUpdated *  |
| HypeRate     | HypeRateHeartRatePulse  |
| Kofi         | KofiCommission  |
|              | KofiDonation  |
|              | KofiResubscription  |
|              | KofiShopOrder  |
|              | KofiSubscription  |
| Patreon      | PatreonFollowCreated  |
|              | PatreonFollowDeleted  |
|              | PatreonPledgeCreated  |
|              | PatreonPledgeDeleted  |
|              | PatreonPledgeUpdated  |
| Pulsoid      | PulsoidHeartRatePulse  |
| StreamElements | StreamElementsConnected  |
|              | StreamElementsDisconnected  |
|              | StreamElementsMerch  |
|              | StreamElementsTip  |
| Streamlabs   | StreamlabsConnected  |
|              | StreamlabsDisconnected  |
|              | StreamlabsDonation  |
|              | StreamlabsMerchandise  |
| TipeeeStream | TipeeeStreamDonation  |
| TreatStream  | TreatStreamTreat  |
| VTubeStudio  | VTubeStudioTrackingStatusChanged  |
|              | VTubeStudioBackgroundChanged  |
|              | VTubeStudioConnected  |
|              | VTubeStudioDisconnected  |
|              | VTubeStudioHotkeyTriggered *  |
|              | VTubeStudioModelAnimation *  |
|              | VTubeStudioModelConfigurationChanged *  |
|              | VTubeStudioModelLoaded *  |
|              | VTubeStudioModelUnloaded *  |
| Twitch       | TwitchAdMidRoll  |
|              | TwitchAdRun  |
|              | TwitchGoalBegin  |
|              | TwitchGoalEnd  |
|              | TwitchGoalProgress  |
|              | TwitchRewardRedemption *  |
|              | TwitchRewardRedemptionUpdated *  |
|              | TwitchFollow  |
|              | TwitchStreamOffline  |
|              | TwitchStreamOnline  |
|              | TwitchViewerCountUpdate  |
|              | TwitchCharityCompleted  |
|              | TwitchCharityProgress  |
|              | TwitchCharityStarted  |
|              | TwitchCharityDonation  |
|              | TwitchHypeChatLevel  |
|              | TwitchBotWhisper  |
|              | TwitchChatMessage  |
|              | TwitchCheer  |
|              | TwitchHypeChat (decrepitated) |
|              | TwitchWhisper  |
|              | TwitchCommunityGoalContribution  |
|              | TwitchCommunityGoalEnded  |
|              | TwitchBroadcasterAuthenticated  |
|              | TwitchBroadcasterChatConnected  |
|              | TwitchBroadcasterEventSubConnected  |
|              | TwitchBroadcasterPubSubConnected  |
|              | TwitchBroadcasterChatDisconnected  |
|              | TwitchBroadcasterEventSubDisconnected  |
|              | TwitchBroadcasterPubSubDisconnected  |
|              | TwitchBetterTTVEmoteAdded  |
|              | TwitchBetterTTVEmoteRemoved  |
|              | TwitchSevenTVEmoteAdded  |
|              | TwitchSevenTVEmoteRemoved  |
|              | TwitchAnnouncement  |
|              | TwitchFirstWord  |
|              | TwitchPresentViewers  |
|              | TwitchShoutoutReceived  |
|              | TwitchStreamUpdate  |
|              | TwitchGuestStarGuestUpdate  |
|              | TwitchGuestStarSessionBegin  |
|              | TwitchGuestStarSessionEnd  |
|              | TwitchGuestStarSettingsUpdate  |
|              | TwitchHypeTrainEnd  |
|              | TwitchHypeTrainLevelUp  |
|              | TwitchHypeTrainUpdate  |
|              | TwitchHypeTrainStart  |
|              | TwitchChatCleared  |
|              | TwitchChatMessageDeleted  |
|              | TwitchShieldModeBegin  |
|              | TwitchShieldModeEnd  |
|              | TwitchShoutoutCreated  |
|              | TwitchUserBanned  |
|              | TwitchUserTimedOut  |
|              | TwitchPollCompleted  |
|              | TwitchPollCreated  |
|              | TwitchPollTerminated  |
|              | TwitchPollUpdated  |
|              | TwitchPredictionCanceled  |
|              | TwitchPredictionCompleted  |
|              | TwitchPredictionCreated  |
|              | TwitchPredictionLocked  |
|              | TwitchPredictionUpdated  |
|              | TwitchPyramidBroken  |
|              | TwitchPyramidSuccess  |
|              | TwitchRaidCancelled  |
|              | TwitchRaidSend  |
|              | TwitchRaidStart  |
|              | TwitchRaid  |
|              | TwitchSub  |
|              | TwitchResub  |
|              | TwitchGiftSub  |
|              | TwitchGiftBomb  |
| YouTube      | YouTubeBroadcastEnded  |
|              | YouTubeBroadcastStarted  |
|              | YouTubeBroadcastUpdated  |
|              | YouTubeStatisticsUpdated  |
|              | YouTubeMessage  |
|              | YouTubeFirstWords  |
|              | YouTubeSuperChat  |
|              | YouTubeSuperSticker  |
|              | YouTubeNewSubscriber  |
|              | YouTubePresentViewers  |
|              | YouTubeNewSponsor  |
|              | YouTubeNewSponsorOnlyEnded  |
|              | YouTubeNewSponsorOnlyStarted  |
|              | YouTubeUserBanned  |
|              | YouTubeGiftMembershipReceived  |
|              | YouTubeMemberMileStone  |
|              | YouTubeMembershipGift  |
|              | KofiSubscription  |