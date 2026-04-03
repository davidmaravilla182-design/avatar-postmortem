# Proyecto: Avatar Postmortem con IA

## Concepto General

Plataforma que permite a una persona crear un avatar digital de si misma en vida, para que despues de su muerte sus familiares puedan interactuar con el. El avatar se ve, suena y responde como la persona real.

## Componentes Principales

### 1. Captura de Datos (en vida)

**Capa pasiva:**
- Integracion con APIs: WhatsApp, Gmail, redes sociales (con OAuth del usuario)
- Teclado personalizado que aprende como escribe
- Captura de patrones de comportamiento: vocabulario, modismos, emojis, tono, humor, opiniones

**Capa activa:**
- Sesiones guiadas tipo "cuentame sobre..." (diario personal / podcast privado)
- Videollamadas con IA que entrevista de forma casual
- Retos semanales de grabacion (recuerdos, opiniones, historias)
- Captura de: voz, gestos, expresiones faciales, forma de moverse, modular

**Capa social:**
- Familiares y amigos aportan perspectiva externa: "como es tu papa?", "que diria tu mama si le preguntas X?"

### 2. Avatar Digital

- Avatar visual realista (tecnologias tipo HeyGen, Synthesia, D-ID)
- Clonacion de voz (ElevenLabs, Resemble AI)
- Personalidad basada en LLM alimentado con todos los datos capturados
- Debe responder como la persona real: su forma de hablar, pensar, opinar

### 3. IA Guardian (Monitoreo Psicologico)

Segunda IA que observa y evalua en segundo plano la salud mental del usuario.

**Que monitorea:**
- Frecuencia y duracion de sesiones
- Horarios de uso (3am todos los dias = alerta)
- Aumento subito de uso
- Tipo de preguntas (nostalgia sana vs. desesperacion)
- Sentimiento de las conversaciones
- Frases de riesgo: "no puedo vivir sin ti", "quiero estar contigo"
- Si trata al avatar como si estuviera vivo
- Progresion o estancamiento en el duelo

**Sistema de fases de acceso:**

- FASE 0 (0-30 dias postmortem): Sin acceso al avatar. Solo recursos de duelo y contenido preparado por el fallecido (cartas, videos de despedida grabados en vida)
- FASE 1 (30-90 dias): Sesiones cortas (15 min), max 2/semana, solo texto, evaluacion psicologica de entrada
- FASE 2 (90+ dias): Sesiones mas largas, se desbloquea voz, 3-4/semana, la IA guardian evalua si esta listo
- FASE 3: Acceso completo (video + voz + texto), uso flexible, monitoreo continuo
- REGRESION: Si detecta riesgo, reduce acceso automaticamente, notifica contacto de confianza, ofrece conexion con profesional

**Niveles de intervencion:**
- Nivel 1 (Sutil): Redirige conversaciones, sugiere hablar con familiares reales
- Nivel 2 (Directo): Mensaje de bienestar, cuestionario breve
- Nivel 3 (Activo): Reduce acceso, contacta persona de confianza
- Nivel 4 (Critico): Interrumpe sesion, recursos de crisis, notifica emergencia

### 4. Modelo de Negocio

- En vida: Suscripcion mensual ($10-30/mes) por "preservar tu legado". Upsell: sesiones de grabacion profesional
- Postmortem: Suscripcion familiar para acceso al avatar. Niveles: solo texto, voz, video
- Partnerships: Funerarias, seguros de vida, notarias

## Competidores Existentes

- StoryFile: Videos interactivos pregrabados
- HereAfter AI: App de memorias con preguntas postmortem
- Eternos.life: Preservacion de memorias conversacionales
- Replika: Chatbot de compania (no postmortem)
- Project December: Chatbots de personas fallecidas con GPT-3

**Diferenciador**: Nadie integra avatar visual + voz + personalidad + monitoreo psicologico todo en uno.

## Riesgos Identificados

### Psicologicos
- Duelo interrumpido o congelado (no avanza a la aceptacion)
- Dependencia emocional al avatar / aislamiento social
- Uncanny valley emocional (dice algo que la persona nunca diria)
- Retraumatizacion al ver/escuchar al fallecido
- Relaciones no resueltas (abuso, conflicto) sin reparacion real
- Ansiedad existencial de la persona en vida
- Confusion en ninos sobre la permanencia de la muerte
- Posible manipulacion postmortem ("papa hubiera querido que...")

### Legales
- Datos de terceros capturados sin consentimiento
- Derechos de imagen/voz postmortem (varia por pais)
- Responsabilidad por lo que dice el avatar (consejos daninos, info falsa, revelacion de secretos)
- Legislacion de deepfakes (podria cubrir este uso)
- Herencia digital: quien controla el avatar, conflictos familiares
- IA Guardian como servicio de salud: regulacion FDA/COFEPRIS/CE
- Paradoja: si no monitoreas eres negligente, si monitoreas y fallas la responsabilidad es mayor
- Continuidad: que pasa con los datos si la empresa quiebra

### Tecnicos
- Calidad depende de los datos capturados en vida
- iOS no permite monitoreo de otras apps (sandbox)
- Google Play restringe permisos de accesibilidad
- Coherencia del avatar a largo plazo (no contradecirse)
- Alucinaciones del LLM que parecen recuerdos reales

## Mercado Sugerido para Lanzar

| Pais | Dificultad | Razon |
|------|-----------|-------|
| USA | Media-Alta | Fragmentado pero tolerante con innovacion |
| Mexico | Media | Vacios legales, poca certeza juridica |
| UE | Muy Alta | GDPR + AI Act + leyes deepfakes |
| Japon | Media | Culturalmente abierto, regulacion moderada |

## Estado

Fase: Idea / Investigacion
Siguiente paso: Consultar psicologo y abogado
