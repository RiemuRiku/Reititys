# Reititys
Tehtävänantona oli simuloida reititystaulun toimintaa. Ohjelmalle annetaan reititystaulu omana tiedostonaan, jonka jälkeen sille syötetään IP-osoitteita. Ohjelman tulee ohjata paketit perille oikein. Tehtävässä pisteytän "huti" meneviä reititystaulun reittejä (class A,B,C&subnetmask), matchaavien reittien pisteiden pysyessä samana. Jos sopivaa reittiä ei löydy, siirretään IP-osoite default-reittiä pitkin ylemmälle kerrokselle. Alimman pistemäärän reitti on tuolloin matchaava (huomioiden maskin bitit), tai "default"-reitti 0.0.0.0.

Vaatii väh. Roslyn 2.0 -compilerin.
# https://dotnetfiddle.net/n7K1NS
