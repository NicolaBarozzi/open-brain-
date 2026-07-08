---
titolo: "Features & Updates | Blockbrain B2B Guide (EN)"
url: "https://docs.blockbrain.ai/news/features-and-updates"
fonte: "docs.blockbrain.ai"
autore: null
data_articolo: "2026-07-01"
recuperato_il: "2026-07-08"
email:
  - "2026-05-27 — dist*ll daily digest <andrew@distll.ai>"
stato: "ok"
---

# Features & Updates | Blockbrain B2B Guide (EN)

# Features & Updates

This section provides release notes and the latest product updates from Blockbrain. Users can learn about new features, improvements, and fixes, ensuring they fully leverage the tool's capabilities.

**Product Updates, July 1st, 2026**

**Product Updates, July 1st, 2026**

#### 1. AI Models

**1.1 **Mistral Medium 3 & Mistral Small 3.1 now Available

**1.1**Mistral Medium 3 & Mistral Small 3.1 now Available

Two new AI models from Mistral are now available in the model dropdown for your bot and workflow configurations: **Mistral Medium 3** for high-performance tasks and **Mistral Small 3.1** as a fast, cost-efficient option for everyday use. Both models are hosted in the EU, ensuring full compliance with European data residency requirements while giving you greater flexibility in choosing the right model for your needs.

**1.2 **New Model: Codestral 2

**1.2**New Model: Codestral 2

**Codestral 2** is now available as a new AI model in the model dropdown, specifically optimized for code-related tasks such as code generation, review, and explanation. Hosted in the EU for full data residency compliance, it provides a powerful option for technical workflows that benefit from a model purpose-built for programming and development use cases.

#### 2. Administration & General

**2.1 **API Key Usage Limits

**2.1**API Key Usage Limits

Each API key can now have its own Compute Block consumption limit, configurable on a **daily**, **weekly**, or **monthly** basis - giving you full control over how much each integration or application can~~ ~~consume. Once the set limit is reached, further CB consumption through that API key is automatically blocked until the next period begins, helping you prevent unexpected overuse and manage your budget more effectively. For more information, please visit Cost Control.

**Product Updates, June 23rd, 2026**

**Product Updates, June 23rd, 2026**

#### 1. Agents & Bots

#### 1.1 Bot Model Management for Admins

The AI Model Settings in the bot configuration have been redesigned - admins can now define a required base model (LLM or Agent) that loads by default, and use simple toggles to control whether users are allowed to switch between LLMs, Agents, or personal Agents.

When model switching is enabled, admins can further restrict the selection to a curated list of approved models; if no specific models are selected, all models available to your organization are offered automatically.

**1.2 Gemini 3.5 Flash & Gemini 3.1 Flash (Lite) Now Available for My Agent**

**1.2 Gemini 3.5 Flash & Gemini 3.1 Flash (Lite) Now Available for My Agent**

You can now select **Gemini 3.5 Flash** and **Gemini 3.1 Flash (Lite)** - both EU hosted via Google - directly from the model picker when configuring your personal agent. Both models are optimized for speed and efficiency, making them ideal for tasks where fast response times matter.

**Gemini 3.5 Flash** delivers strong overall performance, while **Gemini 3.1 Flash (Lite)** offers a lightweight, cost-efficient alternative for simpler tasks and high-volume use cases.

**1.3 OAuth 2.1 Authentication for MCP Servers**

**1.3 OAuth 2.1 Authentication for MCP Servers**

When connecting external tool servers (MCP servers), you can now authenticate using **OAuth 2.1 Client Credentials** - the standard method for secure service-to-service connections. This extended OAuth 2.1 support ensures full compliance with the current security standard, giving you a dedicated authentication option with fields for your token endpoint, client ID, client secret, and optional scopes.

Once configured, the platform automatically handles token renewal in the background, so your connected tools stay operational without any manual re-authentication.

#### 2. AI Models

**2.1 Mistral Medium 3.5 and Large 3 Now Available**

**2.1 Mistral Medium 3.5 and Large 3 Now Available**

**Mistral Medium 3.5** and **Mistral Large 3** - both EU hosted via Mistral - are now available. This models offers high-performance AI options with full data residency in the EU, ideal for users with regional compliance requirements.

LLMs must first be activated by your Admin. Bot Editors then need to favorite (★) the models in each bot to make them selectable for users.


#### 3. Administration & General

#### 3.1 **Automatic User Provisioning via Azure AD**

**Automatic User Provisioning via Azure AD**

When your organization manages access through Azure AD (Entra ID) group sync, new users added to a synced group can now be **automatically provisioned and invited** - no manual confirmation step required. This enables full lifecycle automation so your team members get access as soon as they're added to the right group in Azure AD.

This feature is controlled by an opt-in setting per organization and is disabled by default, ensuring that only organizations that explicitly want automatic provisioning have it enabled.

**Product Updates, June 19th, 2026**

**Product Updates, June 19th, 2026**

#### 1.1 AI Models: AWS Bedrock

**1.1 New Provider: AWS Bedrock (EU-hosted)**

Anthropic's Claude models are now available through **AWS Bedrock** as an additional hosting provider on the Blockbrain platform. All Claude models on Bedrock are hosted in the **European Union** and carry the same data protection guarantees you already rely on:

- **EU data residency**— all inference runs on EU-hosted Bedrock endpoints.
- **Zero data retention**— your prompts and outputs are not stored by AWS.
- **No training on your data**— your data is never used to train models, consistent with our existing providers.

The following Claude models are now available via AWS Bedrock (EU-hosted):

**Claude Opus**

- Claude Opus 4.8 
- Claude Opus 4.7 
- Claude Opus 4.6 
- Claude Opus 4.6 (Low) 
- Claude Opus 4.6 (Medium) 
- Claude Opus 4.6 (High) 
- Claude Opus 4.6 (Max) 

**Claude Sonnet**

- Claude Sonnet 4.6 
- Claude Sonnet 4.6 (Fast) 

**Claude Haiku**

- Claude Haiku 4.5 
- Claude Haiku 4.5 (Fast) 

**1.2 15% Lower Compute Block Consumption**

Running any of these Claude models via AWS Bedrock consumes **15% fewer Compute Blocks (CB)** than the equivalent Anthropic models hosted via Google / Vertex AI — same models, same output quality, lower CB cost.

LLMs must first be activated by your Admin. Bot Editors then need to favorite (★) the models in each bot to make them selectable for users.


**Product Updates, June 17th, 2026**

**Product Updates, June 17th, 2026**

#### 1. Agents & Bots

#### 1.1 Interactive Agent Questions

When the AI agent needs your input - for example, to clarify your intent or choose between different approaches - it can now present you with an interactive multiple-choice picker directly in the chat, instead of asking in plain text.

You can select answers using clicks or keyboard shortcuts, skip questions you don't want to answer, or type a custom response via the "Something else" option - giving you full control over how the agent proceeds with your task.

#### 1.2 Agent Creation Form

You can now build your own custom AI agents directly from the Agent Start Page using a new, easy-to-follow creation form. Simply give your agent a name, select a base model, write a prompt, and optionally add tools, knowledge sources, a description, category, icon, and adjust the creativity level - then hit "Create Agent" to deploy it instantly to your workspace.

#### 1.3 Voice Mode for Agents

You can now interact with your agents entirely through voice commands, making it easy to use them on the go or while multitasking. Voice Mode supports all agent features, including tool calls such as querying emails, Salesforce, and other connected integrations - no manual input required.

#### 2. AI Models

#### 2.1 Faster AI Model Availability

New AI models - including LLMs and embedding models - will now be activated across all organizations at once, meaning you'll get access to the latest models faster and more consistently.

After a new LLM is released it will be automatically possible for admins to activate it via Admin - AI Models. The toggle will be available for the admin to activate the LLM or Embedding Model.

When a model is deprecated, the platform now automatically ensures a smooth transition by prompting for a replacement model, so your workflows continue without interruption.

#### 3. Administration & General

#### 3.1 Group-Level Usage Limits

Admins can now assign Compute Block (CB) usage limits directly to user groups (including Azure AD Groups), so every member of that group automatically inherits the same limit - eliminating the need to set limits one by one for each user.

If a user belongs to multiple groups with different limits, the most generous limit applies automatically; any personal override set for a specific user will always take priority over group-level limits.

Note: In order for Azure AD Groups to be included, the groups first must be synced with the Blockbrain platform.


**Product Updates, June 10th, 2026**

**Product Updates, June 10th, 2026**

#### 1. Agents & Bots

#### 1.1 Bot Export

Admins can now export a detailed summary of the bots' configurations directly from the platform - individually or in bulk across all bots on your tenant.

Each export includes key information such as the bot name, system prompt, selected LLM model, connected knowledge bases, user access permissions, and predefined prompts, making it easy to share with internal stakeholders like compliance teams, works councils, or data protection officers without needing any technical background.

#### 1.2 **Favorite Agents in the Sidebar**

**Favorite Agents in the Sidebar**

You can now customize your sidebar by adding your preferred agents as favorites for quick access. Simply click **"Add Agent"** in the sidebar to browse all available agents - switch between Pre-Built Agents and My Agents, search, filter by type, and toggle agents on or off to instantly add or remove them from your sidebar shortlist.

Starting a new chat directly from the agent selection will also automatically add that agent to your favorites, so your sidebar always reflects the agents you actively use.

#### 1.3 **AI Task Checklist**

**AI Task Checklist**

When handling complex requests, the AI assistant can now automatically create a step-by-step plan and display it as a live checklist directly in your chat. Each step is clearly marked as ○ pending, → in progress, or ✓ completed - updating in real time as the assistant works through the task.

This gives you full transparency into what the assistant is doing, how far along it is, and what's still left - without needing to ask for a status update.

#### 1.4 **Outlook Agent: Access to Archived & Deleted Emails**

**Outlook Agent: Access to Archived & Deleted Emails**

The Outlook Agent can now access emails that Exchange Online retention policies have moved to your **In-Place Archive Mailbox** or **Recoverable Items** (deleted emails) — areas that were previously invisible to the agent. This means you can now search and retrieve older or deleted emails directly through the agent, without having to leave the platform.


Setup required:Users need to authorize a one-time additional connection for archive access. Your administrator will provide instructions if this applies to your organization.

#### 1.5 MS Teams Agent: Meeting Transcripts

The MS Teams Agent can now read your meeting transcripts directly within the platform and provide you with a clear, concise summary of what was discussed.

Simply ask the agent about a specific meeting, and it will pull the transcript automatically - saving you time by highlighting key points, decisions, and action items without the need to re-watch recordings or scroll through lengthy notes.

#### 1.6 **MCP Connector Access Control**

**MCP Connector Access Control**

To protect against unauthorized usage and unexpected costs, **MCP connectors can now only be configured in bots by workspace administrators**. Builders and Pro-Users will no longer be able to add or view MCP connection settings when creating or editing bots — they will see a clear message directing them to contact their workspace administrator.

Existing bots that already use MCP connectors continue to work normally for all users — this change only restricts **who can set up** MCP connections, not who can use bots that rely on them.

#### 2. AI Models

#### 2.1  **New Embedding Model: Gemini Embedding 2**

**New Embedding Model: Gemini Embedding 2**

We've added **Gemini Embedding 2** to the list of available embedding models on the platform. You can now select it from the Embedding Model dropdown when configuring how your documents and data are processed for search and retrieval.

#### 3. Further Updates & Bug Fixes

#### 3.1  **Fixed Incorrect "Connection Required" Warning on Agents**

**Fixed Incorrect "Connection Required" Warning on Agents**

We fixed a bug introduced in the previous release where certain agents — such as the Research Agent and Atlassian Agent — incorrectly displayed a yellow "Limited Functionality – Connection Required" warning banner, even though all necessary tools were already enabled and no additional connection was needed.

The root cause was a faulty connection status check that falsely flagged agents as incomplete. This has been corrected — agents now accurately reflect their connection status, and the misleading warning no longer appears.

**Product Updates, May 27th, 2026**

**Product Updates, May 27th, 2026**

#### 1. Agents & Bots

#### 1.1 Grouped Model Picker

Large Language Models are now grouped in the chat model picker for easier discovery and selection. Models are organised into logical categories - such as by provider or capability - so you can quickly find the right model without scrolling through a flat, unsorted list. This is especially helpful as the number of available models grows, keeping the picker clean and navigable regardless of how many options are available.

#### 1.2 **Role-gated "Share Tenant-Wide" toggle for custom agents**

**Role-gated "Share Tenant-Wide" toggle for custom agents**

Sharing custom agents tenant-wide is now restricted to Admins and Super-Admins, giving organizations greater governance over which agents are visible to all users.


Please Note: This feature can be activated per request. If you'd like to enable this restriction, please contact your Customer Success Manager.

#### 2. Knowledge Management

#### Scheduled Web Crawling

You can now set up automatic, recurring web crawls for specific URLs directly within your Blockbrain databases — for example, once a week — without any manual steps in between.

The scheduling can be set up through a simple configuration interface, and the system handles everything automatically: crawling the page at the chosen interval, updating the database with fresh content, and handling any errors along the way — so your knowledge base always stays current. For more information, please visit Web Crawling.


Please Note: If activated, automatical crawl is possible, but not the exclusion or explicit inclusion of URLs. Additionally, this feature can be activated per request. If you'd like to enable this restriction, please contact your Customer Success Manager.

#### 3. AI Models

#### 3.1 **Gemini 3.5 Flash (EU)**

**Gemini 3.5 Flash (EU)**

**Gemini 3.5 Flash** is now available EU-hosted via Vertex AI (EU Multi-region endpoint), with full compatibility across prompt formats, token limits, streaming, and function calling.

#### 3.2 **Claude Opus 4.7 (EU)**

**Claude Opus 4.7 (EU)**

**Claude Opus 4.7** is now generally available and has moved out of preview mode. It can be accessed EU-hosted via Vertex AI and US-hosted via Anthropic.

#### 3.3 **GPT 5.5 Instant (US)**

**GPT 5.5 Instant (US)**

**GPT 5.5 Instant** is now available through both OpenAI and Azure. Currently, only US-hosted deployments are available.

ℹ️ LLMs must be activated by your Admin in coordination with the Customer Success Manager from Blockbrain.

#### 4. Mobile App

#### 4.1 Cleaner Chat Interface

