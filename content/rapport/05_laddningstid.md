---
---
Laddningstid
=========================

Urval
-----------------------
Det hemsidor jag valt att analysera är: [Expressen](https://www.expressen.se), [CNN](https://edition.cnn.com/) och [BBC](https://www.bbc.com/news). Jag valde dessa sidor då det är hemsidor som jag frekvent besöker, framförallt Expressen som jag besöker dagligen. De andra nyhets-sidorna valde jag då jag ville jämföra hemsidor med samma fokus. Nyhetshemsidor så som de ovan tyckte jag var intressant då det oftast har en massa innehåll att läsa in också, tänkte att det kunde vara intressant att se hur de olika organisationerna har löst det.

Metod
-----------------------
De verktyg jag har valt att använda är Google's [PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/) samt Chrome's inbyggda Dev-Tools.

Resultat
-----------------------
Länk till mitt excel-dokument för [rådata](https://docs.google.com/spreadsheets/d/1Dw1pkpgWa2pu5UTg7aKrfdgOE4Bk8C0Bx9MJDfBFz6E/edit#gid=0).

Den första hemsida jag tänkte analysera är [Expressen](https://www.expressen.se): [FIGURE src="image/Expressen.png?w=500"]
<table>
<thead>
<tr>
  <th>Webbplats</th>
  <th>Desktop</th>
  <th>Mobil</th>
  <th>Laddningstid</th>
  <th>Resurser</th>
  <th>Storlek</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Start</td>
  <td>87</td>
  <td>49</td>
  <td>1.41s</td>
  <td>115</td>
  <td>1.5MB</td>
</tr>
<tr>
  <td>Sport</td>
  <td>79</td>
  <td>49</td>
  <td>1.06s</td>
  <td>134</td>
  <td>1.13MB</td>
</tr>
<tr>
  <td>Nöje</td>
  <td>80</td>
  <td>69</td>
  <td>0.8s</td>
  <td>96</td>
  <td>783KB</td>
</tr>
</tbody>
</table>
Expressen hade ändå ett helt OK betyg från PageSpeed Insights vad gäller dator och mobil. Två förbättringar som skulle kunna göras här för att optimera inläsningen av sidan är bl.a. att skjuta upp CSS som inte används, samt att göra detsamma på bilder som inte visas på skärmen. Det vill säga att låta bilder som inte visas på skärmen för tillfället istället läsas in med lat inläsning.

Den andra hemsidan jag tänkt analysera är [CNN](https://edition.cnn.com/): [FIGURE src="image/CNN.png?w=500"]
<table>
<thead>
<tr>
  <th>Webbplats</th>
  <th>Desktop</th>
  <th>Mobil</th>
  <th>Laddningstid</th>
  <th>Resurser</th>
  <th>Storlek</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Start</td>
  <td>64</td>
  <td>3</td>
  <td>2.47s</td>
  <td>129</td>
  <td>2.6MB</td>
</tr>
<tr>
  <td>Entertainment</td>
  <td>74</td>
  <td>5</td>
  <td>2.27s</td>
  <td>109</td>
  <td>2.7MB</td>
</tr>
<tr>
  <td>Travel</td>
  <td>78</td>
  <td>22</td>
  <td>2.16s</td>
  <td>151</td>
  <td>3.4MB</td>
</tr>
</tbody>
</table>
CNN var den hemsida som presterade sämst enligt PageSpeed Insights. Den största förändringar som drastiskt skulle öka inläsningen av hemsidan är att skicka bilderna i ett modernare bildformat. Istället för att använda JPEG eller PNG så ger JPEG 2000, JPEG XR och WebP ofta bättre komprimering. Detta skulle på så vis förbättra nedladdningen av sidan och bidra till en minskad dataförbrukning.

Den sista hemsida jag tänkte analysera är [BBC](https://www.bbc.com/): [FIGURE src="image/BBC.png?w=500"]
<table>
<thead>
<tr>
  <th>Webbplats</th>
  <th>Desktop</th>
  <th>Mobil</th>
  <th>Laddningstid</th>
  <th>Resurser</th>
  <th>Storlek</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Start</td>
  <td>100</td>
  <td>87</td>
  <td>1.86s</td>
  <td>148</td>
  <td>1.8MB</td>
</tr>
<tr>
  <td>Weather</td>
  <td>93</td>
  <td>15</td>
  <td>1.75s</td>
  <td>128</td>
  <td>1.8MB</td>
</tr>
<tr>
  <td>Travel</td>
  <td>93</td>
  <td>24</td>
  <td>2.44s</td>
  <td>198</td>
  <td>1.7MB</td>
</tr>
</tbody>
</table>
Vad gäller dessa tre analyser så är BBC den hemsida som pressterade bäst. Det som skulle kunna göras för att förbättra inläsningen är dock att ta bort resurser som för tillfället blockerar renderingen av sidan.


Analys
-----------------------
Jag valde att analysera dessa tre hemsidor då de oftast använder en hel del bilder till deras diverse artiklar. Till viss grad så hade de ändå gemensamt att de kan använda modernare bildformat för att snabba på inläsningshastigheten. Vinnaren i mitt test är nog ändå BBC. Det kändes som att sakerna laddade i rätt ordning och jag inte behövde vänta på att min artikel osv skulle läsas in. Trots att Expressen hade något snabbare inläsningshastighet så var det oftast en massa reklam som lästes in först vilket bara upplevdes som en röra, BCC prioreterade ändå rätt innehåll enligt min mening. Men trots det så hamnar Expressen på en andra plats och CNN på en tredje plats. Jag skulle nog säga att en sekund är en rätt bra absolut laddningstid. Allting behöver inte vara inläst och inte heller interaktivt, men går jag in på en hemsida så vill jag iaf kunna se "main"-innehållet efter en sekund. Efter 2 sekunder så tycker jag att hemsidan ska vara interaktiv, kanske bara jag som är otålig men det känner jag personligen är en rätt bra gräns. Jag tycker nog ändå att de hemsidor ja prövade klarade det rätt bra, var egentligen ingenting jag tänkte på. Jag skrev också ineledningsvis att detta är tre sidor jag ganska frekvent besöker och jag kan ärligen säga att jag inte tänkt på det tidigare, att de läses in långsamt dvs, vilket enligt min mening ändå betyder att de presterade bra ställt emot detta test.
Övrigt
-----------------------
