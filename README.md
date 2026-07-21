# Exemple CC

Repositório de exemplo para demonstração e testes com o **Claude Code** (CC) — a CLI oficial da Anthropic para desenvolvimento assistido por IA.

## Sobre o Projeto

Este repositório foi criado para explorar as capacidades do Claude Code no fluxo de trabalho de desenvolvimento de software, incluindo:

- Geração e edição de código com suporte de IA
- Automação de tarefas via terminal
- Integração com ferramentas de controle de versão (Git/GitHub)
- Uso de MCP servers e extensões do Claude Code

## Pré-requisitos

- [Claude Code](https://claude.ai/code) instalado
- Node.js (versão LTS recomendada)
- Git configurado

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/alespindola-07/Exemple_CC.git
   cd Exemple_CC
   ```

2. Abra o projeto com o Claude Code:
   ```bash
   claude
   ```

3. Interaja com o assistente para executar tarefas de desenvolvimento.

## Recursos do Claude Code

| Recurso | Descrição |
|---|---|
| `/help` | Lista todos os comandos disponíveis |
| `/code-review` | Revisa o código do branch atual |
| `/init` | Inicializa o `CLAUDE.md` com documentação da base de código |
| `/run` | Executa e testa o projeto |
| Hooks | Automatiza comportamentos antes/depois de ações |
| MCP Servers | Integra ferramentas externas (GitHub, Outlook, etc.) |

## Estrutura do Projeto

```
Exemple_CC/
├── README.md
└── .git/
```

## Autor

**Carlos Alexandre** — [@alespindola-07](https://github.com/alespindola-07)

## Licença

Este projeto está sob a licença MIT.
