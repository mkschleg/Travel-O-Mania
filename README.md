# Travel-O-Mania

A Class project where me and 3 partners created an android game from a requirement and design documents

-

The Modules I implemented are:
  BitmapUtility
    This Is a BitmapFactory implementation allowing to load all bitmaps into memory at the required size. Helps with
    memory storage.
  ContinentSelectionActivity
    Select Which Continent a player wants to go to. Only allows a player to go to continents not traveled.
  NavigationActivity
    "Flies" the player to the desired continent from the continent they are currently in.  Only happens after the first
    level has been completed.
  IdentifyLandmarkActivity
    A minigame if a player does well, they will choose a landmark found in the continent they just completed and then
    they have to type in the name to have the continent show up on the map.
  LevelActivity
    This is the main bread and butter of the game.  There are 7 questions the player answers about the continent, the
    type of questions are based on the category picked previously, and each question gets a minute to answer.
  EndActivity
    Congratulates the player when they complete the game.  Shows all Landmarks and 
  PlayerHistoryActivity:
    Allows the player to continue their game after logging in.
    
Misc Implementations:
  The Log out timer found in player.  This timer logs the player out after three minutes.
  
