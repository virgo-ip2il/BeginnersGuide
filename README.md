# A guide for beginners in Virgo


## New member joining the Virgo collaboration

When a new member joins the Virgo collaboration (and an existing group), this has to be notified by the group leader to the Virgo Steering Committee.

## Getting your accounts
### EGO accounts
There are two different EGO Virgo account systems:
- **Linux** (used for ctrls, olservers, farmns, thinlinc, etc ...)
- **Active Directory** (used for Windows, Logbook, TDS, wiki, etc ...)
and you will need two separate accounts (a third account system called workarea exists, but its usage is obsolete).

The creation of the accounts is triggered by your group leader, who has to send an email to
the EGO IT department (<service@ego-gw.it>). 
In addition, you will also need a **LIGO account** (more details below).

**Linux account** : you will receive an email with the userid and an initial password, to be reset at the first connection.
This allows you to connect, via plain ssh,  to the following machines for interactive use:
`farmn**X**.virgo.infn.it` with **X**= 1 to 15.
You can also connecto to farmn.virgo.infn.it via a desktop connection using the "thinlinc" client software (see installation procedure below)

**EGO Active Directory account** : you will receive an email with your userid.
To use your account, you will first need to set your password. This you can do by visiting [this page]
(https://www.ego-gw.it/UserProfile/)
and clicking on the link:

`Reset Active Directory password`

You can then undertake the two-step process required to complete the procedure and subsequently begin using your account.

Further information on the different EGO-Virgo accounts is available [here](https://wiki.virgo-gw.eu/IT/Cascina\_EGO-Virgo\_Accounts)

### LIGO account
You also need to create a {\bf LIGO account} [here](https://my.ligo.org/).
You should register on the right side of the page, mentioning you belong to the Virgo collaboration.
This account grants you access to LIGO Document Control Center (DCC), in particular several wiki pages and mailing lists
are hosted on LIGO pages.

### Mailing lists: how to join
You can subscribe to the appropriate mailing lists from the web pages:

http://mail.ego-gw.it/mailman/listinfo

and

http://mail.virgo.infn.it/mailman/listinfo

This will request that you set a dedicated password.
**WARNING: use a trivial password, as this is not protected!**

Depending on the group you work with (ask your conveners), some mailing lists can be hosted by LIGO, in this case
you can subscribe here:

https://grouper.ligo.org/mailinglists/

this works with the LIGO account (see above), so you do not need to set an additional dedicated password.

## Useful tools and software

### Connecting to meetings

Two methods are widely used in the LIGO-Virgo collaboration to connect to meetings remotely: Ezuce (Vibe) and Teamspeak.
Ask your collaborators or check the documentation pages to see which system is mostly used by your group. In any case, it
is good to have both.

You can download Teamspeak from [here](http://www.teamspeak.com/?page=downloads) (no need to create an account). The required Teamspeak servers and channels information can usually be found in the wiki on either Virgo or LIGO websites.

You can download Vibe from [here](https://vibe.ezuce.com/download/), and sign up for an account here [here](https://vibe.ezuce.com/srn/).
You should then join the Virgo-LSC community (password can be found [here](https://dcc.ligo.org/LIGO-M1300453)) (you need a LIGO account to access the information).

### Thinlink
To use thinlink 
- download the client from https://www.cendio.com/thinlinc/download
- make sure you login past the EGO firewall such that your machine has a 12 hours token
from https://fw.ego-gw.it/connect/PortalMain (standard virgo login)
- start the client and put farmn.virgo.infn.it as a server. Standard virgo login. Choose your
desktop. By default this is fullscreen, press F8 and toggle the fullscreen box to go windowed.

