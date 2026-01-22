# Ecoforest Modbus Variables List for HP24 

Quick guide to Modbus communications

## EQUIPMENT (EQUIPO)

### SYSTEM (SISTEMA)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES                                                                                                                                                                                                     |
|------| --- | --- | --- | --- | --- | --- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| x    | Year (system) | A | 2000 | X |  | 1 | -                                                                                                                                                                                                          |
| x    | Month (system) | A | 2001 | X |  | 1 | -                                                                                                                                                                                                          |
| x    | Day (system) | A | 2002 | X |  | 1 | -                                                                                                                                                                                                          |
| x    | Hour (system) | A | 2003 | X |  | 1 | -                                                                                                                                                                                                          |
| x    | Minute (system) | A | 2004 | X |  | 1 | -                                                                                                                                                                                                          |
| x    | Software platform | A | 2005 | X |  | 1 | 7=ESO22<br>12=AWD24<br>13=WWD24<br>14=WWC24                                                                                                                                                                |
| x    | Product range | A | 2006 | X |  | 1 | 1=HP<br>2=PS<br>3=EM<br>4=SM                                                                                                                                                                               |
| x    | Software version VXX | A | 2007 | X |  | 1 | -                                                                                                                                                                                                          |
| x    | Compilation type letter (subversion) | A | 2008 | X |  | 1 | 1=A; 2=B; 3=C; 4=D; 5=E; 6=F; 7=G; 8=H; 9=I; 10=J; 11=K; 12=L; 13=M; 14=N; 15=O; 16=P; 17=Q; 18=R; 19=S; 20=T; 21=U; 22=V; 23=W; 24=X; 25=Y; 26=Z;                                                         |
| x    | Software version BXX | A | 2009 | X |  | 1 | -                                                                                                                                                                                                          |
|      | Model code digit 1 (HP model/ODU model) | A | 2010 | X |  | 1 | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 2 (HP model/ODU model) | A | 2011 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 3 (HP model/ODU model) | A | 2012 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 4 (HP model/ODU model) | A | 2013 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 5 (HP model/ODU model) | A | 2014 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 6 (HP model/ODU model) | A | 2015 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 1 (IDU model) | A | 2018 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 2 (IDU model) | A | 2019 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 3 (IDU model) | A | 2020 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 4 (IDU model) | A | 2021 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 5 (IDU model) | A | 2022 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
|      | Model code digit 6 (IDU model) | A | 2023 | X |  |  | 1=0; 2=1; 3=2; 4=3; 5=4; 6=5; 7=6; 8=9;10=11; 11=A; 12=B; 13=C; 14=D; 15=E; 16=F; 17=G; 18=H; 19=I; 20=J; 21=K; 22=L; 23=M; 24=N; 25=O; 26=P; 27=Q; 28=R; 29 =S; 30=S; 31=U; 32=V; 33=W; 34=X; 35=Y; 36=Z; |
| x    | Device Role | A | 2026 | X |  | 1 | 0 = None 1 = Individual master<br>2 = ecoGEO block master<br>3 = Block slave<br>4 = Supervisor<br>5 = Individual slave<br>6 = ecoAIR block master                                                                     |

### SERVICE STATUS (INFORMACIÓN ESTADO SERVI- CIOS)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
|------| --- | --- | --- | --- | --- | --- | --- |
| x    | DHW production mode status | A | 2030 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Heating production mode status | A | 2031 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Active cooling production mode status | A | 2032 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Passive cooling production mode status | A | 2033 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Pool production mode status | A | 2034 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Afreeze production mode status | A | 2035 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Dryfloor production mode status | A | 2036 | X |  | 1 | 0=OFF<br>1=ON |

### GENERATION SYSTEMS STATUS (INFORMACIÓN ESTADO GENERA- DORES)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
|------| --- | --- | --- | --- | --- | --- | --- |
| x    | Heat pump status | A | 2045 | X |  | 1 | 0=OFF<br>1=ON<br>2=EMERGENCY |
| x    | Integrated auxililliary heater status (Aux 1) | A | 2046 | X |  | 1 | 0=OFF<br>1=ON |
| x    | Generic external auxililliary heater status (Aux 2) | A | 2047 | X |  | 1 | 0=OFF<br>1=ON |
|      | DHW auxililliary heater status (Aux 3) | A | 2048 | X |  | 1 | 0=OFF<br>1=ON |
|      | BUFFER auxililliary heater status (Aux 4) | A | 2049 | X |  | 1 | 0=OFF<br>1=ON |
|      | Generic external auxililliary chiller status (Aux 5) | A | 2050 | X |  | 1 | 0=OFF<br>1=ON |

