# YOUTUBE SHORTS CONTENT GENERATION
Made by: Aleen Dhar and Shivam Singh



## Environment Setup:

1. make a .env file and copy paste the following code
```bash
AGENT_MAILBOX_KEY=
HUGGING_FACE_ACCESS_TOKEN=
gemini_api_key=


elevenlabs_api_key=
eleven_voice_id=

cloudinary_cloud_name=
cloudinary_api_key=
cloudinary_api_secret=
```

2. get AGENT_MAILBOX_KEY from https://agentverse.ai/mailroom
3. get HUGGING_FACE_ACCESS_TOKEN from https://huggingface.co/settings/tokens
4. get gemini_api_key from https://aistudio.google.com/app/u/2/apikey
5. get elevenlabs_api_key from https://elevenlabs.io/  and sign up, click on your icon and choose Profile + API key
6. eleven_voice_id from https://elevenlabs.io/app/voice-lab.
7. get cloudinary_cloud_name, cloudinary_api_key,cloudinary_api_secret from https://console.cloudinary.com/pm/c-2975fa68853eb272867546601d974b/getting-started



## Setup
1. In the main directory install all dependencies

    ```bash
    poetry install
    ```


## Running The Main Script

To run the project, use the command:

```
cd src
poetry run python main.py
```

# Special considerations

