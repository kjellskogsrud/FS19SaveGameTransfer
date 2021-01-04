# FS19 Savegame Transfer
Transfer vehicles and/or animals from one Farming Simulator 2019 savegame to another.

## What is this, and why have I made it?
When I play FS19 I usually play a "survival style" game. Meaning I dont cheat any money. I also use Seasons mod when ever possible.
This brings with it a few "challanges". One challange is that I don't want to repeate as much of the early game when I want to change a map. Seasons mod adds in some added difficulity for the animals. Cows will not produce any milk before they have babies, and that means you will not get any milk the first year.  

I also like to "take my progress" with me. In the past I have done this manualy. That involves going to my old save, and selling all the crops, produce, silage and lands.
Them going ot the new save and cheating in lots of money. I sell all the land and buy all the same equipment I had on the old save and then exit the game. Then starts the rather tedious process of editing the XML files so that my equipment gets the same config, and operating hours. Finally I then edit the money to match that of the old save, and restart the game. Now I have all the "same" equipment that I had with all the same bought configurations, and all the same wear and hours on it. After buying the lands, and getting enough feed for the animals, I do the same thing for them. Transfering over the animals in the XML file. This has the benefit of letting the cows produce milk at once, because they are the same cows that I had on the old save. 

### So what is this tool then?
Well I got tired of doing all of the XML editing manually since it does take a while. So I made this tool to do it for me. It works like this:

1. Start new save, preferably with all the mods you had on the old save. This is not nessasary but the tool does not check for incompatablility to that is your job. 
2. Sell all the land on the new save (optional).
3. Buy all the same things you had on the old save. Also optional, but things that don't appear in both saves will not be transfered. 
4. Save and exit FS.
5. Run the tool.

The tool goes thru the steps of asking about your old save, and new save. It then show you what will be transfered, and ask for confirmation. It then trnasfere all the attributes for the equipment over to the new save, and moves all the animals(if you told it to).
