### Step 1 - Git clone + cd

```
git clone https://github.com/OMx0777/AI-Assistant.git
```

```
cd open you file name
```
### Step 2 - Create & Activate virtual environment  

create virtual environment

```
python3 -m venv env
```

activate environment

```
source env/bin/activate
```

### Step 3 - Install required packages.

```
pip install openai==0.28
```
```
pip install pyttsx3
```
```
pip install scipy
```
```
pip install numpy
```
```
pip install python-dotenv
```
```
pip install sounddevice
```

### Step 4 - Update OpenAI API Key & Assistant ID

Modify `copy.env` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), And rename it to `.env`.

## Example usage

```
python3 app.py
```

