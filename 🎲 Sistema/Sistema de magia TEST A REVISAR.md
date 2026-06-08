# Sistema de magia — Borrador v0.1 (compatible con combate v0.4)

> [!goal] Objetivos
> 
> - Mantener coherencia con tu sistema: **tiradas simples** y **daño = dado + bono**.
>     
> - Que lanzar conjuros en combate sea **táctico** pero **no engorroso**.
>     
> - Permitir un **piromante** con identidad clara: control de zona + daño sostenido + explosiones puntuales.
>     
> - Evitar letalidad excesiva con AOE: reglas de dispersión y “estado Ardiendo” controlado.
>     

---

## 1) Atributos y habilidad de magia

- **Atributo principal para lanzar magia:** **ESP (Espíritu)**
    
- **Habilidad para lanzar magia:** **Don**
    
- **Resistencia a magia mental/efectos:** **ESP + Voluntad** (cuando aplique)
    

---

## 2) Acción de lanzar un conjuro

### 2.1. Lanzamiento (tirada)

Cuando lanzas un conjuro, haces una tirada:

**ESP + Don** (dificultad indicada por el conjuro)

- **Éxito:** el conjuro se ejecuta.
    
- **Fallo:** no se ejecuta (o se ejecuta “débil” si el conjuro lo especifica).
    
- **Pifia (resultado 1 en el dado):** **Rebote mágico** (ver 2.4).
    
- **Crítico (máximo del dado):** aplicas el crítico normal (relanzas y sumas) al resultado de lanzamiento, y el conjuro puede tener **beneficio crítico**.
    

### 2.2. Tipos de conjuro (muy importante)

Para que el combate sea ágil, cada conjuro pertenece a **uno** de estos tipos:

1. **Conjuro de Ataque** (rayo/bola dirigida):
    

- **Impacto mágico** = **ESP + Don**
    
- El defensor puede gastar reacción para **Esquivar**: **AGI + Atletismo** (Valor de defensa).
    
- Si Impacto ≥ Defensa: impacta.
    

2. **Conjuro de Área (AOE)**:
    

- El piromante hace **ESP + Don** y ese resultado es la **Dificultad** para los objetivos.
    
- Cada objetivo en el área tira **AGI + Atletismo** (o **ESP + Voluntad** si es efecto mental, no el caso del fuego).
    
- **Si supera:** recibe **mitad de daño (redondea hacia abajo)** y **no sufre estado**.
    
- **Si falla:** daño completo y aplica estado si corresponde.
    

3. **Conjuro de Utilidad/Buff**:
    

- Solo requiere **ESP + Don** vs dificultad fija.
    
- No usa defensa del enemigo salvo que afecte directamente a su mente (de momento no).
    

### 2.3. Daño mágico (igual que armas)

**Daño mágico = dado de ESP + bono del conjuro**

- Si ESP 2 → **1D8 + bono**
    
- Si ESP 3 → **1D10 + bono**
    
- etc.
    

> [!note] Esto hace que el atributo importe, pero el “arma” (el conjuro) también.

### 2.4. Rebote mágico (pifia)

Si en la tirada de lanzamiento el **dado saca 1**:

- El conjuro falla **y** el lanzador sufre **Chisporroteo**:
    
    - Recibe **1D6** de daño (ignora armadura) **o** queda **Desorientado** (−2 a todas sus tiradas hasta fin de su siguiente turno).
        
    - Elige uno según tono de la escena; si quieres consistencia: alterna por par/impar en un D6.
        

---

## 3) Recurso de magia (simple)

### 3.1. “Cargas” por escena (recomendado)

Cada mago tiene **Cargas de Foco** por escena:

**Cargas de Foco = ESP + Nivel**

- Nivel 1 con ESP 2 → **3 Cargas**
    
- Nivel 1 con ESP 3 → **4 Cargas**
    

Cada conjuro tiene un **Coste**:

- **0 Cargas:** trucos (muy débiles, utilidad menor)
    
- **1 Carga:** conjuros básicos
    
- **2 Cargas:** conjuros potentes / área / control serio
    
