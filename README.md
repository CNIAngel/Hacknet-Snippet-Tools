# Hacknet-SublimeText3-Snippets
This Sublime Text 3 package is made to help out people who are just starting or are already in the process of making their Hacknet Extentions.

## How far along until this package is usable?
At this point of commit (0500 on 14/06/17) the package is usable. Though it's not as good as I want it to be.

## Where can I get the package
Go to Releases and grab Hacknet-Tools.sublime-package and put it into your /Packages folder. I also plan to make it so you can just grab it using Package Control.

## How are you improving on it?
Just general checking up to make sure I didn't ruin the spelling somewhere that makes the work harder. Also adding in the auto tab (not sure what the functionality is called) for all the snippet, so that when the snippet is generated for you you can TAB to each relevant area and put in the data needed.

## What are the Snippet Trigger words
Got that for you right here. To save time I'm grabbing the information from the Hacknet-AHK-Tools README.md file (the main inspriation for this package).

## Currently available Hotstrings

- [General](#general)
- [Computer](#computer)
- [Mission](#mission)
- [Conditional Actions](#conditional-actions)

### General

| Hotstring | Generated xml |
| --- | --- |
| `Comment;` | `<!-- -->` |
| `UTFEncoding;` | `<?xml version = "1.0" encoding = "UTF-8" ?>` |

### Computer

[Return to list](#currently-available-hotstrings)

StartFlag - `Comp`

| Hotstring | Generated xml |
| --- | --- |
|`CompStart;`|`<Computer id="" name="" ip="" security="" allowsDefaultBootModule="" icon="" type="">`<br><br>`</Computer>`|
|`CompPass;`|`<adminPass pass="" />`|
|`CompAccount;`|`<account username="" password="" type="" />`|
|`CompPorts;`|`<ports></ports>`<br>`<portsForCrack val="" />`|
|`CompFirewall;`|`<firewall level="" solution="" additionalTime=""/>`|
|`CompTrace;`|`<trace time="" />`|
|`CompAuto;`|`<admin type="" resetPassword="" isSuper="" />`|
|`CompRemap;`|`<portRemap></portRemap>`|
|`CompTracker;`|`<tracker />`|
|`CompLink;`|`<dlink target="" />`|
|`CompNear;`|`<positionNear target="" position="" total="" extraDistance="" force=""/>`|
|`CompFile;`|`<file path="" name=""></file>`|
|`CompThemeFile;`|`<customthemefile path="" name="" themePath=""/>`|
|`CompEncryptedFile;`|`<encryptedFile path="" name="" extension="" ip="" header="" pass="">`|

Computer Eos subsection

StartFlag - `CompEos`

| Hotstring | Generated XML |
| --- | --- |
|`CompEosStart;`|`<eosDevice name="" id="" icon="" empty="" passOverride="">`<br><br>`</eosDevice>`|
|`CompEosNote;`|`<note></note>`|
|`CompEosMail;`|`<mail username="" pass="" />`|
|`CompEosFile;`|`<file path="" name=""></file>`|

Computer MailServer subsection

StartFlag - `CompMail`

| Hotstring | Generated XML |
| --- | --- |
|`CompMailStart;`|`<mailServer name="" color="" generateJunk="">`<br><br>`</mailServer>`|
|`CompMailEmail;`|`<email recipient="" sender="" subject=""></email>`|

Computer MessageBoard daemon

Starflag - `CompBoard`

| Hotstring | Generated XML |
| --- | --- |
|`CompBoardStart;`|`<messageBoard name="">`<br><br>`</messageBoard>`|
|`CompBoardThread;`|`<thread></thread>`|

Computer Single-flag daemons

StartFlag - `Comp`

| Hotstring | Generated XML |
| --- | --- |
|`CompUpload;`|`<uploadServerDaemon name="" folder="" needsAuth="" color=""/>`|
|`CompWeb;`|`<addWebServer name="" url="" />`|
|`CompDeathRow;`|`<deathRowDatabase />`|
|`CompAcademic;`|`<academicDatabase />`|
|`CompIsp;`|`<ispSystem />`|
|`CompMedical;`|`<MedicalDatabase />`|
|`CompHeart;`|`<HeartMonitor patient=""/>`|
|`CompClicker;`|`<PointClicker />`|
|`CompSongChanger;`|`<SongChangerDaemon />`|
|`CompEntropy;`|`<variableMissionListingServer name="" iconPath="" articleFolderPath="" color="" assigner="" public="" title=""/>`|
|`CompCSEC;`|`<missionHubServer groupName="" serviceName="" missionFolderPath="" themeColor="" lineColor="" backgroundColor="" allowAbandon=""/>`|
|`CompCredits;`|`<CreditsDaemon Title="" ButtonText="" ConditionalActionSetToRunOnButtonPressPath=""/>`|
|`CompCustom;`|`<CustomConnectDisplayDaemon />`|
|`CompLogo;`|`<LogoDaemon Name="" ShowsTitle="" TextColor="" LogoImagePath=""></LogoDaemon>`|
|`CompLogoCustom;`|`<LogoCustomConnectDisplayDaemon logo="" title="" overdrawLogo="" buttonAlignment="" />`|
|`CompWhAuthenticator;`|`<WhitelistAuthenticatorDaemon SelfAuthenticating="" />`|
|`CompWhRemote;`|`<WhitelistAuthenticatorDaemon Remote=""/>`|

Computer Memory subsection

StartFlag - `CompMem`

| Hotstring | Generated XML |
| --- | --- |
|`CompMemDump;`|`<memoryDumpFile name="" path="">`<br><br>`</memoryDumpFile>`|
|`CompMemStart;`|`<Memory>`<br><br>`</Memory>`|
|`CompMemData;`|`<Data>`<br><br>`</Data>`|
|`CompMemBlock;`|`<Block></Block>`|
|`CompMemCommands;`|`<Commands>`<br><br>`</Commands>`|
|`CompMemCommand;`|`<Command></Command>`|
|`CompMemImages;`|`<Images>`<br><br>`</Images>`|
|`CompMemImage;`|`<Image></Image>`|

Computer IRCDaemon subsection

StartFlag - `CompIRC`

| Hotstring | Generated XML |
| --- | --- |
|`CompIRCStart;`|`<IRCDaemon themeColor="" name="" needsLogin="">`<br><br>`</IRCDaemon>`|
|`CompIRCUser;`|`<user name="" color=""/>`|

Computer DHSDaemon subsection

StartFlag `CompDHS`

| Hotstring | Generated XML |
| --- | --- |
|`CompDHSStart;`|`<DHSDaemon groupName="" addsFactionPointOnMissionComplete="" autoClearMissionsOnPlayerComplete="" themeColor="" allowContractAbbandon="">`<br><br>`</DHSDaemon>`|
|`CompDHSAgent;`|`<agent name="" pass="" color=""/>`|

Computer DatabaseDaemon subsection

StartFlag `CompDB`

| Hotstring | Generated XML |
| --- | --- |
|`CompDBStart;`|`<DatabaseDaemon Permissions="" DataType="" Foldername="" Color="" AdminEmailAccount="" AdminEmailHostID="" Name="">`<br><br>`</DatabaseDaemon>`|
|`CompDBGitCommitEntry;`|`<GitCommitEntry>`<br>`<EntryNumber></EntryNumber>`<br>`<ChangedFiles>`<br>`<String></String>`<br>`</ChangedFiles>`<br>`<Message></Message>`<br>`<UserName></UserName>`<br>`<SourceIP></SourceIP>`<br>`</GitCommitEntry>`|
|`CompDBTextRecord;`|`<TextRecord>`<br>`<Title></Title>`<br>`<Data></Data>`<br>`</TextRecord>`|
|`CompDBOnlineAccount;`|`<OnlineAccount>`<br>`<ID></ID>`<br>`<Username></Username>`<br>`<BanStatus></BanStatus>`<br>`<Notes></Notes>`<br>`</OnlineAccount>`|

### Mission

[Return to list](#currently-available-hotstrings)

StartFlag `Miss`

| Hotstring | Generated XML |
| --- | --- |
|`MissStart;`|`<mission id="" activeCheck="" shouldIgnoreSenderVerification="">`<br><br>`</mission>`|
|`MissOnStart;`|`<missionStart val="" suppress=""></missionStart>`|
|`MissOnEnd;`|`<missionEnd val=""></missionEnd>`|
|`MissNext;`|`<nextMission IsSilent=""></nextMission>`|
|`MissBranches;`|`<branchMissions>`<br><br>`</branchMissions>`|
|`MissBranch;`|`<branch></branch>`|
|`MissPost;`|`<posting title="" reqs="" requiredRank="" ></posting>`|

Mission Goals subsection

StartFlag `MissGoal`

| Hotstring | Generated XML |
| --- | --- |
|`MissGoalStart;`|`<goals>`<br><br>`</goals>`|
|`MissGoalFileDeletion;`|`<goal type="filedeletion" target="" file="" path=""/>`|
|`MissGoalClearFolder;`|`<goal type="clearfolder" target="" path=""/>`|
|`MissGoalFileDownload;`|`<goal type="filedownload" target="" file="" path=""/>`|
|`MissGoalFileChange;`|`<goal type="filechange" target="" file="" path="" keyword="" removal="" caseSensitive=""/>`|
|`MissGoalGetAdmin;`|`<goal type="getadmin" target=""/>`|
|`MissGoalGetString;`|`<goal type="getstring" target="" />`|
|`MissGoalDelay;`|`<goal type="delay" time=""/>`|
|`MissGoalHasFlag;`|`<goal type="hasflag" target=""/>`|
|`MissGoalFileUpload;`|`<goal type="fileupload" target="" file="" path="" destTarget="" destPath="" decrypt="" decryptPass=""/>`|
|`MissGoalAddDegree;`|`<goal type="" owner="" degree="" uni="" gpa=""/>`|
|`MissGoalWipeDegrees;`|`<goal type="wipedegrees" owner=""/>`|
|`MissGoalSendEmail;`|`<goal type="sendemail" mailServer="" recipient="" subject=""/>`|
|`MissGoalGetAdminPasswordString;`|`<goal type="getadminpasswordstring" target=""/>`|

Mission Email subsection

StartFlag `MissEmail`

| Hotstring | Generated XML |
| --- | --- |
|`MissEmailStart;`|`<email>`<br>`<sender></sender>`<br>`<subject></subject>`<br>`<body></body>`<br>`<attachments>`<br>`</attachments>`<br>`</email>`|
|`MissEmailNote;`|`<note title=""></note>`|
|`MissEmailLink;`|`<link comp="" />`|
|`MissEmailAccount;`|`<account comp="" user="" pass="" />`|

### Conditional Actions

[Return to list](#currently-available-hotstrings)

Conditional Actions section

StartFlag "Cond"

| Hotstring | Generated XML |
| --- | --- |
| `CondStart;` | `<ConditionalActions>`<br><br>`</ConditionalActions>` |
| `CondFunc;` | `<RunFunction FunctionName="" FunctionValue="" />` |
| `CondLoadMiss;` | `<LoadMission MissionName="" />` |
| `CondAddAsset;` | `<AddAsset FileName="" FileContents="" TargetComp="" TargetFolderpath="" />` |
| `CondCopyAsset;` | `<CopyAsset DestFilePath="" DestComp="" SourceComp="" SourceFileName="" SourceFilePath="" />` |
| `CondAddMiss;` | `<AddMissionToHubServer MissionFilepath="" TargetComp="" AssignmentTag=""/>` |
| `CondAddMissCSEC;` | `<AddMissionToHubServer MissionFilepath="" TargetComp="" />` |
| `CondRemoveMiss;` | `<RemoveMissionFromHubServer MissionFilepath="" TargetComp="" />` |
| `CondAddThread;` | `<AddThreadToMissionBoard ThreadFilepath="" TargetComp="" />` |
| `CondAddIRC;` | `<AddIRCMessage Author="" TargetComp="" Delay=""></AddIRCMessage>` |
| `CondCrashComp;` | `<CrashComputer TargetComp="" CrashSource="" DelayHost="" Delay="" />` |
| `CondDeleteFile;` | `<DeleteFile TargetComp="" FilePath="" FileName="" DelayHost="" Delay=""/>` |
| `CondAddCond;` | `<AddConditionalActions Filepath="" DelayHost="" Delay=""/>` |
| `CondSave;` | `<SaveGame DelayHost="" Delay=""/>` |
| `CondHackScript;` | `<LaunchHackScript Filepath="" DelayHost="" Delay="" SourceComp="" TargetComp="" RequireLogsOnSource="" RequireSourceIntact=""/>` |
| `CondSwitchTheme;` | `<SwitchToTheme ThemePathOrName="" FlickerInDuration="" DelayHost="" Delay="" />` |
| `CondAppend;` | `<AppendToFile DelayHost="" Delay="" TargetComp="" TargetFolderpath="" TargetFilename=""></AppendToFile>` |
| `CondKillExe;` | `<KillExe DelayHost="" Delay="" ExeName="" />` |
| `CondHide;` | `<HideNode DelayHost="" Delay="" TargetComp="" />` |
| `CondHideAll;` | `<HideAllNodes DelayHost="" Delay=""/>` |
| `CondShow;` | `<ShowNode DelayHost="" Delay="" Target="" />` |
| `CondGiveAccount;` | `<GivePlayerUserAccount DelayHost="" Delay="" TargetComp="" Username="" />` |
| `CondChangeIP;` | `<ChangeIP DelayHost="" Delay="" TargetComp="" NewIP="" />` |
| `CondChangeAlert;` | `<ChangeAlertIcon Target="" Type="" DelayHost="" Delay=""/>` |
| `CondStartBleed;` | `<StartScreenBleedEffect AlertTitle="" CompleteAction="" TotalDurationSeconds="" DelayHost="" Delay=""></StartScreenBleedEffect>` |
| `CondCancelBleed;` | `<CancelScreenBleedEffect DelayHost="" Delay="" />` |
| `CondOnConnect;` | `<OnConnect target="" needsMissionComplete="" requiredFlags="">`<br><br>`</OnConnect>` |
| `CondHasFlags;` | `<HasFlags requiredFlags="">`<br><br>`</HasFlags>` |
| `CondOnAdmin;` | `<OnAdminGained target="">`<br><br>`</OnAdminGained>` |
| `CondInst;` | `<Instantly>`<br><br>`</Instantly>` |
| `CondNotHaveFlags;` | `<DoesNotHaveFlags Flags="">`<br><br>`</DoesNotHaveFlags>` |
| `CondOnDisconnect;` | `<OnDisconnect>`<br><br>`</OnDisconnect>` |

