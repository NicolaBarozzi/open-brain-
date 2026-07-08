---
titolo: "x-bees Changelog"
url: "https://wildix.atlassian.net/wiki/spaces/DOC/pages/53903361/x-bees+Changelog"
fonte: "wildix.atlassian.net"
autore: null
data_articolo: "2026-07-08"
recuperato_il: "2026-07-08"
email:
  - "2025-12-05 — dist*ll daily digest <andrew@distll.ai>"
stato: "ok"
---

# x-bees Changelog

# x-bees Changelog

x-bees Changelog contains all the latest features and improvements.

x-bees docs: x-bees documentation.

x-bees blog: x-bees news on our Blog.

Links to download x-bees:

Note: It can take up to 24 hours after release for mobile apps to become publicly available.

Link for sharing: https://wildix.atlassian.net/wiki/x/AYA2Aw

Abbreviations:

- xbs = x-bees 
- rna = React Native Applications (e.g. x-bees, Collaboration 7, x-hoppers) 
- ca = Cloud Analytics 
- int = integrations 
- wms = Wildix Management System (WMS) 
- sys = system 
- wda = Wildix Data Analytics service 
- wim = Wildix Integrations Middleware service 
- wizy = videoconference 

Important:

- To get x-bees web version updated, you need to refresh the page. 
- To update x-bees Chrome extension, you need to restart Google Chrome. 

## Web 2.71.1.2896402 / iOS 2.71.1.521717 / Android 2.71.1.521717 Date: 08.07.2026

### Improvements

[XBS-6907] - rna: made some UI improvements on web by updating button shapes and colors across Inbox, History, Contacts, Favorites, Voicemails tabs and related dialogs and forms

[XBS-7138] - rna: added support for displaying Wildix calls in the native iPhone call history (disabled by default)

How-to:

- Go to Settings -> Calls 
- Enable the option Show in iOS Recents 

[XBS-7140] - rna: added Copy email and Call actions to the group member menu on web

How-to:

- In group conversation, open Info frame and find the relevant user 
- Click three dots 
- Select one of the available actions: 

- Copy email: copies the member's email address to the clipboard 
- Call: starts a call with the selected member 

[WMS-25377] - wms: improved Cloud Analytics (CDR-View 2.0) to ensure the Location column displays correct data instead of "null"

- Documentation: How to use Cloud Analytics (CDR-View 2.0) 

[WMS-26329] - x-ca: updated licensing requirements for the Services tab in the x-bees Live Dashboard. The tab is now available only for PBXs with an x-caracal license

### Fixes

[XBS-7232] - rna: fixed an issue where Revenue Intelligence call recording pages could crash when a call contained both recording and voicemail attachments on web

[WMS-26591] - wizy: fixed an issue where some participants could not hear others during a videoconference

## Web 2.70.1.2875721 / iOS 2.70.1.518479 / Android 2.70.1.518479 Date: 01.07.2026

### Improvements

[WMS-26174] - ai: added Analysis configuration for Chat and Voice AI Agent capabilities, allowing to add tags, variables, timeline comments, and result data to improve conversation categorization, filtering, and analysis in Revenue Intelligence

How-to:

- Go to WMS → PBX → Integrations → Cloud Integrations 
- In the AI section, open Chat AI Agents or Voice AI Agents 
- Create a new AI agent or edit an existing one 
- Under Capabilities, add or edit one of the supported capabilities 
- In the capability configuration window, scroll to the Analysis section 
- Click Add annotation 
- Select the type of annotation you want to add: 

- Tag: adds a tag to the call, chat, or conference. Tag can also be used in Revenue Intelligence analysis 
- Log comment: adds predefined text to the conversation timeline for users and Revenue Intelligence analysis 
- Log variables: record capability variable values for Revenue Intelligence and conversation details 
- Log result: record the tool output for Revenue Intelligence and conversation details 

- Configure the selected annotation and click Add 
- Click Save to save the AI agent configuration 

[XBS-6998] - x-bees: added the possibility to filter and sort the Cases list on the My Salesforce tab

The new Filter menu allows users to view cases by My Cases, Opened Cases, and Closed Cases, while the sorting menu provides options to order records by fields

[XBS-7091] - rna: made some UI/ UX improvements to Revenue Intelligence Dashboards

