# Welcome to my Unofficial Backup Linux GMAD/GMPublish Repository

Q: Why did I Create this Repository?

A: Just because it is much easier for me to Compile and Upload GMod Addons directly to the Steam Workshop, also its faster for me to Compile large Addons because my Processor is garbage. 

# How do I use & Install this?

__**Requirements:**__

- A Linux Server, preferably with ``Debian 9/10/11`` or some Flavor of ``Ubuntu`` (Tested with Debian 10 & 11).
- ``Git`` Installed on your Server.
- The Server Processor should have atleast 3 GHz Single Core Performance when your creating Large Addons with many Files. (You cannot use Multiple Cores, so as I said Single Core Performance is much more needed than Multi Core Performance!)
- Atleast 8 GB of RAM available on your Server for the Addon Creation.
- You need a Legitimate Copy of Garry's Mod.

__Optional, if you want to Upload aswell your Addons to the Steam Workshop directly via your Server:__

- A ``Desktop Enviroment`` installed like ``GNOME``, ``KDE`` or ``XFCE`` on your Server.
- A ``VNC Server`` Program Installed on your Server like ``TigerVNC`` or ``TightVNC`` and a ``VNC Client`` like ``RealVNC`` on your Computer.
- ``SteamCMD`` and ``Steam`` (https://store.steampowered.com/about/) Installed on your Server.

__**Installing:**__

__This should work on any of the above mentioned Operating Systems.__

Open your Terminal...

First update your System and install ``Git`` with ``sudo apt update -y && sudo apt upgrade -y && sudo apt install git``

After installing Git and Updating your System clone the Repository with: ``git clone https://github.com/Liatoast/liatoast-gmadpublish``

Enter the Directory and use the following Command to open GMAD ``./gmad``, if an Error occurs Scroll down to ``Common Issues``.

If you want to use ``GMPublish`` to upload your Addons directly to the Steam Workshop you need as mentioned above have installed Steam, logged into your Steam Account and lastly (If you didn't) have accepted the Steam Workshop ToS. (You will get a Prompt in the Command Line if you didn't)

# Common Issues

Q: I get an ``libsteam_api.so`` is missing or any kind of libsteam Error!

A: That's because sometimes the API cannot hook or get the Libraries, i got around it by just copying ``libsteam_api.so`` to the ``/lib/`` Directory with ``sudo cp libsteam_api.so /lib/``.

Q: I accepted the Steam Workshop ToS but still I cannot upload Addons and it logs me out of Steam in my Server!

A: **Make sure you currently closed Garry's Mod and aren't playing it**, when you try to Upload an Addon it tries to Start GMod possibly to verify that you accepted the Steam Workshop ToS or whatsoever (I really don't know why), but you can only have one Garry's Mod Instance running at a Time that's why just close Garry's Mod while your using GMPublish! 

# License

**I do not own any of these files! these are just a Original Copy of them for you to clone and use, I do not hold credit or copyright by any means!**

(Also im Sorry for my Garbage English)