The mobile chat has been redesigned with a cleaner, more readable layout — agent responses now appear without bulky chat bubbles, and the message input field is smoother to use. Agent response bubbles have been removed in favour of a flat, borderless design, the message input field has been improved for smoother typing, and visual spacing throughout the chat has been refined to reduce clutter.

#### 4.2 Interactive Inline Citations

Inline citations on mobile are now interactive and visually consistent with the web version — simply tap a citation to navigate directly to the source. Previously, citations on mobile were shown as plain bracketed numbers (e.g., [1]) with no tap functionality, making it impossible to verify sources from within the mobile app.

#### 5. Further Updates & Bug Fixes

**Voice Agent**: **Reliable Speech Recognition -** Resolved critical issues with the real-time voice agent that caused unreliable speech recognition and constant interruptions during input.

**Rename Chat in Agentic Data Room **- Fixed a bug where renaming a chat session inside an Agentic Data Room did not update the displayed name in real time.

**Chat scroll during streaming responses** - users can now scroll up while a response is being generated.

**More reliable copy-agent flow** - copied agents appear correctly in sidebars and selection modals, inherited tools and logos are preserved after the first edit, and long system prompts no longer break the copy operation.

**Custom agents now support larger system prompts** (was 2.000, now more than 45,000 input tokens).

**Insights **can now be saved to Database sources.

**Improved tenant-onboarding reliability** around invitations and single sign-on.

**Product Updates, May 19th, 2026**

**Product Updates, May 19th, 2026**

#### 1. Knowledge Management

#### 1.1 **Inline citations for connected database sources**

**Inline citations for connected database sources**

We have restructured grouping of citations in the references panel and added a direct link to the connected database sources to streamline the user journey.

Also clicking a database citation now scrolls directly to the cited chunk inside the reference documents-view, instead of opening the document at the top.

#### 2. Agents & Bots

#### 2.1 **LLM Fallback mechanism on Platform and Web Component **

**LLM Fallback mechanism on Platform and Web Component**

A fallback path now keeps responses flowing when the primary configured model is unavailable, including from embedded web-component surfaces. End users see a brief notice instead of a failed request, and the fallback model takes over until the primary recovers.

**2.2 Outlook Agent with Improved Reliability and Todo-Integration**

**2.2 Outlook Agent with Improved Reliability and Todo-Integration**

Reliability and consistency of the Outlook Agent has been improved considerably. Among other things this affects searching sent items as well as the robustness of the Todo-functionality.

#### 2.3 **Outlook and Gmail Agents Attach and Embed Agent-Generated Images**

**Outlook and Gmail Agents Attach and Embed Agent-Generated Images**

Agent-generated images can now be attached and embedded inline in emails sent via the Outlook and Gmail agents.

**2.4 Transparent Notification when Switching to User Default LLM**

**2.4 Transparent Notification when Switching to User Default LLM**

When the system automatically switches to your default LLM model, you'll now see a brief, auto-dismissing notification explaining the change — so you always know which model is active and why it changed. The notification includes a "Switch default model" link that takes you directly to your default model settings, making it easy to adjust your preferences if needed.

#### 2.5 **DATEV Agent Bugfixes and Reliability**

**DATEV Agent Bugfixes and Reliability**

We conducted a set of reliability fixes for the DATEV Agent across metadata retrieval, pagination, and field mapping. Also a recurring schema error on initial metadata calls has been resolved.

**2.6 Image generation — reliability across providers**

**2.6 Image generation — reliability across providers**

Image generation now runs consistently across all supported providers. Also Agents now correctly retrieve AI-generated images stored in connected Insights.

#### 3. AI Models

#### 3.1 **GPT Realtime 2 for Voice Mode**

**GPT Realtime 2 for Voice Mode**

OpenAI's next-generation realtime voice model is now available in Voice Mode. Audio responsiveness and turn-taking quality are improved over the prior realtime model. Per-tenant rollout follows the standard new-model process.

#### 3.2 **Higher Quality Document extraction — OCR Quality Upgrade**

**Higher Quality Document extraction — OCR Quality Upgrade**

Document-extraction OCR has been upgraded to Mistral OCR 3, bringing improved extraction quality on complex document layouts. Rollout is staged per tenant.

#### 4. Administration & General

**4.1 User-Level Usage Limits**

**4.1 User-Level Usage Limits**

Admins can now define a Compute Block (CB) usage limit for each user directly in User Management, making it easy to control costs and prevent unexpected overages across your organization.

The current usage and the remaining balance can be viewed at a glance, in addition to automatic notifications when approaching their limit. They will be transparently informed when the limit has been reached. Once the limit is hit, further usage is paused until an admin adjusts it — ensuring full cost transparency and control at all times. For further information, please visit Cost Control.

#### Further Updates and Bugfixes

- **Reliability & stability fixes**— approval dialog spurious error, chat view crash on "Limited functionality" hover, BB Chat first-response race on fresh tabs, MCP connector JSON parsing, SharePoint configured-path enforcement.
- **Visibility & access in configuration views**— Data Room settings visible in Chat-only mode, Custom Agents no longer duplicated in the Available Agents list, Edit button on agent copies respecting the tenant-level "My Agents" capability.
- **Navigation & UI interaction improvements**— resizable Chat-List Navigation Sidebar, "Connection required" overlay no longer blocking chat scroll, moved chats between Agent Data Rooms reflected immediately without reload, start a new chat in a bot directly from the Agent Creator.
- **Agentic chat & content rendering**— view/download buttons on AI-generated images, consistent markdown list rendering in connected-agent answers, toast notification when the system switches to a user's default LLM.
- **Connector / data-source correctness**— SharePoint path respected end-to-end, MCP connector parsing reliability.
- **Mobile app — session retention –**The mobile app no longer signs the user out after roughly 15 minutes of inactivity. Sessions now persist according to the standard session policy.

**Product Updates, May 12th, 2026**

**Product Updates, May 12th, 2026**

**1. Agents & Bots**

**1. Agents & Bots**

With the latest changes in user flow and Agent quality, the Blockbrain Agents now moved on to the Beta phase. Nevertheless please continue to provide your feedback to our Customer Success Team.

#### 1.1 AI Model Availability Control

Bot owners and editors can now control which AI models their bot users can select, ensuring users always work with the most suitable models while helping to manage token usage.

Simply navigate to **Bot Settings → AI Models** and use the **star icon (★)** to mark your recommended models. Once at least one model is starred, bot users will only see the starred models in their model selector — keeping the experience focused and straightforward. If no models are starred, all available models remain accessible as usual. For more information, please visit AI Model and Agents Availability Control.

#### 1.2 Copy Blockbrain-Agents

Admins and Builders can now copy the agents that have been pre-defined by Blockbrain, to use them as templates, adjusting individual settings like the LLM or prompt without recreating the entire configuration from scratch. 
Step 1: click the *Edit-*link in the model / agent indicator at the top of the chat page.

Step 2: If required, edit data and submit via the button *Create Agent*. Now you will be able to select the Agent from the regular *Add Agent-*dialogue. 

#### 1.3 Change in Navigation, Unifying Create Agents and Bots

The top navigation will be changed to feature the new *Creator-*menu. Use this to directly jump into Agent or Bot creation flows.

Please note that this functionality is only visible for users with roles Builder and Admin.


#### 1.4 Slash Commands Include Skills

The "/" slash command menu now displays both Prompts and Skills as selectable categories, giving you quick access to all your reusable actions directly from the chat. For more info on skills in Blockbrain, see Skills in Blockbrain.

**Please Note**: this feature can be hidden behind a feature flag. If that is the case, the admin should get in touch with Customer Success.

#### 1.5 Copy Functionality for Source Panels

Source panels in the Extended Sources view now support a copy action, so cited content can be moved into other contexts with one click.

SharePoint connection performance, and many more UI and agent stability fixes across Outlook, Excel, OneNote, and DATEV agents.

**2. Knowledge Management**

**2. Knowledge Management**

#### 2.1 Filter Insights by Type

You can now filter your insights by type, making it easy to distinguish between AI-generated and manually created insights. Also manually created insights are protected from being unintentionally overwritten by AI-generated updates, ensuring your manual content stays intact.

#### 2.2 Notification for Completed Document Processing

You now receive an email notification when document reprocessing completes for a Knowledge Base, so you don't need to check manually.

#### 2.3 Significant Performance Improvements

Significant performance and stability improvements alongside numerous bug fixes, including reliable **file downloads **across all formats (PDF, DOCX, TXT, XLSX), **faster large database browsing**, **reduction of Voice Bot response** delays, improved drag-and-drop file uploads.

**3. AI Models**

**3. AI Models**

**3.1 GPT 5.5 and GPT 5.5 Pro** - OpenAI's GPT 5.5 and GPT 5.5 Pro are now available in the model selector, expanding the range of OpenAI options for chat and agent workflows.

**3.2 GPT 5.4 Nano (EU-hosted)** - GPT 5.4 Nano is now available as an EU-hosted option, providing a lighter and faster OpenAI model for routine tasks.

**3.3 Claude Opus 4.7 (EU-hosted)** - Claude Opus 4.7 is now available in preview mode for EU tenants in the model selector, alongside the existing Opus 4.5 and 4.6 options. 

Preview mode indicates that the model has not yet reached general availability and may still exhibit defects or unexpected behavior.


**3.4 Extended Reasoning Levels for Claude Opus 4.6** - Claude Opus 4.6 now offers all five reasoning levels — Standard, Low, Medium, High, and Max — giving you full control over response depth and speed.

The LLMs must be activated first by the responsible Customer Success Manager and the admin from your company. Please reach out to them for further information.


ℹ️ LLMs must be activated by your Admin in coordination with the Customer Success Manager from Blockbrain.

For more information on choosing the right LLM model, please visit How to Choose the Right LLM.

#### Other Updates and Bugfixes

**Faster & More Accurate Knowledge Search** - Searching through your knowledge base is now significantly faster and returns more relevant results, especially when working with selected files in a conversation.

## Product Updates, May 5th, 2026

**1. Agents & Bots**

**1. Agents & Bots**

**1.1. Improved User Onboarding for Adding Agents**

**1.1. Improved User Onboarding for Adding Agents**

As part of improving the overall agent experience, we introduce an improved onboarding flow, making the initial setup quicker and more intuitive. Our optimized workflow guides users step-by-step through the login and configuration process, when selecting an agent for the first time. This enhancement ensures all configuration requirements are apparent, allowing you to integrate agents quickly and securely into your workflow.

**1.2. Tool Connection Failures**

**1.2. Tool Connection Failures**

When a connection drops during active chat sessions, and the user needs to re-authenticate the user now gets notified immediately, reducing overall friction in the process.

**1.3. Automated Cleaning of Copied URLS for Sharepoint Agent **

**1.3. Automated Cleaning of Copied URLS for Sharepoint Agent**

An automated cleaning process will make it even easier to copy SharePoint folder links from browsers or Microsoft Teams. The auto-cleaner will be triggered automatically when users click the "Add" button, eliminating all manual steps and therefore improving the setup experience.

Note: this feature can be de-activated by your Customer Success Manager, if required.

**1.4. Working with Color Formatting in Excel Agent **

**1.4. Working with Color Formatting in Excel Agent**

The Excel Agent is now capable to apply background colors to cells. This enhancement is particularly valuable for financial and analytical use cases, improving table readability and enabling users to visually distinguish numerical data and variances at a glance.

**1.5. Working with Signatures in Outlook Agent **

**1.5. Working with Signatures in Outlook Agent**

The Outlook Agent now supports use of signatures that include images, when sending or replying to emails, when generating email drafts of forwarding messages.

**New Available Models**

**New Available Models**

The following models have been added to the available options:

- **GPT-5.5**
- **GPT-5.5 Pro**- *(slow and high Compute Block consumption; not recommended for general use)*
- **GPT Image 2**

ℹ️ LLMs must be activated by your Admin in coordination with the Customer Success Manager from Blockbrain.

**2.1. Other Updates and Bugfixes**

**2.1. Other Updates and Bugfixes**

The following models have been added to the available model options:

- GPT-5.5 
- GPT-5.5 Pro - *(slow and high Compute Block consumption; not recommended for overall use)*
- GPT Image 2 

Also a number of bugs has been fixed, among these ones regarding the handling of timestamps and dates in the Outlook Agent, the handling of prompts within the DATEV agent and occasional unexpected cut-offs in bot conversations. We also improved speech recognition and the interruption pattern for the Real Time Voice Agent.

## Product Updates, April 28th, 2026

**1. Agents & Bots**

**1. Agents & Bots**

**1.1. New Agent Panel & Workspace**

**1.1. New Agent Panel & Workspace**

As part of our initiative so bring agents to the center stage, they are now prominently displayed in the left sidebar — automatically sorted by most recent use — giving you instant one-click access to any agent, with a "See More" option to browse your full agent list when you have more than six.

Each agent features its own start page, which acts like a data room, where you can view all past conversations, start new chats and configure data sources — all from one central place. Additionally, Admins and Builders can now copy existing agents (e.g. the SharePoint Agent) to use them as templates and adjust individual settings like the LLM or prompt, without having to recreate the entire configuration from scratch.

Please note that the agent panel is available to a test group, not activated for all users by default. If that is the case and you are interested in using it, kindly get in touch with your Customer Success Manager.

**2. Performance Updates and Bugfixes**

**2. Performance Updates and Bugfixes**

We further improved performance of our retrieval- and LLM-services, fixed bugs around embedding of images in SharePoint documents and resolved migration of some remaining non-SSO accounts.

## Product Updates, April 23rd, 2026

#### 1. Agents & Bots

- Edit Responses - AI Agent responses can now be edited directly via a dedicated "Edit Answer" button in the message context menu, making it easy to adjust answers without hidden gestures or shortcuts. 
- Recognizable Logos - All agents — including SharePoint, Outlook, Salesforce, SAP, and more — now display their own recognizable logos in the selection interface for quick visual identification. 
- Assistant Message Variants - Regenerate AI responses with different LLM models, prompt styles, or web search settings, with each variant stored separately for easy comparison. 
- Skills for Recurring Task Instructions - Save recurring task instructions as "Skills" in the Knowledge Management section, where they are auto-activated when relevant and managed separately from regular Insights. 
- Override Bot Instructions - Bot Editors can now individually control per bot whether Data Room-level instructions override the bot's own instructions, with the default set to disabled for predictable behavior. 

#### 2. Knowledge Management

- Duplicates Detection - The system now automatically detects similar or identical content during upload, notifying you of potential duplicates while giving you full control over whether to proceed or cancel. 
- Load Monitoring in OCR Processing - Get an estimated processing duration before uploading and track real-time progress in the UI, keeping you informed while files are processed in the background. 

