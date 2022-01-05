### WELCOME
# FORK AT YOUR OWN RISK
# Installing
Join https://t.me/HardcoreUserbot to know more !
### The Easy Way

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/AMANTYA1/userbot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="300" height="34.45"/></a></p>

### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/Hack12R/HardcoreUserbot
cd HardcoreUserbot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### UniBorg Configuration

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

