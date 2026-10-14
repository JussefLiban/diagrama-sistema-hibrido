# Diagrama sistema híbrido de alarma contra incendios / Hybrid fire alarm system diagram

Edificio simplificado: 5 pisos, 2 sótanos, 2 departamentos por piso. Detectores convencionales (12–24 V) con módulo de zona direccionable, relay local para sirena por departamento y sistema de rociadores en el sótano. Abrir `index.html` (botón ES/EN).

Simplified building: 5 floors, 2 basements, 2 apartments per floor. Conventional detectors (12–24 V) on addressable zone modules, locally built relay per apartment siren, and a basement sprinkler system. Open `index.html` (ES/EN toggle).

## Datos confirmados / Confirmed data (14-oct-2026)

Respuesta del equipo de producto de Wizmart sobre el modulo NB773 / Answer from Wizmart's product team about the NB773:

- **ES:** el NB773 puede usarse para reportar alarma en condicion de cortocircuito (un contacto seco cerrado = alarma). No hace falta resistencia de alarma en serie.
- **ES:** la resistencia de fin de linea (EOL) debe ser de **20 k a 51 k ohm**.
- **ES:** el detector de 4 hilos se alimenta aparte (fuente de 12 V). Solo su contacto va al modulo. Confirmaron que funciona ("it will work").
- **ES:** entre el detector y el modulo va un rele de 2 polos para aislar: un polo al modulo, el otro a la sirena del depa.
- **EN:** the NB773 can report an alarm in short-circuit condition (a closed dry contact = alarm). No series alarm resistor is needed.
- **EN:** the end-of-line resistor (EOL) must be **20 k to 51 k ohm**.
- **EN:** the 4-wire detector is powered separately (12 V supply). Only its contact goes to the module. They confirmed it works.
- **EN:** a 2-pole relay sits between the detector and the module for isolation: one pole to the module, the other to the apartment siren.

Esquemas / Schematics: `esquema-relay-nb773-es.svg` y `esquema-relay-nb773-en.svg`.
- **ES:** para el panel Ravel, la version del NB773 es la **-2** (confirmado por Wizmart).
- **EN:** for the Ravel panel, the NB773 version is **-2** (confirmed by Wizmart).