- Improved Save button logic, so that the button becomes active only when there are any unsaved changes. Also, the Save button shows the red dot indicator when unsaved changes are present. 
- The Reset button now reverts both filters and chart configurations to the saved baseline in a single click. 
- Renamed Calls tab into Calls & Conferences. 
- Charts that were changed but were not saved are now marked as Unsaved. 
- The Duration filter toggle step has been reduced from 5 minutes to 1 minute for more precise control. 

[XBS-7195] - rna: added support for copy-to-clipboard functionality for custom integrations in WMS -> PBX -> Integrations -> Third-party apps

### Fixes

[WMS-26493] - wizy: fixed a rare issue in which conference recording could not be started

[XBS-6412] - rna: fixed an issue on iOS mobile devices, where spell check did not show spelling suggestions or highlight misspelled words

[XBS-6965] - rna: fixed an issue where the wrong contact note could be displayed when switching between contacts on web

[XBS-7201] - ai: fixed an issue where changes to Wilma settings could not be saved if the Your occupation field was left empty

## Web 2.69.3.2864639 Date: 29.06.2026

### Fix

[XBS-7167] - rna: fixed attended transfer issues on web when using a hardware phone as the active device, including missing transfer completion controls

This fix covers an additional user scenario identified through customer feedback.

## Web 2.69.2.2852136 Date: 25.06.2026

### Fix

[XBS-7225] - rna: fixed an issue where the Salesforce integration appeared blank on mobile devices after a successful login to the integration

## Web 2.69.2.2852136 / iOS 2.69.1.515045 / Android 2.69.1.515045 Date: 24.06.2026

### Improvements

[XBS-6698] - rna: improved contact lookup on web for phone numbers stored in Outlook Classic with different formats

[XBS-6899] - wim: improved Salesforce entity matching by supporting all email and phone number fields, including custom fields

[XBS-6969] - rna: implemented automatic PBX failover in RNA for web and mobile, ensuring telephony continuity when the primary PBX is unavailable, with automatic recovery when the primary PBX is restored

- Failover switching is not performed during an active call. On mobile devices, failover switching is also disabled when the application is running in the background or in Offline status 
- A "Failover mode active" notification is displayed in x-bees web and mobile. Once the primary PBX becomes available again, the application automatically reconnects to it and the notification disappears 

Note: Failover is available only for PBXs within the WMS network with failover enabled

Limitations:

- Only primary domain addresses in the *.wildixin.com format can be used as failover candidates. 
- Failover uses SIP reconnection only. Some PBX features and settings may be unavailable while operating in failover mode. 
- Push notification functionality is limited in failover mode. 
- Phonebook integration is not available in failover mode. 

[XBS-7125] - rna: added possibility to disable automatic transcription and recording of conferences with external users

How-to:

Add the following variables to the /rw2/etc/env.custom.ini file:

- To disable automatic recording: WIZYCONF_RECORDING_AUTOSTART_ALLOW=false 
- To disable automatic transcription: WIZYCONF_TRANSCRIPTION_AUTOSTART_ALLOW=false 

[XBS-7141] - kite: improved the guest user logic for the Kite widget by automatically generating random names for anonymous users instead of prompting them to enter one manually

How-to:

- Go to WMS -> PBX -> Integrations -> Cloud integrations 
- In the Channels section, choose Kite 
- Choose the necessary widget or add a new one 
- Enable the option Generate random names for anonymous visitors and save the changes 

[WMS-26317] - wizy: added notification that a conference is recorded, to ensure participants are informed and consent to the recording

[WMS-26382] - sys: fixed attended transfer issues on web, when using a hardware phone as the active device, including missing transfer completion controls and persistent call pop-ups after transfer completion

### Fixes

[XBS-6442] - ri: fixed details view visibility issue when selecting chart bars in full-screen mode on web

[XBS-6935] - xbs: fixed an issue where Microsoft 365 calendars could be unavailable in Kite settings due to email address casing differences

[XBS-7055] - ai: fixed an issue where Wilma could fail to recognize an active Salesforce integration if it was connected after the chat was created

[XBS-7079] - rna: fixed an issue on mobile in which users received notifications on conference start while the user status was set to offline

