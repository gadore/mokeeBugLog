# mokeeBugLog
05-12 13:35:18.916 D/CloudMusicNativePlayer(17846): GetCurrentPos Fail Current State(3)
05-12 13:35:18.916 D/CloudMusicNativePlayer(17846): AudioStreamTask(9):Start.
05-12 13:35:18.916 D/CloudMusicNativePlayer(17846): Stream(9):Open.
05-12 13:35:18.916 D/CloudMusicNativePlayer(17846): Stream(9):Open Source.
05-12 13:35:18.916 D/CloudMusicNativePlayer(17846): Stream(9):Open Decoder.
05-12 13:35:18.916 D/CloudMusicNativePlayer(17846): source(9):Native Read Begin.
05-12 13:35:18.919 V/qcreverb(24163): 	Effect_command, ctxt 0xddeff300, cmd 2
05-12 13:35:18.919 V/qcreverb(24163): 	Reverb_setConfig, ctxt 0xddeff300
05-12 13:35:18.919 V/qcvirt  (24163): 	Effect_command, ctxt 0xdde6b200, cmd 2
05-12 13:35:18.919 V/qcvirt  (24163): 	Virtualizer_setConfig, ctxt 0xdde6b200
05-12 13:35:18.919 V/qcbassboost(24163): 	Effect_command: ctxt 0xe3112b00, cmd 2
05-12 13:35:18.919 V/qcbassboost(24163): 	BassBoost_setConfig: ctxt 0xe3112b00
05-12 13:35:18.922 V/NewAvrcpMediaPlayerWrapper(25021): onPlaybackStateChanged(): com.netease.cloudmusic : PlaybackState {state=3, position=0, buffered position=0, speed=1.0, updated=138193380, actions=822, custom actions=[], active item id=-1, error=null}
05-12 13:35:18.924 V/NewAvrcpMediaPlayerWrapper(25021): trySendMediaUpdate(): Metadata has been updated for com.netease.cloudmusic
05-12 13:35:18.924 D/NewAvrcpMediaPlayerList(25021): sendMediaUpdate
05-12 13:35:18.924 I/NewAvrcpMediaPlayerList(25021): sendMediaUpdate: Creating a one item queue for a player with no queue
05-12 13:35:18.924 D/NewAvrcpTargetService(25021): onMediaUpdated: track_changed=true state=true queue=true
05-12 13:35:18.924 D/NewAvrcpNativeInterface(25021): sendMediaUpdate: metadata=true playStatus=true queue=true
05-12 13:35:18.924 D/NewAvrcpTargetJni(25021): sendMediaUpdateNative
05-12 13:35:18.924 I/bt_stack(25021): [INFO:avrcp_service.cc(342)] virtual void bluetooth::avrcp::AvrcpService::SendMediaUpdate(bool, bool, bool) track_changed=1 :  play_state=1 :  queue=1
05-12 13:35:18.924 W/bt_stack(25021): [WARNING:device.cc(1192)] Device is not registered for now playing updates
05-12 13:35:18.924 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:18.924 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:18.924 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:18.924 W/bt_stack(25021): [WARNING:device.cc(1167)] Device is not registered for track changed updates
05-12 13:35:18.925 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:18.925 I/bt_stack(25021): [INFO:device.cc(409)] c4:67:b5:39:cc:ea : PlaybackStatusNotificationResponse: Not sending notification due to no state update c4:67:b5:39:cc:ea
05-12 13:35:18.925 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:18.926 D/CloudMusicNativePlayer(17846): source(9):Native Read:1310720 End.
05-12 13:35:18.927 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:18.927 V/NewAvrcpMediaPlayerWrapper(25021): onMetadataChanged(): com.netease.cloudmusic : { mediaId="currsong" title="world.execute (me) ;" artist="Mili" album="" duration=211957 trackPosition=1/1 }
05-12 13:35:18.929 V/NewAvrcpMediaPlayerWrapper(25021): trySendMediaUpdate(): Metadata has been updated for com.netease.cloudmusic
05-12 13:35:18.929 D/NewAvrcpMediaPlayerList(25021): sendMediaUpdate
05-12 13:35:18.929 I/NewAvrcpMediaPlayerList(25021): sendMediaUpdate: Creating a one item queue for a player with no queue
05-12 13:35:18.929 V/qcreverb(24163): 	Effect_command, ctxt 0xddeff300, cmd 2
05-12 13:35:18.929 V/qcreverb(24163): 	Reverb_setConfig, ctxt 0xddeff300
05-12 13:35:18.929 V/qcvirt  (24163): 	Effect_command, ctxt 0xdde6b200, cmd 2
05-12 13:35:18.929 V/qcvirt  (24163): 	Virtualizer_setConfig, ctxt 0xdde6b200
05-12 13:35:18.929 V/qcbassboost(24163): 	Effect_command: ctxt 0xe3112b00, cmd 2
05-12 13:35:18.929 V/qcbassboost(24163): 	BassBoost_setConfig: ctxt 0xe3112b00
05-12 13:35:18.929 D/NewAvrcpTargetService(25021): onMediaUpdated: track_changed=false state=false queue=false
05-12 13:35:18.930 D/NewAvrcpNativeInterface(25021): sendMediaUpdate: metadata=false playStatus=false queue=false
05-12 13:35:18.930 D/NewAvrcpTargetJni(25021): sendMediaUpdateNative
05-12 13:35:18.930 I/bt_stack(25021): [INFO:avrcp_service.cc(342)] virtual void bluetooth::avrcp::AvrcpService::SendMediaUpdate(bool, bool, bool) track_changed=0 :  play_state=0 :  queue=0
05-12 13:35:18.938 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:18.938 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:18.939 D/CloudMusicNativePlayer(17846): AVIOSeek:(0, 65536)
05-12 13:35:18.940 D/CloudMusicNativePlayer(17846): FFmpeg GetSize (5194779)!
05-12 13:35:18.940 D/CloudMusicNativePlayer(17846): AVIOSeek:(0, 65536)
05-12 13:35:18.940 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:18.940 D/CloudMusicNativePlayer(17846): FFmpeg GetSize (5194779)!
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): AVIOSeek:(0, 65536)
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): FFmpeg GetSize (5194779)!
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): AVIOSeek:(0, 65536)
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): FFmpeg GetSize (5194779)!
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): AVIOSeek:(0, 65536)
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): FFmpeg GetSize (5194779)!
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): Decoder(9): Stream index:0, stream_type:1, duration:211.957550
05-12 13:35:18.944 D/CloudMusicNativePlayer(17846): Decoder(9): Stream index:1, stream_type:0, duration:211.957550
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Decoder(9): Codec ID(86017) Code Info:Audio: mp3, 44100 Hz, stereo, s16p, 192 kb/s
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Decoder(9): Pre Codec Open
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): format:mp3
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): support fast seek:1
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Stream(9):Open Decoder End.
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioStreamTask(9):Stream Wait Open
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Player(9) Stream Open
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Player(9) OpenDevice Begin
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioTrack(9):Opened
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioTrack(9): Device Flush
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Player(9) OpenDevice Done (0)
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): SetStereoVolume(1.000000-1.000000)
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioRenderTask(9): Run begin!
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): Player(9) Stream Open Done(0)
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioRenderTask(9):Prepare!
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): PostNativeMsg: what:1, args:0, args2:0
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioRenderTask(9):Prepare Finish!
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioRenderTask(9):Device Init!
05-12 13:35:18.945 D/CloudMusicNativePlayer(17846): AudioRenderTask(9):Running 
05-12 13:35:18.946 D/CloudMusicNativePlayer(17846): AudioStreamTask(9):Stream Run.
05-12 13:35:18.946 D/CloudMusicNativePlayer(17846): Stream(9): Looping Run
05-12 13:35:18.946 D/CloudMusicNativePlayer(17846): Decoder(9): Not Audio Stream Packet!
05-12 13:35:18.946 D/CloudMusicNativePlayer(17846): PostNativeMsg End: what:1, args:0, args2:0
05-12 13:35:18.947 D/LocalPlayback(17846): >>>>onPrepared:com.netease.cloudmusic.module.player.NeteaseAudioPlayer@d207994,-2147483648
05-12 13:35:18.947 D/CloudMusicNativePlayer(17846): call func:jint audio::AudioPlayer_getAudioSessionId(JNIEnv*, jobject)
05-12 13:35:18.947 D/LocalPlayback(17846): >>>>configMediaPlayerState00:-2147483648,2,true,true
05-12 13:35:18.947 D/CloudMusicNativePlayer(17846): setVolume(1.000000-1.000000)
05-12 13:35:18.947 D/CloudMusicNativePlayer(17846): SetStereoVolume(1.000000-1.000000)
05-12 13:35:18.947 D/CloudMusicNativePlayer(17846): call func:jint audio::AudioPlayer_getPlayState(JNIEnv*, jobject)
05-12 13:35:18.947 D/LocalPlayback(17846): >>>>configMediaPlayerState:0,0,-2147483648
05-12 13:35:18.948 D/LocalPlayback(17846): >>>resumeInnerJust:com.netease.cloudmusic.module.player.NeteaseAudioPlayer@d207994,2
05-12 13:35:18.948 W/AudioManager(17846): Use of stream types is deprecated for operations other than volume control
05-12 13:35:18.948 W/AudioManager(17846): See the documentation of requestAudioFocus() for what to use instead with android.media.AudioAttributes to qualify your playback use case
05-12 13:35:18.948 I/MediaFocusControl(  985): requestAudioFocus() from uid/pid 10168/17846 clientId=android.media.AudioManager@e83e721com.netease.cloudmusic.module.player.b.b@6106f64 callingPack=com.netease.cloudmusic req=1 flags=0x0 sdk=22
05-12 13:35:18.949 D/LocalPlayback(17846): >>>tryToGetAudioFocus:2
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): call func:void audio::AudioPlayer_start(JNIEnv*, jobject)
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): Player Play!
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): Player Play finish!
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): DoPlay (5)!
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): AudioTrack(9): Play(1)
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): DoPlay Finish!
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): AudioQueue(9):Fill Wait (0.340658)
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): Enter Buffering<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
05-12 13:35:18.950 D/CloudMusicNativePlayer(17846): PostNativeMsg: what:200, args:701, args2:0
05-12 13:35:18.951 D/CloudMusicNativePlayer(17846): PostNativeMsg End: what:200, args:701, args2:0
05-12 13:35:18.961 V/qcreverb(24163): 	Effect_command, ctxt 0xddeff300, cmd 2
05-12 13:35:18.961 V/qcreverb(24163): 	Reverb_setConfig, ctxt 0xddeff300
05-12 13:35:18.961 V/qcvirt  (24163): 	Effect_command, ctxt 0xdde6b200, cmd 2
05-12 13:35:18.961 V/qcvirt  (24163): 	Virtualizer_setConfig, ctxt 0xdde6b200
05-12 13:35:18.961 V/qcbassboost(24163): 	Effect_command: ctxt 0xe3112b00, cmd 2
05-12 13:35:18.961 V/qcbassboost(24163): 	BassBoost_setConfig: ctxt 0xe3112b00
05-12 13:35:18.965 D/LocalPlayback(17846): >>>>onInfo MEDIA_INFO_BUFFERING_START:3
05-12 13:35:18.968 V/NewAvrcpMediaPlayerWrapper(25021): onPlaybackStateChanged(): com.netease.cloudmusic : PlaybackState {state=3, position=0, buffered position=0, speed=1.0, updated=138193429, actions=822, custom actions=[], active item id=-1, error=null}
05-12 13:35:18.968 W/NewAvrcpMediaPlayerWrapper(25021): onPlaybackStateChanged(): com.netease.cloudmusic tried to update with no new data
05-12 13:35:18.973 F/StreamHalLocal(24163): Local streams can not have effects
05-12 13:35:18.973 F/libc    (24163): Fatal signal 6 (SIGABRT), code -6 (SI_TKILL) in tid 24169 (ApmOutput), pid 24163 (audioserver)
05-12 13:35:18.994 D/CloudMusicNativePlayer(17846): AudioQueue(9):Fill Wait Done(3.005147)
05-12 13:35:18.994 D/CloudMusicNativePlayer(17846): Leave Buffering<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
05-12 13:35:18.995 D/CloudMusicNativePlayer(17846): AudioTrack(9): Play(0)
05-12 13:35:19.026 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.027 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 384 BYTES OUT OF 2688
05-12 13:35:19.027 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 384 bytes instead of 2688
05-12 13:35:19.039 I/crash_dump32(25266): obtaining output fd from tombstoned, type: kDebuggerdTombstone
05-12 13:35:19.040 I//system/bin/tombstoned(  551): received crash request for pid 24169
05-12 13:35:19.040 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.040 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.040 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.040 I/crash_dump32(25266): performing dump of process 24163 (target tid = 24169)
05-12 13:35:19.052 F/DEBUG   (25266): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
05-12 13:35:19.053 F/DEBUG   (25266): MoKee Version: 'MK90.0-icesky-202005090745-NIGHTLY'
05-12 13:35:19.053 F/DEBUG   (25266): Build fingerprint: 'SMARTISAN/icesky_msm8992/icesky_msm8992:5.1.1/LMY47V/1:user/release-keys'
05-12 13:35:19.053 F/DEBUG   (25266): Revision: '0'
05-12 13:35:19.053 F/DEBUG   (25266): ABI: 'arm'
05-12 13:35:19.053 F/DEBUG   (25266): pid: 24163, tid: 24169, name: ApmOutput  >>> /system/bin/audioserver <<<
05-12 13:35:19.053 F/DEBUG   (25266): signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
05-12 13:35:19.053 F/DEBUG   (25266): Abort message: 'Local streams can not have effects'
05-12 13:35:19.053 F/DEBUG   (25266):     r0  00000000  r1  00005e69  r2  00000006  r3  00000008
05-12 13:35:19.053 F/DEBUG   (25266):     r4  00005e63  r5  00005e69  r6  e517b2e4  r7  0000010c
05-12 13:35:19.053 F/DEBUG   (25266):     r8  00000001  r9  e3113280  r10 00000059  r11 00000004
05-12 13:35:19.053 F/DEBUG   (25266):     ip  00000005  sp  e517b2d0  lr  e6f6aee9  pc  e6f62d3a
05-12 13:35:19.054 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.054 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.054 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.068 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.068 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.068 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.083 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.083 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.083 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.086 F/DEBUG   (25266): 
05-12 13:35:19.086 F/DEBUG   (25266): backtrace:
05-12 13:35:19.086 F/DEBUG   (25266):     #00 pc 0001cd3a  /system/lib/libc.so (abort+58)
05-12 13:35:19.086 F/DEBUG   (25266):     #01 pc 00006ccd  /system/lib/liblog.so (__android_log_assert+156)
05-12 13:35:19.086 F/DEBUG   (25266):     #02 pc 00010169  /system/lib/libaudiohal@2.0.so (android::StreamHalLocal::removeEffect(android::sp<android::EffectHalInterface>)+12)
05-12 13:35:19.086 F/DEBUG   (25266):     #03 pc 0001017d  /system/lib/libaudiohal@2.0.so (_ZTv0_n52_N7android14StreamHalLocal12removeEffectENS_2spINS_18EffectHalInterfaceEEE+2)
05-12 13:35:19.086 F/DEBUG   (25266):     #04 pc 00035fcd  /system/lib/libaudioflinger.so (android::AudioFlinger::EffectModule::remove_effect_from_hal_l()+96)
05-12 13:35:19.086 F/DEBUG   (25266):     #05 pc 00034e7d  /system/lib/libaudioflinger.so (android::AudioFlinger::EffectModule::release_l()+12)
05-12 13:35:19.086 F/DEBUG   (25266):     #06 pc 0003803f  /system/lib/libaudioflinger.so (android::AudioFlinger::EffectChain::removeEffect_l(android::sp<android::AudioFlinger::EffectModule> const&, bool)+102)
05-12 13:35:19.087 F/DEBUG   (25266):     #07 pc 0001bc59  /system/lib/libaudioflinger.so (android::AudioFlinger::ThreadBase::removeEffect_l(android::sp<android::AudioFlinger::EffectModule> const&, bool)+80)
05-12 13:35:19.087 F/DEBUG   (25266):     #08 pc 0001bba3  /system/lib/libaudioflinger.so (android::AudioFlinger::ThreadBase::disconnectEffectHandle(android::AudioFlinger::EffectHandle*, bool)+134)
05-12 13:35:19.087 F/DEBUG   (25266):     #09 pc 0003709d  /system/lib/libaudioflinger.so (android::AudioFlinger::EffectHandle::disconnect(bool)+176)
05-12 13:35:19.087 F/DEBUG   (25266):     #10 pc 0002706b  /system/lib/libaudioclient.so (android::AudioEffect::~AudioEffect()+66)
05-12 13:35:19.087 F/DEBUG   (25266):     #11 pc 000271bb  /system/lib/libaudioclient.so (android::AudioEffect::~AudioEffect()+2)
05-12 13:35:19.087 F/DEBUG   (25266):     #12 pc 0000983b  /system/lib/libutils.so (android::RefBase::decStrong(void const*) const+66)
05-12 13:35:19.087 F/DEBUG   (25266):     #13 pc 0000ab1f  /system/lib/libaudiopolicyservice.so (android::Vector<android::sp<android::AudioPolicyService::AudioCommandThread::AudioCommand>>::do_destroy(void*, unsigned int) const+16)
05-12 13:35:19.087 F/DEBUG   (25266):     #14 pc 0000dda1  /system/lib/libutils.so (android::VectorImpl::_shrink(unsigned int, unsigned int)+428)
05-12 13:35:19.087 F/DEBUG   (25266):     #15 pc 0000bb03  /system/lib/libaudiopolicyservice.so (android::AudioPolicyEffects::releaseOutputSessionEffects(int, audio_stream_type_t, audio_session_t)+170)
05-12 13:35:19.087 F/DEBUG   (25266):     #16 pc 0000cbed  /system/lib/libaudiopolicyservice.so (android::AudioPolicyService::doStopOutput(int, audio_stream_type_t, audio_session_t)+64)
05-12 13:35:19.087 F/DEBUG   (25266):     #17 pc 00008ee7  /system/lib/libaudiopolicyservice.so (android::AudioPolicyService::AudioCommandThread::threadLoop()+426)
05-12 13:35:19.087 F/DEBUG   (25266):     #18 pc 0000c087  /system/lib/libutils.so (android::Thread::_threadLoop(void*)+166)
05-12 13:35:19.087 F/DEBUG   (25266):     #19 pc 00064099  /system/lib/libc.so (__pthread_start(void*)+22)
05-12 13:35:19.087 F/DEBUG   (25266):     #20 pc 0001defd  /system/lib/libc.so (__start_thread+24)
05-12 13:35:19.096 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.096 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.096 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.110 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.110 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.110 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.124 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.124 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.124 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.139 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.139 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.139 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.153 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.153 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.153 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.166 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.166 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.166 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.181 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.181 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.181 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.194 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.194 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.194 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.205 W/NativeCrashListener(  985): Couldn't find ProcessRecord for pid 24163
05-12 13:35:19.206 E/crash_dump32(25266): AM data write failed: Broken pipe
05-12 13:35:19.206 E//system/bin/tombstoned(  551): Tombstone written to: /data/tombstones/tombstone_36
05-12 13:35:19.208 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.208 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.208 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.217 I/BootReceiver(  985): Copying /data/tombstones/tombstone_36 to DropBox (SYSTEM_TOMBSTONE)
05-12 13:35:19.222 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.222 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.222 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:34:38.174 I/chatty  (    0): uid=0(root) logd identical 4 lines
05-12 13:35:10.203 W/        (    0): PWM device already freed
05-12 13:35:19.221 I/init    (    0): Untracked pid 25266 exited with status 0
05-12 13:35:19.229 I/init    (    0): Untracked pid 25268 exited with status 0
05-12 13:35:19.237 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.237 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.237 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.250 W/bt_btif (25021): poll timeout (10 ms)
05-12 13:35:19.251 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.251 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.254 I/dropbox_file_copy(  985): [/data/tombstones/tombstone_36,65536,SYSTEM_TOMBSTONE]
05-12 13:35:19.257 W/BroadcastQueue(  985): Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
05-12 13:35:19.258 W/BroadcastQueue(  985): Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
05-12 13:35:19.258 I/commit_sys_config_file(  985): [log-files,4]
05-12 13:35:19.259 I/init    (    0): Service 'audioserver' (pid 24163) received signal 6
05-12 13:35:19.259 I/init    (    0): Sending signal 9 to service 'audioserver' (pid 24163) process group...
05-12 13:35:19.260 I/libprocessgroup(    0): Successfully killed process cgroup uid 1041 pid 24163 in 0ms
05-12 13:35:19.260 I/init    (    0): Command 'restart vendor.audio-hal-2-0' action=onrestart (<Service 'audioserver' onrestart>:1) took 0ms and failed: service vendor.audio-hal-2-0 not found
05-12 13:35:19.260 I/init    (    0): Command 'restart audio-hal-2-0' action=onrestart (<Service 'audioserver' onrestart>:2) took 0ms and failed: service audio-hal-2-0 not found
05-12 13:35:19.260 E/destroy_all_cal_blocks(    0): unmap_cal failed, cal type 2, ret = -22!
05-12 13:35:19.260 E/destroy_all_cal_blocks(    0): unmap_cal failed, cal type 3, ret = -22!
05-12 13:35:19.260 E/destroy_all_cal_blocks(    0): unmap_cal failed, cal type 4, ret = -22!
05-12 13:35:19.260 E/destroy_all_cal_blocks(    0): unmap_cal failed, cal type 5, ret = -22!
05-12 13:35:19.259 W/bt_btif (25021): poll : channel detached remotely
05-12 13:35:19.259 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: CTRL CH DETACHED
05-12 13:35:19.259 W/bt_btif (25021): btif_a2dp_ctrl_cb: A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
05-12 13:35:19.259 W/bt_btif (25021): poll : channel detached remotely
05-12 13:35:19.259 W/bt_btif_a2dp_source(25021): btif_a2dp_source_read_callback: UNDERFLOW: ONLY READ 0 BYTES OUT OF 2688
05-12 13:35:19.259 W/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_send_frames: underflow at PCM reading: read 0 bytes instead of 2688
05-12 13:35:19.259 W/bt_btif (25021): btif_a2dp_data_cb: BTIF MEDIA (A2DP-DATA) EVENT UIPC_CLOSE_EVT
05-12 13:35:19.259 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_NONE, status 0 ##
05-12 13:35:19.259 E/bt_btif (25021): btif_a2dp_command_ack: warning : no command pending, ignore ack
05-12 13:35:19.259 I/btif_av (25021): btif_av_stream_stop peer 00:00:00:00:00:00
05-12 13:35:19.260 I/btif_av (25021): virtual bool BtifAvStateMachine::StateStarted::ProcessEvent(uint32_t, void *): Peer c4:67:b5:39:cc:ea : event=BTIF_AV_STOP_STREAM_REQ_EVT(0x1c) flags=0x0(None)
05-12 13:35:19.260 I/bt_btif_a2dp(25021): btif_a2dp_on_stopped: ## ON A2DP STOPPED ## p_av_suspend=0x0
05-12 13:35:19.260 I/bt_btif_a2dp_source(25021): btif_a2dp_source_on_stopped: state=STATE_RUNNING
05-12 13:35:19.260 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_tx_flush_req: state=STATE_RUNNING
05-12 13:35:19.260 I/bt_btif_a2dp_source(25021): btif_a2dp_source_stop_audio_req: state=STATE_RUNNING
05-12 13:35:19.260 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_tx_flush_event: state=STATE_RUNNING
05-12 13:35:19.260 I/bt_bta_av(25021): BTA_AvStop: handle=65 suspend=true
05-12 13:35:19.260 D/a2dp_vendor_aptx_encoder(25021): aptx_init_framing_params: sleep_time_ns = 14000000
05-12 13:35:19.260 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_tx_stop_event: media_alarm is running, streaming true state=STATE_RUNNING
05-12 13:35:19.260 E/bt_btif (25021): bta_av_str_stopped: peer c4:67:b5:39:cc:ea handle:65 audio_open_cnt:1, p_data 0x70a03e74e8 start:1
05-12 13:35:19.260 E/bt_btif (25021): UIPC_Read : channel 1 closed
05-12 13:35:19.260 W/bt_btif (25021): bta_dm_rm_cback:2, status:6
05-12 13:35:19.260 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_NONE, status 0 ##
05-12 13:35:19.260 E/bt_btif (25021): btif_a2dp_command_ack: warning : no command pending, ignore ack
05-12 13:35:19.260 D/a2dp_vendor_aptx_encoder(25021): aptx_init_framing_params: sleep_time_ns = 14000000
05-12 13:35:19.263 I/init    (    0): starting service 'audioserver'...
05-12 13:35:19.264 W/AudioEffect( 3220): IEffect died
05-12 13:35:19.265 W/AudioEffects-JNI( 3220): EVENT_ERROR
05-12 13:35:19.265 W/IAudioTrack(17846): start() error: Broken pipe
05-12 13:35:19.265 W/AudioTrack(17846): dead IAudioTrack, PCM, creating a new one from start()
05-12 13:35:19.265 W/AudioSystem(  985): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioEffect( 3220): IEffect died
05-12 13:35:19.265 W/AudioEffects-JNI( 3220): EVENT_ERROR
05-12 13:35:19.265 W/AudioSystem(  985): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioEffect( 3220): IEffect died
05-12 13:35:19.265 W/AudioSystem(  985): AudioFlinger server died!
05-12 13:35:19.265 W/AudioEffects-JNI( 3220): EVENT_ERROR
05-12 13:35:19.265 W/AudioSystem(  985): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem(  985): AudioFlinger server died!
05-12 13:35:19.265 W/AudioEffect( 3220): IEffect died
05-12 13:35:19.265 W/AudioEffects-JNI( 3220): EVENT_ERROR
05-12 13:35:19.265 W/AudioSystem( 2042): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem( 3220): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem( 2042): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(  511): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem( 3220): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(25021): AudioFlinger server died!
05-12 13:35:19.265 W/AudioSystem(  511): AudioPolicyService server died!
05-12 13:35:19.265 I/ServiceManager(  343): service 'media.sound_trigger_hw' died
05-12 13:35:19.265 W/AudioSystem(25021): AudioPolicyService server died!
05-12 13:35:19.265 I/ServiceManager(  343): service 'media.audio_flinger' died
05-12 13:35:19.265 I/ServiceManager(  343): service 'media.audio_policy' died
05-12 13:35:19.265 V/MediaRouterService(  985): restoreBluetoothA2dp(true)
05-12 13:35:19.265 W/AudioSystem(17846): AudioPolicyService server died!
05-12 13:35:19.265 W/AudioSystem(17786): AudioFlinger server died!
05-12 13:35:19.266 I/ServiceManager(17846): Waiting for service 'media.audio_flinger' on '/dev/binder'...
05-12 13:35:19.266 E/AudioService(  985): Audioserver died.
05-12 13:35:19.266 I/ServiceManager(  985): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:19.266 I/ServiceManager( 3220): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:19.266 I/ServiceManager(25021): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:19.315 W/bt_btif (25021): bta_dm_rm_cback:2, status:6
05-12 13:35:19.315 I/btif_av (25021): virtual bool BtifAvStateMachine::StateStarted::ProcessEvent(uint32_t, void *): Peer c4:67:b5:39:cc:ea : event=BTA_AV_SUSPEND_EVT(0xf) status=0 initiator=1 flags=0x1(LOCAL_SUSPEND_PENDING)
05-12 13:35:19.315 I/bt_btif_a2dp(25021): btif_a2dp_on_suspended: ## ON A2DP SUSPENDED ## p_av_suspend=0x70a0214878
05-12 13:35:19.315 I/bt_btif_a2dp_source(25021): btif_a2dp_source_on_suspended: state=STATE_RUNNING
05-12 13:35:19.315 I/bt_btif_a2dp_source(25021): btif_a2dp_source_stop_audio_req: state=STATE_RUNNING
05-12 13:35:19.315 I/btif_av (25021): btif_report_audio_state: peer_address=c4:67:b5:39:cc:ea state=1
05-12 13:35:19.315 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_tx_stop_event: media_alarm is not running, streaming false state=STATE_RUNNING
05-12 13:35:19.315 E/bt_btif (25021): UIPC_Read : channel 1 closed
05-12 13:35:19.315 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_NONE, status 0 ##
05-12 13:35:19.315 E/bt_btif (25021): btif_a2dp_command_ack: warning : no command pending, ignore ack
05-12 13:35:19.315 D/a2dp_vendor_aptx_encoder(25021): aptx_init_framing_params: sleep_time_ns = 14000000
05-12 13:35:19.317 I/BluetoothA2dpServiceJni(25021): bta2dp_audio_state_callback
05-12 13:35:19.317 D/A2dpNativeInterface(25021): onAudioStateChanged: A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:C4:67:B5:39:CC:EA, value1:STOPPED}
05-12 13:35:19.317 D/A2dpStateMachine(25021): handleMessage: E msg.what=101
05-12 13:35:19.317 D/A2dpStateMachine(25021): processMsg: Connected
05-12 13:35:19.317 D/A2dpStateMachine(25021): Connected process message(C4:67:B5:39:CC:EA): STACK_EVENT
05-12 13:35:19.317 D/A2dpStateMachine(25021): Connected: stack event: A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:C4:67:B5:39:CC:EA, value1:STOPPED}
05-12 13:35:19.318 I/A2dpStateMachine(25021): Connected: stopped playing: C4:67:B5:39:CC:EA
05-12 13:35:19.318 D/A2dpStateMachine(25021): A2DP Playing state : device: C4:67:B5:39:CC:EA State:PLAYING->NOT_PLAYING
05-12 13:35:19.318 D/A2dpStateMachine(25021): handleMessage: X
05-12 13:35:19.525 I/FastMixerState(25269): sMaxFastTracks = 8
05-12 13:35:19.526 V/MediaUtils(25269): physMem: 2979049472
05-12 13:35:19.526 V/MediaUtils(25269): requested limit: 536870912
05-12 13:35:19.526 V/MediaUtils(25269): actual limit: 536870912
05-12 13:35:19.526 V/MediaUtils(25269): original limits: 4294967295/4294967295
05-12 13:35:19.526 V/MediaUtils(25269): new limits: 536870912/4294967295
05-12 13:35:19.527 I/audioserver(25269): ServiceManager: 0xf5a9c100
05-12 13:35:19.528 I/snet_event_log(  344): [121035042,-1,]
05-12 13:35:19.528 W/hwservicemanager(  344): getTransport: Cannot find entry android.hardware.audio@4.0::IDevicesFactory/default in either framework or device manifest.
05-12 13:35:19.530 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio@2.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:19.531 I/init    (    0): Received control message 'interface_start' for 'android.hardware.audio@4.0::IDevicesFactory/default' from pid: 344 (/system/bin/hwservicemanager)
05-12 13:35:19.531 E/init    (    0): Could not find service hosting interface android.hardware.audio@4.0::IDevicesFactory/default
05-12 13:35:19.532 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio@2.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:19.533 W/hwservicemanager(  344): getTransport: Cannot find entry android.hardware.audio@2.0::IDevicesFactory/msd in either framework or device manifest.
05-12 13:35:19.534 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio@2.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:19.535 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio.effect@4.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:19.535 I/init    (    0): Received control message 'interface_start' for 'android.hardware.audio@2.0::IDevicesFactory/msd' from pid: 344 (/system/bin/hwservicemanager)
05-12 13:35:19.535 E/init    (    0): Could not find service hosting interface android.hardware.audio@2.0::IDevicesFactory/msd
05-12 13:35:19.539 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio.effect@4.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:19.540 I/AudioFlinger(25269): Using default 3000 mSec as standby time.
05-12 13:35:19.545 E/APM::Serializer(25269): deserialize: Could not parse /odm/etc/audio_policy_configuration.xml document.
05-12 13:35:19.545 E/APM::Serializer(25269): deserialize: Could not parse /vendor/etc/audio/audio_policy_configuration.xml document.
05-12 13:35:19.555 D/vndksupport(25269): Loading /vendor/lib/hw/audio.primary.msm8992.so from current namespace instead of sphal namespace.
05-12 13:35:19.558 D/audio_hw_primary(25269): adev_open: enter
05-12 13:35:19.580 W/hardware_info(25269): update_hardware_info_8994: Not an 8994 device
05-12 13:35:19.771 E/AudioService(  985): Audioserver started.
05-12 13:35:19.908 E/        (    0): msm_qti_pp_get_rms_value_control, back not active to query rms be_idx:3
05-12 13:35:19.911 E/        (    0): msm_pcm_volume_ctl_get substream runtime not found
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia4 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia7 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia10 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia11 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia12 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia13 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia14 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia15 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.921 E/audio_route(25269): Control 'MultiMedia16 Mixer MI2S_TX' doesn't exist - skipping
05-12 13:35:19.932 E/audio_route(25269): Control 'RX4 DSM MUX' doesn't exist - skipping
05-12 13:35:19.932 E/audio_route(25269): Control 'RX6 DSM MUX' doesn't exist - skipping
05-12 13:35:19.934 E/audio_route(25269): Control 'AFE_PCM_RX Port Mixer PRI_MI2S_TX' doesn't exist - skipping
05-12 13:35:19.936 E/audio_route(25269): Control 'SLIMBUS_0_RX Audio Mixer MultiMedia3' already exists in path 'audio-ull-playback speaker-and-headphones'
05-12 13:35:19.940 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:19.940 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:19.941 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:19.941 E/audio_route(25269): Control 'MultiMedia8 Mixer SEC_AUX_PCM_UL_TX' doesn't exist - skipping
05-12 13:35:19.942 E/audio_route(25269): Control 'MultiMedia5 Mixer SEC_AUX_PCM_UL_TX' doesn't exist - skipping
05-12 13:35:19.942 E/audio_route(25269): Control 'MultiMedia5 Mixer PRI_MI2S_TX' doesn't exist - skipping
05-12 13:35:19.942 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:19.958 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:19.958 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:19.960 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:19.966 D/msm8974_platform(25269): platform_init: Opened sound card:0
05-12 13:35:19.539 I/chatty  (  344): uid=1000(system) hwservicemanage identical 11 lines
05-12 13:35:19.539 I/snet_event_log(  344): [121035042,-1,]
05-12 13:35:19.965 I/auditd  (25269): type=1400 audit(0.0:9926): avc: denied { read } for comm="audioserver" name="hw_platform" dev="sysfs" ino=20358 scontext=u:r:audioserver:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:19.965 I/audioserver(25269): type=1400 audit(0.0:9926): avc: denied { read } for name="hw_platform" dev="sysfs" ino=20358 scontext=u:r:audioserver:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:19.965 I/auditd  (25269): type=1400 audit(0.0:9927): avc: denied { open } for comm="audioserver" path="/sys/devices/soc0/hw_platform" dev="sysfs" ino=20358 scontext=u:r:audioserver:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:19.965 I/audioserver(25269): type=1400 audit(0.0:9927): avc: denied { open } for path="/sys/devices/soc0/hw_platform" dev="sysfs" ino=20358 scontext=u:r:audioserver:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:19.965 I/auditd  (25269): type=1400 audit(0.0:9928): avc: denied { getattr } for comm="audioserver" path="/sys/devices/soc0/hw_platform" dev="sysfs" ino=20358 scontext=u:r:audioserver:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:19.965 I/audioserver(25269): type=1400 audit(0.0:9928): avc: denied { getattr } for path="/sys/devices/soc0/hw_platform" dev="sysfs" ino=20358 scontext=u:r:audioserver:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_Speaker_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_Global_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_General_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_Bluetooth_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_Handset_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_Hdmi_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> Load file: /etc/acdbdata/MTP/MTP_Headset_cal.acdb
05-12 13:35:19.970 D/ACDB-LOADER(25269): ACDB -> ACDB_CMD_INITIALIZE_V2
05-12 13:35:19.971 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_Speaker_cal.acdb
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.971 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_Global_cal.acdb
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.971 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_General_cal.acdb
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.971 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_Bluetooth_cal.acdb
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.971 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.972 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_Handset_cal.acdb
05-12 13:35:19.972 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.972 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.972 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_Hdmi_cal.acdb
05-12 13:35:19.972 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.972 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.973 D/        (25269): [ACDB Command]->SW Minor/Major/Revision version info for /etc/acdbdata/MTP/MTP_Headset_cal.acdb
05-12 13:35:19.973 D/        (25269): [ACDB Command]->ACDB Sw Major = 5, ACDB Sw Minor = 0, ACDB Sw Revision = 4
05-12 13:35:19.973 D/        (25269): [ACDB Command]->ACDB File Major = 4, ACDB File Minor = 2, ACDB File Revision = 1
05-12 13:35:19.973 D/ACDB-LOADER(25269): ACDB -> ACPH INIT
05-12 13:35:19.973 D/        (25269): [ACPH]->Online service registered with ACPH
05-12 13:35:19.973 E/Diag_Lib(25269):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
05-12 13:35:19.973 E/Diag_Lib(25269):  diagpkt_tbl_reg: Registration failed.
05-12 13:35:19.973 D/        (25269): [ACPH]->ACPH init success
05-12 13:35:19.973 D/ACDB-LOADER(25269): ACDB -> RTAC INIT
05-12 13:35:19.973 D/        (25269): [ACPH]->DSP RTC service registered with ACPH
05-12 13:35:19.973 D/ACDB-LOADER(25269): ACDB -> MCS, FTS INIT
05-12 13:35:19.974 D/        (25269): [ACPH]->MCS RTC service registered with ACPH
05-12 13:35:19.969 I/auditd  (25269): type=1400 audit(0.0:9929): avc: denied { read write } for comm="audioserver" name="msm_audio_cal" dev="tmpfs" ino=10908 scontext=u:r:audioserver:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:19.974 D/        (25269): [ACPH]->FTS RTC service registered with ACPH
05-12 13:35:19.969 I/audioserver(25269): type=1400 audit(0.0:9929): avc: denied { read write } for name="msm_audio_cal" dev="tmpfs" ino=10908 scontext=u:r:audioserver:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:19.974 D/ACDB-LOADER(25269): ACDB -> ADIE RTAC INIT
05-12 13:35:19.974 D/        (25269): [ACPH]->ADIE RTC service registered with ACPH
05-12 13:35:19.974 D/ACDB-LOADER(25269): ACDB -> ACDB_CMD_GET_VOC_PROC_DYNAMIC_TABLE_SIZE
05-12 13:35:19.974 D/        (25269): Invalid AV file. It doesnt contain LUT for tblid 00000017 
05-12 13:35:19.974 D/        (25269): Failed to fetch the Table in ACDB files Table-ID 00000017 
05-12 13:35:19.974 D/ACDB-LOADER(25269): ACDB -> send_meta_info, lic 0
05-12 13:35:19.974 D/        (25269): Couldnt find the key 00000000 
05-12 13:35:19.969 I/auditd  (25269): type=1400 audit(0.0:9930): avc: denied { open } for comm="audioserver" path="/dev/msm_audio_cal" dev="tmpfs" ino=10908 scontext=u:r:audioserver:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:19.969 I/audioserver(25269): type=1400 audit(0.0:9930): avc: denied { open } for path="/dev/msm_audio_cal" dev="tmpfs" ino=10908 scontext=u:r:audioserver:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:19.974 D/        (25269): Output from GetMetaInfoSize command : 0
05-12 13:35:19.969 I/auditd  (25269): type=1400 audit(0.0:9931): avc: denied { ioctl } for comm="audioserver" path="/dev/msm_audio_cal" dev="tmpfs" ino=10908 ioctlcmd=61c8 scontext=u:r:audioserver:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:19.969 I/audioserver(25269): type=1400 audit(0.0:9931): avc: denied { ioctl } for path="/dev/msm_audio_cal" dev="tmpfs" ino=10908 ioctlcmd=61c8 scontext=u:r:audioserver:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> send_adm_custom_topology
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> ACDB_CMD_GET_AUDIO_COPP_TOPOLOGIES
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> AUDIO_SET_ADM_CUSTOM_TOPOLOGY
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> send_asm_custom_topology
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> ACDB_CMD_GET_AUDIO_POPP_TOPOLOGIES
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> AUDIO_SET_ASM_CUSTOM_TOPOLOGY
05-12 13:35:19.979 D/ACDB-LOADER(25269): ACDB -> send_meta_info Enter
05-12 13:35:19.979 E/ACDB-LOADER(25269): Fail to allocate memory for metainfo
05-12 13:35:19.980 D/ACDB-LOADER(25269): ACDB -> send_meta_info failed
05-12 13:35:19.980 D/ACDB-LOADER(25269): ACDB -> init done!
05-12 13:35:19.981 D/audio_hw_ssr(25269): audio_extn_ssr_update_enabled: surround sound recording is not supported
05-12 13:35:19.981 D/audio_hw_spkr_prot(25269): audio_extn_spkr_prot_init: Initialize speaker protection module
05-12 13:35:19.981 D/audio_hw_spkr_prot(25269): audio_extn_spkr_prot_init: Speaker protection disabled
05-12 13:35:19.981 E/DAP_HAL (25269): dap_hal_set_hw_info: dmid=0
05-12 13:35:19.981 E/DAP_HAL (25269):  key 00x
05-12 13:35:19.981 D/msm8974_platform(25269): hw_util_open Opening device /dev/snd/hwC0D1000
05-12 13:35:19.981 D/msm8974_platform(25269): hw_util_open success
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> ACDB_CMD_GET_ANC_SETTING
05-12 13:35:19.981 I/chatty  (25269): uid=1041(audioserver) /system/bin/audioserver identical 7 lines
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> ACDB_CMD_GET_ANC_SETTING
05-12 13:35:19.981 D/msm8974_platform(25269): send_codec_cal cal sent for anc_cal
05-12 13:35:19.981 E/ACDB-LOADER(25269): ACDB -> send_codec_cal
05-12 13:35:19.981 E/ACDB-LOADER(25269): ACDB -> ACDB_CMD_GET_CODEC_CAL_DATA
05-12 13:35:19.981 D/msm8974_platform(25269): send_codec_cal cal sent for mad_cal
05-12 13:35:19.981 D/ACDB-LOADER(25269): send mbhc data
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> MBHC ACDB_PID_GENERAL_CONFIG
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> MBHC ACDB_PID_PLUG_REMOVAL_DETECTION
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> MBHC ACDB_PID_PLUG_TYPE_DETECTION
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> MBHC ACDB_PID_BUTTON_PRESS_DETECTION
05-12 13:35:19.981 D/ACDB-LOADER(25269): ACDB -> MBHC ACDB_PID_IMPEDANCE_DETECTION
05-12 13:35:19.982 D/msm8974_platform(25269): send_codec_cal cal sent for mbhc_cal
05-12 13:35:19.913 I/chatty  (    0): uid=0(root) logd identical 4 lines
05-12 13:35:19.916 E/        (    0): msm_pcm_volume_ctl_get substream runtime not found
05-12 13:30:36.596 I/        (    0): msm8994_pri_mi2s_snd_shutdown Primary MI2S Clock is Disabled
05-12 13:35:19.981 E/core_set_license(    0): Invalid cal block to send
05-12 13:35:19.984 E/audio_hw_primary(25269): adev_open: tfa9890_init called
05-12 13:35:20.001 I/auditd  (25269): type=1400 audit(0.0:9932): avc: denied { read write } for comm="audioserver" name="i2c-5" dev="tmpfs" ino=10893 scontext=u:r:audioserver:s0 tcontext=u:object_r:i2c_device:s0 tclass=chr_file permissive=1
05-12 13:35:20.001 I/audioserver(25269): type=1400 audit(0.0:9932): avc: denied { read write } for name="i2c-5" dev="tmpfs" ino=10893 scontext=u:r:audioserver:s0 tcontext=u:object_r:i2c_device:s0 tclass=chr_file permissive=1
05-12 13:35:20.004 E/        (25269): init_if_firsttime:253 retval
05-12 13:35:20.004 E/        (25269): init_I2C:59 retval
05-12 13:35:20.004 E/        (25269): init_I2C:69 retval
05-12 13:35:20.004 E/        (25269): lxScriboRegister:468 retval
05-12 13:35:20.004 E/        (25269): lxScriboRegister:475 retval
05-12 13:35:20.004 E/        (25269): lxScriboRegister:481 retval
05-12 13:35:20.004 E/        (25269): lxScriboRegister:500 retval
05-12 13:35:20.004 E/        (25269): lxI2cInit:109 devname = /dev/i2c-5
05-12 13:35:20.004 E/        (25269): lxI2cInit:117 devname = /dev/i2c-5
05-12 13:35:20.004 E/        (25269): lxI2cInit:119 devname = /dev/i2c-5
05-12 13:35:20.004 W/audit   (    0): audit_lost=3639 audit_rate_limit=5 audit_backlog_limit=64
05-12 13:35:20.004 E/audit   (    0): rate limit exceeded
05-12 13:35:20.267 I/ServiceManager( 3220): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:20.268 I/ServiceManager(25021): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:20.268 I/ServiceManager(  985): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:20.269 W/AudioSystem(17846): AudioFlinger server died!
05-12 13:35:20.269 I/chatty  (17846): uid=10168(com.netease.cloudmusic) Binder:17846_2 identical 3 lines
05-12 13:35:20.269 W/AudioSystem(17846): AudioFlinger server died!
05-12 13:35:20.509 W/DeviceHAL(25269): Error from HAL Device in function get_master_volume: Function not implemented
05-12 13:35:20.509 W/DeviceHAL(25269): Error from HAL Device in function set_master_volume: Function not implemented
05-12 13:35:20.510 W/DeviceHAL(25269): Error from HAL Device in function set_master_mute: Function not implemented
05-12 13:35:20.510 I/AudioFlinger(25269): loadHwModule() Loaded primary audio interface, handle 10
05-12 13:35:20.510 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x2, SamplingRate 48000, Format 0x000001, Channels 0x3, flags 0x6
05-12 13:35:20.510 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(48000) channel_mask(0x3) devices(0x2) flags(0x6)        stream_handle(0xf2c35000)
05-12 13:35:20.510 D/audio_hw_primary(25269): adev_open_output_stream: Stream (0xf2c35000) picks up usecase (low-latency-playback)
05-12 13:35:20.511 I/AudioFlinger(25269): HAL output buffer size 240 frames, normal sink buffer size 960 frames
05-12 13:35:20.512 I/snet_event_log(  344): [121035042,-1,]
05-12 13:35:20.517 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio.effect@4.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:20.528 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.audio.effect@4.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:20.535 E/EffectsConfig(25269): Could not parse effect configuration in any of the default locations.
05-12 13:35:20.535 E/EffectsFactoryConfigLoader(25269): Failed to parse XML configuration file
05-12 13:35:20.535 W/EffectsFactory(25269): Failed to load XML effect configuration, fallback to .conf
05-12 13:35:20.557 I/MSM-irqbalance(  703): Decided to move IRQ195 from CPU0 to CPU2
05-12 13:35:20.574 I/DiracAPI(25269): ConfigurationManager: Using custom configuration file '/system/vendor/etc/diracmobile.config'
05-12 13:35:20.928 E/DiracAPI(25269): checkVersion: Minor version of Library is different
05-12 13:35:20.928 I/chatty  (25269): uid=1041(audioserver) /system/bin/audioserver identical 3 lines
05-12 13:35:20.928 E/DiracAPI(25269): checkVersion: Minor version of Library is different
05-12 13:35:20.928 I/DiracAPI(25269): ParseConfigurationData: Configuration created by 
05-12 13:35:20.928 I/DiracAPI(25269): '    Project             : 151203_Smartisan_T2_AAC_Lim_PS1_Mod' 
05-12 13:35:20.928 I/DiracAPI(25269): '    At                  : 3 Dec 2015 15:11:56' 
05-12 13:35:20.928 I/DiracAPI(25269): '    With API version    : 2.0.5' 
05-12 13:35:20.928 I/DiracAPI(25269): '    Library version     : 1.1.6' 
05-12 13:35:20.928 I/DiracAPI(25269): '    Configurator version: 1.1.6' 
05-12 13:35:20.928 I/DiracAPI(25269): '    Revision            : 7929' 
05-12 13:35:20.928 I/DiracAPI(25269): ==== Library Info:             
05-12 13:35:20.928 I/DiracAPI(25269): '    API version         : 2.0.5' 
05-12 13:35:20.928 I/DiracAPI(25269): '    Library version     : 1.2.1' 
05-12 13:35:20.928 I/DiracAPI(25269): '    Revision            : 8079' 
05-12 13:35:20.928 W/DiracAPI(25269): No cached entry found for index 1, creating a temporary for decoding info.
05-12 13:35:20.947 W/DiracAPI(25269): No cached entry found for index 0, creating a temporary for decoding info.
05-12 13:35:20.952 W/EffectsFactoryConfigLoader(25269): Error querying effect 7d1580bd-297f-4683-9239-e475b6d1d69f on lib offload_bundle
05-12 13:35:20.952 I/BufferProvider(25269): found effect "Multichannel Downmix To Stereo" from The Android Open Source Project
05-12 13:35:20.952 I/AudioFlinger(25269): Using module 10 as the primary audio interface
05-12 13:35:20.952 I/AudioFlinger(25269): AudioFlinger's thread 0xf2103ec0 tid=25298 ready to run
05-12 13:35:20.952 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:20.958 I/ServiceManager(25269): Waiting for service 'media.audio_policy' on '/dev/binder'...
05-12 13:35:20.961 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:20.961 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:20.961 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:20.962 I/DiracAPI(25269): Dirac_create: DiracObj (F2B8FFB0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.962 I/DiracAPI(25269): (F2B8FFB0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.962 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.962 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:20.962 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.962 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.962 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.962 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:20.965 I/DiracAPI(25269): Dirac_create: DiracObj (F2167030) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.965 I/DiracAPI(25269): (F2167030): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.965 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.965 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:20.965 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.965 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.965 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.969 D/audio_hw_primary(25269): out_standby: enter: stream (0xf2c35000) usecase(1: low-latency-playback)
05-12 13:35:20.969 D/audio_hw_primary(25269): out_standby: mutex unlock out->lock
05-12 13:35:20.969 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:20.971 D/PermissionCache(25269): checking android.permission.MODIFY_AUDIO_SETTINGS for uid=1000 => granted (862 us)
05-12 13:35:20.971 D/audio_hw_primary(25269): adev_set_parameters: enter: restarting=true
05-12 13:35:20.971 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:20.973 I/DiracAPI(25269): Dirac_create: DiracObj (F0FC4DB0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.973 I/DiracAPI(25269): Dirac_create: DiracObj (F2167FC0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.973 I/DiracAPI(25269): (F2167FC0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.973 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.973 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:20.973 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.973 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.973 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.973 I/DiracAPI(25269): (F0FC4DB0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.973 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.973 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:20.973 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.973 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.973 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.973 D/AudioFlinger(25269): isLowRamDevice:false totalMemory:2979049472 mClientSharedHeapSize:8388608
05-12 13:35:20.974 W/AudioFlinger(25269): moveEffects() bad srcOutput 0
05-12 13:35:20.974 D/audio_hw_primary(25269): out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2, device: 2
05-12 13:35:20.974 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:20.975 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x2, SamplingRate 48000, Format 0x000001, Channels 0x3, flags 0x104
05-12 13:35:20.975 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(48000) channel_mask(0x3) devices(0x2) flags(0x104)        stream_handle(0xf2c35780)
05-12 13:35:20.975 D/audio_hw_primary(25269): adev_open_output_stream: Stream (0xf2c35780) picks up usecase (low-latency-playback)
05-12 13:35:20.975 I/AudioFlinger(25269): HAL output buffer size 240 frames, normal sink buffer size 960 frames
05-12 13:35:20.984 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:20.985 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:20.986 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:20.987 I/DiracAPI(25269): Dirac_create: DiracObj (F1C7FF90) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.989 I/DiracAPI(25269): (F1C7FF90): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.989 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.989 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:20.989 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.989 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.989 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.990 I/DiracAPI(25269): Dirac_create: DiracObj (F0EECBF0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.990 I/DiracAPI(25269): (F0EECBF0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.990 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.990 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:20.990 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.990 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.990 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.994 I/DiracAPI(25269): Dirac_create: DiracObj (F0DE5DD0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.994 I/DiracAPI(25269): (F0DE5DD0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.994 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.994 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:20.994 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.994 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.994 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.994 I/DiracAPI(25269): Dirac_create: DiracObj (F2BC9730) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:20.994 I/DiracAPI(25269): (F2BC9730): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:20.994 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:20.994 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:20.994 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:20.994 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:20.994 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:20.995 I/AudioFlinger(25269): AudioFlinger's thread 0xf0d83600 tid=25301 ready to run
05-12 13:35:20.996 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:20.996 D/audio_hw_primary(25269): out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2, device: 2
05-12 13:35:20.996 D/audio_hw_primary(25269): out_standby: enter: stream (0xf2c35780) usecase(1: low-latency-playback)
05-12 13:35:20.996 D/audio_hw_primary(25269): out_standby: mutex unlock out->lock
05-12 13:35:20.997 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x2, SamplingRate 48000, Format 0x000001, Channels 0x3, flags 0x8
05-12 13:35:20.997 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(48000) channel_mask(0x3) devices(0x2) flags(0x8)        stream_handle(0xf2c35600)
05-12 13:35:20.997 E/audio_hw_primary(25269): adev_open_output_stream: Primary output is already opened
05-12 13:35:20.997 D/audio_hw_primary(25269): adev_open_output_stream: exit: ret -17
05-12 13:35:20.997 W/DeviceHAL(25269): Error from HAL Device in function open_output_stream: File exists
05-12 13:35:20.997 I/AudioHwDevice(25269): openOutputStream(), HAL returned sampleRate 48000, Format 0x1, channelMask 0x3, status -61
05-12 13:35:20.997 W/APM_AudioPolicyManager(25269): Cannot open output stream for device 00000002 on hw module primary
05-12 13:35:20.997 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x10000, SamplingRate 48000, Format 0x000001, Channels 0x3, flags 0
05-12 13:35:20.997 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(48000) channel_mask(0x3) devices(0x10000) flags(0)        stream_handle(0xf2c35600)
05-12 13:35:20.997 D/audio_hw_primary(25269): adev_open_output_stream: Stream (0xf2c35600) picks up usecase (afe-proxy-playback)
05-12 13:35:20.997 I/AudioFlinger(25269): HAL output buffer size 768 frames, normal sink buffer size 1152 frames
05-12 13:35:21.007 I/DiracAPI(25269): Dirac_create: DiracObj (F0A2B130) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.008 I/AudioFlinger(25269): AudioFlinger's thread 0xf09abac0 tid=25303 ready to run
05-12 13:35:21.008 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.008 D/audio_hw_primary(25269): out_standby: enter: stream (0xf2c35600) usecase(36: afe-proxy-playback)
05-12 13:35:21.008 D/audio_hw_primary(25269): out_standby: mutex unlock out->lock
05-12 13:35:21.008 I/DiracAPI(25269): Dirac_create: DiracObj (F09FCF40) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.009 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.009 I/DiracAPI(25269): (F09FCF40): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.009 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.009 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.009 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.009 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.009 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.009 D/audio_hw_primary(25269): out_set_parameters: enter: usecase(36: afe-proxy-playback) kvpairs: routing=65536, device: 65536
05-12 13:35:21.009 I/DiracAPI(25269): (F0A2B130): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.009 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.009 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.009 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.009 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.009 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.009 D/audio_hw_primary(25269): adev_open_input_stream: enter: sample_rate(48000) channel_mask(0xc) devices(0x80002000)        stream_handle(0xf5ac3e60) io_handle(14) source(1)
05-12 13:35:21.010 E/audio_hw_extn(25269): audio_extn_perf_lock_init: Perf lock handles Success 
05-12 13:35:21.011 I/AudioFlinger(25269): AudioFlinger's thread 0xf0583d00 tid=25304 ready to run
05-12 13:35:21.011 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.011 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.012 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.013 I/DiracAPI(25269): Dirac_create: DiracObj (F051A5F0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.013 I/DiracAPI(25269): (F051A5F0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.013 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.013 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.013 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.013 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.013 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.013 I/DiracAPI(25269): Dirac_create: DiracObj (F05F96D0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.013 I/DiracAPI(25269): (F05F96D0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.013 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.013 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.013 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.013 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.013 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.015 I/DiracAPI(25269): Dirac_create: DiracObj (F052D970) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.015 I/DiracAPI(25269): (F052D970): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.015 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.015 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.015 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.015 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.015 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.015 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.016 D/audio_hw_primary(25269): adev_close_input_stream: enter:stream_handle(0xf5ac3e60)
05-12 13:35:21.016 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.017 D/audio_hw_primary(25269): adev_open_input_stream: enter: sample_rate(48000) channel_mask(0x17000c) devices(0x80000004)        stream_handle(0xf5ac3e60) io_handle(22) source(1)
05-12 13:35:21.018 E/AudioFlinger(25269): not enough memory for pipe buffer size=49152; roHeap=0xf05f9d90, pipeMemory=0x0, pipeBuffer=0x0; roHeapSize: 16384
05-12 13:35:21.022 I/DiracAPI(25269): Dirac_create: DiracObj (F057F9F0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.023 I/DiracAPI(25269): Dirac_create: DiracObj (F03AA320) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.023 I/DiracAPI(25269): (F03AA320): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.023 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.023 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.023 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.023 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.023 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.024 I/DiracAPI(25269): (F057F9F0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.024 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.024 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.024 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.024 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.024 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.025 I/DiracAPI(25269): Dirac_create: DiracObj (F02D5160) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.025 I/DiracAPI(25269): (F02D5160): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.025 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.025 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.025 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.025 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.025 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.027 I/DiracAPI(25269): Dirac_create: DiracObj (F02D5FA0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.027 I/DiracAPI(25269): (F02D5FA0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.027 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.027 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.027 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.027 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.027 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.028 I/DiracAPI(25269): Dirac_create: DiracObj (F0325830) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.028 I/DiracAPI(25269): (F0325830): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.028 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.028 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.028 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.028 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.028 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.029 I/DiracAPI(25269): Dirac_create: DiracObj (F02EEDE0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.029 I/DiracAPI(25269): (F02EEDE0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.029 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.029 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.029 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.029 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.029 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.030 I/DiracAPI(25269): Dirac_create: DiracObj (F034D670) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.030 I/DiracAPI(25269): (F034D670): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.030 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.030 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.030 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.030 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.030 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.031 I/DiracAPI(25269): Dirac_create: DiracObj (F026CC20) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.031 I/DiracAPI(25269): (F026CC20): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.031 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.031 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.031 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.031 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.031 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.032 I/DiracAPI(25269): Dirac_create: DiracObj (F01AD4B0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.032 I/DiracAPI(25269): (F01AD4B0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.032 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.032 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.032 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.032 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.032 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.033 I/DiracAPI(25269): Dirac_create: DiracObj (F0273A60) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.033 I/DiracAPI(25269): (F0273A60): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.033 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.033 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.033 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.033 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.033 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.034 I/DiracAPI(25269): Dirac_create: DiracObj (F01BA2F0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.034 I/DiracAPI(25269): (F01BA2F0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.034 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.034 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.034 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.034 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.034 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.034 I/DiracAPI(25269): Dirac_create: DiracObj (F010F8A0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.035 I/DiracAPI(25269): (F010F8A0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.035 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.035 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.035 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.035 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.035 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.035 I/DiracAPI(25269): Dirac_create: DiracObj (F101F130) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.035 I/DiracAPI(25269): (F101F130): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.035 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.035 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.035 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.035 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.035 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.036 I/AudioFlinger(25269): AudioFlinger's thread 0xf0583880 tid=25305 ready to run
05-12 13:35:21.036 D/audio_hw_primary(25269): adev_close_input_stream: enter:stream_handle(0xf5ac3e60)
05-12 13:35:21.036 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.036 D/audio_hw_primary(25269): adev_open_input_stream: enter: sample_rate(48000) channel_mask(0xc) devices(0x80000040)        stream_handle(0xf5ac3e60) io_handle(30) source(1)
05-12 13:35:21.036 W/DeviceHAL(25269): Error from HAL Device in function open_input_stream: Invalid argument
05-12 13:35:21.036 D/audio_hw_primary(25269): adev_open_input_stream: enter: sample_rate(48000) channel_mask(0xc) devices(0x80000040)        stream_handle(0xf5ac3e60) io_handle(30) source(1)
05-12 13:35:21.036 W/DeviceHAL(25269): Error from HAL Device in function open_input_stream: Invalid argument
05-12 13:35:21.036 W/APM_AudioPolicyManager(25269): Cannot open input stream for device 80000040 on hw module primary
05-12 13:35:21.036 I/DiracAPI(25269): Dirac_create: DiracObj (F0133600) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.038 I/DiracAPI(25269): Dirac_create: DiracObj (F101FF70) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.039 I/DiracAPI(25269): (F0133600): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.039 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.039 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.039 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.039 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.039 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.043 I/DiracAPI(25269): (F101FF70): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.043 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.043 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.043 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.043 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.043 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.044 I/DiracAPI(25269): Dirac_create: DiracObj (F02BF440) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.044 I/DiracAPI(25269): (F02BF440): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.044 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.044 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.044 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.044 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.044 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.045 I/DiracAPI(25269): Dirac_create: DiracObj (F0314DB0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.045 I/DiracAPI(25269): (F0314DB0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.045 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.045 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.045 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.045 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.045 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.046 I/DiracAPI(25269): Dirac_create: DiracObj (F068C280) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.046 I/DiracAPI(25269): Dirac_create: DiracObj (F0A26C20) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.046 I/DiracAPI(25269): (F068C280): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.046 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.046 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.046 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.046 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.046 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.047 I/DiracAPI(25269): Dirac_create: DiracObj (F0314EF0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.047 I/DiracAPI(25269): Dirac_create: DiracObj (F05F1A00) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.052 I/DiracAPI(25269): (F0314EF0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.052 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.052 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.052 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.052 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.052 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.058 I/DiracAPI(25269): Dirac_create: DiracObj (F05F97D0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.063 I/bt_a2dp_hw(25269): adev_open:  adev_open in A2dp_hw module
05-12 13:35:21.063 I/AudioFlinger(25269): loadHwModule() Loaded a2dp audio interface, handle 18
05-12 13:35:21.063 D/vndksupport(25269): Loading /vendor/lib/hw/audio.usb.default.so from current namespace instead of sphal namespace.
05-12 13:35:21.065 I/DiracAPI(25269): Dirac_create: DiracObj (F0A75DB0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.066 I/DiracAPI(25269): (F05F97D0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.066 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.066 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.066 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.066 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.066 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.067 I/DiracAPI(25269): (F0A75DB0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.067 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.067 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.067 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.067 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.067 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.075 I/DiracAPI(25269): (F05F1A00): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.075 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.075 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.075 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.075 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.075 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.077 I/DiracAPI(25269): (F0A26C20): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.077 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.077 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.077 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.077 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.077 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.078 I/DiracAPI(25269): Dirac_create: DiracObj (EFF23D70) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.083 I/DiracAPI(25269): Dirac_create: DiracObj (EFEAA400) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.085 I/DiracAPI(25269): (EFF23D70): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.085 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.085 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.085 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.085 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.085 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.087 I/DiracAPI(25269): (EFEAA400): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.087 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.087 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.087 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.087 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.087 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.089 I/AudioFlinger(25269): loadHwModule() Loaded usb audio interface, handle 26
05-12 13:35:21.089 D/vndksupport(25269): Loading /vendor/lib/hw/audio.r_submix.default.so from current namespace instead of sphal namespace.
05-12 13:35:21.105 I/DiracAPI(25269): Dirac_create: DiracObj (EFF49BB0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.105 I/DiracAPI(25269): Dirac_create: DiracObj (EFEB4240) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.111 I/DiracAPI(25269): (EFF49BB0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.111 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.111 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.111 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.111 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.111 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.112 V/NewAvrcpMediaPlayerWrapper(25021): onMetadataChanged(): com.netease.cloudmusic : { mediaId="currsong" title="world.execute (me) ;" artist="Mili" album="" duration=211957 trackPosition=1/1 }
05-12 13:35:21.115 I/DiracAPI(25269): (EFEB4240): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.115 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.115 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.115 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.115 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.115 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.126 V/NewAvrcpMediaPlayerWrapper(25021): trySendMediaUpdate(): Metadata has been updated for com.netease.cloudmusic
05-12 13:35:21.126 D/NewAvrcpMediaPlayerList(25021): sendMediaUpdate
05-12 13:35:21.126 I/NewAvrcpMediaPlayerList(25021): sendMediaUpdate: Creating a one item queue for a player with no queue
05-12 13:35:21.126 D/NewAvrcpTargetService(25021): onMediaUpdated: track_changed=false state=true queue=false
05-12 13:35:21.126 D/NewAvrcpNativeInterface(25021): sendMediaUpdate: metadata=false playStatus=true queue=false
05-12 13:35:21.126 D/NewAvrcpTargetJni(25021): sendMediaUpdateNative
05-12 13:35:21.126 I/bt_stack(25021): [INFO:avrcp_service.cc(342)] virtual void bluetooth::avrcp::AvrcpService::SendMediaUpdate(bool, bool, bool) track_changed=0 :  play_state=1 :  queue=0
05-12 13:35:21.127 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:21.127 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:21.127 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:21.131 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:21.131 I/bt_stack(25021): [INFO:device.cc(409)] c4:67:b5:39:cc:ea : PlaybackStatusNotificationResponse: Not sending notification due to no state update c4:67:b5:39:cc:ea
05-12 13:35:21.131 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:21.136 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:21.137 I/r_submix(25269): adev_open(name=audio_hw_if)
05-12 13:35:21.138 I/r_submix(25269): adev_init_check()
05-12 13:35:21.138 W/DeviceHAL(25269): Error from HAL Device in function set_master_mute: Function not implemented
05-12 13:35:21.138 I/DiracAPI(25269): Dirac_create: DiracObj (EFD279F0) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.138 I/AudioFlinger(25269): loadHwModule() Loaded r_submix audio interface, handle 34
05-12 13:35:21.138 I/DiracAPI(25269): (EFD279F0): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.138 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.138 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.138 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.138 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.138 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.138 D/r_submix(25269): adev_open_input_stream(addr=0)
05-12 13:35:21.139 D/r_submix(25269): submix_audio_device_create_pipe_l(addr=0, idx=9)
05-12 13:35:21.139 D/r_submix(25269):   now using address 0 for route 9
05-12 13:35:21.147 I/AudioFlinger(25269): AudioFlinger's thread 0xefc03900 tid=25306 ready to run
05-12 13:35:21.147 I/DiracAPI(25269): Dirac_create: DiracObj (EFEFF210) created with conf: 'USECASE_EXTERNAL_HEADSET'
05-12 13:35:21.147 D/r_submix(25269): adev_close_input_stream()
05-12 13:35:21.147 D/r_submix(25269): submix_audio_device_release_pipe_l(idx=9) addr=0
05-12 13:35:21.149 D/r_submix(25269): submix_audio_device_destroy_pipe_l(): pipe destroyed
05-12 13:35:21.149 I/DiracAPI(25269): (EFEFF210): Prepared with conf: 'USECASE_EXTERNAL_HEADSET' 
05-12 13:35:21.149 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.149 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.149 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.149 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.149 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.150 D/AudioPolicyManagerCustom(25269): USE_XML_AUDIO_POLICY_CONF is TRUE
05-12 13:35:21.150 E/EffectsConfig(25269): Could not parse effect configuration in any of the default locations.
05-12 13:35:21.150 W/AudioPolicyEffects(25269): Failed to load XML effect configuration, fallback to .conf
05-12 13:35:21.153 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:21.153 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:21.153 D/vndksupport(25269): Loading /vendor/lib/hw/android.hardware.soundtrigger@2.0-impl.so from current namespace instead of sphal namespace.
05-12 13:35:21.157 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:21.172 E/SoundTriggerHalImpl(25269): couldn't load sound trigger module sound_trigger.primary (No such file or directory)
05-12 13:35:21.173 I/SoundTriggerHalHidl(25269): getProperties res implementor 
05-12 13:35:21.174 I/SoundTriggerHalHidl(25269): getProperties ret -19
05-12 13:35:21.174 E/SoundTriggerHwService(25269): could not read implementation properties
05-12 13:35:21.181 I/DiracAPI(25269): Dirac_create: DiracObj (EFD662C0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.183 I/DiracAPI(25269): (EFD662C0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.183 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.183 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.183 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.183 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.183 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.195 I/DiracAPI(25269): Dirac_create: DiracObj (EFE96A90) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.197 I/DiracAPI(25269): (EFE96A90): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.197 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.197 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.197 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.197 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.197 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.202 I/DiracAPI(25269): Dirac_create: DiracObj (EF9A6E60) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.203 I/DiracAPI(25269): (EF9A6E60): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.203 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.203 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.203 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.203 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.203 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.222 I/DiracAPI(25269): Dirac_create: DiracObj (EF8AA5F0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.223 I/DiracAPI(25269): Dirac_create: DiracObj (EF7EDA00) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.223 I/DiracAPI(25269): (EF8AA5F0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.223 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.223 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.223 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.223 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.223 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.224 I/DiracAPI(25269): (EF7EDA00): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.224 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.224 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.224 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.224 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.224 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.242 I/DiracAPI(25269): Dirac_create: DiracObj (EF562190) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.242 I/DiracAPI(25269): Dirac_create: DiracObj (EF5975A0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.243 I/DiracAPI(25269): (EF562190): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.243 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.243 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.243 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.243 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.243 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.243 I/DiracAPI(25269): (EF5975A0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.243 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.243 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.243 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.243 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.243 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.261 I/DiracAPI(25269): Dirac_create: DiracObj (EF475D30) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.261 I/DiracAPI(25269): Dirac_create: DiracObj (EF2D0140) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.263 I/DiracAPI(25269): (EF2D0140): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.263 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.263 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.263 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.263 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.263 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.263 I/DiracAPI(25269): (EF475D30): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.263 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.263 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.263 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.263 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.263 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.271 D/AudioPolicyManagerCustom(25269): setDeviceConnectionStateInt() device: 0x10, state 1, address C4:67:B5:39:CC:EA name Libratone Q ADAPT On Ear
05-12 13:35:21.272 D/audio_hw_primary(25269): adev_set_parameters: enter: C4:67:B5:39:CC:EA=;connect=16
05-12 13:35:21.272 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:21.273 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x10, SamplingRate 48000, Format 0x000001, Channels 0x3, flags 0x8
05-12 13:35:21.273 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(48000) channel_mask(0x3) devices(0x10) flags(0x8)        stream_handle(0xf2c35f00)
05-12 13:35:21.273 E/audio_hw_primary(25269): adev_open_output_stream: Primary output is already opened
05-12 13:35:21.273 D/audio_hw_primary(25269): adev_open_output_stream: exit: ret -17
05-12 13:35:21.273 W/DeviceHAL(25269): Error from HAL Device in function open_output_stream: File exists
05-12 13:35:21.273 I/AudioHwDevice(25269): openOutputStream(), HAL returned sampleRate 48000, Format 0x1, channelMask 0x3, status -61
05-12 13:35:21.273 W/APM_AudioPolicyManager(25269): checkOutputsForDevice() could not open output for device 10
05-12 13:35:21.273 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x10, SamplingRate 8000, Format 0x000006, Channels 0x1, flags 0x2001
05-12 13:35:21.273 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(8000) channel_mask(0x1) devices(0x10) flags(0x2001)        stream_handle(0xf2c35f00)
05-12 13:35:21.273 E/voice_extn(25269): voice_extn_check_and_set_incall_music_usecase: Invalid session id 0
05-12 13:35:21.273 E/audio_hw_primary(25269): adev_open_output_stream: Incall music delivery usecase cannot be set error:-22
05-12 13:35:21.273 D/audio_hw_primary(25269): adev_open_output_stream: exit: ret -22
05-12 13:35:21.273 W/DeviceHAL(25269): Error from HAL Device in function open_output_stream: Invalid argument
05-12 13:35:21.274 I/AudioHwDevice(25269): openOutputStream(), HAL returned sampleRate 8000, Format 0x6, channelMask 0x1, status -22
05-12 13:35:21.274 W/APM_AudioPolicyManager(25269): checkOutputsForDevice() could not open output for device 10
05-12 13:35:21.274 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x10, SamplingRate 8000, Format 0x1000000, Channels 0x1, flags 0x31
05-12 13:35:21.274 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(8000) channel_mask(0x1) devices(0x10) flags(0x31)        stream_handle(0xf2c35f00)
05-12 13:35:21.274 E/audio_hw_primary(25269): adev_open_output_stream: Unsupported Offload information
05-12 13:35:21.274 D/audio_hw_primary(25269): adev_open_output_stream: exit: ret -22
05-12 13:35:21.274 W/DeviceHAL(25269): Error from HAL Device in function open_output_stream: Invalid argument
05-12 13:35:21.274 I/AudioHwDevice(25269): openOutputStream(), HAL returned sampleRate 8000, Format 0x1000000, channelMask 0x1, status -22
05-12 13:35:21.274 W/APM_AudioPolicyManager(25269): checkOutputsForDevice() could not open output for device 10
05-12 13:35:21.274 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 10 Device 0x10, SamplingRate 8000, Format 0x2000000, Channels 0x1, flags 0x8001
05-12 13:35:21.274 D/audio_hw_primary(25269): adev_open_output_stream: enter: sample_rate(8000) channel_mask(0x1) devices(0x10) flags(0x8001)        stream_handle(0xf2c35f00)
05-12 13:35:21.274 E/audio_hw_primary(25269): adev_open_output_stream: Primary output is already opened
05-12 13:35:21.274 D/audio_hw_primary(25269): adev_open_output_stream: exit: ret -17
05-12 13:35:21.274 W/DeviceHAL(25269): Error from HAL Device in function open_output_stream: File exists
05-12 13:35:21.274 I/AudioHwDevice(25269): openOutputStream(), HAL returned sampleRate 8000, Format 0x2000000, channelMask 0x1, status -61
05-12 13:35:21.274 E/AudioHwDevice(25269): ERROR - openOutputStream(), SPDIFEncoder does not support format 0x02000000
05-12 13:35:21.274 W/APM_AudioPolicyManager(25269): checkOutputsForDevice() could not open output for device 10
05-12 13:35:21.275 D/audio_hw_primary(25269): out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=0, device: 2
05-12 13:35:21.275 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:21.278 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.278 D/audio_hw_primary(25269): out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=0, device: 2
05-12 13:35:21.280 D/audio_hw_primary(25269): out_set_parameters: enter: usecase(36: afe-proxy-playback) kvpairs: routing=0, device: 65536
05-12 13:35:21.281 I/DiracAPI(25269): Dirac_create: DiracObj (EF1ECD20) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.281 I/DiracAPI(25269): Dirac_create: DiracObj (EF04A8D0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.282 I/DiracAPI(25269): (EF1ECD20): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.282 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.282 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.282 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.282 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.282 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.282 D/AudioPolicyManagerCustom(25269): setDeviceConnectionStateInt() device: 0x80, state 1, address C4:67:B5:39:CC:EA name Libratone Q ADAPT On Ear
05-12 13:35:21.282 I/DiracAPI(25269): (EF04A8D0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.282 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.282 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.282 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.282 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.282 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.283 D/audio_hw_primary(25269): adev_set_parameters: enter: C4:67:B5:39:CC:EA=;connect=128
05-12 13:35:21.283 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:21.284 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 18 Device 0x80, SamplingRate 0, Format 00000000, Channels 0, flags 0
05-12 13:35:21.284 I/bt_a2dp_hw(25269): adev_open_output_stream: opening output
05-12 13:35:21.284 I/bt_a2dp_hw(25269): a2dp_command: starting up or recovering from previous error: command=A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.284 I/bt_a2dp_hw(25269): skt_connect: connect to /data/misc/bluedroid/.a2dp_ctrl (sz 256)
05-12 13:35:21.284 I/bt_a2dp_hw(25269): skt_connect: connected to stack fd = 35
05-12 13:35:21.284 W/bt_btif (25021): btif_a2dp_ctrl_cb: A2DP-CTRL-CHANNEL EVENT UIPC_OPEN_EVT
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_CHECK_READY
05-12 13:35:21.285 I/btif_av (25021): btif_av_stream_ready: Peer c4:67:b5:39:cc:ea : state=2, flags=0x0(None)
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_CHECK_READY, status 0 ##
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_CHECK_READY DONE
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.285 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=true): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.285 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_SET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.285 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_SET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.286 I/bt_btif_a2dp_source(25021): btif_a2dp_source_feeding_update_req: state=STATE_RUNNING
05-12 13:35:21.286 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_SET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.286 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_feeding_update_event: state=STATE_RUNNING
05-12 13:35:21.286 I/bt_a2dp_hw(25269): a2dp_write_output_audio_config: sent output codec config: sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.286 D/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_encoder_update: sample_rate=48000 bits_per_sample=16 channel_count=2
05-12 13:35:21.286 D/a2dp_vendor_aptx_encoder(25021): aptx_init_framing_params: sleep_time_ns = 14000000
05-12 13:35:21.286 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.286 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.286 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.286 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=true): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.286 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.286 I/bt_a2dp_hw(25269): adev_open_output_stream: Output stream config: format=0x1 sample_rate=48000 channel_mask=0x3 buffer_sz=7680
05-12 13:35:21.301 I/DiracAPI(25269): Dirac_create: DiracObj (EEBB1940) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.302 I/DiracAPI(25269): Dirac_create: DiracObj (EEB0F4D0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.302 I/DiracAPI(25269): (EEBB1940): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.302 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.302 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.302 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.302 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.302 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.303 I/DiracAPI(25269): (EEB0F4D0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.303 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.303 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.303 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.303 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.303 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.320 I/DiracAPI(25269): Dirac_create: DiracObj (EEAC64E0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.321 I/DiracAPI(25269): (EEAC64E0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.321 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.321 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.321 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.321 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.321 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.321 I/DiracAPI(25269): Dirac_create: DiracObj (EEA30070) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.323 I/DiracAPI(25269): (EEA30070): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.323 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.323 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.323 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.323 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.323 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.338 I/DiracAPI(25269): Dirac_create: DiracObj (EE697080) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.340 I/DiracAPI(25269): (EE697080): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.340 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.340 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.340 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.340 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.340 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.340 I/DiracAPI(25269): Dirac_create: DiracObj (EE604C10) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.342 I/DiracAPI(25269): (EE604C10): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.342 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.342 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.342 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.342 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.342 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.358 I/DiracAPI(25269): Dirac_create: DiracObj (EE5B8C20) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.359 I/DiracAPI(25269): (EE5B8C20): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.359 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.359 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.359 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.359 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.359 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.360 I/DiracAPI(25269): Dirac_create: DiracObj (EE51D7B0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.361 I/DiracAPI(25269): (EE51D7B0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.361 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.361 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.361 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.361 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.361 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.377 I/DiracAPI(25269): Dirac_create: DiracObj (EE1847C0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.378 I/DiracAPI(25269): (EE1847C0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.378 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.378 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.378 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.378 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.378 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.379 I/DiracAPI(25269): Dirac_create: DiracObj (EE25E350) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.380 I/DiracAPI(25269): (EE25E350): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.380 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.380 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.380 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.380 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.380 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.396 I/DiracAPI(25269): Dirac_create: DiracObj (EDFB6360) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.397 I/DiracAPI(25269): (EDFB6360): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.397 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.397 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.397 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.397 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.397 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.398 I/DiracAPI(25269): Dirac_create: DiracObj (EDF1BEF0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.399 I/DiracAPI(25269): (EDF1BEF0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.399 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.399 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.399 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.399 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.399 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.415 I/DiracAPI(25269): Dirac_create: DiracObj (EDEDAF00) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.416 I/DiracAPI(25269): (EDEDAF00): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.416 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.416 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.416 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.416 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.416 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.417 I/DiracAPI(25269): Dirac_create: DiracObj (EDE49A90) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.419 I/DiracAPI(25269): (EDE49A90): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.419 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.419 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.419 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.419 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.419 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.434 I/DiracAPI(25269): Dirac_create: DiracObj (EDB90AA0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.435 I/DiracAPI(25269): (EDB90AA0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.435 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.435 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.435 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.435 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.435 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.436 I/DiracAPI(25269): Dirac_create: DiracObj (EDC75630) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.438 I/DiracAPI(25269): (EDC75630): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.438 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.438 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.438 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.438 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.438 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.453 I/DiracAPI(25269): Dirac_create: DiracObj (ED9C3640) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.454 I/DiracAPI(25269): (ED9C3640): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.454 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.454 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.454 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.454 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.454 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.456 I/DiracAPI(25269): Dirac_create: DiracObj (ED9281D0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.457 I/DiracAPI(25269): (ED9281D0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.457 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.457 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.457 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.457 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.457 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.472 I/DiracAPI(25269): Dirac_create: DiracObj (ED7171E0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.474 I/DiracAPI(25269): (ED7171E0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.474 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.474 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.474 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.474 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.474 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.475 I/DiracAPI(25269): Dirac_create: DiracObj (ED663D70) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.476 I/DiracAPI(25269): (ED663D70): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.476 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.476 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.476 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.476 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.476 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.491 I/DiracAPI(25269): Dirac_create: DiracObj (ED3CBD80) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.493 I/DiracAPI(25269): (ED3CBD80): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.493 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.493 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.493 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.493 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.493 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.494 I/DiracAPI(25269): Dirac_create: DiracObj (ED419910) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.495 I/DiracAPI(25269): (ED419910): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.495 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.495 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.495 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.495 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.495 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.510 I/DiracAPI(25269): Dirac_create: DiracObj (ED2F2920) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.512 I/DiracAPI(25269): (ED2F2920): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.512 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.512 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.512 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.512 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.512 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.513 I/DiracAPI(25269): Dirac_create: DiracObj (ED1574B0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.514 I/DiracAPI(25269): (ED1574B0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.514 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.514 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.514 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.514 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.514 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.530 I/DiracAPI(25269): Dirac_create: DiracObj (ECEB14C0) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.531 I/DiracAPI(25269): (ECEB14C0): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.531 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.531 I/DiracAPI(25269):  samplerate: 44100 
05-12 13:35:21.531 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.531 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.531 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.532 I/DiracAPI(25269): Dirac_create: DiracObj (ECE0B050) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.533 I/DiracAPI(25269): (ECE0B050): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.533 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.533 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.533 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.533 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.533 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.537 I/AudioFlinger(25269): HAL output buffer size 960 frames, normal sink buffer size 960 frames
05-12 13:35:21.538 I/AudioFlinger(25269): AudioFlinger's thread 0xecc83840 tid=25309 ready to run
05-12 13:35:21.538 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.538 I/bt_a2dp_hw(25269): suspend_audio_datapath: state 3
05-12 13:35:21.538 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_SUSPEND
05-12 13:35:21.538 I/btif_av (25021): btif_av_stream_started_ready: Peer c4:67:b5:39:cc:ea : state=2 flags=0x0(None) ready=0
05-12 13:35:21.539 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_SUSPEND, status 0 ##
05-12 13:35:21.539 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_SUSPEND DONE
05-12 13:35:21.542 I/bt_a2dp_hw(25269): skt_disconnect: fd -1
05-12 13:35:21.542 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.542 I/bt_a2dp_hw(25269): out_set_parameters: state 5 kvpairs a2dp_sink_address=C4:67:B5:39:CC:EA
05-12 13:35:21.543 I/hash_map_utils(25269): key: 'a2dp_sink_address' value: 'C4:67:B5:39:CC:EA'
05-12 13:35:21.544 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.544 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.544 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.544 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=false): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.544 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.544 I/bt_a2dp_hw(25269): out_get_parameters: get parameters result = sup_formats=AUDIO_FORMAT_PCM_16_BIT;
05-12 13:35:21.545 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.545 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.545 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.545 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=false): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.545 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.545 I/bt_a2dp_hw(25269): out_get_parameters: get parameters result = sup_sampling_rates=44100|48000;
05-12 13:35:21.545 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.546 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.546 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.546 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=false): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.546 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.546 I/bt_a2dp_hw(25269): out_get_parameters: get parameters result = sup_channels=AUDIO_CHANNEL_OUT_STEREO;
05-12 13:35:21.547 I/bt_a2dp_hw(25269): out_set_parameters: state 5 kvpairs closing=true
05-12 13:35:21.547 I/hash_map_utils(25269): key: 'closing' value: 'true'
05-12 13:35:21.548 I/bt_a2dp_hw(25269): out_set_parameters: state 2 kvpairs exiting=1
05-12 13:35:21.548 I/hash_map_utils(25269): key: 'exiting' value: '1'
05-12 13:35:21.548 I/bt_a2dp_hw(25269): adev_close_output_stream: adev_close_output_stream: state 2
05-12 13:35:21.549 I/bt_a2dp_hw(25269): adev_close_output_stream: closing output (state 2)
05-12 13:35:21.549 I/bt_a2dp_hw(25269): stop_audio_datapath: state 2
05-12 13:35:21.549 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_STOP
05-12 13:35:21.549 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_STOP, status 0 ##
05-12 13:35:21.549 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_STOP DONE
05-12 13:35:21.549 I/bt_a2dp_hw(25269): skt_disconnect: fd -1
05-12 13:35:21.549 I/bt_a2dp_hw(25269): skt_disconnect: fd 35
05-12 13:35:21.549 W/bt_btif (25021): poll : channel detached remotely
05-12 13:35:21.549 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: CTRL CH DETACHED
05-12 13:35:21.549 W/bt_btif (25021): btif_a2dp_ctrl_cb: A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
05-12 13:35:21.550 I/AudioFlinger(25269): openOutput() this 0xf5abe000, module 18 Device 0x80, SamplingRate 48000, Format 0x000001, Channels 0x3, flags 0
05-12 13:35:21.550 I/bt_a2dp_hw(25269): adev_open_output_stream: opening output
05-12 13:35:21.550 I/bt_a2dp_hw(25269): a2dp_command: starting up or recovering from previous error: command=A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.550 I/bt_a2dp_hw(25269): skt_connect: connect to /data/misc/bluedroid/.a2dp_ctrl (sz 256)
05-12 13:35:21.551 W/bt_btif (25021): btif_a2dp_ctrl_cb: A2DP-CTRL-CHANNEL EVENT UIPC_OPEN_EVT
05-12 13:35:21.551 I/bt_a2dp_hw(25269): skt_connect: connected to stack fd = 35
05-12 13:35:21.551 I/DiracAPI(25269): Dirac_create: DiracObj (ECD39C60) created with conf: 'USECASE_INTERNAL_POWERSOUND'
05-12 13:35:21.552 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_CHECK_READY
05-12 13:35:21.552 I/btif_av (25021): btif_av_stream_ready: Peer c4:67:b5:39:cc:ea : state=2, flags=0x0(None)
05-12 13:35:21.552 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_CHECK_READY, status 0 ##
05-12 13:35:21.552 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_CHECK_READY DONE
05-12 13:35:21.552 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.552 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.552 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.552 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=true): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.552 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.553 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_SET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.553 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_SET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.553 I/DiracAPI(25269): (ECD39C60): Prepared with conf: 'USECASE_INTERNAL_POWERSOUND' 
05-12 13:35:21.553 I/DiracAPI(25269):  preset: 'default' 
05-12 13:35:21.553 I/DiracAPI(25269):  samplerate: 48000 
05-12 13:35:21.553 I/DiracAPI(25269):  nChannelsIn: 2 
05-12 13:35:21.553 I/DiracAPI(25269):  maxFrames: 2000 
05-12 13:35:21.553 I/DiracAPI(25269):  inFmt/outFmt: 1/1
05-12 13:35:21.553 I/bt_btif_a2dp_source(25021): btif_a2dp_source_feeding_update_req: state=STATE_RUNNING
05-12 13:35:21.553 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_SET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.553 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_feeding_update_event: state=STATE_RUNNING
05-12 13:35:21.553 I/bt_a2dp_hw(25269): a2dp_write_output_audio_config: sent output codec config: sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.553 D/a2dp_vendor_aptx_encoder(25021): a2dp_vendor_aptx_encoder_update: sample_rate=48000 bits_per_sample=16 channel_count=2
05-12 13:35:21.554 D/a2dp_vendor_aptx_encoder(25021): aptx_init_framing_params: sleep_time_ns = 14000000
05-12 13:35:21.554 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG
05-12 13:35:21.554 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG, status 0 ##
05-12 13:35:21.554 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_GET_OUTPUT_AUDIO_CONFIG DONE
05-12 13:35:21.554 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec config (update_stream_config=true): sample_rate=0x2 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.554 I/bt_a2dp_hw(25269): a2dp_read_output_audio_config: got output codec capability: sample_rate=0x3 bits_per_sample=0x1 channel_mode=0x2
05-12 13:35:21.554 I/bt_a2dp_hw(25269): adev_open_output_stream: Output stream config: format=0x1 sample_rate=48000 channel_mask=0x3 buffer_sz=7680
05-12 13:35:21.804 I/AudioFlinger(25269): HAL output buffer size 960 frames, normal sink buffer size 960 frames
05-12 13:35:21.805 I/AudioFlinger(25269): AudioFlinger's thread 0xeca83940 tid=25310 ready to run
05-12 13:35:21.805 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.805 I/bt_a2dp_hw(25269): suspend_audio_datapath: state 3
05-12 13:35:21.806 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_SUSPEND
05-12 13:35:21.806 I/btif_av (25021): btif_av_stream_started_ready: Peer c4:67:b5:39:cc:ea : state=2 flags=0x0(None) ready=0
05-12 13:35:21.806 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_SUSPEND, status 0 ##
05-12 13:35:21.806 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_SUSPEND DONE
05-12 13:35:21.807 I/bt_a2dp_hw(25269): skt_disconnect: fd -1
05-12 13:35:21.808 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.813 W/AudioFlinger(25269): moveEffectChain_l() effect chain for session 0 not on source thread 0xf2103ec0
05-12 13:35:21.814 I/AudioFlinger(25269): HAL output buffer size 960 frames, normal sink buffer size 960 frames
05-12 13:35:21.815 I/AudioFlinger(25269): AudioFlinger's thread 0xeca03d40 tid=25311 ready to run
05-12 13:35:21.815 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.815 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.826 D/AudioPolicyManagerCustom(25269): setDeviceConnectionStateInt() device: 0x80000008, state 1, address C4:67:B5:39:CC:EA name Libratone Q ADAPT On Ear
05-12 13:35:21.827 D/audio_hw_primary(25269): adev_set_parameters: enter: C4:67:B5:39:CC:EA=;connect=-2147483640
05-12 13:35:21.827 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:21.827 I/bt_a2dp_hw(25269): adev_set_parameters: state 5
05-12 13:35:21.828 I/bt_a2dp_hw(25269): out_set_parameters: state 5 kvpairs C4:67:B5:39:CC:EA=;connect=-2147483640
05-12 13:35:21.828 I/hash_map_utils(25269): key: 'connect' value: '-2147483640'
05-12 13:35:21.828 I/hash_map_utils(25269): key: 'C4:67:B5:39:CC:EA' value: ''
05-12 13:35:21.829 D/audio_hw_primary(25269): adev_open_input_stream: enter: sample_rate(48000) channel_mask(0xc) devices(0x80000008)        stream_handle(0xf5ac3e60) io_handle(46) source(1)
05-12 13:35:21.830 I/AudioFlinger(25269): AudioFlinger's thread 0xec883640 tid=25312 ready to run
05-12 13:35:21.830 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.830 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.830 D/audio_hw_primary(25269): in_set_parameters: enter: kvpairs=C4:67:B5:39:CC:EA=
05-12 13:35:21.830 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.831 W/AudioFlinger(25269): no wake lock to update, system not ready yet
05-12 13:35:21.831 D/audio_hw_primary(25269): adev_close_input_stream: enter:stream_handle(0xf5ac3e60)
05-12 13:35:21.831 D/audio_hw_primary(25269): in_standby: enter: stream (0xf5ac3e60) usecase(15: audio-record)
05-12 13:35:21.833 D/AudioPolicyManagerCustom(25269): setPhoneState() state 0
05-12 13:35:21.833 W/APM::AudioPolicyEngine(25269): setPhoneState() setting same state 0
05-12 13:35:21.833 W/AudioPolicyManagerCustom(25269): setPhoneState() invalid or same state 0
05-12 13:35:21.834 D/PermissionCache(25269): checking android.permission.MODIFY_AUDIO_ROUTING for uid=1000 => granted (538 us)
05-12 13:35:21.834 D/AudioPolicyManagerCustom(25269): setForceUse() usage 0, config 0, mPhoneState 0
05-12 13:35:21.834 D/AudioPolicyManagerCustom(25269): setForceUse() usage 2, config 0, mPhoneState 0
05-12 13:35:21.835 D/BluetoothActiveDeviceManager(25021): onAudioDevicesAdded
05-12 13:35:21.835 D/BluetoothActiveDeviceManager(25021): Audio device added: Libratone Q ADAPT On Ear type: 7
05-12 13:35:21.835 D/BluetoothActiveDeviceManager(25021): Audio device added: Libratone Q ADAPT On Ear type: 8
05-12 13:35:21.835 D/BluetoothActiveDeviceManager(25021): Audio device added: Libratone Q ADAPT On Ear type: 7
05-12 13:35:21.835 D/AudioPolicyManagerCustom(25269): setForceUse() usage 4, config 0, mPhoneState 0
05-12 13:35:21.835 D/NewAvrcpVolumeManager(25021): onAudioDevicesAdded: size: 3
05-12 13:35:21.835 D/NewAvrcpVolumeManager(25021): onAudioDevicesAdded: address=C4:67:B5:39:CC:EA
05-12 13:35:21.835 D/NewAvrcpVolumeManager(25021): onAudioDevicesAdded: address=C4:67:B5:39:CC:EA
05-12 13:35:21.836 D/NewAvrcpVolumeManager(25021): switchVolumeDevice: Set Absolute volume support to true
05-12 13:35:21.836 D/NewAvrcpVolumeManager(25021): getVolume: Returning volume 4
05-12 13:35:21.836 D/NewAvrcpVolumeManager(25021): switchVolumeDevice: savedVolume=4
05-12 13:35:21.836 I/NewAvrcpVolumeManager(25021): switchVolumeDevice: Updating device volume: avrcpVolume=33
05-12 13:35:21.836 D/NewAvrcpNativeInterface(25021): sendVolumeChanged: volume=33
05-12 13:35:21.836 D/NewAvrcpTargetJni(25021): sendVolumeChangedNative
05-12 13:35:21.840 I/Telecom (  985): WiredHeadsetManager: ACTION_HEADSET_PLUG event, plugged in: false, : WHC.oADR@AUs
05-12 13:35:21.841 D/AudioFx-AudioOutputChangeListener( 3220): onAudioOutputChanged id: 19 type: 8 name: Libratone Q ADAPT On Ear address: C4:67:B5:39:CC:EA [android.media.AudioDeviceInfo@32]
05-12 13:35:21.842 I/Telecom (  985): WiredHeadsetManager: ACTION_HEADSET_PLUG event, plugged in: false, : WHC.oADA@AUw
05-12 13:35:21.851 D/AudioPolicyManagerCustom(25269): setForceUse() usage 1, config 0, mPhoneState 0
05-12 13:35:21.851 D/AudioPolicyManagerCustom(25269): setForceUse() usage 3, config 8, mPhoneState 0
05-12 13:35:21.855 I/AudioFlinger(25269): systemReady
05-12 13:35:21.855 D/audio_hw_primary(25269): adev_set_parameters: enter: restarting=false
05-12 13:35:21.855 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:21.855 I/bt_a2dp_hw(25269): adev_set_parameters: state 5
05-12 13:35:21.855 I/bt_a2dp_hw(25269): out_set_parameters: state 5 kvpairs restarting=false
05-12 13:35:21.855 I/hash_map_utils(25269): key: 'restarting' value: 'false'
05-12 13:35:21.857 D/AudioPolicyManagerCustom(25269): setForceUse() usage 7, config 0, mPhoneState 0
05-12 13:35:21.857 D/AudioPolicyManagerCustom(25269): setForceUse() usage 6, config 0, mPhoneState 0
05-12 13:35:21.959 W/AudioFlinger(25269): createTrack_l(): mismatch between requested flags (00000008) and output flags (00000000)
05-12 13:35:21.959 D/AudioFlinger(25269): Client defaulted notificationFrames to 11025 for frameCount 33075
05-12 13:35:21.973 W/AshmemAllocator(  425): ashmem_create_region(7680) returning hidl_memory(0x775342c100, 7680)
05-12 13:35:21.990 W/AshmemAllocator(  425): ashmem_create_region(7680) returning hidl_memory(0x775342c100, 7680)
05-12 13:35:21.990 E/se.dirac.effect(25269): check_config: bad parameter: bufferProvider
05-12 13:35:21.991 W/EffectHAL(25269): Effect 0xecb47080 command SET_CONFIG returned status: Invalid argument
05-12 13:35:21.991 E/se.dirac.effect(25269): check_config: bad parameter: bufferProvider
05-12 13:35:21.991 W/EffectHAL(25269): Effect 0xecb47080 command SET_CONFIG returned status: Invalid argument
05-12 13:35:21.991 E/AudioFlinger::EffectModule(25269): configure failed -22 with int16_t (as well as float)
05-12 13:35:21.991 I/bt_a2dp_hw(25269): out_set_parameters: state 5 kvpairs a2dp_sink_address=C4:67:B5:39:CC:EA;routing=128
05-12 13:35:21.991 I/hash_map_utils(25269): key: 'routing' value: '128'
05-12 13:35:21.991 I/hash_map_utils(25269): key: 'a2dp_sink_address' value: 'C4:67:B5:39:CC:EA'
05-12 13:35:22.000 E/AudioFlinger(25269): no wake lock to update, but system ready!
05-12 13:35:22.001 D/CloudMusicNativePlayer(17846): AudioTrack(9): Played
05-12 13:35:22.001 D/CloudMusicNativePlayer(17846): PostNativeMsg: what:200, args:702, args2:0
05-12 13:35:22.001 I/bt_a2dp_hw(25269): start_audio_datapath: state 5
05-12 13:35:22.001 W/AudioTrack(17846): dead IAudioTrack, PCM, creating a new one from obtainBuffer()
05-12 13:35:22.001 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_START
05-12 13:35:22.001 I/btif_av (25021): btif_av_stream_ready: Peer c4:67:b5:39:cc:ea : state=2, flags=0x0(None)
05-12 13:35:22.002 I/btif_av (25021): btif_av_stream_start
05-12 13:35:22.002 W/bt_btif (25021): btif_a2dp_recv_ctrl_data: a2dp-ctrl-cmd : A2DP_CTRL_CMD_START DONE
05-12 13:35:22.002 I/btif_av (25021): virtual bool BtifAvStateMachine::StateOpened::ProcessEvent(uint32_t, void *): Peer c4:67:b5:39:cc:ea : event=BTIF_AV_START_STREAM_REQ_EVT(0x1b) flags=0x0(None)
05-12 13:35:22.002 I/bt_bta_av(25021): BTA_AvStart: handle=65
05-12 13:35:22.002 I/bt_bta_av(25021): bta_av_do_start: peer c4:67:b5:39:cc:ea sco_occupied:false role:0x0 started:false wait:0x0
05-12 13:35:22.002 W/bt_btif (25021): bta_dm_rm_cback:2, status:7
05-12 13:35:22.002 D/CloudMusicNativePlayer(17846): PostNativeMsg End: what:200, args:702, args2:0
05-12 13:35:22.002 I/bt_bta_av(25021): bta_av_do_start: peer c4:67:b5:39:cc:ea start requested: sco_occupied:false role:0x10 started:false wait:0x0
05-12 13:35:22.003 D/LocalPlayback(17846): >>>>onInfo MEDIA_INFO_BUFFERING_END:6
05-12 13:35:22.004 W/AudioFlinger(25269): createTrack_l(): mismatch between requested flags (00000008) and output flags (00000000)
05-12 13:35:22.004 D/AudioFlinger(25269): Client defaulted notificationFrames to 11025 for frameCount 33075
05-12 13:35:22.007 D/CloudMusicNativePlayer(17846): AudioTrack(9): reset base time_line(0)
05-12 13:35:22.023 I/bt_bta_av(25021): bta_av_start_ok: peer c4:67:b5:39:cc:ea handle:65 wait:0x0 role:0x10 local_tsep:0
05-12 13:35:22.023 I/bt_bta_av(25021): bta_av_link_role_ok: peer c4:67:b5:39:cc:ea hndl:0x41 role:1 conn_audio:0x1 bits:1 features:0x865b
05-12 13:35:22.023 W/bt_btif (25021): bta_dm_rm_cback:2, status:0
05-12 13:35:22.023 W/bt_btif (25021): bta_dm_rm_cback:2, status:7
05-12 13:35:22.023 I/btif_av (25021): virtual bool BtifAvStateMachine::StateOpened::ProcessEvent(uint32_t, void *): Peer c4:67:b5:39:cc:ea : event=BTA_AV_START_EVT(0x4) status=0 suspending=0 initiator=1 flags=0x4(PENDING_START)
05-12 13:35:22.023 I/bt_btif_a2dp(25021): btif_a2dp_on_started: ## ON A2DP STARTED ## peer c4:67:b5:39:cc:ea pending_start:true p_av_start:0x70a02d5ca8
05-12 13:35:22.023 I/bt_btif_a2dp(25021): btif_a2dp_on_started: peer c4:67:b5:39:cc:ea pending_start:true status:0 suspending:false initiator:true
05-12 13:35:22.023 W/bt_btif (25021): btif_a2dp_command_ack: ## a2dp ack : A2DP_CTRL_CMD_START, status 0 ##
05-12 13:35:22.023 I/btif_av (25021): btif_report_audio_state: peer_address=c4:67:b5:39:cc:ea state=2
05-12 13:35:22.023 I/bt_a2dp_hw(25269): skt_connect: connect to /data/misc/bluedroid/.a2dp_data (sz 7680)
05-12 13:35:22.023 I/bt_a2dp_hw(25269): skt_connect: connected to stack fd = 40
05-12 13:35:22.023 W/bt_btif (25021): btif_a2dp_data_cb: BTIF MEDIA (A2DP-DATA) EVENT UIPC_OPEN_EVT
05-12 13:35:22.024 I/bt_btif_a2dp_source(25021): btif_a2dp_source_start_audio_req: state=STATE_RUNNING
05-12 13:35:22.024 I/bt_btif_a2dp_source(25021): btif_a2dp_source_audio_tx_start_event: media_alarm is not running, streaming false state=STATE_RUNNING
05-12 13:35:22.024 D/a2dp_vendor_aptx_encoder(25021): aptx_init_framing_params: sleep_time_ns = 14000000
05-12 13:35:22.025 E/AudioFlinger(25269): no wake lock to update, but system ready!
05-12 13:35:22.027 I/BluetoothA2dpServiceJni(25021): bta2dp_audio_state_callback
05-12 13:35:22.028 D/A2dpNativeInterface(25021): onAudioStateChanged: A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:C4:67:B5:39:CC:EA, value1:STARTED}
05-12 13:35:22.029 D/A2dpStateMachine(25021): handleMessage: E msg.what=101
05-12 13:35:22.029 D/A2dpStateMachine(25021): processMsg: Connected
05-12 13:35:22.029 D/A2dpStateMachine(25021): Connected process message(C4:67:B5:39:CC:EA): STACK_EVENT
05-12 13:35:22.029 D/A2dpStateMachine(25021): Connected: stack event: A2dpStackEvent {type:EVENT_TYPE_AUDIO_STATE_CHANGED, device:C4:67:B5:39:CC:EA, value1:STARTED}
05-12 13:35:22.029 I/A2dpStateMachine(25021): Connected: started playing: C4:67:B5:39:CC:EA
05-12 13:35:22.029 D/A2dpStateMachine(25021): A2DP Playing state : device: C4:67:B5:39:CC:EA State:NOT_PLAYING->PLAYING
05-12 13:35:22.030 D/A2dpStateMachine(25021): handleMessage: X
05-12 13:35:22.033 V/NewAvrcpMediaPlayerWrapper(25021): onPlaybackStateChanged(): com.netease.cloudmusic : PlaybackState {state=3, position=20, buffered position=0, speed=1.0, updated=138196491, actions=822, custom actions=[], active item id=-1, error=null}
05-12 13:35:22.042 V/NewAvrcpMediaPlayerWrapper(25021): trySendMediaUpdate(): Metadata has been updated for com.netease.cloudmusic
05-12 13:35:22.042 D/NewAvrcpMediaPlayerList(25021): sendMediaUpdate
05-12 13:35:22.042 I/NewAvrcpMediaPlayerList(25021): sendMediaUpdate: Creating a one item queue for a player with no queue
05-12 13:35:22.042 D/NewAvrcpTargetService(25021): onMediaUpdated: track_changed=false state=true queue=false
05-12 13:35:22.042 D/NewAvrcpNativeInterface(25021): sendMediaUpdate: metadata=false playStatus=true queue=false
05-12 13:35:22.042 D/NewAvrcpTargetJni(25021): sendMediaUpdateNative
05-12 13:35:22.042 I/bt_stack(25021): [INFO:avrcp_service.cc(342)] virtual void bluetooth::avrcp::AvrcpService::SendMediaUpdate(bool, bool, bool) track_changed=0 :  play_state=1 :  queue=0
05-12 13:35:22.043 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:22.043 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:22.043 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:22.047 I/bt_stack(25021): [INFO:device.cc(409)] c4:67:b5:39:cc:ea : PlaybackStatusNotificationResponse: Not sending notification due to no state update c4:67:b5:39:cc:ea
05-12 13:35:22.047 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:22.047 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:22.051 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:22.064 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:22.064 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:22.069 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:22.263 E/AudioFlinger(25269): no wake lock to update, but system ready!
05-12 13:35:23.069 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:23.070 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:23.070 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:23.089 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:23.100 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:23.100 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:23.113 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:24.114 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:24.115 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:24.115 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:24.131 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:24.141 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:24.142 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:24.149 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:25.150 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:25.151 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:25.151 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:25.171 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:25.185 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:25.185 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:25.195 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:21.985 I/chatty  (  344): uid=1000(system) hwservicemanage identical 10 lines
05-12 13:35:21.987 I/snet_event_log(  344): [121035042,-1,]
05-12 13:35:25.229 I/auditd  (25313): type=1400 audit(0.0:9939): avc: denied { ioctl } for comm="sensors.qcom" path="/dev/sensors" dev="tmpfs" ino=10900 ioctlcmd=6403 scontext=u:r:init:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:25.229 I/sensors.qcom(25313): type=1400 audit(0.0:9939): avc: denied { ioctl } for path="/dev/sensors" dev="tmpfs" ino=10900 ioctlcmd=6403 scontext=u:r:init:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:25.570 I/MSM-irqbalance(  703): Decided to move IRQ271 from CPU1 to CPU2
05-12 13:35:26.195 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:26.199 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:26.200 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:26.221 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:26.231 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:26.231 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:26.236 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:26.365 I/auditd  ( 2900): type=1400 audit(0.0:9940): avc: denied { read } for comm="sensors.qcom" scontext=u:r:init:s0 tcontext=u:r:init:s0 tclass=socket permissive=1
05-12 13:35:26.365 I/sensors.qcom( 2900): type=1400 audit(0.0:9940): avc: denied { read } for scontext=u:r:init:s0 tcontext=u:r:init:s0 tclass=socket permissive=1
05-12 13:35:27.237 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:27.238 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:27.238 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:27.258 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:27.271 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:27.271 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:27.279 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:28.280 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:28.281 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:28.281 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:28.303 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:28.320 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:28.320 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:28.325 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:29.326 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:29.327 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:29.327 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:29.349 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:29.363 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:29.363 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:29.370 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:30.371 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:30.372 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:30.372 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:30.399 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:30.414 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:30.414 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:30.419 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:31.420 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:31.422 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:31.422 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:31.441 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:31.456 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:31.456 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:31.463 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:32.463 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:32.464 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:32.464 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:32.485 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:32.497 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:32.498 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:32.503 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:33.505 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:33.505 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:33.506 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:33.528 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:33.537 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:33.537 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:33.542 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:34.543 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:34.544 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:34.544 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:34.564 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:34.573 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:34.574 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:34.579 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:34.793 D/ImsManager( 2342): Connector: getImsService
05-12 13:35:34.796 I/ImsManager( 2342): Creating ImsService
05-12 13:35:34.803 W/MmTelFeatureConnection( 2342): create: binder is null! Slot Id: 0
05-12 13:35:34.804 E/ImsManager( 2342): Connector: Retrying getting ImsService...
05-12 13:35:34.805 D/ImsManager( 2342): Connector: getImsService
05-12 13:35:34.805 I/ImsManager( 2342): Creating ImsService
05-12 13:35:34.810 W/MmTelFeatureConnection( 2342): create: binder is null! Slot Id: 0
05-12 13:35:34.811 E/ImsManager( 2342): Connector: Retrying getting ImsService...
05-12 13:35:35.229 I/auditd  (25314): type=1400 audit(0.0:9941): avc: denied { write } for comm="sensors.qcom" scontext=u:r:init:s0 tcontext=u:r:init:s0 tclass=socket permissive=1
05-12 13:35:35.229 I/sensors.qcom(25314): type=1400 audit(0.0:9941): avc: denied { write } for scontext=u:r:init:s0 tcontext=u:r:init:s0 tclass=socket permissive=1
05-12 13:35:35.579 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:35.581 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:35.581 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:35.607 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:35.617 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:35.618 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:35.631 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:36.632 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:36.633 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:36.633 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:36.652 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:36.660 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:36.660 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:36.668 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:37.669 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:37.669 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:37.669 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:37.689 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:37.703 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:37.703 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:37.713 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:38.177 I/auditd  (  426): type=1400 audit(0.0:9942): avc: denied { read } for comm="healthd" name="present" dev="sysfs" ino=20166 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:38.177 I/healthd (  426): type=1400 audit(0.0:9942): avc: denied { read } for name="present" dev="sysfs" ino=20166 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:38.177 I/auditd  (  426): type=1400 audit(0.0:9943): avc: denied { open } for comm="healthd" path="/sys/devices/soc.0/qpnp-smbcharger-17/power_supply/battery/present" dev="sysfs" ino=20166 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:38.177 I/healthd (  426): type=1400 audit(0.0:9943): avc: denied { open } for path="/sys/devices/soc.0/qpnp-smbcharger-17/power_supply/battery/present" dev="sysfs" ino=20166 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:38.177 I/auditd  (  426): type=1400 audit(0.0:9944): avc: denied { getattr } for comm="healthd" path="/sys/devices/soc.0/qpnp-smbcharger-17/power_supply/battery/present" dev="sysfs" ino=20166 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:38.177 I/healthd (  426): type=1400 audit(0.0:9944): avc: denied { getattr } for path="/sys/devices/soc.0/qpnp-smbcharger-17/power_supply/battery/present" dev="sysfs" ino=20166 scontext=u:r:healthd:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:38.714 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:38.715 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:38.715 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:38.735 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:38.754 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:38.755 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:38.765 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:39.766 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:39.767 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:39.768 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:39.790 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:39.802 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:39.802 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:39.809 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:40.439 I/PowerManagerService(  985): Waking up from sleep (uid=1000 reason=android.policy:KEY)...
05-12 13:35:40.437 I/auditd  ( 1837): type=1400 audit(0.0:9945): avc: denied { call } for comm="InputReader" scontext=u:r:system_server:s0 tcontext=u:r:init:s0 tclass=binder permissive=1
05-12 13:35:40.437 I/InputReader( 1837): type=1400 audit(0.0:9945): avc: denied { call } for scontext=u:r:system_server:s0 tcontext=u:r:init:s0 tclass=binder permissive=1
05-12 13:35:40.442 W/UsageStatsService(  985): Event reported without a package name
05-12 13:35:40.446 E/LightsService(  985): Light requested not available on this device. 2
05-12 13:35:40.453 I/DisplayPowerController(  985): Blocking screen on until initial contents have been drawn.
05-12 13:35:40.470 I/screen_toggled(  985): 1
05-12 13:35:40.470 I/power_screen_broadcast_send(  985): 1
05-12 13:35:40.471 I/DisplayManagerService(  985): Display device changed state: "鍐呯疆灞忓箷", ON
05-12 13:35:40.471 D/SurfaceFlinger(  453): Set power mode=2, type=0 flinger=0x7e88455000
05-12 13:35:40.471 D/qdhwcomposer(  453): hwc_setPowerMode: Setting mode 2 on display: 0
05-12 13:35:40.484 D/audio_hw_primary(25269): adev_set_parameters: enter: screen_state=on
05-12 13:35:40.484 D/audio_hw_extn(25269): audio_extn_set_anc_parameters: anc_enabled:0
05-12 13:35:40.484 I/bt_a2dp_hw(25269): adev_set_parameters: state 1
05-12 13:35:40.484 I/bt_a2dp_hw(25269): out_set_parameters: state 1 kvpairs screen_state=on
05-12 13:35:40.484 I/hash_map_utils(25269): key: 'screen_state' value: 'on'
05-12 13:35:40.491 W/wificond(  514): Failed to get NL80211_ATTR_EXT_FEATURES
05-12 13:35:40.489 I/auditd  ( 2611): type=1400 audit(0.0:9946): avc: denied { ioctl } for comm="RenderThread" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=935 scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:40.489 I/RenderThread( 2611): type=1400 audit(0.0:9946): avc: denied { ioctl } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=935 scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:40.498 I/sysui_view_visibility(  985): [127,100]
05-12 13:35:40.498 I/sysui_multi_action(  985): [757,127,758,1]
05-12 13:35:40.498 I/sysui_histogram(  985): [note_load,3]
05-12 13:35:40.498 I/sysui_multi_action(  985): [757,804,799,note_load,801,3,802,1]
05-12 13:35:40.498 I/notification_panel_revealed(  985): 3
05-12 13:35:40.493 I/auditd  ( 2611): type=1400 audit(0.0:9947): avc: denied { read write } for comm="RenderThread" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:40.493 I/RenderThread( 2611): type=1400 audit(0.0:9947): avc: denied { read write } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:40.506 I/InputReader(  985): Reconfiguring input devices.  changes=0x00000004
05-12 13:35:40.507 I/DeviceStatusMonitor( 2029): DeviceStatusMonitor$1.onReceive():51 onReceive() : Action = android.intent.action.SCREEN_ON
05-12 13:35:40.508 I/DeviceStatusMonitor( 2029): DeviceStatusMonitor.updateCountryInfo():111 updateCountryInfo(), notifyAnyway = false
05-12 13:35:40.513 D/StatusBar( 2042): disable<e i a s b H R c s > disable2<q i n >
05-12 13:35:40.514 I/sysui_multi_action(  985): [757,128,758,1,793,451995,794,0,795,451995,796,26,798,1,806,android,857,DEVELOPER,858,2,947,0,1395,3,1500,451991]
05-12 13:35:40.514 I/sysui_histogram(  985): [note_freshness,451995]
05-12 13:35:40.514 I/sysui_multi_action(  985): [757,804,799,note_freshness,801,451995,802,1]
05-12 13:35:40.514 I/notification_visibility(  985): [-1|android|26|null|1000,1,451995,451995,0,1]
05-12 13:35:40.514 I/sysui_multi_action(  985): [757,128,758,1,793,282101,794,0,795,281452,796,1,798,0,806,com.netease.cloudmusic,857,miscellaneous,858,2,947,0,1395,3,1500,281452]
05-12 13:35:40.514 I/sysui_histogram(  985): [note_freshness,281452]
05-12 13:35:40.514 I/sysui_multi_action(  985): [757,804,799,note_freshness,801,281452,802,1]
05-12 13:35:40.514 I/notification_visibility(  985): [0|com.netease.cloudmusic|1|null|10168,1,282101,281452,0,0]
05-12 13:35:40.517 D/DCT     ( 2342): [0]screen on
05-12 13:35:40.518 D/DCT     ( 2342): [0]stopNetStatPoll
05-12 13:35:40.513 D/StatusBar( 2042): disable<e i a s b H R c s > disable2<q i n >
05-12 13:35:40.555 I/MSM-irqbalance(  703): Decided to move IRQ128 from CPU2 to CPU3
05-12 13:35:40.689 I/auditd  (  875): type=1400 audit(0.0:9948): avc: denied { read } for comm="hwcVsyncThread" path="/sys/devices/virtual/graphics/fb0/show_blank_event" dev="sysfs" ino=12153 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:40.694 I/qdhwcomposer(  453): handle_blank_event: dpy:0 panel power state: 1
05-12 13:35:40.689 I/hwcVsyncThread(  875): type=1400 audit(0.0:9948): avc: denied { read } for path="/sys/devices/virtual/graphics/fb0/show_blank_event" dev="sysfs" ino=12153 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:40.696 D/qdhwcomposer(  453): hwc_setPowerMode: Done setting mode 2 on display 0
05-12 13:35:40.697 D/SurfaceFlinger(  453): Finished set power mode=2, type=0
05-12 13:35:40.697 D/SurfaceControl(  985): Excessive delay in setPowerMode()
05-12 13:35:40.474 I/        (    0): synaptics tp on start
05-12 13:35:40.491 I/Wlan[I] (    0): dhd_set_suspend: Remove extra suspend setting
05-12 13:35:40.548 I/        (    0): synaptics_rmi4_resume
05-12 13:35:40.749 I/auditd  ( 1697): type=1400 audit(0.0:9949): avc: denied { write } for comm="light@2.0-servi" path="/sys/devices/soc.0/fd900000.qcom,mdss_mdp/qcom,mdss_fb_primary.182/leds/lcd-backlight/brightness" dev="sysfs" ino=12142 scontext=u:r:init:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:40.749 I/light@2.0-servi( 1697): type=1400 audit(0.0:9949): avc: denied { write } for path="/sys/devices/soc.0/fd900000.qcom,mdss_mdp/qcom,mdss_fb_primary.182/leds/lcd-backlight/brightness" dev="sysfs" ino=12142 scontext=u:r:init:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:40.492 I/chatty  (  514): uid=1010(wifi) /system/bin/wificond identical 1 line
05-12 13:35:40.496 W/wificond(  514): Failed to get NL80211_ATTR_EXT_FEATURES
05-12 13:35:40.753 I/DisplayPowerController(  985): Unblocked screen on after 301 ms
05-12 13:35:40.758 I/sysui_multi_action(  985): [757,198,758,1,759,0,1359,318]
05-12 13:35:40.758 I/power_screen_state(  985): [1,0,0,0,318]
05-12 13:35:40.758 W/PowerManagerService(  985): Screen on took 318 ms
05-12 13:35:40.804 I/libnfc_nci( 3238): [INFO:NativeNfcManager.cpp(1754)] nfcManager_doSetScreenState: state = 4 prevScreenState= 2, discovry_param = 1
05-12 13:35:40.809 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:40.809 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:40.809 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:40.813 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:40.860 I/NearbyDiscovery( 2385): FastPairHandler: Received action android.intent.action.SCREEN_ON [CONTEXT service_id=49 ]
05-12 13:35:40.861 D/BluetoothAdapter( 2385): isLeEnabled(): ON
05-12 13:35:40.864 I/bt_stack(25021): [INFO:gatt_api.cc(948)] GATT_Register bd52f3e4-e981-af64-eae2-8216852e8fe9
05-12 13:35:40.864 I/bt_stack(25021): [INFO:gatt_api.cc(968)] allocated gatt_if=5
05-12 13:35:40.865 D/BluetoothLeScanner( 2385): onScannerRegistered() - status=0 scannerId=5 mScannerId=0
05-12 13:35:40.874 I/NearbyDiscovery( 2385): FastPairScanner2: Starting LOW_LATENCY_SCANNING scan for 6 seconds [CONTEXT service_id=49 ]
05-12 13:35:40.886 I/power_screen_broadcast_done(  985): [1,415,1]
05-12 13:35:40.900 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:40.900 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:40.903 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:40.915 W/Notification(17846): Use of stream types is deprecated for operations other than volume control
05-12 13:35:40.915 W/Notification(17846): See the documentation of setSound() for what to use instead with android.media.AudioAttributes to qualify your playback use case
05-12 13:35:40.927 I/notification_enqueue(  985): [10168,17846,com.netease.cloudmusic,1,NULL,0,Notification(channel=null pri=2 contentView=com.netease.cloudmusic/0x109009a vibrate=null sound=null tick defaults=0x0 flags=0x40 color=0x00000000 category=transport actions=5 vis=PUBLIC),1]
05-12 13:35:41.162 W/Notification(17846): Use of stream types is deprecated for operations other than volume control
05-12 13:35:41.162 W/Notification(17846): See the documentation of setSound() for what to use instead with android.media.AudioAttributes to qualify your playback use case
05-12 13:35:41.180 I/notification_enqueue(  985): [10168,17846,com.netease.cloudmusic,1,NULL,0,Notification(channel=null pri=2 contentView=null vibrate=null sound=null tick defaults=0x0 flags=0x0 color=0x00000000 category=transport actions=5 vis=PUBLIC),1]
05-12 13:35:41.904 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:41.904 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:41.904 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:41.910 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:41.925 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:41.926 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:41.935 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:42.657 D/WificondControl(  985): Scan result ready event
05-12 13:35:42.687 D/PasspointManager(  985): No matches not found for simba-agv
05-12 13:35:42.687 D/PasspointManager(  985): Match not found for simba-agv
05-12 13:35:42.687 D/PasspointManager(  985): No matches not found for simba-agv
05-12 13:35:42.687 D/PasspointManager(  985): Match not found for simba-agv
05-12 13:35:42.935 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:42.936 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:42.937 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:42.947 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:42.963 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:42.963 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:42.967 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:43.967 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:43.968 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:43.968 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:43.986 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:44.000 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:44.000 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:44.008 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:44.869 I/auditd  (  701): type=1400 audit(0.0:9950): avc: denied { read } for comm="storaged" name="stat" dev="sysfs" ino=19141 scontext=u:r:storaged:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:44.869 I/storaged(  701): type=1400 audit(0.0:9950): avc: denied { read } for name="stat" dev="sysfs" ino=19141 scontext=u:r:storaged:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:45.009 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:45.012 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:45.012 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:45.031 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:45.049 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:45.049 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:45.058 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:45.578 I/MSM-irqbalance(  703): Decided to move IRQ276 from CPU2 to CPU3
05-12 13:35:45.577 I/auditd  (  703): type=1400 audit(0.0:9953): avc: denied { write } for comm="msm_irqbalance" name="def_timer_ms" dev="sysfs" ino=20317 scontext=u:r:init:s0 tcontext=u:object_r:sysfs_devices_system_cpu:s0 tclass=file permissive=1
05-12 13:35:45.577 I/msm_irqbalance(  703): type=1400 audit(0.0:9953): avc: denied { write } for name="def_timer_ms" dev="sysfs" ino=20317 scontext=u:r:init:s0 tcontext=u:object_r:sysfs_devices_system_cpu:s0 tclass=file permissive=1
05-12 13:35:45.916 E/LightsService(  985): Light requested not available on this device. 2
05-12 13:35:46.059 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:46.063 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:46.063 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:46.082 I/        (    0): TP resume success !
05-12 13:35:46.089 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:46.090 E/LightsService(  985): Light requested not available on this device. 2
05-12 13:35:46.103 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:46.103 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:46.108 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:46.332 I/sysui_multi_action( 2042): [757,186,758,4,826,177,827,2843,1326,22,1327,0,1329,0]
05-12 13:35:46.333 I/sysui_lockscreen_gesture( 2042): [1,177,2843]
05-12 13:35:46.514 I/sysui_multi_action(  985): [757,128,758,2,793,457995,794,6000,795,457995,796,26,798,1,806,android,857,DEVELOPER,858,2,947,0,1395,3,1500,457991]
05-12 13:35:46.514 I/notification_visibility(  985): [-1|android|26|null|1000,0,457995,457995,0,1]
05-12 13:35:46.514 I/sysui_multi_action(  985): [757,128,758,2,793,288101,794,6000,795,5335,796,1,798,0,806,com.netease.cloudmusic,857,miscellaneous,858,2,947,0,1395,3,1500,5335]
05-12 13:35:46.514 I/notification_visibility(  985): [0|com.netease.cloudmusic|1|null|10168,0,288101,5335,0,0]
05-12 13:35:46.515 I/sysui_view_visibility(  985): [127,0]
05-12 13:35:46.515 I/sysui_multi_action(  985): [757,127,758,2]
05-12 13:35:46.515 I/notification_panel_hidden(  985): 
05-12 13:35:46.520 I/am_set_resumed_activity(  985): [0,com.netease.cloudmusic/.activity.MainActivity,resumeTopActivityInnerLocked]
05-12 13:35:46.525 I/am_resume_activity(  985): [0,175403132,39,com.netease.cloudmusic/.activity.MainActivity]
05-12 13:35:46.530 D/StatusBar( 2042): disable<e i a s b H R c s > disable2<q i n >
05-12 13:35:46.537 I/auditd  (17875): type=1400 audit(0.0:9954): avc: denied { ioctl } for comm="RenderThread" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=935 scontext=u:r:untrusted_app_25:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.537 I/RenderThread(17875): type=1400 audit(0.0:9954): avc: denied { ioctl } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=935 scontext=u:r:untrusted_app_25:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.551 I/snet_event_log(  344): [121035042,-1,]
05-12 13:35:46.558 I/init    (    0): Received control message 'interface_start' for 'vendor.mokee.trust@1.0::IUsbRestrict/default' from pid: 344 (/system/bin/hwservicemanager)
05-12 13:35:46.558 E/init    (    0): Could not find service hosting interface vendor.mokee.trust@1.0::IUsbRestrict/default
05-12 13:35:46.552 W/hwservicemanager(  344): getTransport: Cannot find entry vendor.mokee.trust@1.0::IUsbRestrict/default in either framework or device manifest.
05-12 13:35:46.555 D/StatusBar( 2042): disable<e i a s b H R c s > disable2<q i n >
05-12 13:35:46.557 W/AudioTrack( 2042): dead IAudioTrack, PCM, creating a new one from getTimestampExtended()
05-12 13:35:46.559 D/StatusBar( 2042): disable<e i a s b h!r!c s > disable2<q i n >
05-12 13:35:46.553 I/snet_event_log(  344): [121035042,-1,]
05-12 13:35:46.560 I/sysui_view_visibility( 2042): [111,0]
05-12 13:35:46.560 I/sysui_multi_action( 2042): [757,111,758,2]
05-12 13:35:46.565 I/am_on_restart_called(17786): [0,com.netease.cloudmusic.activity.MainActivity,performRestartActivity]
05-12 13:35:46.568 I/am_on_start_called(17786): [0,com.netease.cloudmusic.activity.MainActivity,handleStartActivity]
05-12 13:35:46.569 I/sysui_multi_action( 2042): [757,196,758,2,759,0]
05-12 13:35:46.569 I/sysui_status_bar_state( 2042): [0,0,0,0,0,1]
05-12 13:35:46.569 W/AudioFlinger(25269): createTrack_l(): mismatch between requested flags (00000004) and output flags (00000000)
05-12 13:35:46.571 W/AudioTrack( 2042): AUDIO_OUTPUT_FLAG_FAST denied by server; frameCount 4800 -> 4800
05-12 13:35:46.576 D/PushManager(17786): resumePush
05-12 13:35:46.585 E/AudioFlinger(25269): no wake lock to update, but system ready!
05-12 13:35:46.585 W/UsageStatsService(  985): Event reported without a package name
05-12 13:35:46.586 I/notification_expansion(  985): [0|com.netease.cloudmusic|1|null|10168,0,1,288173,5407,6072]
05-12 13:35:46.586 I/user_activity_timeout_override(  985): -1
05-12 13:35:46.597 V/xiaomi  (17846): [Thread:408] JOB: Handle intent action = com.xiaomi.mipush.SEND_MESSAGE
05-12 13:35:46.597 D/PlayService(17846): PlayerHandler,action:49,null,0,0
05-12 13:35:46.598 W/BroadcastQueue(  985): Permission Denial: broadcasting Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } from com.android.systemui (pid=2042, uid=10011) requires com.mokee.center.permission.JPUSH_MESSAGE due to registered receiver BroadcastFilter{49ab0de u0 ReceiverList{2493819 14257 com.mokee.center:pushcore/10022/u0 remote:1eabb60}}
05-12 13:35:46.598 I/libnfc_nci( 3238): [INFO:NativeNfcManager.cpp(1754)] nfcManager_doSetScreenState: state = 8 prevScreenState= 2, discovry_param = 1
05-12 13:35:46.600 V/xiaomi  (17846): [Thread:408] try send mi push message. packagename:com.netease.cloudmusic action:Command
05-12 13:35:46.600 I/GsaVoiceInteractionSrv(10708): O received Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 }
05-12 13:35:46.601 D/StatInvokeReceiver(24635): onReceive Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 cmp=com.baicizhan.dict/.control.stats.StatInvokeReceiver }
05-12 13:35:46.581 I/auditd  (  875): type=1400 audit(0.0:9955): avc: denied { read } for comm="hwcVsyncThread" path="/sys/devices/virtual/graphics/fb0/vsync_event" dev="sysfs" ino=12130 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:46.581 I/hwcVsyncThread(  875): type=1400 audit(0.0:9955): avc: denied { read } for path="/sys/devices/virtual/graphics/fb0/vsync_event" dev="sysfs" ino=12130 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:sysfs:s0 tclass=file permissive=1
05-12 13:35:46.614 W/BroadcastQueue(  985): Background execution not allowed: receiving Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } to com.chan.cwallpaper/com.tencent.android.tpush.XGPushReceiver
05-12 13:35:46.615 W/BroadcastQueue(  985): Background execution not allowed: receiving Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } to com.google.android.gms/.auth.setup.devicesignals.LockScreenReceiver
05-12 13:35:46.616 W/BroadcastQueue(  985): Background execution not allowed: receiving Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } to com.google.android.gms/.trustagent.UserPresentBroadcastReceiver
05-12 13:35:46.616 W/BroadcastQueue(  985): Background execution not allowed: receiving Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
05-12 13:35:46.616 D/PlayService(17846): PlayerHandler,action:10,null,0,0
05-12 13:35:46.616 W/BroadcastQueue(  985): Permission Denial: broadcasting Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } from com.android.systemui (pid=2042, uid=10011) is not exported from uid 10022 due to receiver com.mokee.center/cn.jpush.android.service.PushReceiver
05-12 13:35:46.629 I/am_on_resume_called(17786): [0,com.netease.cloudmusic.activity.MainActivity,RESUME_ACTIVITY]
05-12 13:35:46.652 I/am_proc_start(  985): [0,25330,10047,com.baicizhan.dict:stat,service,com.baicizhan.dict/.control.stats.StatLogUploadService]
05-12 13:35:46.652 I/ActivityManager(  985): Start proc 25330:com.baicizhan.dict:stat/u0a47 for service com.baicizhan.dict/.control.stats.StatLogUploadService
05-12 13:35:46.653 I/MicroDataManager(10649): isInitializing-false locale not changed-true model not changed-true
05-12 13:35:46.659 I/MicroDetectionState(10649): Should stop hotword detection immediately - true
05-12 13:35:46.661 I/Zygote  (25330): seccomp disabled by setenforce 0
05-12 13:35:46.671 E/izhan.dict:sta(25330): Not starting debugger since process cannot load the jdwp agent.
05-12 13:35:46.673 I/auditd  ( 2611): type=1400 audit(0.0:9956): avc: denied { ioctl } for comm="RenderThread" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=93d scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.673 I/RenderThread( 2611): type=1400 audit(0.0:9956): avc: denied { ioctl } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=93d scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.680 V/xiaomi  (17846): [Thread:408] receive a message, appid=2882303761517142681, msgid= i5LL1589254213031
05-12 13:35:46.686 I/CastDatabase( 2912): Opening the database
05-12 13:35:46.698 I/am_proc_bound(  985): [0,25330,com.baicizhan.dict:stat]
05-12 13:35:46.701 I/WifiService(  985): startScan uid=10120
05-12 13:35:46.703 I/DiscoveryManager( 2912): WifiGuestModeDeviceScanner enabled.
05-12 13:35:46.717 I/SQLiteCastStore( 2912): 0 CastNetworkInfo instances loaded, 0 CastDeviceInfo instances loaded, 0 paired guest mode devices loaded.
05-12 13:35:46.728 I/dvm_lock_sample(  985): [system_server,1,android.display,17,WindowManagerService.java,4997,void com.android.server.wm.WindowManagerService$H.handleMessage(android.os.Message),-,1873,int com.android.server.wm.WindowManagerService.relayoutWindow(com.android.server.wm.Session, android.view.IWindow, int, android.view.WindowManager$LayoutParams, int, int, int, int, long, android.graphics.Rect, android.graphics.Rect, android.graphics.Rect, android.graphics.Rect, android.graphics.Rect, android.graphics.Rect, android.graphics.Rect, android.view.DisplayCutout$ParcelableWrapper, android.util.MergedConfiguration, android.view.Surface),3]
05-12 13:35:46.741 I/auditd  ( 2611): type=1400 audit(0.0:9957): avc: denied { read write } for comm="RenderThread" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.741 I/RenderThread( 2611): type=1400 audit(0.0:9957): avc: denied { read write } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 scontext=u:r:platform_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.790 W/izhan.dict:sta(25330): resources.arsc in APK '/data/app/com.baicizhan.dict-4ibZrgS4lJRoPiG7RsYc0g==/base.apk' is compressed.
05-12 13:35:46.798 I/MultiDex(25330): VM with version 2.1.0 has multidex support
05-12 13:35:46.798 I/MultiDex(25330): install
05-12 13:35:46.798 I/MultiDex(25330): VM has multidex support, MultiDex support library is disabled.
05-12 13:35:46.809 I/auditd  (17875): type=1400 audit(0.0:9958): avc: denied { ioctl } for comm="RenderThread" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=935 scontext=u:r:untrusted_app_25:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.809 I/RenderThread(17875): type=1400 audit(0.0:9958): avc: denied { ioctl } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=935 scontext=u:r:untrusted_app_25:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:46.817 W/audit   (    0): audit_lost=3645 audit_rate_limit=5 audit_backlog_limit=64
05-12 13:35:46.817 E/audit   (    0): rate limit exceeded
05-12 13:35:46.847 D/whiz    (25330): process name: com.baicizhan.dict:stat
05-12 13:35:46.889 I/WebViewFactory(25330): Loading com.android.webview version 81.0.4044.117 (code 404411703)
05-12 13:35:46.914 I/NearbyDiscovery( 2385): FastPairScanner2: Stopping scan [CONTEXT service_id=49 ]
05-12 13:35:46.915 D/BluetoothAdapter( 2385): isLeEnabled(): ON
05-12 13:35:46.920 E/AudioFlinger(25269): no wake lock to update, but system ready!
05-12 13:35:46.925 D/BluetoothAdapter( 2385): isLeEnabled(): ON
05-12 13:35:46.925 I/cr_LibraryLoader(25330): Loaded native library version number "81.0.4044.117"
05-12 13:35:46.929 I/bt_stack(25021): [INFO:gatt_api.cc(948)] GATT_Register 94313328-a570-ac84-80bd-7b9a808a1862
05-12 13:35:46.929 I/bt_stack(25021): [INFO:gatt_api.cc(968)] allocated gatt_if=5
05-12 13:35:46.929 D/BluetoothLeScanner( 2385): onScannerRegistered() - status=0 scannerId=5 mScannerId=0
05-12 13:35:46.935 I/NearbyDiscovery( 2385): FastPairScanner2: Starting LOW_POWER_SCANNING scanning [CONTEXT service_id=49 ]
05-12 13:35:47.019 I/am_meminfo(  985): [608333824,326709248,76292096,213745664,256700416]
05-12 13:35:47.027 W/SurfaceFlinger(  453): Attempting to set client state on removed layer: SnapshotStartingWindow for taskId=39#0
05-12 13:35:47.028 W/SurfaceFlinger(  453): Attempting to destroy on removed layer: SnapshotStartingWindow for taskId=39#0
05-12 13:35:47.054 I/am_pss  (  985): [2385,10120,com.google.android.gms.persistent,45958144,36962304,4117504,85245952,1,5,34]
05-12 13:35:47.086 I/am_pss  (  985): [2029,10081,com.google.android.inputmethod.latin,46587904,38219776,5661696,84361216,1,6,31]
05-12 13:35:47.108 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:47.109 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:47.109 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:47.115 I/am_pss  (  985): [17681,10126,com.google.android.packageinstaller,23202816,21229568,83968,59834368,1,18,29]
05-12 13:35:47.119 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:47.135 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:47.135 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:47.141 I/am_pss  (  985): [11167,10144,com.google.android.tts,22647808,610304,21065728,32043008,1,18,26]
05-12 13:35:47.143 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:47.166 I/am_pss  (  985): [21453,10119,com.google.android.apps.turbo,7159808,5840896,98304,39809024,1,18,25]
05-12 13:35:47.191 I/am_pss  (  985): [3676,10035,ch.deletescape.lawnchair.mokee:bugReport,8650752,1314816,6572032,29298688,1,4,24]
05-12 13:35:47.216 I/am_pss  (  985): [3174,10120,com.google.process.gservices,6033408,2838528,2378752,31981568,1,18,24]
05-12 13:35:47.244 I/am_pss  (  985): [14191,10022,com.mokee.center,12377088,7299072,3518464,45686784,1,4,28]
05-12 13:35:47.277 I/am_pss  (  985): [14257,10022,com.mokee.center:pushcore,14988288,9621504,3235840,58056704,1,4,32]
05-12 13:35:47.303 I/am_pss  (  985): [10708,10128,com.google.android.googlequicksearchbox:interactor,11384832,8900608,108544,43659264,1,4,26]
05-12 13:35:47.332 I/am_pss  (  985): [5151,10117,com.google.android.ims,12160000,6848512,4061184,42491904,1,9,28]
05-12 13:35:47.354 W/cr_AwDataDirLock(25330): Using WebView from more than one process at once with the same data directory is not supported. https://crbug.com/558377 : Lock owner com.baicizhan.dict (pid 24635)
05-12 13:35:47.356 I/am_pss  (  985): [5830,1001,com.qualcomm.qcrilmsgtunnel,4600832,770048,3146752,26902528,1,5,24]
05-12 13:35:47.380 I/am_pss  (  985): [3339,10084,com.android.smspush,3553280,987136,1963008,24678400,1,5,23]
05-12 13:35:47.387 E/cr_ChildProcessService(24704): Service is already bound by pid 24635, cannot bind for pid 25330
05-12 13:35:47.394 E/cr_SpareChildConn(25330): Failed to warm up the spare sandbox service
05-12 13:35:47.404 I/am_pss  (  985): [3250,1068,com.android.se,3648512,1032192,1995776,25362432,1,0,23]
05-12 13:35:47.429 I/am_pss  (  985): [3238,1027,com.android.nfc,16165888,11710464,3458048,42557440,1,0,25]
05-12 13:35:47.452 W/chromium(25330): [WARNING:dns_config_service_posix.cc(341)] Failed to read DnsConfig.
05-12 13:35:47.454 I/am_pss  (  985): [3220,10005,org.mokee.audiofx,6535168,3383296,2269184,31965184,1,0,24]
05-12 13:35:47.470 D/ConnectivityService(  985): requestNetwork for uid/pid:10047/25330 NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ]
05-12 13:35:47.471 D/WIFI    (  985): got request NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ] with score 60
05-12 13:35:47.471 D/WIFI_UT (  985): got request NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ] with score 60
05-12 13:35:47.472 D/Ethernet(  985): got request NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ] with score 60
05-12 13:35:47.472 D/PhoneSwitcherNetworkRequstListener( 2342): got request NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ] with score 60
05-12 13:35:47.472 D/TelephonyNetworkFactory[0]( 2342): got request NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ] with score 60
05-12 13:35:47.472 D/PhoneSwitcher( 2342): evaluating due to netRequest
05-12 13:35:47.482 I/am_pss  (  985): [2342,1001,com.android.phone,13508608,8638464,3144704,46600192,1,0,28]
05-12 13:35:47.495 I/app init(25330): [DictAppHandler.java, f, 80]:app init channel = qq
05-12 13:35:47.506 I/am_pss  (  985): [2328,1000,org.pixelexperience.screenshot,4092928,1122304,2374656,24772608,1,0,24]
05-12 13:35:47.507 D/StatLogUploadService(25330): refresh mobile quota 104857600
05-12 13:35:47.512 V/baicizhandb(24635): delete tb_stat_log where timestamp <= 1588392000509
05-12 13:35:47.516 I/izhan.dict:sta(25330): System.exit called, status: 0
05-12 13:35:47.516 I/AndroidRuntime(25330): VM exiting with result code 0, cleanup skipped.
05-12 13:35:47.532 I/am_pss  (  985): [2056,1000,com.mokee.aegis,7669760,3948544,2579456,37969920,1,0,25]
05-12 13:35:47.577 D/ConnectivityService(  985): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ LISTEN id=263, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&FOREGROUND Unwanted:  Uid: 10047] ], android.os.BinderProxy@785f867)
05-12 13:35:47.577 D/ConnectivityService(  985): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ], android.os.BinderProxy@c645614)
05-12 13:35:47.577 D/ConnectivityService(  985): releasing NetworkRequest [ TRACK_DEFAULT id=262, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Unwanted:  Uid: 10047] ] (release request)
05-12 13:35:47.577 I/ActivityManager(  985): Process com.baicizhan.dict:stat (pid 25330) has died: fore SVC 
05-12 13:35:47.577 I/am_proc_died(  985): [0,25330,com.baicizhan.dict:stat,0,9]
05-12 13:35:47.578 W/libprocessgroup(  985): kill(-25330, 9) failed: No such process
05-12 13:35:47.578 D/PhoneSwitcher( 2342): evaluating due to netReleased
05-12 13:35:47.580 I/Zygote  (  376): Process 25330 exited cleanly (0)
05-12 13:35:47.617 I/am_pss  (  985): [985,1000,system,154518528,103022592,9621504,265936896,1,0,84]
05-12 13:35:47.620 W/libprocessgroup(  985): kill(-25330, 9) failed: No such process
05-12 13:35:47.620 I/libprocessgroup(  985): Successfully killed process cgroup uid 10047 pid 25330 in 42ms
05-12 13:35:48.143 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:48.150 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:48.154 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:48.169 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:48.184 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:48.184 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:48.189 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:48.520 I/ActivityManager(  985): START u0 {flg=0x20000 cmp=com.netease.cloudmusic/.activity.PlayerActivity (has extras)} from uid 10168
05-12 13:35:48.522 I/am_create_activity(  985): [0,7007933,39,com.netease.cloudmusic/.activity.PlayerActivity,NULL,NULL,NULL,131072]
05-12 13:35:48.525 I/am_pause_activity(  985): [0,175403132,com.netease.cloudmusic/.activity.MainActivity,userLeaving=true]
05-12 13:35:48.543 I/am_on_paused_called(17786): [0,com.netease.cloudmusic.activity.MainActivity,performPause]
05-12 13:35:48.549 I/auditd  (  958): type=1400 audit(0.0:9961): avc: denied { append } for comm="qmuxd" path="/sys/power/wake_lock" dev="sysfs" ino=77 scontext=u:r:init:s0 tcontext=u:object_r:sysfs_wake_lock:s0 tclass=file permissive=1
05-12 13:35:48.549 I/qmuxd   (  958): type=1400 audit(0.0:9961): avc: denied { append } for path="/sys/power/wake_lock" dev="sysfs" ino=77 scontext=u:r:init:s0 tcontext=u:object_r:sysfs_wake_lock:s0 tclass=file permissive=1
05-12 13:35:48.550 I/am_restart_activity(  985): [0,7007933,39,com.netease.cloudmusic/.activity.PlayerActivity]
05-12 13:35:48.553 I/am_set_resumed_activity(  985): [0,com.netease.cloudmusic/.activity.PlayerActivity,minimalResumeActivityLocked]
05-12 13:35:48.560 W/ActivityThread(17786): handleWindowVisibility: no activity for token android.os.BinderProxy@9b2663a
05-12 13:35:48.561 I/sysui_count(  985): [window_time_0,230]
05-12 13:35:48.561 I/sysui_multi_action(  985): [757,803,799,window_time_0,802,230]
05-12 13:35:48.570 I/AppCompatDelegate(17786): The Activity's LayoutInflater already has a Factory installed so we can not install AppCompat's
05-12 13:35:48.730 I/am_on_create_called(17786): [0,com.netease.cloudmusic.activity.PlayerActivity,performCreate]
05-12 13:35:48.733 I/am_on_start_called(17786): [0,com.netease.cloudmusic.activity.PlayerActivity,handleStartActivity]
05-12 13:35:48.737 D/PlayService(17846): PlayerHandler,action:49,null,1,0
05-12 13:35:48.738 D/PlayerActivityBase(17786): onResume()
05-12 13:35:48.741 D/PlayService(17846): PlayerHandler,action:51,null,0,0
05-12 13:35:48.751 I/am_on_resume_called(17786): [0,com.netease.cloudmusic.activity.PlayerActivity,RESUME_ACTIVITY]
05-12 13:35:48.881 I/auditd  (  453): type=1400 audit(0.0:9964): avc: denied { ioctl } for comm="surfaceflinger" path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=915 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:48.881 I/surfaceflinger(  453): type=1400 audit(0.0:9964): avc: denied { ioctl } for path="/dev/kgsl-3d0" dev="tmpfs" ino=1772 ioctlcmd=915 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:device:s0 tclass=chr_file permissive=1
05-12 13:35:49.190 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:49.191 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:49.191 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:49.201 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:49.217 I/am_stop_activity(  985): [0,175403132,com.netease.cloudmusic/.activity.MainActivity]
05-12 13:35:49.220 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:49.220 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:49.225 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:49.335 I/am_on_stop_called(17786): [0,com.netease.cloudmusic.activity.MainActivity,STOP_ACTIVITY_ITEM]
05-12 13:35:50.226 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:50.226 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:50.226 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:50.240 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:50.255 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:50.256 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:50.264 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:50.571 I/MSM-irqbalance(  703): Decided to move IRQ215 from CPU2 to CPU3
05-12 13:35:51.265 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:51.269 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:51.269 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:51.282 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:51.289 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:51.289 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:51.295 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:52.296 I/bt_stack(25021): [INFO:device.cc(1227)] c4:67:b5:39:cc:ea : HandlePlayPosUpdate
05-12 13:35:52.296 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:52.296 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:52.305 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
05-12 13:35:52.319 D/NewAvrcpTargetJni(25021): getCurrentPlayStatus
05-12 13:35:52.319 D/NewAvrcpNativeInterface(25021): getPlayStatus
05-12 13:35:52.329 I/bt_stack(25021): [INFO:device.cc(461)] c4:67:b5:39:cc:ea : PlaybackPosNotificationResponse: Queue next play position update
