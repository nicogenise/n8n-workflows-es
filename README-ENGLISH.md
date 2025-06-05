[🌐 Versión en español](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README.md) | [🌐 English Version](https://github.com/DragonJAR/n8n-workflows-es/blob/main/README-ENGLISH.md)

# 🧠 n8n Workflow Collection

This repository is a **fork** of the original initiative by [@Zie619](https://github.com/Zie619/n8n-workflows), who gathered n8n workflows from various sources, such as:

- The official [n8n.io](https://n8n.io/) site and its community forum.  
- Examples shared publicly on GitHub, blogs, and other websites.

The purpose of this repository is to offer a consolidated resource to inspire you, facilitate your learning, and allow you to reuse workflows in your own n8n projects.


## 📂 Implemented Improvements

- **Spanish Descriptions**: Each `.json` file was analyzed and given a clear description in Spanish based on the actions it performs.  
- **Duplicate Removal**: The unique hash of each file was verified and validated to detect and remove duplicate workflows, ensuring that each workflow is unique in content.  
- **File Renaming**: File names were updated to more accurately describe their main functionality, making them easier to search for and select.


## 🛠 Usage Instructions

To import any workflow into your n8n instance, follow these steps:

1. Open your n8n instance.  
2. Click the “Import” menu (☰ → Import workflow).  
3. Select the desired `.json` file from the `workflows` folder.  
4. Review and adjust credentials or webhook URLs as needed.  
5. Save and run the workflow.  
6. [If you can’t find the workflow you need, you can use this Custom GPT to help you find it or resolve any issues you have with n8n.](https://chatgpt.com/g/g-6840a79abd348191966dd06abd7236c8-asistente-de-flujos-n8n)  
7. You can also chat with this repository using [https://gitmcp.io/DragonJAR/n8n-workflows-es/chat](https://gitmcp.io/DragonJAR/n8n-workflows-es/chat)

## 🖥️ MCP Server (Model Context Protocol)

The MCP server for this repository, so you can interact with this large knowledge base of documented n8n workflows, is:

`https://gitmcp.io/DragonJAR/n8n-workflows-es`

[Here you’ll find instructions on how to use it in Cursor, Claude Desktop, Windsurf, VSCode, Cline, or Highlight AI](https://gitmcp.io/DragonJAR/n8n-workflows-es).

## 🤝 Contribution

If you discovered an interesting workflow or developed one yourself, feel free to contribute to this collection! Just keep in mind:

- **Descriptive Name**: Choose a file name that clearly reflects the workflow’s main function.  
- **Source Mention**: If the workflow comes from another source, include a brief comment at the beginning of the file indicating its origin.

To propose contributions, open a pull request with your new workflow or improvement.


## ⚠️ Notice

All workflows shared here are provided “as is.” **Before using them in a production environment, inspect and test them in a controlled setting**. Make sure you fully understand each node, credential, and link to avoid possible errors or security breaches.


## 📋 Workflow Listing

- [0001-nostr-damus-ai-report.json](workflows/0001-nostr-damus-ai-report.json)
  Description: This automated flow analyzes Nostr content with the hashtag #damus using language models to generate reports and then sends the results via email and Telegram.

- [0002-Gumroad-MailerLite-trigger.json](workflows/0002-Gumroad-MailerLite-trigger.json)
  Description: This automated flow adds a subscriber to MailerLite when a sale occurs on Gumroad and immediately assigns them to a specific group.

- [0003-line-chatgpt-image-flow.json](workflows/0003-line-chatgpt-image-flow.json)
  Description: This automated flow processes image generation requests through the LINE chatbot and stores them in Google Drive as binary files and in a spreadsheet with details including prompts, estimated costs, and relevant information.

- [0004-connectwise-ticket-alerts-to-teams.json](workflows/0004-connectwise-ticket-alerts-to-teams.json)
  Description: This automated flow activates daily between 8 AM and 4 PM to query new tickets in Connectwise with certain conditions, filter out those already notified using Redis, combine them by company or site into HTML messages, and send alerts to Microsoft Teams.

- [0005-google-calendar-outlook-sync.json](workflows/0005-google-calendar-outlook-sync.json)
  Description: This flow synchronizes events between Google Calendar and Microsoft Outlook, automatically creating events in Outlook when they are added in Gmail and deleting them when canceled.

- [0006-airtable-hn-job-scraping.json](workflows/0006-airtable-hn-job-scraping.json)
  Description: This automated flow allows extracting and structuring job offers posted on 'Ask HN: Who is hiring' on Hacker News using the Algolia API.

- [0007-social-media-creator.json](workflows/0007-social-media-creator.json)
  Description: This automated flow allows a chatbot to create content optimized for multiple social networks (X-Twitter, Instagram, Facebook, LinkedIn, Threads, YouTube Shorts) using LLM models and web search tools. It generates posts with specific JSON structures and creates images using external services like pollinations.ai.

- [0008-notion_linkedin_pub.json](workflows/0008-notion_linkedin_pub.json)
  Description: This automated flow posts daily on LinkedIn a selected post from a Notion database, based on the scheduled date and time.

- [0009-multi-agente-ia.json](workflows/0009-multi-agente-ia.json)
  Description: This flow allows maintaining a multi-turn conversation with multiple AI agents based on defined models and configurations, combining their responses and incorporating memory for follow-up.

- [0010-crm-lead-batchdata-calification.json](workflows/0010-crm-lead-batchdata-calification.json)
  Description: This flow verifies and qualifies leads using BatchData to query property details such as estimated value, size, or age, and then automatically updates the lead record in the CRM with this information.

- [0011-totp-generator.json](workflows/0011-totp-generator.json)
  Description: This workflow generates TOTP codes automatically when the 'Test workflow' button is executed.

- [0012-typeform-feedback-route.json](workflows/0012-typeform-feedback-route.json)
  Description: This flow analyzes responses from Typeform forms and classifies them into Google spreadsheets based on whether the numerical value 'usefulness' is greater than or equal to 3.

- [0013-bitwarden-line-sync.json](workflows/0013-bitwarden-line-sync.json)
  Description: This automated flow creates a new group in Bitwarden, gets the list of members from the LINE chatbot to synchronize subscriptions, updates the members within the created group, and finally verifies the result obtained.

- [0014-monitor-verstappen-tweets.json](workflows/0014-monitor-verstappen-tweets.json)
  Description: This flow searches for the latest public and private tweets with the keyword 'Verstappen', then compares those results with an existing list in Airtable to identify and save only new entries, eliminating duplicates.

- [0015-berlin-clima-plivo.json](workflows/0015-berlin-clima-plivo.json)
  Description: This automated flow sends the current weather forecast for Berlin daily at 9:00 AM via a message using Plivo.

- [0016-todoist-task-creator.json](workflows/0016-todoist-task-creator.json)
  Description: This flow allows creating a new task in the Todoist application through a manual trigger.

- [0017-stripe-hubspot-slack.json](workflows/0017-stripe-hubspot-slack.json)
  Description: This automated flow updates a deal in HubSpot to paid when a Stripe invoice is successfully paid and reports the payment and its details via Slack messages.

- [0018-entrevistas-y-participantes.json](workflows/0018-entrevistas-y-participantes.json)
  Description: This flow processes two separate datasets containing information about interviews and their participants, converting each individual entry into an independent object and then merging them based on specific keys.

- [0019-EscrituraJSONBinario.json](workflows/0019-EscrituraJSONBinario.json)
  Description: This automated flow creates sample JSON data, converts it to binary format (Base64), and writes this content to a file.

- [0020-todoist-ai-categorization.json](workflows/0020-todoist-ai-categorization.json)
  Description: This flow automatically organizes Todoist tasks into specific projects using artificial intelligence to categorize them.

- [0021-mock-contacts-to-sheet.json](workflows/0021-mock-contacts-to-sheet.json)
  Description: This flow loads sample contact data from the HubSpot service into a Set and then simulates an 'add row' or similar operation to Google Sheets/Airtable.

- [0022-copper-person-flow.json](workflows/0022-copper-person-flow.json)
  Description: This automated flow creates a record in Copper with the name Harshil and his email, then updates that record by adding a specific phone number, and finally gets the updated details of the person.

- [0023-coda-insert-data.json](workflows/0023-coda-insert-data.json)
  Description: This n8n flow inserts new data into a specific table of a Coda document when manually triggered by a click.

- [0024-iss-position-updates.json](workflows/0024-iss-position-updates.json)
  Description: This automated flow gets the current position of the International Space Station (ISS) every minute from an external API and sends the data to a topic in ActiveMQ.

- [0025-google-slides-thumbnail.json](workflows/0025-google-slides-thumbnail.json)
  Description: This automated flow allows downloading a specific page thumbnail from Google Slides after having previously obtained all slides of the presentation.

- [0026-linkedin-top-sourcer.json](workflows/0026-linkedin-top-sourcer.json)
  Description: This flow allows finding LinkedIn profiles using boolean search techniques from a natural description of the candidate.

- [0027-chargebee-nuevo-cliente.json](workflows/0027-chargebee-nuevo-cliente.json)
  Description: This automated flow allows creating a new customer in Chargebee when the manual task is executed.

- [0028-verificacion-email-deliverable.json](workflows/0028-verificacion-email-deliverable.json)
  Description: This flow verifies if the email 'mcolomer@gmail.com' is valid and deliverable using an external service.

- [0029-mattermost-emelia-trigger.json](workflows/0029-mattermost-emelia-trigger.json)
  Description: This automated flow sends notifications to Mattermost when someone responds in a specific Emelia campaign.

- [0030-iss-monitoring-sqs.json](workflows/0030-iss-monitoring-sqs.json)
  Description: This automated flow checks the position of the ISS satellite every minute via an API and stores the data in variables for later use.

- [0031-webflow-crear-y-actualizar.json](workflows/0031-webflow-crear-y-actualizar.json)
  Description: This flow allows creating and updating an item in a Webflow collection via manual activation.

- [0032-iss-satellite-monitoring.json](workflows/0032-iss-satellite-monitoring.json)
  Description: This automated flow periodically queries the position of the ISS satellite via an API and loads the data into Google BigQuery.

- [0033-ip-location-email.json](workflows/0033-ip-location-email.json)
  Description: This flow checks if the user is in Spain via their IP and sends a welcome email in Spanish or English depending on the detected location.

- [0034-clearbit-persona-buscar.json](workflows/0034-clearbit-persona-buscar.json)
  Description: This flow allows searching for detailed information about a person using their email via the Clearbit API.

- [0035-airtable-mailcheck-validacion.json](workflows/0035-airtable-mailcheck-validacion.json)
  Description: This flow automatically verifies the email of a contact in the database and updates the 'Valid' field in an Airtable table with the result. It first lists Airtable records, then takes the email to perform verification via Mailcheck API.

- [0036-mattermost-notificacion-iniciado.json](workflows/0036-mattermost-notificacion-iniciado.json)
  Description: This workflow uses n8n's automatic start to send a message in the specified Mattermost channel with the exact time of activation.

- [0037-mattermost-trigger.json](workflows/0037-mattermost-trigger.json)
  Description: This reverse flow uses a Mattermost update as input to trigger an event and send the configured message.

- [0038-orbit-member-update.json](workflows/0038-orbit-member-update.json)
  Description: This flow automates the creation and updating of a member in Orbit, adds their tags, creates a custom note for them, and publishes an existing article to their profile.

- [0039-clickup-task-creator.json](workflows/0039-clickup-task-creator.json)
  Description: This automated flow allows creating a task in ClickUp via a manual trigger.

- [0040-screenshot-automation.json](workflows/0040-screenshot-automation.json)
  Description: This automated flow generates screenshots of the webpage https://uproc.io in full and normal mode, uploads them to Dropbox with specific paths, and sends an email with both files attached.

- [0041-filemaker-multi-step.json](workflows/0041-filemaker-multi-step.json)
  Description: This automated flow executes sequential FileMaker actions: first, it creates a record in 'My Form Layout', then it edits the country in the same table, and finally, it queries an existing record.

- [0042-iss-mqtt-flow.json](workflows/0042-iss-mqtt-flow.json)
  Description: This automated flow executes an HTTP call every minute to get the current position of the International Space Station from api.wheretheiss.at, processes the data, and sends it via MQTT to the topic 'iss-position'.

- [0043-rag-supabase-notion.json](workflows/0043-rag-supabase-notion.json)
  Description: This automated flow allows a chatbot to maintain a contextualized conversation with current Notion data using embeddings stored in Supabase.

- [0044-gmail-drive-adjunto.json](workflows/0044-gmail-drive-adjunto.json)
  Description: This automated flow extracts messages from Gmail, saves attachments to Google Drive, and then gets the direct link to facilitate access.

- [0045-google-books-automation.json](workflows/0045-google-books-automation.json)
  Description: This automated flow gets information about a specific volume and adds it to a bookshelf in the Google Books API via a sequence of calls with OAuth2 authentication.

- [0046-email-invite-calendar.json](workflows/0046-email-invite-calendar.json)
  Description: This automated flow sends an email invitation to a specific meeting when the 'execute' button is clicked, attaching the corresponding iCal file.

- [0047-calendly-notion-auto.json](workflows/0047-calendly-notion-auto.json)
  Description: This automated flow creates a new record in a Notion database every time an 'invitee' is created in Calendly.

- [0048-notion-mattermost-marketing.json](workflows/0048-notion-mattermost-marketing.json)
  Description: This automated flow checks if a new page in the specific Notion database belongs to the Marketing team and, if so, sends a message to Mattermost with details about the new page.

- [0049-chargebee-event-trigger.json](workflows/0049-chargebee-event-trigger.json)
  Description: This automated flow receives updates for any event in Chargebee.

- [0050-calendly-humantic-personality-analysis.json](workflows/0050-calendly-humantic-personality-analysis.json)
  Description: This automated flow responds to Calendly events (such as the creation of an invitee) to execute personality analysis with Humantic AI and subsequently store the results in a Notion database page.

- [0052-release-content-publisher.json](workflows/0052-release-content-publisher.json)
  Description: This automated flow allows obtaining and publishing all content whose name starts with 'release' using Storyblok.

- [0053-ssl-expiry-checker.json](workflows/0053-ssl-expiry-checker.json)
  Description: This automated flow checks if the SSL certificate for n8n.io has expired and sends a Telegram notification if it has.

- [0054-clickup-trigger.json](workflows/0054-clickup-trigger.json)
  Description: This automated flow is triggered upon receiving updates of any event in the ClickUp tool.

- [0055-line-message-processing.json](workflows/0055-line-message-processing.json)
  Description: This flow analyzes received messages and processes different actions according to their type.

- [0056-aws-transcribe-s3.json](workflows/0056-aws-transcribe-s3.json)
  Description: This flow runs AWS Transcribe on all files found in the S3 bucket 'n8n-docs'.

- [0057-uptime-robot-monitor-management.json](workflows/0057-uptime-robot-monitor-management.json)
  Description: This automated flow uses UptimeRobot to manage web monitors: first, it creates a monitor with the given parameters, then updates it immediately, and finally gets the status of the existing monitor.

- [0058-microsoft-todo-blueprint.json](workflows/0058-microsoft-todo-blueprint.json)
  Description: This flow allows creating and updating tasks in Microsoft To Do via a manual trigger. It starts with the trigger activation that initializes the process. Then it creates a new task (create) specifying details like task list, high importance, and content. Subsequently, it updates that same task using the data returned by the creation to identify it.

- [0059-mattermost-bot-config.json](workflows/0059-mattermost-bot-config.json)
  Description: This workflow initializes and saves the necessary configurations for the Mattermost bot's operation to a binary file.

- [0060-notion-sigalerts.json](workflows/0060-notion-sigalerts.json)
  Description: This automated flow uses the Notion trigger to receive events related to database changes, processes these events through functions, and then updates records in Notion according to detected states (Open, Resolved, Annotated, or No one aware). It also integrates with SIGNL4 to send alerts.

- [0061-flujo-buscar-empresa.json](workflows/0061-flujo-buscar-empresa.json)
  Description: This flow searches and verifies the existence of a company by its name using an external service.

- [0062-active-campaign-account-trigger.json](workflows/0062-active-campaign-account-trigger.json)
  Description: This workflow is triggered when an administrator adds a new account in ActiveCampaign.

- [0063-standup-bot-config.json](workflows/0063-standup-bot-config.json)
  Description: This automated flow allows the standup bot to load a configuration from a local file.

- [0064-twitter-if-trigger.json](workflows/0064-twitter-if-trigger.json)
  Description: This automated flow executes a fixed message on Twitter when activated by a manual click or by the evaluation of a numerical condition that depends on the iteration index ($runIndex), then proceeds to NoOp and Twitter nodes according to the results.

- [0065-telegram-deploy-automation.json](workflows/0065-telegram-deploy-automation.json)
  Description: This automated flow listens to Telegram messages, checks if they contain '/deploy', and if so, extracts the first argument as a version tag. It then triggers an action on GitHub to create a release.

- [0066-pipedrive-crear-deal.json](workflows/0066-pipedrive-crear-deal.json)
  Description: This automated flow creates a new deal in Pipedrive when the manualTrigger is clicked.

- [0067-obtener-registros-dns.json](workflows/0067-obtener-registros-dns.json)
  Description: This automated flow gets the DNS records of a specific domain using n8n.

- [0068-line-chatbot-config-override.json](workflows/0068-line-chatbot-config-override.json)
  Description: This flow allows updating the chatbot configuration via a manual trigger and saving it in binary format.

- [0069-line-weather-kelvin.json](workflows/0069-line-weather-kelvin.json)
  Description: This automated flow sends a weather update message daily at 9:00 AM with the current temperature in Kelvin (Celsius degrees) for Berlin via LINE.

- [0070-114_validar_telefono.json](workflows/0070-114_validar_telefono.json)
  Description: This automated flow verifies if the phone number +34605281220 is valid using a validation process via uProc. It starts with a manual trigger that initiates the flow, then sets a 'phone' variable in the flow data and sends it to a verification service.

- [0071-pipedrive-change-monitor.json](workflows/0071-pipedrive-change-monitor.json)
  Description: This flow monitors all changes in Pipedrive via its webhook and executes automated actions.

- [0072-medium-rss-feed.json](workflows/0072-medium-rss-feed.json)
  Description: This automated flow processes N8N RSS feeds from Medium in batches.

- [0073-hubspot-pagination.json](workflows/0073-hubspot-pagination.json)
  Description: This automated flow gets multiple pages of results from the HubSpot API for contacts.

- [0074-getresponse-contact-update-flow.json](workflows/0074-getresponse-contact-update-flow.json)
  Description: This automated flow allows getting all contacts from GetResponse and updating their campaignId field if the campaign is not equal to 'n8n'.

- [0075-syncro-opsgenie-integration.json](workflows/0075-syncro-opsgenie-integration.json)
  Description: This automated flow allows integrating incidents from the Syncro tool with OpsGenie, creating and closing alerts automatically based on events received by a webhook.

- [0076-google-calendar-status-hue.json](workflows/0076-google-calendar-status-hue.json)
  Description: This flow automatically checks events started in Google Calendar every 5 minutes. Then, it assigns specific colors or states (like '4dw_leading' or 'Lavendar') to a variable called calColor and uses this information to control Philips Hue smart lights via HTTP POST webhooks according to the determined state. Finally, it updates the user's Slack profile with related text and emoji.

- [0077-conversor-json-a-xml.json](workflows/0077-conversor-json-a-xml.json)
  Description: This flow converts JSON data to XML using the 'Set' node to define specific values and responds via a webhook.

- [0078-comida-diaria-recipe.json](workflows/0078-comida-diaria-recipe.json)
  Description: This automated flow searches for recipes on Edamam according to specified parameters, including random diet and health conditions if configured. It then calculates the correct range of recipes to send by email.

- [0079-sheets-to-dropbox.json](workflows/0079-sheets-to-dropbox.json)
  Description: This automated flow reads a spreadsheet every 15 minutes and converts it into an XLS file to upload to Dropbox.

- [0080-shopify-product-alerts.json](workflows/0080-shopify-product-alerts.json)
  Description: This automated flow sends a message when a new product is created in Shopify, both to Twitter and Telegram chat.

- [0081-shopify-pedidos-trigger.json](workflows/0081-shopify-pedidos-trigger.json)
  Description: This automated flow processes the creation of new orders in Shopify to synchronize data with Zoho CRM, create tasks in Trello, and send email communications if the order exceeds a minimum value.

- [0082-shopify-reportes-semanal.json](workflows/0082-shopify-reportes-semanal.json)
  Description: This automated flow runs a report every week at 10:00 AM that collects all Shopify orders, calculates the total number and their sum, adds this data to a Google Sheets spreadsheet, and sends a Slack message with this information.

- [0083-harvest-cliente-ciclo.json](workflows/0083-harvest-cliente-ciclo.json)
  Description: This n8n flow allows creating a client in Harvest via manual execution.

- [0084-telegram-profanity-detector.json](workflows/0084-telegram-profanity-detector.json)
  Description: This automated flow detects and responds with a warning message when inappropriate language (profanity) is identified in messages received by the Telegram bot.

- [0085-n8n_LinkedIn_Interactions_Automation.json](workflows/0085-n8n_LinkedIn_Interactions_Automation.json)
  Description: This automated flow processes LinkedIn interactions (comments and likes) to obtain contact data and update or create new records in Airtable, in addition to adding them to Lemlist and Hubspot.

- [0086-calendly-pipedrive-slack.json](workflows/0086-calendly-pipedrive-slack.json)
  Description: This automated flow is triggered when an invitee is created in Calendly. It creates an activity in Pipedrive with the meeting details and sends a reminder to Slack for the sales team about the meeting, asking them to write their notes.

- [0087-github-backup-flujos.json](workflows/0087-github-backup-flujos.json)
  Description: This automated flow runs jobs every day at 11:59 PM and saves the edited content in JSON files in a GitHub repository.

- [0088-typeform-hubspot-email.json](workflows/0088-typeform-hubspot-email.json)
  Description: This automated flow captures data from a Typeform form, creates or updates contacts in HubSpot, and sends personalized information by email when the prospect shows interest.

- [0089-hubspot-deals-processing.json](workflows/0089-hubspot-deals-processing.json)
  Description: This automated flow processes the properties of a deal in HubSpot, determining if it is high priority or not. It then sends notifications to Slack and saves information in Airtable, in addition to generating presentations in Google Slides.

- [0090-GitHub-issue-autoassign.json](workflows/0090-GitHub-issue-autoassign.json)
  Description: This flow automatically assigns the issue author or whoever is requested in a conversation.

- [0091-steam-cloudflare-phishing-monitor.json](workflows/0091-steam-cloudflare-phishing-monitor.json)
  Description: This flow verifies domains on Steam to detect if they are hosted on Cloudflare using dig commands and sends email alerts when potential phishing sites are identified.

- [0092-segment-track-event.json](workflows/0092-segment-track-event.json)
  Description: This flow allows manually sending an event to Segment when activated by the 'execute' button.

- [0093-pokemon-rate-limiter.json](workflows/0093-pokemon-rate-limiter.json)
  Description: This flow checks usage limits per minute and hour via Redis, queries Pokémon data from Airtable, and uses webhooks to process responses.

- [0094-zendesk-ticket-flow.json](workflows/0094-zendesk-ticket-flow.json)
  Description: This automated flow allows creating a ticket in Zendesk via manual activation.

- [0095-sequential-http-post.json](workflows/0095-sequential-http-post.json)
  Description: This flow allows manually starting execution, getting all customer data from storage, splitting it into individual batches, and sending each via an HTTP POST request to the JSONPlaceholder API.

- [0096-news-hacker.json](workflows/0096-news-hacker.json)
  Description: This automated flow collects titles and URLs of news from Hacker News, exports them as a CSV or Excel file, and sends an email notification.

- [0097-netlify-to-airtable.json](workflows/0097-netlify-to-airtable.json)
  Description: This automated flow captures Netlify form submissions and automatically adds them to a specific table in Airtable.

- [0098-line-chatbot-memory.json](workflows/0098-line-chatbot-memory.json)
  Description: This automated flow allows a message received on the webhook to be used to create a resource in Netlify using dynamic data.

- [0099-crear-contacto-drift.json](workflows/0099-crear-contacto-drift.json)
  Description: This flow allows creating a contact in the Drift platform manually by clicking the trigger.

- [0100-zulip-send-private-message.json](workflows/0100-zulip-send-private-message.json)
  Description: This flow allows sending a private message in Zulip via a manual trigger.

- [0101-github-issue-auto-assignment.json](workflows/0101-github-issue-auto-assignment.json)
  Description: This automated flow automatically assigns GitHub issues to the person who created or commented on them when no one is assigned.

- [0102-google-calendar-meetings-slack.json](workflows/0102-google-calendar-meetings-slack.json)
  Description: This automated flow queries Gmail calendar events and compares them with today to send a list of scheduled meetings via Slack.

- [0104-vero-profile-creation.json](workflows/0104-vero-profile-creation.json)
  Description: This manual flow allows creating user profiles in Vero through direct execution, using the parameters defined in the Vero node.

- [0105-invoicing-textract-s3.json](workflows/0105-invoicing-textract-s3.json)
  Description: When the button is clicked, a 'Rechnung.jpg' file is uploaded to the S3 folder and then Amazon Textract processes it.

- [0106-google-drive-email-alert.json](workflows/0106-google-drive-email-alert.json)
  Description: This automated flow sends an email when a file is created in a specific Google Drive folder.

- [0107-salesmate-company-creator.json](workflows/0107-salesmate-company-creator.json)
  Description: This flow allows creating a company entry in the Salesmate system via a manual trigger when clicked.

- [0108-hubspot-trigger-para-chatbot.json](workflows/0108-hubspot-trigger-para-chatbot.json)
  Description: This automated flow uses the HubSpot trigger to initiate and update contact data with information obtained from Clearbit via the email address.

- [0109-ph-discord-rank.json](workflows/0109-ph-discord-rank.json)
  Description: This automated flow queries the Product Hunt API every hour to get the most upvoted projects and sends the formatted details in a message to Discord.

- [0110-info-uplead-company.json](workflows/0110-info-uplead-company.json)
  Description: This automated flow allows obtaining detailed information about a specific company using the UpLead service.

- [0111-onfleet-tasks-from-spreadsheet.json](workflows/0111-onfleet-tasks-from-spreadsheet.json)
  Description: This flow loads an Excel file from a local path and uses it to create tasks in Onfleet.

- [0112-lem-list-carga.json](workflows/0112-lem-list-carga.json)
  Description: This flow allows loading contact data from Dropcontact into a Google sheet and then transferring them as leads to Lemlist.

- [0113-webhook-html-response.json](workflows/0113-webhook-html-response.json)
  Description: This basic flow sets up a webhook that listens to the 'my-form' route and responds with HTML that includes Bootstrap.

- [0114-flujo-tareas.json](workflows/0114-flujo-tareas.json)
  Description: This flow allows getting all tasks of a specific flow via a manual trigger.

- [0115-facebook-profile-changes-mattermost.json](workflows/0115-facebook-profile-changes-mattermost.json)
  Description: This automated flow sends a Mattermost notification when a user updates their Facebook profile.

- [0116-typeform_lead_workflow.json](workflows/0116-typeform_lead_workflow.json)
  Description: This automated flow allows a chatbot to process leads from Typeform and perform operations in Airtable: if the contact does not exist, it creates it; if it already exists, it updates its fields. It also sends Slack notifications when a lead is added or updated.

- [0117-calendly-dropcontact-notion-integracion.json](workflows/0117-calendly-dropcontact-notion-integracion.json)
  Description: This automated flow allows integrating Calendly events with the DropContact system and storing the data in a Notion database.

- [0118-slack-error-alert.json](workflows/0118-slack-error-alert.json)
  Description: This automated flow sends a notification message to the Slack node when an error occurs in the 'Error Trigger' workflow.

- [0119-close-date-automation.json](workflows/0119-close-date-automation.json)
  Description: This automated flow checks if a close date exists and, if not, sets it to three weeks later.

- [0120-customer-data-post.json](workflows/0120-customer-data-post.json)
  Description: This automated flow starts manually with a click, sets an API key, and then gets all person data from the dataStore to send via POST to webhook.site.

- [0121-crm-sync.json](workflows/0121-crm-sync.json)
  Description: This flow synchronizes contacts between Pipedrive and HubSpot by obtaining all records from both systems, then uses 'Merge' to combine data when they match by email or name.

- [0122-sync-hubspot-pipedrive.json](workflows/0122-sync-hubspot-pipedrive.json)
  Description: This flow synchronizes contacts between HubSpot and Pipedrive via a cron trigger every minute, using email matches to merge records.

- [0125-flow-trigger-task.json](workflows/0125-flow-trigger-task.json)
  Description: This automated flow is triggered when an update occurs in any specified task.

- [0126-sanitized-invoices-upload.json](workflows/0126-sanitized-invoices-upload.json)
  Description: This flow reads emails from the 'Invoices' mailbox on an IMAP server and processes each attachment, sanitizing the filename to remove special characters, before uploading it to Nextcloud.

- [0127-github-release-to-gitlab-issue.json](workflows/0127-github-release-to-gitlab-issue.json)
  Description: This flow monitors the latest releases of a GitHub repository weekly and checks if a corresponding issue exists in the attached GitLab repository. If there is no match, it automatically creates a new issue.

- [0128-iss-position-firebase.json](workflows/0128-iss-position-firebase.json)
  Description: This automated flow collects the current position of the ISS from an API every minute and stores the data in real-time in a Firebase database.

- [0129-twitter-banner-creator.json](workflows/0129-twitter-banner-creator.json)
  Description: This automated flow allows downloading recent Twitter followers' profiles, processing their avatar images (resizing and cropping), combining them with a background image through multi-stage composition, and finally uploading them as a banner using the OAuth1.0 API.

- [0130-config-impresao.json](workflows/0130-config-impresao.json)
  Description: This automated flow queries printing configuration and fabric roll information to issue labels.

- [0131-limpia_pacotes_telegram.json](workflows/0131-limpia_pacotes_telegram.json)
  Description: This automated flow executes daily SQL queries to clean transport packages in the 'PPM' database and then updates old records to 'DELETE'. Afterwards, it sends a predefined message to the specified chatId.

- [0132-line-chatbot-memory.json](workflows/0132-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation by remembering the name and email of the user who activates it.

- [0133-gitlab-release-outline.json](workflows/0133-gitlab-release-outline.json)
  Description: This flow automatically detects the creation of a new tag in the GitLab 'ci-test' repository and, if it is a release tag, creates an Outline document based on the provided data.

- [0134-tweet-image-jokes.json](workflows/0134-tweet-image-jokes.json)
  Description: This automated flow executes a task every day at 5:00 PM to get graphic jokes from the Blablagues API and then publishes them on Twitter using images.

- [0135-dominio-email-extractor.json](workflows/0135-dominio-email-extractor.json)
  Description: This flow extracts the domain from a provided email using a function.

- [0136-torrent-search-transmission.json](workflows/0136-torrent-search-transmission.json)
  Description: This automated flow searches for torrents on KickassTorrents and Rarbg from a title provided by a POST Webhook request. If a torrent is found, it attempts to add it to the Transmission client for download. If no results are found or a 409 error (conflict) is received, it notifies that the movie is not available.

- [0137-tareas-toggl-alertas.json](workflows/0137-tareas-toggl-alertas.json)
  Description: This automated flow continuously monitors new time entries in Toggl.

- [0138-telegram-receipts-textract.json](workflows/0138-telegram-receipts-textract.json)
  Description: This automated flow allows receiving a document (likely an invoice) via Telegram bot, downloading it, and uploading it to S3 cloud storage. Subsequently, it uses AWS Textract to analyze the text contained in that file and finally saves the extracted results in a specific Airtable table.

- [0139-gdrive-aws-s3-sync.json](workflows/0139-gdrive-aws-s3-sync.json)
  Description: This flow monitors changes in a specific Google Drive file and synchronizes files with the 'mybucket' bucket in AWS S3 through get and upload operations, using a 'merge' node to combine data.

- [0140-onfleet-shopify-task.json](workflows/0140-onfleet-shopify-task.json)
  Description: This automated flow synchronizes the creation of a new fulfillment in Shopify with the corresponding generation of a task in Onfleet.

- [0141-twilio-mautic-form-sms.json](workflows/0141-twilio-mautic-form-sms.json)
  Description: This automated flow receives notifications when a form is submitted in Mautic and sends an SMS confirmation.

- [0142-xml-to-json-dropbox.json](workflows/0142-xml-to-json-dropbox.json)
  Description: This flow takes XML data from a URL, converts it to JSON format using the 'To JSON' node, then updates the message title with the 'Change title' parameter, and finally uploads the JSON content to Dropbox using the specified path.

- [0143-rekognition-google-images.json](workflows/0143-rekognition-google-images.json)
  Description: This automated flow searches for street images from Google and uses AWS Rekognition to analyze them and extract labels. It then combines these results with the original data and saves everything in a Google spreadsheet.

- [0144-funcion-hoy.json](workflows/0144-funcion-hoy.json)
  Description: This flow uses the Function node to get the current date in ISO format and the day of the week.

- [0145-readwise_telegram_sync.json](workflows/0145-readwise_telegram_sync.json)
  Description: This automated flow synchronizes books and articles from Readwise with Telegram, sending summaries and details.

- [0146-baserow-release-feed.json](workflows/0146-baserow-release-feed.json)
  Description: This automated flow collects blog articles about 'release' from baserow.io and generates an XML response that can be used to feed RSS feeds or webhooks.

- [0147-set-variables-flujo.json](workflows/0147-set-variables-flujo.json)
  Description: This flow uses a manual trigger to execute a Set node, which allows defining default values for different variables based on the specified type.

- [0148-daily-weather-spontit.json](workflows/0148-daily-weather-spontit.json)
  Description: This automated flow checks the current weather conditions in Berlin every day at 9 AM and sends a push notification to the user with the current temperature.

- [0150-workflow-spreadsheet-export.json](workflows/0150-workflow-spreadsheet-export.json)
  Description: This n8n flow processes a webhook input containing lists of items, converts these into an Excel file (.xlsx), and responds to the webhook with the spreadsheet as an attachment.

- [0151-line-chatbot-response-token.json](workflows/0151-line-chatbot-response-token.json)
  Description: This flow processes LINE webhook requests, using HMAC SHA256 on a received token and storing the result as 'response_token' to maintain contextualized memory.

- [0152-gdpr-data-deletion.json](workflows/0152-gdpr-data-deletion.json)
  Description: This automated flow handles slash commands in Slack to request data deletion according to GDPR. It validates that the token and email address are present, processes deletions from different services (Paddle, Customer.io, and Zendesk), and then logs these events in an Airtable database.

- [0153-145-traductor-cocinas.json](workflows/0153-145-traductor-cocinas.json)
  Description: This automated flow allows getting cocktail instructions from an API and translating them automatically into Italian.

- [0154-hubspot-company-alerts.json](workflows/0154-hubspot-company-alerts.json)
  Description: This flow is triggered when a new company is created in HubSpot and checks if it has deliverability issues or if its domain is invalid/disposable email, sending alerts via Slack.

- [0155-mattermost-financial-metrics-cron.json](workflows/0155-mattermost-financial-metrics-cron.json)
  Description: This automated flow sends monthly financial metrics from ProfitWell to Mattermost every day at a scheduled time.

- [0156-news-ycombinator-telegram.json](workflows/0156-news-ycombinator-telegram.json)
  Description: This flow periodically checks if the news server response has changed using two identical HTTP requests and a Telegram bot to notify when changes occur.

- [0157-line-syncro-timer-sync.json](workflows/0157-line-syncro-timer-sync.json)
  Description: This automated flow synchronizes time entries in Syncro from a webhook that receives information about phone calls from a chatbot.

- [0159-strava-accountability-checker.json](workflows/0159-strava-accountability-checker.json)
  Description: This daily flow checks that a user has logged enough active time in Strava (minimum defined in accountability hours) and sends motivational emails to their team if they do not.

- [0160-sendy-subscribe-campaign.json](workflows/0160-sendy-subscribe-campaign.json)
  Description: This automated flow allows adding a subscriber to a list and creating/sending a campaign when manually activated.

- [0161-onfleet-driver-signup-alert.json](workflows/0161-onfleet-driver-signup-alert.json)
  Description: This automated flow sends a message to Slack when a new driver is created in Onfleet.

- [0162-crypto-portfolio-updater.json](workflows/0162-crypto-portfolio-updater.json)
  Description: This automated flow updates crypto asset values in an Airtable base every hour with current data from CoinGecko.

- [0163-mock-transactions-sum.json](workflows/0163-mock-transactions-sum.json)
  Description: This flow uses function nodes to generate mocked data with amounts in USD and calculate the total sum.

- [0164-mattermost-airtable-trigger.json](workflows/0164-mattermost-airtable-trigger.json)
  Description: This flow monitors a record in Airtable called 'Data' and sends a notification to the specified Mattermost channel when new information is added.

- [0165-hashtag-tweet-generator.json](workflows/0165-hashtag-tweet-generator.json)
  Description: This flow randomly selects a hashtag from a predefined list, generates a tweet using the OpenAI API, and saves it to an Airtable table.

- [0167-shopify-onfleet-tags-sync.json](workflows/0167-shopify-onfleet-tags-sync.json)
  Description: This automated flow updates the tags of a product in Shopify whenever a delay is detected in an Onfleet task.

- [0168-Onfleet-to-QuickBooks-Invoices.json](workflows/0168-Onfleet-to-QuickBooks-Invoices.json)
  Description: This automated flow creates an invoice in QuickBooks Online when a new task is generated in Onfleet.

- [0169-onfleet-task-from-google-drive.json](workflows/0169-onfleet-task-from-google-drive.json)
  Description: This automated flow creates a task in Onfleet when a specific file in Google Drive is updated.

- [0170-rss-security-monitor.json](workflows/0170-rss-security-monitor.json)
  Description: This automated flow monitors multiple RSS feeds for new content, using a mechanism to avoid duplicate submissions. When new information is detected, it sends notifications to different Telegram accounts according to their category (security, IT, or Microsoft 365).

- [0171-if-condition-checker.json](workflows/0171-if-condition-checker.json)
  Description: This flow takes a predefined JSON output, parses it, and then checks if the value of 'value1' (which is always true in this example) meets the expected condition.

- [0172-slack-file-downloader.json](workflows/0172-slack-file-downloader.json)
  Description: This manual flow downloads a file from the specified URL and sends it to a Slack channel using OAuth2 authentication.

- [0173-sinonimos_aleman_openthesaurus_api.json](workflows/0173-sinonimos_aleman_openthesaurus_api.json)
  Description: This flow allows obtaining synonyms of a term in German using the OpenThesaurus API.

- [0174-adobesign-webhook-data.json](workflows/0174-adobesign-webhook-data.json)
  Description: This automated flow sets up a webhook response that includes the clientID variable and extracts specific data from the JSON body about agreements and participants.

- [0175-pagerduty-incident-flow.json](workflows/0175-pagerduty-incident-flow.json)
  Description: This automated flow allows creating an incident in PagerDuty, updating it, and then getting its details.

- [0176-weather-api.json](workflows/0176-weather-api.json)
  Description: This automated flow allows obtaining weather information (temperature and description) of any city specified via an HTTP request. It collects data from the OpenWeatherMap API and creates two variables: 'temp' for temperature and 'description' for the weather state.

- [0177-youtube-telegram-monitor.json](workflows/0177-youtube-telegram-monitor.json)
  Description: This automated flow checks every 30 minutes if there are new YouTube videos on a specific channel, compares them with already processed IDs to avoid duplicates, and sends a Telegram notification when new content is detected.

- [0178-thehive-case-management.json](workflows/0178-thehive-case-management.json)
  Description: This automated flow allows creating, updating, and getting a case in TheHive through a sequence of connected steps.

- [0179-bubble-data-access.json](workflows/0179-bubble-data-access.json)
  Description: This flow allows making an authenticated HTTP request to access user data from the Bubble API.

- [0180-gitlab-backup.json](workflows/0180-gitlab-backup.json)
  Description: This automated flow allows performing backups of n8n workflows and credentials using Git commands, which are executed periodically or manually.

- [0181-cortex-abuse-detector.json](workflows/0181-cortex-abuse-detector.json)
  Description: This flow analyzes a URL using the Abuse Finder node in Cortex, and then gets the job details using the returned ID.

- [0182-logo-download-script.json](workflows/0182-logo-download-script.json)
  Description: This automated flow downloads an image from a URL and writes it to the local file system.

- [0183-questdb-tabla-datos.json](workflows/0183-questdb-tabla-datos.json)
  Description: This automated flow creates a 'test' table with id and name columns in QuestDB when manually executed.

- [0184-thehive-event-monitor.json](workflows/0184-thehive-event-monitor.json)
  Description: This flow monitors all events in TheHive system and triggers an action when one occurs.

- [0185-datos-binarios-descomprimidos.json](workflows/0185-datos-binarios-descomprimidos.json)
  Description: This automated flow downloads a ZIP file containing binary data and splits it into individual items, each with a single sequence of binary data under the 'data' key.

- [0186-164_Crear-canal-invitar-y-subir-archivo.json](workflows/0186-164_Crear-canal-invitar-y-subir-archivo.json)
  Description: This automated flow creates a Slack channel using a bot, invites the specified users, and then sends a welcome message along with the n8n logo.

- [0187-165_create_update_get_user_iterable.json](workflows/0187-165_create_update_get_user_iterable.json)
  Description: This flow allows creating, updating, and retrieving user information via the Iterable API.

- [0188-kafka-temp-alert.json](workflows/0188-kafka-temp-alert.json)
  Description: This flow receives Kafka messages from the topic_test topic and sends an SMS when the temperature exceeds 50 degrees.

- [0189-url-shortener-stats.json](workflows/0189-url-shortener-stats.json)
  Description: This n8n flow creates a short URL from a provided link and then gets statistics about the performance and reach of that same shortened URL.

- [0190-smart-factory-data-generator.json](workflows/0190-smart-factory-data-generator.json)
  Description: This automated flow generates random temperature and uptime data for an industrial machine, using a fixed name 'n8n_cr8' as an identifier, and sends it periodically via AMQP.

- [0192-reporte-tiempo-hilo.json](workflows/0192-reporte-tiempo-hilo.json)
  Description: This automated flow generates a detailed HTML report from timesheet records for users and tasks.

- [0193-user-request-management.json](workflows/0193-user-request-management.json)
  Description: This automated flow handles user requests from a Typeform form and classifies them into different types (Documentation, Presentation, etc.) to process them appropriately in ClickUp.

- [0194-customer-data-processing.json](workflows/0194-customer-data-processing.json)
  Description: This workflow uses a manual trigger to get customer data from the 'Customer Datastore' and then edits it in a variable using the Set node.

- [0195-ghost-post-automation.json](workflows/0195-ghost-post-automation.json)
  Description: This automated flow allows creating a post in Ghost, updating its status to published, and then getting information about the created post.

- [0196-airtable-insert-update.json](workflows/0196-airtable-insert-update.json)
  Description: This automated flow inserts an initial record into Airtable's Table 1, then lists records filtered by the 'Name' field equal to 'n8n', and finally updates the first found record with the values defined in the Set step.

- [0197-snowflake-table-management.json](workflows/0197-snowflake-table-management.json)
  Description: This automated flow allows creating a table in Snowflake and performing data insertions and updates using previously defined operations.

- [0198-csv-conversion.json](workflows/0198-csv-conversion.json)
  Description: This flow allows you to read a CSV file, process it as a spreadsheet, and convert it to JSON format for storage.

- [0200-users-api-spreadsheet.json](workflows/0200-users-api-spreadsheet.json)
  Description: This flow uses the randomuser.me API to get data and then extracts it in JSON format. Subsequently, it updates a Google spreadsheet with these values and also generates a CSV file.

- [0201-users-data-flow.json](workflows/0201-users-data-flow.json)
  Description: This flow gets random user data from the randomuser.me API, processes it, and stores it in a Google sheet. It also creates a CSV file with that data and prepares an email to attach the JSON.

- [0202-twist-channel-automation.json](workflows/0202-twist-channel-automation.json)
  Description: This automated flow allows creating a new channel in Twist and then sending it a custom notification with an action link to the user.

- [0203-n8n-fecha-dinamica.json](workflows/0203-n8n-fecha-dinamica.json)
  Description: This flow uses Luxon expressions to dynamically calculate and format dates in n8n.

- [0204-clientes-condicion.json](workflows/0204-clientes-condicion.json)
  Description: This flow processes customer data through filters and conditional branches to segment them by country.

- [0205-workflow-merge-demo.json](workflows/0205-workflow-merge-demo.json)
  Description: This flow demonstrates how n8n's Merge node combines data from different sources using different join modes, showing examples from ingredients to band formation.

- [0206-n8n_paginacion_ejemplo.json](workflows/0206-n8n_paginacion_ejemplo.json)
  Description: This automated flow uses HTTP nodes to get data in a structured way (like lists of albums or web pages) and handle responses by creating items.

- [0207-workflow-automatico-mensajes-clientes.json](workflows/0207-workflow-automatico-mensajes-clientes.json)
  Description: This automated flow sends personalized messages to each customer obtained from a data store, waiting briefly between each message to avoid exceeding request limits, and then provides them with a specific URL for their interaction.

- [0208-apod-telegram-daily.json](workflows/0208-apod-telegram-daily.json)
  Description: This automated flow sends NASA's Astronomy Picture of The Day (APOD) every day at 8:00 PM in a message with its title as a caption via Telegram bot.

- [0209-google-search-url-generator.json](workflows/0209-google-search-url-generator.json)
  Description: This flow uses the Webhook node to receive input data, then creates a URL by concatenating those values (first and last letter) to generate a Google search, and finally responds to the webhook showing the generated URL.

- [0210-google-sheets-data-preparation.json](workflows/0210-google-sheets-data-preparation.json)
  Description: This flow processes data from the 'Customer Datastore' node to prepare it before performing an UPSERT operation in Google Sheets. The field format is adjusted: the 'name' field from the input is renamed to 'Full name', and a new 'Created time' field is added with the current date.

- [0211-etl-weekly-google-sheets-mysql.json](workflows/0211-etl-weekly-google-sheets-mysql.json)
  Description: This automated flow executes an insert into MySQL every week using data from Google Sheets.

- [0212-mysql-gsheets-semanal.json](workflows/0212-mysql-gsheets-semanal.json)
  Description: This automated flow executes a SQL query weekly on the books table and writes the result to a Google sheet.

- [0213-google-sheets-process-timer.json](workflows/0213-google-sheets-process-timer.json)
  Description: This automated flow checks every 5 minutes if there are unprocessed rows in a spreadsheet and marks them as such when manually executed.

- [0214-hoja-html-flujo.json](workflows/0214-hoja-html-flujo.json)
  Description: This automated flow reads data from a specific spreadsheet and converts it into an HTML file when a request is received via Webhook.

- [0215-html-sheet.json](workflows/0215-html-sheet.json)
  Description: This automated flow reads data from a Google Sheets spreadsheet and converts it into HTML with table format to respond via webhook.

- [0216-typeform-pipedrive-mapeo.json](workflows/0216-typeform-pipedrive-mapeo.json)
  Description: This automated flow collects data from a Typeform form and integrates it into Pipedrive to automatically create organization, person, and lead records, maintaining the mapping logic between the original format and custom properties.

- [0217-gestionar-correos-eliminar-y-agregar.json](workflows/0217-gestionar-correos-eliminar-y-agregar.json)
  Description: This flow allows getting Gmail messages marked with a specific label, removing that label, and adding a new one.

- [0218-asana-notion-sync.json](workflows/0218-asana-notion-sync.json)
  Description: This n8n flow synchronizes tasks between Asana and Notion via webhooks, creating or updating entries in the Notion database according to changes detected in Asana tasks.

- [0219-company-data-airtable.json](workflows/0219-company-data-airtable.json)
  Description: This flow extracts the logo, icon, and data of a company using Brandfetch, and automatically stores them in an Airtable table.

- [0220-mailchimp-nueva-cita.json](workflows/0220-mailchimp-nueva-cita.json)
  Description: This automated flow searches for new contacts created today in HubSpot, extracts their main properties, and adds them as members to a specific Mailchimp list every day at 07:00.

- [0221-line-mailchimp-sync.json](workflows/0221-line-mailchimp-sync.json)
  Description: This flow synchronizes contacts between LINE and Mailchimp using the HubSpot API.

- [0222-pipedrive-stripe-deal.json](workflows/0222-pipedrive-stripe-deal.json)
  Description: This flow checks if a deal in Pipedrive has been recently won and, if the associated customer does not exist in Stripe, creates it using the provided data.

- [0223-stripe-organization-sync.json](workflows/0223-stripe-organization-sync.json)
  Description: This automated flow seeks to process successful Stripe charges that occurred before the last execution time, searching in Pipedrive for the organization corresponding to each customer and creating a note with the charge details.

- [0224-pipedrive-stripe-product-sync.json](workflows/0224-pipedrive-stripe-product-sync.json)
  Description: This automated flow synchronizes new products from Pipedrive with Stripe via an API and then creates their corresponding price records.

- [0225-pipedrive-datagma-enrichment.json](workflows/0225-pipedrive-datagma-enrichment.json)
  Description: This automated flow uses Pipedrive to track organizations and personnel, enriching their data with information from Datorama such as Investment Fund and web traffic.

- [0226-tradegate-investment-report.json](workflows/0226-tradegate-investment-report.json)
  Description: This automated flow collects investment data stored in a Baserow table and queries current quotes on the Tradegate platform to generate a detailed report that is sent via email using SendGrid.

- [0227-pipedrive-organization-sync.json](workflows/0227-pipedrive-organization-sync.json)
  Description: This flow monitors an Excel file in Google Drive and creates organizations and contact information in Pipedrive based on its content.

- [0228-github-fork-to-pipedrive-lead.json](workflows/0228-github-fork-to-pipedrive-lead.json)
  Description: This flow detects forks on GitHub and creates leads in Pipedrive if the person does not exist.

- [0229-github-pullrequest-pipedrive.json](workflows/0229-github-pullrequest-pipedrive.json)
  Description: This automated flow searches Pipedrive for an existing user based on the email of a PR (Pull Request) creator detected by a GitHub webhook, and if it exists, adds a note to their account.

- [0230-mattermost-channel-onboarding.json](workflows/0230-mattermost-channel-onboarding.json)
  Description: This automated flow creates a Mattermost channel, adds members to it, and then posts a message in that same channel.

- [0231-line-chatbot-context.json](workflows/0231-line-chatbot-context.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation by using user data in personalized messages.

- [0232-agregar-archivo-json-a-hoja-google.json](workflows/0232-agregar-archivo-json-a-hoja-google.json)
  Description: This flow reads a JSON file and adds it to Google spreadsheets.

- [0233-salesforce-sync.json](workflows/0233-salesforce-sync.json)
  Description: This automated flow allows maintaining the relationship between Google Sheets companies and their corresponding data in Salesforce by creating both account and contact records.

- [0234-excel-to-salesforce.json](workflows/0234-excel-to-salesforce.json)
  Description: This automated flow extracts data from Microsoft Excel to search and create records in both account and contact in Salesforce.

- [0235-salesforce-carga-hoja-calculo.json](workflows/0235-salesforce-carga-hoja-calculo.json)
  Description: This flow processes data from a spreadsheet to create records in Salesforce: first, it searches for existing accounts, then creates new accounts if not found, and finally adds contacts linked to them.

- [0236-ard-podcast-scraper.json](workflows/0236-ard-podcast-scraper.json)
  Description: This automated flow extracts episode links from a webpage, then gets and processes the information for each episode to generate a complete RSS feed.

- [0237-firestore-document-management.json](workflows/0237-firestore-document-management.json)
  Description: This automated flow allows creating and updating documents in Google Cloud Firestore.

- [0238-nextcloud-spreadsheet.json](workflows/0238-nextcloud-spreadsheet.json)
  Description: This automated flow allows downloading an Excel file from NextCloud, processing it, and uploading it again to the same location after integrating data.

- [0239-github-issue-notion-sync.json](workflows/0239-github-issue-notion-sync.json)
  Description: This flow synchronizes GitHub Issues events with actions in a Notion database, allowing automatic updating of properties like title and status.

- [0240-shopify-zendesk-sync.json](workflows/0240-shopify-zendesk-sync.json)
  Description: This automated flow synchronizes customer information between Shopify and Zendesk when a contact is updated in Shopify.

- [0241-shopify-zendesk-sync.json](workflows/0241-shopify-zendesk-sync.json)
  Description: This flow checks if a Shopify order already exists in Zendesk. If not found, it creates a new ticket with the order information and updates the flow.

- [0243-google-drive-notion.json](workflows/0243-google-drive-notion.json)
  Description: This automated flow creates a page in a Notion database when a new file is uploaded to a specific Google Drive folder.

- [0244-zendesk-slack-sync.json](workflows/0244-zendesk-slack-sync.json)
  Description: This automated flow synchronizes Zendesk events with messages in Slack via webhooks.

- [0245-workflow-zendesk-asana.json](workflows/0245-workflow-zendesk-asana.json)
  Description: This automated flow checks if an Asana task already exists based on a custom Zendesk field, and updates the ticket with the corresponding information.

- [0246-monday-mautic-automation.json](workflows/0246-monday-mautic-automation.json)
  Description: This automated flow creates an item in Monday.com with the contact's name and email when a new one is saved in Mautic.

- [0247-calendly-mautic-sync.json](workflows/0247-calendly-mautic-sync.json)
  Description: This automated flow synchronizes data from Calendly with Mautic to create or update contacts when a new event is generated.

- [0248-shopify-mautic-contact.json](workflows/0248-shopify-mautic-contact.json)
  Description: This automated flow allows creating a contact in Mautic every time a new customer is created in Shopify.

- [0249-zendesk-github-integration.json](workflows/0249-zendesk-github-integration.json)
  Description: This automated flow synchronizes Zendesk tickets with issues and comments on GitHub.

- [0250-zendesk-jira-integracion.json](workflows/0250-zendesk-jira-integracion.json)
  Description: This automated flow integrates Zendesk and Jira: if a Zendesk ticket already has an associated Jira Issue Key, a comment is added to that existing issue; if it does not exist, a new issue is automatically created in Jira based on the Zendesk ticket.

- [0251-notion-clockify-invoices.json](workflows/0251-notion-clockify-invoices.json)
  Description: This automated flow automatically creates a record in a Notion database every time a new invoice is generated in Clockify.

- [0252-flujo-captura-emails.json](workflows/0252-flujo-captura-emails.json)
  Description: This automated flow processes email responses by categorizing them and executing actions such as creating leads in HubSpot or marking them in Lemlist, in addition to sending notifications via Slack.

- [0253-hubspot-zendesk-company-sync.json](workflows/0253-hubspot-zendesk-company-sync.json)
  Description: This flow synchronizes HubSpot company data with the Zendesk API to keep organizations updated.

- [0254-hubspot-zendesk-sync.json](workflows/0254-hubspot-zendesk-sync.json)
  Description: This automated flow synchronizes data between HubSpot and Zendesk systems, checking if the ticket exists before performing actions like creating or updating contacts and tickets.

- [0255-iss-position-rabbitmq.json](workflows/0255-iss-position-rabbitmq.json)
  Description: This flow sends the updated position of the International Space Station (ISS) to a RabbitMQ queue every minute.

- [0256-github-light-alert.json](workflows/0256-github-light-alert.json)
  Description: This flow activates a switch in Home Assistant to red when there are updates in the GitHub repository.

- [0257-analisis-domini.json](workflows/0257-analisis-domini.json)
  Description: This automated flow takes a list of web domains (divided into batches), queries their content via HTTP requests, asks OpenAI to analyze the text to obtain key properties about value proposition, audience, and sector, and then saves this classified data in a Google Sheets spreadsheet.

- [0258-rabbitmq-sms-alert.json](workflows/0258-rabbitmq-sms-alert.json)
  Description: This flow receives messages from a RabbitMQ queue containing a 'temp' field, and if it exceeds 50 degrees Celsius, sends an SMS alert using Vonage.

- [0259-mysql-export-spreadsheet.json](workflows/0259-mysql-export-spreadsheet.json)
  Description: This flow automates the download of data from a specific MySQL table in Excel format, thus allowing storage of the catalog content.

- [0260-woo-product-flow.json](workflows/0260-woo-product-flow.json)
  Description: This automated flow allows creating a product in WooCommerce, updating its stock, and then getting the created product.

- [0261-mattermost-woocommerce-pedido.json](workflows/0261-mattermost-woocommerce-pedido.json)
  Description: This automated flow sends a message in the specified Mattermost channel when a new order is created in WooCommerce, including the buyer's name and the first product purchased.

- [0262-diagnostico-migracion-n8n.json](workflows/0262-diagnostico-migracion-n8n.json)
  Description: This flow identifies workflows affected by the n8n 0.214.3 migration in nodes with multiple outputs.

- [0263-egoi-suscriptor-creacion_actualizacion_recuperacion.json](workflows/0263-egoi-suscriptor-creacion_actualizacion_recuperacion.json)
  Description: This flow allows creating a subscriber in a specific e-goi list, then modifying some fields (like the name), and finally getting the updated contact details.

- [0264-mattermost-language-inclusion.json](workflows/0264-mattermost-language-inclusion.json)
  Description: This automated flow detects gender-exclusive terms (like 'guys', 'bros') in incoming messages and suggests the use of inclusive language via a predefined message in Mattermost.

- [0265-customer-data-count-set.json](workflows/0265-customer-data-count-set.json)
  Description: This manual flow counts the number of customer records in the n8n Training database.

- [0266-mssql-to-csv.json](workflows/0266-mssql-to-csv.json)
  Description: This flow allows executing a SQL query on the 'SalesLT.ProductCategory' table and saving the result as a CSV file with that name.

- [0267-imagenes-line-merge.json](workflows/0267-imagenes-line-merge.json)
  Description: This automated flow downloads multiple sample images via HTTP requests and merges them into a single result containing all concatenated binary data.

- [0268-uProc_telegram_screenshot.json](workflows/0268-uProc_telegram_screenshot.json)
  Description: This automated flow allows creating screenshots of websites and automatically sending them to a Telegram channel.

- [0269-download-pdf-robot.json](workflows/0269-download-pdf-robot.json)
  Description: This automated flow allows downloading a specific PDF file from Deutsche Bahn when a GET request is received on the webhook.

- [0270-postgres-google-sheets-sync.json](workflows/0270-postgres-google-sheets-sync.json)
  Description: This automated flow listens for updates in the users table and filters them to save only those that do not have @n8n.io in the email.

- [0271-linear-alert-slack.json](workflows/0271-linear-alert-slack.json)
  Description: This automated flow detects urgent incident events in Linear and sends an alert to a specific Slack channel to notify the team.

- [0272-datos-aleatorios.json](workflows/0272-datos-aleatorios.json)
  Description: This workflow performs an HTTP request to an API service to obtain data and saves it in Google Sheets.

- [0273-outlook-automated-email.json](workflows/0273-outlook-automated-email.json)
  Description: This automated flow allows a user to automatically create an email draft in Outlook, attach a downloaded image, and send it.

- [0274-discord-calendar-sync.json](workflows/0274-discord-calendar-sync.json)
  Description: This flow automatically synchronizes events scheduled in Discord to Google Calendar. It detects if an event already exists or is new and proceeds to update or create it respectively.

- [0275-sheets-discord-table.json](workflows/0275-sheets-discord-table.json)
  Description: This automated flow sends a formatted ASCII table message from Google Sheets to a Discord channel when there are changes (new row or update) in the specified spreadsheet.

- [0276-notion-outlook-sync.json](workflows/0276-notion-outlook-sync.json)
  Description: This automated flow synchronizes Outlook calendar events with database pages in Notion by verifying and creating/updating based on the event ID.

- [0277-products-to-xml.json](workflows/0277-products-to-xml.json)
  Description: This flow randomly queries 16 products from a MySQL database and transforms them into two different XML files, maintaining the structure with tags using set functions.

- [0278-paul_graham_essays.json](workflows/0278-paul_graham_essays.json)
  Description: This automated flow allows extracting and summarizing the texts of up to three recent essays published on Paul Graham's website.

- [0279-gmail-appointment-autoresponder.json](workflows/0279-gmail-appointment-autoresponder.json)
  Description: This automated flow processes unread emails to determine if they are appointments and responds appropriately.

- [0280-line-chatbot-agent.json](workflows/0280-line-chatbot-agent.json)
  Description: This automated flow uses a LINE chatbot to handle messages, store context in buffer memory, and access OpenAI's GPT-4o-mini model. It also integrates the SerpAPI tool for web search.

- [0281-llm-chain-ai-agent.json](workflows/0281-llm-chain-ai-agent.json)
  Description: This flow executes an LLM chain to generate responses and uses an AI agent with tools like Wikipedia to improve searches in conversations.

- [0282-llm-output-structured.json](workflows/0282-llm-output-structured.json)
  Description: This flow processes requests with large language models (LLM) to generate structured responses, using an automatic parser that attempts to correct invalid outputs with another LLM model.

- [0283-cadena-q-a.json](workflows/0283-cadena-q-a.json)
  Description: This flow sets up a chain processing to perform question-based searches and answer them, using assignments as input.

- [0284-n8n-chat-conversational.json](workflows/0284-n8n-chat-conversational.json)
  Description: This flow allows the conversation to maintain context with the latest messages thanks to buffer memory storage. It uses search tools (SerpAPI) and Wikipedia to improve agent responses.

- [0285-bitcoin-chat-flow-pinecone.json](workflows/0285-bitcoin-chat-flow-pinecone.json)
  Description: This flow allows loading data from the Bitcoin White Paper from Google Drive into Pinecone using GPT-4o-mini embeddings and answering questions using vector tools.

- [0286-slack-gilfoyle-chatbot.json](workflows/0286-slack-gilfoyle-chatbot.json)
  Description: This n8n flow processes messages in Slack via a Webhook, using the Gilfoyle agent to generate sarcastic and irritable responses on defined topics. The system verifies if the message is human and not bot-generated, uses tools like web search (SerpAPI) and Wikipedia information as needed, and maintains conversation memory using the channel ID as a key.

- [0287-google-drive-summarizer.json](workflows/0287-google-drive-summarizer.json)
  Description: This flow allows downloading and processing a Google Drive file to generate summaries using summarization chains.

- [0288-line-ai-color-bot.json](workflows/0288-line-ai-color-bot.json)
  Description: This automated flow allows a line chatbot to generate responses with specific functions like selecting random colors.

- [0289-mistral-cadena-hf.json](workflows/0289-mistral-cadena-hf.json)
  Description: This flow uses a basic LLM chain connected to Hugging Face's Mistral-7B-Instruct-v0.1 model along with generation options like temperature and penalty.

- [0290-feedback-openai-google.json](workflows/0290-feedback-openai-google.json)
  Description: This automated flow allows collecting customer feedback through a form and using OpenAI to analyze its sentiment. The results, along with the form data, are combined and automatically saved in a Google sheet.

- [0291-telegram-n8n-control.json](workflows/0291-telegram-n8n-control.json)
  Description: This flow allows activating or deactivating n8n workflows via Telegram commands. Messages must start with '/start' or '/stop' followed by the workflow name to perform the corresponding action.

- [0292-snowflake-csv-insert.json](workflows/0292-snowflake-csv-insert.json)
  Description: This flow loads data from a CSV file hosted on Azure Blob Storage, processes it, and then inserts the specified columns into Snowflake's 'users' table.

- [0293-email-validation-flow.json](workflows/0293-email-validation-flow.json)
  Description: This flow automatically verifies the validity of an email address captured via a form and adds the contact to a list if it is valid.

- [0294-twentycrm-eventos-canales.json](workflows/0294-twentycrm-eventos-canales.json)
  Description: This automated flow gets notifications/events from TwentyCRM and distributes them through preferred channels according to the event type.

- [0295-brightdata-screenshot.json](workflows/0295-brightdata-screenshot.json)
  Description: This automated flow allows capturing a web screen using Bright Data Web Unlocker and saving it to a local file.

- [0296-calendario-eventos.json](workflows/0296-calendario-eventos.json)
  Description: This automated flow allows adding events to the Gmail calendar specified manually when starting an execution.

- [0297-imagen-texto-automatico.json](workflows/0297-imagen-texto-automatico.json)
  Description: This automated flow allows downloading an image from the internet and adding text to it.

- [0298-cheems-discord.json](workflows/0298-cheems-discord.json)
  Description: This automated flow sends humorous reminders on Discord every Friday and Thursday morning at 9 AM, plus messages every 30 minutes also using the same webhook.

- [0299-airtable-mailchimp-sync.json](workflows/0299-airtable-mailchimp-sync.json)
  Description: This automated flow synchronizes entries from the Users table in Airtable with a specific Mailchimp list, converting the Email field into a subscriber and using Name as the value for the FNAME field.

- [0300-nextcloud-deck-email.json](workflows/0300-nextcloud-deck-email.json)
  Description: This automated flow reads emails via IMAP, cleans their content, and creates cards in Nextcloud Deck.

- [0301-telegram-journal-reminder.json](workflows/0301-telegram-journal-reminder.json)
  Description: This automated flow sends a Telegram reminder every morning to reflect on the activities performed the previous day.

- [0302-zoom-from-google-calendar.json](workflows/0302-zoom-from-google-calendar.json)
  Description: This automated flow creates Zoom meetings based on filtered events from Google Calendar.

- [0303-google-sheets-sync.json](workflows/0303-google-sheets-sync.json)
  Description: This automated flow reads data from a Google spreadsheet and periodically synchronizes it with the Mailchimp subscriber list.

- [0304-email-xml-to-http-post.json](workflows/0304-email-xml-to-http-post.json)
  Description: This automated flow extracts an email from IMAP, processes the XML content in the first attachment, and sends the data via an HTTP POST request to an API.

- [0305-certificate-email-batch.json](workflows/0305-certificate-email-batch.json)
  Description: This automated flow reads a CSV file, splits it into batches, and uses its content to send emails with previously generated certificates.

- [0306-twake-message-trigger.json](workflows/0306-twake-message-trigger.json)
  Description: This automated flow is manually triggered and sends an empty message to Twake without specifying content or channel.

- [0307-send-sms-from-airtable.json](workflows/0307-send-sms-from-airtable.json)
  Description: This automated flow allows sending SMS using Twilio to numbers and names stored in Airtable.

- [0308-typeform-whatsapp-message.json](workflows/0308-typeform-whatsapp-message.json)
  Description: This automated flow allows receiving new Typeform responses and sending them formatted to WhatsApp using Twilio.

- [0309-twitter-mentions-rocketchat.json](workflows/0309-twitter-mentions-rocketchat.json)
  Description: This flow checks Twitter every minute for mentions of '@n8n_io' and, if new, sends a message to RocketChat with the tweet text and its URL.

- [0310-twitter-monitor.json](workflows/0310-twitter-monitor.json)
  Description: This flow monitors recent mentions of 'n8n_io' on Twitter and posts them to a Mattermost channel.

- [0311-website-stock-alert.json](workflows/0311-website-stock-alert.json)
  Description: This flow periodically checks the content of an HTTP response to determine if it contains 'Out Of Stock', sending notifications on Discord according to the results.

- [0312-wordpress-csv-export.json](workflows/0312-wordpress-csv-export.json)
  Description: This automated flow extracts and exports all WordPress articles to a CSV file.

- [0313-insertar-productos-desde-excel.json](workflows/0313-insertar-productos-desde-excel.json)
  Description: This flow reads an Excel file (.xls), interprets it, and then inserts each row of this file into the 'product' table of a PostgreSQL database.

- [0314-bill-bot.json](workflows/0314-bill-bot.json)
  Description: This automated flow processes invoices received via WhatsApp or Telegram, analyzes details with the Mindee API, stores information in Google Sheets, and sends an SMS notification.

- [0315-icypeas-email-verifier.json](workflows/0315-icypeas-email-verifier.json)
  Description: This automated flow processes lists of emails in batches from a Google sheet, using API credentials for authentication and making HTTP POST requests to the Icypeas platform.

- [0316-icypeas-email-search.json](workflows/0316-icypeas-email-search.json)
  Description: This flow processes real-time search results from Icypeas and stores the email, first name, and last name.

- [0317-phantom-airtable-store.json](workflows/0317-phantom-airtable-store.json)
  Description: This flow allows executing a Phantom Buster operation and storing the structured result in Airtable using the 'append' option.

- [0318-line-chatbot-memory.json](workflows/0318-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using memory and custom tools.

- [0319-fastmail-mailbox-email.json](workflows/0319-fastmail-mailbox-email.json)
  Description: This automated flow gets and processes mailbox and email information from Fastmail's JMAP API.

- [0320-dingtalk-tfs-automation.json](workflows/0320-dingtalk-tfs-automation.json)
  Description: This automated flow sends a DingTalk notification when a new Pull Request is created in Azure DevOps, using MySQL database maps to translate user accounts.

- [0321-airtable-image-automation.json](workflows/0321-airtable-image-automation.json)
  Description: This automated flow searches and updates records in Airtable to add images via URL.

- [0322-notion-bookmark-tracker.json](workflows/0322-notion-bookmark-tracker.json)
  Description: This automated flow receives URLs via a POST webhook and creates them as new pages in a specified Notion database.

- [0323-crm_lead_automation.json](workflows/0323-crm_lead_automation.json)
  Description: This automated flow detects email responses to marketing campaigns, evaluates prospect interest using artificial intelligence, and if interested, creates a new deal in Pipedrive.

- [0324-google-drive-file-share.json](workflows/0324-google-drive-file-share.json)
  Description: This n8n flow allows getting and sharing Google Drive files in public mode via manual execution.

- [0325-binance_telegram_price_alert.json](workflows/0325-binance_telegram_price_alert.json)
  Description: This automated flow monitors price changes on Binance and sends formatted alerts via Telegram when a cryptocurrency experiences a change greater than or equal to 15% (different from the initial mention) in the last 24 hours.

- [0326-spotify-discover-weekly-archiver.json](workflows/0326-spotify-discover-weekly-archiver.json)
  Description: This automated flow archives tracks from the 'Discover Weekly' playlist on Spotify by comparing and adding only songs that are not already present.

- [0327-tron_wallet_monitor.json](workflows/0327-tron_wallet_monitor.json)
  Description: This automated flow queries and processes recent transactions in a TRC20 wallet, displaying formatted information about received tokens.

- [0328-analytics-airtable.json](workflows/0328-analytics-airtable.json)
  Description: This automated flow gets historical web analytics data and stores it in an Airtable table.

- [0329-blog-medium-publisher.json](workflows/0329-blog-medium-publisher.json)
  Description: This automated flow extracts content from WordPress blogs to publish on Medium using HTML and HTTP requests.

- [0330-monday-error-tracking.json](workflows/0330-monday-error-tracking.json)
  Description: This automated flow detects when an error occurs during execution processing, captures its stack trace and message, and then automatically updates an item in Monday.com with this information.

- [0331-eleven-openai-audio-translation.json](workflows/0331-eleven-openai-audio-translation.json)
  Description: This flow executes a process of converting and transcribing French text to speech and then to English.

- [0332-strava-beeminder-datapoint-flow.json](workflows/0332-strava-beeminder-datapoint-flow.json)
  Description: This flow adds a data point in Beeminder when a new activity is created in Strava.

- [0333-bored-api-activity-tool.json](workflows/0333-bored-api-activity-tool.json)
  Description: This flow allows an AI agent to call a subflow to extract information about type and number of participants, then use that information to filter activities via the Bored API and return the combined result in a chatbot response.

- [0334-line-chatbot-memory.json](workflows/0334-line-chatbot-memory.json)
  Description: This automated flow processes chat messages in LINE using contextualized memory to maintain a significant history and calls the specified assistant to generate responses.

- [0335-sendgrid-contact-flow.json](workflows/0335-sendgrid-contact-flow.json)
  Description: This flow allows creating, updating, and getting contact information in SendGrid via the SendGrid node.

- [0336-google-contacts-test.json](workflows/0336-google-contacts-test.json)
  Description: This automated flow allows creating a contact in Google Contacts with n8n's data and then updating and immediately getting that same contact.

- [0337-empresa-noticias-automatizacion.json](workflows/0337-empresa-noticias-automatizacion.json)
  Description: This automated flow seeks to keep informed about the latest news of companies related to each scheduled meeting in the daily calendar, sending a summary by email at the agreed time.

- [0338-hubspot-exact-enrichment.json](workflows/0338-hubspot-exact-enrichment.json)
  Description: This automated flow allows n8n to automatically enrich contact profiles in HubSpot with additional information obtained from the ExactBuyer API.

- [0339-hubspot-engagement-automation.json](workflows/0339-hubspot-engagement-automation.json)
  Description: This automated flow sends follow-up emails to uncontacted contacts in HubSpot using Gmail and logs the engagement.

- [0340-telegram-ai-bot.json](workflows/0340-telegram-ai-bot.json)
  Description: This automated flow allows a Telegram bot to maintain a conversation using the OpenAI GPT-4o-mini model, sending responses with emojis.

- [0341-hubspot-seguimiento-email.json](workflows/0341-hubspot-seguimiento-email.json)
  Description: This automated flow searches for contacts in HubSpot that have been previously contacted and have only had one engagement, to send them a polite follow-up email.

- [0342-lead-verification-madkudu-slack.json](workflows/0342-lead-verification-madkudu-slack.json)
  Description: This automated flow verifies and qualifies leads using Hunter and integrates with MadKudu to send Slack notifications when customer fit exceeds a threshold.

- [0343-validacion-email-madkudu-n8n.json](workflows/0343-validacion-email-madkudu-n8n.json)
  Description: This automated flow validates emails with Hunter and scores leads with MadKudu via a webhook form, sending email alerts only if the score is greater than 60.

- [0344-form-contacto-telegram.json](workflows/0344-form-contacto-telegram.json)
  Description: This automated flow collects emails via a contact form, verifies their validity using Hunter API, and if valid, calculates the customer fit score via MadKudu. The results are sent to Telegram for quick follow-up.

- [0345-google-indexing-sitemap.json](workflows/0345-google-indexing-sitemap.json)
  Description: This automated flow extracts URLs from an XML sitemap and sends them in batches to the Google Indexing API to notify about updates.

- [0346-lead-alertas-n8n.json](workflows/0346-lead-alertas-n8n.json)
  Description: This automated flow monitors new hot companies in HubSpot and sends alerts to a specific user in Slack every 5 minutes.

- [0347-euro-exchange-rate-processor.json](workflows/0347-euro-exchange-rate-processor.json)
  Description: This automated flow gets and processes real-time euro exchange rates via an HTTP request to the European Central Reserve API.

- [0348-mail-api-scraper.json](workflows/0348-mail-api-scraper.json)
  Description: This flow allows extracting email addresses from any website via an HTTP request to a webhook.

- [0349-stoic-twitter-bot.json](workflows/0349-stoic-twitter-bot.json)
  Description: This automated flow allows creating and publishing viral tweets with a personal style about modern stoicism, scheduled randomly every 6 hours.

- [0350-slack-idea-capture.json](workflows/0350-slack-idea-capture.json)
  Description: This automated flow allows a user to send a travel request (slash command) '/idea' in Slack to automatically create a database page in Notion and request additional details.

- [0351-slack-feature-ideas.json](workflows/0351-slack-feature-ideas.json)
  Description: This automated flow allows receiving ideas via Slack commands and adding them to a Google sheet with a link to add details.

- [0352-rss-monitor.json](workflows/0352-rss-monitor.json)
  Description: This flow periodically reviews (every hour) multiple specific RSS feeds, checks if articles were published in the last hour cycle, and sends emails with the news.

- [0353-gmail-archivar.json](workflows/0353-gmail-archivar.json)
  Description: This automated flow archives email messages and threads in the inbox that are not marked as favorites (starred) since the last execution, leaving only the starred ones.

- [0354-todoist-recurring-tasks.json](workflows/0354-todoist-recurring-tasks.json)
  Description: This n8n flow processes tasks from a Todoist project to create new tasks in the inbox daily, based on parameters like specific days and hours. It analyzes task descriptions, checks if they match the current day, generates new tasks, and deletes those that already exist.

- [0355-slack-error-notification.json](workflows/0355-slack-error-notification.json)
  Description: This automated flow sends a Slack notification when a workflow fails, reporting the workflow name and execution URL.

- [0356-sync-n8n-notion.json](workflows/0356-sync-n8n-notion.json)
  Description: This flow automatically synchronizes n8n workflows with the Notion system every 15 minutes.

- [0357-auto-seo-keywords-generator.json](workflows/0357-auto-seo-keywords-generator.json)
  Description: This automated flow receives a query via Webhook, generates related keywords using the Google Suggest API, and formats them for use in SEO research.

- [0358-telegram-error-notification.json](workflows/0358-telegram-error-notification.json)
  Description: This automated flow sends a Telegram notification when an error occurs in another workflow or process.

- [0359-crea_actualiza_y_consulta_usuario_gsuite.json](workflows/0359-crea_actualiza_y_consulta_usuario_gsuite.json)
  Description: This flow creates a user in Google Workspace using the admin node and then updates and gets it to confirm changes.

- [0360-gmail-error-alert.json](workflows/0360-gmail-error-alert.json)
  Description: This automated flow detects errors in other job executions and sends a detailed email to the user via the configured Gmail account.

- [0361-workflow-error-config.json](workflows/0361-workflow-error-config.json)
  Description: This flow updates the error handling configuration in workflows via Postgres and uses predefined variables to exclude certain cases.

- [0362-country-query-formatter.json](workflows/0362-country-query-formatter.json)
  Description: This automated flow queries country data via GraphQL using a code as a parameter, then extracts the country object and converts it into formatted text to be sent via a URL.

- [0363-highlevel-address-verification.json](workflows/0363-highlevel-address-verification.json)
  Description: This automated flow verifies the postal address of new contacts in HighLevel via a verification API and adds a tag depending on whether it is valid or not.

- [0364-documentacion-n8n-automatica.json](workflows/0364-documentacion-n8n-automatica.json)
  Description: This automated flow allows users to generate documentation for their n8n workflows using the OpenAI API.

- [0365-reporte-fallas-telegram.json](workflows/0365-reporte-fallas-telegram.json)
  Description: This flow reviews failed executions of a task in the last week and sends a summary via Telegram.

- [0366-slack-to-clickup-tasks.json](workflows/0366-slack-to-clickup-tasks.json)
  Description: This flow analyzes a JSON file

- [0367-tweets-publicador.json](workflows/0367-tweets-publicador.json)
  Description: This automated flow extracts and publishes the latest Tweets stored in a Google sheet named 'Tweets' every 6 hours.

- [0368-youtube-upload-create-playlist.json](workflows/0368-youtube-upload-create-playlist.json)
  Description: This automated flow allows uploading a video to YouTube and creating a playlist, adding the ID of the newly uploaded video.

- [0369-youtube-description-automation.json](workflows/0369-youtube-description-automation.json)
  Description: This automated flow allows adding a predefined text to the description of all your YouTube videos while maintaining the existing original content and checking if updates are necessary.

- [0370-flujo-confirmacion-transferencia.json](workflows/0370-flujo-confirmacion-transferencia.json)
  Description: This automated flow checks if a record already exists in Grist before creating a new one based on a webhook input with a 'Confirmed' field to ensure the operation is only performed when necessary.

- [0371-telegram-chatbot-ai.json](workflows/0371-telegram-chatbot-ai.json)
  Description: This automated flow allows a Telegram chatbot to generate intelligent responses based on received messages and send those responses along with AI-generated images.

- [0372-xml-to-json-converter.json](workflows/0372-xml-to-json-converter.json)
  Description: This flow allows converting XML files to JSON, has multiple connections, and handles errors with custom HTTP responses.

- [0373-nasa-api-credentials.json](workflows/0373-nasa-api-credentials.json)
  Description: This flow uses a form to dynamically enter the NASA API key, which is then used in the NASA connection node via expressions.

- [0374-crm-address-verification.json](workflows/0374-crm-address-verification.json)
  Description: This flow verifies the validity of the postal address of new contacts imported from Groundhogg CRM using the Lob API. If the result indicates it is deliverable, it adds a tag and updates the contact; if not, it adds another tag and triggers manual or automated actions.

- [0375-email-validation-domain-extraction.json](workflows/0375-email-validation-domain-extraction.json)
  Description: This flow tests email address validation and extracts the domain using n8n's native functions.

- [0376-unsubscribe-mautic.json](workflows/0376-unsubscribe-mautic.json)
  Description: This automated flow allows users to unsubscribe from marketing emails by replying to a specific message in Gmail, integrating with Mautic CRM to manage their data.

- [0377-google_slides_image_replacer.json](workflows/0377-google_slides_image_replacer.json)
  Description: This automated flow allows replacing images in Google Slides presentations via a POST request with parameters like presentation_id, image_key, and image_url.

- [0378-elevenlabs-text-to-speech.json](workflows/0378-elevenlabs-text-to-speech.json)
  Description: This flow verifies input parameters and uses the ElevenLabs API to generate voice responses from the provided text.

- [0379-Keap-Lob-Address-Verification.json](workflows/0379-Keap-Lob-Address-Verification.json)
  Description: This automated flow verifies the postal address of a contact in Keap using Lob via an API, and automatically updates fields or applies tags depending on whether it is deliverable or not.

- [0380-hacker-news-monitor.json](workflows/0380-hacker-news-monitor.json)
  Description: This flow checks every day at 1:00 PM if there are featured 'Show HN' articles on the Hacker News homepage and sends an email with the most recent ones.

- [0381-airtable-seo-metatags.json](workflows/0381-airtable-seo-metatags.json)
  Description: This automated flow searches Airtable for records that do not have a URL or title/metadata description defined and updates those fields with real values extracted from web content.

- [0382-webhook-google-sheets.json](workflows/0382-webhook-google-sheets.json)
  Description: This flow reads data from a specific Google Sheets spreadsheet when a request is received via the webhook.

- [0383-workflow-estado.json](workflows/0383-workflow-estado.json)
  Description: This automated flow executes a main workflow with trigger intervals and checks in Redis if the workflow is currently running to avoid multiple concurrent instances.

- [0384-api-flutterflow-data.json](workflows/0384-api-flutterflow-data.json)
  Description: This n8n flow is used to create an API in FlutterFlow that receives data from a data store (like 'Customer Datastore') and inserts it into a variable before returning it as JSON to the application.

- [0385-convertapi-docx2pdf.json](workflows/0385-convertapi-docx2pdf.json)
  Description: This automated flow downloads a DOCX file from a URL and converts it to PDF using ConvertAPI credentials, then writes it to the file system.

- [0386-ejecuciones_workflow.csv](workflows/0386-ejecuciones_workflow.csv)
  Description: This flow allows getting all workflow execution records and converting them into a CSV file.

- [0387-convertir-docx-a-pdf.json](workflows/0387-convertir-docx-a-pdf.json)
  Description: This automated flow allows converting DOCX files linked from a remote URL to PDF format using ConvertAPI.

- [0388-scrappey-test-schedule.json](workflows/0388-scrappey-test-schedule.json)
  Description: This automated flow schedules a test process at certain intervals to extract data via the Scrappey API.

- [0389-chat-movie-recommendations.json](workflows/0389-chat-movie-recommendations.json)
  Description: This flow allows a conversational AI to interact with MongoDB data via aggregations, maintain context in buffer memory, and log user preferences.

- [0390-convertapi-xlsx-to-pdf-test.json](workflows/0390-convertapi-xlsx-to-pdf-test.json)
  Description: This automated flow allows testing the conversion of XLSX files to PDF using a public API.

- [0391-convertir-pptx-a-json.json](workflows/0391-convertir-pptx-a-json.json)
  Description: This automated flow downloads a demo PPTX file, converts it to PDF using authenticated ConvertAPI, and saves the result as 'document.pdf' on the local system.

- [0392-proteccion-pdf-google.json](workflows/0392-proteccion-pdf-google.json)
  Description: This flow automatically downloads a demo PDF and writes it to disk or uploads it to Google Drive.

- [0393-2310_webpage-to-pdf_test.json](workflows/0393-2310_webpage-to-pdf_test.json)
  Description: This test flow converts the webpage https://n8n.io into a PDF file and saves it as document.pdf.

- [0394-manejador-errores.json](workflows/0394-manejador-errores.json)
  Description: This flow checks if a workflow is active and does not have an error handler configured. If so, it updates its settings by assigning the default error handler ID via an API call.

- [0395-html-to-pdf-automation.json](workflows/0395-html-to-pdf-automation.json)
  Description: This automated flow converts HTML documents to PDF using ConvertAPI.

- [0396-convertapi-jpg-to-pdf.json](workflows/0396-convertapi-jpg-to-pdf.json)
  Description: This automated flow downloads a demo image and converts the JPG file to PDF format using the ConvertAPI.

- [0397-convertapi-pdf-conversion.json](workflows/0397-convertapi-pdf-conversion.json)
  Description: This automated flow downloads a demo file, converts it to PDFA format using the ConvertAPI, and writes the result to a PDFA file.

- [0398-agente-ia-herramientas.json](workflows/0398-agente-ia-herramientas.json)
  Description: This demonstrative flow allows an AI agent to interact with web tools and APIs to provide activities or information via messages.

- [0399-workflow-credentials-agent.json](workflows/0399-workflow-credentials-agent.json)
  Description: This flow allows storing n8n configurations in a SQLite database and querying them via a conversational agent.

- [0400-gmail-attachment-upload.json](workflows/0400-gmail-attachment-upload.json)
  Description: This flow detects new emails in Gmail with attachments, extracts each file individually, and uploads it to the root folder of Google Drive.

- [0401-line-chatbot-memory-automation.json](workflows/0401-line-chatbot-memory-automation.json)
  Description: This automated flow extracts data from specific Webhook nodes in an execution and passes it to the processing node.

- [0402-github-release-monitor.json](workflows/0402-github-release-monitor.json)
  Description: This flow checks the latest releases of selected GitHub repositories daily and sends a Slack notification if a new version is available.

- [0403-stripe-checkout-filters.json](workflows/0403-stripe-checkout-filters.json)
  Description: This automated flow retrieves all Stripe checkout sessions from the last month and allows filtering them based on custom fields like nickname or job_title.

- [0404-systeme-io-contact-flow.json](workflows/0404-systeme-io-contact-flow.json)
  Description: This automated flow collects all contacts and tags from Systeme.io using pagination to handle API limitations.

- [0406-zigbee-backups-schedule.json](workflows/0406-zigbee-backups-schedule.json)
  Description: This automated flow performs weekly backups (every Monday at 2:45 am) via MQTT messages, decodes the JSON response to get the ZIP file, and automatically uploads it to an SFTP server.

- [0407-n8n-totp-authentication.json](workflows/0407-n8n-totp-authentication.json)
  Description: This flow verifies the validity of an entered TOTP code using the provided secret.

- [0408-confluence-template-automation.json](workflows/0408-confluence-template-automation.json)
  Description: This flow automates the creation of a page in Confluence from a predefined template. The base URL and template ID parameters are fixed, while the target space and parent relationships are configured via a set node.

- [0409-todoist-categorizador.json](workflows/0409-todoist-categorizador.json)
  Description: This automated flow takes tasks from the Todoist inbox, discards subtasks, and uses AI to assign them to specific projects based on predefined priorities or tags them as 'other'.

- [0411-backup-n8n-workflows.json](workflows/0411-backup-n8n-workflows.json)
  Description: This automated flow performs backups of n8n workflows to a Bitbucket repository, thus avoiding exceeding rate limits.

- [0412-zendesk-unassigned-tickets-to-slack.json](workflows/0412-zendesk-unassigned-tickets-to-slack.json)
  Description: This automated flow queries unassigned and pending Zendesk tickets, formats their information, and sends a summary message to a specific Slack channel.

- [0413-analisis-multimodal-cv.json](workflows/0413-analisis-multimodal-cv.json)
  Description: This flow analyzes PDF resumes using visual models to detect 'bypass' with hidden prompts, thus preventing candidates from trying to trick the system.

- [0414-passport-photo-validator.json](workflows/0414-passport-photo-validator.json)
  Description: This automated flow verifies the validity of passport photos according to British government criteria using an AI model.

- [0415-siri-ai-agente.json](workflows/0415-siri-ai-agente.json)
  Description: This workflow allows interacting with an AI agent via the 'Hey Siri' command on mobile devices.

- [0416-zotero-pagination-bibliography.json](workflows/0416-zotero-pagination-bibliography.json)
  Description: This automated flow allows downloading collections and items (articles) from the Zotero API via a loop that handles pagination.

- [0417-image-composite-overlay.json](workflows/0417-image-composite-overlay.json)
  Description: This automated flow allows composing two images, overlaying one on top of the other in the center of the base image.

- [0418-fastmail-masked-email-generator.json](workflows/0418-fastmail-masked-email-generator.json)
  Description: This automated flow allows creating masked email addresses using the Fastmail API. It is initiated by a POST request to a webhook, which processes and generates the requested addresses with the necessary parameters.

- [0419-google-ads-keyword-data.json](workflows/0419-google-ads-keyword-data.json)
  Description: This workflow uses the Google Ads API to get historical data and search volumes for up to 20 keywords.

- [0420-xero-webhook-verifier.json](workflows/0420-xero-webhook-verifier.json)
  Description: This flow verifies the authenticity of incoming Xero webhooks by calculating and comparing the HMAC hash using SHA-256 to ensure integrity and security.

- [0421-alertas-azure-task.json](workflows/0421-alertas-azure-task.json)
  Description: This automated flow periodically checks Elasticsearch for the number of alerts, and if it exceeds a specific threshold (likely 0), it automatically creates an incident in Azure DevOps.

- [0422-image-processing-flow.json](workflows/0422-image-processing-flow.json)
  Description: This flow processes images uploaded to ImgBB, optimizes them with ReSmush.it, and stores the optimized version in ImgBB.

- [0423-spotify-youtube-sync.json](workflows/0423-spotify-youtube-sync.json)
  Description: This flow synchronizes songs between YouTube and Spotify playlists by adding only new ones without duplicates.

- [0424-prism-elastic-alert-email.json](workflows/0424-prism-elastic-alert-email.json)
  Description: This automated flow periodically checks security alerts in an Elastic system and sends emails notifying about detected incidents.

- [0425-n8n-flujos-backup-github.json](workflows/0425-n8n-flujos-backup-github.json)
  Description: This automated flow backs up n8n workflows to a git repository by checking changes and updating files.

- [0426-token-management.json](workflows/0426-token-management.json)
  Description: This flow uses persistent static variables to manage an access token that expires after 1 minute. When the token expires (due to verification in 'if token is valid'), a new one is requested via HTTP and updates the static data.

- [0427-zoom-wordpress-schedule.json](workflows/0427-zoom-wordpress-schedule.json)
  Description: This automated flow schedules a new Zoom meeting every 360 days and updates a WordPress post with its URL.

- [0428-libros-historicos-extractor.json](workflows/0428-libros-historicos-extractor.json)
  Description: This flow extracts information about historical books from Toscrape using Jina.ai and uses the OpenAI ChatGPT model to analyze the data, finally saving the results in a Google sheet.

- [0429-webflow-to-gsheets.json](workflows/0429-webflow-to-gsheets.json)
  Description: This automated flow collects data from form submissions in Webflow and automatically adds them as new rows to a Google spreadsheet.

- [0430-calvin-hobbes-discord-daily-comic.json](workflows/0430-calvin-hobbes-discord-daily-comic.json)
  Description: This automated flow publishes Calvin and Hobbes comic strips on Discord, with Korean translations alongside the original dialogues.

- [0431-blue-sky-rss.json](workflows/0431-blue-sky-rss.json)
  Description: This flow automates the publication of RSS articles converted into BlueSky multimedia posts.

- [0432-meal-plan-generator.json](workflows/0432-meal-plan-generator.json)
  Description: This automated flow generates a random meal plan based on specific recipes for future days and sends it to the Mealie API.

- [0433-github-release-monitor.json](workflows/0433-github-release-monitor.json)
  Description: This automated flow checks the latest n8n releases on GitHub daily, converts any markdown content to HTML, and sends an email notifying if a new version is available.

- [0434-convertkit-list-subscribe-tag.json](workflows/0434-convertkit-list-subscribe-tag.json)
  Description: This manual flow allows adding a subscriber to a ConvertKit list specifically identified by its ID, creating an associated tag, and adding the same existing subscriber in that list to the new tag.

- [0435-openai-supabase-sql-chat.json](workflows/0435-openai-supabase-sql-chat.json)
  Description: This flow allows a user to interact conversationally with a PostgreSQL database on Supabase using OpenAI functions to execute queries and generate responses.

- [0436-cleaner-old-executions.json](workflows/0436-cleaner-old-executions.json)
  Description: This n8n flow checks for old executions and deletes them if they are older than 10 days.

- [0437-youtube-transcript-summary.json](workflows/0437-youtube-transcript-summary.json)
  Description: This flow allows extracting a YouTube video ID from its URL using a regular expression, getting its main data like title and description, concatenating transcripts if available, and sending a formatted message with the summary via Telegram.

- [0438-twitch-stream-checker.json](workflows/0438-twitch-stream-checker.json)
  Description: This flow checks if a specific Twitch user is live streaming by querying their GraphQL API.

- [0439-hn-lookback-bot.json](workflows/0439-hn-lookback-bot.json)
  Description: This automated flow allows reviewing top Hacker News stories from the current day and previous days across multiple years, analyzing them with an LLM model to categorize them into themes using Google Gemini, and sending the formatted summary in Markdown via Telegram.

- [0440-jira_telegram_webhook.json](workflows/0440-jira_telegram_webhook.json)
  Description: This flow sends updates via Telegram according to the type of event in Jira (creation, change, or assignment).

- [0441-youtube-video-summarizer.json](workflows/0441-youtube-video-summarizer.json)
  Description: This automated flow allows getting a YouTube video transcript and generating its summary using language models.

- [0442-transform-image-to-lego-line.json](workflows/0442-transform-image-to-lego-line.json)
  Description: This automated flow allows receiving an image via a LINE webhook, analyzing it with GPT-4O-MINI to create the appropriate prompt in DALL-E 3, generating the allegorized image as if it were made of LEGO, and finally sending this new image to the user via Line.

- [0443-comparativo-llm-pdf.json](workflows/0443-comparativo-llm-pdf.json)
  Description: This automated flow allows testing and comparing the ability of Gemini 2.0 Flash and Claude 3.5 Sonnet models to extract information directly from PDFs using predefined credentials.

- [0444-google-drive-pii-detector.json](workflows/0444-google-drive-pii-detector.json)
  Description: This automated flow detects the creation of new CSV files in Google Drive, identifies columns containing personal data (PII) using OpenAI, deletes those columns, and re-uploads the processed file.

- [0445-sentry-release-flow.json](workflows/0445-sentry-release-flow.json)
  Description: This automated flow allows creating a new version of a project in Sentry and then getting all existing versions.

- [0446-telegram-welcome-bidirectional.json](workflows/0446-telegram-welcome-bidirectional.json)
  Description: This automated flow allows a Telegram bot to send personalized greetings in Spanish when someone joins or leaves a chat, using webhooks.

- [0447-perplexity-ai-chat.json](workflows/0447-perplexity-ai-chat.json)
  Description: This automated flow sends a request to the Perplexity AI API using the provided key, including parameters like prompt and domains for filtering.

- [0448-upwork-jobs-sync.json](workflows/0448-upwork-jobs-sync.json)
  Description: This flow queries recent Upwork jobs using Apify and MongoDB. If the hours are between 2-15, it checks if similar entries already exist by title and budget before inserting them.

- [0449-rankmath-update-product.json](workflows/0449-rankmath-update-product.json)
  Description: This automated flow runs when the user clicks 'Test flow' and updates the SEO metadata of a specific product using the Rank Math plugin API.

- [0450-gitlab-merge-request-flow.json](workflows/0450-gitlab-merge-request-flow.json)
  Description: This automated flow checks if an open merge request with the same branch name exists and, if so, closes it; if it does not exist, it creates a new one.

- [0451-backups-workflow-google.json](workflows/0451-backups-workflow-google.json)
  Description: This automated flow performs periodic workflow backups to Google Drive every 4 hours and deletes the original files to keep storage optimized.

- [0452-wordpress-posts-csv.json](workflows/0452-wordpress-posts-csv.json)
  Description: This automated flow allows getting published WordPress posts in JSON format and subsequently converting them into a CSV file to automatically upload to Google Drive.

- [0453-convertkit-form-subscribe.json](workflows/0453-convertkit-form-subscribe.json)
  Description: This workflow monitors when a new subscriber is added via the specific form number 165198 in ConvertKit.

- [0454-vps-upgrade-email-checker.json](workflows/0454-vps-upgrade-email-checker.json)
  Description: This automated flow daily executes the 'apt list --upgradable' command via SSH on a remote machine and sends an HTML formatted email if there are upgradable packages.

- [0456-keywords-analysis.json](workflows/0456-keywords-analysis.json)
  Description: This automated flow processes keywords from a Google sheet, analyzes them to determine if they contain IT software names using an AI agent, and updates the sheet with the results.

- [0457-vps-resource-monitor.json](workflows/0457-vps-resource-monitor.json)
  Description: This flow checks CPU, RAM, and disk usage on a VPS every 15 minutes via three SSH nodes executed at intervals. If any resource exceeds the 80% threshold, it sends an email with detailed information.

- [0458-google-drive-batch-upload.json](workflows/0458-google-drive-batch-upload.json)
  Description: This automated flow allows uploading multiple files to Google Drive in an organized way via a form that automatically verifies and creates the destination folder.

- [0459-imagen-gen-config.json](workflows/0459-imagen-gen-config.json)
  Description: This n8n flow allows generating custom images from parameters defined in the Set Image Properties nodes.

- [0461-milvus-rag-chatbot-flow.json](workflows/0461-milvus-rag-chatbot-flow.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation using PDF documents inserted into Milvus and RAG queries with Cohere embeddings.

- [0462-n8n-blueprint-backoff.json](workflows/0462-n8n-blueprint-backoff.json)
  Description: This flow implements an exponential backoff mechanism to handle rate limiting in the Google Sheets API, retrying an action with exponential time increments between attempts up to a maximum of 5 retries.

- [0463-add-task-google.json](workflows/0463-add-task-google.json)
  Description: This manual flow allows adding a specific Google Tasks task by clicking and executing the corresponding node.

- [0464-telegram-affirmations-daily.json](workflows/0464-telegram-affirmations-daily.json)
  Description: This automated flow executes a script every day at 9 AM to get and send a daily affirmation message via the affirmations.dev API.

- [0465-discord-webhook-message.json](workflows/0465-discord-webhook-message.json)
  Description: This automated flow allows sending a 'Hello World!' message to a Discord channel using webhooks.

- [0466-mattermost-rss-monitor.json](workflows/0466-mattermost-rss-monitor.json)
  Description: This automated flow publishes each new article from an RSS feed to the corresponding Mattermost channel, using Mastodon as an intermediary for verification.

- [0467-signl4-event-processing.json](workflows/0467-signl4-event-processing.json)
  Description: This automated flow processes pending events from the SIG SIGNL4 system every hour, reading previous data stored in a binary file and checking if they have already been resolved to send the corresponding alerts.

- [0468-syncro-clockify-tasks.json](workflows/0468-syncro-clockify-tasks.json)
  Description: This automated flow receives data via webhook and uses it to create tasks in Clockify.

- [0469-telegram-meteogram.json](workflows/0469-telegram-meteogram.json)
  Description: This automated flow allows receiving messages on Telegram about the weather and sending back a report with the current weather description, real temperature, and wind chill for the specified city.

- [0470-postgres-excel-generator.json](workflows/0470-postgres-excel-generator.json)
  Description: This flow executes a query in PostgreSQL to get product names and EAN codes, converts the result into an Excel file, and writes it.

- [0471-line-chatbot-ssh.json](workflows/0471-line-chatbot-ssh.json)
  Description: This automated flow allows a LINE chatbot to interactively request help on SSH commands and execute them on a VPS, using tools like ReAct Agent and the n8n-nodes-base extension.

- [0472-workflow-wordpress-tts.json](workflows/0472-workflow-wordpress-tts.json)
  Description: This automated flow allows getting a WordPress article, generating its summary or transcription with an AI, and converting it to audio to be inserted as multimedia content in the same post.

- [0473-line-chatbot-memory.json](workflows/0473-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation with users by storing and retrieving states.

- [0474-update-youtube-descriptions.json](workflows/0474-update-youtube-descriptions.json)
  Description: This automated flow allows inserting a specific text between two determined lines in the descriptions of all YouTube videos. It first collects all videos, then for each one, it gets its ID and searches for the text to insert based on previously defined variables.

- [0475-nocodebot-multilang.json](workflows/0475-nocodebot-multilang.json)
  Description: This automated flow allows a Telegram chatbot to maintain a contextualized conversation about open-source tools (No-Code) by integrating with a Strapi database.

- [0476-mailerlite-airtable-sync.json](workflows/0476-mailerlite-airtable-sync.json)
  Description: This flow detects when a subscriber is added to a group in MailerLite and automatically saves their name and email in an Airtable table.

- [0477-n8n-workflow-backup-schedule.json](workflows/0477-n8n-workflow-backup-schedule.json)
  Description: This automated flow performs daily backups at 1:30 AM of all n8n workflows into a JSON file and saves it in a specified Google Drive folder.

- [0478-formulario-google-docs.json](workflows/0478-formulario-google-docs.json)
  Description: This automated flow allows the user to send data through a form and have this data used to fill in text in a Google Docs document using the API.

- [0479-ideas-para-post.json](workflows/0479-ideas-para-post.json)
  Description: This automated flow reads ideas from a Google sheet, generates a post for the specified platform using OpenAI, and if it's Twitter, publishes it. It then updates the sheet with the post text.

- [0480-calendar-voice-reminder.json](workflows/0480-calendar-voice-reminder.json)
  Description: This automated flow searches for upcoming appointments and generates synthesized voice reminders to send to attendees.

- [0481-shopify-orders-sync.json](workflows/0481-shopify-orders-sync.json)
  Description: This automated flow gets Shopify orders via API and stores them in Google Sheets.

- [0482-invitaciones-google-sheets-n8n.json](workflows/0482-invitaciones-google-sheets-n8n.json)
  Description: This automated flow compares users in n8n with data from a Google Sheets spreadsheet to send invitations to those who do not exist on the platform.

- [0483-mailchimp-google-sheets-newsletter.json](workflows/0483-mailchimp-google-sheets-newsletter.json)
  Description: This automated flow processes new newsletter subscriptions in Google Sheets and adds them as active contacts in Mailchimp.

- [0484-merge-pdfs-from-urls.json](workflows/0484-merge-pdfs-from-urls.json)
  Description: This flow allows combining multiple PDFs from URLs into a single file using a custom JavaScript function.

- [0485-library-install.json](workflows/0485-library-install.json)
  Description: This automated flow allows installing Node.js libraries (specified as a comma-separated list) by executing npm commands.

- [0486-telegram-chinese-tutor.json](workflows/0486-telegram-chinese-tutor.json)
  Description: This automated flow allows a Telegram chatbot to efficiently practice the Chinese language through multiple-choice exercises, using memory to maintain conversation context.

- [0487-shopify-fulfillment-auto.json](workflows/0487-shopify-fulfillment-auto.json)
  Description: This automated flow searches to filter and obtain pending fulfillment orders in Shopify for digital downloads or gift cards.

- [0488-crear_cliente_segment.json](workflows/0488-crear_cliente_segment.json)
  Description: This automated flow creates a new customer in Customer.io with the custom property 'Name' configured and then immediately adds that customer to a specified segment.

- [0489-line-n8n-assistant.json](workflows/0489-line-n8n-assistant.json)
  Description: This flow implements an AI assistant in n8n that responds to LINE messages using GPT models and MCP tools.

- [0490-mediamarkt-deals.json](workflows/0490-mediamarkt-deals.json)
  Description: This automated flow processes and sends product offers classified by category via web scraping.

- [0491-ai-chat-agent-memory.json](workflows/0491-ai-chat-agent-memory.json)
  Description: This flow uses an AI agent with memory to maintain context during interaction and perform BigQuery queries on shipping data.

- [0492-notion-tasks-slack.json](workflows/0492-notion-tasks-slack.json)
  Description: This flow checks Notion To Dos every hour at 8 am, looks for tasks assigned to user 'NAME', and if any are pending, sends a direct notification on Slack to a specific user.

- [0493-proyectos-coste-missing.json](workflows/0493-proyectos-coste-missing.json)
  Description: This automated flow executes a weekly SQL query to get active external projects with missing budgeted cost and sends personalized emails to different cost center teams based on their names.

- [0494-monitor-alertas-postgres.json](workflows/0494-monitor-alertas-postgres.json)
  Description: This automated flow periodically checks records in the PostgreSQL database where the value is greater than 70 and has not been notified, then updates the status of said records to mark them as notified and informs via SMS using Twilio.

- [0495-gumroad-sale-trigger.json](workflows/0495-gumroad-sale-trigger.json)
  Description: This automated flow is triggered when a sale occurs on Gumroad.

- [0496-gmail-news-to-linkedin.json](workflows/0496-gmail-news-to-linkedin.json)
  Description: This automated flow allows a user to receive Gmail newsletters and use OpenAI to identify top news, summarize them, and generate LinkedIn posts with an intelligent style and subtle humor.

- [0497-incident-integracion.json](workflows/0497-incident-integracion.json)
  Description: This automated flow integrates incident monitoring with tracking in Jira, notifying the team via Mattermost channels.

- [0498-resume-screener.json](workflows/0498-resume-screener.json)
  Description: This n8n flow listens for new emails in Gmail with attachments, extracts text from the PDF, evaluates it using an AI agent based on LangChain and OpenAI, and logs structured results (name, email, LinkedIn, and score) in a Google sheet.

- [0499-tts-generation.json](workflows/0499-tts-generation.json)
  Description: This automated flow allows executing a Python script to generate MP3 audio files based on predefined text and voice.

- [0500-pagerduty-mattermost-update.json](workflows/0500-pagerduty-mattermost-update.json)
  Description: This automated flow allows a system to receive a notification via webhook containing the ID of an incident in PagerDuty. Once the information is received, it automatically updates the incident status to 'acknowledged' and sends a confirmation to the corresponding Mattermost channel.

- [0501-pager-duty-jira-integracion.json](workflows/0501-pager-duty-jira-integracion.json)
  Description: This automated flow updates the status of an incident in PagerDuty and its corresponding issue in Jira, then notifies Mattermost channels.

- [0502-chart-upload.json](workflows/0502-chart-upload.json)
  Description: This flow dynamically creates a line chart from JSON data and uploads it to Google Drive.

- [0503-error-alertas.json](workflows/0503-error-alertas.json)
  Description: This automated flow detects errors in jobs and sends notifications via both SMS and Mattermost.

- [0504-sharepoint-upload.json](workflows/0504-sharepoint-upload.json)
  Description: This automated flow uploads files to Microsoft SharePoint using Graph API.

- [0505-openai-image-generation-edit.json](workflows/0505-openai-image-generation-edit.json)
  Description: This workflow allows generating an initial image using the OpenAI API, converting it to binary format, and then editing it by adding elements like horns using the same API.

- [0506-facebook-lead-to-klicktipp.json](workflows/0506-facebook-lead-to-klicktipp.json)
  Description: This automated flow imports data from Facebook Lead Ads forms and synchronizes it in KlickTipp to start email campaigns.

- [0507-whatsapp-crm-automation.json](workflows/0507-whatsapp-crm-automation.json)
  Description: This automated flow collects data from WhatsApp via a webhook, saves it in a Google sheet, and adds the contact to the CRM with the tag 'New Lead'. Subsequently, it sends an email and a WhatsApp message to welcome the customer.

- [0508-google-autocomplete-letter.json](workflows/0508-google-autocomplete-letter.json)
  Description: This flow combines an initial keyword with all letters of the alphabet to get multiple Google autocompletions and returns the complete list.

- [0509-html-pdf-compress.json](workflows/0509-html-pdf-compress.json)
  Description: This automated flow allows converting an HTML block into a PDF file and compressing it, as well as processing a specific URL to generate another PDF from it.

- [0510-html-pdf-png-conversion.json](workflows/0510-html-pdf-png-conversion.json)
  Description: This n8n flow allows testing HTML to PDF conversion and its subsequent conversion to PNG by clicking the 'Test workflow' button.

- [0511-outlook-jira-ai-tickets.json](workflows/0511-outlook-jira-ai-tickets.json)
  Description: This automated flow monitors email in the Outlook inbox for support tickets, classifies and prioritizes them with artificial intelligence, then creates a ticket in Jira using that structured data. Sticky notes provide instructions and context on how the flow works.

- [0512-web-scraper-structured.json](workflows/0512-web-scraper-structured.json)
  Description: This automated flow allows extracting structured information about web products (name, description, price, rating, and number of reviews) from cleaned HTML pages. It uses Google Sheets to get lists of URLs to process, cleans the content with a Node.js script before sending it to the GPT-4 model via OpenRouter, and finally appends the structured JSON results to another sheet in the document.

- [0513-email-tracking-pixel.json](workflows/0513-email-tracking-pixel.json)
  Description: This automated flow allows detecting when an email is opened by sending a transparent PNG image via webhook, capturing parameters like userId to identify the sender.

- [0515-auto-iniciar-flujos-n8n.json](workflows/0515-auto-iniciar-flujos-n8n.json)
  Description: This flow allows manually starting two execution instances in n8n via the trigger. The description explains that these flows do not start automatically after import, unless they have the 'Auto start' tag and are configured for auto-deploy.

- [0516-email-classification-ai.json](workflows/0516-email-classification-ai.json)
  Description: This flow processes emails, classifies them into specific categories using OpenAI models, and extracts relevant information about candidates.

- [0517-postgres-csv-export.json](workflows/0517-postgres-csv-export.json)
  Description: This automated flow queries data from a specific table (booksRead) in PostgreSQL via a manual trigger and exports the result to a CSV file.

- [0518-google-drive-pdf-to-html.json](workflows/0518-google-drive-pdf-to-html.json)
  Description: This automated flow converts new PDF files saved in Google Drive to HTML and automatically saves them in the same folder.

- [0519-clockify-syncro-timer-sync.json](workflows/0519-clockify-syncro-timer-sync.json)
  Description: This flow synchronizes time entries between Clockify and Syncro via Google Sheets.

- [0520-daily-english-poems.json](workflows/0520-daily-english-poems.json)
  Description: This automated flow sends a random daily poem translated into British English, using the Poemist API and Telegram.

- [0521-mailchimp-subscribe.json](workflows/0521-mailchimp-subscribe.json)
  Description: This manual flow allows subscribing to the Mailchimp list with the specified email and adding predefined fields like FNAME.

- [0522-namecheap-ddns-updater.json](workflows/0522-namecheap-ddns-updater.json)
  Description: This automated flow checks every 15 minutes if the public IP has changed and automatically updates DNS records for multiple subdomains in Namecheap.

- [0523-orlen-factura-automatizada.json](workflows/0523-orlen-factura-automatizada.json)
  Description: This automated flow downloads and processes daily electronic invoices from Orlen's Gmail, uploads them to a Google Drive folder organized by year and month, marks them as read, and notifies via Slack the directory where they have been uploaded.

- [0524-mattermost-instagram-stats.json](workflows/0524-mattermost-instagram-stats.json)
  Description: This automated flow checks Instagram profile statistics (like followers and posts) every day at 8:00 AM and sends the updated data in a formatted message with the current date and time.

- [0525-the-hive-alerts.json](workflows/0525-the-hive-alerts.json)
  Description: This automated flow checks when a new alert is created in TheHive that is not closed. If the condition is met, it sends a notification to SIGNL4 (likely to send an alarm via LINE) with the alert details and also starts an additional process if necessary.

- [0526-webhook-analisis-datos.json](workflows/0526-webhook-analisis-datos.json)
  Description: This flow analyzes a webhook to extract data and generate a response.

- [0527-3-xml-transform.json](workflows/0527-3-xml-transform.json)
  Description: This flow processes and transforms data in XML format by converting an XML string into a structured object.

- [0528-twilio_trigger.json](workflows/0528-twilio_trigger.json)
  Description: This automated flow allows manually executing actions in Twilio via an API using the manual trigger.

- [0529-active-campaign-contact.json](workflows/0529-active-campaign-contact.json)
  Description: This flow allows manually loading user information to ActiveCampaign from n8n.

- [0530-workflow-bloqueo-medio-dev-to.json](workflows/0530-workflow-bloqueo-medio-dev-to.json)
  Description: This automated flow allows sending articles to both the Medium platform and the dev.to API via an HTTP request, using configured credentials for both actions.

- [0531-webflow-form-trigger.json](workflows/0531-webflow-form-trigger.json)
  Description: This automated flow is triggered when a form is submitted on a Webflow webpage and collects the data for processing.

- [0532-hackernoon-extractor.json](workflows/0532-hackernoon-extractor.json)
  Description: This manual flow extracts article titles and links from the Hacker Noon homepage (hackernoon.com) via HTML analysis.

- [0533-digitalocean-create-droplet.json](workflows/0533-digitalocean-create-droplet.json)
  Description: This automated flow creates a Droplet instance on DigitalOcean using specified parameters and authenticating with a personal access token.

- [0534-speech-recognition-wit-ai.json](workflows/0534-speech-recognition-wit-ai.json)
  Description: This automated flow uses the Read Binary File node to read a WAV file at the specified path and sends it to the Wit.ai API via an HTTP POST request for processing.

- [0535-pay-pal-batch-operation.json](workflows/0535-pay-pal-batch-operation.json)
  Description: This flow executes an operation on the PayPal account using the provided batch ID.

- [0536-signl4-test-alert.json](workflows/0536-signl4-test-alert.json)
  Description: This manual flow allows triggering a predefined alert in SIGNL4 by clicking the 'execute' button, sending a sample message and title.

- [0537-shopify-odoo-product-sync.json](workflows/0537-shopify-odoo-product-sync.json)
  Description: This flow automatically synchronizes new products from Shopify with Odoo. It is activated when a product is created in Shopify (event 'products/create') and searches if it already exists in Odoo using the default code. If it does not exist, it creates it; if it already exists, it verifies the product data to perform an update.

- [0538-postgres-query.json](workflows/0538-postgres-query.json)
  Description: This automated flow allows executing a SQL select command in a PostgreSQL database via manual activation.

- [0539-banner-cocktail.json](workflows/0539-banner-cocktail.json)
  Description: This automated flow displays a random cocktail recipe every Friday at 6:00 PM via a message with an image in Rocket.Chat.

- [0540-paypal-billing-plan-activated-trigger.json](workflows/0540-paypal-billing-plan-activated-trigger.json)
  Description: This automated flow allows n8n to receive notifications when PayPal activates a billing plan.

- [0541-github-notifications-monitor.json](workflows/0541-github-notifications-monitor.json)
  Description: This automated flow periodically queries (every minute) user notifications on GitHub and if they exist, sends a formatted summary to a Discord application.

- [0542-asana-tweet-event-trigger.json](workflows/0542-asana-tweet-event-trigger.json)
  Description: This automated flow allows receiving updates when an event related to tweets occurs in Asana.

- [0543-postmark-email-events-trigger.json](workflows/0543-postmark-email-events-trigger.json)
  Description: This flow collects updates for specific Postmark events for emails, such as bounces or opens.

- [0544-n8n-daily-ai-news.json](workflows/0544-n8n-daily-ai-news.json)
  Description: This automated flow searches for articles related to artificial intelligence (AI) using NewsAPI and GNews APIs, merges them, and uses GPT-4 to summarize and translate them into traditional Chinese while keeping technical terms in English.

- [0545-google-page-entity-extraction.json](workflows/0545-google-page-entity-extraction.json)
  Description: This flow analyzes the HTML content of any webpage to extract structured data about entities recognized by Google.

- [0546-thehive-email-iocs.json](workflows/0546-thehive-email-iocs.json)
  Description: This automated flow processes incoming emails via IMAP, analyzes them with Cortex to detect indicators of compromise (IoCs), and creates corresponding observables in TheHive for each identified IoC type.

- [0547-wallabag-ttrss-sync.json](workflows/0547-wallabag-ttrss-sync.json)
  Description: This automated flow is used to save articles marked as starred in TT-RSS to the Wallabag application.

- [0548-telegram-journal-saver.json](workflows/0548-telegram-journal-saver.json)
  Description: This automated flow captures user responses in Telegram to save daily entries in a spreadsheet.

- [0549-github-stars-slack.json](workflows/0549-github-stars-slack.json)
  Description: This automated flow monitors changes in stars of the 'n8n' GitHub repository and sends real-time messages to a Slack channel.

- [0550-zammad-tickets-summary.json](workflows/0550-zammad-tickets-summary.json)
  Description: This automated flow allows querying the number of open and new tickets in Zammad, filtering them by status, and sending a summary to the Zulip support room.

- [0551-manual-aws-sns-trigger.json](workflows/0551-manual-aws-sns-trigger.json)
  Description: This manual flow allows sending a predefined message to a specific AWS SNS topic by clicking the 'execute' button.

- [0552-insertar-valor-mongodb.json](workflows/0552-insertar-valor-mongodb.json)
  Description: This manual flow inserts a specific value into the MongoDB database when executed.

- [0553-aws-ses-email.json](workflows/0553-aws-ses-email.json)
  Description: This automated flow allows sending a predefined email via AWS SES when manually executed.

- [0554-aws-sns-trigger.json](workflows/0554-aws-sns-trigger.json)
  Description: This flow uses an AWS SNS subscription to receive notifications and potentially initiate processes or workflows in response.

- [0555-manual-aws-lambda-test.json](workflows/0555-manual-aws-lambda-test.json)
  Description: This manual flow allows triggering a specific AWS Lambda via a click action.

- [0556-msg91-sms-flow.json](workflows/0556-msg91-sms-flow.json)
  Description: This automated flow allows sending SMS using the MSG91 service via manual activation.

- [0557-facebook_datos_basicos.json](workflows/0557-facebook_datos_basicos.json)
  Description: This flow manually gets the basic personal data (first and last name) of the current user on Facebook via an API call.

- [0558-google-drive-download.json](workflows/0558-google-drive-download.json)
  Description: This automated flow allows downloading a Google Drive file and saving it locally with a specific name.

- [0559-mailchimp-subscribe-alert.json](workflows/0559-mailchimp-subscribe-alert.json)
  Description: This flow activates an action when someone subscribes to the specified Mailchimp list.

- [0560-trigger-cockpit-sample.json](workflows/0560-trigger-cockpit-sample.json)
  Description: This automated flow allows initiating a manual process and immediately connecting it with the Cockpit node to visualize data from the 'samplecollection' collection.

- [0561-flujo-verificacion-email-hunter.json](workflows/0561-flujo-verificacion-email-hunter.json)
  Description: This automated flow verifies the email using the Hunter API when manually activated.

- [0562-mqtt-trigger.json](workflows/0562-mqtt-trigger.json)
  Description: This automated flow receives messages from an MQTT queue when a message is published to the corresponding topic.

- [0563-mailjet-correo-test.json](workflows/0563-mailjet-correo-test.json)
  Description: This manual flow allows sending an email using Mailjet. Predefined text, subject, sender address, and recipient address are included.

- [0564-line-chatbot-memory.json](workflows/0564-line-chatbot-memory.json)
  Description: This flow is triggered when an email is sent via the Mailjet API.

- [0565-mailgun-email-sender-test.json](workflows/0565-mailgun-email-sender-test.json)
  Description: This manual flow allows sending a predefined email message when the 'execute' button is clicked.

- [0566-hacker-news-trigger.json](workflows/0566-hacker-news-trigger.json)
  Description: This automated flow allows manually executing an action to get data from all Hacker News categories.

- [0567-github-monitor-repo.json](workflows/0567-github-monitor-repo.json)
  Description: This flow monitors any activity in the 'n8n-io/n827-docs' GitHub repository via a webhook, using predefined credentials for the API.

- [0568-gitlab-trigger-n8n-docs.json](workflows/0568-gitlab-trigger-n8n-docs.json)
  Description: This flow monitors events in the GitLab n8n-io/n8n-docs repository via a webhook.

- [0569-bitbucket-push-monitor.json](workflows/0569-bitbucket-push-monitor.json)
  Description: This flow is automatically triggered when there is a push event in the 'test' Bitbucket repository.

- [0570-travis-ci-trigger-build.json](workflows/0570-travis-ci-trigger-build.json)
  Description: This manual flow allows initiating a build in Travis CI by clicking, integrating the service in an automated way.

- [0571-acuity-appointment-trigger.json](workflows/0571-acuity-appointment-trigger.json)
  Description: This flow is triggered when a user schedules an appointment via Acuity Scheduling.

- [0572-invoice-ninja-getall.json](workflows/0572-invoice-ninja-getall.json)
  Description: This manual flow allows getting all invoices from the account using the Invoice Ninja API service.

- [0573-invoice-creation-trigger.json](workflows/0573-invoice-creation-trigger.json)
  Description: This automated flow is triggered when an invoice is created in the Invoice Ninja API.

- [0574-clockify-event-poller.json](workflows/0574-clockify-event-poller.json)
  Description: This automated flow periodically monitors the specified Clockify workspace every minute, waiting for any event to occur to trigger subsequent actions.

- [0575-copper-project-trigger.json](workflows/0575-copper-project-trigger.json)
  Description: This automated flow is triggered by a Copper webhook when 'new' events occur in 'project' type resources.

- [0576-eventbrite-order-triggers.json](workflows/0576-eventbrite-order-triggers.json)
  Description: This flow activates an integration when events related to ticket orders occur in Eventbrite, such as creation, update, or refund.

- [0577-rundeck-job-trigger.json](workflows/0577-rundeck-job-trigger.json)
  Description: This flow allows manually initiating the execution of a specific job in Rundeck by clicking the 'execute' button.

- [0578-calendly-eventos-monitor.json](workflows/0578-calendly-eventos-monitor.json)
  Description: This flow monitors Calendly events to receive notifications when a participant is created or canceled in an appointment.

- [0579-jotform-trigger.json](workflows/0579-jotform-trigger.json)
  Description: This automated flow is triggered when a specific JotForm form (ID: 202012795501445) is completed, using authentication credentials with the JotForm API.

- [0580-xero-get-all.json](workflows/0580-xero-get-all.json)
  Description: This manual flow initiates execution to get all items from Xero via OAuth2 authentication.

- [0582-bannerbear-imagen-manual.json](workflows/0582-bannerbear-imagen-manual.json)
  Description: This automated flow allows a user to manually initiate the generation of an image using the Bannerbear service with a specific identifier and predefined parameters for text, color, and background.

- [0583-wordpress-get-all.json](workflows/0583-wordpress-get-all.json)
  Description: This flow allows manually executing an action that gets all articles from a WordPress instance via its API credentials.

- [0584-shopify-order-trigger.json](workflows/0584-shopify-order-trigger.json)
  Description: This active flow is triggered when a new order is created in Shopify via webhook.

- [0585-shopify-get-all-records.json](workflows/0585-shopify-get-all-records.json)
  Description: This flow manually executes the 'execute' trigger which then gets all records from a Shopify account.

- [0586-typeform-seleccion-automatizada.json](workflows/0586-typeform-seleccion-automatizada.json)
  Description: This automated flow allows logging Typeform form selections in Airtable.

- [0587-paddle-coupon-creator.json](workflows/0587-paddle-coupon-creator.json)
  Description: This automated flow allows creating a coupon offer in Paddle using specific parameters.

- [0588-survey-monkey-trigger.json](workflows/0588-survey-monkey-trigger.json)
  Description: This automated flow is triggered when a new response is created in the specific SurveyMonkey survey.

- [0589-zoho-crm-get-all.json](workflows/0589-zoho-crm-get-all.json)
  Description: This manual flow initiates execution to get all records from Zoho CRM via OAuth2 authentication.

- [0590-keap-contact-all.json](workflows/0590-keap-contact-all.json)
  Description: This flow manually activates an execution that gets all contacts from Keap.

- [0591-line-keap-integracion-automatica.json](workflows/0591-line-keap-integracion-automatica.json)
  Description: This automated flow initiates processes in n8n when a new contact is added in Keap.

- [0592-monday-board-data.json](workflows/0592-monday-board-data.json)
  Description: This flow executes a manual action in n8n to get data from a specific board in Monday.com.

- [0593-line-chatbot-memory.json](workflows/0593-line-chatbot-memory.json)
  Description: This automated flow allows a LINE chatbot to maintain a contextualized conversation through persistence in Redis.

- [0594-spacex-graphql-query.json](workflows/0594-spacex-graphql-query.json)
  Description: This manual flow queries the SpaceX API via GraphQL to get details about the latest launches and spacecraft data.

- [0595-box-folder-execution.json](workflows/0595-box-folder-execution.json)
  Description: This flow automatically executes an action on a specific Box folder when the 'execute' button is clicked.

- [0596-cfp-trello-cards.json](workflows/0596-cfp-trello-cards.json)
  Description: This flow selects applicants from a CFP event with a score greater than 15 in Airtable and creates Trello cards from the form information using Bannerbear to generate advertising images.

- [0597-cocktaildb-json-xml-conversion.json](workflows/0597-cocktaildb-json-xml-conversion.json)
  Description: This automated flow converts JSON response data from the CocktailDB API to XML.

- [0598-expense-receipt-automation.json](workflows/0598-expense-receipt-automation.json)
  Description: This automated flow collects receipts via Typeform, extracts relevant information using Mindee, and stores the data in Airtable.

- [0599-box-folder-file-events.json](workflows/0599-box-folder-file-events.json)
  Description: This automated flow is triggered when files or folders are moved or downloaded in a specific Box folder.

- [0600-one-drive-folder-creation.json](workflows/0600-one-drive-folder-creation.json)
  Description: This manual flow allows creating a folder in OneDrive by clicking the 'execute' button.

- [0601-excel-trigger.json](workflows/0601-excel-trigger.json)
  Description: This flow executes a manual process by clicking the start button, which then queries all available data via the Microsoft Excel connector.

- [0602-helpscout-mailbox-fetcher.json](workflows/0602-helpscout-mailbox-fetcher.json)
  Description: This flow allows getting all emails stored in a specific mailbox via integration with HelpScout.

- [0603-jira-trigger-any-event.json](workflows/0603-jira-trigger-any-event.json)
  Description: This flow monitors any event in Jira Software Cloud via a web connection.

- [0604-sms-alert-error-notification.json](workflows/0604-sms-alert-error-notification.json)
  Description: This workflow sends an SMS alert when a specific workflow fails in its execution.

- [0605-mandrill-email.json](workflows/0605-mandrill-email.json)
  Description: This flow allows sending an email using the 'welcomeemailv2' template from the Mandrill node by clicking 'execute'.

- [0606-n8n-rocks-crypto-example.json](workflows/0606-n8n-rocks-crypto-example.json)
  Description: This manual flow allows executing an encryption operation on the string 'n8n rocks!' simply by clicking.

- [0607-manual-execute-date.json](workflows/0607-manual-execute-date.json)
  Description: This automated flow allows the user to manually start a process with the specific date '14/02/2020' using DD/MM/YYYY format.

- [0608-analisis-imagen-http.json](workflows/0608-analisis-imagen-http.json)
  Description: This manual flow allows downloading an image from a specific URL and extracting information about it.

- [0609-trigger-leer-imagen-binaria.json](workflows/0609-trigger-leer-imagen-binaria.json)
  Description: This flow allows loading binary files like images by clicking the trigger.

- [0610-read-images-trigger.json](workflows/0610-read-images-trigger.json)
  Description: This automated flow allows a user to manually initiate an execution, which reads binary files (specifically jpg images) from the /data/lol directory.

- [0611-telegram-cocktails-daily.json](workflows/0611-telegram-cocktails-daily.json)
  Description: This automated flow sends a random cocktail from TheCocktailDB daily at 8:00 PM via a photo with its recipe.

- [0612-workflow-n8n-581.json](workflows/0612-workflow-n8n-581.json)
  Description: This flow starts with a manual trigger, processes data through a function that returns two objects (with IDs 0 and 1), and then uses a conditional node to evaluate if the 'value1' value matches the expected results.

- [0613-manual-trigger-renamer.json](workflows/0613-manual-trigger-renamer.json)
  Description: This flow is manually triggered and then sets a value for the key 'somevalue', which is later renamed to 'newkey'.

- [0614-read-rss-feed.json](workflows/0614-read-rss-feed.json)
  Description: This automated flow allows executing the reading of a specific RSS feed via a manual button.

- [0615-send-email-example.json](workflows/0615-send-email-example.json)
  Description: This manual flow allows sending a predefined email by clicking the execution button.

- [0616-pdf-binario-lector.json](workflows/0616-pdf-binario-lector.json)
  Description: This automated flow, when 'execute' is clicked, reads a locally stored binary PDF file and processes it.

- [0618-flujo-email-imap.json](workflows/0618-flujo-email-imap.json)
  Description: This automated flow allows reading emails from an IMAP server.

- [0619-trigger-workflow.json](workflows/0619-trigger-workflow.json)
  Description: This manual flow allows initiating the execution of another workflow by clicking the button.

- [0620-58_telegram_coktai_random.json](workflows/0620-58_telegram_coktai_random.json)
  Description: This automated flow captures Telegram messages using a webhook. It then makes a GET request to TheCocktailDB API to get a random cocktail and extracts its image and name.

- [0621-crear-tabla-y-insertar.json](workflows/0621-crear-tabla-y-insertar.json)
  Description: This manual flow creates a table in CrateDB if it doesn't exist and then inserts a record with predefined values.

- [0622-crear-tabla-json.json](workflows/0622-crear-tabla-json.json)
  Description: This flow executes a SQL query to create a table named 'test' with id and name columns, then sets a set of values that includes that data.

- [0623-postgres-create-set-insert.json](workflows/0623-postgres-create-set-insert.json)
  Description: This automated flow starts with a manual click that executes a SQL query to create a table called 'test' in PostgreSQL. Then, it takes the output of that creation and uses it as input to set values in the Set node (specifically, it expects to set a numerical value for 'id' and a fixed string for 'name'). Finally, these values are sent to another PostgreSQL operation.

- [0624-mocean-sms.json](workflows/0624-mocean-sms.json)
  Description: This automated flow allows sending a text message (SMS) via the Mocean service through manual activation.

- [0625-facebook_comments_flow.json](workflows/0625-facebook_comments_flow.json)
  Description: This flow gets the most recent messages and comments from posts on a Facebook page according to the initial configuration.

- [0626-github-release-slack-notification.json](workflows/0626-github-release-slack-notification.json)
  Description: This automated flow monitors new releases in the 'Mesdocteurs/mda-admin-partner-api' GitHub repository and sends a notification message on Slack to the 'extranet-md' channel.

- [0627-figma-jira-sync.json](workflows/0627-figma-jira-sync.json)
  Description: This flow detects updates in Figma versions via the Commit plugin webhook and adds a comment to the specific Jira issue JAJ-368 with relevant details.

- [0628-perplexity-research.json](workflows/0628-perplexity-research.json)
  Description: This automated flow searches and extracts information related to a specific query using the Perplexity AI API, formatting the result to get clean content.

- [0629-chatbot-pizza-order.json](workflows/0629-chatbot-pizza-order.json)
  Description: This flow allows a chatbot to handle pizza orders by maintaining conversational memory and using tools like a calculator, product menu, and order history.

- [0630-telegram-bash-automated-response.json](workflows/0630-telegram-bash-automated-response.json)
  Description: This automated flow allows an automatic response to be sent when a message is received on the Telegram bot (bash-dash).

- [0631-manual-github-profile-request.json](workflows/0631-manual-github-profile-request.json)
  Description: This flow allows manually triggering a request to the GitHub API to get a repository profile.

- [0632-slack-github-email-query.json](workflows/0632-slack-github-email-query.json)
  Description: This automated flow queries user information and their latest contributions on GitHub via GraphQL, processes the found emails (filtering those not corresponding to a real user), and sends a formatted message with this data to the specified Slack channel.

- [0633-syncro-ticket-proyecto.json](workflows/0633-syncro-ticket-proyecto.json)
  Description: This flow synchronizes the status of unresolved tickets from an external source with their corresponding projects in Clockify.

- [0634-dos_pasos_google_sheets.json](workflows/0634-dos_pasos_google_sheets.json)
  Description: This automated flow allows the user to initiate manual execution and then append data in Google Sheets.

- [0635-api-reqres-interactions.json](workflows/0635-api-reqres-interactions.json)
  Description: This flow makes a GET request to the reqres.in user API, followed by a POST to create a user, and finally a PATCH to update their job.

- [0636-wp-post-automation.json](workflows/0636-wp-post-automation.json)
  Description: This automated flow creates a new post in WordPress and immediately updates the content afterwards.

- [0637-60_n8n_mysql_purge_older_records.json](workflows/0637-60_n8n_mysql_purge_older_records.json)
  Description: This flow automatically deletes old execution records (older than one month) in the MySQL database to optimize storage.

- [0638-mattermost-chatbot-response.json](workflows/0638-mattermost-chatbot-response.json)
  Description: This automated flow uses a Mattermost webhook to process messages and send notifications with information stored using the Set node.

- [0639-dropbox-http-image.json](workflows/0639-dropbox-http-image.json)
  Description: This n8n flow allows interaction with Dropbox via an HTTP request, first listing files from a directory and then uploading a specific file.

- [0640-helpscout-customer-created.json](workflows/0640-helpscout-customer-created.json)
  Description: This flow specifically listens for the 'customer.created' event in HelpScout using an OAuth webhook.

- [0641-nextcloud-http-image-upload.json](workflows/0641-nextcloud-http-image-upload.json)
  Description: This flow allows downloading an image from an HTTP server and then uploading it to the 'n8n' folder in NextCloud, as well as saving it directly with the specified name.

- [0642-hubspot-trigger-dghert3.json](workflows/0642-hubspot-trigger-dghert3.json)
  Description: This automated flow is a trigger for processing specific events in HubSpot with appId dghert3.

- [0643-email-excuse-notification.json](workflows/0643-email-excuse-notification.json)
  Description: This automated flow analyzes the sender of an email, reads data from a spreadsheet to generate random excuses, and sends both results (the modified original email and Slack notifications) when the sender is Louis Litt.

- [0644-hoja-mautic-sync.json](workflows/0644-hoja-mautic-sync.json)
  Description: This automated flow reads data from a Google Sheets spreadsheet every 5 minutes and sends it as custom fields to Mautic CRM.

- [0645-sse-trigger-n8n.json](workflows/0645-sse-trigger-n8n.json)
  Description: This automated flow uses an SSE trigger node to initiate processes based on events sent from the n8n.io server.

- [0646-nuevo-triage-afinidad-lista.json](workflows/0646-nuevo-triage-afinidad-lista.json)
  Description: This flow is triggered when a new list is created in the Affinity API.

- [0647-contentful-get-all.json](workflows/0647-contentful-get-all.json)
  Description: This automated flow allows getting all content items from a Contentful instance via a manual trigger.

- [0648-unleashed-ordenes-completadas.json](workflows/0648-unleashed-ordenes-completadas.json)
  Description: This manual flow executes a query in the Unleashed system only for completed orders.

- [0649-amazon-s3-upload-list-json.json](workflows/0649-amazon-s3-upload-list-json.json)
  Description: Downloads a file from a URL, uploads it to Amazon S3, and displays all files in the bucket.

- [0650-cocktail-storage.json](workflows/0650-cocktail-storage.json)
  Description: This automated flow allows persistently storing raw data of a random drink obtained from the CocktailDB API by saving it as a JSON file.

- [0651-ejemplo-merge.json](workflows/0651-ejemplo-merge.json)
  Description: This flow analyzes sample data to merge information about name and greeting based on common language.

- [0652-product-feedback-workflow.json](workflows/0652-product-feedback-workflow.json)
  Description: This automated flow collects feedback and ratings about a product via Typeform, stores them in Airtable, and when the score is equal to 7, creates a Trello card with the provided information.

- [0653-bidirectional-sync.json](workflows/0653-bidirectional-sync.json)
  Description: This flow bidirectionally synchronizes data between the MySQL database and Pipedrive CRM.

- [0654-descargar-y-subir-imagen.json](workflows/0654-descargar-y-subir-imagen.json)
  Description: This automated flow allows downloading an image from n8n.io and uploading it directly to an FTP server via the 'execute' button.

- [0655-salesforce-update-and-note.json](workflows/0655-salesforce-update-and-note.json)
  Description: This automated flow allows updating specific fields of a record in Salesforce and adding a note to it, using the ID of the preceding record.

- [0656-teams-automation.json](workflows/0656-teams-automation.json)
  Description: This automated flow allows manually executing a sequence of actions in Microsoft Teams, where first the connection with a predefined team is initiated, then its name is updated, and finally a message is sent to a specific channel.

- [0657-linkedin-automation.json](workflows/0657-linkedin-automation.json)
  Description: This automated flow downloads an image from the specified URL and posts that image to LinkedIn along with a predefined message.

- [0658-demo-n8n-flujo.json](workflows/0658-demo-n8n-flujo.json)
  Description: This flow demonstrates how n8n can use 'function' nodes to generate data and 'switch' nodes to create response paths based on comparisons.

- [0659-error-alert-email.json](workflows/0659-error-alert-email.json)
  Description: This flow detects errors in any node and sends a detailed email to the administrator with information about the error, affected workflow, and technical details.

- [0660-taiga-issue-management.json](workflows/0660-taiga-issue-management.json)
  Description: This automated flow allows creating, updating, and getting an issue in Taiga from a manual trigger.

- [0661-weather-alert.json](workflows/0661-weather-alert.json)
  Description: This automated flow periodically queries the temperature in Berlin and sends a text message notifying to bundle up if the current 'feeling' value is below 18 degrees Celsius.

- [0662-brave-search-chatbot.json](workflows/0662-brave-search-chatbot.json)
  Description: This workflow implements a chatbot that uses GPT-4o and MCP tools to perform web searches on Brave, maintaining contextualized memory.

- [0663-iot-mqtt-influxdb-monitoring.json](workflows/0663-iot-mqtt-influxdb-monitoring.json)
  Description: This automated flow receives data from remote IoT sensors via an MQTT topic 'wokwi-weather', processes and validates temperature and humidity readings, then writes these values in JSON format to an InfluxDB database.

- [0664-tts-openai.json](workflows/0664-tts-openai.json)
  Description: This flow allows text-to-speech conversion via OpenAI's speech synthesis service.

- [0665-pipeline-etl-twitter-sentiment.json](workflows/0665-pipeline-etl-twitter-sentiment.json)
  Description: This automated flow searches for tweets with the hashtag #OnThisDay, inserts the texts into a MongoDB database, and performs sentiment analysis using Google Cloud Natural Language to store score and magnitude metrics in PostgreSQL. If the score is high, it sends a message to Slack.

- [0666-sheets-sync-every-2min.json](workflows/0666-sheets-sync-every-2min.json)
  Description: This automated flow executes an update on two Google sheets every two minutes, using previously read data.

- [0667-taiga-event-trigger.json](workflows/0667-taiga-event-trigger.json)
  Description: This flow listens for events in the specific Taiga project via a webhook trigger.

- [0668-wekan-board-creation.json](workflows/0668-wekan-board-creation.json)
  Description: This automated flow allows a user to manually execute the process of creating Wekan boards, lists, and cards.

- [0669-event-registration.json](workflows/0669-event-registration.json)
  Description: This automated flow allows registering attendees and managing their participation in n8nConf, the no-code conference.

- [0670-n8n-cron-google-sheets-mattermost.json](workflows/0670-n8n-cron-google-sheets-mattermost.json)
  Description: This automated flow executes a task in Mattermost every year on December 17th at 00:00 (UTC), using dynamic values extracted from Google Sheets.

- [0671-weather-processing.json](workflows/0671-weather-processing.json)
  Description: This automated flow processes weather data using the OpenWeatherMap API to get information about temperature, humidity, wind speed, and description.

- [0672-webhook-weather-sync.json](workflows/0672-webhook-weather-sync.json)
  Description: This automated flow receives data via webhook, extracts key information, and stores it in Airtable for later use. Subsequently, it queries the weather of the provided city using OpenWeatherMap API and sends an SMS message to a specific number with the forecast details via Twilio.

- [0673-expense-tracker-mindee-airtable.json](workflows/0673-expense-tracker-mindee-airtable.json)
  Description: This flow allows receiving a webhook with invoice data that Mindee processes and stores in an Airtable table.

- [0674-transformador-array.json](workflows/0674-transformador-array.json)
  Description: This automated flow starts with a node that generates static data in array form and then uses a custom function to transform each element of the array into an individual JSON object.

- [0675-clockify-proyecto-entrada-tiempo.json](workflows/0675-clockify-proyecto-entrada-tiempo.json)
  Description: This automated flow creates a project in Clockify with specific details and then adds a time entry using that project, maintaining context consistency.

- [0676-google-sheets-telegram-batch.json](workflows/0676-google-sheets-telegram-batch.json)
  Description: This flow processes Google Sheets entries in batches and sends each batch to Telegram.

- [0677-mindee-receipt-extractor.json](workflows/0677-mindee-receipt-extractor.json)
  Description: This automated flow processes a receipt image using Mindee to extract structured information and returns the result in JSON format.

- [0678-wufoo-form-submission.json](workflows/0678-wufoo-form-submission.json)
  Description: This automated flow receives updates when a specific form in Wufoo is submitted.

- [0679-bitcoin-monitor-sms.json](workflows/0679-bitcoin-monitor-sms.json)
  Description: This flow checks the price of Bitcoin in euros from CoinGecko every minute and sends an SMS if it exceeds 9000 EUR.

- [0680-firecrawl-markdown-extractor.json](workflows/0680-firecrawl-markdown-extractor.json)
  Description: This automated flow uses FireCrawl to perform web scraping from a provided URL, formatting the result as markdown text for easy use in applications and agents.

- [0681-notion-ai-blog-update.json](workflows/0681-notion-ai-blog-update.json)
  Description: This automated flow reacts to updates in a Notion database using DeepSeek to create SEO articles and publish them both on WordPress and update the original record.

- [0682-sitemap-json-filter.json](workflows/0682-sitemap-json-filter.json)
  Description: This flow reads a sitemap.xml file and extracts all its URLs individually.

- [0683-github-credentials-restore.json](workflows/0683-github-credentials-restore.json)
  Description: This automated flow allows restoring all instance credentials from a GitHub repository.

- [0684-hubspot-contactos-getall.json](workflows/0684-hubspot-contactos-getall.json)
  Description: This automated flow manually initiates obtaining all HubSpot contacts via the 'getAll' node of the 'contact' resource.

- [0685-coffee-bot-mattermost.json](workflows/0685-coffee-bot-mattermost.json)
  Description: This automated flow organizes employees into random groups for virtual coffee sessions every Monday and sends calendar invitations, in addition to announcing the formed groups.

- [0686-language-learning-words.json](workflows/0686-language-learning-words.json)
  Description: This automated flow extracts words from the titles of the top three Hacker News stories, translates them into German, and saves the result. It then sends an SMS with a selection of five German words along with their corresponding English term.

- [0687-medium-publication.json](workflows/0687-medium-publication.json)
  Description: This flow allows publishing articles in a Medium publication.

- [0688-youtube-raindrop-sync.json](workflows/0688-youtube-raindrop-sync.json)
  Description: This automated flow checks the specified YouTube playlist every 30 minutes and adds new videos to Raindrop as bookmarks with a title composed of the owner's name and video title, and tags them 'youtube'.

- [0689-nuevo-producto-slack.json](workflows/0689-nuevo-producto-slack.json)
  Description: This automated flow detects the creation of new products in WooCommerce and sends a notification to a Slack channel.

- [0690-github-sync-n8n.json](workflows/0690-github-sync-n8n.json)
  Description: This flow automatically synchronizes N8N workflows with a file on GitHub via comparison and deferred editing.

- [0691-openai-image-gen.json](workflows/0691-openai-image-gen.json)
  Description: This automated flow uses the OpenAI ImageGen v1 API to edit images and generate a new version based on the provided prompt.

- [0692-disco-alerta-cron.json](workflows/0692-disco-alerta-cron.json)
  Description: This flow automatically checks the disk space of the system root (host) every day at 9:00 AM and 4:00 PM. If it detects that it is above 80%, it sends an SMS alert to Twilio, notifying the exact percentage of use. Otherwise, it takes no action.

- [0693-woocommerce-order-notification.json](workflows/0693-woocommerce-order-notification.json)
  Description: This automated flow sends a Slack notification when a new order is created in WooCommerce, provided the order total is 100 or more.

- [0694-orbit-import-from-sheets.json](workflows/0694-orbit-import-from-sheets.json)
  Description: This automated flow imports member and activity data from Google Sheets to the Orbit platform using OAuth2 credentials.

- [0695-automizy-list-management.json](workflows/0695-automizy-list-management.json)
  Description: This flow automates the creation of a new list in Automizy, adds a contact with a predefined and updated email, then gets all stored contacts.

- [0696-woocommerce-refund-notification.json](workflows/0696-woocommerce-refund-notification.json)
  Description: This flow checks when a WooCommerce order is updated to refunded status and if the total is 100 or more, automatically sends a notification to the 'woo-commerce' Slack channel with specific details.

- [0697-weather-daily-update.json](workflows/0697-weather-daily-update.json)
  Description: This scheduled flow sends a daily Pushcut notification with the Berlin weather forecast.

- [0698-matrix-room-invite.json](workflows/0698-matrix-room-invite.json)
  Description: This automated flow creates a discussion room in Matrix and invites the current user if they are not already invited.

- [0699-zoom-crear-reunion.json](workflows/0699-zoom-crear-reunion.json)
  Description: This automated flow creates a meeting in Zoom using the OAuth2 API via a manual trigger.

- [0700-mautic-woocommerce-sync.json](workflows/0700-mautic-woocommerce-sync.json)
  Description: This flow checks if a WooCommerce customer exists in Mautic via a Mautic search and automatically creates or updates contacts in Mautic.

- [0701-circleci-api-trigger.json](workflows/0701-circleci-api-trigger.json)
  Description: This flow allows executing an action on the CircleCI CI/CD platform via its API by manually activating the trigger.

- [0702-daily-weather-alert.json](workflows/0702-daily-weather-alert.json)
  Description: This automated flow sends a daily SMS message with the current temperature of the user specified in OpenWeatherMap.

- [0703-new-product-twitter-telegram.json](workflows/0703-new-product-twitter-telegram.json)
  Description: This automated flow announces the creation of new products in WooCommerce on Twitter and Telegram.

- [0704-messagebird-sms-trigger.json](workflows/0704-messagebird-sms-trigger.json)
  Description: This automated flow allows sending an SMS using MessageBird via manual activation.

- [0705-google-sheets-mattermost-notification.json](workflows/0705-google-sheets-mattermost-notification.json)
  Description: This automated flow checks for new data from a Google Sheets spreadsheet every 45 minutes and sends a formatted message to the chatbot indicating the addition.

- [0706-mautic-email-validation-alert.json](workflows/0706-mautic-email-validation-alert.json)
  Description: This flow checks if a Mautic contact has an invalid or low-quality email address and, if so, sends an alert to Slack.

- [0707-Crear-Issue-Jira.json](workflows/0707-Crear-Issue-Jira.json)
  Description: This automated flow allows quickly creating a new issue in Jira Software by activating a manual trigger.

- [0708-workflow-timer-unique.json](workflows/0708-workflow-timer-unique.json)
  Description: This flow reviews the connections of a workflow in n8n to detect if there are new input items that have not been processed before, based on the timestamp.

- [0709-openweathermap-weather.json](workflows/0709-openweathermap-weather.json)
  Description: This automated flow allows the user to execute a manual process that queries the current weather data for the specified city (in this case, Berlin) via the OpenWeatherMap service.

- [0710-hoja-calc-binaria-lector.json](workflows/0710-hoja-calc-binaria-lector.json)
  Description: This flow reads a binary spreadsheet file and stores it in memory.

- [0711-phishing-analysis-n8n.json](workflows/0711-phishing-analysis-n8n.json)
  Description: This automated flow analyzes indicators of compromise in emails, extracts URLs, and scans them with VirusTotal and URLScan.io to detect potential phishing threats.

- [0712-lead-calification.json](workflows/0712-lead-calification.json)
  Description: This flow automates the qualification of new leads in a spreadsheet with Google using OpenAI's GPT-4.

- [0713-bright-data-gemini-chat-enhancement.json](workflows/0713-bright-data-gemini-chat-enhancement.json)
  Description: This flow allows Gemini AI to incorporate real-time search results from Google, Bing, or Yandex to improve chatbot responses.

- [0714-telegram-bot-ai-integration.json](workflows/0714-telegram-bot-ai-integration.json)
  Description: This automated flow processes text, audio, and image messages from a Telegram bot using webhooks and the OpenAI API for analysis.

- [0715-ai-calendar-mcp.json](workflows/0715-ai-calendar-mcp.json)
  Description: This n8n workflow uses an AI agent with OpenAI to manage conversational interactions related to Google Calendar. It allows creating, searching, updating, and deleting events, as well as modifying text between uppercase and lowercase via command-responsive tools.

- [0716-blotato-social-publishing.json](workflows/0716-blotato-social-publishing.json)
  Description: This automated flow publishes videos and images on multiple social networks like Instagram, Facebook, LinkedIn, TikTok, and more using the Blotato platform. The automation extracts content from Airtable, generates viral YouTube titles with OpenAI, and manages publication status.

- [0717-rag-chatbot-docs.json](workflows/0717-rag-chatbot-docs.json)
  Description: This automated flow allows an AI chatbot to maintain a contextualized conversation using documents stored in Google Drive and Qdrant. It extracts relevant metadata such as main topics, pain points, and key information to improve semantic search and assistant responses.

- [0718-crypto-news-sentiment-bot.json](workflows/0718-crypto-news-sentiment-bot.json)
  Description: This automated flow analyzes user queries to extract a keyword, searches for related news in multiple cryptocurrency RSS feeds, and uses GPT-4o to synthesize information and evaluate market sentiment.

- [0719-n8n_rss_photo_filter.json](workflows/0719-n8n_rss_photo_filter.json)
  Description: This flow gets new RSS feeds from The Verge that contain images.

- [0720-spotify-cancion-especifica-trigger.json](workflows/0720-spotify-cancion-especifica-trigger.json)
  Description: This manual flow initiates an action in Spotify using a specific song URI to search or play.

- [0721-error-trigger-mailgun.json](workflows/0721-error-trigger-mailgun.json)
  Description: This flow uses an error trigger to send email notifications when an error occurs in workflow execution.

- [0722-compression-to-dropbox.json](workflows/0722-compression-to-dropbox.json)
  Description: This automated flow downloads two images from HTTP URLs, compresses them into a ZIP file, and then uploads the result to Dropbox.

- [0723-gmail-expenses-mindee.json](workflows/0723-gmail-expenses-mindee.json)
  Description: This flow checks emails in Gmail containing keywords like 'expenses' or 'receipt', extracts invoice data using the Mindee API, and automatically adds the details to a Google sheet.

- [0724-rocket-message-sender.json](workflows/0724-rocket-message-sender.json)
  Description: This automated flow is manually triggered and sends a predefined message to the general RocketChat room.

- [0725-file-list-processing.json](workflows/0725-file-list-processing.json)
  Description: This automated flow is manually triggered, reads content from the file '/home/n8n/filelist.txt', splits it into lines using the newline character, stores each item in an array called 'arrData', and then uses the $runIndex variable to execute commands that print filenames based on this array.

- [0726-typeform-airtable-slack.json](workflows/0726-typeform-airtable-slack.json)
  Description: This automated flow collects responses from a Typeform form, extracts the user's name and email, adds them to Airtable, and sends a Slack notification.

- [0727-iss-tracking-timescaledb.json](workflows/0727-iss-tracking-timescaledb.json)
  Description: This automated workflow periodically queries the current position of the ISS satellite and stores it in a TimescaleDB table for temporal analysis.

- [0728-crear-usuario-intercom.json](workflows/0728-crear-usuario-intercom.json)
  Description: This automated flow allows creating a new user in Intercom by manual click.

- [0729-gmail-invoice-alert.json](workflows/0729-gmail-invoice-alert.json)
  Description: This flow checks for new invoices in Gmail using Mindee and sends Slack or email notifications if the total amount exceeds 1000.

- [0730-diaria-temperatura-push.json](workflows/0730-diaria-temperatura-push.json)
  Description: This scheduled flow executes a daily check at 9 AM to get the current temperature of Berlin and sends a Pushover notification with this information.

- [0731-security-scorecard-context-management.json](workflows/0731-security-scorecard-context-management.json)
  Description: This automated flow starts manually, generates a security scorecard for 'n8n.io', gets a single instance of the report, and downloads it from the provided URL.

- [0732-reddit-automated-posting.json](workflows/0732-reddit-automated-posting.json)
  Description: This automated flow posts an initial message on Reddit, then gets data from that post, and finally adds a comment with processed information.

- [0733-automatic-sms-trigger.json](workflows/0733-automatic-sms-trigger.json)
  Description: This automated flow allows sending a predefined SMS by clicking the 'execute' button.

- [0734-pushcut-sms-trigger.json](workflows/0734-pushcut-sms-trigger.json)
  Description: This automated flow sends an SMS when the 'Leaving Home' action is triggered via Pushcut.

- [0735-manual-trigger-translation.json](workflows/0735-manual-trigger-translation.json)
  Description: This manual flow allows executing a fixed translation of an English text to German using Google Translate.

- [0736-discourse-automated.json](workflows/0736-discourse-automated.json)
  Description: This automated flow allows creating, updating, and retrieving messages in Discourse using n8n.

- [0737-getresponse-trigger-airtable.json](workflows/0737-getresponse-trigger-airtable.json)
  Description: This automated flow is triggered by a subscriber in GetResponse for the list 'qtPk7'. When this event occurs, n8n collects the contact data and adds an entry in Airtable to the specified table.