### CONSUMPTION GROUPS STATUS (INFORMACIÓN ESTADO GRUPOS CONSUMO)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | DHW recirculation status | A | 2055 | X |  | 1 | 0=OFF<br>1=ON |
|  | Group 1 status | A | 2056 | X |  | 1 | 0=OFF<br>1=ON |
|  | Group 2 status | A | 2057 | X |  | 1 | 0=OFF<br>1=ON |
|  | Group 3 status | A | 2058 | X |  | 1 | 0=OFF<br>1=ON |
|  | Group 4 status | A | 2059 | X |  | 1 | 0=OFF<br>1=ON |
|  | Group 5 status | A | 2060 | X |  | 1 | 0=OFF<br>1=ON |

### ALARMS (INFORMATION) INFORMACIÓN ALARMAS

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Alarm level | A | 2065 | X |  | 1 | 0=No alarm<br>1=Active alarm<br>2=Active alarm + recurrent alarm<br>3=Recurrent alarm<br>4=Long time alarm<br>5=Lock-down due to alarm |
|  | Lock alarma code | A | 2066 | X |  | 1 | Ver listado códigos de alarma See alarm code list |
|  | Long time alarm code | A | 2067 | X |  | 1 |  |
|  | Recurrence alarm code | A | 2068 | X |  | 1 |  |
|  | Active alarm code 1 | A | 2069 | X |  | 1 |  |
|  | Active alarm code 2 | A | 2070 | X |  | 1 |  |
|  | Active alarm code 3 | A | 2071 | X |  | 1 |  |
|  | Active alarm code 4 | A | 2072 | X |  | 1 |  |
|  | Active alarm code 5 | A | 2073 | X |  | 1 |  |
|  | Reset recurrence alarm by BUS | A | 2074 |  | X |  | 0=OFF<br>1=ON |

### HEAT PUMP GENERAL INFORMATION (INFORMACIÓN GENERAL BOMBA CALOR)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
|------| --- | --- | --- | --- | --- | --- | --- |
| x    | Outdoor temperature | A | 2080 | X |  | 0.1 | - |
| x    | Primary circuit outlet temperature | A | 2081 | X |  | 0.1 | - |
| x    | Primary circuit intlet temperature | A | 2082 | X |  | 0.1 | - |
| x    | Primary circuit pressure | A | 2083 | X |  | 0.1 | - |
| x    | Secondary circuit outlet temperature | A | 2084 | X |  | 0.1 | - |
| x    | Secondary circuit intlet temperature | A | 2085 | X |  | 0.1 | - |
| x    | Secondary circuit pressure | A | 2086 | X |  | 0.1 | - |
|      | Tertiary circuit outlet temperature | A | 2087 | X |  | 0.1 | - |
|      | Tertiary circuit intlet temperature | A | 2088 | X |  | 0.1 | - |
|      | Auxiliary heater outlet temperature | A | 2089 | X |  | 0.1 |  |
|      | Auxiliary chiller outlet temperature | A | 2090 | X |  | 0.1 | - |
|      | Air unit outlet temperature | A | 2091 | X |  | 0.1 | - |
| x    | Compressor suction temperature | A | 2092 | X |  | 0.1 | - |
| x    | Compressor suction pressure | A | 2093 | X |  | 0.1 | - |
| x    | Compressor discharge pressure | A | 2094 | X |  | 0.1 | - |
| x    | Compressor discharge temperature / Scroll temperature | A | 2095 | X |  | 0.1 | - |
| x    | Superheat | A | 2096 | X |  | 0.1 | - |
| x    | Inverter temperature | A | 2097 | X |  | 0.1 | - |
| x    | Evaporation temperatura | A | 2098 | X |  | 0.1 | - |
| x    | Condensing temperature | A | 2099 | X |  | 0.1 | - |
|      | DT primary circuit | A | 2100 | X |  | 0.1 | - |
|      | DT secondary circuit | A | 2101 | X |  | 0.1 | - |
|      | DT tertiary circuirt | A | 2102 | X |  | 0.1 | - |
| x    | Compresor starts (high part) | A | 2103 | X |  | 1 |  |
| x    | Compresor starts (low part) | A | 2104 | X |  | 1 |  |
| x    | Compressor operating hours (high part) | A | 2105 | X |  | 1 |  |
| x    | Compressor operating hours (low part) | A | 2106 | X |  | 1 |  |

