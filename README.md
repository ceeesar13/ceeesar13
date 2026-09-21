## César Rivas

**AI Engineer en [niawi tech](https://niawi.tech/)** · Colombia · [bycesar.dev](https://bycesar.dev)

No vengo de ingeniería de software. Entré por la puerta de la automatización low-code — n8n, webhooks, pegar sistemas que no se hablaban entre ellos — y la IA me fue empujando hacia abajo en el stack hasta terminar escribiendo agentes, pipelines RAG y frontend. Sigo usando n8n todos los días: no lo veo como un escalón que se deja atrás, sino como la herramienta correcta para buena parte de los problemas reales de una empresa.

Me especializo en **agentes conversacionales**: diseñar la conversación, acotar el alcance, ponerle guardrails de verdad y hacer que el agente se niegue cuando no sabe en lugar de inventar.

## Un ejemplo concreto

Automaticé una de mis propias tareas. Mis reuniones las transcribe Bluedot, la transcripción viaja a un webhook de n8n, un pipeline de prompts y reglas clasifica lo que se dijo, y las tareas se crean solas en el ClickUp donde el equipo lleva los pendientes. Dejé de tomar notas y de repartir tareas a mano.

## Proyectos públicos

| Proyecto | De qué va |
| --- | --- |
| [onboardbot-langchain-agent](https://github.com/ceeesar13/onboardbot-langchain-agent) | Agente RAG que responde sobre la documentación de un repo. Tres guardrails escritos en código imperativo y con tests — anti-injection, anti-alucinación y scope-lock — más citas obligatorias en cada afirmación. Si algo no está documentado, lo dice. |
| [uno-game](https://github.com/ceeesar13/uno-game) | UNO contra bots con personalidad táctica. Vanilla JS, cero dependencias, sin backend. Todo el azar sale de un PRNG sembrado que viaja dentro del estado: misma semilla, misma partida — y hay un test que lo garantiza. |
| [frontpage-race](https://github.com/ceeesar13/frontpage-race) | Tres retos on-chain resueltos con micropagos USDC sobre HTTP 402, incluido un tres en línea contra minimax donde el tablero es el canvas. Node puro, cero dependencias. |
| [llmeme](https://github.com/ceeesar13/llmeme) | Bot que no puede responder texto plano: todo sale en meme. Construido en 60 minutos en un hackathon LatAm. |

## Stack

| Área | Herramientas |
| --- | --- |
| Automatización | n8n, webhooks, APIs (ClickUp, Chatwoot, CRMs) |
| IA | LangChain, RAG, MCP, OpenRouter, Claude |
| Código | TypeScript, Node, Python, React / Next, Supabase |
| Cómo trabajo | guardrails en código y no solo en el prompt, determinismo donde se pueda, y documentar explícitamente lo que el sistema **no** hace |

Buena parte de lo que construyo es interno y vive en repos privados: hubs financieros, dashboards de operación, comparadores de facturas. Lo público es donde pruebo ideas y las dejo documentadas.