[XBS-7104] - rna: fixed an issue in which false "Leave app?" notification was displayed on web when downloading a recording from Revenue Intelligence or a Desktop app during an active call or conference

[XBS-7167] - rna: fixed attended transfer issues on web when using a hardware phone as the active device, including missing transfer completion controls and persistent call pop-up after transfer completion

The fix is available starting from WMS versions 7.09.20260619.1 and 6.10.20260622.1

[XBS-7192] - rna: fixed an issue with Live dashboard tab on web, in which admin users could not add themselves as dynamic agents to Call groups

[XBS-7194] - wim: fixed an issue with Knowledge Base in which content chunks were duplicated after data source content was changed

[XBS-7231] - rna: fixed an issue where summaries for transferred calls were continuously refreshed during conversations with agents

## Web 2.68.1.2816630 / iOS 2.68.1.511552 / Android 2.68.1.551552 Date: 17.06.2026

### Improvements

[XBS-7018] - wim: updated the logic for Salesforce Partner Community integration to prevent configuration conflicts with Salesforce integration

Enabling Salesforce Partner Community in the Connectors section in WMS -> PBX -> Integrations -> Cloud Integrations automatically replaces the standard Salesforce app in the Apps section, preventing potential conflicts between the two. Also, this gives possibility to manage such settings as Tab view display, make integration available to some users only, etc. Also, the Tab View now uses My Salesforce as the default naming of the tab in x-bees.

[XBS-7144] - rna: added percentage ratio display across Revenue Intelligence data overview views

[WMS-21856] - ai: added real-time translation for call and conference transcriptions

How-to:

- During the call/conference, click the Transcription button in the top-right corner 
- Click the Translate button 
- Select the desired language 

Note: Supported languages are English, Italian, French, German, and Spanish

[WMS-26222] - ai: added possibility to edit predefined system configurations (e.g. Customer Satisfaction, Sentiment, etc.) in Revenue Intelligence settings in WMS allowing you to tailor AI metrics to specific business needs

How-to:

- Go to WMS → - *PBX*→- *Integrations*→- *Cloud integrations*→- *Revenue Intelligence*
- Choose the configurations with the label System, which you wish to edit and click on it 
- Click Edit 
- Make the necessary changes and click Save 

### Fixes

[XBS-5559] - rna: fixed an issue where an extra badge overlapped the presence indicator in chats on web and mobile

[XBS-6981] - rna: fixed an issue where global ACL restrictions could override specific user permissions on web and mobile

Also covered by ACL "Call Reject" option (applied the same logic as in Legacy Collaboration - managed by ACL can/not set Call waiting)

[XBS-7013] - rna: fixed a rare issue where conversations appeared empty on macOS after waking from sleep until the web page was refreshed

[XBS-7078] - xbx: fixed an issue where Wilma used incorrect date ranges for YTD (year-to-date) call searches

[XBS-7087] - rna: fixed an issue on iOS where switching to speakerphone before an outgoing call was answered did not work

## Web 2.67.1.2790593/ iOS 2.67.1.507807 / Android 2.67.2.508893 Date: 10.06.2026

### Improvements

[XBS-5526] - rna: added possibility to set a mandatory delay before booking in Kite Calendar, preventing last-minute meetings by requiring a specified gap (in minutes, hours, or days) before a slot becomes available

How-to:

- Go to Settings -> Kite Settings -> Calendar Settings tab 
- Navigate to the Minimum notice before booking field and choose the necessary option 
- Click Save 

[XBS-5809] - rna: added automatic scrolling to the first unread message when opening a conversation on web and mobile

[XBS-6792] - rna: improved the pop-up when adding agent to service on the Live Dashboard -> Services tab by adding dynamic lookup, making it easier to find users and preventing errors caused by typing incorrect extensions/ text

[XBS-6851] - xbs: improved auto logging feature for Salesforce integration with x-bees on web by adding the following notifications:

- the notification about logging of the call to Salesforce 
- the notification after the call ends, with a countdown timer that indicates exactly when the call will be logged 
 Note:

- The notifications are displayed in Salesforce section on the Info Frame. 
- Depending on the call logging type selected in WMS (Smart logging or manual matching) the notifications may vary. In case of manual matching, Log task window automatically opens where agent can fill out the necessary data and click Confirm to log the call. 
 Also, for manual matching option, the notification with countdown timer also includes the Edit button which allows for editing the entry.

