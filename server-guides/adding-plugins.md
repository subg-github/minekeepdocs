# Adding Plugins

!!!
This guide assumes that you have already [created a server](../account/server-creation.md)
!!!

To add a plugin to your MineKeep server, you must first find a plugin you want to add. This plugin can be any plugin that has support for bukkit, spigot or paper. These can be commonly found on websites like [SpigotMC](https://www.spigotmc.org/resources/categories/spigot.4/) or [Hangar](https://hangar.papermc.io/). For this tutorial, I will be using the [Simple TPA](https://www.spigotmc.org/resources/simple-tpa.64270/) plugin on SpigotMC.

The first thing you do is download the jar file for your plugin. This can differ between plugin websites. On SpigotMC, this can be done by pressing the Download Now button, as shown below:
![](/static/spigotdownload.png)

Once you have downloaded the plugin jar file, go to your [MineKeep](https://minekeep.net/servers) dashboard and select the server you want to install the plugin on, as shown below:
![](/static/minekeepservers.png)

This will take us to our server console, however we want to go into the files of the server. To do this, click the files button above the server console, as shown below:
![](/static/minekeepfiles.png)

Now that we are in the server files, we can select the plugins folder, as that is where we want the plugin to be uploaded to, and then we press the upload button, as shown below:
![](/static/uploadplugin.png)

In the upload window, select or drag in your plugin jar file, which will upload your plugin. The final thing you need to do is return to the console, stop the server, and start it back up again to load the plugin.

After that, you are finished! You may now use your plugin on your server, for example I will now be able to use the TPA command. You can confirm your plugin is working by running the command `/plugins`, and making sure your plugin is there, and that it is green.