#### 3. Administration & General

- Better Overview in AI Model Management - The admin model management view is now organized into dedicated tabs for LLMs, Image Generation, and Video Generation, replacing the previous single-list view. 
- Entra ID User and Group Provisioning - A SCIM 2.0 server enables automatic push-based user and group provisioning from Entra ID, streamlining onboarding and access management. 
- Deeplinks with QR Codes - QR codes with bot links now automatically launch the native Blockbrain app on iOS and Android and navigate directly to the specified bot. 
- Performance Updates and Bugfixes - Significant performance and security improvements alongside numerous bug fixes, including resolved permission errors for web component bot mappings and an extended Top-K range for knowledge base retrieval. 

**1. Agents & Bots**

**1. Agents & Bots**

**1.1. Edit Responses**

**1.1. Edit Responses**

You can now edit AI Agent responses directly using a new "Edit Answer" button in the message context menu, making it easy to adjust and refine answers without relying on hidden gestures or shortcuts.

**1.2. Recognizable Logos**

**1.2. Recognizable Logos**

All agents — including SharePoint, Outlook, Salesforce, SAP, DATEV, Slack, and MS Teams — now display their own recognizable logos in the agent selection interface, mirroring the familiar visual identification pattern already used for LLM providers like OpenAI, Anthropic, and Google.

Note also that we are actively and incrementally improving agent performance and reliability, with numerous known issues and bugs already addressed. More improvements are in the pipeline — stay tuned for upcoming updates.

**1.3. Assistant Message Variants Using Regenerate and Different Settings**

**1.3. Assistant Message Variants Using Regenerate and Different Settings**

We now empower users to regenerate assistant responses with different settings such as LLM model, prompt style (e.g. simplify or expand), and web search on/off. With this feature each regenerated response is being stored as a separate variant, instead of overwriting the previous answer. Switch between multiple response versions directly in the UI and explore different ways to answer your questions.

**1.4. Use Skills for Recurring Task Instructions**

**1.4. Use Skills for Recurring Task Instructions**

If you are working with recurring task instructions (e.g. Code Review Patterns), you can save these as a new dedicated type called **"Skills” in the Knowledge Management section**. For each skill, a name can be defined by which it can be called. This works simply by using the *prompt /[skill name]. *In the Knowledge Management section, Skills are clearly separated from regular Insights in their **own tab**, making it easy to manage **long-term instructions** independently from everyday knowledge entries. Within the Knowledge Management pane, skills appear as a separate category in the left column, giving clear visibility into which instructions are available for the agent.

**Please Note**: this feature can be hidden behind a feature flag. If that is the case, the admin should get in touch with Customer Success.

**1.5. Override Bot Instructions When Building Bots**

**1.5. Override Bot Instructions When Building Bots**

Bot Editors can now enable or disable the "Override Bot Instructions" setting individually for each bot under **Settings → Setup**, giving you granular control over whether Data Room-level instructions take priority over the bot's own instructions. The default is set to **disabled** for all new and existing bots, ensuring your bot instructions behave consistently and predictably unless you explicitly choose otherwise.

**Please Note**: this feature can be hidden behind a feature flag. If that is the case, the admin should get in touch with Customer Success.

**2. Knowledge Management**

**2. Knowledge Management**

**2.1. Duplicates Detection**

**2.1. Duplicates Detection**

With the new duplicate knowledge detection-feature, the system automatically checks if something similar or identical already exists, so you don't end up with duplicate content in your knowledge base. It doesn't just look for exact matches — it's smart enough to catch content that covers the same topic but is worded differently. If a potential duplicate is found, you will get notified right away during the upload process, alongside additional information on the match. In any case you have full control over, whether the content is being submitted anyway or the process is cancelled.

**2.2. Load Monitoring in OCR Processing**

**2.2. Load Monitoring in OCR Processing**

With this new feature, users can get an **estimate** **of the expected duration** before uploading a file to the Knowledge Management section. During upload the system will show you real-time progress in the user interface.

This feature keeps users informed and productive while their files are being **processed in the background **and therefore gives more transparency without overwhelming the user with too many notifications.

**3. Administration & General**

**3. Administration & General**

**3.1. Better Overview in AI Model Management**

**3.1. Better Overview in AI Model Management**

The AI model management area for admins is now organized into dedicated tabs — **LLMs**, **Image Generation**, and **Video Generation** — replacing the previous single-list view, so you can find and configure models faster as the platform's model library continues to grow.

**3.2. Entra ID User and Group Provisioning**

**3.2. Entra ID User and Group Provisioning**

A SCIM 2.0 server to handle user and group provisioning from Entra ID has been implemented. This allows for a push-based sync, where users and groups are automatically sent from the Entra system.

**3.3. Deeplinks with QR Codes**

**3.3. Deeplinks with QR Codes**

QR codes with Blockbrain bot links now automatically launch the native app on iOS and Android and navigate directly to the specified bot — ideal for presentations, demos, and quick access without any additional navigation steps.

**3.4. Performance Updates and Bugfixes**

**3.4. Performance Updates and Bugfixes**

Besides vast improvements regarding performance and security of our system, we fixed numerous bugs. Among these a fix for the **Permission Denied****-error** when creating a bot mapping for a web components as well as the ability to effectively **increase the Top-K range** (e.g. from 30 to 200) and therefore the number of chunks from the knowledge base.

## Product Updates, March 31st, 2026

- User Deactivation & Reactivation - Admins can now temporarily deactivate and reactivate user accounts directly in the Admin UI, preserving all user data and settings without permanent deletion. 
- Gemini 3 Pro Preview Retired - Gemini 3 Pro Preview has been removed from the model selection. 
- Extended Context Window for Claude 4.6 Models - Claude Opus 4.6 and Claude Sonnet 4.6 now support a 1M token context window, enabling significantly longer conversations and larger document processing within a single session. 
- Clear Agent History Button & Updated Icon - A new "Clear Agent History" button is now directly accessible in the message toolbar, paired with a redesigned icon for clearer visual communication of the reset action. 
- GPT 5.4 (EU Hosted) - OpenAI's latest GPT 5.4 model is now available on EU servers, delivering next-generation performance and advanced capabilities for complex tasks. 

#### 1. User Deactivation & Reactivation 

Admins can now deactivate user accounts directly in the Admin UI to temporarily prevent platform access — for example, when an employee leaves the company — without permanently deleting the account and its associated data. Deactivated users are clearly marked in the admin overview and can be reactivated with one click, instantly restoring full login access while all settings and data remain preserved.

#### 2. Gemini 3 Pro Preview Retired 

Gemini 3 Pro Preview (Vertex AI) has been retired and is no longer available in the model dropdown or workflow configurations.

#### 3. Extended Context Window for Claude 4.6 Models 

Claude Opus 4.6 and Claude Sonnet 4.6 now support a 1M token context window — a 5x increase from the previous 200k configuration — allowing you to process significantly larger documents, maintain longer conversation histories, and handle more complex tasks within a single session.

#### 4. Clear Agent History Button & Updated Icon 

When working with Agents, you can now reset the agent conversation history directly from the message toolbar using a new dedicated button placed next to the existing LLM/Agent selector and save button — the button appears automatically in Agent conversations only. Additionally, the "Delete Chat History" icon has been updated from the previous reload-style arrows to a new "Chat Bubble with an X" icon.

#### 5. GPT 5.4 (EU Hosted) 

The new GPT 5.4 model is now available in the LLM selection. This model is hosted on EU servers and fully compatible with all platform features including streaming, function calling, and workflow configurations.

For further information, please click here.

ℹ️ This LLM must be activated by your Admin in coordination with the Customer Success Manager from Blockbrain.

## Product Updates, March 24th, 2026

- Reasoning Level Selector - A new selector in the sendbox lets you switch between sub-models of your selected LLM (e.g., "Standard" and "Fast" for Claude Sonnet 4.6), automatically adjusting to show only the variants supported by your current model. 
- Updated AI Model Logos - AI models now display their developer logos (OpenAI, Anthropic, Google) instead of hosting provider logos, making it easier to identify and differentiate between model families at a glance. 
- Unified Insight Editor - All Insight editors now share a consistent, spacious design with fullscreen mode, providing a more comfortable and unified editing experience across the entire platform. 
- Retired Legacy Models - - **GPT 3.5 Turbo, Claude 3 Opus,**and- **Claude 3.7 Sonnet**have been removed from the platform and replaced by their significantly more capable successors.
- Improved Data Retention Indicators - Data retention notifications are now less intrusive with a subtle icon during normal periods and a clear warning only in the final 24 hours before scheduled deletion. 

#### 1. Reasoning Level Selector

A new reasoning level selector in the sendbox allows you to choose between different sub-models of your selected LLM to control how the AI responds to your questions — for example, selecting Claude Sonnet 4.6 will offer you "Standard" and "Fast" as options, reflecting the model variants available from the provider. The selector automatically adjusts to display only the options supported by your currently selected model — some models may show two, three, or four levels, and for certain models the selector may not appear at all.

#### 2. Updated AI Model Logos 

The Quick Selection interface now shows the logos of the actual model developers — such as OpenAI for GPT models, Anthropic for Claude models, and Google for Gemini models — instead of the hosting provider logos, so you can instantly recognize which AI family you're selecting.

#### 3. Unified Insight Editor 

All Insight editors — whether you're creating new Insights, editing existing ones, working with Dynamic Insights, or pinning from canvas — now feature a unified, spacious design with generous text areas and a consistent action bar for a seamless editing experience. A new fullscreen mode toggle lets you maximize your workspace for longer content, hiding unnecessary UI elements so you can focus entirely on writing and editing.

#### 4. Retired Legacy Models 

**GPT 3.5 Turbo, Claude 3 Opus, **and** Claude 3.7 Sonnet** have been retired and are no longer available in the model selection, as their successors — including GPT 5, Claude 4.6 Opus, and Claude 4.6 Sonnet — deliver significantly better performance across all use cases.

#### 5. Improved Data Retention Indicators 

Data retention indicators have been redesigned for a calmer, more intuitive experience — a subtle icon now quietly informs you that a retention policy is active, while a prominent warning state and an in-chat alert banner only appear during the final 24 hours before scheduled deletion. You can dismiss the banner at any time, and opening the chat during the urgent window automatically resets the retention timer per your configured policy, returning the icon to its subtle state.

## Product Updates, March 16th, 2026

- Gemini 3.1 Pro Preview Now Available (US) - Access Google's latest Gemini 3.1 Pro Preview model for enhanced AI capabilities. 
- Custom Agents in Bot Configuration - Select shared custom agents as bot models to enable tenant-wide agent functionality. 
- Streamlined PDF Export Notifications - PDF export notifications now appear only in the app, reducing unnecessary email alerts. 
- Enhanced Research Agent - Research Agent upgraded to Claude Sonnet 4.5 for improved performance and EU data compliance. 
- Improved Code Block Display - Code blocks now extend to full screen width with enhanced copy options for better readability. 
- Dynamic Text Input & Fullscreen Mode - Message input field now expands automatically and offers fullscreen editing for longer texts. 
- Clearer System Notifications - Improved clarity and consistency of notifications for Chat and Data Room actions. 
- Strengthened Access Control - Editor role users can no longer share content, enhancing security and access governance. 
- Edit Answer Button - AI responses now include a visible "Edit Answer" button, making it easier to refine and customize chat responses without needing to double-click. 

**1. Gemini 3.1 Pro Preview Now Available (US)**

You can now select Gemini 3.1 Pro Preview as an AI model option to test early features and capabilities of Google's newest language model before its full release. This preview version is currently available exclusively for US-hosted instances.

**2. Custom Agents in Bot Configuration**

Tenant admins can now select shared custom agents as bot models in bot configuration, allowing all users within your organization to leverage these custom agents when interacting with bots. This makes it easier to deploy specialized AI capabilities across your entire team.

**3. Streamlined PDF Export Notifications**

When you export a chat or insight as PDF, you'll now receive confirmation directly in the application instead of via email, reducing inbox clutter while maintaining full export functionality. The export process continues to work exactly as before, just without the additional email notification.

**4. Enhanced Research Agent**

The Research Agent now uses Claude Sonnet 4.5 (EU hosted) instead of Claude Sonnet 4, providing enhanced model capabilities and improved performance while ensuring compliance with EU data residency requirements. This upgrade delivers better results for research tasks while maintaining data security standards.

**5. Improved Code Block Display**

Code blocks in chat view now utilize the full available screen width (similar to tables), making long code lines easier to read without horizontal scrolling. Additionally, you can now copy code in multiple formats (raw, formatted, or all) with a sticky header that remains visible while scrolling for easy access to copy functions.

**6. Dynamic Text Input & Fullscreen Mode**

The message input box now automatically grows as you type (up to 300px), making it easier to review your text before sending. For longer messages, click the "Expand" button to open a fullscreen editing mode with optimal width for comfortable reading and editing.

**7. Clearer System Notifications**

System notifications for creating, updating, and deleting Chats and Data Rooms now use clearer, more professional language with consistent formatting across the platform. These improvements make it easier to understand what actions have been completed successfully.

**8. Strengthened Access Control**

Users with the Editor role can no longer share bots or resources with other users, ensuring only Builders, Admins and Owners control access distribution. Editors retain all other capabilities including editing LLM models and configurations, while this change enhances security and compliance for enterprise environments.

**9. Edit Answer Button**

AI responses now feature a visible "Edit Answer" button that allows you to directly modify and refine bot responses in your conversations. This replaces the previous double-click interaction, making the editing functionality easier to discover and use for everyone.

## Model Updates, March 5th, 2026

- Claude Sonnet 4.6 (EU) - The latest Claude Sonnet 4.6 model is now available on EU servers, offering enhanced performance and capabilities while ensuring strict data compliance. 
- Mistral Embed Integration - Select Mistral Embed for new databases to leverage state-of-the-art semantic understanding and improved retrieval accuracy across multiple languages. 
- Smarter Long Conversation Management - Extended chat conversations are now managed more intelligently, ensuring a seamless dialogue experience even during lengthy interactions. 
- Save Chat as Insight - Compress an entire chat conversation into a concise summary and save it as an Insight with one click, making it easy to find, share, and reference key takeaways later. 

**1. Claude Sonnet 4.6 (EU)**

