# 📘 Miniguia de Estudos — Educação Financeira Pessoal para Iniciantes

Projeto criado com o **NotebookLM**, reunindo fontes oficiais e abertas sobre finanças pessoais no Brasil, com o objetivo de praticar curadoria de fontes, engenharia de prompts e organização de conhecimento usando IA como ferramenta de aprendizagem ativa.

---

## 🎯 Contexto e Objetivos

**Tema escolhido:** Educação Financeira Pessoal para Iniciantes — do orçamento doméstico ao primeiro investimento em renda fixa (Tesouro Direto).

**Por que esse tema?** É a base de qualquer decisão financeira futura ( investir, tirar um empréstimo, planejar aposentadoria ) e existe farto material oficial, gratuito e confiável em português, produzido por órgãos reguladores brasileiros — ideal para testar a IA como ferramenta de estudo com fontes de alta qualidade.

**Objetivos de estudo:**
- Entender os conceitos centrais de gestão de orçamento pessoal (receitas, despesas, superávit/déficit).
- Compreender por que e como formar uma reserva de emergência.
- Conhecer os fundamentos do Tesouro Direto como primeiro passo fora da poupança.
- Construir um vocabulário técnico básico (glossário) sobre o tema.
- Desenvolver um conjunto de prompts reutilizáveis para revisar esse conteúdo (ou aplicar a outros temas) no futuro.

---

## 📚 Curadoria de Fontes

Fontes abertas selecionadas e carregadas no Caderno do NotebookLM (todas em texto/PDF, de domínio público ou distribuição gratuita):

