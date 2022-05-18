# Cybertalent-Digital-Forensic-writeup-

# 1.ADSL Modem
┌─[root@kali]─[~]

└──╼ #file Adsl-modem.bin 

Adsl-modem.bin: RAR archive data, v4, os: Win32

┌─[root@kali]─[~]

└──╼ #unrar e Adsl-modem.bin

UNRAR 5.50 freeware      Copyright (c) 1993-2017 Alexander Roshal

Extracting from Adsl-modem.bin

Flag{reversing_FW_is_interesting_but_this_is_for_fun}

Extracting  TL-MR3220 V2 _FW.bin                                      OK 

All OK
<h2>
Flag : Flag{reversing_FW_is_interesting_but_this_is_for_fun}

</h2>

# Lost Files 

┌─[root@kali]─[~/Downloads]

└──╼ #strings lost_files.mem.001 | grep -i flag | head 

B.j.YFlag(You_Get_It_2)

...Flag(You_Get_It_2)

Local\{C15730E2-145C-4c5e-B005-3BC753F42475}-once-flag

Adobe APP14 marker: version %d, flags 0x%04x 0x%04x, transform %d

unknown header flags set

GlobalFlags

?GetFlags@CxImage@@QBEKXZ

?SetFlags@CxImage@@QAEXK_N@Z

U_REGEX_INVALID_FLAG


<h2> Flag : Flag(You_Get_It_2)</h2>


