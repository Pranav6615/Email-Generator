**📧 Email Generator using LLaMA-2 + Streamlit + LocalTunnel**
This project is a lightweight web-based AI Email Generator powered by LLaMA-2, deployed with Streamlit and made publicly accessible using LocalTunnel. It allows users to generate professional, customizable emails by providing simple prompts like the recipient's role, topic, or purpose.

While the generation process may not be lightning-fast due to local model inference and limited hardware resources, it provides a fully offline and privacy-respecting solution for drafting emails using a fine-tuned LLaMA-2 model.

**🔧 Tech Stack**
LLaMA-2 (7B or similar): Used for generating email content based on input context.

Streamlit: Provides a clean, interactive UI for users to input parameters and view the generated email.

LocalTunnel: Enables temporary public access to the local Streamlit app for quick sharing and demo purposes.

**⚙️ Features**
Prompt-based custom email generation (e.g., “Cold email for sales lead in IT industry”).

Editable subject and body preview.

Streamlit UI for easy interaction — no coding required.

Simple public access via LocalTunnel without complex deployment.

⚠️ Note
Performance is optimized for basic usage on low-resource machines. You may experience some delay in generation due to local inference and resource limitations — especially on CPUs or non-optimized models. However, it’s a fully self-contained, privacy-focused tool that doesn’t rely on external APIs.


**Run this python notebook on Google Colab**

Download the model from HuggingFace : https://huggingface.co/meta-llama/Llama-2-7b-chat-hf 

Sign up to the Ngrok website : https://ngrok.com/

On Dashboard page there is Your Authtoken, copy it and paste it in place of my Authtoken.

Use the hardware accelerators(runtime environment) provided by Colab for free viz. T4- GPU and v2-8 TPU 

Connect one of these Runtime environment

Run all the cells 

After putting the email topic, sender name and receiver name, Click the Generate Button

It takes around 5 - 8 minutes to genrate Email, so do not exit or inturrupt the cell.

Wait patiently for the email, it will be eventully generated. 

										-Pranav6615
