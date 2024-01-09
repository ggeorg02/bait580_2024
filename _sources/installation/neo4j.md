# Neo4j

In this document, we will set up a neo4j aura instance in the cloud.

Click on [this](https://neo4j.com/cloud/aura/?ref=get-started-dropdown-cta) and press on `Start Free`; this will take you to the registration page.

```{figure} img/register.png
---
width: 900px
align: center
---
```

Enter an email and password that you want to use for the registration.


Followed by this will take you to this page, 

```{figure} img/verifyemail.png
---
width: 900px
align: center
---
```

You need to verify your email and `Go to the Dashboard`. Then, agree to the `terms and conditions,` and after that, it will take you to this page to create your first database. If it doesn't takes you automatically then you can click on the button `New Instance`. Following is how the page looks like - Here you want to create 

```{figure} img/emptyinstance.png
---
width: 900px
align: center
---
```

```{note}
You can only create one free instance. If you want to create another you want to first you want to destroy the existing one.
```
We will be going with `AuraDB Free instance`. You need to keep an eye on the limitations of this database, copying and pasting it here for better visibility.

```{important}
- 1 forever free database
- Limits on graph size (50k nodes, 175k relationships)
- Standard procedure library (apoc-core)
- Auto-pause after 3 days of inactivity
```

You will get credentials for your database; make sure you save it safely. We need this for making a connection to this database.

```{figure} img/credentials.png
---
width: 900px
align: center
---
```

It might take some time, but you will see it `Running` once your database is ready. 

```{figure} img/settingup.png
---
width: 900px
align: center
---
```

Make a note of the connection URL; you will need this to connect to your database.

To summarize, now you created a neo4j graph database in the cloud. 


```{important}
You need the following information for connecting to the graph database (in our case, for connecting from our jupyter notebook).
- connection URL
- username = default is neo4j
- password
```

You can now `Open with` neo4j browser. 

```{figure} img/query.png
---
width: 900px
align: center
---
```

This will take you to a page where you want to enter your connection details. Most of them will be automatically populated, and you want to enter your password.

```{figure} img/finalconnect.png
---
width: 900px
align: center
---
```

This is your workspace for creating and exploring your graph database. Now it got nothing in there as we haven't exported any data.

```{figure} img/nowconnected.png
---
width: 900px
align: center
---
```

```{note}
- If you want to log back in, you can use this [URL](https://neo4j.com/cloud/platform/aura-graph-database/); Click on `Start Free` and then login using your email and password. Once you log in you can see your databases.
```

## Resume Database

- If the database is inactive, then it will automatically be paused. So you need to start it after logging back.

Here is how it looks like;

```{figure} img/neo4jresume.png
---
width: 900px
align: center
---
```

Once you click on `Resume` your database will be resumed in few minutes. 

```{warning}
After you resume your database and when you try to connect to the database from your jupyter, you might run into an error `py2neo.errors.ServiceUnavailable: Cannot connect to any known routers`. There won't be issues in using it with the neo4j query space. If this is the situation you want to connect from the jupyterbook, then you want to create another instance after deleting the current instance. Sorry, it is weird that it is like this with the free database. 
```