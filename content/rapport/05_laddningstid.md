---
---
Laddningstid
=========================

Du skall välja ut ett antal olika webbplatser och testa dem för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag valde dessa webbplatser eftersom jag och/eller andra jag känner ofta besöker dem.

<p>webbplatserna är:</br>
https://www.emp-shop.se</p>

<p>https://arbetsformedlingen.se</p>

<p>https://www.facebook.com</p>


Metod
-----------------------

Google Pagespeed och Devtools


Resultat
-----------------------
<a href="https://docs.google.com/spreadsheets/d/1Vtt5hhLbNj8yzO9t6iGmJOHfnlDgRcLliaIji03xJA4/edit?usp=sharing">Länk till excelark för rådata.</a>

<p><H4>-EMP-</H4></p>
[FIGURE src="image/emp.png?w=1000" class="right"]

<table style="width:100%">
    <tr>
        <th>Webbplats</th>
        <th>Desktop</th>
        <th>Mobile</th>
        <th>Laddningstid</th>
        <th>Resurser</th>
        <th>Storlek</th>
    </tr>
    <tr>
        <td>Index</td>
        <td>70</td>
        <td>35</td>
        <td>20.9</td>
        <td>139</td>
        <td>2.5</td>
    </tr>
    <tr>
        <td>Logga in</td>
        <td>99</td>
        <td>75</td>
        <td>8.9</td>
        <td>92</td>
        <td>8.6</td>
    </tr>
    <tr>
        <td>Varukorg</td>
        <td>96</td>
        <td>55</td>
        <td>9.28</td>
        <td>87</td>
        <td>3.1</td>
    </tr>
</table>

Sidorna behöver ha bättre speed. EMP får 70+ på Desktop, vilket är okej men det tar över 8.9s att ladda in sidorna.








<p><H4>-Arbetsförmedlingen-</H4></p>
[FIGURE src="image/arbets.png?w=1000" class="right"]

<table style="width:100%">
    <tr>
        <th>Webbplats</th>
        <th>Desktop</th>
        <th>Mobile</th>
        <th>Laddningstid</th>
        <th>Resurser</th>
        <th>Storlek</th>
    </tr>
    <tr>
        <td>Index</td>
        <td>84</td>
        <td>38</td>
        <td>2.16</td>
        <td>87</td>
        <td>4.4</td>
    </tr>
    <tr>
        <td>Platsbanken</td>
        <td>84</td>
        <td>35</td>
        <td>2.36</td>
        <td>103</td>
        <td>6.0</td>
    </tr>
    <tr>
        <td>Kontakt</td>
        <td>85</td>
        <td>36</td>
        <td>1.8</td>
        <td>83</td>
        <td>4.3</td>
    </tr>
</table>

Sidornas laddningstid är under 2.36s så det är bra. Något som dem dock behöver jobba på är Mobile speed.






<p><H4>-Facebook-</H4></p>
[FIGURE src="image/facebook.png?w=1000" class="right"]

<table style="width:100%">
    <tr>
        <th>Webbplats</th>
        <th>Desktop</th>
        <th>Mobile</th>
        <th>Laddningstid</th>
        <th>Resurser</th>
        <th>Storlek</th>
    </tr>
    <tr>
        <td>Index</td>
        <td>92</td>
        <td>81</td>
        <td>9.61</td>
        <td>72</td>
        <td>7.6</td>
    </tr>
    <tr>
        <td>Användarvillkor</td>
        <td>97</td>
        <td>80</td>
        <td>9.43</td>
        <td>55</td>
        <td>5.6</td>
    </tr>
    <tr>
        <td>Sidor</td>
        <td>97</td>
        <td>84</td>
        <td>9.2</td>
        <td>59</td>
        <td>3.7</td>
    </tr>
</table>

Sidan får godkänt på de speedtest som jag gjort för Desktop och Mobile. Men även här behöver dem jobba på laddningstiden. Det tar över 9.2s att ladda in sidorna.


Analys
-----------------------

<table style="width:100%">

    <tr>
        <th>Vinnare</th>
        <th>Desktop</th>
        <th>Mobile</th>
        <th>Laddningstid</th>
        <th>Resurser</th>
        <th>Storlek</th>
    </tr>
    <tr>
        <td>1</td>
        <td>Facebook</td>
        <td>Facebook</td>
        <td>Arbetsförmedlingen</td>
        <td>Facebook</td>
        <td>EMP</td>
    </tr>
    <tr>
        <td>2</td>
        <td>EMP</td>
        <td>EMP</td>
        <td>EMP</td>
        <td>Arbetsförmedlingen</td>
        <td>Arbetsformedlingen</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Arbetsförmedlingen</td>
        <td>Arbetsformedlingen</td>
        <td>Facebook</td>
        <td>EMP</td>
        <td>Facebook</td>
    </tr>
</table>

Mobile pagespeed var sämre än Desktop pagespeed för alla sidor. Alla sidor behöver få bättre Mobile pagespeed. Det tycker jag är ganska konstigt eftersom så många gärna vill kunna använda sin telefon. I testet var ändå Facebook bäst, vilket kanske inte är så konstigt eftersom så många fler besöker sidan dagligen.

Detta är sidor som jag och/eller några som jag känner ofta besöker och jag upplever dem inte slöa alls. Men enligt statestiken så är 2/3 av mina testsidor väldigt slöa. Jag blev också förvånad då ingen av sidorna fick 100 i Desktop speed. vinnaren i detta testet är ändå facebook som fick 3 bäst i fem punkter.

Anmärkningsvärt är att Arbetsförmedlingen hade en väldigt kort laddningstid men många resurser att ladda in och relativt stor storlek.

Jag tycker att laddningstiden för en sida skall vara under 3sek, vilket bara arbetsförmedlingens hemsida klarar av. Alla sidor borde förbättra laddningstiden och få bättre Mobile pagespeed.



Referenser
-----------------------
<p>EMP</p>

<p>Arbetsförmedlingen</p>

<p>Facebook</p>

Övrigt
-----------------------

Av: Linnea Gullmak