## SERVICES (SERVI- CIOS)

### ACCUMULATED SERVICES INFORMATION (INFORMACIÓN ACUMULACIÓN SERVICIOS)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
|------| --- | --- | --- | --- | --- | --- | --- |
| x    | DHW tank temperature | A | 2130 | X |  | 0.1 | - |
| x    | DHW recirculation temperature | A | 2131 | X |  | 0.1 | - |
| x    | Heating buffer tank temperature | A | 2132 | X |  | 0.1 | - |
| x    | Cooling buffer tank temperature | A | 2133 | X |  | 0.1 | - |
|      | Pool temperature | A | 2134 | X |  | 0.1 | - |

### CONSUMPTION GROUPS INFORMATION (INFORMACIÓN GRUPOS IMPUL- SIÓN)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Group 1 delivery temperature | A | 2140 | X |  | 0.1 | - |
|  | Group 2 delivery temperature | A | 2141 | X |  | 0.1 | - |
|  | Group 3 delivery temperature | A | 2142 | X |  | 0.1 | - |
|  | Group 4 delivery temperature | A | 2143 | X |  | 0.1 | - |
|  | Group 5 delivery temperature | A | 2144 | X |  | 0.1 | - |

### SETPOINTS CONFIGURATION (CONFIGURACIÓN CONSIGNAS)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES                                                           |
|------| --- | --- | --- | --- | --- | --- |------------------------------------------------------------------|
| x    | DHW setpoint | A | 2150 | X |  | 0.1 | The temperature at which the water is heated varies according to the scheduler. |
|      | Pool setpoint | A | 2151 | X |  | 0.1 | -                                                                |
| x    | Buffer heating setpoint | A | 2152 | X |  | 0.1 | -                                                                |
| x    | Buffer cooling setpoint | A | 2153 | X |  | 0.1 | -                                                                |
| x    | HTR setpoint | A | 2154 | X |  | 0.1 | -                                                                |
| x    | Group 1 heating setpoint (final setpoint) | A | 2155 | X |  | 0.1 | -                                                                |
| x    | Group 1 cooling setpoint (final setpoint) | A | 2156 | X |  | 0.1 | -                                                                |
|      | Group 2 heating setpoint (final setpoint) | A | 2157 | X |  | 0.1 | -                                                                |
|      | Group 2 cooling setpoint (final setpoint) | A | 2158 | X |  | 0.1 | -                                                                |
|      | Group 3 heating setpoint (final setpoint) | A | 2159 | X |  | 0.1 | -                                                                |
|      | Group 3 cooling setpoint (final setpoint) | A | 2160 | X |  | 0.1 | -                                                                |
|      | Group 4 heating setpoint (final setpoint) | A | 2161 | X |  | 0.1 | -                                                                |
|      | Group 4 cooling setpoint (final setpoint) | A | 2162 | X |  | 0.1 | -                                                                |
|      | Group 5 heating setpoint (final setpoint) | A | 2163 | X |  | 0.1 | -                                                                |
|      | Group 5 cooling setpoint (final setpoint) | A | 2164 | X |  | 0.1 | -                                                                |

### INDOOR ZONES INFORMATION (INFORMACIÓN ZONAS AMBIENTE INTERIOR)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Zone 1 temperature | A | 2170 | X |  | 0.1 | - |
|  | Zone 2 temperature | A | 2171 | X |  | 0.1 | - |
|  | Zone 3 temperature | A | 2172 | X |  | 0.1 | - |
|  | Zone 4 temperature | A | 2173 | X |  | 0.1 | - |
|  | Zone 5 temperature | A | 2174 | X |  | 0.1 | - |
|  | Zone 1 humidity | A | 2175 | X |  | 0.1 | - |
|  | Zone 2 humidity | A | 2176 | X |  | 0.1 | - |
|  | Zone 3 humidity | A | 2177 | X |  | 0.1 | - |
|  | Zone 4 humidity | A | 2178 | X |  | 0.1 | - |
|  | Zone 5 humidity | A | 2179 | X |  | 0.1 | - |

