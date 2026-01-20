# Alfred-Volume-Control-Workflow

Control Your system volume direct from alfred. By default the workflow sets "vol as the main keyword and "v" as the quick keyword, if you change these then replace all instances of "vol" and "v" below for the functions, note that arguments and modifiers made after the keywords remain the same. Below are the keywords you use to access the functions:

- "vol" - The keyword that triggers the options, you can follow this with any number between 0 and 100 to set the volume to that percentage.

- "V" - On its own the letter "V" followed by a space can be used to quick show a series of preset options for volume.

- "Vol s" - Adding an s after the "vol" keyword will show a menu of predetermined volume states.

- "Vol c" - Adding a c after the "Vol" keyword will print your current volume number.

Preset Options:
- Mute (mutes output volume)
- 25% (sets volume to 25%)
- 50% ( sets volume to 50%)
- 75% (sets volume to 75%)
- Max (sets volume to 100%)


The workflow uses applescripts exclusively and should therefore function natively. You should not need to give alfred more control in your privacy settings. To troubleshoot issues open the script node of the function that isnt working and copy and paste the script into Script Editor.app, run the script and see if it functions there. If it does then it may be an issue with the workflow, if it doesnt work within script editor you may have a system setting preventing applescript from having control permissions. 
