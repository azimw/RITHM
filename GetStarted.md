# Getting Started
> This markdown file needs to be updated so that others can get started using RITHM. There is an open [issue](https://github.com/CRMTH/RITHM/issues/12) related to this. For formatting, don't use these quote blocks (they are just here as placeholders). Use heading formats, numbered lists, and links as much as possible (check your markdown cheat sheet or [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)).

## Setting up Twitter
> There are a couple links under "RITHM Streamer" in [README.md](https://github.com/CRMTH/RITHM/blob/master/README.md) to get you started with outlining the processes under this heading. Follow those links and document the steps that you took to get the infrastructure set up.

### Create a new Twitter user account

> To use the RITHM streamer you must use have a twitter account. I don’t recommend using personal account, you can easily create an account using the link below
>
>https://twitter.com/i/flow/signup?lang=en

### Create a Twitter developer account

> The next step is to obtain access to Twitter as a developer. Use your Twitter credentials and follow the steps provided in the link below to obtain access to Twitter as a developer.
> 
>https://developer.twitter.com/en/apply-for-access

## Setting up RITHM

### Install Git client 

> To use the RITHM streamer you must install git, use the link below to install git if you don’t have git already

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

### Download RITHM source files

> _git clone_ is the current command line method, I think. It should look something like this:

```git clone http://github.com/CRMTH/RITHM/```

> Follow the instructions provided in the link below to donwload Twython: 
> https://github.com/ryanmcgrath/twython

>> For the streamer to run Twython must be loacated within the RITHM folder 

### Create a Twitter developer app

> The next step is to create your first app on Twitter. After creating an app your authentication password and keys will be attainlable.
> https://apps.twitter.com/app/new

### Set up RITHM streamer 
  
> After creating your first app, open the "keys and access tokens " tab. There you will find your: Consumer Key (API Key),
Consumer Secret (API Secret), Access Token, and Access Token Secret.

> Using your preffered text editor open the "auth.ini' stored within the RITHM folder and put your Consumer Key (API Key),
Consumer Secret (API Secret), Access Token, and Access Token Secret into their respective places.

> How to start the streamer. From here on out, use the streamer documentation!
