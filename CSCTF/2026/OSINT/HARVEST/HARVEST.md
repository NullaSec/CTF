#### Genesis24 - 

First step is using the Vigenére Cipher to decode the messages on the file 06. To achieve this we first need to know the key. The file 04. indicates that the key is the crew callsign for the operation.

As the 00. File said, the helicopter was carrying a sling load, so in the 03. file the only reports that mentioned "sling load" were the borts 22 and 25, I tried both and noticed some code words that were on the 05. file when i used the key = "ZHATVA". So that was the key.

decodeKey = ZHATVA

Already knowing the rigth key i decrypted the codes on the 06. file.

#1
received 10:21
     141020
     CVKEV DWGHT OVZEG KPZWZ NHKXB OEMTR DEMXN TZEDH NTZCL
     XIXOW XLZMW CRXHY ZEDXN YZAXW QACAS TOXAV RMSDU HDMNA
     SEDOV XJVNX X
     21

||      (Already Spaced)
\/

received 10:21
     141020
     DOKLAD X ZHATVA X GRUZ X SNOP X CHETYRE X MESTA X DOSTAVLEN X
     PP X SEM X VREMYA X DESYAT X DVADTSAT X BORT X DVADTSAT X DVA X KONEC
     21



AND

Note*: Tried the same key as the one before, and it didn't work, so i tried the other "sling load" CallSign and it didn't work, tried the ones left and the "VORON" worked. Maybe this means that this code was not for a sling load

#2
received 16:34
     141630
     YCBZN YLMCE JBOUE PNOYB MNZBN SGYSF OLDSF OLUCF OOMZR
     ILGDK YJRLF OOICF ZZPSK QFVAL VLJVR NHEOQ OGRHK OFZRG
     NOKLO JFKLG MWUHF VHOQU ZHPFR SYFBR X
     24

||      (Already Spaced)
\/

received 16:34
     141630
     DOKLAD X VORON X GRUZ X KORZINA X SHEST X MEST X DOSTAVLEN X PP X DVA X 
     STAROSELYE X VREMYA X SHESTNADTSAT X TRIDTSAT X BORT X TRIDTSAT X CHETYRE X KONEC
     24



-------

Focusing on the first code because the thing i mentioned on the note, the info that i could extract from it was the following:

DOKLAD X ZHATVA X GRUZ X SNOP X CHETYRE X MESTA X DOSTAVLEN X
     PP X SEM X VREMYA X DESYAT X DVADTSAT X BORT X DVADTSAT X DVA X KONEC

Report _ ZHATVA (callsign) _ Cargo _ portable EW jamming set _ 4 _ Pieces _ delivered _ 
PP _ 7 _ Time _ 10 _ ...

Didn't finish the decription because already got the info. needed.

PP-7
SNOP

so the final answer is CSCTF{PP-7_SNOP}

CORRECT

POINTS: 270 
