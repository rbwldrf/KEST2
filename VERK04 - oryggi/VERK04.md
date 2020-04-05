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

   - 2.2e) Hópurinn getur sjálfgefið lesið skrár og keyrt forrit sem staðsett eru í möppunni, ásamt því að geta séð hvað er staðsett í möppunni.

   - 3.1b) Gat skapað textaskrá í möppu af því að Student02 hefur nægileg réttindi til þess.
   - 3.1c) Gat ekki opnað Staff möppu af því að Student02 hefur ekki nægileg réttindi til þess.
   - 3.1e) Gat ekki opnað Staff möppu af því að Student01 hefur ekki nægileg réttindi til þess. Student02 mappan er ekki til í Staff, né textaskráin sem á að vera í möppunni vegna þess að Student02 hafði ekki heldur nægileg réttindi til að framkvæma það.
   - 3.1l) Fæ ekki aðgang að Student01 möppunni en fæ aðgang að Student02 möppunni því að réttindum var breytt af Student01 á þann hát að einungis Student01 hefur aðgang að möppunni. 
   - 3.1n) Hafði aðgang að öllum möppum af því að Staff notendur hafa aðgang að öllum þremur möppum.
   - 3.2f) Get ekki sráð mig inn sem Staff02 vegna þess að notandinn er óvirkur.