[XBS-7019] - xbs: added possibility to create Feature Request Cases within Salesforce Partner Community integration with x-bees

[XBS-7052] - xbs: added possibility to configure permissions in a way to allow call summaries transferred by AI Voice Agent while hiding transcription and Wilma buttons during active calls

How-to:

- Go to WMS -> Users -> Groups -> ACL permissions 
- Set Can see transcription summary 
- Set Cannot see call recordings and Cannot use Wilma and AI Assistant 
 Also, updated the logic of the ACL permission Can/ cannot use Analytics. When the permission is forbidden, the Analytics button is not displayed.

### Fixes

[XBS-6850] - rna: fixed an issue in which remote calls didn’t trigger pop-up URL on web

[XBS-6881] - rna: fixed an issue that caused errors and chat unresponsiveness when uploading .doc, .docx, or .xlsx files to Wilma on the web

[XBS-6925] - rna: fixed an issue where the incoming call popup could display an incorrect avatar when the native application was running in the background

[XBS-7002] - rna: fixed an issue causing unexpected scrolling and navigation to Inbox on mobile app

[XBS-7041] - rna: fixed an issue that could cause dual ringback tones on outbound calls when the SIP Ringing message was received after early media

[XBS-7162] - rna: fixed an issue in which Android mobile app stopped playing the configured Wildix ringtones and either reverted to the system default notification sound or remained silent during incoming calls

## Web 2.66.1.2771515 / iOS 2.66.1.504830 / Android 2.66.1.504830 Date: 3.06.2026

### Improvements

[WMS-25968] - xbs: made some improvements for Live Dashboard in x-bees:

- Added the call Forward button. The button routes the call according to the user’s Dialplan. 
- Added the field ACL Group to Call group strategy settings in WMS -> Dialplan -> Call Groups, which allows to define which ACL group the Service (Call group) belongs to. The ACL permission Manage CallGroup allows admins to assign a specific ACL group for individual Call Groups. The ACL gives the possibility for non-admin users to manage Call Group members in x-bees Live Services, e.g. pick-up or transfer incoming calls in queues. The support starts from 7.08.20260521.1 . Temporary limitation: adding or removing dynamic members to call group requires user to be of admin type. 
- The ACL can/ cannot view calls of users allows to manage calls of which services (Call groups) are visible to users. 
 By default, all services (Call groups) are visible if permissions are not forbidden via ACL.

[XBS-7026] - kite: added possibility to enable guest-only access for Kite widgets so that guests are prompted to only enter their name when accessing the widget

How-to:

- Go to WMS -> PBX -> Integrations -> Cloud integrations -> Kite 
- Choose the necessary widget -> navigate to the Access Settings -> enable the option Allow only anonymous sessions 

[XBS-6973] - rna: unified the UI of the Create contact window on the History, Live Search, and Phonebook pages on web for a consistent user experience

### Fixes

[XBS-6644] - xbs: fixed an issue in which chats were not displayed in the Playlists section on the Library page in Revenue Intelligence

[XBS-7037] - ri: fixed an issue where participant names in Revenue Intelligence filters were incorrectly displayed as user extensions after saving dashboard changes

[XBS-7046] - rna: fixed an issue where media on mobile was lost on trunks that support only the alaw codec

[XBS-7053] - rna: fixed an issue where right-click Call actions in Contacts and Favorites were not working on web

[WMS-26143] - wizy: fixed an issue where users could not automatically join a meeting via a shared link after selecting "Continue as Guest"

## Web 2.65.1.2742754 / iOS 2.65.1.501150 / Android 2.65.1.501150 Date: 27.05.2026

### Improvements

[XBS-5962], [XBS-6008], [XBS-6895] - ai: made some improvements to Revenue Intelligence configuration in WMS, which include:

