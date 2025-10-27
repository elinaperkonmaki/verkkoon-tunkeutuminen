#h1 Sniff

b)	Aluksi testasin että netti toimii, pingasin ping -c 4 1.1.1.1 

 <img width="864" height="205" alt="image" src="https://github.com/user-attachments/assets/408fe336-a39c-410a-86b7-56e2e9ad68fb" />

katkaisin verkkoyhteyden ja kokeilin pingata uudelleen

<img width="919" height="153" alt="image" src="https://github.com/user-attachments/assets/f348b8ba-5a2f-4c35-bdd8-08eebd51e807" />

 
palautin verkkoyhteyden ja kokeilin taas pingiä
 
<img width="869" height="244" alt="image" src="https://github.com/user-attachments/assets/1d6b384b-9271-416b-95a7-d34e13e21630" />

c)	Wireshark asennus sujui ilman ongelmia

d)	 
<img width="1004" height="331" alt="image" src="https://github.com/user-attachments/assets/ef9c7bac-99f7-4f97-9510-e6469b4b2b3b" />



e)	Kuvankaappauksessa näkyy yhteyden muodostaminen terokarvinen.com
DNS-kyselyitä mm. terokarvinen.com ja zgo.at, TCP-kättely ja TLS-salaus, lopulta Application Dataa

 <img width="1004" height="440" alt="image" src="https://github.com/user-attachments/assets/c58491cc-cc1c-48f0-a12e-4311b6ea4de1" />


g)	Wiresharkissa näkyvä mac osoite on 52:54:00:cc:d7:12 tarkistin osoitteen OUI-kannasta, ei tullut osumia. Osoite kuuluu virtuaaliverkkokortille

<img width="548" height="39" alt="image" src="https://github.com/user-attachments/assets/3fd4435b-9cb7-4e66-a10a-dd2ec704f6eb" />

 
h)	<img width="1004" height="661" alt="image" src="https://github.com/user-attachments/assets/a21faef8-f3f8-434e-8e3d-9677ca61777c" />

 
i)	sieppauksess kone kyselee DNS:ltä osoitteita, esimerkiksi areena.fi:n ja mozilla.net:in IP:tä, sen jälkeen alkaa TCP-yhteyden muodostus porttiin 80, näkyy kolme vaihetta: SYN, SYN-ACK ja ACK. Näkyy myös TCP Keep-Alive viestejä joilla yhteys pidetään auki. Retransmission-paketteja, kun jotain on pitänyt lähettää uudestaan. Lisäksi osa liikenteestä on QUIC-protokollaa

<img width="1004" height="381" alt="image" src="https://github.com/user-attachments/assets/eec532ba-89ad-402a-a230-9044e2657bf6" />


## Viittaukset

https://terokarvinen.com/verkkoon-tunkeutuminen-ja-tiedustelu/#h1-sniff
https://terokarvinen.com/wireshark-getting-started/
https://www.wireshark.org/tools/oui-lookup.html
https://superuser.com/questions/1722057/setting-down-and-up-a-working-interface-with-ip-command-causes-it-to-stop-workin





