# redis-migrate
Migrate keys from one Redis cluster to another.

## Installation

### Clone the repo

`git clone https://github.com/kylemclaren/redis-migrate && cd redis-migrate`

### Make the script executable

`chmod +x redis-migrate.py`

### Install pip (if you don't have it already)

`easy_install pip`

### Install the Redis Python module with pip

`pip install redis`

Now grab the Redis URI for both the source and destination databases and run the script:

`./redis-migrate.py --src redis://x:password@host1:10111 --dst redis://x:password@host2:10222`

Then follow the onscreen prompts.
