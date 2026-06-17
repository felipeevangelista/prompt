# 🧠 Repositório de Prompts para Pesquisa Acadêmica e Execução de Tarefas

> Biblioteca organizada de prompts para apoiar atividades acadêmicas, produção científica, qualificação de doutorado, revisão de artigos, geração de materiais e execução orientada de tarefas com Inteligência Artificial.

---

## 📌 Objetivo

Este repositório tem como objetivo centralizar, organizar, versionar e manter prompts reutilizáveis voltados à **pesquisa acadêmica**, **produção científica**, **execução de tarefas orientadas por etapas** e **apoio à elaboração de documentos técnicos e acadêmicos**.

A proposta é permitir que os prompts sejam utilizados de forma padronizada, rastreável e evolutiva, facilitando:

* 🔎 pesquisas em bases científicas;
* 📄 elaboração de artigos, relatórios e trabalhos acadêmicos;
* 🎓 apoio à qualificação de doutorado;
* 🧩 revisão sistemática, mapeamento sistemático e sistemas de evidências;
* 🛠️ execução de tarefas com fluxo controlado;
* 🖼️ criação ou ajuste de imagens para perfis acadêmicos e institucionais.

---

## 🗂️ Organização sugerida do repositório

```text
prompts/
├── README.md
├── pesquisa-academica/
│   ├── prompt-pesquisador-geral.md
│   ├── prompt-pesquisa-short-paper.md
│   └── prompt-qualificacao-doutorado.md
├── artigos/
│   ├── prompt-publicacao-artigo.md
│   └── prompt-artigo-academico-fsc.md
├── revisao-evidencias/
│   └── prompt-mapeamento-rsl-dsr-pbl.md
├── imagens/
│   └── prompt-imagem-3x4.md
├── templates/
│   └── template-prompt.md
└── docs/
    ├── guia-manutencao.md
    └── changelog.md
```

---

## 📚 Catálogo de prompts

| Categoria             | Prompt                             | Finalidade                                                                                                                   |
| --------------------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| 🔎 Pesquisa acadêmica | `prompt-pesquisador-geral.md`      | Apoiar pesquisa científica com tema, palavras-chave, string de busca, síntese de artigos e geração de documentos.            |
| 🧪 Short paper        | `prompt-pesquisa-short-paper.md`   | Apoiar pesquisa comparativa, seleção de fontes, síntese crítica, tabela de trabalhos e geração de referências BibTeX.        |
| 🎓 Qualificação       | `prompt-qualificacao-doutorado.md` | Apoiar a construção progressiva de proposta, revisão da literatura, metodologia, estado da arte e estrutura de qualificação. |
| 📄 Publicação         | `prompt-publicacao-artigo.md`      | Verificar viabilidade de submissão de artigo a evento, aderência temática, Qualis e sugestões de melhoria.                   |
| 🧠 Artigo acadêmico   | `prompt-artigo-academico-fsc.md`   | Apoiar a elaboração de artigo curto em formato IEEE, com análise comparativa de arquiteturas ou processadores.               |
| 🧩 Evidências e PBL   | `prompt-mapeamento-rsl-dsr-pbl.md` | Comparar mapeamento sistemático, revisão sistemática e sistema de evidências orientado a DSR.                                |
| 🖼️ Imagem 3x4        | `prompt-imagem-3x4.md`             | Orientar ajustes de imagem 3x4 com etapas de confirmação antes da geração final.                                             |

---

## 🧭 Princípios de criação dos prompts

Cada prompt deve seguir uma estrutura clara, objetiva e reutilizável, contendo:

### 1. 🎯 Papel da IA

Definir o perfil esperado da IA.

### 2. 📌 Objetivo da tarefa

Informar de forma direta o que o prompt deve produzir.

### 3. 🔁 Fluxo obrigatório

Organizar a execução por etapas, evitando respostas prematuras.

### 4. ✅ Critérios de qualidade

* Não inventar referências.
* Diferenciar fatos documentados de inferências.
* Solicitar confirmação antes de avançar para etapas críticas.
* Utilizar linguagem acadêmica, clara e objetiva.
* Justificar limitações de acesso a bases científicas.
* Registrar fontes utilizadas.

### 5. 📦 Entregáveis

Definir os produtos esperados ao final da execução, como resumo, tabela, matriz, artigo, referências, `.docx`, `.pdf`, `.md` ou `.bib`.

---

## 🛠️ Gestão e manutenção dos prompts

A manutenção dos prompts deve considerar clareza, rastreabilidade e evolução incremental.

### 🔖 Convenção de nomes

Utilizar nomes curtos, descritivos e em letras minúsculas:

```text
prompt-pesquisador-geral.md
prompt-publicacao-artigo.md
prompt-qualificacao-doutorado.md
prompt-imagem-3x4.md
```

### 🧾 Cabeçalho recomendado