## ENERGY METERS (CONTADORES ENERGÍA) ENERGY METERS (CONTADORES ENERGÍA)

### INSTANTANEOUS COUNTER INFORMATION (INFORMACIÓN MEDIDOR INSTAN- TÁNEO)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
|------| --- | --- | --- | --- | --- | --- | --- |
|      | Instantaneous power units | A | 2185 | X |  | 1 | 10=W<br>20=kW<br>30=MW |
| x    | Total heating power | A | 2186 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | Heating service power | A | 2187 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | DHW service power | A | 2188 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
|      | Pool service power | A | 2189 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | Total cooling power | A | 2190 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | Active cooling service power | A | 2191 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | Passive cooling service power | A | 2192 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | Total electric consumption | A | 2193 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
| x    | Electric consumption in surplus mode | A | 2194 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |

### CURRENT DAY COUNTER INFORMATION (INFORMACIÓN CONTADOR DÍA ACTUAL)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Current day energy units | A | 2200 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | DHW useful energy in current day | A | 2201 | X |  | 0.1 | - |
|  | Heating useful energy in current day | A | 2202 | X |  | 0.1 | - |
|  | Pool useful energy in current day | A | 2203 | X |  | 0.1 | - |
|  | Active cooling useful energy in current day | A | 2204 | X |  | 0.1 | - |
|  | Passive cooling useful energy in current day | A | 2205 | X |  | 0.1 | - |
|  | Energy consumption in current day | A | 2206 | X |  | 0.1 | - |
|  | Surplus energy consumption in current day | A | 2207 | X |  | 0.1 | - |
|  | Current day auxiliary heaters units | A | 2208 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | Pool service auxiliary heaters consump- tion in current day | A | 2209 | X |  | 0.1 | - |
|  | DHW service auxiliary heaters consump- tion in current day | A | 2210 | X |  | 0.1 | - |
|  | Heating service auxiliary heaters con- sumption in current day | A | 2211 | X |  | 0.1 | - |

### CURRENT MONTH COUNTER INFORMATION (INFORMACIÓN CONTADOR MES ACTUAL)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Current month energy units | A | 2220 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | DHW useful energy in current month | A | 2221 | X |  | 0.1 | - |
|  | Heating useful energy in current month | A | 2222 | X |  | 0.1 | - |
|  | Pool useful energy in current month | A | 2223 | X |  | 0.1 | - |
|  | Active cooling useful energy in current month | A | 2224 | X |  | 0.1 | - |
|  | Passive cooling useful energy in current month | A | 2225 | X |  | 0.1 | - |

## ENERGY METERS (CONTADORES ENERGÍA)

### CURRENT MONTH COUNTER INFORMATION (INFORMACIÓN CONTADOR MES ACTUAL)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Energy consumption in current month | A | 2226 | X |  | 0.1 | - |
|  | Surplus energy consumption in current month | A | 2227 | X |  | 0.1 | - |
|  | Current month auxiliary heaters units | A | 2228 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | Pool service auxiliary heaters consump- tion in current month | A | 2229 | X |  | 0.1 | - |
|  | DHW service auxiliary heaters consump- tion in current month | A | 2230 | X |  | 0.1 | - |
|  | Heating service auxiliary heaters con- sumption in current month | A | 2231 | X |  | 0.1 | - |

### ANNUAL ENERGY METER INFORMATION (INFORMA- CIÓN CONTADOR AÑO ACTUAL)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Annual counter units | A | 2235 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | Annual DHW useful energy | A | 2236 | X |  | 0.1 | - |
|  | Annual heating useful energy | A | 2237 | X |  | 0.1 | - |
|  | Pool heating useful energy | A | 2238 | X |  | 0.1 | - |
|  | Annual active cooling useful energy | A | 2239 | X |  | 0.1 | - |
|  | Annual passive cooling useful energy | A | 2240 | X |  | 0.1 | - |
|  | Annual energy consumption | A | 2241 | X |  | 0.1 | - |
|  | Annual surplus energy consumption | A | 2242 | X |  | 0.1 | - |
|  | Current month auxiliary heaters units | A | 2243 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | Pool service auxiliary heaters consump- tion in current year | A | 2244 | X |  | 0.1 | - |
|  | DHW service auxiliary heaters consump- tion in current year | A | 2245 | X |  | 0.1 | - |
|  | Heating service auxiliary heaters con- sumption in current year | A | 2246 | X |  | 0.1 | - |