- Added Settings button on Revenue Intelligence page in WMS -> PBX → Integrations → Cloud integrations, which allows to 1) disable Revenue Intelligence globally; 2) select a default AI model; 3) set conditions 
- Updated Revenue Intelligence UI in WMS: added “system” label to configurations that are set by default and cannot be changed; added possibility to search configurations and filter them by the status Enabled/ Disabled/ Paused. 
- Added a set of Quick Start Templates which you can use to create new configurations. 
- Added possibility to choose AI model for each configuration in the Advanced Settings section. The AI model selected for the configuration has higher priority than the default model set in global settings. 
- Added the option Adaptive to the Fields section -> Choice, which allows to add custom choice options, extracted from calls/ meetings. When the system detects such options, it adds them to under Adaptive options field. 
- Extended the list of Conditions (e.g. PBX, Group, Department, Tags, Service, etc.). Conditions can be set for each individual configuration or in global settings (global settings have higher priority). 
- Introduced a Custom date range option under the Analyze tool. 
- In Configuration test, added possibility to test different AI models and compare their results. 
- Added an Execution group option in Advanced Settings to separate group requests for better performance. 

[XBS-6699] - sys: removed the legacy https://x-bees.biz/ domain

[XBS-6816] - rna: added support for the "Popup URL" feature on the web, allowing users to configure a URL to open automatically during calls and select trigger behavior for incoming and outgoing calls

How-to:

- Go to Settings -> Calls 
- Enable the option "Popup URL" 
- Enter the URL in the field below 
- Select the trigger behavior for Incoming call and Outgoing call: Ringing, Answer, or On-Click 

[XBS-6909] - rna: improved the Wilma button behavior in chats and calls so that the conversation state is now preserved when switching between tabs on web

[WMS-25739] - wizy: added a notification to inform users when network conditions are blocking the process of joining the videoconference

- Also, added the Network tab in More options -> Settings, which allows to run test to check the connection 

### Fixes

[XBS-5577] - rna: fixed an issue on mobile where microphone permission request was incorrectly displayed to guest user after moving the app to the background from the Settings page or after logout

[XBS-6947] - rna: fixed a rare issue on Android where the chat input field floated mid-screen after returning to the app from the background

[XBS-6999] - rna: fixed an issue when it wasn’t possible to add AI Chat Agent to WhatsApp conversation

[XBS-7028] - ai: fixed an issue in which Dashboard sharing dialog in Revenue Intelligence didn’t display the latest shared information

[WMS-25754] - wda: fixed a rare issue in which the conference record was not created in Revenue Intelligence

## Web 2.64.1.2716697/ iOS 2.64.1.497611 / Android 2.64.1.497611 Date: 20.05.2026

### New Features

[XBS-6312] - sf: added possibility to enable Salesforce tab, which allows to view Salesforce cases right in x-bees

- Go to WMS -> PBX -> Integrations -> Cloud Integrations -> Salesforce integration 
- Navigate to the Integration type section 
- Switch to the Tab view tab and enable it 
- Save the changes 

Once the tab view is enabled, you can see the Salesforce tab on the left-side panel in x-bees. On the tab, you can view and edit cases.

Documentation: How to Enable and Use Salesforce Tab in x-bees

[XBS-6334] - rna: added integration of Wilma with Salesforce and Salesforce Partner Community, which allows users to request Salesforce / Salesforce Partner Community data, such as contact details, tasks, and opportunities right within x-bees

Documentation: https://wildix.atlassian.net/wiki/x/AYDRhg

[XBS-6896] - rna: added new ACL permissions to control user access to Wilma, AI Assistant, Revenue Intelligence, and Transcription summary features

- Can/Cannot use Revenue Intelligence 
- Can/Cannot use Wilma and AI Assistant 
- Can/Cannot see transcription summary 

Note:

- The Transfer Summary button visibility depends on ACL permissions: - Hidden if the user does not have the "Wilma and AI Assistant" permission and does not have the "See transcription summary" permission 
- Visible but disabled if the user has Wilma access but does not have the "See transcription summary" permission 
 
- Available starting from WMS 7.08.20260512 

### Improvements

[XBS-6682] - wms: updated the client integration creation flow to support both Info view and Tab view display types in a single integration

[XBS-6945] - rna: added the ability to search for colleagues and contacts while adding a Speed dial entry in Favorites on web

### Fixes

[WMS-25857] - rna: fixed an issue where the Kite widget was not including dynamic group members when creating a conversation

[XBS-6070] - rna: fixed an issue where the Kite bot did not respond when a user from the same organization started a Kite chat with it

