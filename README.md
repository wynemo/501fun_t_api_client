##501fun twitter api

###python webpy
this a twitter api written in webpy
python version >= 2.6

###how to use
1. change key and secect in config/settings.py(you can get them from <https://dev.twitter.com>)
2. change callback url on <https://dev.twitter.com>: https://host_url
3. https://host_url/api is your api url(maybe https://host_url/api/)
4. in browser,go to https://host_url/,authenticate

###deploy on appfog

1. register on appfog, create a app, install the command line tools.
2. upload the code

        git clone git://github.com/wynemo/501fun_t_api_client.git
        cd 501fun_t_api_client
        git submodule init
        git submodule update
        af login
        af update yourappdname


###supported apps

+ twitter ios offical client <http://itunes.apple.com/us/app/twitter/id333903271?mt=8>

###todo
+ fix http 403 error on twitter iphone
+ fix failing to get reply info of tweet
