Prompt Template Type	What it Creates
Campaign Brief	
Content for a campaign brief including name, key message, audience description, and detailed campaign goals.

See Agent Action: Draft a Campaign Brief

Case Summary	
Summary of a Case object including a Summary, Issue, and Resolution.

See Customize the Work Summaries for Case Prompt Template.

Contextual Service Replies	
Customize your context based Service Replies prompt templates for Live Chat and Messaging Sessions.

See Customize the Context Based Service Replies Prompt Templates.

Contract Analysis	
Retrieves key information from contract documents to answer user questions or generate summaries of important clauses and sections.

See Customize Prompt Templates for Contract Search.

Common Services AI	
Content for any business purposes that requires context of current user object and its related fields. Used for enabling Einstein Summary component on the home page. For example, in Salesforce, users can create a prompt that summarises top leads and execute it through Einstein Summary directly at the homepage. This prompt template requires the EinsteinForSvcInovtAddOn add-on.

See Add Einstein Summary to a page.

Extract Product Mentions	
Identifies and retrieves product-related details from unstructured conversations such as emails, slack messages, or call transcripts. This prompt template requires Revenue Cloud and Einstein or Agentforce for Sales add-on or the Einstein 1 Sales add-on.

See Configure Extract Product Mentions Template.

Field Generation	
Content for record fields in Lightning Experience. In Salesforce, users click a button to run this prompt and populate the field with output.

See Create a Field Generation Prompt Template and Field Generation Prompt Templates in Action.

Flex	
Content for any business purposes that other templates don’t cover. Flex prompt templates let you define your own resources.

See Create a Flex Prompt Template and Flex Prompt Templates in Action.

Grounded Service Replies	
Customize your grounded Service Replies prompt templates for Live Chat and Messaging Sessions.

See Customize the Grounded Service Replies Prompt Templates.

Generate case description	
Content for the case description, including key details discussed during the interaction to help support teams understand and resolve the issue.

See Agent Action: Create Case with Enhanced Data .

Generate case subject	Content for the case subject line that summarizes the reported issue.
Intent Retrieval	Content including the user's relevant conversation history and available filter options, to help the agent understand the user's intent.
Journey Decisioning Content	Content for the journey messages that are stored in a data extension for use in Journey Builder in Marketing Cloud Engagement.
Journey Decisioning Selection	Content is the subscribers that are sorted into their optimal journeys stored in a data extension for use in Journey Builder in Marketing Cloud Engagement.
Knowledge Answers	
Customize how Agentforce agents answer questions.

See Create a Knowledge Answers Prompt Template and Agentforce Platform | Answer Questions with Knowledge.

Sales Emails	
Personalized customer email based on record data.

See Create a Sales Email Prompt Template and Draft a Sales Email with Einstein Generative AI.

Sales Pitch Coaching	Feedback for sales reps based on their transcript from a sales pitch or role play session.
Search Learning Courses	A list of recommendations based on record data in response to the user’s query.
Security Risk Analysis	
Next steps to remediate risks for instances where risks or threats are detected with Salesforce security posture data.

See Agent Action: Classify Security Risk.

Record Prioritization	
Prioritized records based on user input or available data. Using agents, the record prioritization prompt templates are used by the Prioritize Opportunities standard agent action.

See Sales | Prioritize Opportunities

Record Research	Summarized research results based on delivered prompt templates or user input. In Salesforce, users click a button on the Account Research component to run this prompt and generate the output. Record research prompt templates use the Einstein Search Web Retriever to perform research.
Record Summary	
Summarized record data for a comprehensive view of a record. Record summary prompt templates are used by the Summarize Record standard invocable action. Agents use the Summarize Record standard agent action.

See Agentforce Platform | Summarize Record

Work Summary	
Drafts a Summary, Issue, and Resolution in the Wrap Up component at the end of a Voice Call or Messaging Session.

See Customize the Summarize Messaging Session Prompt Template and Customize the Summarize Voice Call Prompt Template.


===========
Prompt Builder Limits
Learn the numerical limits of prompt templates.

Required Editions
Available in: Lightning Experience
Available in: Enterprise, Performance, and Unlimited Editions with the Einstein for Platform, or Einstein or Agentforce for Sales or Service add-on, or Agentforce Foundations
Numerical Limits
Prompt templates have these numerical limits.

Numerical Limits
Limit Description	Limit
Maximum template size	128,000 characters
Maximum number of template versions	50
Maximum number of merge fields	50
Maximum number of flow merge fields	5
Maximum number of Apex merge fields	5
Maximum number of related list merge fields	5
Maximum number of inputs in a Flex template	5
File Upload Limits
Most models support at least one file type that can be used with prompt templates.

These file limits apply across all models:

Maximum quantity: 10 images or 100 PDF pages per request
Total file size: 15MB per request
