---
layout: article
permalink: /setup/
title: "Setup"
toc: true
share: false
noindex: true
---

Setting up the workflow is easy, you just need to follow these steps:-


# First Time Use


## Create a Spotify Application

* Create an [Application on Spotify](https://developer.spotify.com/my-applications) (this is for both free and premium users)
    * You can set Application Name and Description to whatever you want
    * ***Redirect URI must be set to*** `http://localhost:15298/callback.php`
    
**Warning:** Make sure to click 'Save' button once you set the Redirect URI 
{: .notice-danger}

<figure>
	<a href="http://cl.ly/image/0h2F1z232Q2p/Capture_d%E2%80%99e%CC%81cran_2014-11-04_a%CC%80_11_13_50.png"><img src="{{ site.url }}/images/spotify_application.png"></a>
	<figcaption>Example of Spotify Application.</figcaption>
</figure>


## Create the library

* Invoke the workflow (with keyword `spot_mini`, or with an [hotkey]({{ site.url }}/setup/#toc2) ) and follow the steps as below by copy/pasting the Client ID and Client Secret into Alfred window when asked:

<figure>
	<a href="{{ site.url }}/images/setup.gif"><img src="{{ site.url }}/images/setup.gif"></a>
	<figcaption>Paste Client ID and Client Secret.</figcaption>
</figure>


* Invoke the workflow again and select Authenticate with Spotify, your web browser will open and you'll be prompted to login with Spotify and allow access to your application. 
At the end you should see a message like this:-

```
Hello <your name here> ! You are now successfully logged and you can close this window.
```

* Invoke the workflow again and Create the library.

* After some time, you should get a notification saying that library has been created.


**Note:** All artworks are downloaded in the background. Until this process is over, you can see blank artworks when using the workflow.
{: .notice-info}


* You can check progress by invoking the workflow again:-

<figure>
	<img src="{{ site.url }}/images/update_progress.png"></a>
	<figcaption>See progress by invoking workflow.</figcaption>
</figure>

# Setting Hotkeys

Spotify Mini Player has full support of [Alfred hotkeys](http://support.alfredapp.com/workflows:config:triggers-hotkey) to invoke the workflow and for every possible action !

## Invoke workflows with hotkeys

It is highly recommended to use hotkeys to invoke the workflow rather than the keyword `spot_mini`

To setup hotkeys, see example below:-

<figure>
	<a href="{{ site.url }}/images/setup_hotkeys.gif"><img src="{{ site.url }}/images/setup_hotkeys.gif"></a>
	<figcaption>Setup hotkeys.</figcaption>
</figure>

You can setup hotkeys to:-

* Show main window

* Show Current track menu

* Show Alfred Playlist menu

* Show Playlists menu

* Show Charts menu

* Show Settings menu

* Show New Releases menu



## Invoke actions with hotkeys

For every possible action with Spotify Mini Player, you can configure hotkey.
Simply add hotkeys for actions you want:-

<figure>
	<a href="{{ site.url }}/images/setup_hotkeys_action.png"><img src="{{ site.url }}/images/setup_hotkeys_action.png"></a>
	<figcaption>Setup hotkeys for any action you want.</figcaption>
</figure>