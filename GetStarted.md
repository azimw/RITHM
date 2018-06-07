# Getting Started
> This markdown file needs to be updated so that others can get started using RITHM. There is an open [issue](https://github.com/CRMTH/RITHM/issues/12) related to this. For formatting, don't use these quote blocks (they are just here as placeholders). Use heading formats, numbered lists, and links as much as possible (check your markdown cheat sheet or [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)).

## Setting up Twitter
> There are a couple links under "RITHM Streamer" in [README.md](https://github.com/CRMTH/RITHM/blob/master/README.md) to get you started with outlining the processes under this heading. Follow those links and document the steps that you took to get the infrastructure set up.


### Install Git Client 
>  If you do not have git downloaded on your machine use the link below to download git.
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git



### Create a new Twitter user account

> To use the RITHM streamer you must use have a twitter account. I don’t recommend using personal account, you can easily create an account using the link below
https://twitter.com/i/flow/signup?lang=en 

### Create a Twitter developer account

> The next step is to obtain access to Twitter as a developer. Use your Twitter credentials and follow the steps provided in the link below to obtain access to Twitter as a developer.
https://developer.twitter.com/en/apply-for-access


### Download RITHM source files

> Git makes donwloading RITHM's source file relatively straightforward.
> _git clone_ is the current command line method to download source files

```git clone http://github.com/CRMTH/RITHM/```


> The RITHM streamer also uses the Twython package, use the link below to download the Twython package.
https://github.com/ryanmcgrath/twython

> After downloading Twython place the package within the RITHM folder, if the Twython package is not in within the RITHM folder. The streamer will not be able to use the methods/functions in the Twython package.

### Create a Twitter developer app

> The next step is to create your first app on Twitter, Use the link below
https://apps.twitter.com/app/new
 

## Setting up RITHM

> After creating your first Twitter app, go to the "Keys and Access Tokens" tab. You should see your Consumer Key (API Key) and Consumer Secret (API Secret). 

> Your Access Token and Access Token Secret are also located under the "Keys and Access Tokens" tab. Click the button that reads " Generate my Access Tokens"

> Copy and Paste your: Consumer Key (API Key),Consumer Secret (API Secret), Access Token , and  Access Token Secret into their respective places in the  "auth.ini" file


### Set up RITHM streamer 


> How to start the streamer. From here on out, use the streamer documentation!
