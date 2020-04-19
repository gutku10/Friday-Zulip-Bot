# Friday-Zulip-Bot
ZulipBot for HackOn

# Welcome to Friday!
## Team Nokia3310 in HackON
!
## **Friday-Bot** is a zulip chatbot   



# Instructions to run locally:
1. [Create a Zulip Realm](https://zulip.com/create_realm/)
2. Goto to settings and create a new generic bot named 'Friday'. (Settings can be found in dropdown of gear icon present in top right corner of zulip realm)
3. Download the zuliprc file for your bot and place it in your home directory as '.zuliprc'.
![](./images/instructions.png)  
4. Install all the requirements using ``` pip install -r requirements.txt ```
5. In ``` bot.py ``` , change site in ``` self.client = zulip.Client(site="https://chunkzz.zulipchat.com/api/") ``` to url of your created zulip realm.Do the same for ``` BOT_MAIL ``` variable.  
6. Run ``` bot.py ``` using python 3. ``` python3 bot.py ```
7. Head over to your created zulip realm and start using the bot.

# Features

friday-Bot can :
>

>* Get top news
>* Crack a joke
>* Motivates you with quotes
>* Have a nice chat with friday

## How to use?

(./images/help.png) 


###  News:
Get top 10 stories in no time in your Zulip server.  
`friday news`  

![](./images/news.png)    

###  News:
Get the covid 19 statistics.  
`friday covid19 stats india`  

![](./images/stats.png)  


###  Motivate:
Motivate is here to help you with motivational quotes when you are down :smile:  

```friday motivate```  

![](./images/motivate.png)  



###  Joke:
This integration cracks some really good as well as lame jokes !. 

`friday joke`  

![](./images/joke.png)



## Contributors
* [Tanishq Bhalla](https://github.com/)  
* [Abhinav Goyal](https://github.com/zabhitak)  
* [Utkrisht Agrawal] 
