Judul: thermometer

Deklarasi:
1. fahrenheit to celcius = (N - 32) * (5/9)
2. kelvin to celcius = (N - 273.15)
3. celcius to celcius = N

INPUT: typeTemperatur = celcius = N
OUTPUT: typeTemperatur

START

IF  type is `(typeTemperatur == fahrenheit)` {
    (N - 32) * (5/9) = N
} ELSE IF `(kelvin == typeTemperatur)` {
    (N - 273.15) = N
} ELSE{
    `(typeTemperatur)` = N
}

DISPLAY
    `(typeTemperatur)`

END
