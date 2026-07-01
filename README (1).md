# 📘 Miniguia de Estudos — Educação Financeira Pessoal para Iniciantes

Projeto criado com o **NotebookLM**, reunindo fontes oficiais e abertas sobre finanças pessoais no Brasil, com o objetivo de praticar curadoria de fontes, engenharia de prompts e organização de conhecimento usando IA como ferramenta de aprendizagem ativa.

---

## 🎯 Contexto e Objetivos

**Tema escolhido:** Educação Financeira Pessoal para Iniciantes — do orçamento doméstico ao primeiro investimento em renda fixa (Tesouro Direto).

**Por que esse tema?** É a base de qualquer decisão financeira futura (investir, tirar um empréstimo, planejar aposentadoria) e existe farto material oficial, gratuito e confiável em português, produzido por órgãos reguladores brasileiros — ideal para testar a IA como ferramenta de estudo com fontes de alta qualidade.

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
1. Quais são os principais módulos/capítulos do documento sobre o Tesouro Direto?
2. Como comparar os três tipos de título do Tesouro Direto em uma tabela, com fonte citada?
3. Quais pontos do tema costumam gerar mais confusão para iniciantes, segundo as fontes?
4. Quais riscos um iniciante deve entender antes de investir no Tesouro Direto?
5. Qual a diferença entre poupança (hábito) e caderneta de poupança (produto)?

### Prompts testados e respostas reais (NotebookLM)

**Prompt 1:**
```
Explique os principais módulos ou capítulos deste documento, um por um, em 2 linhas cada.
```
**Resultado:** resposta completa e bem estruturada, cobrindo 7 blocos do Guia do Investidor — Tesouro Direto: o que é o programa, como investir, os tipos de título, como escolher o título certo (simulador/orientador financeiro), horário de funcionamento, resgate/riscos e custos (taxa de custódia B3 de 0,25%, tabela regressiva de IR). Trouxe até detalhes práticos como o valor mínimo de aplicação (pouco mais de R$ 30) e a janela de negociação (dias úteis, 9h30–18h).
**Avaliação:** ✅ funcionou de primeira, sem precisar reformular — pedir "módulo por módulo" gera resposta organizada e fácil de reaproveitar.

**Prompt 2:**
```
Compare o Tesouro Selic, Prefixado e IPCA+ em uma tabela, citando explicitamente de qual fonte veio cada informação.
```
**Resultado:** o NotebookLM montou uma tabela comparando rentabilidade, perfil ideal, prazo indicado, comportamento em resgate antecipado e disponibilidade de cupons semestrais — e confirmou que toda a informação veio do "Guia_Investidor TD.pdf".
**Avaliação:** ✅ pedir a citação da fonte explicitamente evitou a mistura de PDFs que eu esperava que acontecesse (os dois documentos do Tesouro são parecidos).

**Prompt 3:**
```
Quais pontos deste tema costumam gerar mais confusão para iniciantes? Liste com uma explicação curta para cada.
```
**Resultado:** trouxe 7 pontos de confusão comuns, incluindo alguns que eu nem tinha pensado em perguntar: poupança (hábito) vs. caderneta de poupança (produto), desejos confundidos com necessidades, despesas sazonais tratadas como imprevistos, risco de resgate antecipado no Tesouro Direto, títulos com cupom semestral não serem ideais para reinvestir, a "ilusão da parcela"/crédito fácil mascarando o Custo Efetivo Total, e o fato de que juros compostos (não simples) dominam o mercado real.
**Avaliação:** ✅ foi o prompt mais valioso dos três — gerou conteúdo novo e não óbvio, útil pra complementar o miniguia.

### Dificuldades encontradas (troubleshooting)
- **Nenhuma reformulação foi necessária nos 3 prompts testados** — pedir explicitamente estrutura (módulo a módulo, tabela) e citação de fonte desde o início evitou os problemas que eu esperava (respostas rasas, mistura de fontes).
- **Aprendizado principal:** perguntas abertas tipo "resuma isso" tendem a ser fracas; perguntas que já pedem um formato de saída (tabela, lista numerada, "módulo por módulo") retornam respostas muito mais organizadas e citáveis de primeira.

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

**5. Erros comuns de iniciantes**
- Confundir o hábito de poupar com a caderneta de poupança, que é apenas um produto entre vários disponíveis.
- Tratar desejos como se fossem necessidades, o que leva ao descontrole do orçamento.
- Tratar despesas sazonais previsíveis (IPTU, IPVA, material escolar) como se fossem imprevistos.
- Achar que títulos com cupom semestral são sempre a melhor escolha — na prática, geram mais imposto para quem quer reinvestir.
- Cair na "ilusão da parcela" (propaganda tipo "R$ 3,99 por dia"), que mascara o Custo Efetivo Total (CET) da dívida.
- Achar que os juros do dia a dia são simples — na prática, o mercado usa juros compostos, que crescem de forma exponencial (bom para investimento, perigoso para dívida).

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
| **CET (Custo Efetivo Total)** | O custo real de uma dívida, somando juros e todas as taxas — costuma ficar escondido em anúncios de "parcelas baixinhas" |
| **Juros compostos** | "Juros sobre juros": o valor cresce de forma exponencial ao longo do tempo — ótimo para investir, perigoso para dívidas |
| **Cupom semestral** | Pagamento de juros a cada 6 meses em alguns títulos do Tesouro Direto — bom para renda periódica, mas gera mais imposto para quem quer reinvestir |

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
