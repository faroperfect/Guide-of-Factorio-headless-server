First of all, I have factorio on the Steam.  
Here is the always newest stable version of Factorio headless server.  
  https://factorio.com/get-download/stable/headless/linux64  
After download, extract to a place u want, I refer to a blog, /usr/local/games/ .
Then u need to rename the file "server.setting.json", and edit it.  
I suggest u can read english:P , also plz forgive my english sucks:{  
"username" and "token" used to check if u have bought this game.
You can find it in %appdata%\Factorio\player-data.json under the name service-token,  
refer to https://forums.factorio.com/viewtopic.php?t=39073  
Also u can find username in this file.  
That's all.  
*****************************************************************************************  
FAQ:  
1. Q: Error InterruptibleStdioStream.cpp:61: Got EOF on stdin; closing  
   A: Just follow my attempt.  
2. Q: How to run the server?  
   A: First, create a save.   ./bin/x64/factorio --create saves.zip
      Then run on it.         ./bin/x64/factorio --start-server saves.zip --server-settings ./data/server-settings.json