- Also, fixed an issue where the bot stopped responding after being re-added to the chat 
- Fixed an issue where the bot stopped responding in Kite chats after transferring the conversation to agent/agents and leaving the chat. If the bot was added back to the conversation and tagged again by a user from the same organization as the bot, it previously did not respond. The bot now correctly handles messages and responds after being re-added to the chat. 
 Generative AI bot response rules in simple group chats:
- In a group chat where only the user and the Generative AI bot are participants, the bot responds to user messages without requiring @mention or Quote 
- After adding additional participants, the bot continues responding until another participant sends a message in the chat. After that, the bot responds only when explicitly mentioned via @mention or when replying to the bot’s message using Quote 
- In group chats created with three or more participants, where one of the participants is a Generative AI bot (or when a Generative AI bot is added to an existing chat with other participants), the bot responds only when explicitly mentioned via @mention or when replying to the bot’s message using Quote 
 Generative AI bot response rules in kite chats:
- If a kite chat has only two participants and one of them is the bot, the bot always responds, regardless of the other participant’s company 
- If another internal user from the same organization as the bot is added to the chat, the bot responds to users from the same organization as the bot only when explicitly mentioned via @mention 
- If an external user is added to the chat, the bot continues responding to that external user normally without requiring @mention or Quote 

[XBS-6916] - rna: fixed an issue on web and mobile where it was impossible to see draft messages in the conversation list for old conversations in the chat list (e.g. positioned 30 or lower)

[XBS-7021] - ai: fixed an issue where it was impossible to share a dashboard in Revenue Intelligence

## Web 2.63.1.2689956 / iOS 2.63.1.493666 / Android 2.63.1.493666 Date: 13.05.2026

### New Feature

[XBS-6450] - rna: added possibility to enable anonymous sessions for Kite widgets on web and allow users to participate in conversations without providing an email address, by signing in as a guest user

How-to:

- Go to WMS -> PBX -> Integrations -> Cloud integrations -> Kite 
- Choose the necessary widget -> navigate to the Access Settings and enable the option Allow anonymous sessions. 
 When the option is enabled and guests sign in, they can use the option "Continue as a guest" and enter their name only.

Note:

- The option applies only to Kite website widget and direct channel links (for direct channel links the option is enabled by default). 
- Anonymous sessions are temporary and are not saved once the session is closed. Conversation history is not saved even if the anonymous user registers with their email address afterwards. 
- Anonymous users do not have access to calendar. 

[XBS-6869] - rna: added the possibility to enable/disable the "Keep Call Dialog after the call" feature via WMS

How-to:

To enable, go to WMS -> PBX -> Features, and enable the “Keep Call Dialog after the call”

Note:

- By default this feature is disabled 
- The feature setting is available starting from WMS 7.08.20260427 

### Improvements

[XBS-6664] - rna: improved audio playback on the mobile History tab by using the in-app player instead of requiring external applications to play files

[XBS-6744] - rna: improved the logic to preserve filters selected or data entered on the Contacts (Colleagues tab and tab selection), Favorites (edit mode state) and Call History tabs after switching between tabs

[XBS-6966] - rna: added the option of starting a conference during a call on web from the More options menu to the Transfer menu for better user experience

[WMS-25469] - xbs: added the possibility to assign an ACL group to an AI Agent, defining who can view the agent's conversations and recordings in analytics

How-to:

- Go to WMS -> PBX -> Integrations 
- Choose AI Agent 
- In Additional settings -> ACL Group, select the PBX ACL group 
- Click Save 

Note: Only admins can assign a PBX ACL group to an AI Agent

[WMS-26076] - wizy: improved the logic so that users joining the conference via dial-in, have the correct transcription language

### Fixes

[XBS-5158] - rna: fixed an issue on web when in some cases search inside conversation displayed incorrect items when switching between results

[WMS-26124] - sys: fixed Internal server error for Revenue Intelligence, Analytics, Live view (Calls), live transcriptions and Colleagues status when in a call/conference, which occurred if PBX was accessible only via custom secure port

## CLASSOUND 2-Way Messaging Analytics Date: 07.05.2026

### New Feature

