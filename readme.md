# Confeção de PCB
_Método foto sensível_



#### Fritizing 

* Criar o arquivo no Fritzing

* Arquivo > Exportar > para produção > Etchable (svg)

* Imprimir os arquivos:

1. ```*_etch_copper_bottom.svg``` _(sem mirror)_ - Inverter as cores _(gerar negativo)_;

2. ```*_etch_mask_bottom.svg``` _(sem mirror)_ - Inverter as cores _(gerar negativo)_;

3. ```*_etch_silk_top_mirror.svg``` _(com mirror)_ - Inverter as cores _(gerar negativo)_.

 > Usando esses arquivos, na hora de aplicar a luz, a tinta da impressora sempre ficará voltada para o cobre. Isso é importante para garantir a qualidade das trilhas na pcb.
