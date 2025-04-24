Adresy MODBUS nastaviť podľa odst.10.1, str.39 na zariadení.

V servisnych nastaveniach modulu treba v pripade Slave ID inej ako 1, nastaviť v ReadScript hodnoty:
pri chybe jednotky na (SlaveID*100 + 21) 
a pri Alarme filtru na (SlaveID*100 + 24)

To isté pri všetkých čítaných registroch ktoré sú väčšie ako 100, pre bližšie informácie referujte na manuál.

Ostatné užitočné údaje sú v servisných atribútoch zariadení.
