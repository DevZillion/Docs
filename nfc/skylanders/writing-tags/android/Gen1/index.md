# » Writing **Gen 1** or **UID LOCKED Tags** Skylander Tags Using Android Phones & a PC.

## » Getting TheSkyLib Ready [PC]
### [You have to do this for every tag you want to write]
> ### 1 - Download [TheSkyLib](https://github.com/ZillionMuffin/TheSkyLib/archive/refs/heads/main.zip).
> ### 2 - Extract it.
> ### 3 - Open it and place a dump of your **BLANK** tag inside ``dumps/blank_tags`` and place the dump of your skylander inside ``dumps/skylanders``.
> ### 4 - Now execute **Dump2LockedTag.bat** and do what the program asks for.
> ### 5 - You'll find your output dump on ``output\Dump2LockedTag``, that dump is ready to be written into your UID Locked/Gen 1 tag.

## » Writing [Android]
> ### For PC users just write it using your reader and [Mifare Windows Tool](https://github.com/xavave/Mifare-Windows-Tool).
> ### 1 - For Android users download [Mifare Classic Tool](https://github.com/ikarus23/MifareClassicTool/releases/download/v4.0.4/MifareClassicTool-4.0.4.apk)
> ### 2 - Open it, import your dump on the **Tools** Tab and write your dump on the **Write** tab.
> ### 3 - Now your dump is ready to go, if keys are asked use std.keys

## » **Re**-Writing [Android]
> ### The process is the same as writing the tags for the 1st time but when keys are asked use this instead:
> ### 1 - Open your **TheSkyLib** folder and execute **AccessKeyGen.bat**, input the name desired for the .keys file and your tag's UID.
> ### 2 - You'll find the keys on ``output/KeyAGen``, use them to ovewrite/re-write the skylander from your tag.
