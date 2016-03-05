:do_not_litter: Fritz!Box Blacklist
===================================

Een lijst te blokeren domeinen in de Fritz!Box

Instructies
------------

1. Zie [AVM's instructies hoe een blacklist te gebruiken Fritz!Box](http://en.avm.de/service/fritzbox/fritzbox-7490/knowledge-base/publication/show/8_Restricting-Internet-access-using-parental-controls/)
2. Maak een kopie van [fritzbox-blacklist.txt](https://raw.githubusercontent.com/fabiobruna/fritzbox-blacklist/master/fritzbox-blacklist.txt) na je Fritz!Box' blacklist
3. Controleer of https verkeer nog werkt.

Algemeen
-----------

Maximaal 500 regels.

Zet elk te blokkeren domein op een eigen regel. Voeg geen commentaar of andere zaken toe.

Om `http://ads.example.com/some_script.js` te blokkeren voeg `ads.example.com` of alleen `example.com` toe. `example.com` zal alles blokkeren van `www.example.com` en andere subdomeinen.


Toevoegen
------------

Voeg regels toe bij een oorspronkelijke auteur(zie hieronder).

Voor specifiek Nederlandse domeinen, ik merge alle suggesties die goed zijn.

Legal
-----------

Author: [Frank Boës](http://3960.org) and others

Copyright & license: See LICENSE.txt

These instructions are NOT affiliated with, endorsed, or sponsored by AVM.