```md
---
titulo: Prompt de Pesquisador para Trabalho Acadêmico
categoria: pesquisa-academica
versao: 1.0.0
autor: Felipe Evangelista dos Santos
idioma: pt-BR
ultima_atualizacao: AAAA-MM-DD
status: em uso
---
```

### 🧬 Versionamento semântico

| Versão  | Quando usar                                          |
| ------- | ---------------------------------------------------- |
| `1.0.0` | Primeira versão estável do prompt.                   |
| `1.1.0` | Inclusão de nova etapa ou novo entregável.           |
| `1.1.1` | Correção de ortografia, clareza ou pequenos ajustes. |
| `2.0.0` | Mudança estrutural significativa no fluxo do prompt. |

---

## 🔄 Fluxo de atualização recomendado

1. 📝 Identificar necessidade de ajuste.
2. 🌿 Criar uma branch específica.
3. ✏️ Editar o prompt mantendo o objetivo original.
4. ✅ Testar o prompt com um caso real ou simulado.
5. 📌 Registrar alteração no `CHANGELOG.md`.
6. 🔀 Realizar merge após revisão.

Exemplo de branch:

```text
ajuste/prompt-qualificacao-etapa-rsl
```

Exemplo de commit:

```text
docs: ajusta fluxo do prompt de qualificação para etapa de RSL
```

---

## ✅ Checklist de revisão antes de publicar um prompt

* [ ] O objetivo está claro?
* [ ] O papel da IA está bem definido?
* [ ] As entradas obrigatórias foram especificadas?
* [ ] O fluxo está dividido em etapas?
* [ ] Há regras para impedir respostas prematuras?
* [ ] Os entregáveis estão definidos?
* [ ] O formato de saída está indicado?
* [ ] Há orientação para tratamento de incertezas?
* [ ] O prompt evita inventar fontes, dados ou referências?
* [ ] A linguagem está adequada ao público-alvo?

---

## 🧪 Boas práticas para prompts acadêmicos

* 📌 Comece sempre pela definição do tema, objetivo e palavras-chave.
* 🔍 Solicite a criação de string de busca antes da pesquisa.
* ✅ Peça confirmação do usuário antes de executar etapas longas.
* 📚 Priorize bases científicas, normas, guias técnicos e documentos oficiais.
* ⚠️ Registre limitações quando uma base científica não puder ser acessada.
* 🧠 Solicite análise crítica positiva e negativa dos trabalhos recuperados.
* 📊 Use tabelas para comparar artigos, evidências, autores, métodos e resultados.
* 🔗 Mantenha rastreabilidade entre evidência, decisão, requisito e artefato.
* 🧾 Gere referências em formato padronizado, como IEEE, ABNT ou BibTeX.

---

## 🚫 Cuidados importantes

Evite prompts que:

* gerem respostas sem coletar dados mínimos;
* solicitem pesquisa sem delimitação de tema;
* não diferenciem fato, inferência e opinião;
* peçam referências sem validação;
* misturem objetivos acadêmicos, técnicos e administrativos sem separação;
* não definam entregáveis;
* não indiquem formato de saída.

---

## 📈 Critérios de qualidade do repositório

| Critério        | Descrição                                                       |
| --------------- | --------------------------------------------------------------- |
| Clareza         | O usuário entende rapidamente a finalidade do prompt.           |
| Reutilização    | O prompt pode ser aplicado em diferentes temas.                 |
| Controle        | O fluxo impede execução sem informações mínimas.                |
| Rastreabilidade | As decisões ficam associadas a fontes, evidências ou critérios. |
| Manutenção      | O prompt pode ser atualizado sem perda de histórico.            |
| Padronização    | Os arquivos seguem estrutura e nomenclatura semelhantes.        |

---

## 📌 Roadmap sugerido

* [ ] Padronizar todos os prompts em formato `.md`.
* [ ] Criar cabeçalho com metadados em cada arquivo.
* [ ] Separar prompts por categoria.
* [ ] Criar exemplos de uso para cada prompt.
* [ ] Criar `CHANGELOG.md`.
* [ ] Criar checklist de avaliação dos prompts.
* [ ] Criar modelos de saída para `.docx`, `.pdf`, `.bib` e `.md`.

---

## 🤝 Contribuição

Contribuições podem seguir o seguinte padrão:

1. Criar ou editar um prompt em uma branch própria.
2. Explicar no commit qual problema foi resolvido.
3. Validar o prompt com um exemplo de uso.
4. Atualizar o catálogo no `README.md`.
5. Registrar a mudança no `CHANGELOG.md`.

---

## 📄 Licença

Este repositório pode ser utilizado para fins acadêmicos, educacionais e de apoio à pesquisa. Recomenda-se definir uma licença aberta, como MIT, CC BY 4.0 ou outra compatível com o objetivo do projeto.

---

## 👤 Autor

**Felipe Evangelista dos Santos**
Prompts para apoio à pesquisa acadêmica, produção científica e execução orientada de tarefas com Inteligência Artificial.