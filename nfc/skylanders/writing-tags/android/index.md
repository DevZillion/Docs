# » Are your tags Gen 0 or Gen 2?

>[Gen 0 (UID) or Locked UID Tags](https://devzillion.github.io/Docs/nfc/skylanders/writing-tags/android/Gen1/)
>
>[Gen 2 (CUID) - Not Recommended anymore as Gen 1 method is better but part of this guide is useful to some people.](https://devzillion.github.io/Docs/nfc/skylanders/writing-tags/android/Gen2/)


## » Reading your actual Skylanders figures [NOT WRITTEN TAGS]
>### 1 - Download [this](https://github.com/ZillionMuffin/TheSkyLib/archive/refs/heads/main.zip) to a PC running Windows.
>### 2 - Extract it using [WinRar](https://winrar.com/) or [7Zip](http://7zip.org/).
>### 3 - Execute **the AccessKeyGen.bat** file and write the name wanted for the .keys file and the tag's UID.
>### 4 - Tag's UID are the 1st 8 characters from Sector 0 Block 0 and look like this `2F03EC30`.
>### 
>### Android
>### - Now transfer the .keys files to your phone and read it with that file using the Mifare Classic Tool app.
>### - From there you can read it the same as a written tag but using the generated .keys
