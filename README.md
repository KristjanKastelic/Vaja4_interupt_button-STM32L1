# Vaja4_interupt_tipka_Skupina4

V Pinout % Configuraton pogledu glede na vašo razvojno ploščico ugotovite, ali
lahko uporabite modro tipko za digitalni vhod kot interrupt (GPIO_EXT…). Če da,
kateri pin je to?
- PA0

Zapišite naslov izhodnih pinov za zeleno in modro LED:
- LD3(green Led) , LD4(blue Led)

Znotraj te funkcije zapišite ukaz za vklop/izklop zelene LED (pomagajte si z metodo
toggle, glej vaja0a).
- HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_0);

Koliko znaša (v mili sekundah) zapisana zakasnitev, ki jo proizvede zanka for?
- 1000.

V user code begin 3 - zanka while(1) - zapišite ukaz za utripanje modre LED (metoda
toggle, glej vaja0a):
- HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_0);

V to zanko dodajte ukaz za zakasnitev z funkcijo Delay iz knjižnice HAL, in sicer pol
sekunde (glej vaja0a):
- HAL_Delay(500);

Kpmentar: program mi ne deluje verjetno ni nekaj prav v kodi.
