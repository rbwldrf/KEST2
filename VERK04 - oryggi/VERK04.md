## 13.2.3.7 -- Bitlocker and Bitlocker To Go

   - 1.2c) Gott er að hafa recovery lykil til staðar ef tölvunni sem er að reyna að lesa drifið er neitað aðgang.
   - 2.1i) TPM (Trusted Platform Module) er örflaga sem skapar öryggislykil fyrir drifin sem Bitlocker á að vernda. Ef lyklinum er breytt á einhvern hátt, neitar Bitlocker aðgang að drifum sem hefur verið læst með Bitlocker fyrir breytingar, sem eiga sér stað meðal annars þegar að BIOS er breytt á einhvern hátt.

## 13.3.2.5 -- Configure Windows Local Security Policy

   - 4a) Notandinn hefur fimm tilraunir til að slá inn lykilorðið.
   - 4b) Notandinn verður að bíða í fimm mínutur áður enn hægt er að slá inn nýtt lykilorð.
   
   - 6b) Meðal annars hægt að koma í veg fyrir að notendur geta skráð sig inn yfir Remote Access, sem gæti bætt öryggi.

## 13.3.3.6 -- Configure Users and Groups in Wndows

   - 1.1b) Notendur eru: Administrator, DefaultAccount, Guest, og WDAGUtilityAccount.
   - 1.1c) Hópar eru meðal annars: Hyper-V Administrators, Performance Log Users, Distributed COM Users, Cryptographic Operators, og Access Control Assistance Operators.
   - 1.1d) Notandi í notkun tilheyrir System Managed Accounts Group.

   - 1.2b) Notandi er beðinn um að breyta um lykilorð eftir að hafa skráð sig inn í fyrsta skipti.
   - 1.2f1) Notendur sem tilheyra Users-hópnum er óheimilt að gera breytingar á tölvunni. Hins vegar geta þeir breytt skrám, skapað og eytt, fyrir utan þær skrár sem hafa sérstaklega verið stilltar til að koma í veg fyrir breytingar eða eyðslu.
   - 1.2f2) DefaultAccount, Guest, Student01 og 02, og Staff 01 og 02.