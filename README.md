"# Ashik-Test-Bot" 

##Setup

npm i

##Run Local

npm run dev

###optional

install https://docs.botframework.com/en-us/tools/bot-framework-emulator/

##Azure CLI commands

npm install -g azure-cli

azure config mode asm

azure login

git push azure master

##Demo Website through Microsoft Azure

http://ashiktestbotdemo.azurewebsites.net/

##References

https://docs.botframework.com/en-us/node/builder/overview/#navtitle

https://dev.botframework.com/

https://github.com/Microsoft/BotBuilder/tree/master/Node/examples

https://github.com/Microsoft/BotBuilder-Samples/tree/master/Node

https://www.luis.ai

##Other

App ID

old- 4294e391-35cd-4546-86a5-12e25f577e7e
e889783f-686c-423d-830f-023130abca47
	
Password

old- 1nH8UqiKVtSfJOK3W8vCtev
LpzNuMvpV0oUVqns0x2VVZQ

Test connection
curl -k -X POST https://login.microsoftonline.com/botframework.com/oauth2/v2.0/token -d "grant_type=client_credentials&client_id=4294e391-35cd-4546-86a5-12e25f577e7e&client_secret=1nH8UqiKVtSfJOK3W8vCtev&scope=https%3A%2F%2Fapi.botframework.com%2F.default"
