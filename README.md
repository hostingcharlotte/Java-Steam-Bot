# Java-Steam-Bot
Steam Bot based od Steam-Kit

This bot is based on Steam-Kit Java port done by Top-Cat. Here you can download updated Steam-Kit version: 
https://github.com/jhomlala/SteamKit-Java

To see working examples, please check test package.

#Examples

Create simple bot:

```
  BotConfiguration config = new BotConfiguration().Builder().
                            setUsername(your_username).
                            setPassword(your_password).
                            build();
  SteamBot steamBot = new SteamBot(config);
  
  steamBot.start();

```


