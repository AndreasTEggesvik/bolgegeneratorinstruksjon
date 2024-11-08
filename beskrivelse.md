# Trekk på kode for å få motoren til å spinne

## Åpne motorblokken
Bruk ulik kode for å gjøre dette
Bruk blokken ``||basic:pause||`` og blokken ``||servos:Sett Vinkel På Servo||`` og plasser dem i gjenta for alltid blokken.
```blocks
basic.forever(function () {
servos.P0.setAngle(90)
basic.pause(100)
```
