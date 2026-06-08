# Revisión de combate — Daño, PG, armas, armaduras, munición y NPC (v0.4)

> [!goal] Objetivos v0.4
> 
> - Mantener **Daño = dado del atributo + bono del arma**.
>     
> - Que el **arma importe** (bonos altos + calidad).
>     
> - Subir PG para compensar mayor letalidad.
>     
> - Simplificar: **cada arma lista sus cualidades** (sin grupos).
>     

---

## 1) Daño (sin cambios)

**Daño = (Dado del atributo del arma) + (Bono total del arma)**

### Dado por atributo

- 1 → D6
    
- 2 → D8
    
- 3 → D10
    
- 4 → D12
    
- 5 → D20
    

### Bono total del arma

**Bono total = Bono base del arma + Modificador de calidad**

---

## 2) Calidad del arma

|Calidad|Modificador al bono del arma|
|---|---|
|Mala / Improvisada|−4|
|Normal|+0|
|Buena|+2|
|Excelente|+5|
|Maestra (herreros reputados)|+10|

---

## 3) Cualidades (tabla)

| Cualidad            | Regla (resumen)                                                                                                                                                   | Notas                                                                                 |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Parada**          | Si te defiendes **parando** (AGI + arma/escudo), **+1** al Valor de defensa.                                                                                      | Solo cuando eliges **parar** (no al esquivar).                                        |
| **Versátil**        | Sin penalizador narrativo por espacios estrechos (bancos, pasillos, puertas).                                                                                     | Evita desventajas situacionales; no añade daño.                                       |
| **Cortante**        | Si impactas y el **daño final** (tras armadura) es **10+**, aplicas **Sangrado 2** por **2 turnos**.                                                              | Detener sangrado: **acción normal** (AGI + Medicina) dificultad **6–7**.              |
| **Brutal**          | Si **Impacto − Defensa ≥ 5**, añades **+2 daño**.                                                                                                                 | Premia “ganar bien” el intercambio sin pasos extra.                                   |
| **Aturdidora**      | Si el **daño final** (tras armadura) es **12+**, el objetivo queda **Desorientado**: **−2 a todas sus tiradas** hasta el final de su siguiente turno.             | No acumulable.                                                                        |
| **Rompedora**       | Al impactar, reduces la **Reducción** de armadura del objetivo en **1** (mín 0) **hasta el final del combate**.                                                   | Acumulable. Reparar la armadura requiere tiempo fuera de combate.                     |
| **Ligera**          | Si este turno gastaste acción normal en **movimiento extendido**, aún puedes atacar con **−2 a Impacto**.                                                         | Si usas **Ligera** en un turno no puedes usar **Doble ataque** (salvo talento/poder). |
| **Oculta**          | **+2** a tiradas para ocultar/colar el arma en registros o cacheos.                                                                                               |                                                                                       |
| **Alcance**         | Puedes atacar a **2 casillas** (cuadrícula).                                                                                                                      |                                                                                       |
| **Punta defensiva** | Si un enemigo **entra en tu alcance**, gastas **1 reacción** para atacarle con **−2 a Impacto**.                                                                  | “Entra” = se aproxima hasta 1 casilla o cruza tu zona.                                |
| **Dos manos**       | Se necesitan las dos manos para blandir el arma.                                                                                                                  | Normalmente impide usar escudo.                                                       |
| **Precisa**         | **+1 a Impacto** con esta arma.                                                                                                                                   |                                                                                       |
| **Perforante**      | Ignora **2** puntos de Reducción de armadura.                                                                                                                     | Antes de aplicar reducción.                                                           |
| **Distancia**       | Permite atacar a distancia (alcance práctico definido por el arma).                                                                                               | Usa **Proyectiles**.                                                                  |
| **Munición**        | Gestión simple de flechas/virolas si la escena lo exige.                                                                                                          | El Master decide cuándo importa.                                                      |
| **Recarga**         | Necesitas recargar tras disparar: en **ballesta** es **acción normal**.                                                                                           | Arcos normalmente no requieren recarga aparte.                                        |
| **Doble ataque**    | En tu **acción normal** haces **2 ataques**. El **2º** tiene **−2 a Impacto**.                                                                                    | Si usas **Doble ataque** en un turno no puedes usar **Ligera** (salvo talento/poder). |
| **No letal**        | Si alguien llega a **Caído** por daño **No letal**, queda inconsciente y **no hace tiradas de salvación**.                                                        | Útil para capturas.                                                                   |
| **Maldita**         | Si se recibe el impacto el objetivo recibe un penalizador de -1 a todas sus tiradas durante 2 turnos. Es acumulable. Otro impacto reinicia el contador de turnos. |                                                                                       |

