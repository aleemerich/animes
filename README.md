# Acervo de Animes - Base de Conhecimento RAG

Este repositório serve como a memória externa do Alessandro sobre os animes que ele já assistiu.
Foi desenhado para ser legível por humanos e facilmente processado por agentes LLM (Large Language Models).

## Estrutura
- `/content/`: Contém os arquivos `.md` individuais para cada anime.
- `/assets/`: Imagens (posters, cenas marcantes) vinculadas aos animes.
- `template.md`: Estrutura padrão com YAML frontmatter para criação de novos registros.

## Fluxo de Trabalho do Agente
1. O Alessandro conversa com o agente sobre um anime.
2. O agente processa a opinião dele, extrai os critérios de nota e gera os resumos.
3. O agente preenche o modelo e salva o arquivo em `/content/nome-do-anime.md`.