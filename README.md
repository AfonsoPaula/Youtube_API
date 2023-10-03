# Youtube_API

## Getting Started

I initially created this project in Google Colab; however, if you prefer to use Jupyter Notebook, please follow the steps below:

### Prerequesites

- Python 3.x
- Pandas library (install using `pip install pandas` if not already installed)

#### Installation

1. Clone this Github repository:
  
```bash
git clone https://github.com/AfonsoPaula/Youtube_API.git
```

2. Navigate to the project directory:

```bash
cd Youtube_API
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the **'Youtube_API.ipynb'** notebook to see the code in action.


<hr>


### Obtaining API Key and Channel ID

To use this project, you'll need to obtain an API key from Google Developers and your Youtube Channel ID. Here are the steps to acquire them:

1. **Create a Google Dvelopers Account:**

   - If you don't already have one, go to the [Google Developers Console](https://console.developers.google.com/).
   - Sign in with your Google Account or create one if necessary.

2. **Create a New project:**

   - Click on the project dropdown and select "New Project".
   - Enter a name for your project and click "Create".
  
3. **Enable the Youtube Data API v3:**

   - In the Google Developers Console, navigate to the "APIs & Services" > "Credentials"
   - Click on "Create Credentials" and select "API key".
   - Your API kwy will be generated. Copy it.
  
### Obtaining the channel ID

To obtain the channel ID:

1. **Go to your Youtube Channel:**

   - Open Youtube and go to your channel page.
  
2. **Retrieve the Channel ID:**

  - Click on your channel's profile picture.
  - Select "Youtube Studio"
  - In the Youtube Studio, click on "Settings" (gear icon) on the left sidebar.
  - Under "Channel", you will find your "Channel ID".

### Using the API Key and Channel ID in the Project:

In your project code, replace the placeholders with your obtained API key and Channel Key:

```python
# Replace 'YOUR_API_KEY' with the API key you obtained.
API_KEY = 'YOUR_API_KEY'

# Replace 'YOUR_CHANNEL_ID' with your Youtube Channel ID.
CHANNEL_ID = 'YOUR_CHANNEL_ID'
```

<hr>

## Usage

In this notebook, you will find step-by-step explanations and code examples for:
1. Learning how to use the **'requests'** library to make API calls.
2. Making API calls to the Youtube Data API.
3. Collecting data as JSON.
4. Saving the data as a pandas DataFrame.
5. Refactoring the code with good Software Engeneering (SWE) fundamentals.


<hr>

**Watch the Video tutorial**: For a step-by-step guide on setting up and using this project, check out the [video tutorial on Youtube](https://www.youtube.com/watch?v=fklHBWow8vE&ab_channel=StrataScratch).



