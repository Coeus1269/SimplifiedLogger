# SimplifiedLogger
Simplified version of the overly complicated logger


My version of a logger that is SUPER easy to use, and logical.
I feel that a logger should take how the developers will use it into consideration first.

I want to use it like this:

  Console logs -> BrilliantLogger.Console.Warning("This is a warning to the console")
  
  File Log ->  BrilliantLogger.File.Warning("This is a warning to a file")
  
  Standard Out -> BrilliantLogger.STDO.Warning("This is a warning to Standard out, still under construction")
  
			
Simplified with 4 basic levels: Error, Warning, Info and Debug
  each of which can have a different log file,  where DeBug is always logged in the Error Log file
