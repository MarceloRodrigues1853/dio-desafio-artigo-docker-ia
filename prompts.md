# Prompts Utilizados no Desafio DIO: Artigo sobre Docker

Este arquivo documenta todos os prompts usados no ChatGPT e Lexica.art para criar o artigo técnico **"Descomplicando o Docker: Como Contêineres Estão Revolucionando o Deploy"**.

## 1. Geração do Título (ChatGPT)

O primeiro prompt foi usado para gerar ideias de títulos chamativos e focados em SEO.

**Prompt no ChatGPT:**

```
Atue como um especialista em SEO e Copywriting. Estou escrevendo um artigo técnico para iniciantes sobre Docker, focado em como ele facilita o deploy de projetos. Gere 10 títulos chamativos e magnéticos.
```

**Título Escolhido (entre as opções geradas):** `Descomplicando o Docker: Como Contêineres Estão Revolucionando o Deploy`

## 2. Imagem de Capa (Lexica.art)

Foram explorados dois tipos de prompts no Lexica.art para gerar a imagem de capa: um mais abstrato/conceitual e outro mais literal.

**Prompt 1 (Abstrato/Digital):**

```
a blue whale (baleia azul) made of digital code, swimming in a sea of data, neon lights, abstract technology background, high resolution, cyberpunk style, blue and white color scheme
```

**Prompt 2 (Literal/Conceitual):**

```
glowing shipping containers (contêineres de navio) stacked, representing software, server room background, futuristic, data visualization, minimalist
```

## 3. Estrutura e Conteúdo do Artigo (ChatGPT)

O processo de escrita foi dividido em duas etapas: primeiro, a criação da estrutura (outline) e, depois, a geração de conteúdo para cada bloco.

### 3.1. Prompt para Estrutura (Outline)

Este prompt definiu o esqueleto do artigo, garantindo uma progressão lógica para o leitor.

**Prompt no ChatGPT:**

```
Para o artigo com o título "Descomplicando o Docker: Como Contêineres Estão Revolucionando o Deploy", crie uma estrutura em blocos. O artigo deve explicar:
1. O problema clássico do "funciona na minha máquina".
2. O que é Docker e o que são contêineres (usando uma analogia simples).
3. Como o Docker resolve o problema (mencionando DockerFile e Imagem).
4. Um exemplo prático simples de como o Docker é usado em um projeto real.
5. Uma conclusão com um Call to Action.
```

### 3.2. Prompts para Geração de Conteúdo (Bloco a Bloco)

Para cada bloco da estrutura, prompts específicos foram usados para gerar o texto.

**Bloco 1 - Introdução (O Problema):**

```
Escreva a introdução do artigo (cerca de 100 palavras). Comece com o problema clássico que todo desenvolvedor já ouviu: "Mas funciona na minha máquina!". Explique brevemente como a diferença de ambientes (bibliotecas, versões, S.O.) causa esse problema e apresente o Docker como a solução que será discutida.
```

**Bloco 2 - O que é Docker (A Solução):**

```
Agora, escreva a seção "O que é Docker?". Use a analogia de "contêineres de navio" para explicar como o Docker "empacota" uma aplicação com todas as suas dependências (código, bibliotecas, runtime) em uma unidade isolada e portátil. O tom deve ser simples e direto para iniciantes.
```

**Bloco 3 - DockerFile e Imagem (Como Funciona):**

```
Escreva a seção "Como o Docker resolve isso?". Explique de forma simples o que é um `Dockerfile` (a "receita" ou manual de instruções) e o que é uma Imagem (o "pacote" pronto para ser executado). Destaque como isso garante que o ambiente é o mesmo em qualquer lugar (desenvolvimento, teste, produção).
```

**Bloco 4 - Exemplo Prático (Experiência Real):**

```
Vou escrever a seção "Exemplo prático". Eu usei o Docker em um projeto Node.js com um banco de dados PostgreSQL. O maior desafio era garantir que a versão do Node e do Postgres fossem idênticas no meu PC (Windows) e no servidor (Linux).

Ajude-me a transformar esta experiência em um parágrafo simples e didático para o artigo. Mencione como o `docker-compose.yml` foi usado para "subir" os dois serviços (a API Node e o banco de dados) com um único comando, resolvendo o problema de configuração de ambiente de forma elegante.
```

## 4. Call to Action (CTA)

Para finalizar o artigo, foi solicitado um CTA para incentivar a interação do leitor.

**Prompt no ChatGPT:**

```
Escreva 3 opções de "Call to Action" (CTA) para o final do meu artigo sobre Docker. O CTA deve ser amigável e incentivar o leitor a:
1. Ver meus outros projetos com Docker no GitHub.
2. Conectar-se comigo no LinkedIn para trocar ideias sobre tecnologia e DevOps.
```
