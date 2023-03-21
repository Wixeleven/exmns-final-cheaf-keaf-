# exmns-final-cheaf-keaf-

Šī ir Flask tīmekļa lietojumprogramma, kas nodrošina tulkošanas pakalpojumu, izmantojot Googletrans Python bibliotēku. Lietotāji var ievadīt tekstu, ko tulkot no vienas valodas citā, un tulkotais teksts tiks parādīts jaunā lapā.

Prasības
Šim kodam ir nepieciešama Python 3.x, Flask bibliotēka un Googletrans bibliotēka. Flask bibliotēku var instalēt, izmantojot pip, un Googletrans bibliotēku var instalēt, izmantojot pip vai citu pakotņu pārvaldnieku.

Lietošana
Lai palaistu lietojumprogrammu, terminālī palaidiet šādu komandu: python app.py

Tādējādi tiks palaists Flask serveris, un lietojumprogrammai var piekļūt, tīmekļa pārlūkprogrammā apmeklējot vietni http://localhost:8080.

Indeksa lapa
Lietojumprogrammas rādītāja lapā tiek parādīta veidlapa, kas ļauj lietotājiem ievadīt tekstu, ko viņi vēlas tulkot, un atlasīt avota un mērķa valodas.

Tulkošana
Lai tulkotu tekstu, lietotājam ir jāaizpilda nepieciešamie lauki (avota valoda, mērķa valoda un teksts) un jānoklikšķina uz pogas "Tulkot". Veidlapas dati tiek nosūtīti serverim, izmantojot POST pieprasījumu, un serveris izmanto Googletrans bibliotēku, lai tulkotu tekstu.

Rezultātu lapa
Kad tulkojums ir pabeigts, rezultātu lapā tiek parādīts tulkotais teksts. Ja tulkošanas laikā rodas kādas kļūdas vai ja trūkst obligāto lauku, tā vietā tiks parādīts kļūdas ziņojums.

Pateicības
Šo kodu ir uzrakstījis anonīms autors, un tas ir paredzēts tikai izglītojošiem nolūkiem. Googletrans bibliotēka ir Google tulkotāja API Python iesaiņojums, un uz API lietošanu attiecas Google noteikumi un nosacījumi.