You can now select the **Claude Sonnet 4.6** and **Claude Sonnet 4.6 (Fast) Non-Reasoning **from the LLM dropdown to leverage its improved performance and advanced reasoning capabilities for your workflows. Hosted in the European Union, this update ensures you benefit from the latest AI technology while maintaining strict adherence to EU data privacy and compliance standards.

For further information, please **click here****.**

**2. Mistral Embed Integration**

You can now select Mistral Embed when creating a new database to leverage state-of-the-art semantic understanding for your document retrieval. This model offers improved accuracy in finding relevant information across multiple languages, ensuring your AI provides more precise answers based on your data.

For further information, please **click here.**

3. **Smarter Long Conversation Management**

Long-running conversations are now handled even more efficiently — the system intelligently validates and manages the full conversation context, including chat history, knowledge base content, and tool outputs, to keep your dialogue flowing smoothly. When a conversation becomes very extensive, older messages are automatically summarized in the background so you can continue chatting without interruption and always receive clear, reliable responses.

**4. Save Chat as Insight**

A new button in the chat header lets you compress your entire conversation into a concise summary and save it as an Insight with just one click — perfect for capturing decisions, tasks, and key findings from long chat sessions. Simply choose your destination folder, and the AI automatically summarizes the chat in the conversation's language and saves it as an Insight, complete with a confirmation linking directly to the saved result for instant access.

## Model Updates - February 18, 2026

- Sonnet 4.5 Fast Upgrade - Sonnet 3.5 has been automatically upgraded to Sonnet 4.5 Fast, delivering faster responses, higher intelligence, and improved data extraction on Vertex AI EU. 
- Claude Opus 4.6 (EU) - Anthropic's most advanced model is now available on Vertex AI EU, offering superior reasoning capabilities and enhanced performance for complex tasks. 

**1. Sonnet 3.5 has been deprecated and replaced by Sonnet 4.5 Fast**

**1. Sonnet 3.5 has been deprecated and replaced by Sonnet 4.5 Fast**

Claude Sonnet 4.5 Fast (hosted on Vertex AI EU) operates in "Non-Reasoning" mode and offers the following improvements:

- **Higher Speed**– Responses are generated noticeably faster.
- **Higher Intelligence**– Complex contexts are recognized with even greater precision.
- **Better Extraction**– Smart Image and Table Processing deliver more accurate results for new database uploads.

ℹ️ *No manual adjustment is required – the migration happens automatically.*

**2. Claude Opus 4.6 Model (EU)**

**2. Claude Opus 4.6 Model (EU)**

The new Claude Opus 4.6 model is now available, hosted on Vertex AI EU. As Anthropic's most advanced model, it delivers enhanced performance and superior reasoning capabilities.

ℹ️* This LLM must be activated by your Customer Success Manager and Admin.*

## Product Updates - January 19th, 2026

- Improved Reference Accuracy - Document references now only display sources that are actually relevant to your query and the AI's answer, eliminating irrelevant citations for clearer, more trustworthy results. 
- Optimized Smart-OCR Processing - Smart-OCR processing has been significantly accelerated to handle high-volume, time-critical document workflows more efficiently, making it practical for daily operations with large case volumes. 
- Self-Service Client Secret Management - Update and rotate client secret keys for SharePoint and Azure Group connections directly in the admin interface without requiring backend support. 
- Fixed Code Character Display Issue - Special characters in code outputs (like < and >) now display correctly instead of being converted to HTML entities (<, >). 

#### 1. Improved Reference Accuracy

References displayed with AI answers now only include documents that are genuinely relevant to your query and the generated response, rather than showing all connected knowledge base files. This improvement ensures citations point you to the actual sources used to create the answer, making it easier to verify information and explore related content with confidence.

#### 2. Optimized Smart-OCR Processing

Smart-OCR processing speed has been significantly improved to meet the demands of high-volume, time-critical workflows, enabling faster extraction of text from scanned documents and images even when processing hundreds of cases daily.

#### 3. Self-Service Client Secret Management

You can now update and rotate client secret keys for your SharePoint and Azure Group integrations directly in the admin interface, giving you full control over credential management without needing to contact support. This feature includes built-in validation and error handling to ensure seamless updates, while all key changes are automatically logged for security and audit purposes.

#### 4. Fixed Code Character Display Issue

Special characters in code outputs, such as "<" and ">", now display correctly when used for programming languages like Power BI DAX. Previously, these characters were incorrectly converted to HTML entities (e.g., "<" and ">"), but this formatting issue has been resolved to ensure code outputs match industry-standard formatting.

## Product Updates - January 8th, 2026

- GPT 5.1 Codex - New GPT 5.1 Codex is now available on the Blockbrain platform. 
- GPT 5.1 No/Low/High Reasoning - Three new GPT 5.1 variants are available—No Reasoning for very fast, tool-optimized replies, Low Reasoning for a balance of speed and quality, and High Reasoning for deep, careful thinking. 
- GPT Image 1.5 Model - New GPT Image 1.5 model now available for generating images with enhanced quality and capabilities. 
- System Notifications and Announcements - Feature updates, warnings, and helpful tips now appear as dismissible banners at the top of your interface to keep you informed about platform status and upcoming events. 
- Image Support in HTML Files - HTML files you upload now preserve embedded images, ensuring all visual content is captured and available when needed. 

**1. GPT 5.1 Codex**

You can now select GPT 5.1 Codex and GPT 5.1 Codex Max (US hosted) from your model dropdown, giving you access to OpenAI's specialized model designed for long-running software engineering tasks. This model excels at handling complex refactoring and debugging across large codebases, performing structured code reviews, and working autonomously on extended coding sessions without losing context through advanced compaction technology.

*Please note: This feature must be activated by your Customer Success Manager and Admin.*

**2. GPT 5.1 No/Low/High Reasoning**

Two new GPT 5.1 variants are now available: **GPT 5.1 No Reasoning** delivers particularly fast responses with optimized tool integration for time-critical applications. **GPT 5.1 Low Reasoning** offers a balanced ratio between speed and quality with adaptive reasoning processes. **GPT 5.1 High Reasoning **uses high reasoning token resources for deeper answers. Best for work that requires planning, judgment, and careful thinking. All models are available via the LLM selection in the chat interface after activation by your admin.

*Please note: This feature must be activated by your Customer Success Manager and Admin.*

**3. GPT Image 1.5 Model**

You can now select GPT Image 1.5 (US hosted) for all your image generation task. Access this new model by clicking the "Options" button in the sendbox and selecting it from the Image Generation Models list.

*Please note: This feature must be activated by your Customer Success Manager and Admin.*

**4. System Notifications and Announcements**

Information banners now appear at the top of your user interface, keeping you informed about important announcements, feature updates, system alerts, or helpful tips regarding platform status and upcoming events.

After the feature flag has been activated by your Customer Success Manager, admins can individually configure these banners in the "Notifications" section of the admin area. They can specify on which pages the banners appear, set expiration dates, and determine whether users are allowed to dismiss the banners. This ensures that important information reaches users exactly where and when it is relevant.

**5. Image Support in HTML Files**

When you upload HTML files, the system now preserves and processes images that are embedded directly within those files, ensuring complete content capture. Previously, only the text content was extracted, but images are now stored alongside the text for a more complete document representation.

## Product Updates - December 22nd, 2025

- Gemini 3 Pro Image Model - New advanced image model now available for generating and analyzing images with improved quality and accuracy (US hosted only). 
- Connect Specific Knowledge Base Folders - You can now connect individual folders from your knowledge bases to data rooms instead of the entire database for more precise AI responses. 
- GPT 5.2 Model - New GPT 5.2 model now available (US hosted version only), offering enhanced performance and advanced reasoning capabilities for your AI interactions. 
- Claude Opus 4.5 Model - New Claude Opus 4.5 (EU) model now available, offering enhanced performance and advanced reasoning capabilities for your AI interactions. 
- Configurable Bot Data Retention - Your organizations can now request automatic data retention policies for all bots by contacting their Customer Success Manager, with options to enable 12-month retention for enhanced data security or keep data indefinitely. 
- Clean Code Output - Code generated by AI models now appears without unwanted HTML fragments, delivering pure code that's ready to use directly. 
- Secure API Key Rotation - API keys can now rotate automatically on your schedule or manually when needed, with email reminders and a grace period to update your integrations without interruption. 
- Controlled Content Sharing - Organizations can now control which users are allowed to share data bases and insights by contacting their Customer Success Manager to adjust sharing permissions. 
- View Original Page in Embedded Chats - Embedded chat widgets now include a "View Original Page" button, allowing you to access the original source documents directly from your conversations while using a web component. 

1. Gemini 3 Pro Image Model

You can now select the Gemini 3 Pro model (“Nano Banana”) for all your image-related tasks, giving you access to the latest AI technology for creating and analyzing images. This new model option appears in your model selection menu and delivers enhanced image quality and more accurate visual analysis results (only US hosted).

2. Connect Specific Knowledge Base Folders

You can now select and connect specific folders from your knowledge bases to data rooms instead of adding the entire database, helping you get more accurate AI responses by focusing only on relevant content. The interface has been updated with toggles (matching the style used for files and insights) to make browsing your knowledge base structure and selecting folders easier.

3. GPT 5.2 Model

You can now select GPT 5.2 from your model dropdown, giving you access to OpenAI's latest large language model with improved performance and reasoning capabilities. Please note that OpenAI currently only offers the US hosted version for this new model, which seamlessly integrates with your existing workflows and conversations for better AI responses.

4. Claude Opus 4.5 Model

You can now select Claude Opus 4.5 (EU hosted) from your model dropdown, giving you access to Anthropic's latest language model with improved performance and reasoning capabilities. This new model option seamlessly integrates with your existing workflows and conversations for better AI responses.

5. Configurable Bot Data Retention

Your organization can now request data retention standards that automatically apply to all new bots, either enabling automatic deletion of bot conversations after a specified period (e.g., 12 months) for enhanced security compliance or keeping all data indefinitely based on your needs. To enable or adjust these retention policies for your organization, please contact your Customer Success Manager.

**Please Note:** Bot Editors can always modify the retention period for individual bots at any time.

6. Clean Code Output

When asking AI models to generate code (like PowerShell scripts), the output now contains only clean, properly formatted code without any HTML fragments. Previously, HTML elements would sometimes appear in code responses even when explicitly requesting clean code, but this has been fixed across all available models.

7. Secure API Key Rotation

You can now set up automatic API key rotation on schedules ranging from 30 to 365 days (or rotate keys manually anytime), receiving email notifications before, during, and after the rotation to keep you informed. The system provides a grace period where both your old and new keys work simultaneously, giving you time to update your integrations, while a complete timeline shows your rotation history and upcoming scheduled changes.

8. Controlled Content Sharing

Organizations can now request tighter control over who can share data bases and insights with others, helping prevent unauthorized distribution of sensitive information. To enable or adjust these sharing restrictions for your organization, please contact your Customer Success Manager who will configure the appropriate permissions.

9. View Original Page in Embedded Chats

When using embedded chat widgets on external websites through the web component function, you can now click "View Original Page" to instantly access the original source document that the AI referenced in its response. This feature works the same way as on the main platform, opening the source document in a new view so you can verify information or explore content in more detail.

## Product Updates - December 8th, 2025

- Renaming the "Consumer" Role – The "Consumer" role has been renamed to "User" for improved clarity, with all existing permissions and behaviors retained. 
- Paste Files from Clipboard – You can now paste files directly into the chat using Ctrl/Cmd+V, with automatic upload and visual progress indicators for a seamless experience. 
- Smart OCR for Technical Drawings – Extract text and tables from technical drawings by manually selecting areas and enabling OCR processing in your data source’s advanced settings. 
- Smart OCR for File Uploads – Extract text from handwritten notes and PDFs by enabling Smart OCR in the bot settings and selecting the dedicated upload option during file upload. 
- User Analytics per Bot – Admins can now view the total number of users and active users for each bot directly in the analytics dashboard to monitor engagement at a glance. 
- Query Export per Bot – Admins can now export query statistics for selected bots as Excel files, showing the total number of queries and active users for chosen periods directly from the analytics dashboard. 
- Enhanced Identity Provider Support – Sign in with your preferred account – Google, GitHub, Apple, and custom OAuth providers are now supported in addition to existing Azure authentication. 
- Database Creation Control – Administrators can now control which users can create new database sources via feature flag settings available through your Customer Success Manager. 
- Knowledge Sharing Control – Administrators can now restrict permissions for sharing databases and insights for specific user roles to enhance data security and prevent unintended excessive sharing. 

1. Renaming the "Consumer" Role

The role previously called Consumer has been renamed to User to make role names clearer and more intuitive within the platform. This change is purely a naming update, and all existing permissions and behaviours associated with the former Consumer role remain the same under the new User designation. Any users who were assigned the Consumer role will now see this displayed as User in the interface and settings.

2. Paste Files from Clipboard

You can now paste images directly into the chat box using Ctrl/Cmd+V (or right-click paste), making it quicker to share files and images without manually selecting files. The system automatically uploads your file, shows upload progress with a visual indicator, and handles any errors with clear retry options.

3. Smart OCR for Technical Drawings

You can now extract text and tables from technical drawings and PDFs by manually selecting specific areas within your documents. To enable this feature, activate OCR processing in the advanced settings as a database owner—text extraction is only available when OCR processing is enabled.

4. Smart OCR for File Uploads

You can now extract text from handwritten notes and PDFs using intelligent text recognition technology. To use this feature, first enable as bot editor the Smart OCR toggle under Capabilities and Skills in your bot settings, then upload files using the "Upload file with Smart OCR" option rather than the standard "Upload file" button—only the dedicated Smart OCR upload option will process your documents with text recognition

5. User Analytics per Bot

The analytics dashboard now displays Total Users and Active Users for each individual bot, giving admins immediate visibility into bot engagement levels. This eliminates the need for manual reports and allows you to quickly identify which bots are most actively used and track user activity trends across your organisation

6. Query Export per Bot

Admins can now export detailed usage statistics for individual bots directly from the Admin - Analytics section by selecting specific bots and timeframes to generate an Excel report. Each export contains one row per selected bot showing the total number of queries and the number of users who interacted with that bot during the chosen period, making it easier to track bot performance and user engagement across your organisation.

7. Enhanced Identity Provider Support

You can now sign in to Blockbrain using your Google, GitHub, or Apple accounts, in addition to Azure authentication. For organisations with custom identity providers, Generic OAuth support enables seamless integration with any OAuth 2.0-compliant authentication system whilst maintaining full compatibility with existing Azure-based login workflows.

