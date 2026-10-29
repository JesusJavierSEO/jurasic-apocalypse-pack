# 🦖 Jurassic Armagedon

Servidor de Minecraft 1.20.1 con mods. Está apagado casi siempre para ahorrar luz: **lo enciendes tú desde Discord** y se apaga solo cuando nadie juega.

**Dirección del servidor:** `mc.cenoteshomun.com`

---

## Cómo empezar a jugar

### 1. Instala el pack de mods (solo la primera vez)

Elige **una** de las dos opciones:

#### Opción A: tengo la app de CurseForge

1. Descarga el pack: **[jurasic-apocalypse.zip](https://github.com/JesusJavierSEO/jurasic-apocalypse-pack/releases/latest/download/jurasic-apocalypse.zip)**. No lo descomprimas.
2. En CurseForge, arriba a la derecha: **Crear perfil personalizado** → **Importar** → elige el zip.
3. Espera a que baje los mods. Son unos 180, la primera vez tarda.
4. En el perfil → ⋯ → **Configuración del perfil**: dale al menos **8 GB** de memoria.

#### Opción B: no tengo CurseForge (solo Windows)

1. Instala **[Forge para Minecraft 1.20.1](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html)** (versión 47.4.10): botón *Installer* → «Install client».
2. Descarga el actualizador: **[actualizar-mods.bat](https://github.com/JesusJavierSEO/jurasic-apocalypse-pack/releases/latest/download/actualizar-mods.bat)**. Guárdalo donde quieras, lo usarás más veces.
3. Ábrelo con doble clic. La primera vez te pide la carpeta del juego: `.minecraft` o la carpeta de tu instancia.
4. Te dice qué mods te faltan, los descarga, y aparta los que sobran en una carpeta `mods-apartados`.
5. En tu launcher, dale al perfil de Forge al menos **8 GB** de memoria.

> Si Windows avisa de «archivo poco común»: *Más información* → *Ejecutar de todas formas*.

### 2. Enciende el servidor desde Discord

Escribe **`/encender`** en el Discord. El bot va avisando y en unos **3 minutos** dice **«✅ ¡Listo!»**.

### 3. Entra

Minecraft → **Multijugador** → **Añadir servidor** → `mc.cenoteshomun.com`

---

## Comandos del bot

| Comando | Qué hace |
|---|---|
| `/encender` | Enciende el servidor. Si ya estaba encendido, te dice quién está jugando. |
| `/estado` | 🟢 encendido · 🟡 arrancando · 🔴 apagado, y quién juega. |
| `/apagar` | Apaga el servidor cuando terminéis. Solo funciona si no queda nadie dentro. |
| `/modpack` | Enlaces del pack y qué cambió en la última versión. |

---

## Lo que conviene saber

- ⏲️ **Se apaga solo.** Si pasa 15 minutos sin nadie, guarda el mundo y se apaga. Para volver, otro `/encender`.
- 🛑 **No se puede apagar con gente dentro.** `/apagar` se niega y dice quién sigue jugando.
- 🔄 **Si al entrar sale «mismatched mod list» o «mods incompatibles»**, te falta la última versión del pack:
  - con CurseForge, descarga e importa el zip nuevo (mismo enlace de arriba) y borra el perfil viejo;
  - sin CurseForge, vuelve a abrir `actualizar-mods.bat`.
- 📵 **Si `/encender` dice «el PC no respondió»** o el bot no contesta, avisa al admin.

¿Algo falla la primera vez? Manda una captura del error por Discord. Casi siempre es el pack desactualizado o poca memoria asignada.

---

<sub>Las versiones del pack están en [Releases](https://github.com/JesusJavierSEO/jurasic-apocalypse-pack/releases). Los mods se descargan desde CurseForge; aquí solo se guarda la lista de mods y las configuraciones.</sub>