| # | Fonte | Tipo | Instituição | Link |
|---|-------|------|-------------|------|
| 1 | Caderno de Educação Financeira — Gestão de Finanças Pessoais | PDF | Banco Central do Brasil (BCB) | [PDF oficial](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf) |
| 2 | Guia de Planejamento Financeiro | PDF/Página | Comissão de Valores Mobiliários (CVM) — Portal do Investidor | [investidor.gov.br/guiafinanceiro](https://www.investidor.gov.br/guiafinanceiro) |
| 3 | Guia do Investidor — Tesouro Direto | PDF | Tesouro Nacional (via repositório ENAP) | [PDF](https://repositorio.enap.gov.br/bitstream/1/6248/1/Guia_Investidor%20TD.pdf) |
| 4 | Manual do App do Tesouro Direto | PDF | Tesouro Nacional (Licença Creative Commons) | [PDF oficial](https://www.gov.br/tesouronacional/pt-br/importacao-arquivos/Manual-do-app-do-tesouro-direto.pdf) |

> Critério de seleção: priorizei fontes de **órgãos reguladores oficiais** (BCB, CVM, Tesouro Nacional), por serem gratuitas, sem viés comercial, atualizadas e amplamente citadas por outras publicações educacionais — reduzindo o risco de a IA "alucinar" com base em conteúdo de baixa qualidade.

**Como reproduzir:** baixe os 4 PDFs pelos links acima → crie um Caderno novo no [NotebookLM](https://notebooklm.google.com) → clique em "Adicionar fonte" → faça upload dos arquivos.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Perguntas estratégicas elaboradas
1. Quais são os passos práticos para montar um orçamento pessoal do zero?
2. Qual a diferença entre poupança e reserva de emergência, segundo as fontes?
3. Quais os tipos de título do Tesouro Direto e para qual objetivo cada um serve?
4. Quais riscos um iniciante deve entender antes de investir no Tesouro Direto?
5. Como as fontes definem "educação financeira" e por que ela importa para a economia como um todo?

### Variações de prompt testadas

| Versão do prompt | Resultado obtido | Ajuste feito |
|---|---|---|
| `"Resuma o documento do Banco Central"` | Resposta genérica demais, cobriu só a introdução institucional do BCB | Troquei por um prompt focado em capítulo/competência específica |
| `"Explique os 6 módulos do Caderno de Educação Financeira do BCB, um por um, em 2 linhas cada"` | Resposta estruturada e citável, com referência à fonte correta | ✅ Prompt reutilizável |
| `"Compare o Tesouro Selic, Prefixado e IPCA+ em uma tabela"` | O NotebookLM organizou bem, mas misturou informação das duas fontes do Tesouro sem deixar claro qual PDF originou cada dado | Adicionei a instrução: `"e cite explicitamente de qual fonte veio cada informação"` |
| `"Monte um plano de estudo de 7 dias sobre este tema"` | Resposta útil, mas fora do escopo estrito das fontes (a IA complementou com conhecimento geral) | Reformulei pedindo: `"baseando-se apenas no conteúdo das fontes carregadas"` |

### Dificuldades encontradas (troubleshooting)
- **Respostas genéricas:** prompts muito abertos ("resuma tudo") geram respostas rasas — funciona melhor pedir um recorte específico (um módulo, um capítulo, uma comparação).
- **Mistura de fontes sem atribuição clara:** ao comparar dois PDFs semelhantes (os dois guias do Tesouro Direto), é preciso pedir explicitamente a citação da fonte, senão a IA generaliza.
- **Tendência a complementar com conhecimento externo:** em perguntas mais abertas, o modelo às vezes extrapola além do que está nas fontes — reforçar "apenas com base nas fontes" resolve.

> *Preencha esta seção com suas próprias capturas de tela e respostas reais obtidas no NotebookLM — isso é o que dá autenticidade e "maturidade técnica" ao repositório.*

---

## 📖 Miniguia de Estudo (Entrega Final)

### Resumos estruturados

**1. Orçamento pessoal**
Consiste em comparar receitas e despesas para saber se sobra ou falta dinheiro no fim do mês. Quando as receitas superam as despesas, a recomendação das fontes é separar o excedente para poupança antes de gastar o restante — e não esperar o que "sobrar" no fim do mês.

**2. Reserva de emergência**
Valor guardado com alta liquidez (fácil de resgatar) para cobrir imprevistos, evitando recorrer a crédito caro (cartão, cheque especial) em situações inesperadas.

**3. Tesouro Direto — primeiros passos**
Programa do governo federal que permite investir em títulos públicos com valores baixos (a partir de poucos reais), com liquidez e segurança consideradas altas por ser garantido pelo Tesouro Nacional. Os principais títulos são: Selic (pós-fixado, indicado para reserva de emergência), Prefixado (taxa definida na compra) e IPCA+ (protegido da inflação, indicado para objetivos de longo prazo).

**4. Marcação a mercado**
O valor de um título pode oscilar antes do vencimento conforme a taxa de juros muda — mas isso só vira perda real se o investidor resgatar antes do prazo combinado.

### Glossário

| Termo | Definição |
|---|---|
| **Orçamento pessoal** | Registro e planejamento de receitas e despesas de um indivíduo ou família |
| **Superávit** | Quando as receitas são maiores que as despesas |
| **Reserva de emergência** | Dinheiro guardado com liquidez alta para imprevistos |
| **Tesouro Direto** | Programa que permite comprar títulos públicos federais pela internet |
| **Renda fixa** | Investimento cuja regra de rentabilidade é conhecida no momento da aplicação |
| **Liquidez** | Facilidade e rapidez para transformar um investimento em dinheiro disponível |
| **Marcação a mercado** | Atualização diária do preço de um título conforme variação das taxas de juros |
| **IPCA** | Índice oficial de inflação usado como referência em títulos pós-fixados |
| **Selic** | Taxa básica de juros da economia brasileira, definida pelo Banco Central |

### Prompts reutilizáveis (para revisão futura)

```
1. "Liste os conceitos-chave do documento [nome] em formato de glossário, com definição de até 2 linhas cada."

2. "Crie 5 perguntas de revisão estilo quiz sobre [tópico], baseando-se apenas nas fontes carregadas, e depois me dê as respostas."

3. "Compare [conceito A] e [conceito B] em uma tabela, citando explicitamente de qual fonte veio cada informação."

4. "Resuma o capítulo/módulo sobre [tópico] em um parágrafo, mantendo linguagem simples."

5. "Quais pontos deste tema costumam gerar mais confusão para iniciantes, segundo as fontes? Liste com uma explicação curta para cada."
```

---

## 🛠️ Como este repositório foi construído
1. Definição do tema e objetivos de estudo.
2. Curadoria de 4 fontes oficiais abertas (BCB, CVM, Tesouro Nacional).
3. Upload das fontes em um Caderno do NotebookLM.
4. Testes iterativos de prompts, registrando variações e dificuldades.
5. Consolidação dos resumos, glossário e prompts reutilizáveis neste `README.md`.

---

*Projeto desenvolvido para o desafio de projeto da [DIO](https://www.dio.me) — Caderno Temático com NotebookLM.*