8. Database Creation Control

Administrators can now restrict database creation privileges using a feature flag that hides the "New Database Source" button from specific users or roles, providing the same level of access control that already exists for bot creation. To enable this feature for your organisation, please contact your Customer Success Manager, as it cannot be activated by clients directly.

9. Knowledge Sharing Control

Administrators can now control which user roles are allowed to share databases and insights by hiding sharing options from specific users, preventing unauthorized knowledge distribution and enhancing data security. To enable these controls for your organisation, please contact your Customer Success Manager, as this feature flag cannot be activated by clients directly.

## Product Updates - November 20th, 2025

- Background Task Processing - AI tasks now run in the background, allowing you to switch between chats, close your browser, or continue working elsewhere without interrupting ongoing processes. 
- Expanded AI Model Selection - Choose from 9 new AI models including GPT 5.1, Gemini 3, and 7 IONOS models, plus 3 new embedding models—with most options hosted in the EU for enhanced data sovereignty. 
- Auto-Display New Bots - Newly created bots now appear automatically at the top of your bot list, eliminating the need to manually add them. 
- Increased Scrollable Space - Folder descriptions now appear as tooltips when hovering over folder names, freeing up more screen space for your file list. 
- Smart Citation Control - The system now automatically disables citations when you specifically request not to receive them in your conversation, giving you more control over response formatting. 
- Image Generation Model Info - Image generation features now display which AI model is being used through an information icon, providing greater transparency about the technology powering your images. 
- File Upload Toggle in Bot Settings - A new toggle in bot settings allows you to independently control file upload functionality in the message box, separate from action-based file uploads. 
- Agentic Chat Indicators - Agentic chats are now marked with a visual indicator on the left sidebar, and the sidebar colour has been changed to grey for improved readability and navigation. 
- Elevated Security Standards - Enhanced session management now provides superior workspace security, requiring a one-time login for all users to activate the new protection measures 

1. Background Task Processing

AI tasks now continue running in the background even when you navigate to different chats or close your browser, allowing you to work efficiently without waiting for long-running tasks to complete. You'll receive a notification when your task finishes, and the results will be ready for you in the data room where you started the task.

2. Expanded AI Model Selection

Our platform now offers 9 additional AI models to choose from:

- GPT 5.1 (EU-hosted) 
- Gemini 3 (US-hosted) 

And 7 IONOS models hosted in the EU:

- Teuken 7B 
- Llama 3.1 8B 
- Llama 3.3 70B 
- Llama 3.1 405B 
- Mistral Nemo 12B 
- GPT-OSS 120B 
- Mistral Small 24B 

This gives you more flexibility to select the right model for your specific use case whilst maintaining data sovereignty where needed.

Additionally, 3 new IONOS embedding models enhance your platform's ability to understand and process multilingual content with improved accuracy:

- Paraphrase Multilingual MPNET Base V2 
- BGE Large EN V1.5 
- BGE M3 

3. Auto-Display New Bots

When you create a new bot using the Bot Creator (as Builder or Admin), it now appears automatically at the top of your bot list, ready to use immediately. This eliminates the need to manually add the bot through the "Add Bot" function, making your workflow faster and more intuitive.

4. Increased Scrollable Space

We've optimized the folder view by moving folder descriptions from below the path into convenient tooltips that appear when you hover over folder names. This change provides more screen space for your file list, making it easier to view and navigate your content without sacrificing access to important folder information.

5. Smart Citation Control

Citations now intelligently adapt to your preferences expressed during conversations—when you request information without citations (e.g., "tell me how to feed my dog, I don't need citations"), the system will automatically disable them for that response. This works across Knowledge Base searches, web searches, and Dynamic Insights, making your experience more tailored to your immediate needs whilst still respecting your bot's default citation settings.

6. Image Generation Model Info

When using image generation features, you can now click an information icon (ⓘ) to see details about which AI model (such as DALL·E) is creating your images, including the model name, version, and provider. This transparency helps you understand the technology behind your results and will support future enhancements like switching between different image generation models.

7. File Upload Toggle in Bot Settings

You can now independently control file upload functionality in your bot's message box through a new toggle in the Sendbox Controls section of your bot settings. This toggle works separately from the existing file upload toggle in Action Settings, allowing you to enable or disable each feature independently based on your specific needs.

**8. Agentic Chat Indicators**

Agentic chats are now clearly identifiable with a flash indicator displayed on the right side of the left sidebar, making it easy to distinguish them from regular chats at a glance. Additionally, the left sidebar colour has been updated from white to grey, improving overall readability and making it easier to navigate between your conversations.

9. Elevated Security Standards

Our latest release introduces an advanced session management feature, significantly enhancing the security of your workspace. As part of this upgrade, all users will be securely logged out and prompted to log in again, ensuring the highest level of protection for your data and activities.

## Product Updates - October 30th, 2025

- Document Processing & Monitoring - Smart load balancer ensures fair document processing by automatically managing file distribution and preventing any single user from dominating system resources. 
- Faster PDF/Image Processing - Smart image and table extraction now runs on a dedicated system to prevent these intensive tasks from slowing down regular file processing. 
- Improved Login Experience - Enhanced authentication system keeps you logged in across all devices for up to 30 days, with sessions staying active as long as you're using any device. 
- AI-Powered Image Editing - Upload or select images and modify them using AI prompts, with a green indicator showing which image generation models support editing capabilities. 
- Transparent Prompt Library - Saved prompts now appear as editable text in your message box instead of tags, allowing you to modify them before sending whilst preserving the original library prompt. 

1. Document Processing & Monitoring

A smart load balancer now ensures fair and efficient document processing for all users by automatically managing the order and distribution of files. This helps everyone experience consistent performance and prevents any single user from dominating system resources.

2.Faster PDF/Image Processing

When creating a new database, you can enable smart image and table processing under "Advanced Settings." We have now moved smart image and table extraction to a dedicated processing system to prevent these resource-intensive tasks from slowing down regular file processing. This ensures that all other files continue to process at normal speed without delays.

3. Improved Login Experience

We've upgraded our authentication system to provide a more reliable and seamless login experience across all your devices and browsers, allowing you to stay logged in for up to 30 days without interruption. As long as you're active on any device, all your other logged-in sessions remain active automatically—even after your computer goes to sleep or you switch between devices.

4. AI-Powered Image Editing

If image generation is activated, you can now upload an image via the sendbox or select an image from the output window and modify it using AI prompts—the system automatically uses your most recently uploaded/generated image to generate a new version based on your instructions using image generation models. A green indicator next to each image generation model shows which models support image editing (currently Image 1 and 2.5 Flash Image).

5. Transparent Prompt Library

Saved prompts from the Prompt Library now appear as editable text directly in your message box instead of just showing a tag, allowing you to modify the prompt before sending whilst keeping the original library prompt untouched. Your existing text remains in place with the selected prompt added to it.

## Product Updates - October 9th, 2025

- New Knowledge Menu Interface - The knowledge menu (files, insights, email and database sources) now opens in a full-screen view with left-side navigation for easier browsing instead of separate pop-up windows. 
- Enhanced Image Generation Models - Three new image generation models (Gemini 2.5 Pro Image, Imagen 4, and Black Forest Labs flux-schnell) now available for higher-quality, creative image outputs. 
- Save Files as Insights - Files in your data room can now be saved directly as insights from the file menu, eliminating the need to manually recreate or re-upload content. 
- Share Insights via Link - Generate shareable links for insights that allow recipients to save them directly and optionally open them in a bot with one click. 
- Real-Time Mathematical Formula Display - Mathematical formulas and equations now render properly in real-time as the AI generates responses when using GPT 4.1, GPT 5, or Claude 4.5 Sonnet. 
- Improved List View Navigation - List views for files, insights, and databases now feature traditional page navigation with 50 items per page, including navigation arrows and direct page input. 

**1. New Knowledge Menu Interface**

The knowledge menu (files, insights, Email and Database Sources) now opens in a full-screen view instead of separate pop-up windows, providing a cleaner and more organized workspace.

When you click on a specific knowledge type, the menu automatically opens that section, with a left-side navigation panel that makes switching between different knowledge types quick and intuitive.

**2. Enhanced Image Generation Models**

Next to GPT-image-1, the Blockbrain platform now supports three other advanced image generation models: Gemini 2.5 Pro Image, Imagen 4, and Black Forest Labs (flux-schnell)—delivering higher-quality and more creative image outputs. Select your preferred model from the list, set defaults in bot settings, and exit via the CLOSE icon.

**Important: ***Image Generation Models are feature flags and only available upon request. The Admin of your company should reach out to your Key Account Manager if you would like to enable it.*

**3. Saves Files as Insights**

Files uploaded to a data room can now be saved as insights directly in the file menu (button is located next to the download and delete options on the right side). When you click "Save as Insight," the system automatically generates a summary and saves it to your Insights library, eliminating the need to manually recreate the content.

**4. Share Insights via Link**

Click the share icon on the right side of any insight to generate a shareable link. When someone opens this link, they can save it directly to their Insights library or click "Save and Open Insight with a Bot" to select a bot and automatically open a new chat with the insight already connected—eliminating the manual process of saving and connecting insights separately.

**5. Real-Time Mathematical Formula Display**

Mathematical formulas and equations are now properly rendered in real-time as the AI generates responses, displaying LaTeX code as visual formulas instead of raw text. This feature is currently available when using GPT 4.1, GPT 5 and all Claude Sonnet models, ensuring mathematical content appears correctly formatted and readable during live conversations for technical and scientific discussions.

**6. Improved List View Navigation**

List views for files, insights, and databases now feature traditional page navigation with 50 items per page, replacing the previous scroll-to-load system. The new pagination bar includes page numbers, navigation arrows, and direct page input, whilst fixing the "Select All" confusion by clearly showing which items are currently selected on each page.

## Product Updates - September  24th, 2025

- Smarter Web Search - Web searches now use information from your files, folders, and insights to deliver more relevant results while maintaining fast performance. 
- Simplified Interface - Removed duplicate LLM Selection and Prompt Library buttons from sidebar for cleaner workspace navigation and reduced interface confusion. 
- Personalized Settings Panel - Settings panel now remembers whether you prefer it open or closed, automatically restoring your choice when you return whilst showing open by default for new users. 
- Cleaner Header Design - Simplified header now displays a single logo with Blockbrain branding repositioned to the bottom of your workspace for a cleaner appearance. 
- SharePoint Calendar Integration - Ask natural language questions about your SharePoint calendar events and receive instant answers about upcoming meetings, past events, and schedules. 

1. Smarter Web Search

Web searches now deliver more targeted results by analyzing your uploaded files, databases, insights, and emails to understand your context and generate better search queries.

The system examines your content internally to identify relevant themes and topics, then creates smarter search terms using your question, chat history and language settings - whilst keeping your documents completely secure by only sending these refined keywords to internet search providers, never your actual files or sensitive content.

2. Simplified Interface

We've streamlined the sidebar to make your workspace cleaner and easier to navigate. All your tools are still available, now better organized to reduce clutter and improve usability. The LLM Selection and Prompt Library buttons have been removed from the right sidebar—LLM Selection is now located in the top left corner, and the Prompt Library can be accessed via the text box.

3. Personalized Settings Panel

Your bot's settings panel now remembers whether you prefer it open or closed, automatically showing your choice when you return. New users will see the right sidebar open by default to explore available features. Once you adjust it, your preference (open or closed) will be saved for future visits.

4. Cleaner Header Design

We've simplified the header to show just one logo (either Blockbrain or your custom logo) for a cleaner look, with Powered by Blockbrain branding now neatly positioned at the bottom of your workspace.

5. SharePoint Calendar Integration

You can now ask simple questions about your SharePoint calendar events and get instant answers. The system connects to your SharePoint calendar so you can ask things like "When is my next meeting?" or "What do I have scheduled this week?" and it will check your calendar and give you a clear answer.

## Product Updates - September 9th, 2025

- Updated Default AI Model - GPT 4.1 is now the platform's default LLM 
- Automatic Azure Group Sync - Azure groups sync automatically when new users are created, eliminating manual admin intervention. 
- Chat Rewind for Web Components - Reset conversations to any previous point within web components without creating new data rooms. 
- Enhanced Voice Mode Interface - Voice mode displays clearer visual cues and guidance to indicate when typing is disabled and voice input is required. 
- File Selection During Procesing - Select files while they're still processing in data rooms for bulk actions like deletion. 
- File Preview in Messages - Uploaded files display preview thumbnails within sent messages for better visibility and confirmation. 

**1. Updated Default AI Model** 

GPT 4.1 is now the platform's default AI model, replacing GPT 4 Omni.

**2. Automatic Azure Group Sync** 

Azure groups now sync automatically when new users are created, eliminating the need for manual admin intervention. New users will receive their proper group permissions immediately upon account creation without requiring additional setup steps.

**3. Chat Rewind for Web Components** 

Added rewind functionality to reset conversations to any previous point within web components. Access the rewind feature through the chat interface to restart from your desired conversation point without creating new data rooms.

4. Enhanced Voice Mode Interface

Voice mode now displays clearer visual cues with updated placeholder text "Voice chat enabled – tap the icon to speak" and a dimmed input field to indicate typing is disabled. The interface now clearly guides users to use voice input when voice mode is active.

*Image 1:  Voice Mode activated (Azure GPT 4o Realtime) and Chat Interface deactivated*

5. File Selection During Processing

Select files while they're still processing in data rooms for bulk actions like deletion. When files are selected during processing, you'll see the selection count and delete option, with connect/disconnect and download options hidden until processing completes.

6. File Preview in Messages

Uploaded files now display preview thumbnails within sent messages for better visibility and confirmation. File previews appear automatically when you attach files to your messages in the chat interface.

*Image 1: The file which was dragged & dropped into the sendbox is now also displayed in the sent message *

## Product Updates - August 26th, 2025

