# [Marketing Campaign App](https://yuktabande-marketing-campaign-app-app-vkolmr.streamlit.app/)

A Streamlit-based AI-powered tool to generate marketing content tailored for different age groups and tasks using Google Gemini (via LangChain).

## Features

- Generate marketing content such as sales copy, tweets, and product descriptions.
- Customize output for different age groups: Kid, Adult, or Senior Citizen.
- Adjustable word limit for generated content.
- Uses Google Gemini (via LangChain) for high-quality AI responses.
- Simple, interactive web UI built with Streamlit.

## Setup

### 1. Clone the repository

```sh
git clone https://github.com/yuktabande/marketing-campaign-app/
cd Marketing-Campaign-App
```

### 2. Install dependencies

```sh
pip install -r requirements.txt
```

### 3. Configure API Key

- Copy `.env.example` to `.env`:

```sh
cp .env.example .env
```

- Add your Google API key to the `.env` file:

```
GOOGLE_API_KEY="your-google-api-key"
```

### 4. Run the app

```sh
streamlit run app.py
```

## Usage

1. Enter your marketing prompt in the text area.
2. Select the action (e.g., Write a sales copy, Create a tweet, Write a product description).
3. Choose the target age group.
4. Set the desired word limit.
5. Click "Generate" to get your AI-powered marketing content.

## File Structure

- `app.py` - Main Streamlit application.
- `requirements.txt` - Python dependencies.
- `.env.example` - Example environment file for API keys.

---

**Note:** This app uses Google Gemini via the LangChain framework. Make sure your API key has the necessary permissions.
