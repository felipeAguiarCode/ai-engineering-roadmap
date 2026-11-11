# AI Engineering · Roadmap

Um mapa mental interativo para estudar engenharia de IA aplicada: de fundamentos de LLMs até agentes, harnesses e operação em produção.

<p align="center">
  <a href="https://felipeaguiarcode.github.io/ai-engineering-roadmap/">
    <img src="https://img.shields.io/badge/Abrir%20o%20roadmap-GitHub%20Pages-007aff?style=for-the-badge&logo=github&logoColor=white" alt="Abrir o roadmap no GitHub Pages">
  </a>
</p>

**15 macrotópicos · 71 subtópicos · 368 conteúdos de estudo**

---

## O que você encontra

- **Mapa mental navegável** – clique em um macrotópico para expandir os ramos e em um subtópico para abrir os conteúdos.
- **Visualização em lista** – a mesma estrutura em formato de leitura linear.
- **Controle de progresso** – marque cada conteúdo como estudado; o subtópico passa de *A estudar* → *Em estudo* → *Concluído*.
- **Anotações por subtópico** – guarde links, dúvidas e o que aprendeu.
- **Busca e filtros** – encontre termos no mapa todo e filtre por status.
- **Editor Markdown** – altere o conteúdo do mapa direto no navegador, com pré-visualização ao vivo.
- **Exportação e backup** – exporte o HTML completo, o Markdown ou um backup `.json` com progresso e anotações.
- **Tema claro e escuro**.

> O progresso e as anotações ficam salvos no `localStorage` do seu navegador. Nada é enviado para servidor algum. Use **Exportar → Backup completo** para levar seus dados para outro dispositivo.

## Trilha de estudo

| # | Macrotópico | O que cobre |
|---|---|---|
| 1 | **AI Foundations** | Conceitos de IA/ML/DL, como LLMs funcionam (tokens, embeddings, transformers), limitações e pré-requisitos técnicos |
| 2 | **Prompt Engineering** | Princípios, papéis de mensagem, estrutura de prompt, zero/few-shot, design de saída, templates e iteração |
| 3 | **Reasoning Strategies** | Decomposição de tarefas, Chain-of-Thought, modelos de raciocínio, Self-Consistency, Tree of Thoughts e verificação |
| 4 | **Context Engineering** | Composição de contexto, grounding, orçamento de tokens, *context rot*, memória e compactação |
| 5 | **Structured Outputs** | Contratos de saída com JSON Schema, validação (Zod, Pydantic) e tratamento de falhas |
| 6 | **Retrieval-Augmented Generation (RAG)** | Ingestão, chunking, embeddings, busca híbrida, reranking e geração fundamentada |
| 7 | **Tools and Integrations** | Function calling, design de ferramentas, confiabilidade de execução e Model Context Protocol (MCP) |
| 8 | **Workflows and Agents** | Workflows vs. agentes, padrões de workflow, loop ReAct, human-in-the-loop e sistemas multiagentes |
| 9 | **Spec-Driven Development (SDD)** | Descoberta, requisitos e critérios de aceite, artefatos de especificação, rastreabilidade e GitHub Spec Kit |
| 10 | **Harness Engineering** | Runtime do agente, design de ambiente e repositório, gestão de estado, quality gates e recuperação |
| 11 | **Evaluation and Experimentation** | Critérios de sucesso, datasets, LLM-as-a-Judge, avaliação por tipo de sistema e regressão |
| 12 | **Safety, Security and Governance** | Guardrails, prompt injection, permissões, privacidade e governança |
| 13 | **Model Selection and Adaptation** | Escolha de modelos, prompting vs. RAG vs. fine-tuning, SFT, LoRA/QLoRA e inferência local |
| 14 | **Multimodal AI** | Visão e documentos, fala e áudio, geração de imagem e vídeo |
| 15 | **AI Application Engineering and LLMOps** | Arquitetura de aplicações, UX e confiabilidade, observabilidade, deploy e operação |

A ordem sugerida segue a progressão **fundamentos → prompting → contexto → integração → agentes → produção**. Avaliação e segurança devem acompanhar o desenvolvimento desde o início; fine-tuning, multiagentes e multimodalidade podem ser aprofundados conforme o seu objetivo.

## Atalhos

| Tecla | Ação |
|---|---|
| `/` | Focar a busca |
| `M` | Abrir/fechar o menu de tópicos |
| `Esc` | Fechar o painel do subtópico |

## Rodando localmente

O projeto é um único arquivo HTML, sem dependências nem etapa de build:

```bash
git clone https://github.com/felipeAguiarCode/ai-engineering-roadmap.git
cd ai-engineering-roadmap
# abra o index.html no navegador, ou sirva a pasta:
npx serve .
```

## Editando o conteúdo

Clique em **Editar** no topo da página. O mapa usa um Markdown simples:

```markdown
# Macrotópico

## Subtópico

- Conteúdo de estudo
- Outro conteúdo
```

O progresso é preservado nos conteúdos que mantiverem o mesmo nome. Para publicar uma nova versão, use **Exportar → HTML completo** e substitua o `index.html` deste repositório.