- **New LLM: Gemini 2.5 Flash Lite**- New Gemini 2.5 Flash Lite provides quicker responses while maintaining quality.
- **Automatic Model Selection (GPT-5 Auto)**- Automatic model choosing intelligently picks the best model out of the GPT 4 or GPT 5 family for your question.
- **Cleaner Chat Interface**- Redesigned layout with organized Options menu in the sendbox (with a new “Writing Style” option) and streamlined file management.
- **New LLM Selection Layout**- Improved positioning moves AI model selection and token usage to the top-left corner.
- **Enhanced File Management**- Streamlined data room experience with search and bulk selection capabilities. Use the search bar and checkbox selection in your data room list.
- **Improved Settings Panel**- Improved settings panel with better organization and navigation. Access through the settings icon with new close buttons and enlarged clickable areas.
- **Dynamic Insight: Flexible Web Search**- Flexible web search with different search types in Dynamic Insight (Web Search or Web Search Pro).
- **Full Conversation Downloads**- Full conversation downloads including entire chat history and sources. Use the Export PDF button next to a data room.
- **Improved Web Crawling**- Improved website crawling for more reliable information extraction — now applied automatically when crawling a website in a database.
- **Upload Files in Chat Interface**- Upload files in chat via the file upload button directly in the sendbox or drag & drop into the window.
- **ZIP File Upload**- ZIP file support for uploading multiple documents at once. Upload ZIP files through the standard file upload interface.
- **Default LLM Selection (Editors only)**- Bot customization with specific AI models set as defaults. Administrators can configure default LLMs in bot settings.
- **Updated Embedding Model Descriptions**- Updated model information with clearer embedding model descriptions. View improved descriptions in the model selection interface.
- **British and American English Option**- Regional language support with British and American English variants. Select your preferred language variant in platform settings
- **Workflow Auto-Advance Toggle Behavior Improvements**- Auto-advance toggle refinements with better behavior in workflow modes. Configure auto-advance settings in workflow configuration.
- **General UI Enhancements**

**1. New LLM: Gemini 2.5 Flash Lite**

A lightweight AI model optimized for speed that provides faster responses for routine tasks and quick interactions.

**New LLMs must be activated by your admin in coordination with the Key Account Manager from Blockbrain.*

**2. Automatic Model Selection (GPT-5 Auto)**

An intelligent system that automatically selects the most appropriate GPT 4.1 or GPT 5 model (8 different LLMs) based on your query's complexity and requirements. Select "GPT 5 (Auto)" from the LLM-model dropdown to enable automatic routing, and you'll see which specific model was chosen for each response.

**New LLMs must be activated by your admin in coordination with the Key Account Manager from Blockbrain.*

*Image 1: Select GPT 5 (Auto)*

**3. Cleaner Chat Interface**

A comprehensive interface redesign featuring a new Tools menu that consolidates Writing Styles and Prompt Library (prompts can be adjusted through the Sendbox), plus enhanced data room management with search and sorting. Access the tools menu from the main chat interface and use the new search functionality in your data room list.

*Image 1: Upload your files*

*Image 2: Select your prompts or the bot’s writing style*

*Image 3: Select your writing style*

Writing styles essentially control how much the AI elaborates on its answers, ranging from very short answers (1 or 2 sentences) to comprehensive deep-dives, allowing you to match the response length to your specific needs:

- Auto - Automatically determines the optimal response length based on your question 
- Very Short - Minimal, concise answers with essential information only 
- Short - Brief responses that cover key points without elaboration 
- Normal - Standard response length with balanced detail and context 
- Long - Extended responses with comprehensive explanations and examples 
- Extra Long - Maximum detail with thorough analysis and extensive context 

*Image 4: Web Search*
**Web Search:** Perfect for quick facts and straightforward answers. This mode executes 3-8 targeted searches simultaneously to deliver instant, relevant results. Ideal for definitions, current events and simple requests.

**Web Search Pro:** For complex investigations, the systems splits your query into 3 core themes, runs 9-24 searches (3-8 per theme) and delivers structured, multi-perspective results, which are ideal for market research, academic topics and strategy.

**4. New LLM Selection Layout**

LLM selection dropdown and token usage display have been moved to the top-left corner for better visibility and easier access. Look for your model selection and token counter in the new prominent top-left location of the chat interface.

*Image 1: New LLM selection in the top left of the data room *

**5. Enhanced File Management**

Enhanced data room interface with compact displays, search capabilities, and multi-selection to e.g. delete data rooms. In order to use the bulk selection, go to the left sidebar and select the dots-icon next to the magnifying glass and click “select”.

*Image 1: Select the dots-icon*

*Image 2: Click “Select” to access the bulk-selection or sort your data rooms with the options above*

**6. Improved Settings Panel**

Redesigned settings interface with close buttons, better spacing, and enlarged clickable areas for improved navigation. Access settings through the settings icon and notice the new close buttons and improved layout throughout the interface.

**7. Dynamic Insight: Flexible Web Search**

Enhanced web search in Dynamic Insight* with selectable search types for more targeted results. Choose your preferred search type from the new dropdown menu when configuring web search in Dynamic Insight.

*Image 1: Select your Web Search type *

**Dynamic Insight is controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

**8. Full Conversation Downloads**

You can now not only download messages, but entire data rooms as PDF, by clicking on the “dots” icon and selecting “Export PDF” on the left side of the data room.

*Image 1: As a new feature you can now download you entire data room as PDF*

**Feature tip: Include entire chat history in the insight**

- When creating an insight from a chat message, you can enable a simple toggle (“Include entire chat history in the insight”) to save the entire chat history in the Insight. 
- When this Insight is linked to a data room, the entire chat history is taken into context—not just the last bot response. 

**9. Improved Web Crawling**

Upgraded web crawling* system using Firecrawl technology for more reliable information extraction from websites and documents. This enhancement works automatically in the background when processing web content for your knowledge bases.

**only visible for Builder and Admins*

**10. Upload Files in Chat Interface**

Add files directly within your conversation without switching screens or interrupting your workflow. Use the file upload button located directly in the chat sendbox or drag and drop files into the screen for immediate processing.

*Image 1: Either click “Upload Files/Folder” or drag and drop your files into the data room*

*Image 2: Your file(s) will be shown to you in the sendbox and are automatically connected with the data room through “Files”*

**11. ZIP File Upload**

Upload and process ZIP files containing multiple documents simultaneously, with automatic extraction and processing of all contained files. Upload ZIP files through the standard file upload interface or via drag and drop, and the system will automatically extract and process all contents.

**12. Default LLM Selection (Editors only)**

Editors can now set specific LLMs as favorites for individual bots based on their intended purpose and use case. Navigate to bot settings as an Editor and configure default LLMs in the bot configuration section.

*Image 1: In the top left of your data room, click the selected LLM you chose*

**13. Updated Embedding Model Descriptions**

Clearer and more detailed descriptions for embedding models to help with informed selection decisions. View the improved descriptions when selecting embedding models in the admin dashboard under the "Embedding Models" section.

**14. British and American English Option**

Added regional language variants with British and American English bot-options for improved localization. Select your preferred language variant in the data room settings under language.

*Image 1: Select your preferred bot language*

**15. Workflow Auto-Advance Toggle Behavior Improvements**

The Auto-Advance toggle now works consistently across workflow modes. In Human-in-the-Loop mode, ON automatically progresses to the next step while OFF requires manual advancement. In Autopilot mode, the toggle has no effect and maintains automatic flow.

*Image 1: Enable the “Auto-Advance” button to automatically progress to the next step*

**16. General UI Enhancements**

Platform-wide visual improvements including layout optimizations, visual consistency updates, and overall user experience enhancements. These improvements are visible throughout the updated interface and require no user action to access.

## Product Update – August 11th, 2025

#### 1. New Models

**Integration of new LLMs***

- **OpenAI**

- GPT-5 Family – Next-gen flagship with major performance boosts across 4 modes (hosted on EU & US servers) - **GPT-5**– Specialized conversational model with superior dialogue skills (likely to replace GPT-4.1 as the default Company GPT LLM)
- **GPT-5 Thinking**– Flagship variant with advanced reasoning power
- **GPT-5 Mini**– Lightweight, speed-optimized version
- **GPT-5 Nano**– Ultra-fast model for real-time use
 
- GPT-image-1 – Image Generation is now available on Azure 
- GPT 4o Realtime audio – Realtime Chat via Voice Mode 

*All LLMs are hosted on servers in the EU (and optionally in the US).*

- **Anthropic**

Claude 4.1 Opus – Most powerful model from Anthropic with advanced reasoning capabilities

*Hosted on US servers; EU availability coming soon.*

- **Meta**

Llama 4 is Meta’s latest generation of AI models, offering advanced reasoning, long-context handling, and powerful multimodal capabilities.

- **Llama 4 Maverick**– High-performance general-purpose model excelling in reasoning, coding, and multilingual capabilities.
- **Llama 4 Scout**– Optimized for ultra-long context and multimodal tasks, ideal for document and image analysis.

*Hosted on US servers; EU availability coming soon.*

- **Mistral**

- Mistral offers three different models, depending on complexity. - **Mistral Small**: Fast and efficient, best for simple tasks.
- **Mistral Medium**: Balanced performance, suitable for moderate complexity tasks.
- **Mistral Large**: High performance, ideal for complex and detailed tasks.
 

*Hosted by Mistral in the EU.*

**New LLMs must be activated by your admin in coordination with the Key Account Manager from Blockbrain.*

**Enhanced Transcription Capabilities***

Realtime Transcription Model – Seamless voice-to-text conversion with improved accuracy and faster processing

**This feature is still in early alpha, and its quality doesn't yet match the current version. It is controlled via a feature flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

#### 2. Enhanced User Experience

**Improved Content Management**

- Folder Upload Functionality – Upload entire folders to data rooms with a single action, making bulk content management significantly faster 

- Preserved Formatting – Blank lines in bot "Initial Instructions"* are now maintained after saving, ensuring your formatting stays exactly as intended 

**Initial instructions in bots are only visible for Editors.*

**Enhanced Chat Experience**

- Unified Chat History – In Webcomponents (integration in SharePoint, Microsoft Teams or a website) private login users can now view consolidated chat histories across all sessions for better continuity 
- Mobile-Optimized Interface – Web app adjustments provide enhanced usability and navigation on phone devices 

**Voice Mode: Realtime Chat (Alpha)***

- Voice Mode Integration – Experience low-latency, "speech in, speech out" conversational interactions with enhanced responsiveness via Azure GPT 4o Realtime audio for a more natural conversational flow 
- Simple Activation – Simply activate "Voice Mode" next to the sendbox to start talking with the AI 

- Note: This feature is currently in alpha and may still contain bugs 

**Realtime chat is controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

#### 3. Collaboration & Management Enhancements

**Advanced Role Management**

- Enhanced Consumer Permissions – Consumers can now be assigned as bot editors, allowing them to modify settings of existing bots (note: editors cannot create new bots) 

- Improved Editor Workflow – The “Remove Editor” option has been replaced with a new Demote to "User” option. 

**Sharing Settings in bots are only visible for Editors.*

**Administrative Controls**

- Image Generation Settings – You can control image generation capabilities on a per-bot basis through dedicated bot settings* 

**Image generation is controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain). The Bot Settings are only visible for Editors.*

- Data Retention Enhancement – Comprehensive data retention management with informational layers and extend retention for better compliance control 

**Improved Insight Management**

- Streamlined Insight Sharing – Enhanced sharing workflow with improved user experience 
- Smart Error Handling – "Insight Unavailable" modal for deleted insights provides clear communication and next steps 

#### 4. UI/UX Improvements

**Enhanced LLM Selection Interface**

- Performance Visualization – Updated LLM list view with clear performance KPIs for informed model selection 

**Improved Visual Navigation**

- Bot Status Indicators – Clear status icons for scheduled-deletion and template-based bots in dropdown menus 

- Enhanced Sorting – Organized bot dropdown in analysis tab for faster navigation* 
- Updated Tooltips – Clearer descriptions for right sidebar buttons in Knowledge Bot chat interface 

**Analysis is only visible for Admins.*

**Streamlined User Interface***

- Refined Connection Modals – Updated "Disconnect" modals for Azure Group and SharePoint with improved clarity 

**This is only visible for Admins.*

#### 5. Integration Enhancements

**SharePoint Integration**

- Global Floating Button – Webcomponent integration as a floating button across SharePoint environments 
- Configurable Sidebar – Control sidebar state during webcomponent initialization for customized user experiences 

**Administrative Enhancements***

- Organization ID Display – The Org ID is now visible in the frontend for easier identification and support. Simply click your profile and copy the Org ID displayed beneath your name and email. 

**This is only visible for Admins.*

## Product Update – July 28th, 2025

#### 1. New Models

**Integration of new LLMs***

- o3-pro – hosted on EU & US servers 
- Gemini 2.5 Pro (Google) – hosted on EU & US servers 
- Gemini 2.5 Flash (Google) – hosted on EU & US servers 
- Grok 4 (xAI) – hosted on US servers; EU availability coming soon 

**Integration of new Embedding Models***

Gemini Embedding 001 - hosted via Google on US-servers (EU availability coming soon)

**New LLMs and Embedding Models must be activated by your admin in coordination with the Key Account Manager from Blockbrain.*

#### 2. Enhanced User Experience

#### Streamlined Content Management

- Improved Editor - Edit bot responses (just double click on an answer) and insights with fewer clicks. 

- Access formatting tools more easily, and enjoy a more intuitive workflow that makes content updates significantly faster. 

#### Listen to Bot Messages

- Listen to bot responses read aloud by clicking “Listen” (headphone icon). 

- Control playback speed or pause using the media panel while continuing to navigate the platform. You can even download the bot response read aloud. 

**3. Collaboration & Managemenet Enhancements**

**3. Collaboration & Managemenet Enhancements**

**Bot Creator Update: Streamlined Creation with Nexus by Default**

- Faster Workflow: Removed the “Pick a Bot Template” step for quicker setup 
- Simplified Experience: Nexus is now the default and only option 
- Instant Start: Go directly into building your bot without extra clicks 

**only visible for Builder and Admins*

**Default Web Research***

- New “Web Research” category in bot settings allows enabling or disabling Web Research per bot 
- Option to enable Web Research by default automatically activates Web Research for all newly created Data Rooms, eliminating the need for manual activation each time 
- Set default Web Research type: Web Research, Web Research Pro, or Web Research Pro (R) 

**only visible for Builder and Admins.*

**Role Management**

- Direct Role Upgrades - Upgrade user roles directly from the dropdown menu in bot Share settings from User to Editor* 
- Peer-Level Role Management in Knowledge Databases - Content Managers and Contributors can now promote, demote, or remove users at or below their own level 

**only visible for Builder and Admins*

#### 4. Content Organization

**Include entire chat history in the insight**

- Enable a simple toggle (“Include entire chat history in the insight”) to save full chat histories in the Insight. 
- When this Insight is linked to a data room, the entire chat history is taken into context—not just the last bot response. 