> [!note] Nota sobre Doble ataque y Ligera  
> **Doble ataque** no se puede combinar con **Ligera** (movimiento extendido + atacar) en el mismo turno salvo talento/poder.

---

## 4) Tabla de armas básicas (todas juntas)

> [!note] Convención
> 
> - **Atributo de daño** define el **dado** del daño.
>     
> - **Bono base** define el bono del arma **antes** de calidad.
>     

| Arma                   | Tipo        | Atributo de daño | Bono base | Cualidades                                   |
| ---------------------- | ----------- | ---------------- | --------- | -------------------------------------------- |
| **Daga**               | Daga        | AGI              | +5        | Ligera, Oculta, Doble ataque                 |
| **Puñal / cuchillo**   | Daga        | AGI              | +4        | Oculta, Doble ataque                         |
| **Garrote pequeño**    | Contundente | CUE              | +5        | No letal                                     |
| **Espada corta**       | Espada      | AGI              | +8        | Parada, Versátil                             |
| **Espada larga**       | Espada      | AGI              | +12       | Parada, Versátil                             |
| **Ropera / estoc**     | Espada      | AGI              | +7        | Parada, Precisa                              |
| **Hacha de mano**      | Hacha       | CUE              | +9        | Cortante, Brutal                             |
| **Hacha de guerra**    | Hacha       | CUE              | +13       | Cortante, Brutal, Dos manos                  |
| **Maza**               | Contundente | CUE              | +9        | Aturdidora, Rompedora                        |
| **Martillo de guerra** | Contundente | CUE              | +14       | Aturdidora, Rompedora, Dos manos             |
| **Lanza**              | Asta        | AGI              | +9        | Alcance, Punta defensiva, Dos manos          |
| **Alabarda**           | Asta        | CUE              | +11       | Alcance, Punta defensiva, Dos manos          |
| **Arco corto**         | Proyectil   | AGI              | +7        | Distancia, Munición                          |
| **Arco largo**         | Proyectil   | AGI              | +8        | Distancia, Munición, Dos manos               |
| **Ballesta**           | Proyectil   | AGI              | +10       | Distancia, Munición, Recarga (acción normal) |

---

## 5) Puntos de golpe (v0.4)

### Fórmula v0.4

**PG en Sano = (CUE × 8) + (Resistencia × 6) + 12**  
**Cada nivel de daño posterior añade: (CUE × 3) + 2**

### Tabla de niveles

| Nivel     | PG acumulados          |
| --------- | ---------------------- |
| Sano      | (CUE×8) + (RES×6) + 12 |
| Lastimado | + (CUE×3) + 2          |
| Herido    | + (CUE×3) + 2          |
| Lesionado | + (CUE×3) + 2          |
| Malherido | + (CUE×3) + 2          |
| Tullido   | + (CUE×3) + 2          |
| Caído     | + (CUE×3) + 2          |

### Ejemplo (Nivel 1 típico)

**CUE 2, RES 1**

- Sano: (16) + (6) + 12 = **34**
    
- Por nivel: (6) + 2 = **8**
    
- Caído: 34 + 6×8 = **82**
    

