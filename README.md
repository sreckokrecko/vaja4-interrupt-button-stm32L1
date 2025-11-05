# vaja4-interrupt-button-stm32L1

2.b)
pin PA0

c)
PC9-zelena led
PC8-modra led

3.c)
HAL_GPIO_TogglePin(GPIOC,GPIO_PIN_8);

d)
138,889 μ sek kar je 0,138 m sek

e)
HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);

f)
HAL_Delay(500);

4.e)
nič se ne zgodi , ker je naša funkcija zapiana tako, da samo zeleno LED prižgemo, modra LED pa deluje neprekinjeno

f)
zelena led se prižge in ugasne ko mi pritisnemo na tipko po želji

slika pinout mikroprocesorja
![cbd3f2e0-df62-4c4e-81af-f40bbd5a9773](https://github.com/user-attachments/assets/5bb77834-c80c-4d00-ad43-73e53ab7beec)

Komentar:
videli smo da ko pritisnemo tipko se zelena led užge če ga pritisnemo še enkrat se ugasne, ampak ko smo to naredili smo opazili da signal skače

posnetek delovanja:

![MicrosoftTeams-video1-ezgif com-optiwebp](https://github.com/user-attachments/assets/93059a82-8c85-4260-a332-20d685a8152c)
