# 🤖 Autonomous Connect 4 Machine

Projecte acadèmic universitari per al disseny i desenvolupament d’una màquina física autònoma capaç de jugar a **4 en ratlla (Connect 4)** contra un jugador humà.

Aquest sistema combinarà:

- Mecànica física
- Control electrònic amb Raspberry Pi
- Intel·ligència artificial (Minimax + Alpha-Beta)
- Recuperació i classificació automàtica de peces
- Preparació automàtica per a noves partides

---

# 🎯 Objectiu del Projecte

Construir una màquina autònoma capaç de:

1. Detectar l’estat del tauler
2. Calcular la millor jugada
3. Executar físicament el moviment
4. Recuperar les peces en acabar la partida
5. Classificar-les mecànicament (sense sensors)
6. Reiniciar-se automàticament

El projecte es troba actualment en **fase conceptual inicial**.

---

# 🏗 Arquitectura General (Conceptual)

## Subsistemes Principals

### 1️⃣ Mecànica
- Tauler vertical 7x6
- Capçal mòbil en eix X
- Sistema de drop de fitxa
- Trapa inferior per buidatge
- Sistema mecànic de classificació de peces (sense sensors)
- Dipòsits verticals d’emmagatzematge

### 2️⃣ Electrònica
- Raspberry Pi (model per definir)
- Motor pas a pas per moviment lateral
- Driver de motor
- Servo per alliberar fitxa
- Endstops per calibratge (homing)
- Font d’alimentació separada per lògica i motors

### 3️⃣ Software
- Motor d’intel·ligència artificial
- Lògica de joc
- Control de moviment
- Sistema de detecció (pendent de definir)

---

# 🧠 Algorisme d’Intel·ligència Artificial

S’utilitza:

- Minimax
- Poda Alpha-Beta
- Heurística amb priorització de columna central
- Bloqueig immediat de victòries rivals

Optimitzat per funcionar en Raspberry Pi.

---