|Nivel|PG|
|---|---|
|Sano|34|
|Lastimado|42|
|Herido|50|
|Lesionado|58|
|Malherido|66|
|Tullido|74|
|Caído|82|

## Tabla completa de Puntos de Golpe — v0.4

| CUE | RES | Sano | Lastimado | Herido | Lesionado | Malherido | Tullido | Caído |
| --- | --- | ---- | --------- | ------ | --------- | --------- | ------- | ----- |
| 1   | 0   | 20   | 25        | 30     | 35        | 40        | 45      | 50    |
| 1   | 1   | 26   | 31        | 36     | 41        | 46        | 51      | 56    |
| 1   | 2   | 32   | 37        | 42     | 47        | 52        | 57      | 62    |
| 1   | 3   | 38   | 43        | 48     | 53        | 58        | 63      | 68    |
| 1   | 4   | 44   | 49        | 54     | 59        | 64        | 69      | 74    |
| 1   | 5   | 50   | 55        | 60     | 65        | 70        | 75      | 80    |
| 2   | 0   | 28   | 36        | 44     | 52        | 60        | 68      | 76    |
| 2   | 1   | 34   | 42        | 50     | 58        | 66        | 74      | 82    |
| 2   | 2   | 40   | 48        | 56     | 64        | 72        | 80      | 88    |
| 2   | 3   | 46   | 54        | 62     | 70        | 78        | 86      | 94    |
| 2   | 4   | 52   | 60        | 68     | 76        | 84        | 92      | 100   |
| 2   | 5   | 58   | 66        | 74     | 82        | 90        | 98      | 106   |
| 3   | 0   | 36   | 47        | 58     | 69        | 80        | 91      | 102   |
| 3   | 1   | 42   | 53        | 64     | 75        | 86        | 97      | 108   |
| 3   | 2   | 48   | 59        | 70     | 81        | 92        | 103     | 114   |
| 3   | 3   | 54   | 65        | 76     | 87        | 98        | 109     | 120   |
| 3   | 4   | 60   | 71        | 82     | 93        | 104       | 115     | 126   |
| 3   | 5   | 66   | 77        | 88     | 99        | 110       | 121     | 132   |
| 4   | 0   | 44   | 58        | 72     | 86        | 100       | 114     | 128   |
| 4   | 1   | 50   | 64        | 78     | 92        | 106       | 120     | 134   |
| 4   | 2   | 56   | 70        | 84     | 98        | 112       | 126     | 140   |
| 4   | 3   | 62   | 76        | 90     | 104       | 118       | 132     | 146   |
| 4   | 4   | 68   | 82        | 96     | 110       | 124       | 138     | 152   |
| 4   | 5   | 74   | 88        | 102    | 116       | 130       | 144     | 158   |
| 5   | 0   | 52   | 69        | 86     | 103       | 120       | 137     | 154   |
| 5   | 1   | 58   | 75        | 92     | 109       | 126       | 143     | 160   |
| 5   | 2   | 64   | 81        | 98     | 115       | 132       | 149     | 166   |
| 5   | 3   | 70   | 87        | 104    | 121       | 138       | 155     | 172   |
| 5   | 4   | 76   | 93        | 110    | 127       | 144       | 161     | 178   |
| 5   | 5   | 82   | 99        | 116    | 133       | 150       | 167     | 184   |

---

## 6) Armaduras (Reducción de daño)

> [!rule] Regla  
> **Daño recibido = Daño final − Reducción de armadura** (mínimo 0).

|Armadura|Reducción|Penalizador (simple)|Notas|
|---|---|---|---|
|Ropa / sin armadura|0|0|—|
|Acolchada / gambesón|1|0|Buena contra cortes leves.|
|Cuero|2|0|Ligera y común.|
|Cuero tachonado|3|−1 a **Esquiva** (AGI+Atletismo)|Penaliza movilidad.|
|Cota de malla|4|−1 a **Esquiva** y **Sigilo**|Ruidosa.|
|Brigantina / escamas|5|−2 a **Esquiva** y **Sigilo**|Pesada.|
|Placas|6|−2 a **Esquiva**, **Sigilo** y **Movimiento** (−1 casilla)|Muy buena, muy restrictiva.|