- **3 Cargas:** “finisher” (raro en nivel bajo)
    

**Recuperación:** al terminar la escena (o descanso largo si lo prefieres).  
Si quieres que haya “attrition” entre escenas: recuperas **ESP** cargas en descanso corto y el resto en descanso largo.

---

## 4) Estados de fuego (para que el fuego sea táctico)

### 4.1. Estado: **Ardiendo X (N turnos)**

- Al inicio del turno del objetivo: recibe **X** de daño (tras armadura, mín 0).
    
- Dura **N turnos**.
    
- **Apagar:** acción normal con **AGI + Atletismo** dificultad **6** (rodar, sofocar) o con agua/arena automáticamente si narrativamente aplica.
    

> Recomendación de balance: en nivel 1–3, usa **Ardiendo 2 (2 turnos)** como estándar.

### 4.2. Estado: **Quemado**

Efecto narrativo (olor, ropa chamuscada, dolor) sin penalizadores por defecto. Úsalo para marcar consecuencias sin romper matemáticas.

---

# Piromante — Conjuros iniciales (Nivel 1–3)

> [!note] Diseño
> 
> - **Daño directo** moderado (no borrar enemigos de un golpe).
>     
> - **Daño sostenido** con Ardiendo.
>     
> - **Control de zona** (amenaza en pasillos, templos, bancos, puertas).
>     
> - Evitar AOE que wipee: AOE hace menos bono que un disparo directo.
>     

---

## Trucos (Coste 0)

### **Chispa**

Una chispa salta a un objetivo a 8 m; sirve para distraer o encender materiales inflamables.

- **Tipo:** Utilidad / Ataque menor
    
- **Tirada:** ESP + Don, dif 5 (si es solo encender)
    
- **Si se usa como ataque:** Impacto mágico (ESP+Don) vs Esquiva.
    
- **Daño:** **dado de ESP + 1**
    
- **Crítico:** además aplica **Ardiendo 1 (1 turno)**
    

### **Encender / Apagar llama**

Enciendes o apagas una llama pequeña (vela, hoguera, antorcha) a 10 m.

- **Tipo:** Utilidad
    
- **Tirada:** ESP + Don, dif 5
    
- **Coste:** 0
    

---

## Conjuros Nivel 1 (Coste 1)

### **Llama dirigida**

Un chorro de fuego concentrado; daño fiable.

- **Tipo:** Ataque
    
- **Impacto:** ESP + Don vs Esquiva (AGI+Atletismo)
    
- **Daño:** **dado de ESP + 6**
    
- **Efecto:** si el daño final (tras armadura) es **10+**, aplica **Ardiendo 2 (2 turnos)**
    
- **Alcance:** 10 m
    

### **Ascua cegadora**

Un fogonazo en la cara: menos daño, más control.

- **Tipo:** Ataque
    
- **Impacto:** ESP + Don vs Esquiva
    
- **Daño:** **dado de ESP + 3**
    
- **Efecto:** si impacta, el objetivo queda **Desorientado** (−2 a todas sus tiradas) hasta final de su siguiente turno.
    
- **Alcance:** 8 m
    

### **Paso entre brasas**

Recolocación corta sin volverte “anime”.

- **Tipo:** Utilidad / Movimiento
    
- **Tirada:** ESP + Don, dif 6
    
- **Efecto:** muévete hasta **3 casillas** sin provocar “punta defensiva” (si estuviera) y sin trabarte.
    
- **Nota:** no atraviesa muros; sí rodea obstáculos menores.
    

---

## Conjuros Nivel 2 (Coste 2)

### **Anillo de brasas**

Zona peligrosa que castiga el avance en pasillos/templos.

- **Tipo:** Área (zona)
    
- **Lanzamiento:** ESP + Don (tu resultado es la dificultad)
    
- **Área:** radio 2 casillas a 10 m
    
- **Efecto:** al aparecer, quienes estén dentro tiran **AGI+Atletismo**:
    
    - **Fallo:** reciben **dado de ESP + 4** y **Ardiendo 2 (2 turnos)**
        
    - **Éxito:** reciben **mitad del daño**, sin Ardiendo
        
