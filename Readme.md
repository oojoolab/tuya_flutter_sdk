# [Eng] Tuya Flutter SDK

![tuya_smart_logo.jpg](tuya_smart_logo.jpg)

Although [Tuya's SDK](https://developer.tuya.com/en/docs/iot) officially supports Android and iOS, there's currently no support for React-Native or Flutter. However, given the substantial demand for a Tuya Flutter SDK, I took it upon myself to develop one. This endeavor involved numerous trials and errors and tackling several issues not documented in Tuya's official documentation. Through this process, I managed to create a stable SDK, resolving specific problems for both Android and iOS before integrating everything into Flutter.

This development journey was fraught with challenges, but ultimately, it culminated in success. If anyone is interested in the Tuya Flutter SDK, I plan to sell it for a fee, roughly equivalent to the salary of a developer for a month.

I ask that the effort invested in this project be appreciated, as it is an attempt to gain due compensation for the developer's hard work.

### Features Offered in the Flutter SDK

---

- `TuyaSmartSdk`
    - `init`
        
        
    - `setDebugMode`
- `TuyaSmartActivator`
    - `getActivatorToken`
    - `startConfigWiFi`
        - `onQRCodeSuccess`
        - `onActiveSuccess`
        - `onActiveFailed`
    - `stopConfigWiFi`
- `TuyaSmartCamera`
    - `getCameraInstance`
    - `connect`
    - `disConnect`
    - `isConnecting`
    - `publishDps`
    - `queryRecordDaysByMonth`
    - `queryRecordTimeSliceByDay`
    - `getDayKey`
    - `getMonthKey`
    - `getMute`
    - `setMute`
    - `snapshot`
    - `setLoudSpeakerStatus`
    - `startPreview`
    - `stopPreview`
    - `setVideoClarity`
    - `startPlayBack`
    - `stopPlayBack`
    - `pausePlayBack`
    - `resumePlayBack`
    - `setPlayBackSpeed`
    - `startRecordLocalMp4`
    - `stopRecordLocalMp4`
    - `isRecording`
    - `startPlayBackDownload`
    - `stopPlayBackDownload`
    - `pausePlayBackDownload`
    - `resumePlayBackDownload`
    - `startAudioTalk`
    - `stopAudioTalk`
    - `isTalking`
    - `removeDevice`
    - `dispose`
- `TuyaSmartHome`
    - `getHomeDetail`
- `TuyaSmartHomeDataManager`
    - `queryValueByDPID`
- `TuyaSmartHomeManager`
    - `createHome`
    - `getHomeList`
- `TuyaSmartUser`
    - `sendVerifyCodeWithEmail`
    - `registerWithEmail`
    - `registerWithPhone`
    - `switchUserRegion`
    - `loginWithEmail`
    - `logout`

### Collaborative Enhancement: Tailoring the SDK to Your Project's Needs

---

I already possess the SDK, but it may lack certain features you desire, necessitating a collaboration where you hire me for a month. I am capable of further enhancing the SDK to ensure the successful completion of your project.

### Proposal Request: Estimation Based on Senior Developer's Monthly Salary

---

Please propose an initial estimate based on the monthly salary of a senior developer. I will then assess the appropriateness of your offer and check my schedule before responding.

### Contact Me

---

If you're interested in this tailored approach to enhancing the SDK for your specific project needs, please don't hesitate to contact me. Let's collaborate to ensure the success of your project.

email: oojooteam@gmail.com