### HISTORIC (LAST 12 MONTH COMPLETED) (INFORMACIÓN CONTADOR HIS- TORICO 12 MESES COMPLETOS)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Historical monthly units | A | 2247 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | DHW useful energy (january) | A | 2248 | X |  | 0.1 | - |
|  | DHW useful energy (february) | A | 2249 | X |  | 0.1 | - |
|  | DHW useful energy (march) | A | 2250 | X |  | 0.1 | - |
|  | DHW useful energy (april) | A | 2251 | X |  | 0.1 | - |
|  | DHW useful energy (may) | A | 2252 | X |  | 0.1 | - |
|  | DHW useful energy (june) | A | 2253 | X |  | 0.1 | - |
|  | DHW useful energy (july) | A | 2254 | X |  | 0.1 | - |
|  | DHW useful energy (august) | A | 2255 | X |  | 0.1 | - |
|  | DHW useful energy (september) | A | 2256 | X |  | 0.1 | - |
|  | DHW useful energy (october) | A | 2257 | X |  | 0.1 | - |
|  | DHW useful energy (november) | A | 2258 | X |  | 0.1 | - |
|  | DHW useful energy (december) | A | 2259 | X |  | 0.1 | - |
|  | Heating useful energy (january) | A | 2260 | X |  | 0.1 | - |
|  | Heating useful energy (february) | A | 2261 | X |  | 0.1 | - |
|  | Heating useful energy (march) | A | 2262 | X |  | 0.1 | - |
|  | Heating useful energy (april) | A | 2263 | X |  | 0.1 | - |
|  | Heating useful energy (may) | A | 2264 | X |  | 0.1 | - |
|  | Heating useful energy (june) | A | 2265 | X |  | 0.1 | - |
|  | Heating useful energy (july) | A | 2266 | X |  | 0.1 | - |
|  | Heating useful energy (august) | A | 2267 | X |  | 0.1 | - |
|  | Heating useful energy (september) | A | 2268 | X |  | 0.1 | - |
|  | Heating useful energy (october) | A | 2269 | X |  | 0.1 | - |
|  | Heating useful energy (november) | A | 2270 | X |  | 0.1 | - |
|  | Heating useful energy (december) | A | 2271 | X |  | 0.1 | - |
|  | Pool useful energy (january) | A | 2272 | X |  | 0.1 | - |
|  | Pool useful energy (february) | A | 2273 | X |  | 0.1 | - |
|  | Pool useful energy (march) | A | 2274 | X |  | 0.1 | - |
|  | Pool useful energy (april) | A | 2275 | X |  | 0.1 | - |
|  | Pool useful energy (may) | A | 2276 | X |  | 0.1 | - |
|  | Pool useful energy (june) | A | 2277 | X |  | 0.1 | - |
|  | Pool useful energy (july) | A | 2278 | X |  | 0.1 | - |
|  | Pool useful energy (august) | A | 2279 | X |  | 0.1 | - |
|  | Pool useful energy (september) | A | 2280 | X |  | 0.1 | - |
|  | Pool useful energy (october) | A | 2281 | X |  | 0.1 | - |
|  | Pool useful energy (november) | A | 2282 | X |  | 0.1 | - |
|  | Pool useful energy (december) | A | 2283 | X |  | 0.1 | - |
|  | Active cooling useful energy (january) | A | 2284 | X |  | 0.1 | - |
|  | Active cooling useful energy (february) | A | 2285 | X |  | 0.1 | - |
|  | Active cooling useful energy (march) | A | 2286 | X |  | 0.1 | - |
|  | Active cooling useful energy (april) | A | 2287 | X |  | 0.1 | - |
|  | Active cooling useful energy (may) | A | 2288 | X |  | 0.1 | - |
|  | Active cooling useful energy (june) | A | 2289 | X |  | 0.1 | - |
|  | Active cooling useful energy (july) | A | 2290 | X |  | 0.1 | - |
|  | Active cooling useful energy (august) | A | 2291 | X |  | 0.1 | - |
|  | Active cooling useful energy (september) | A | 2292 | X |  | 0.1 | - |
|  | Active cooling useful energy (october) | A | 2293 | X |  | 0.1 | - |
|  | Active cooling useful energy (november) | A | 2294 | X |  | 0.1 | - |
|  | Active cooling useful energy (december) | A | 2295 | X |  | 0.1 | - |
|  | Passive cooling useful energy (january) | A | 2296 | X |  | 0.1 | - |
|  | Passive cooling useful energy (february) | A | 2297 | X |  | 0.1 | - |
|  | Passive cooling useful energy (march) | A | 2298 | X |  | 0.1 | - |
|  | Passive cooling useful energy (april) | A | 2299 | X |  | 0.1 | - |
|  | Passive cooling useful energy (may) | A | 2300 | X |  | 0.1 | - |
|  | Passive cooling useful energy (june) | A | 2301 | X |  | 0.1 | - |
|  | Passive cooling useful energy (july) | A | 2302 | X |  | 0.1 | - |
|  | Passive cooling useful energy (august) | A | 2303 | X |  | 0.1 | - |
|  | Passive cooling useful energy (septem- ber) | A | 2304 | X |  | 0.1 | - |
|  | Passive cooling useful energy (october) | A | 2305 | X |  | 0.1 | - |
|  | Passive cooling useful energy (novem- ber) | A | 2306 | X |  | 0.1 | - |
|  | Passive cooling useful energy (decem- ber) | A | 2307 | X |  | 0.1 | - |
|  | Energy consumption (january) | A | 2308 | X |  | 0.1 | - |
|  | Energy consumption (february) | A | 2309 | X |  | 0.1 | - |
|  | Energy consumption (march) | A | 2310 | X |  | 0.1 | - |
|  | Energy consumption (april) | A | 2311 | X |  | 0.1 | - |
|  | Energy consumption (may) | A | 2312 | X |  | 0.1 | - |
|  | Energy consumption (june) | A | 2313 | X |  | 0.1 | - |
|  | Energy consumption (july) | A | 2314 | X |  | 0.1 | - |
|  | Energy consumption (august) | A | 2315 | X |  | 0.1 | - |
|  | Energy consumption (september) | A | 2316 | X |  | 0.1 | - |
|  | Energy consumption (october) | A | 2317 | X |  | 0.1 | - |
|  | Energy consumption (november) | A | 2318 | X |  | 0.1 | - |
|  | Energy consumption (december) | A | 2319 | X |  | 0.1 | - |
|  | Surplus energy consumption (january) | A | 2401 | X |  | 0.1 | - |
|  | Surplus energy consumption (february) | A | 2402 | X |  | 0.1 | - |
|  | Surplus energy consumption (march) | A | 2403 | X |  | 0.1 | - |
|  | Surplus energy consumption (april) | A | 2404 | X |  | 0.1 | - |
|  | Surplus energy consumption (may) | A | 2405 | X |  | 0.1 | - |
|  | Surplus energy consumption (june) | A | 2406 | X |  | 0.1 | - |
|  | Surplus energy consumption (july) | A | 2407 | X |  | 0.1 | - |
|  | Surplus energy consumption (august) | A | 2408 | X |  | 0.1 | - |
|  | Surplus energy consumption (sep- tember) | A | 2409 | X |  | 0.1 | - |
|  | Surplus energy consumption (october) | A | 2410 | X |  | 0.1 | - |
|  | Surplus energy consumption (november) | A | 2411 | X |  | 0.1 | - |
|  | Surplus energy consumption (decem- ber) | A | 2412 | X |  | 0.1 | - |
|  | Auxiliary heaters historical monthly units | A | 2425 | X |  | 1 | 10=Wh<br>20=kWh<br>30=MWh |
|  | Pool auxiliary heaters historical meters (january) | A | 2426 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (february) | A | 2427 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (march) | A | 2428 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (april) | A | 2429 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (may) | A | 2430 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (june) | A | 2431 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (july) | A | 2432 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (august) | A | 2433 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (september) | A | 2434 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (october) | A | 2435 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (november) | A | 2436 | X |  | 0.1 | - |
|  | Pool auxiliary heaters historical meters (december) | A | 2437 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (january) | A | 2438 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (february) | A | 2439 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (march) | A | 2440 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (april) | A | 2441 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (may) | A | 2442 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (june) | A | 2443 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (july) | A | 2444 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (august) | A | 2445 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (september) | A | 2446 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (october) | A | 2447 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (november) | A | 2448 | X |  | 0.1 | - |
|  | DHW auxiliary heaters historical meters (december) | A | 2449 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (january) | A | 2450 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (february) | A | 2451 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (march) | A | 2452 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (april) | A | 2453 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (may) | A | 2454 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (june) | A | 2455 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (july) | A | 2456 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (august) | A | 2457 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (september) | A | 2458 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (october) | A | 2459 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (november) | A | 2460 | X |  | 0.1 | - |
|  | Heating auxiliary heaters historical meters (december) | A | 2461 | X |  | 0.1 | - |

