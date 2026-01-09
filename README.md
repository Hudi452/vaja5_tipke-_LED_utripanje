#  Vaja5-buttons-LED-STM32F0

Odgovori na vprašanja:\
T1: PB10\
T2: PB11\
T3: PB12\
T4: PB13\
T5: PB14\
T6: PB15\
zelena LED: PC9\
modra LED: PC8

Pinout mikroprocesorja:\
![pinout](https://github.com/Hudi452/Vaja5-buttons-LED-STM32F0/blob/main/Pinout_konfiguracija.png)

Video (T1, T2, T3):\
![video1](Vaja5-MIN1.del-ezgif.com-speed.gif)

Komentar delovanja:\
Program deluje po pričakovanjih. Vsi vhodi za tipke so nastavljeni kot pull-down, kar pomeni, da je tipka pritisnjena, kadar prebermo 1 (GPIO_PIN_SET). Program najprej prebere stanje vseh tipk in tako spremenljivki izbrana_tipka dodeli številčno vrednost, ki nam pove, katera tipka je bila pritisnjena. Za tem s pomočjo switch-case stavkov na podlagi vrednosti spremenljivke izbrana_tipka izvedemo določeno funkcijo z zeleno in modro LED.  
