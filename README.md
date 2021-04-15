# GoogleSyncAdapters for Magisk v.22

# Why should I have this module?

First of all let me write a brief introduction to what the module does.
Let's suppose that you're on a de-googled ROM (or microG) and wanna sync your contacts or your calendar with Google. 
<sub> (I know, someone may find me and my family and kill me for that statement but hey, I don't have much spare time to setup a Nextcloud server :p)</sup>

Btw, if you wanna sync your stuff with Google you have two choices:

1. Install GApps (OpenGApps, NikGApps or whatever) **highly discouraged tbf**
2. Install just the sync adapters as system apps **highly recommended**

Let's suppose that you have a brain and opt for the **2** choice: installing the sync adapters as system apps.

Because I'm too lazy to write 69420 times stuff, I wrote a small gist.github.com which you can check [here](https://gist.github.com/dreamwhite/934e7d2bb9e1f2a89c5307485a5c3fb3)

**Q:** Okay, and now where's the problem? Why should I use your dumb module? çç<br>
**A:** If you update your ROM you'll lose the sync adapters, and you have to repeat the procedure again :p That's where Magisk systemless stuff helps us

Please note that nanodroid_gsync stuff isn't working at the time of writing. I don't know if they'll even care about this or not, but at the moment this is the only solution çç

# How to install then your dumb module?

**Before installing the module remove any previous attempt of using sync adapters**

Download from Releases section of this GitHub repository the latest version of the module (at the time of writing is 69420 for obvious reasons hehe) and install it via Magisk Manager.

After doing so, follow those steps:
1. open `System Settings`
2. click on `Apps & Notifications`
3. click on `See all 69420 apps`
4. Tap on the three dots and click on `Show system`
5. Locate `Google Calendar Sync` and give it the `Calendar` permission
5. Locate `Google Contacts Sync` and give it both `Contacts` permission and `Additional permissions/Contacts`
6. **ADDITIONAL STEP IF YOU HAVE A FIREWALL LIKE AFWALL+:** in `System` section give both adapters the permission to use internet both via WiFi and Mobile data

# Credits:

Please note that I do not own neither APKMirror nor Google Sync Adapter, nor microG nor whateveryouwant I just wanted to clarify the setup process for the install adapters after reading [this issue](https://github.com/microg/GmsCore/issues/585)
