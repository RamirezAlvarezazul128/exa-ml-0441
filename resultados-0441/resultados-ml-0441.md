# Reporte de Análisis de Datos - Pandas

`Ramirez Azul Machine Learning pandas, NC 0441`

## 1. DataFrame Convertido
```text
    Aeropuerto  Vuelos_dia  Pasajeros_anio
0         AICM        1200        50000000
1       Cancún         450        25000000
2  Guadalajara         380        15000000
3    Monterrey         320        10000000
4      Tijuana         250         7000000
5       Mérida         180         4000000
```

## 2.1 Primeras Filas (head)
```text
  Aeropuerto  Vuelos_dia  Pasajeros_anio
0       AICM        1200        50000000
1     Cancún         450        25000000
```

## 2.2 Últimas Filas (tail)
```text
  Aeropuerto  Vuelos_dia  Pasajeros_anio
4    Tijuana         250         7000000
5     Mérida         180         4000000
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Aeropuerto          str
Vuelos_dia        int64
Pasajeros_anio    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column          Non-Null Count  Dtype
---  ------          --------------  -----
 0   Aeropuerto      6 non-null      str  
 1   Vuelos_dia      6 non-null      int64
 2   Pasajeros_anio  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Pasajeros_anio'
```text
count    6.000000e+00
mean     1.850000e+07
std      1.709678e+07
min      4.000000e+06
25%      7.750000e+06
50%      1.250000e+07
75%      2.250000e+07
max      5.000000e+07
Name: Pasajeros_anio, dtype: float64
```

## 4. Ordenar Ascendente por Pasajeros_anio
```text
    Aeropuerto  Vuelos_dia  Pasajeros_anio
5       Mérida         180         4000000
4      Tijuana         250         7000000
3    Monterrey         320        10000000
2  Guadalajara         380        15000000
1       Cancún         450        25000000
0         AICM        1200        50000000
```

## 5. Ordenar Descendente por Vuelos_dia
```text
    Aeropuerto  Vuelos_dia  Pasajeros_anio
0         AICM        1200        50000000
1       Cancún         450        25000000
2  Guadalajara         380        15000000
3    Monterrey         320        10000000
4      Tijuana         250         7000000
5       Mérida         180         4000000
```

`Ramirez Azul Machine Learning pandas, NC 0441`