> [!note] Interacción con cualidades
> 
> - **Perforante** ignora **2** de Reducción.
>     
> - **Rompedora** reduce la Reducción del objetivo en **1** (mín 0) hasta fin del combate.
>     

---

## 7) Munición (flechas y virotes)

> [!rule] Regla de munición  
> La munición añade un **Bono de munición** al daño y/o un efecto breve.  
> **Bono de munición** se suma al daño como parte del bono total.

|Munición|Compatible|Bono munición|Efecto|Notas|
|---|---|---|---|---|
|Flecha común|Arco corto / largo|+0|—|Estándar.|
|Flecha pesada|Arco largo|+1|—|Opcional: −1 a Impacto si el Master lo ve relevante.|
|Flecha de caza (ancha)|Arco corto / largo|+1|Si el daño final (tras armadura) es **10+**, **Sangrado 2** por 2 turnos|Detener sangrado: acción normal (AGI+Medicina) dif 6–7.|
|Flecha bodkin (punta fina)|Arco corto / largo|+0|**Perforante (2)** en este disparo|Ignora 2 de armadura.|
|Flecha roma|Arco corto / largo|+0|**No letal**|Capturas.|
|Flecha incendiaria|Arco corto / largo|+0|Si impacta: **Arde 2** por 2 turnos|No suele funcionar con lluvia fuerte.|
|Virote común|Ballesta|+0|—|Estándar.|
|Virote pesado|Ballesta|+2|—|Alto daño.|
|Virote bodkin|Ballesta|+1|**Perforante (2)** en este disparo|Excelente contra armadura.|
|Virote barbelado|Ballesta|+1|Si el daño final (tras armadura) es **8+**: **−1 a todas las tiradas** hasta gastar acción normal para extraerlo|No apila: solo cuenta uno.|
|Virote roma|Ballesta|+0|**No letal**|Capturas.|

---

## 8) Tabla rápida de PG (combinaciones típicas)

> [!note] Tabla rápida  
> Valores de **Sano / Herido / Malherido / Caído** para combinaciones comunes.

| CUE | RES | Sano | Herido | Malherido | Caído |
| --- | --- | ---- | ------ | --------- | ----- |
| 1   | 0   | 20   | 30     | 40        | 50    |
| 1   | 1   | 26   | 36     | 46        | 56    |
| 1   | 2   | 32   | 42     | 52        | 62    |
| 2   | 0   | 28   | 44     | 60        | 76    |
| 2   | 1   | 34   | 50     | 66        | 82    |
| 2   | 2   | 40   | 56     | 72        | 88    |
| 3   | 0   | 36   | 58     | 80        | 102   |
| 3   | 1   | 42   | 64     | 86        | 108   |
| 3   | 2   | 48   | 70     | 92        | 114   |

---

## 9) Minifichas sencillas de NPC (v0.4)

> [!note] Cómo leer las tiradas
> 
> - **Impacto** = dado de **AGI** + habilidad (p. ej. Armas de filo).
>     
> - **Daño** = dado del **atributo del arma** + **bono total** (ya definido por arma y calidad).
>     
> - En “equipo” indico armadura típica y arma (con calidad).
>     

---

### 9.1. Lobo normal

**Descripción:** depredador territorial; ataca en manada, busca flancos y derribos.  
**Atributos clave:** CUE 2, AGI 2, INS 3, ESP 1 | **RES 0**  
**PG (niveles):** Sano **28** · Lastimado **36** · Herido **44** · Lesionado **52** · Malherido **60** · Tullido **68** · Caído **76**  
**Armadura:** 0

**Ataques**

