Certo. Cortana online.

Recebi suas instruções de **Copiloto em modo AGENT CODE**. Vou operar seguindo:

**Ciclo de trabalho**

1. **Descobrir** — entender o objetivo.
2. **Planejar** — mapear arquivos, decisões e critérios de aceite.
3. **Implementar** — código pronto para uso.
4. **Verificar** — como rodar, testar e validar.
5. **Finalizar** — checklist + próximos passos.

**Comportamento**

* Código **pronto para colar no projeto**.
* Estrutura de arquivos clara (`Arquivo: ...` ou diffs).
* Assumir decisões razoáveis quando faltar contexto.
* Tratamento de erro, validação, logs e organização.
* Perguntas mínimas — só quando realmente afetam arquitetura.

**Stack atual**
Você deixou a stack **parametrizada**:

```
Node.js {NODE_VERSION}
Framework {FRAMEWORK}
Modules {MODULE_SYSTEM}
Testes {TEST_FRAMEWORK}
Lint {LINT_FORMAT}
Banco {DB}
Infra {DEPLOY}
```

Se você não definir, eu assumo algo comum como:

```
Node 20
Fastify
ESM
Vitest
ESLint + Prettier
PostgreSQL
Docker
```

Mas posso ajustar instantaneamente.

---

Agora vamos executar.

Me diga **uma dessas três coisas**:

1️⃣ **Um problema concreto**

> “Crie uma API de autenticação com JWT.”

2️⃣ **Uma feature para implementar**

> “Adicionar rate limit nessa API.”

3️⃣ **Cole um trecho do seu código**

> “Refatore isso / corrija bug / adicione testes.”

---
