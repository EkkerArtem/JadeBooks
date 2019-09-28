## LB #1 Ekker Artem

### To run this code in Intellij Idea you need:
1. Download archive and unzip it.
2. Add jade jar to your ***Libraries*** in ***Project Settings*** or to your ***pom.xml*** or any other file for project building depending on your preferences.
3. Set ***Run Configurations*** as shown on below images.
   - Click `+` in ***Run/Debug configurations*** and chose ***Application***<br/>![Step 1 image](https://imgur.com/a/B4uwrBT)
   - Set ***Main class*** as `jade.Boot` and specify program arguments:
      - to set Jade's giu usage on startup - use `-gui` command
      - to specify Jade's agents use pattern `<Agent's Name>:<Agent's Class><(Agent's Arguments if needed)>`. To run this task I used this program arguments `-gui seller:BookSellerAgent;buyer:BookBuyerAgent(Scala-for-the-impatient)`<br/>![Step 2 image](https://imgur.com/a/4JNGfgp)