**Improved Bot Sharing Visibility**

Bots now clearly display all sharing states (private, restricted, public) in both the bot list and bot creator tab

**5. UI/UX Improvements**

**5. UI/UX Improvements**

**Agents are now Prompts / Prompt Library**

- We’ve updated the terminology to make the feature’s purpose clearer and more intuitive. 
- Functionality remains unchanged—only the name and design has been updated. 

**New LLM Selection Design**

We’ve redesigned the LLM selection to make it clearer and faster to use.

- Search Function: You can now quickly find and select the LLM you want from all models available on your platform. 
- Information Button (ℹ): Click the info icon to view detailed information about each LLM. 
- Key Metrics: The evaluation criteria have been refined for better clarity. Models are now rated by Answer Quality, Speed, and Cost Efficiency. 

**Multiselect for E-Mails**

- Select all E-Mails with a single click 

**Speech-To-Text: Intuitive Button Placement**

- Enhanced Layout: Speech-to-Text button repositioned within the "Send-Box" for greater prominence 
- Improved Discoverability: More intuitive placement based on user expectations and the upcoming Voice Mode (real time chat with the bot) 

**Branded App Icon / Favicon in the Browser Tab**

Professional appearance in the browser tab and when added to home screens on iOS, Android, or Windows

**Consistent Terminology Update across the platform**

- “Databases” is now called “Database Sources”; the word “connected” has been removed from the Knowledge Management section of data rooms. 
- “Knowledge Destinations” is now called “Destination Databases”. 

**Improved OCR Processing**

Better handling of two-column PDF layouts for more accurate text extraction

## Product Update – July 15th, 2025

** 1. New Features & Enhancements**

#### Intuitive Drag & Drop Functionality

- Easily move files and Insights into folders inside the platform with a simple drag & drop action 
- Visual indicators highlight valid drop targets when dragging files 
- Receive clear visual confirmation when files are successfully moved 
- Get helpful feedback when attempting invalid file moves 

**Automatic Removal of Disconnected Databases from Data Rooms**

**Automatic Removal of Disconnected Databases from Data Rooms**

- When a database is disconnected from a bot, it will automatically be removed from existing data rooms. 
- Receive clear alerts when a bot is no longer connected to a database — either upon entering a data room or during interactions. 
- Alerts remain visible until dismissed, ensuring awareness of potential impacts on response quality. 

**2. Maintenance & UI Optimizations**

#### 1. Enhanced Analytics & Exports

#### Improved Usage Analytics*

- Track real-time token and storage usage through comprehensive dashboards. 
- Monitor current consumption, projected limits, and per-bot statistics for better tracking of usage per use case. 

**only visible for Admins*

#### Excel Table Export

- Instantly export tables from prompt results to Excel (.xlsx) with one click, maintaining original formatting and structure for easy analysis and sharing. 
- Only table data is exported; non-table text is excluded. 
- If no table is detected, the “Download as XLSX” button is disabled. 

#### Image Upload Token Tracking

- Token consumption for image uploads via Prompt Injection is now tracked and displayed in the usage dashboard. 
- Provides transparent resource cost monitoring for both individual requests and cumulative usage. 

#### 2. Knowledge Management Improvements

#### Sorting Insights by Creation

- Sort insights by creation date with the new "Created At" column in table view, making it easier to locate original entries even after batch updates. 
- The less relevant node type column is automatically hidden when space is limited. 

#### Folder Descriptions

- Add descriptions to Insight folders to better organize and understand folder contents. 
- Descriptions appear as sublines in the folder list, can be entered via text or voice, and are automatically shortened with full text available on hover. 

#### Folder Selection in Insight Editor

- Choose or create target folders directly when creating or editing insights. 
- Your content is automatically saved or moved to the selected location, eliminating extra organizational steps. 

#### 3. Interface Refinements

#### Improved Bot List View

- The bot list (former dashboard) now features a lighter card design for better visibility. 
- It defaults to a two-column layout for easier browsing but remembers your preference if you want to keep the one-column by default. 

#### Better Deleted Resource Handling

- Deleted bots or data rooms now display their last known name in grey with a "deleted" icon in workflows and results. 
- This preserves context and avoids confusion when reviewing past activities. 

#### Simplified Data Room Creation

- Data rooms now receive automatic names by default, eliminating the "Name your Data Room" prompt during creation. 
- You can still rename data rooms later if needed. 

#### Enhanced Text Editor

The editor toolbar now includes all essential markdown formatting options: headers, bold, italic, strikethrough, code, lists, quotes, alignment, hyperlinks, and tables.

#### 4. New Large Language Models

#### Integration of new LLMs*

- Llama models (from Meta) now available on US-servers (EU availability coming soon). 
- Gemini 2.5 Pro now available on EU Servers. 

**New LLMs must be activated by your admin in coordination with the Key Account Manager from Blockbrain.*

## Product Update – July 1st, 2025

** 1. New Features & Enhancements**

#### 1. Organization & Management

#### Automatic Naming of Data Rooms

- System now automatically names new data rooms based on your first message 
- Helps organize your data room list more efficiently 
- Prevents multiple generic "New Data Room" entries 
- Automatic naming occurs only once and won't override custom names you set 

**Folder Selection in Insight Editor**

**Folder Selection in Insight Editor**

- Choose where to save insights during creation or editing 
- Current folder path displayed below insight title 
- Browse existing folders or create new ones via dialog 
- Insights automatically stored in chosen folder for better organization 

#### 2. Interface Enhancements

**Redesigned Bot List Page (former “Dashboard”)**

**Redesigned Bot List Page (former “Dashboard”)**

- Clearer, more intuitive bot overview interface 
- Improved navigation and organization with more filtering options 

#### Display of Complete File Path for References

- Complete file path now visible for all database source references 
- Provides enhanced context for source identification 
- Improves traceability of information across the platform 
- Accessible in all reference displays throughout the system 

**Newsletter Language Preference***

**Newsletter Language Preference***

- Go to your profile (top right corner) and click “Manage Subscriptions” 
- Select your preferred language for newsletters related to knowledge contributions to a knowledge base 
- All future emails will be sent in the language you selected 

**The newsletter is part of the ‘Knowledge Contribution Subscription’ and controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

#### 3. Workflow Improvements*

#### Step Result Binding

- Choose whether workflow steps use previous step results as input 
- Visual diagram with connection points shows data flow between steps 
- System prevents illogical connections between steps 
- Default setting requires explicit enabling of connections 

**Multi Data Room Selection in Workflows**

**Multi Data Room Selection in Workflows**

- Select specific data rooms as input for each workflow step 
- Toggle data room selection with administrator controls 
- Choose multiple data rooms from searchable list with checkboxes 
- Selected data rooms appear as removable tags for easy management 

**Workflow is controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

#### 4. Enhanced Bot Access Control

#### Update Access Levels for Connected Database Sourcess in Bot-Sharing

- Control bot access with Private, Restricted, or Public sharing modes 
- Connected database sources automatically update access settings to match bot privacy 
- Clear notifications guide you through privacy changes 
- Ensures data security and transparency about bot access 

**Bot Status Update on Privacy Change**

**Bot Status Update on Privacy Change**

- Shared bots made private appear as "offline" in your bot list 
- View old conversations while new sessions are restricted 
- System provides popup and permanent notifications until acknowledged 

#### 5. Mobile Experience*

**UI Improvements in Chat View**

**UI Improvements in Chat View**

- Enhanced chat interface for smoother mobile experience 
- More intuitive navigation and interaction 

**Add Photo Functionality to Chat View**

**Add Photo Functionality to Chat View**

- Send photos directly from the mobile app chat view 
- Seamless media sharing capabilities 

**The mobile app must be activated by your admin in coordination with the Key Account Manager from Blockbrain.*

#### 6. Integration

#### Web Component of Chat in MS Teams*

- Blockbrain chat now embeddable directly in Microsoft Teams 
- Seamless integration with existing interface 

**If you are interested in the chat integration with Microsoft Teams, please contact the Key Account Manager at Blockbrain.*

#### Integration of OpenAI o3-pro Model

- Now available on US-servers (EU availability coming soon) 
- Designed for advanced reasoning and generation tasks 

**2. Maintenance & UI Optimizations**

#### Folder Navigation Improvements

- Clicking anywhere on a folder now opens it directly, showing its contents 
- Consistent behavior implemented across file browser, database source, and SharePoint interfaces 
- Eliminates the need to click on specific small areas for navigation 
- Provides a more intuitive experience aligned with standard file system behaviors 

#### Expandable Prompt Input Fields

- All prompt input areas now feature expandable text boxes 
- Easily compose and review longer, complex prompts with improved visibility 
- Consistent with the existing functionality in the Workflows section 
- Enhanced user experience when working with detailed prompts 

#### Standardized Sharing Settings Interface*

- Consistent "Sharing Settings" tab format throughout the platform 
- Same interface during both bot creation and subsequent editing 
- Eliminated confusing toggle switch in favor of a unified approach 
- Ensures seamless transition between creation and management workflows 

**only visible for Builder and Admins*

#### Multi-Select Connect/Disconnect for Files

- Select multiple files at once for bulk connection/disconnection in a dataroom 
- Significantly improves efficiency when managing large numbers of files 
- Streamlines prompt setup and modification workflows 

#### Web Research Enhancements*

- New “Web Research” category in bot settings to enable or disable Web Research per bot 
- Option to enable Web Research by default for new Data Rooms 
- Removes the need for manual activation in every new Data Room 

**only visible for Builder and Admins. This is controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

#### Enhanced Search Capabilities

- Global search now includes Insight folders 
- Folders appear with icons and full path information 
- Direct navigation to folder contents with a single click 
- Optimized for quick performance with thousands of folders 

#### Document Processing Enhancements

- New option to combine multiple PDF pages into a single chunk (this has to be activated in the "Advanced Settings" of a Knowledge Base) 
- Support for IFC file format via Knowledge Base integration 
- LLM Gateway integration for improved reliability and load balancing 
- Enhanced processing of images and tables within documents 

#### Interface Refinements

- Added separator line in "Save Insight" modal for improved visual clarity 
- Fixed "Save in Database Source" modal for workflow outputs* 
- Added "(Deleted)" placeholder for removed Bots/Data Rooms in workflow records* 
- Split Azure App Registrations for smoother Microsoft service connections 
- Automatic full-screen view for long chat entries 

**Workflow is controlled via a Feature Flag (Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).*

## Product Update – June 10th, 2025

** 1. New Features & Enhancements**

#### New Bot-view in Main Navigation

- “Bots” receives a dropdown menu - Recently used Bots now appear directly in the main navigation 
- Enhanced with search functionality for quicker access 
- Use "Show Bot List" to see all available Bots 
 
- Workshop is now called Bot Creator (only visible for Admins and Builder) 

#### Data Retention Option for Data Rooms

- It is now possible to auto-delete data rooms after a predefined time 
- Configure data retention policies directly in Bot Settings under "Data Retention" (Bot Editors only) 
- Access this feature from the right panel within any Bot (all users) 

#### Design and UI Changes on Dynamic Insights*

- Refreshed interface with improved usability 
- New feature: LLM selection options for customized insights 

*Dynamic Insights is a Feature Flag (*Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain).

#### Folder Management for Insights

- Create new folders directly via the "New" button 
- Select "New Folder" to organize your insights more efficiently 

#### New Speech-to-Text Models (Feature Flag*)

- Integration of Azure's advanced 4o-transcribe and 4o-mini-transcribe models 
- Access and configure these models via your profile settings (top-right corner) 

*Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain.

**2. Maintenance & UI Optimizations**

#### Voice Input Overlay Optimization

- Completely redesigned Speech-to-Text interface 
- More intuitive and responsive user experience 

#### Multi-Select Connect/Disconnect for Data Room Sources

- Use multi-select functionality to connect/disconnect multiple insights simultaneously 
- Currently available for Insights only (Files support coming soon) 

#### Support for Image and Audio Files via SharePoint Connection

- Consistent file handling across all upload methods 
- Seamless integration with existing SharePoint connections 

#### Workflow Scheduling for All User Roles (*Feature Flag)

- Access via "Set up workflow" in the Data Room 
- Click the three dots next to the workflow name to find "Workflow Scheduling" 

*Feature Flags must be activated by your admin in coordination with the Key Account Manager from Blockbrain.

#### Improved Error Messaging with Fallback LLM

- System now uses a fallback LLM to generate helpful error messages 
- Provides meaningful guidance when the primary LLM encounters processing issues 

#### Automatic Full-Screen View for Long Chat Entries

- System automatically expands to full-screen when entries exceed a certain length 
- Provides better readability for extensive conversations 

## Product Update – May 26th, 2025

**1. New Features & Enhancements**

#### Unified Navigation

- The main navigation has been redesigned for a cleaner, more intuitive experience. 
- The Dashboard is now called Bots. 
- Knowledge Management and Admin tabs now feature drop-down menus for easier access. 
- As before, Consumers have access to Bots and Knowledge Management. Builders additionally see Workshop, while Admins have access to the Admin tab. 

#### Seamless Session Continuation

- Easily resume your work in the last data room you used when you reopen the application after closing the window. 
- Enable this feature once in Account Settings by selecting “Start on last data room”. 

#### OneNote Access via SharePoint (Admin only)

Admins can now manage OneNote files directly via SharePoint integration for all users.

#### Web Component UI in German

- The web component interface—e.g. used for integrating knowledge bots into SharePoint or websites—is now fully available in German. 
- Admins can switch the interface language between English and German. 

#### Folder Upload

Upload entire folders (not just individual files) into a database source under Knowledge Management.

#### Enhanced “Save Insight to Knowledge Base”

- Save insights more efficiently with a modernized workflow. 
- Select one or multiple Knowledge Bases and save insights into one or more folders within a Knowledge Base. 

#### Support for 80+ File Types

- Upload and process over 80 different file types, including VTT files. 

#### Export Chat Messages & Insights as TXT

- In addition to PDF and Word, you can now export chat messages and insights as plain text (TXT) files. 
- Use the multi-select option (three dots) under the prompt result to download as TXT. 

#### Save Custom Prompts as Agents

- Save your custom prompts as reusable agents. 
- Use the “Save as Agent” option (three dots) under the prompt result. 
- Prompt instructions are automatically included; just add a Category and Title (Description is optional). 

#### New LLMs: Claude 4

