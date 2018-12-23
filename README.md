# Vaja3-ADC-trigger-timer-conversion-STM32F0


Cube MX:

b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni
analogni vhod. Kateri pin je to? PC0 .

e) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni
kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v
zeleno barvo. Kaj se izpiše poleg pina? ADC_IN10.

h) Aktiviramo samo zeleno LED diodo na ustreznem izhodu PC9.

i) V Clock Configuration spremenimo APB1 Timerl clock (MHz) na 16 MHz. Kaj
opazite? Vse se spremeni na 16Mhz.


l) V configuration kliknemo gumb za TIM1, ki je v polju Control. Časovniku bi radi spremenili frekvenco na 1
kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju Prescaler (PSC – 16 bit value). Koliko
znaša ta vrednost? 16000 . 



kylev5:
f) Branje vrednosti želimo prikazati z utripanjem zelene LED diode na STM32f0 ploščici. Uporabite metodo
TogglePin iz HAL knjižnice in zapišite ukaz: (pomagajte si z vajo 0a).
HAL_GPIO_TogglePin(GPIOD,GPIO_PIN9);
