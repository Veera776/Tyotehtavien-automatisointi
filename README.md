
Tämän README tiedoston tarkoitus on antaa tietoa automatisoidusta tehtävästä Windows defender offline skannaus.
-----------------------------------------------------------------------------------------------------------------------------------------------------------


Powershell skriptin tarkoitus on ajastaa Microsoft defender tekemään offline skannaus kerran kuukaudessa. 

Offline tilassa on mahdollista havaita sellaiset haittaohjelmat, jotka olisi vaikeaa havaita tavallisella skannauksella. 

Tietokone käynnistyy uudelleen, ja se käynnistyy Windowsin palautusympäristössä, eli skannaus ei tarvitse verkkoyteyttä tai käyttöjärjestelmää toimiakseen.

Skannaus kestää noin 15 minuuttia tai enemmän(riippuen tilanteesta) jonka jälkeen tietokone käynnistyy automaattisesti uudelleen, ja pääsee kirjautumaan tavalliselle Windows ympäristölle.

Tarkastustulokset näkee kun menee defenderiin, siellä kohtaan "Virusten ja uhkien torjunta" sitten painaa tekstistä jossa lukee "Suojaushistoria".



HUOMIOITAVAA
-----------------------------------------------------------------------------------------------------------------------------------------------------------


Järjestelmään saattaa tulla sininen kuolemanruutu skannauksen alkaessa, silloin tietokone kannattaa käynnistää uudelleen. 

Skannaus vaatii järjestelmänvalvojan oikeudet jotta sen voi suorittaa. Skannausta ei siis ole mahdollista suorittaa sellaisella käyttäjällä jolla ei ole erityisoikeuksia hallita järjestelmää.

Defenderin on oltava ensisijainen virusturvaohjelmisto, jotta defenderin tietokanta on varmasti ajan tasalla, eli offine skannaus ei välttämättä ole mahdollista jos laitteessa käytetään jotakin toista virusturvaohjelmaa.

Windowsin palautusympäristö on oltava käytössä, jotta skannaus voidaan suorittaa (Windows recovery enviroment).

Ennen kuin skannaus ajetaan, kannattaa tallentaa kaikki keskeneräiset työt. 																																																			

Väliaikaistiedostoille on oltava riittävästi tilaa, kovalevyllä olisi hyvä olla ainakin joitakin satoja megatavuja vapaana. 





																				
																					


































																				









																				.
























































																										




																										


																																																							


















































