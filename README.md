## Rename Bot 

An Open Source Telegram Rename Bot


### Installation

#### The Easy Way

### You can tap the Deploy To Heroku button below to deploy straight to Heroku!
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/EL-Coders/ELRenameBot)


#### The Hard Way

### Deploy in your vps
```sh
git clone https://github.com/EL-Coders/ELRenameBot
cd ELRenameBot
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
# <Create config.py appropriately>
python3 bot.py
```

An example `config.py` file could be:

**Not All of the variables are mandatory**

```python3
from sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  TG_BOT_TOKEN = ""
  AUTH_USERS = [
      "7351948"
      # is a string for LEGACY purposes
  ]
```


## Credits, and Thanks to Beloved Developers ;

* [SpEcHlDe](https://telegram.dog/SpEcHlDe) - The Father 
* [Dan Tès](https://telegram.dog/haskell) 
* [Yoily](https://telegram.dog/YoilyL) 
* [Anand](https://telegram.dog/Anandpskerala)


- For FeedBack and Suggestions, please feel free to say in [@EL_Support](https://telegram.dog/el_support)

#### LICENSE
- GPLv3