## e-MANAGER

### E-MANAGER BALANCE INFORMATION (INFORMACIÓN E-MANAGER BALANCES INS- TANTÁNEOS)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | e-manager units | A | 2501 | X |  | 1 | 10=W<br>20=kW<br>30=MW |
|  | Power consumption from electrical network | A | 2504 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |
|  | Electrical power injected into network | A | 2508 | X |  | W-->1<br>kW --> 0.1<br>MW--> 0.1 | - |

## BUS CONTROL (CONTROL POR BUS)

### DEVICE STATUS (CONTROL ESTADO EQUIPO)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Heat pump status | A | 2700 |  | X | 1 | 1=OFF<br>2=ON<br>3=Emergency |
|  | Operation program | A | 2701 |  | X | 1 | 1= Winter<br>2= Summer<br>3= Mixto |

### SERVICE DEMANDS CONTROL (CONTROL DEMANDAS SERVICIO)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | DHW BUS demand | A | 2705 |  | X | 1 | 0=No setpoint BUS 1= Setpoint/Offset by BUS |
|  | DHW recirculation BUS demand | A | 2706 |  | X | 1 | Pendiente de desarrollar |
|  | Pool BUS demand | A | 2707 |  | X | 1 | 0=No BUS demand<br>1= BUS demand with setpoint by BUS |
|  | Group 1 demand | A | 2708 |  | X | 1 | 0=NoBUS demand<br>1=BUS heating demand with setpoint by BUS<br>2=BUS cooling demand with setpoint by BUS<br>11=BUS heating demand with setpoint from heat pump<br>12=BUS cooling demand with setpoint |
|  | Group 2 demand | A | 2709 |  | X |  |  |
|  | Group 3 demand | A | 2710 |  | X |  |  |
|  | Group 4 demand | A | 2711 |  | X |  |  |
|  | Group 5 demand | A | 2712 |  | X |  |  |
|  | Heating buffer BUS demand | A | 2713 |  | X | 1 | 0=No setpoint BUS 1= Setpoint/Offset by BUS |
|  | Cooling buffer BUS demand | A | 2714 |  | X | 1 | 0=No setpoint BUS 1= Setpoint/Offset by BUS |
|  | HTR BUS demand | A | 2715 |  | X | 1 | 0=No setpoint BUS 1= Setpoint by BUS (offset fijo 3ºC) |