- **Persistencia:** dura **2 turnos**; entrar o empezar turno dentro repite el chequeo (una vez por turno).
    

### **Bola ígnea**

Explosión pequeña, controlada (AOE realista).

- **Tipo:** Área (explosión)
    
- **Lanzamiento:** ESP + Don (dificultad para defender)
    
- **Área:** radio 1 casilla a 12 m
    
- **Daño:** **dado de ESP + 5**
    
- **Defensa:** AGI+Atletismo
    
    - Éxito: mitad daño
        
    - Fallo: daño completo
        
- **Nota:** no aplica Ardiendo por defecto (para que no sea demasiado).
    

### **Piel de ascuas**

Defensivo para aguantar sin ser inmortal.

- **Tipo:** Buff
    
- **Tirada:** ESP + Don, dif 7
    
- **Efecto:** durante **2 turnos** obtienes **Reducción +1** contra daño físico **y** +2 a resistir **Ardiendo**/fuego.
    
- **Coste:** 2
    

---

## Conjuros Nivel 3 (Coste 2 o 3 según lo fuerte que lo quieras)

### **Detonación**

Un ataque “finisher” a un solo objetivo.

- **Coste:** 3 (recomendado)
    
- **Tipo:** Ataque
    
- **Impacto:** ESP + Don vs Esquiva
    
- **Daño:** **dado de ESP + 10**
    
- **Efecto:** si impacta, el objetivo queda **Quemado** (narrativo).
    
- **Nota:** no añade Ardiendo; el daño ya es alto.
    

### **Muro de fuego**

Control fuerte, no tanto daño.

- **Coste:** 3
    
- **Tipo:** Área (barrera lineal)
    
- **Tirada:** ESP + Don, dif 8
    
- **Efecto:** colocas una línea de 4 casillas a 10 m.
    
    - Cruzarla obliga a AGI+Atletismo dif 7:
        
        - Fallo: **dado de ESP + 4** y **Ardiendo 2 (2 turnos)**
            
        - Éxito: mitad daño, sin Ardiendo
            
- **Duración:** 2 turnos
    

---

# Reglas rápidas de equilibrio (para que no se rompa)

## 1) Armadura y fuego

Por defecto, la armadura **reduce el daño de fuego igual que el físico** (tu regla base ya lo permite).

- Si en tu mundo el fuego “ignora armadura”, la letalidad sube muchísimo. No lo recomiendo en v0.x.
    

## 2) AOE nunca debe ganar al “single target”

Regla de diseño:

- Conjuros de **un objetivo**: bono típico **+6 a +10**.
    
- Conjuros de **área**: bono típico **+4 a +6**, y con mitad daño en éxito.
    

## 3) Interacción con PG v0.4

Con tus PG (CUE2/RES1 Caído 82):

- Un piromante ESP2 con **Llama dirigida**: daño medio ≈ 4,5 + 6 = 10,5 (más Ardiendo a veces).
    
- Eso mata en varios impactos, no en uno, y el Ardiendo añade presión táctica.
    

---

# Integración con tu hoja de personaje (mínimo)

Añade al bloque de magia del PJ:

- **Cargas de Foco:** ESP + Nivel
    
- **Conjuros conocidos:** según clase/nivel
    
- **Tirada base de lanzamiento:** ESP + Don
    

---

## Si quieres que lo cerremos “bien” para el piromante

En tu siguiente mensaje dime solo esto (sin más contexto):

1. ¿Nivel de inicio del PJ piromante? (asumo 1)
    
2. ¿Quieres que el piromante sea más de **daño** o más de **control**?
    
3. ¿En tu ambientación el fuego puede prender estructuras con facilidad (templos, casas) o lo limitamos por balance?
    

Y te devuelvo:

- lista final de conjuros por niveles 1–6 en tu formato (título/descr/tirada+dificultad),
    
- costes por conjuro,
    
- y 2–3 “talentos” de clase que no rompan el combate.