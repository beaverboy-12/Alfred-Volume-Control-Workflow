# Alfred-Volume-Control-Workflow

<img width="637" height="186" alt="Screenshot 2026-01-20 at 17 37 56" src="https://github.com/user-attachments/assets/7fc71c23-4468-4805-a3fc-56d8b91323ad" />


Control Your system volume direct from alfred. By default the workflow sets "vol as the main keyword and "v" as the quick keyword, if you change these then replace all instances of "vol" and "v" below for the functions, note that arguments and modifiers made after the keywords remain the same. Below are the keywords you use to access the functions:

- "vol" - The keyword that triggers the options, you can follow this with any number between 0 and 100 to set the volume to that percentage.

- "V" - On its own the letter "V" followed by a space can be used to quick show a series of preset options for volume.

- "Vol s" - Adding an s after the "vol" keyword will show a menu of predetermined volume states.

- "Vol c" - Adding a c after the "Vol" keyword will print your current volume number.

<img width="678" height="494" alt="Screenshot 2026-01-20 at 17 48 02" src="https://github.com/user-attachments/assets/ffa36b60-7c94-4c35-97c1-6c8e885dd767" />

Preset Options:
- Mute (mutes output volume)
- 25% (sets volume to 25%)
- 50% ( sets volume to 50%)
- 75% (sets volume to 75%)
- Max (sets volume to 100%)

Display options allow you to determine how the workflow outputs a result after altering the system volume. By default it will show "large type" of the number in the middle of the screen of the current volume level for 0.5 seconds. Alternatively you can select "Notification" to have alfred send a push notification to your notification centre or "None" to stop them altogether. Note that if you turn them off altogether the current volume modifier will no longer function.

The final configuration is a simple tick box as to whether you would like a sound effect to play upon the execution of a script, By default this is yet but by toggleing it off you can mute the entire workflow.

The workflow uses applescripts exclusively and should therefore function natively. You should not need to give alfred more control in your privacy settings. To troubleshoot issues open the script node of the function that isnt working and copy and paste the script into Script Editor.app, run the script and see if it functions there. If it does then it may be an issue with the workflow, if it doesnt work within script editor you may have a system setting preventing applescript from having control permissions. 