### SETPOINTS CONTROL (CONTROL OBJETIVOS SER- VICIO)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | DHW setpoint | A | 2720 |  | X | 0.1 | [Min=10,0 … Max=82,0] [ºC] |
|  | DHW recirculation setpoint | A | 2721 |  | X | 0.1 | [Min=0,0 … Max=99,9] [ºC] |
|  | Buffer tank heating setpoint | A | 2722 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |
|  | Buffer tank cooling setpoint | A | 2723 |  | X | 0.1 | [Min=T_lim … Max=25,0] [ºC] |
|  | HTR setpoint by BUS | A | 2724 |  | X | 0.1 | [Min=0,0 … Max=82,0] [ºC] |
|  | Offset DHW | A | 2725 |  | X | 0.1 | [Min=2,0 … Max=25,0] [ºC] |
|  | Offset DHE recirculation | A | 2726 |  | X | 0.1 | [Min=0,0 … Max=99,9] [ºC] |
|  | Offset heating buffer tank | A | 2727 |  | X | 0.1 | [Min=2,0 … Max=10,0] [ºC] |
|  | Offset cooling buffer tank | A | 2728 |  | X | 0.1 | [Min=2,0 … Max=10,0] [ºC] |
|  | Offset pool | A | 2729 |  | X | 0.1 | [Min=0,5 … Max=20,0] [ºC] |
|  | Heating group 1 setpoint | A | 2730 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |
|  | Cooling group 1 setpoint | A | 2731 |  | X | 0.1 | [Min=T_lim … Max=25,0] [ºC] |
|  | Heating group 2 setpoint | A | 2732 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |
|  | Cooling group 2 setpoint | A | 2733 |  | X | 0.1 | [Min=T_lim … Max=25,0] [ºC] |
|  | Heating group 3 setpoint | A | 2734 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |
|  | Cooling group 3 setpoint | A | 2735 |  | X | 0.1 | [Min=T_lim … Max=25,0] [ºC] |
|  | Heating group 4 setpoint | A | 2736 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |
|  | Cooling group 4 setpoint | A | 2737 |  | X | 0.1 | [Min=T_lim … Max=25,0] [ºC] |
|  | Heating group 5 setpoint | A | 2738 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |
|  | Cooling group 5 setpoint | A | 2739 |  | X | 0.1 | [Min=T_lim … Max=25,0] [ºC] |
|  | Pool setpoint (delivery temperature/pool) | A | 2740 |  | X | 0.1 | [Min=20,0 … Max=T_lim] [ºC] |

