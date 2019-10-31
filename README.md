# News Summary Api Challenge


Build a REST API to be able create this frontend web application: https://github.com/makersacademy/news-summary-challenge/#api


### Requirements 

```aidl
   As a developer, so that I can query my rest API 
   I would like a get request endpoint which returns the latest news
```

Implementation ideas:
 - Guardian and Aylien have public apis you can query. Other sources could be interesting too.
 - Prototype this in a simple web app like sinatra
 - Build this out in another framework you would like to learn
 - Can you host this API in the cloud?
 
 ```aidl

    As a developer, so that I can avoid hitting rate limits,
    I would like an app which polls these APIS and stores results in a database

```

Implementation ideas:
 - Think about what datastore would be good to query
 - Think about how you would run a cron job in the cloud
 - How would you know whether these services were working?