# DTAAE_Temporal
DTAAE (Disk Trash Avoid Avenue Exp) Repository for Viewer Made Malware series





# Main Details

DTAAE is a malware i've made in C# to destroy data while avoiding antiviruses.

No special effects nor other stuff, just direct, small and fast malware

(I only tested this on Win 7 and Win 10. Other systems like XP or 11 might not work)

I have tested 14 AVs and all of them failed protecting the computer 

(Note: the results can change in the future)

|Antivirus Name|Virus Won|Virus Lost|
|----------------|---------|--------|
|Avast|O| |
|MalwareBytes|O||
|AVG|O||
|Nod32|O||
|Kaspersky|O||
|Bitdefender|O||
|Avira|O||
|TotalAV|O||
|Panda|O||
|Emsisoft|O||
|Windows Defender|O||
|TrendMicro|O||
|Norton|O||
|McAfee|O||

# Attack Explanation

DTAAE's Attack Process is made of 3 Stages:

- Stage 1:

  Make itself as a Critical Process to trigger a BSOD if terminated (its also used to crash the PC after destruction is done)

- Stage 2:

  Deny access to the C: drive to all processes (this dosen't affect DTAAE as it dosen't access files and C: is just a partition, not a disk)

  (This is mainly what prevents antiviruses from stopping it)

- Stage 3:
 
  DTAAE will clear the first 5 MB of the disk, destroying the MBR (GPT if present) and possibly a bit of a partition

  (If it deletes some pieces of a partition its very unlikely that it could be recovered with the method used for MEMZ with a Windows installer ISO)


All 3 stages are done in a matter of seconds, its very hard to do anything if the user finds out the PC is infected.


# How to get

DTAAE is very dangerous and because of that i won't be giving it publicly, only to known channels that make Viewer Made Malware series.

If you are one of them, please follow these instructions:

- Download the zip file of this repository

- Extract it with the key i've sent you trough Email or Discord.

- You will get another zip file, the password for it is on the file's comments under the 'paasuwoodo' section

  (I recommend to use winrar to see the comments)

- Extract DTAAE on a VM WITHOUT internet, i don't want this to be automatically sent to random servers

  (This also includes NOT using public sandboxes like Any.Run or Intezer Analyzer or VirusTotal)

- Make sure your VM has .NET Framework 3.5 Installed (Check 'Turn On or Off Windows features' to install it)

- Before you run DTAAE create a file named 'GabeIsCute.X3' on the C: drive of your VM (this is to prevent running the malware accidentally)

- Have fun with it :D

If you see DTAAE being distributed on other places without my pemission please report it IMMEDIATELY to [Issues](https://github.com/Gabolate/DTAAE_Temporal/issues)

Made by Gabolate (Gabe) ∑:3 2024
