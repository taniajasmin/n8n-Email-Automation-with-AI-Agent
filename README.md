# n8n Email Automation with AI Agent

An n8n workflow that allows an AI assistant to send personalized emails by accessing contact information from an Excel spreadsheet.

## Screenshots

### Workflow Configuration
![Workflow Configuration](https://github.com/user-attachments/assets/ba2540fe-5245-4890-abf1-43deebe798e3)

### n8n Workflow
![n8n Workflow](https://github.com/user-attachments/assets/180be9fa-2688-4deb-8606-81a2ce89d249)

### Chat Interaction
![Chat Interaction](https://github.com/user-attachments/assets/d0acaeed-5419-43a1-8936-fa989732cb2e)

### Received Email
![Received Email](https://github.com/user-attachments/assets/8d8aac00-d408-4573-a98c-fbbda9cd87ab)


### Key Features
- **Natural Language Interface**: Users request emails using everyday language.
- **Contact Database Integration**: Fetches contact emails from a spreadsheet.
- **Intelligent Email Drafting**: Generates contextually relevant email drafts.
- **Two-Step Confirmation**: Ensures emails are sent only after user approval.
- **Transparent Process**: Guides users through each step of the email sending process.
- **Flexible AI Provider**: Supports OpenAI and OpenRouter models.

## Technical Implementation

### Technologies Used
- **n8n**: For workflow automation and orchestration.
- **Excel/Google Sheets**: For managing contact information.
- **AI Models**: Initially OpenAI GPT, later migrated to OpenRouter for cost efficiency.
- **SMTP**: For email delivery.

### Workflow Components
The n8n workflow includes:
- **When Chat Message Received**: Triggers on user input.
- **AI Agent**: Manages requests and node coordination.
- **Model Selection**: Choose between OpenAI and OpenRouter.
- **Simple Memory**: Retains conversation context.
- **Contacts**: Retrieves email addresses from spreadsheets.
- **Send Email**: Sends the email upon confirmation.

## Conversation Flow Example
1. **User Request**: "Can you send a message to Tania asking if she is available for coffee today?"
2. **AI Drafts Email**: Generates a suitable email.
3. **Confirmation**: AI asks for user approval.
4. **User Approval**: User confirms with "Great, send it".
5. **Email Sending**: Retrieves Tania's email and sends the email.
6. **Confirmation**: Notifies user once the email is sent.

## AI Model Considerations
- **Initial Development**: Used OpenAI's model with free trial credits.
- **Migration**: Switched to OpenRouter for ongoing free access, showcasing adaptability and cost optimization.

## Use Cases
This automation is beneficial for:
- Personal assistants
- Team leads
- Individuals seeking quick email dispatch without app switching
- Small businesses managing customer communications

## Learning Outcomes
- Workflow automation using n8n
- Integration of AI, databases, and communication tools
- Prompt engineering for practical AI applications
- Designing conversational flows with confirmations
- Utilization of both commercial and open-source AI models

## Future Improvements
- **Calendar Integration**: Check contact availability.
- **Attachments & Templates**: Support for email attachments and predefined templates.
- **Response Tracking**: Monitor and log email responses.
- **Enhanced Contact Management**: Additional features for contact organization.
Building this project taught me about:
- Workflow automation with n8n
- System integration between different services
- Prompt engineering for practical AI applications
- User experience design for confirmation flows
