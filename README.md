# Cómo Usar Claude de Verdad
### 18 pasos para aprovechar el 100% de su potencial

> Claude lleva dos años disponible. La mayoría de quienes lo usan a diario todavía están aprovechando el 10% de lo que puede hacer. No porque sea complicado — sino porque nadie les mostró cómo se ve el otro 90%.

---

## Índice

1. [Crea un Proyecto, no un chat](#1--crea-un-proyecto-no-un-chat)
2. [Dile a Claude quién eres](#2--dile-a-claude-quién-eres)
3. [Conviértelo en Instrucciones Personalizadas](#3--conviértelo-en-instrucciones-personalizadas)
4. [Claude no es un buscador](#4--claude-no-es-un-buscador)
5. [Pídele que te haga preguntas primero](#5--pídele-que-te-haga-preguntas-primero)
6. [Clonación de estilo](#6--clonación-de-estilo)
7. [Claude como tu sparring](#7--claude-como-tu-sparring)
8. [Extended Thinking](#8--extended-thinking)
9. [Claude escribe prompts para Claude](#9--claude-escribe-prompts-para-claude)
10. [Especifica la longitud del resultado](#10--especifica-la-longitud-del-resultado)
11. [Elimina el preámbulo](#11--elimina-el-preámbulo)
12. [No te reexpliques en cada conversación](#12--no-te-reexpliques-en-cada-conversación)
13. [Empieza un chat nuevo para un tema nuevo](#13--empieza-un-chat-nuevo-para-un-tema-nuevo)
14. [Entiende cualquier cosa con el método Feynman](#14--entiende-cualquier-cosa-con-el-método-feynman)
15. [Plan de viaje personalizado](#15--plan-de-viaje-personalizado)
16. [Análisis de gastos mensuales](#16--análisis-de-gastos-mensuales)
17. [Compañero de reflexión personal](#17--compañero-de-reflexión-personal)
18. [Stress-test de ideas de negocio](#18--stress-test-de-ideas-de-negocio)

---

## Empieza aquí

### 1 — Crea un Proyecto, no un chat

Cada vez que abres un chat nuevo en Claude, empieza con cero memoria. No sabe tu nombre, tu trabajo, tus metas ni cómo te gusta comunicarte. Pasas los primeros mensajes reexplicándote — o no lo haces, y Claude te da algo genérico que no encaja.

**Los Proyectos lo resuelven.** Un Proyecto es un espacio de trabajo persistente donde Claude mantiene el contexto en cada conversación dentro de él. Lo configuras una vez y cada sesión posterior comienza con Claude ya sabiendo quién eres.

**Cómo hacerlo:**
- Ve a [claude.ai](https://claude.ai)
- Haz clic en **Proyectos** en la barra lateral
- Crea uno nuevo — nómbralo `Trabajo`, `Personal`, o como uses Claude habitualmente
- Todo lo que sigue en esta guía va dentro de ese Proyecto

---

### 2 — Dile a Claude quién eres

Antes de que Claude pueda ayudarte bien, necesita entenderte. La mayoría se salta este paso y luego se pregunta por qué las respuestas se sienten levemente incorrectas.

**Copia esta plantilla, complétala y pégala en tu Proyecto:**

```
Mi nombre es [tu nombre].

Trabajo como [tu rol o profesión].
Mis principales responsabilidades son [2-3 cosas que haces día a día].

Ahora mismo mis mayores metas son [1-3 metas específicas].

Uso Claude principalmente para [lista tus casos de uso — escritura, investigación, análisis, código, etc.].

Mi nivel de conocimiento: [qué dominas, qué estás aprendiendo, qué es nuevo para ti].

Cómo me gusta recibir información: [ej. directo y conciso / detallado con ejemplos / paso a paso / párrafos cortos].

Cosas que no quiero: [ej. no añadas disclaimers, no uses lenguaje corporativo, no repitas lo que acabo de decir, no empieces con "Gran pregunta"].

Temas y áreas que me importan: [tus intereses, industria, nicho].
```

Guarda esto en la **base de conocimiento** de tu Proyecto. Claude lo leerá al inicio de cada conversación.

---

### 3 — Conviértelo en Instrucciones Personalizadas

Pegar tu perfil es un buen comienzo. Las Instrucciones Personalizadas van más lejos: le dicen a Claude no solo quién eres, sino **cómo comportarse contigo por defecto**.

**Después de completar la plantilla del paso 2, pega este prompt en Claude:**

```
Basándote en todo lo que te he contado sobre mí, escríbeme un conjunto de instrucciones
personalizadas para este Proyecto de Claude.

Las instrucciones deben:
- Describir quién soy y qué hago
- Establecer mi estilo y formato de comunicación por defecto
- Decirle a Claude qué nunca hacer al trabajar conmigo
- Definir el tono que quiero en cada respuesta
- Incluir cualquier comportamiento predeterminado que querría en cada sesión

Escríbelas en segunda persona, como si Claude estuviera leyendo reglas sobre cómo ayudarme.
Sé específico. Sin consejos genéricos. Menos de 400 palabras.
```

Toma el resultado y pégalo en las **Instrucciones de tu Proyecto**. Esto se convierte en el modo de operación permanente de Claude para cada conversación.

---

## Claude no es lo que crees

### 4 — Claude no es un buscador

La mayoría usa Claude como usa Google. Esa es la forma de menor valor de usarlo.

Claude no es una herramienta de búsqueda. Es un **compañero de pensamiento**. No solo recupera información — razona, sintetiza, argumenta y construye sobre el contexto. En el momento en que lo tratas como buscador, reduces su utilidad en un 80%.

**Deja de preguntarle qué es algo. Empieza a pedirle que piense contigo.**

| ❌ Evita esto | ✅ Prueba esto |
|---|---|
| `¿Qué es el prompt caching?` | `Estoy construyendo un flujo que llama a Claude 20 veces por sesión. ¿El prompt caching reduciría mis costes dado ese contexto?` |
| `¿Qué es el método Zettelkasten?` | `Quiero organizar mis notas de investigación. Explícame si el método Zettelkasten encajaría con mi flujo de trabajo actual: [descríbelo].` |

---

### 5 — Pídele que te haga preguntas primero

Esta es una de las técnicas más poderosas que casi nadie usa. Antes de que Claude empiece cualquier tarea compleja, dile que recopile información de ti primero.

**Prompt universal:**

```
Antes de empezar, hazme las 5 preguntas más importantes que te ayudarían
a hacer esto bien. Después de que yo responda, entonces comienza.
```

**Para una tarea específica:**

```
Necesito que me ayudes a escribir un email frío a un cliente potencial.
Antes de escribir nada, pregúntame lo que necesitas saber para que esto
sea genuinamente bueno, no genérico.
```

---

## Lo que ni los usuarios habituales saben

### 6 — Clonación de estilo

Cuando Claude escribe con tu voz sin ejemplos, escribe con la suya propia. El resultado es gramaticalmente correcto y completamente incorrecto en tono. Suena a IA porque lo es.

**Cómo clonar tu estilo:**

```
Aquí hay 3 ejemplos de mi escritura:

[pega muestra 1]

[pega muestra 2]

[pega muestra 3]

Analiza mi estilo de escritura en detalle. Fíjate en: longitud de frases,
ritmo, elecciones de vocabulario, cómo abro y cierro párrafos, qué evito,
qué tan formal o informal soy, y cualquier patrón que haga mi escritura
distintiva.

Después de esto, cuando te pida que escribas algo para mí, iguala este
estilo exactamente. No uses tus patrones propios.
```

---

### 7 — Claude como tu sparring

La mayoría pide a Claude que les ayude con ideas. Claude construye sobre lo que dices, lo amplía. Obtienes acuerdo y elaboración. Útil a veces — pero no es así como se pone a prueba una idea.

**Antes de comprometerte con cualquier plan, pídele que lo ataque:**

```
Aquí está mi plan: [describe tu plan]

Tu trabajo es destruirlo. Encuentra cada suposición que estoy haciendo
que podría estar equivocada. Encuentra cada forma en que esto podría fallar.
Argumenta la posición opuesta con toda tu fuerza. No seas amable.
No añadas calificaciones. Solo ataca.

Después de eso, defiende mi posición. Construye el argumento más sólido
posible para que yo tenga razón.

Luego dime lo que realmente piensas.
```

---

### 8 — Extended Thinking

La mayoría de usuarios nunca ha activado esto. **Extended Thinking** es un modo donde Claude razona el problema paso a paso antes de darte una respuesta, en vez de ir directo al resultado.

Para tareas simples no lo necesitas. Para decisiones complejas, análisis profundo, o cualquier pregunta donde quieras que Claude *realmente piense* en vez de reconocer patrones — actívalo.

**Cómo activarlo:** Haz clic en el ícono del cerebro antes de enviar tu mensaje.

**O añade esto al prompt:**

```
Reflexiona sobre esto cuidadosamente antes de responder. Trabaja el problema
paso a paso, muestra tu razonamiento, identifica dónde estás inseguro,
luego dame tu conclusión.
```

---

### 9 — Claude escribe prompts para Claude

Si no sabes cómo hacer un prompt para una tarea específica, **pídele a Claude que escriba el prompt por ti**.

```
Necesito que Claude me ayude a [describe tu tarea real].

Escríbeme el mejor prompt posible para esta tarea. Incluye rol, contexto,
instrucciones de formato y cualquier restricción que mejoraría el resultado.

Luego usa ese prompt inmediatamente.
```

---

## Cómo gastar menos tokens y obtener más

### 10 — Especifica la longitud del resultado

El valor predeterminado de Claude es escribir tanto como considera apropiado — generalmente más de lo que necesitas. Una sola instrucción reduce el uso de tokens en un 40–60% sin perder valor.

```
Responde en máximo 3 frases.
```
```
Dame 5 viñetas. Sin explicaciones. Solo los puntos.
```
```
Escribe esto en menos de 150 palabras.
```

---

### 11 — Elimina el preámbulo

Cada respuesta de Claude por defecto empieza con algo que no pediste: *"Gran pregunta. Déjame desglosarlo."* O una reafirmación completa de lo que dijiste. O un disclaimer. O un resumen final.

**Añade esto a tus Instrucciones Personalizadas:**

```
Nunca empieces respuestas con preámbulo, afirmaciones o reafirmaciones
de mi pregunta. Ve directamente a la respuesta. No añadas un resumen
al final a menos que específicamente te lo pida. Sin disclaimers a
menos que el tema genuinamente los requiera.
```

---

### 12 — No te reexpliques en cada conversación

Si pegas la misma información de contexto en cada chat nuevo, estás desperdiciando tokens en cada sesión. Esto es exactamente para lo que son los Proyectos y las Instrucciones Personalizadas.

**Ponlo una vez. Deja que Claude lo lea automáticamente. Nunca vuelvas a pegar tu contexto.**

Si no usas Proyectos todavía, empieza ahí antes de cualquier otra cosa en esta guía.

---

### 13 — Empieza un chat nuevo para un tema nuevo

Claude lleva el contexto de todo lo dicho antes en una conversación. Cuando cambias de tema dentro de un chat largo, Claude todavía tiene todo el contexto anterior cargado — más tokens usados, procesamiento más lento, y contexto anterior que puede contaminar tu tema nuevo.

**Cuando cambies a algo no relacionado:** abre un chat nuevo dentro de tu Proyecto. Conservas la memoria del Proyecto. Pierdes el equipaje irrelevante.

---

## Prompts listos para usar ahora mismo

### 14 — Entiende cualquier cosa con el método Feynman

Las explicaciones por defecto de Claude son técnicamente correctas y prácticamente inútiles. El método Feynman fuerza la comprensión a través de la simplicidad.

```
Explícame [tema] usando solo analogías y ejemplos cotidianos.
Sin jerga. Asume que no tengo ningún conocimiento previo en este campo.

Después de cada analogía, comprueba si realmente lo he entendido
haciéndome una pregunta. Según mi respuesta, profundiza o ajusta la explicación.

Sigue hasta que pueda explicártelo con mis propias palabras sin usar
ningún término técnico.
```

---

### 15 — Plan de viaje personalizado

La clave es darle información real sobre ti, no solo fechas y ubicaciones.

```
Estoy planeando un viaje a [destino]. Estaré allí [número] días.
Mi presupuesto es aproximadamente [cantidad] por día incluyendo alojamiento.

Así es como viajo en realidad: [describe tu estilo — mañanas lentas o días
llenos, lugares turísticos o locales, museos o comida, activo o relajado, etc.]

Cosas que quiero evitar: [multitudes, trampas turísticas, restaurantes caros,
tiempos de transporte largos, etc.]

Hazme un itinerario día por día que se adapte a esto. Para cada día, incluye
dónde quedarme, qué hacer, dónde comer y cualquier logística que deba saber.
Señala todo lo que requiera reserva anticipada.
```

---

### 16 — Análisis de gastos mensuales

Convierte números brutos en un cuadro claro de a dónde va tu dinero y qué hacer al respecto.

```
Voy a pegarte mis gastos del último mes. Analízalos y dime:

1. En qué categorías estoy gastando más
2. Dónde mi gasto parece inusual comparado con mis metas
3. Qué podría recortar sin afectar significativamente mi vida
4. En qué probablemente estoy gastando de menos que importa
5. Un cambio específico que tendría el mayor impacto financiero

Aquí están mis gastos: [pega tu estado de cuenta o lista de gastos]

Mis metas financieras ahora mismo: [describe qué estás tratando de hacer]
```

---

### 17 — Compañero de reflexión personal

```
Quiero pensar en voz alta sobre algo. Tu trabajo no es darme consejos de inmediato.

Primero, hazme preguntas para entender la situación completamente.
Qué está pasando realmente, cómo me siento al respecto, qué he intentado
ya y qué resultado espero.

Después de que entiendas el panorama completo, refleja lo que estás escuchando —
no solo los hechos sino lo que parece estar debajo de ellos.

Luego, y solo entonces, ofrece tu perspectiva. Sé honesto, no tranquilizador.
Dime lo que realmente piensas, incluyendo lo que quizás no quiero escuchar.

Esto es lo que tengo en mente: [describe lo que quieres pensar]
```

---

### 18 — Stress-test de ideas de negocio

La mayoría de ideas de negocio mueren porque la gente se enamora de ellas antes de probarlas. Claude puede actuar como un primer filtro implacable.

```
Tengo una idea de negocio que quiero someter a prueba antes de invertir
tiempo serio en ella.

Aquí está la idea: [descríbela en detalle — qué es, para quién es,
cómo genera dinero, por qué crees que funciona]

Tu trabajo es encontrar todo lo que está mal con ella. Específicamente:

1. Qué suposiciones estoy haciendo que podrían estar equivocadas
2. Quién ya hace esto y por qué podría ganarme
3. Por qué el cliente objetivo podría no pagar por esto
4. Qué tendría que ser verdad para que esto funcionara, y qué tan probable es eso
5. El único mayor problema con esta idea

Sé específico. Los riesgos genéricos como "el mercado quizás no esté listo"
no son útiles. Dame la versión real de cada problema.

Después de eso, dime cómo tendría que verse la idea para funcionar realmente.
```

---

## El punto real

Claude no es más inteligente que tú. No tiene mejores ideas que tú. Lo que tiene es paciencia infinita, conocimiento amplio y la capacidad de pensar en los problemas desde ángulos que no has considerado.

Las personas que más obtienen de Claude no son las que tienen las mejores preguntas. Son las que lo han **configurado para entenderlas**, que le dan **contexto real**, y que saben usarlo como **compañero** en lugar de dispensador.

La mayoría leerá esto y seguirá abriendo Claude como siempre lo han hecho.

**Configúralo una vez. Cambia cómo trabajas permanentemente.**

---

*Basado en el hilo original de [@AnatoliKopadze](https://x.com/AnatoliKopadze) en X.*