- Claude Sonnet 4 is now available on Vertex AI servers in the EU (like Claude Sonnet 3.7). 
- Claude Opus 4 is available exclusively on US servers for now. 
- For more details, visit: Claude 4 Information 

Activation of Claude Sonnet 4 requires admin access and consultation with your Key Account Manager.

**2. Maintenance & UI Optimizations**

#### Redesigned Toast Messages

- Toast notifications now have titles and a consistent look for clearer feedback. 
- Improved error messaging for system load failures (Error Level 0). 

#### Improved Insights and Search

Enhanced prompts for Dynamic Insight and Full-text Search for better results.

#### Consistent Agent Responses

Agents now deliver more reliable and consistent responses, matching the quality of standard prompts.

#### Retry Failed Workflows

Easily retry any failed workflows directly from the interface.

#### Smarter AI-Generated Insight Titles

AI now generates more accurate and context-aware titles for insights.

#### Refined Sign-Out Modal for Connected Services

The sign-out process for integrations (e.g., OneDrive) is now clearer and more user-friendly.

#### Updated File Upload Instructions

- File upload instructions are now clearer. 
- The maximum number of files applies per upload, not in total. Wording has been improved for better understanding. 

### Knowledge Bots – Product Update – May 9th, 2025

**1. New Features & Enhancements**

We have introduced a range of powerful new features to make working with Knowledge Bots even more efficient and flexible:

- **Download Chat Messages as PDF/DOCX**Individual chat messages or results can now be exported directly as PDF or DOCX files—ideal for sharing and archiving key insights.
- **Enhanced SharePoint Integration**Improved document visibility and optimized database source connectivity enable seamless collaboration.
- **Azure GPT-4o-Mini-TTS Voice Output**Frontend support for voice output makes the platform more accessible and interactive.
- **Grok Integration**Integration with Grok provides even more advanced AI options for demanding knowledge work.
- **New File Upload**The file upload process has been completely redesigned for greater reliability and user-friendliness.
- **Webcomponent Bots: Notification & Retry for Crawling Errors**Users are now notified of failed crawling attempts and can easily retry, ensuring data completeness.

**2. Maintenance & UI Optimizations**

- **Improved Dynamic Insight Usability**Clearer labels, better hover states, and activated action buttons for a more intuitive user experience.
- **Updated Canvas and Dialogue Layouts**Modernized interfaces and optimized error handling.
- **Audio Recording & AI-Powered Title Generation**Insights can now be recorded via audio and automatically titled using AI.
- **Improved display and layouts in Audit Trail and LLM overview**
- **Optimized multi-selection (checkboxes instead of radio buttons)**

### Knowledge Bots - Product Update - March 31st 2025

#### 1. Enhanced Media Capabilities

We've expanded how you can capture and share knowledge:

- **Audio File Upload and Conversion**- Upload audio files with automatic WAV conversion for transcription
- **Download Insights as PDF/WORD**- Export insights in multiple document formats with preserved formatting
- **Increased File Size Upload Limits**- Support for larger files in data rooms
- **Updated Static Insight Creation**- Redesigned interface for intuitive insight creation (beta - feature flag only)

#### 2. User Experience Improvements

We've enhanced platform interactions:

- **Dynamic Insights**- Automatically update insights as new information becomes available (beta - feature flag only)
- **Token-based Presets**- Optimize queries with predefined output lengths (beta - feature flag only)
- **Improved Error Handling**- Automatic removal of error paths on page refresh

### Knowledge Bots - Product Update - March 17th 2025

#### 1. Expanded AI Model Portfolio - More Power, More Options!

We've significantly expanded our AI model lineup to give clients unprecedented choice and performance:

- Google Gemini Flash 2 (US & EU regions) - Google's latest offering with impressive reasoning capabilities 
- GPT 4.5 integration - OpenAI's newest model with enhanced contextual understanding 
- Claude 3.7 Sonnet (Anthropic & Vertex) - Known for nuanced responses and excellent instruction-following 
- O1 platform feature (now out of Alpha) - Our proprietary model is now production-ready after extensive testing 

#### 2. Enhanced Search & Workflow Features - Streamlined Productivity!

We've reimagined how users interact with our platform:

- Model switching in datarooms - Switch between AI models on-the-fly without disrupting workflow 
- Upgraded Insight Search with Global Search technology - Find exactly what you need, when you need it 
- Workflow access for all roles - Democratizing automation across organizations 
- Image Generation functionality - Expanding beyond text to visual content creation 
- Web Research Pro - Transform research capabilities with advanced real-time information gathering 

#### 3. User Management Improvements - Simplified Administration!

We've made administration more flexible and user-friendly:

- Extended Temporary Role Switch for Admins/Builders - Test experiences from different perspectives 
- Automatic "General Access Group" assignment - Streamlined onboarding for new users 
- Enhanced Azure Group sync with pagination - Better handling of large organizational structures 

#### 4. Platform Experience Updates - Polished Interactions!

We've refined countless details to create a more cohesive experience:

- Improved file upload consistency across the platform 
- Enhanced third-party integrations with Google Drive, OneDrive, and SharePoint 
- Live reasoning stream for Claude 3.7 and DeepSeek R1 - Watch the AI's thinking process in real-time 
- New hover effects with Dark Mode support - Subtle but important visual improvements 

### Knowledge Bots - Product Update - February 25th 2025

- **New EU-compliant models:**OpenAI o1 and o3-mini are now available

These are still beta LLMs that are a) *very expensive* and b) have *limited functionality* - **NOT** recommendable to use for long workflows or web searches yet.

- **Document Chunk Highlighting:**Helps users easily locate relevant sources in original documents
- **UI Improvement:**LLM host region information is now visible in Bot Settings
- **Upload:**ALL text-based formats are now allowed

### Knowledge Bots - Product Update - 22 January 2025 

- **Web Search Enhancement:**Added Web Search Toggle to Workflow Interface
- **Knowledge Base Improvements:**Implemented Email Service for File Upload
- **Speech-to-Text:**Extended support to 50 minutes
- **SharePoint Integration:**Updated Resync Permission functionality
- **Database Sources:**Enabled .html file uploads to database sources
- **User Interface Enhancements:**Added new "All Database Sources" tab in Data Management, management with edit icon for descriptions

### Knowledge Bots - Product Update - 06 January 2025

#### 1. Global Search

- **New full-text search functionality**across the entire platform
- Enables quick and efficient information retrieval across all areas 

#### 2. New AI Models & Compliance

- **New LLMs from Vertex AI**available in Admin tab
- **Claude 3.5 SONNET V2**now EU-hosted- GDPR compliant 
- High-performance model for European users 
 

#### 3. Email Integration

- **Connect Gmail and Outlook accounts**
- Search through email inboxes 
- Direct integration of selected emails as insights into ongoing conversations 

#### 4. Workshop Permissions

- **New User Roles in Workshop**:- Editor: Full editing rights 
- User-Editor: Can add and edit bots 
- User: Usage rights only 
 

#### 5. Dashboard Improvements

- **New "All" filter for bots**- Simplified view of all bots 
- No longer limited to Retriever or Nexus selection 
 

#### 6. Web Search Agent

- **Activation of web search functionality**
- Enables web research during queries 

### Knowledge Bots - Product Update - 04 November 2024 

- **Feature: Global Search**

- **Description:**The new Global Search feature allows users to search across the entire platform for relevant information quickly and efficiently.
- **Key Benefits:**- **Unified Search:**Perform searches across all data sources and modules within the platform.
- **Improved Efficiency:**Reduces time spent looking for specific information by providing a centralized search function.
- **Enhanced User Experience:**Provides a seamless and intuitive search experience, making it easier to find and access necessary data.
 

- **Feature: Refine Email Newsletter and Knowledge Contribution Loop**

- **Description:**Users can now connect their email inbox to the Knowledge Management system, allowing them to pull specific emails as insights directly into the platform.
- **Key Benefits:**- **Email Integration:**Seamlessly integrate your email account to import important emails into the Knowledge Management system.
- **Insight Extraction:**Convert relevant emails into actionable insights, enhancing the knowledge base.
- **Streamlined Workflow:**Simplifies the process of managing and utilizing email content within the platform.
 

### Knowledge Bot - Product Update - 25 October 2024

- **Rework the Workshop Bot Access Control:**You can now share your Bots with different access rights.
- **Ability to Switch Language to German on entire Platform**
- **Human-in-the-Loop Mode for Automation Workflow:**Workflows may now be checked step-by-step.
- **Improved UI/UX for Sharing Modal**
- **Ability to update Builder-Role in Dashboard**
- **Real-time Synchronization of Pinned Message Edits with Chat Timeline**
- **Add "Created At" and "Modified At" Timestamps to User and Bot Messages**
- **Share Selected Agent in Shared Bot/Add to New User's Dashboard - View Only, No Edit Permissions: A**llows users to share a specific agent within a shared bot environment, automatically adds the shared agent to new users' dashboards for immediate access, and restricts new users to view-only permissions to maintain bot configuration integrity.

### Knowledge Bot - Product Update - 09 September 2024

- **Merging Retriever and Nexus:**Unified functionality and UX for improved efficiency.
- **User Analytics Tab in Admin Dashboard:**New analytics features for better user insights.
- **More LLM Models from Vertex AI (Mistral and Llama):**Expanded model options for better performance.
- **Integrate GPT-4o Mini from OpenAI and Azure:**Enhanced AI capabilities.
- **Agent Prompt Library:**Introduction of a centralized Agent Prompt Library (Agent Templates), allowing reuse of agents across different bots and data rooms.
- **Add Speech to Text Icon in Agent Library:**Enhanced accessibility.
- **New Folder and Subfolder Structure for Document Management:**Implementation of an improved structure for more efficient document organization.
- **Bulk Image Delete Function:**Introduction of a feature to delete multiple images simultaneously in document management.
- **Integration of User Feedback:**Continuous improvements based on feedback from our users.
- **Refined Design of Split Layout:**Optimization of the display for pinned insights, improving user-friendliness.
- **Improvements in Reference Retrieval and Data Management:**Overhaul of the user interface for more intuitive handling of references and data.

### Knowledge Bot - Product Update - 05 August 2024

- **Shareable Knowledgebase Folder:**New feature allowing users to save insights and messages into a shareable folder, complete with an accessible audit trail.
- **Bot Creation Flow and Settings Redesign:**Streamlined process for creating bots and managing their settings, enhancing user experience.
- **Date Addition to Knowledgebase Contributions:**Implementation of date stamps for messages and insights added to the knowledge base, improving traceability.
- **Dataroom-Specific Workflow Auto Trigger:**Introduction of customizable workflow auto-trigger settings for each individual dataroom.

### Knowledge Bot - Product Update - 26 July 2024

- **Excel files (xls, xlsx) for document processing:**Enables users to upload and process Excel files directly within the platform.
- **New LLM Model:**Launched the new LLM model, Gemma 2, which offers advanced capabilities (note: it is not optimized for speed).
- **Download option:**Allows users to download files that have been uploaded to Nexus.
- **Admin Tenant Dashboard for LLM Models and Embedding Models:**Introduces a dashboard for administrators to manage LLM and embedding models.
- **Agent for part of message in Nexus Bot | Scroll AI Context Menu:**Allows users to select agents for specific parts of a message within the Nexus Bot and scroll through the AI context menu.
- **User Initials Avatar:**Adds user initials as avatars for better identification.
- **Dragdrop and Agent Import to Workflow:**Enable drag-and-drop functionality and agent import in workflows.
- **Default agents to be set by user preferences instead of a bot-level config:**Allows users to set default agents based on their preferences rather than a bot-level configuration.

### Knowledge Bot - Product Update - 08 July 2024

#### Release Notes (08 July 2024)

- **New Folder and Subfolder Structure for Document Management:**Implementation of an improved structure for more efficient document organization.
- **Bulk Image Delete Function:**Introduction of a feature to delete multiple images simultaneously in document management.
- **Integration of User Feedback:**Continuous improvements based on feedback from our users.
- **Refined Design of Split Layout:**Optimization of the display for pinned insights, improving user-friendliness.
- **Improvements in Reference Retrieval and Data Management:**Overhaul of the user interface for more intuitive handling of references and data.

### Knowledge Bot - Product Update - 01 July 2024

**Release Notes (01 July 2024)**

- Renamed 'Folders' to ' - **Data Rooms**' to reflecting the ability for user to connect different data and context .
- Ability to pin an insight across different 'Data Rooms'. 
- Refined design of system messages. 
- Refined design of the right side bar in the Knowledge Bot Nexus. - **Bot Settings**
- **File Management**(Context/Data that is connected to the respective data room)
- **Other Settings**(e.g. Language of the bot)
 
- Added detailed descriptions and parameters to benchmark different AI models - **Model descriptions**(Info about which model is suitable for which tasks)
- **Answer Quality**(General intelligence and reasoning skills)
- **Performance**(Response speed)
- **Cost Efficiency**(Cost per input and output tokens)
 
- Added the latest LLM models that are - **hosted on European servers**.- **GPT-4o**(Microsoft Azure)
- **Claude 3.5 Sonnet**(Vertex AI)
- **Gemini 1.5 Flash**(Vertex AI)
 

### Knowledge Bot - Product Update - 23 May 2024

**Release Notes (23 May 2024)**

- Redesigned and refined the " - **document management**" section to give users a better overview of their folders, files, and insights
- Added - **Microsoft SharePoint Integration**allowing administrators to sync and update documents seamlessly. Admins can selectively share folders from SharePoint that can be used as a knowledge base.
- Implemented " - **Pinnable Insight Feature**" which helps users to create and iterate on content/documents much more seamlessly. Users can now pin important messages and insights to the left side for easy reference while iterating on the content on the timeline to the right side.
- Added the - **best performing LLM (AI) models**on the market to date for users to select:- GPT-4o (Omni) 
- GPT-4 Turbo (Vision) 
- Claude 3 Opus 
- Claude 3 Sonnet 
- Claude 3 Haiku 
- Gemini 1.5 Pro (Vision) 
- Gemini 1.0 Pro (Vision) 
 

### Knowledge Bot - Product Update - 14 March 2024

**Release Notes (14 March 2024)**

- **Import textual & image content from webpages t**o build a knowledge base
- Advanced - **document references**that explains which information was used for answer generation
- Advanced - **bot sharing option to restrict access**to specific users in the organization
- **Multi-language support**(Nexus)
- Option to include chat history as a reference when sharing a note with another user (Nexus) 

Last updated
