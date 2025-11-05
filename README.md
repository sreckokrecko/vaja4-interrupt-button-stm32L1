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
