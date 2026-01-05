# 📜 Comandos disponibles solo para 📹 streamer y ⚔️ moderadores.  

### ▶️ `#star`  
- Enciende el bot para que empiece a procesar la información de Kukoro.  

### ℹ️ `#info`  
- Muestra información de la mazmorra:  
  - Jugadores jugando.  
  - Total de enemigos registrados.
  - Información extra de la partida
  
### 📋 `#all`  
- Muestra todos los mensajes de `!getinfo` (agrupados por enemigo).  

### 🔄 `#get`  
- Actualiza el `!getinfo` de todos los jugadores en partida (ideal para cambios de habilidades).  
  - 📝 *Nota:* No incluye jugadores no registrados a tiempo (requiere actualización manual).  
  - 📝 *Nota 2:* Los jugadores que murieron y no se les colocó su #f serán eliminados automáticamente al ejecutar `#get`

- ### `#get @jugadorX @jugadorX2, @jugadorX3`  
  - Actualiza el !getinfo de jugadores especificos  

- ### `#get lobo, limo, etc`  
  - Actualiza el !getinfo de los jugadores que luchan contra dicho enemigo (se pueden usar [abreviaturas:](https://github.com/slvs11/comandos/tree/main?tab=readme-ov-file#%E2%80%8D%EF%B8%8F-lista-completa-de-enemigos-por-categor%C3%ADa-y-abreviaturas) disponibles)  

### ⚔️ `#luchando`, `#siguen`, `continuan`, `viven`  
- Cualquiera de los comandos anteriores funciona para indicar que jugadores continúan en la mazmorra.  
 - `viven @juador1 @jugador4 @jugador15` estos jugadores son los que siguen vivos en la mazmorra el resto  
que no se mencione será eliminado de la información del bot, si borras a alguien que sigue en juego  
basta con mandar `!getinfo @jugador` para volver a meterlo a las listas

### 🆑 `#clear`  
- Elimina toda la información de jugadores regitrada en el bot.

### 🔄 `#rst`  
- Reinicia la mazmorra y limpia la información de jugadores registrada (ideal para no usar el menu de pausa y el botón "reiniciar").  

### 🎯 `#ENEMIGO` (ej. `#lobo`, `#limo`, `#murciélago`, `#sombra`, etc.)  
- Muestra los jugadores que enfrentarán a dicho enemigo (ignora acentos).  

### 👾 `#enemigos` / `#mobs`  
- Agrupa a los jugadores por enemigo sin mostrar su `!getinfo`.   

### 📜 Comandos `#bestia` / `#maldito` / `#humanoide` / `#desconocido`  
- Agrupa enemigos por categoría/especie.  

### 🏃 `#agiles` y 🛡️ `#resistentes`  
- Jugadores que pueden luchar contra enemigos más ágiles o resistentes que ellos.  

### ⚠️ `#riesgo`  
- Muestra jugadores que ponen en riesgo la mazmorra.  

### 🛩️ `#kami`  
- Jugadores que matarán a su enemigo al morir.  

### 📊 `#b agiles` y `#b resistentes`  
- Lista todos los enemigos ágiles/resistentes de Kukoro.  

### 📌 `#b [enemigo]` (ej. `#b lobo`, `#b lizardo`)  
- Muestra estadísticas detalladas del enemigo:  
    - `#b lizardo`  
>🦎 Lizardo Lancero [Bestia] ★ 🛡️6% ➤ 💥24% ➤ ⚡12% ★

### 🎭 Comandos relacionados con roles del juego y jugadores  
- `#roles` muestra todos los roles disponibles que hay en kukoro.
- `#jroles` muestra agrupados a los jugadores que tiene un rol.
- `#NOMBRE_ROL` muestra a los jugadores que tiene el rol especificado, ejemplo:  
    - `paladin` 
> ☀️ 𝐏𝐀𝐋𝐀𝐃Í𝐍 (1) | tobyloopy (15) ✯ Rol contra: 🔮 𝐌𝐀𝐋𝐃𝐈𝐓𝐎

### ⬆️ `#Suben`  
- Muestra los jugadores que subirán de nivel al ganar la mazmorra.

### ✨ Comandos `curan`, `cura` y `curanderos`  
- Comandos para ver si alguien del equipo puede curar a los jugadores

### 🕊️ `#f @jugador`  
- Elimina a un jugador (muerto) de las listas `#info` y `#ENEMIGOS`.  

### 🔚 `#fin`  
- El bot finaliza su chamba. 😆  

### ❓ `#extra`  
- Jugadores sin enemigo asignado (Ya no es necesario, pero lo dejo por si HeyNau actualiza nuevos enemigos).

## 🦹‍♂️ Lista completa de enemigos por categoría y abreviaturas.

### 👑 Jefe
| Emoji | Nombre | Inglés | Abreviaturas         |
|-------|--------|--------|----------------------|
| 👑    | Jefe   | Boss   | -                    |

### 🧑 Humanoides
| Emoji | Nombre   | Inglés     | Abreviaturas         |
|-------|----------|------------|----------------------|
| 🧙    | Humano   | Human      | hum, huma            |
| 🐸    | Goblin   | Goblin     | gob                  |
| 🦁    | Orco     | Orc        | orc                  |
| 🧜    | Naga     | Naga       | naga, nag            |
| 🐗    | Troll    | Troll      | trol                 |
| 👁️    | Cíclope  | Cyclops    | ciclo, cic, cyc      |
| 🏆    | Campeón  | Champion   | camp                 |

### 🐾 Bestias
| Emoji | Nombre     | Inglés   | Abreviaturas         |
|-------|------------|----------|----------------------|
| 🦇    | Murciélago | Bat      | murci, mur           |
| 🐉    | Dragón     | Dragon   | drag, dra            |
| 🦎    | Lizardo    | Lizard   | liz, liza            |
| 🐮    | Minotauro  | Minotaur | mino, min            |
| 🦠    | Limo       | Slime    | lim                  |
| 🕷️    | Araña      | Spider   | ara, aña             |
| 🐺    | Lobo       | Wolf     | lob                  |

### 👻 Malditos
| Emoji | Nombre    | Inglés     | Abreviaturas         |
|-------|-----------|------------|----------------------|
| 🗿    | Gárgola   | Gargoyle   | garg, gar            |
| 😈    | Diablillo | Imp        | diab, dia            |
| 👹    | Oni       | Oni        | oni                  |
| 👻    | Sombra    | Shadow     | som                  |
| 💀    | Esqueleto | Skeleton   | esq, esque           |
| 🧟    | Zombi     | Zombie     | zomb, zombie         |

### ❓ Desconocidos
| Emoji | Nombre | Inglés | Abreviaturas |
|-------|--------|--------|--------------|
| 😼    | Momba  | Momba  | momb         |

📌 **Uso:**  
Puedes usar el nombres (ESP / ING) o cualquiera de las abreviaturas con los comandos disponibles.  

## ⭐ Añade al bot a tu mazmorra
- Usa `#vs` para invocar al bot en tu partida. Esto ejecuta automáticamente `!kukoro` y `!getinfo`.
>- ⚠️ *Verifica en modo entrenamiento que el bot esté sincronizado con su cuenta de Twitch.  
Siempre agrégalo al final, cuando ya nadie se une; los espectadores tienen prioridad sobre el bot.*
### Comando de *focus*:
- `v focus ENEMIGO`  
- `v !focus ENEMIGO`  
- `@vegastar14 focus ENEMIGO`  
(Puedes usar nombre, sin acento, o [abreviaturas:](https://github.com/slvs11/comandos/tree/main?tab=readme-ov-file#%E2%80%8D%EF%B8%8F-lista-completa-de-enemigos-por-categor%C3%ADa-y-abreviaturas) ej. `mino`, `cyc`, `som`)

## ℹ️ Comandos de Información  

| Comando   | Descripción                                |  
|-----------|--------------------------------------------|  
| `#v`      | Muestra la versión actual del bot.         |    
| `#c`      | Muestra créditos a bots que inspiraron este bot. |  
| `git`      | Te trae a esta página |  
| `#error`      | Envia un reporte de errores encontrados en el bot |  
| `#sug`/`#sugerencia`      | Envia una sugerencia para implementarla en el bot |  



# [SnoopyLoopy](https://github.com/snoopyloopy11/comandosl/tree/main)

