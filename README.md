# Notion_News_Server

Update the news every hour.

## Table of contents

[Install libraries](#install-libraries)  
[Run server](#run-server)  
[Todo](#todo)

## Install libraries

Python version : 3.10

```bash
pip3 install -r requirements.txt
```

## Run server

I run the sever on ubuntu by crontab.

```bash
0 * * * * /home/kar7mp5/Projects/Notion-News-Server/server.sh >> /home/kar7mp5/Projects/Notion-News-Server/server.log 2>&1
```

## Todo

I need to edit my library 'notion-news-cralwer' that toggle `tqdm` function.
