# adspower-import-metamask

данный скрипт импортирует заранее созданные метамаски в твои готовые профили в adspower. 
скрипт написан на основе https://github.com/zaivanza/adspower-import-metamask  
после импорта он добавляет сети optimism, bsc и arbitrum в кошелек. 

1. экспортируй ids из adspower со своих профилей.
2. добавляешь эти ids в файл id_users.txt (файл надо создать)
3. добавляешь сид фразы от заранее созданных кошельков в файл seeds.txt (файл надо создать)
4. меняешь в файле main.py переменную password_metamask
5. запускаешь файл main.py

не забудь заранее войти в свой adspower, скрипт работает именно через него. 

библиотеки для скачивания : 
pip install selenium, requests, pyperclip, termcolor