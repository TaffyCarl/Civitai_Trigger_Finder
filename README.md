Before going on with all the gibberish, Civitai LoRA Trigger Finder up to and including V6 (this version) is copyright Carl Bratcher aka Taffy_Carl, you are free to use it but not reverse engineer, modify, whatever it. While it's a free program, a donation of Buzz on Civitai would be nice ;-) If you see this in places other than Civitai, Github and Pure Fooocus AI on Facebook please let me know. Finally, NEVER PAY FOR IT, It's free apart from a Buzz donation grovel grovel :-) - https://civitai.com/user/Taffy_Carl

Zip Contents - image1.png, image2.png, changeme.jpg, *header.png, Lora_Trigger_Finder_V6.exe, json_validator.exe (see below for this), editing_json.txt and this readme.txt.

Additions: A counter showing the number of LoRA's you have. A help menu in the top right corner (self explanatory), if you have a large number of LoRA's like me it became a pain so it's also now got down in the bottom right corner a jump up arrow which takes you back to the top of the page. The best features as I see them are the Trigger Word copy buttons AND the View Metadata buttons associated with each LoRA. Sometimes LoRA's don't show Trigger words because the creator forgot to add them to Civitai - if you view the Metadata you will possibly find hints or even the actual Triggers. So check them out if you're missing them! In the footer is a little something else :-)

Installation is simple, create a folder called Lora Triggers to wherever you want the output files to go, I'd recommend inside the root of your AI Image program but it's up to you. Extract the zip file (leave it intact in its own folder) to there or wherever you want to put it on your PC. When it's extracted, Open it (obviously) and leave everything alone, the program will move the image1.png and image2.png to the Lora Triggers folder you created. If it doesn't automatically do it due to your systems security (security is different on everyones PC's) you'll have to manually do it, don't blame me blame Microsoft. Hold your right mouse button down on the Lora_Trigger_Finder_V6.exe and select 'Send To' then from the popout select Desktop (Create shortcut) and a shortcut is now on your desktop. This isn't a necessity but it may make it easier for those who aren't really computer savvy.

The CivitAI LoRA Trigger Finder has been updated to Version 6, now only available as an Windows executable as there was an un-noticed bug in V3, it didn't append the missing LoRA's to the lora_not_found.txt file, all it did was add them again when it was re-run, that's now been fixed. You now have the option to view the HTML,the TXT version, the JSON and the Not Found LoRA's text directly from the GUI.

In short each time you run it, it now reads from a json file instead of going backwards and forwards to Civitai, it will take a little longer on it's first run but after that all it's looking for are newly added LoRA's and if you watch as it's going through your LoRA's for new ones, you will see SKIPPING when it comes across something already in the list. The HTML output file also now has a search function which makes it a damn site easier and a copy button for the trigger(s) of each LoRA so if you leave it open in a new tab when you are toying with AI, you can quickly get to the NSFW LoRA trigger words you want ;-)
It (the trigger finder) used to over-write the existing files which was great until you managed to find a missing LoRA and it proved a touch flaky so now it saves the files with a date and time addition so you know which is the most current one.

The files it creates are:
lora_not_found_DD-MM-YYYY_{time}.txt - self explanatory
lora_triggers_DD-MM-YYYY_{time}.html - a pretty html with a search box, a copy triggers button and thumbnails
lora_triggers_DD-MM-YYYY_{time}.json (don't manually edit this if you don't know what you're doing!)
Please see editing_json.txt in this folder
lora_triggers_DD-MM-YYYY_{time}.txt - added if you prefer to read a text file
config.json - An automatic field filler for the LoRA directory and the Output directory to save you having to do it every time you run it.
lora_trigger_finder.txt - a debug file that I decided to leave as it helps if it goes belly up but I can't see that happening, but who knows.

If you happen to remove any LoRA's you will have to delete the above output files and re-run it so it can re-populate the output files.

*A note on the header.png - I did have it hard coded in to the LTF but decided that it may be a tad gruesome for some, so if you want to change it, feel free. Just make sure it's 820x280 and the name is header and it's a png (header.png) and you put it right back where it belongs, that being the same folder as Lora_Trigger_Finder_V6.exe.

Cheers
Taff
12/09/25 
