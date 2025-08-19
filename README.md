# Agents Studio Docs

Documentación oficial de Agents Studio: crea y orquesta agentes de IA (texto y voz) con flujos visuales, knowledge base, Tools y multi‑tenant.

## 🚀 Quickstart

1. Crea una cuenta y accede al Workspace
	- Crea tu cuenta en [app.getsupervisor.ai](https://app.getsupervisor.ai) o únete a un Workspace existente invitado por tu organización.
	- Con esa misma cuenta podrás entrar a Agents Studio en [https://agents.studio.getsupervisor.ai](https://agents.studio.getsupervisor.ai) y seleccionar tu Workspace (Sandbox o Production).

2. Crea tu primer agente
	- Define nombre, avatar y tono. Ajusta el System Prompt e instrucciones específicas.
	- Usa el Playground para validar respuestas antes de publicar.

3. Diseña el flujo de conversación
	- Abre el Editor Visual y arrastra nodos: Start → Message/Decision/Action → End.
	- Valida conexiones y guarda; publica cuando estés listo.

4. Conecta conocimiento y herramientas
	- Vincula tu fuente de documentos y habilita vectorización automática.
	- Activa tools (voz/telefonía, geocoding, escalado a humano, etc.).

5. Itera sobre tu experiencia
	- Revisa conversaciones de prueba y ajusta prompts, Tools y flujos.

![PLACEHOLDER — Recorrido Quickstart en 5 pasos](/images/placeholder-quickstart-5-steps.png)
_Prompt para IA: “Infografía UI de 5 pasos para crear y publicar un agente de IA: login, crear agente, editor de flujos, conectar conocimiento/tools, monitoreo; estilo limpio profesional”_

## ✅ Capacidades actuales

- Gestión de agentes con CRUD, versionado, estados (Inactivo/Entrenamiento/Activo/Archivado) y clonación
- Playground con memoria de conversación y modo debug
- Flujos visuales con nodos (Start, Message, Decision, Action, Phone, Timer, Message Received, Trace, End)
- Integración de conocimiento desde Google Drive con vectorización automática
- Integración de conocimiento desde documentos con vectorización automática
- Catálogo de tools (+10) con activación condicional y estadísticas de uso
- Agentes de voz (canal telefónico) reutilizables y asignables
- Multi-tenant con workspaces y multi-entorno (Sandbox/Producción)
- Inicio de sesión empresarial (SSO)

![PLACEHOLDER — Grid de funcionalidades con iconos](/images/placeholder-features-grid.png)
_Prompt para IA: “Cuadrícula moderna de features de una plataforma de agentes de IA, iconografía minimalista, texto corto por tarjeta, tema neutro”_

## 🔌 Tools e integraciones

- Voice/Telephony Tool para experiencias de voz
- Geocoding Tool para ubicaciones y distancias
- Human Handoff Tool para escalar a un humano
- Knowledge Base connector para indexar documentos (Drive‑like) y búsqueda semántica
- Mensajería (p. ej., WhatsApp, chat web)

![PLACEHOLDER — Diagrama de arquitectura con integraciones](/images/placeholder-architecture.png)
_Prompt para IA: “Diagrama arquitectónico de alto nivel conectando Frontend web, proveedor de identidad (SSO), almacenamiento de datos, canales de mensajería y conector de Knowledge Base; flechas y etiquetas claras, sin marcas”_

## 🧭 Navegación recomendada

- Introducción y valor: `/` (esta portada)
- Empezar en minutos: `/quickstart`
- Markdown, code samples y snippets: `/essentials/*`
- API Reference (OpenAPI): `/api-reference/introduction`

## 🧪 Buenas prácticas

- Mantén el System Prompt claro y versiona cambios frecuentes.
- Activa solo las tools necesarias y configura condiciones de invocación.
- Prueba en Sandbox y usa el Playground antes de publicar en Producción.


## 🛟 Troubleshooting

- No veo mi Workspace: verifica que tengas invitación o solicita acceso al admin de tu organización.
- Google Drive no sincroniza: revisa consentimiento OAuth y vuelve a vincular.
- Flujos no publican: valida conexiones/nodos y errores en tiempo real.
- Tokens expirados: la renovación es automática; verifica conectividad de red.

## 📮 Soporte

Escríbenos a [sistemas@getsupervisor.ai](mailto:sistemas@getsupervisor.ai)

---

## Desarrollo de esta documentación

Para previsualizar localmente con Mintlify:

```bash
npm i -g mint
mint dev
```

Vista local en `http://localhost:3000`.

Publicación: instala la app de GitHub desde el dashboard de Mintlify para despliegue automático al hacer push a la rama por defecto.