- **Mordisco**
    
    - Impacto: **AGI (1D8) + Pelea 1**
        
    - Daño: **CUE (1D8) + 7**
        
    - Regla rápida: si el daño final (tras armadura) es **10+**, el objetivo queda **Derribado** (−2 a Esquiva hasta su próximo turno).
        

**Habilidades destacadas**

- **Alerta 2** (olfato/ruido)
    
- **Supervivencia 2** (rastreo, caza)
    

---

### 9.2. Guardia de la ciudad

**Descripción:** soldado urbano; mantiene línea, intimida y controla accesos.  
**Atributos clave:** CUE 2, AGI 2, INS 2, ESP 2 | **RES 1**  
**Equipo típico:** **Espada larga (Normal)**, **cuero (Red 2)**.  
**PG (niveles):** Sano **34** · Lastimado **42** · Herido **50** · Lesionado **58** · Malherido **66** · Tullido **74** · Caído **82**  
**Armadura:** Cuero (Red 2)

**Ataques**

- **Espada larga (Normal)**
    
    - Impacto: **AGI (1D8) + Armas de filo 1**
        
    - Daño: **AGI (1D8) + 12**
        
    - Cualidades: **Parada**, **Versátil**
        

**Habilidades destacadas**

- **Alerta 1**
    
- **Negociación 1**
    
- **Dominación 1**
    

---

### 9.3. Capitán de la guardia

**Descripción:** veterano; decide rápido, aguanta presión y dirige a otros.  
**Atributos clave:** CUE 3, AGI 3, GRA 2, ESP 3 | **RES 2**  
**Equipo típico:** **Espada larga (Buena)**, **cota de malla (Red 4)**.  
**PG (niveles):** Sano **48** · Lastimado **59** · Herido **70** · Lesionado **81** · Malherido **92** · Tullido **103** · Caído **114**  
**Armadura:** Malla (Red 4)

**Ataques**

- **Espada larga (Buena)**
    
    - Impacto: **AGI (1D10) + Armas de filo 2**
        
    - Daño: **AGI (1D10) + 14**
        
    - Cualidades: **Parada**, **Versátil**
        

**Habilidades destacadas**

- **Liderazgo 2**
    
- **Alerta 2**
    
- **Dominación 2**
    

**Rasgo rápido (opcional)**

- **Orden de hierro (1/combate):** un aliado que le oiga gana **+2 a su próxima tirada de Impacto** este turno.
    

---

### 9.4. Bandido común

**Descripción:** oportunista; evita duelos limpios, busca superioridad numérica.  
**Atributos clave:** CUE 2, AGI 2, INS 2, ESP 1 | **RES 0**  
**Equipo típico:** **Espada corta (Normal)** o **Daga (Normal)**, ropa gruesa o **cuero (Red 2)**.  
**PG (niveles):** Sano **28** · Lastimado **36** · Herido **44** · Lesionado **52** · Malherido **60** · Tullido **68** · Caído **76**  
**Armadura:** 1 (ropa gruesa) o Cuero (Red 2)

**Ataques**

- **Espada corta (Normal)**
    
    - Impacto: **AGI (1D8) + Armas de filo 1**
        
    - Daño: **AGI (1D8) + 8**
        
    - Cualidades: **Parada**, **Versátil**
        
- **Daga (Normal)**
    
    - Impacto: **AGI (1D8) + Armas de filo 1**
        
    - Daño: **AGI (1D8) + 5**
        
    - Cualidades: **Ligera**, **Oculta**, **Doble ataque**
        

**Habilidades destacadas**

- **Sigilo 1**
    
- **Latrocinio 1**
    
- **Engaño 1**
    

---

## 10) Sanity check (rápido)

- **Espada larga (Normal)**: daño medio en AGI 2 ≈ **1D8 (4,5) + 12 = 16,5**.
    
- Objetivo típico **CUE2/RES1**: **Caído 82**.
    
- Resultado: ~**5 impactos limpios** para llevar a Caído (más en mesa por defensa, fallos, armadura, posicionamiento).
    

---