[WMS-25690] - classound: added CLASSOUND 2-way messaging Liveboard in x-bees Analytics -> Liveboards, which displays messages by direction, channel type, messages stats including message ID, destination number, source number, conversation ID, direction, delivery status, as well as messages quantity by extension

Documentation: CLASSOUND 2-Way Messaging Analytics

## Web 2.62.1.2669009/ iOS 2.62.1.490836 / Android 2.62.1.490836 Date: 06.05.2026

### Improvements

[XBS-6769] - dev: improved call transfer behavior on web by enabling attended transfer as the default action when using drag-and-drop on the Favorites and Colleagues tabs

- It is possible to change the default behavior: when the Direct transfer checkbox is enabled in Function Key settings, the blind transfer is performed when transferring a call via drag-and-drop on the Favorites tab. 

[XBS-6901] - rna: improved user experience on web by preventing the application from switching to the Inbox tab when answering an incoming call from other tabs

### Fixes

[XBS-6527] - rna: fixed an issue where Phonebooks were not loading for users connected to a PBX accessible only via a custom secure port

[XBS-6818] - rna: fixed an issue where the called colleague's name was missing from the incoming call popup when the "View calls" function key for this colleague was enabled

[XBS-6942] - rna: fixed an issue on web and mobile in which it was not possible to find Salesforce contacts in x-bees in case the phone numbers contained country prefix

[XBS-6950] - rna: fixed an issue on iOS where incoming calls received while the app was in the background could be automatically dropped

## Cloud Analytics (CDR-View 2.0), Meeting and Conference Analytics Date: 04.05.2026

### Improvements

[IT-7352] - ca: added Agents and Chat/ Conference stats tabs to ChatView and MeetingView Liveboards in x-bees Analytics, and added Calculation, Time Bucket, Hour of day filters

[IT-7636] - ca: added the Join column to Conversation Analytics → Data Grid, which allows to join conversations

- Clicking on the conversation links now opens the relevant Revenue Intelligence page with conversation insights. 

[IT-8061] - ca: improved map view on the Home tab in CDR-View 2.0 by grouping data by location instead of country for more detailed information

Documentation: __How to use Cloud Analytics (CDR-View 2.0)__

## Web 2.61.1.2646503 / iOS 2.61.1.487646 / Android 2.61.1.487646 Date: 29.04.2026

### Improvements

[XBS-6838] - rna: improved behavior of the "Call control mode" feature to ensure it remains enabled after logout on web

[WMS-25107] - wizyHw: removed Wizywebinar from the list of integrations in Wizyconf Station

[WMS-25549] - rna: added the ability to disable chat functionality on web and mobile 

How-to:

- To disable chat functionality, add the following parameter to the /rw2/etc/env.custom.ini file: COLLABORATION_CHAT_ALLOW=false 

Limitation: In a WMS network with multiple PBXs, disabling chat on one PBX does not disable it on other PBXs

[WMS-25721] - wizy: improved general performance and stability

### Fixes

[XBS-6875] - xbs: fixed an issue in which it was not possible to find Salesforce contacts in x-bees in case the phone numbers contained country prefix

[XBS-6913] - rna: fixed an issue in which JPEG streaming from doorphone froze in some cases

[XBS-6917] - rna: fixed an issue on iOS, when after trying to share logs to any conversation, the Share to app feature stopped working until the app was restarted

[XBS-6933] - rna: fixed an issue in which the app remained disconnected after restoring internet connection, unless the page was reloaded

[WMS-25018] - wizy: fixed one-way audio issue that occurred after switching from WiFi to mobile data on iOS

## Web 2.60.1.2621691 / iOS 2.60.1.484676 / Android 2.60.1.484676 Date: 22.04.2026

### New Features

[XBS-6492] - rna: added support for Dark mode on Android

[XBS-6692] - rna: added possibility to select and forward multiple messages at the same time on web and mobile

How-to:

- Long-tap any message (on mobile) or click the message menu (on web) and choose Select 
- Select several messages 
- Click Forward, choose the person or group you want to send them to, and click Send. 

### Improvements

[MS-15488] - xbs: renamed Sales Intelligence to Revenue Intelligence

[XBS-6886] - rna: improved performance and stability of call functionality on Android

### Fixes

