# Radar de Creadores · Creator Radar

**[Español](#español) · [English](#english)**

Métricas y tendencias por nicho para creadoras y creadores de contenido, en español e inglés. Funciona como un artefacto de Claude (claude.ai).
*Niche metrics and trends for content creators, in Spanish and English. Runs as a Claude artifact (claude.ai).*

Creado por / Created by [Alexa Ramírez](https://github.com/alexadarks).

---

## Español

### Qué hace
- **Mi marca:** documento base con preguntas clave: nicho, audiencia, voz, pilares de contenido, referentes y metas.
- **Métricas:**
  - **Google Search Console:** sube un ZIP por canal (blog, Instagram, TikTok, YouTube) y el radar los separa solo.
  - **Meta Business Suite:** sube capturas de Estadísticas y de la tabla Contenido; Claude lee los números.
  - **Cruces:** Google por canal, Google → tus redes, una búsqueda en varios canales, pilares por canal, dónde ganar clics, piezas por formato y por cuenta.
- **Tendencias:**
  - búsquedas en alza frente al período anterior
  - pilares en el tiempo
  - Google Trends (opcional)
  - tendencias del nicho aterrizadas a tu voz, marcando si salen de *tus datos* o de *conocimiento general*
- **Benchmark anónimo por nicho** (opcional): solo se comparten porcentajes.
- **Bilingüe:** botón ES / EN arriba a la derecha. Detecta el idioma de tu navegador.

### Instalación (5 minutos)
Necesitas una cuenta de [claude.ai](https://claude.ai) con artefactos.

1. Descarga `index.html` y `capabilities.json`.
2. En un chat nuevo de Claude, adjunta los dos archivos y pega:
   > Publica `index.html` como un artefacto nuevo llamado "Radar de Creadores", sin modificar el código. Después declara las capacidades exactamente como dice `capabilities.json` (db con esas reglas, user y sample con imágenes).
3. Abre el artefacto, completa **Mi marca** y carga tu primer período en **Métricas**.

### Compartirlo con otras personas
- Invita a cada persona **por correo con nivel Editor**. No uses el enlace público: con ese enlace se puede ver la página, pero no guardar datos.
- Cada persona ve solo sus propios datos. El benchmark del nicho se arma con quienes usan esa misma copia.

### Cómo exportar los datos
- **Search Console:**
  1. Ve a Rendimiento y elige "Últimos 28 días".
  2. Exporta como CSV, un ZIP por canal, usando el **mismo rango** en todos.
  3. Suelta los ZIP o las carpetas en el radar.
- **Meta Business Suite:**
  - En **Estadísticas**, captura las vistas de Rendimiento de Instagram y Facebook y la vista Público (para el total de seguidores).
  - En **Contenido**, captura la tabla con la **fila de títulos de columnas** visible.

### Ejemplos de capturas
Imágenes de referencia con **datos ficticios**:

| Qué subir | Ejemplo |
|---|---|
| **Meta → Estadísticas → Rendimiento** (Instagram y Facebook por separado) | ![Rendimiento](ejemplos/1-meta-rendimiento.png) |
| **Meta → Público → Tendencias**: para el total de seguidores. Ojo: en la tarjeta Seguimientos, el número grande son los seguimientos *nuevos* | ![Público](ejemplos/2-meta-publico-total.png) |
| **Meta → Contenido**: la tabla con la fila de títulos visible. Si no se ve, el radar te pregunta qué es cada columna (una sola vez) | ![Contenido](ejemplos/3-meta-contenido.png) |
| **Search Console**: un ZIP por canal, con el mismo rango | ![Search Console](ejemplos/4-search-console-zip.png) |

### Privacidad
Tus datos se guardan en el espacio privado del artefacto, en tu cuenta; ni la persona dueña de la copia puede verlos. Este repo no contiene datos de nadie.

---

## English

### What it does
- **My brand:** a brand brief with key questions: niche, audience, voice, content pillars, role models and goals.
- **Metrics:**
  - **Google Search Console:** upload one ZIP per channel (blog, Instagram, TikTok, YouTube) and the radar separates them automatically.
  - **Meta Business Suite:** upload screenshots of Insights and of the Content table; Claude reads the numbers.
  - **Cross-checks:** Google by channel, Google → your socials, one search across channels, pillars by channel, where to win clicks, content by format and by account.
- **Trends:**
  - rising searches vs. the previous period
  - pillars over time
  - Google Trends (optional)
  - niche trends grounded in your voice, labeled as coming from *your data* or *general knowledge*
- **Anonymous niche benchmark** (optional): only percentages are shared.
- **Bilingual:** ES / EN toggle in the top right. It detects your browser language.

### Install (5 minutes)
You need a [claude.ai](https://claude.ai) account with artifacts.

1. Download `index.html` and `capabilities.json`.
2. In a new Claude chat, attach both files and paste:
   > Publish `index.html` as a new artifact called "Creator Radar" without changing the code. Then declare its capabilities exactly as in `capabilities.json` (db with those rules, user, and sample with images).
3. Open the artifact, fill in **My brand** and load your first period in **Metrics**.

### Sharing it with others
- Invite each person **by email as an Editor**. Don't use the public link: people who open it can view the page but can't save data.
- Each person only sees their own data. The niche benchmark is built from everyone using that same copy.

### Exporting your data
- **Search Console:**
  1. Go to Performance and choose "Last 28 days".
  2. Export as CSV, one ZIP per channel, using the **same range** for all.
  3. Drop the ZIPs or folders into the radar.
- **Meta Business Suite:**
  - In **Insights**, screenshot the Instagram and Facebook Performance views and the Audience view (for total followers).
  - In **Content**, screenshot the table with the **column header row** visible.

### Screenshot examples
Reference images with **made-up data** (Meta's interface shown in Spanish; in English the cards are Views, Follows, Interactions, Profile visits):

| What to upload | Example |
|---|---|
| **Meta → Insights → Performance** (Instagram and Facebook separately) | ![Performance](ejemplos/1-meta-rendimiento.png) |
| **Meta → Audience → Trends**: for total followers. Note: on the Follows card, the big number is *new* follows | ![Audience](ejemplos/2-meta-publico-total.png) |
| **Meta → Content**: the table with the header row visible. If it isn't visible, the radar asks you what each column is (once) | ![Content](ejemplos/3-meta-contenido.png) |
| **Search Console**: one ZIP per channel, same range | ![Search Console](ejemplos/4-search-console-zip.png) |

### Privacy
Your data is stored in the artifact's private space in your account; not even the copy's owner can see it. This repo contains no one's data.

---

| Archivo / File | Para qué / Purpose |
|---|---|
| `index.html` | La app completa / The full app (HTML + CSS + JS) |
| `capabilities.json` | Capacidades del artefacto / Artifact capabilities |

Licencia / License: MIT