### BUS AMBIENT TERMINALS CONTROL (CONTROL TERMINALES BUS AMBIENTE INTERIORES)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Zone 1 BUS terminal ON/OFF | A | 2750 |  | X | 1 | 0=OFF<br>1=ON |
|  | Zone 2 BUS terminal ON/OFF | A | 2751 |  | X | 1 | 0=OFF<br>1=ON |
|  | Zone 3 BUS terminal ON/OFF | A | 2752 |  | X | 1 | 0=OFF<br>1=ON |
|  | Zone 4 BUS terminal ON/OFF | A | 2753 |  | X | 1 | 0=OFF<br>1=ON |
|  | Zone 5 BUS terminal ON/OFF | A | 2754 |  | X | 1 | 0=OFF<br>1=ON |
|  | Zone 1 ambient temperature setpoint | A | 2755 |  | X | 0.1 | [Min=5,0 … Max=35,0] [ºC] |
|  | Zone 2 ambient temperature setpoint | A | 2756 |  | X | 0.1 | [Min=5,0 … Max=35,0] [ºC] |
|  | Zone 3 ambient temperature setpoint | A | 2757 |  | X | 0.1 | [Min=5,0 … Max=35,0] [ºC] |
|  | Zone 4 ambient temperature setpoint | A | 2758 |  | X | 0.1 | [Min=5,0 … Max=35,0] [ºC] |
|  | Zone 5 ambient temperature setpoint | A | 2759 |  | X | 0.1 | [Min=5,0 … Max=35,0] [ºC] |

### COMPRESSOR SPEED (CONTROL VELOCIDAD COMPRESOR)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Maximun reference of compresor (%) | A | 2765 |  | X | 0.1 | 0-100,0 [%] |

### SURPLUS CONTROL (CONTROL BALANCE RED)

| Impl | DESCRIPTION | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  | Surplus control enabled by BUS | A | 2775 |  | X | 1 | 0=OFF<br>1=ON |
|  | Maximun consumption enabled by BUS | A | 2776 |  | X | 1 | 0=OFF<br>1=ON |
|  | Surplus regulation setpoint | A | 2777 |  | X | 0.1 | [Min=-99,9 … Max=99,9] [kW] |
|  | Maximun consumption setpoint | A | 2778 |  | X | 0.1 | [Min=-99,9 … Max=99,9] [kW] |

## REVERSE ENGINEERING

| Impl | DESCRIPTION                  | TYPE | ADDRESS | READ | READ/WRITE | GAIN | VALUES |
| --- |------------------------------| --- |---------| --- |------------| --- |--------|
|  | Heating buffer tank DT start | A | 6148 |  | R/W | 0.1 | - |