[XBS-6751] - xbs: fixed an issue where Wilma could not load the call context or would freeze when reopening a chat with Wilma from the Wilma history

[XBS-5508] - rna: fixed an issue where the incoming call dialog was significantly delayed or missing when the app was resumed from the background on some mobile phones

[XBS-6740] - rna: fixed an issue where DTMF did not work during call transfer on web

[XBS-6873] - rna: fixed an issue in which unread message counter did not update correctly when receiving push notifications on iOS

[WMS-25673] - xbs: fixed a rare one-way audio issue that occurred after an attended transfer of an external call from one x-bees user to another

- The fix is available starting from WMS Beta 7.08.20260413.1. 

[WMS-25793] - wms: fixed an issue in which Microsoft Teams Offline status was incorrectly mapped to Away in x-bees instead of Offline, as configured in presence mapping

## Web 2.59.1.2599329 / iOS 2.59.1.482064 / Android 2.59.1.482064 Date: 15.04.2026

### Improvements

[WMS-25787] - wizy: extended the list of languages supported for transcription in the conferences

- Added support for Estonian and Turkish languages 

### Fixes

[XBS-6638] - rna: fixed an issue where audio quality decreased after multiple calls without refreshing the page

[XBS-6791] - rna: fixed an issue where search in conversations worked inconsistently on web and mobile

[XBS-6864] - rna: fixed an issue where Call ended notification was displayed to a user who did not answer a call group call

## AI Voice and Chat Agents, Web 2.58.2.2584106 Date: 09.04.2026

### Improvements

[WMS-25087] - ai: added support for Google Gemini models for AI Voice and Chat Agents, which can be selected in Additional Settings -> Model

[WMS-25108] - ai: updated AI Agents interface, adding support for knowledge bases and Wilma tools, updated traces viewer, and enhanced configuration options for AI agents.

- Important: The Third Party Function feature in AI Agents has been deprecated and replaced with Webhook option within Wilma Tools. 

For more information, check out the guides:

[XBS-6117] - wms: added Knowledge Base integration for Chat and Voice AI agents, which allows to integrate external knowledge sources (files, Confluence, Google Drive) to enhance AI responses

For setup and usage details, see the documentation: https://wildix.atlassian.net/wiki/x/A4CbcQ

[XBS-6576] - xbs: added Wilma button to conversation header, message menu, and active call dialog, allowing users to access chat and call assistance directly from Inbox

- Requirements: x-bees-Standard / x-bees-SuperBee subscription plan 

[XBS-6537] - ai: released Wilma Tools, which is a set of tools for AI Agents (AI Voice and Chat Agent, Wilma) that enable integration with external APIs via webhooks, connection to MCP servers, and built-in functions for sending messages, SMS, emails, and performing web searches

- You can access Wilma Tools in WMS -> Integrations -> Cloud Integrations -> AI section -> Capabilities 
- Webhook option within Wilma Tools replaces the Third Party Function feature in AI Agents. 

For more information, check out the guide: https://wildix.atlassian.net/wiki/x/AwCsdQ

### Fix

[XBS-6853] - xbs: fixed a regression after XBS-6640 in which: 1) call popup after performing an attendant transfer was displayed to an external user; 2) there was no ringtone during an incoming call if there was the Ended call dialog open in the conversation list

## Web 2.58.1.2580722 / iOS 2.58.1.479814 / Android 2.58.1.479814 Date: 08.04.2026

### New Features

[WMS-24956] - rna: added a new Services tab in the Live Dashboard section, which provides real-time monitoring and management of call group calls (similar to Live view in x-caracal)

How-to:

- Go to Live section 
- Select the new Services tab 
- When first accessing the tab, you need to select one or more services (call groups) you want to monitor. 

The Services tab allows you to:

- View all live incoming and outgoing calls for the selected services. 
- See a list of agents in each service, along with their current status (available, ringing, paused, etc.). 
- Interact with agents directly from the dashboard: start a chat, make a call, or change their presence. 
- Add or remove dynamic agents from services (static agents cannot be removed). 
- Use other tools, such as blind transfer and call pickup for ringing calls. 

Requirements:

- For the tab to be displayed, users should have the necessary license: 
- x-bees-SuperBee subscription plan 
- ACL permission “Can Modify presence” for modifying user presence.
