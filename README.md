🤖 HA Blueprint: Generative AI to Input Text
Supercharge your Home Assistant dashboards by integrating the power of generative AI directly into your UI. This blueprint creates a seamless automation that takes a prompt from an input_text helper, sends it to any configured generative AI conversation agent, and displays the response in a second input_text helper—all in real-time.

It's a powerful and flexible way to create AI-powered tools within your smart home, such as a content generator, a research assistant, or a smart query interface.

(Suggestion: Replace this with a screenshot or GIF of the blueprint in action on your dashboard!)

🚀 Features
Dynamic AI Integration: Works with any generative AI integration that provides a conversation agent in Home Assistant (e.g., OpenAI, Google Generative AI, etc.).

Real-time Interaction: The automation triggers instantly when you submit a new prompt.

UI-Driven: Allows you to build interactive AI chats and tools directly into your Lovelace dashboards.

Flexible & Reusable: Use the response text in other automations, scripts, or display it anywhere in your UI.

Efficient: Includes a condition to prevent the automation from running on empty prompts, saving unnecessary API calls.

✅ Prerequisites
Before you begin, ensure you have the following:

Home Assistant: A running instance of Home Assistant (version 2023.5 or newer is recommended for response_variable support).

Generative AI Integration: At least one configured conversation agent.

Two input_text Helpers: You will need two helpers to serve as the prompt and response fields. If you don't have them, create them by going to Settings > Devices & Services > Helpers:

AI Prompt Helper: (e.g., input_text.ai_prompt)

AI Response Helper: (e.g., input_text.ai_response)

🔧 Installation
You can install this blueprint in two ways:

Easy Method (Import Blueprint)
Click the button below to import the blueprint directly into your Home Assistant instance.


(Important: Replace the URL with the raw URL of the blueprint file in your own GitHub repository.)

Manual Method
Copy the YAML code from the blueprint file.

1. In your Home Assistant instance, go to Settings > Automations & Scenes > Blueprints.

2. Click Create Blueprint and paste the code into the editor.

3. Click Save Blueprint.

⚙️ Configuration
1. After importing, go to Settings > Automations & Scenes > Blueprints and find "Generative AI Conversation to Input Text".

2. Click "Create Automation" to configure a new instance.

3. Fill in the required fields:
