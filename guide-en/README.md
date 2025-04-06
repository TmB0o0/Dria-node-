# 🌐 DRIA Node Installation and Setup Guide

## ⚙️ System Requirements

| Component | Minimum Specs |
|-----------|---------------|
| CPU       | 4 cores       |
| RAM       | 8GB           |
| Storage   | 100GB SSD     |
| Port      | 4001          |

## Step 1: Start the Installation

To install and run the DRIA node, execute the following command in the terminal:

```bash
curl -O https://raw.githubusercontent.com/TmB0o0/dria-node/refs/heads/main/guide-en/dria && chmod +x dria && sudo ./dria
```
After running this command, the installation process will begin, and you will need to choose a model.
## Step 2: Choose the Model

-   **Make sure to save your key!** It will not be shown again.

When starting the node, you will be prompted to select a model. You have several options:

### 1. Using Gemini 2.0 Flash

-   Go to the [AI Studio](https://aistudio.google.com/prompts/new_chat) website.
    
-   On the left, click **"Great API key"**.
    
-   Click **"Great API key"** again and select the **GEMINI API** model.
    

⚠️ _Possible issue:_  
If an error occurs related to the region, use an alternative option — OpenAI.

### 2. Using OpenAI (may be paid)

-   Go to the [OpenAI API](https://platform.openai.com/api-keys).
    
-   In the top right corner, click **"Create new secret key"**.
    
-   In the window that appears, enter a name for the key and select the **Default Project**.
    
-   **Make sure to save your key!** It will not be shown again.
    

### 3. Using OpenRouter

[https://openrouter.ai/](https://openrouter.ai/)

#### You can view all models here: [https://dria.co/edge-ai](https://dria.co/edge-ai)

## Step 3: Enter Private Key and API Key

Use the keyboard arrows in the terminal to select the desired model.  
Press the **left arrow** key to choose all models. Paste the keys in the corresponding fields.  
After choosing the model, the system will ask for the following:

-   **Private wallet key**
    
-   **API key**
    

## Completing the Installation

Once all the steps are completed, the DRIA node will be installed and running.

⚠️ If you encounter any issues, try the following:

-   Check that the API keys are entered correctly.
    
-   Verify if there are any regional restrictions.
    

### Possible Errors
```bash
"error": {
    "code": 400,
    "message": "User location is not supported for the API use.",
    "status": "FAILED_PRECONDITION"
}
```
This means **your current location (geolocation) is not supported for using this API**.
