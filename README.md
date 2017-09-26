# opintopolku-proto
Uuden opintopolku.fi:n html-proto

master-branch autodeployataan 5 minuutin välein osoitteeseen https://testi.opintopolku.fi/proto/

Autodeploy ajetaan koneella essee käyttäjätunnuksen nws crontabista. 
Deploy-skripti ei ole tässä versionhallinnassa, koska päivittimen päivittäminen itsellään synnyttäisi Jännittäviä tietoturvaimplikaatiota.
Lähinnä siellä sanotaan "git checkout --force origin/master", mikä runttaa mahdolliset paikalliset muutokset pois deployattavista tiedostoista.
