# Stardew Valley Modding
## Function 1: Successfully connecting to Stardew Valley 
Use C# and SMAPI to create a log that will check what inputs the player does once the game has started. It should say "player" input "direction key" and so on
### Errors
So far there has been one issue where when left running too long, the game crashes and I cannot move anything. Could have been a laptop issue or something though, have yet to test further
## Function 2: "Good morning" text
So technically it works, it detects the start of the day and sends the message, but only to the SMAPI console. I'll need to use other frameworks and likely some kind of Content Patcher JSON file to make it appear on the screen, still a work in progress
## Function 3: Animal Texture Pack
IT WORKS and it was very easy, just needed to make sure the file paths were correct in the code (JSON file) and then it read them perfectly. Which also means that the sprites I made worked just fine, and were read by the game. Success!
