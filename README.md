# Template LaTeX - Pré Projeto TCC (IFPI)

Este repositório contém a estrutura organizada em **LaTeX** para elaboração de pré-projetos de Trabalhos de Conclusão de Curso (TCC), estruturado de acordo com as normas da ABNT e adaptado para o **Instituto Federal do Piauí (IFPI)**.

---

## Estrutura do Projeto

O projeto é organizado de forma modular para facilitar a edição e manutenção:

```text
.
├── main.tex                       # Arquivo principal (compilação)
├── dados.tex                      # Dados do trabalho (autor, título, orientador, data)
├── bib/
│   └── referencias.bib            # Base de dados de referências (BibTeX)
├── images/
│   └── ifpi_logo.jpg              # Logotipo da instituição
└── estrutura/
    ├── 1_pre_textuais/            # Elementos pré-textuais
    │   ├── capa.tex
    │   ├── folha_rosto.tex
    │   ├── folha_aprovacao.tex
    │   ├── lista_ilustracoes.tex
    │   ├── lista_quadros_tabelas.tex
    │   ├── lista_abreviaturas.tex
    │   ├── lista_simbolo.tex
    │   └── sumario.tex
    ├── 2_textuais/                 # Elementos textuais (Corpo do trabalho)
    │   ├── 1-introducao.tex
    │   ├── 2-justificativa.tex
    │   ├── 3-objetivos.tex
    │   ├── 4-referencial_teorico.tex
    │   ├── 5-metodologia.tex
    │   ├── 6-resultados_esperados.tex
    │   ├── 7-orcamento.tex
    │   └── 8-cronograma.tex
    └── 3_pos_textuais/             # Elementos pós-textuais
        ├── referencias.tex
        ├── apendice_A.tex
        ├── apendice_B.tex
        └── anexo.tex
```

---

## Como Usar

### 1. No Overleaf (Recomendado)
1. Baixe o projeto como um arquivo `.zip`.
2. Acesse o [Overleaf](https://www.overleaf.com/).
3. Clique em **New Project** > **Upload Project**.
4. Faça o upload do arquivo `.zip`.
5. Garanta que o compilador esteja definido como **pdfLaTeX** ou **XeLaTeX** no menu de configurações do Overleaf.

### 2. Localmente (VS Code / TeXstudio / TeXmaker)
1. Certifique-se de ter uma distribuição TeX instalada (ex: **TeX Live**, **MikTeX** ou **MacTeX**).
2. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
3. Abra a pasta do projeto no editor de sua preferência.
4. Compile a partir do arquivo principal **`main.tex`**.

---

## Como Editar

1. **Informações Gerais (`dados.tex`):** Altere nome, título, nome do orientador, instituição, campus e ano.
2. **Desenvolvimento do Conteúdo (`estrutura/2_textuais/`):** Adicione ou modifique o texto nas seções correspondentes (Introdução, Metodologia, etc.).
3. **Referências Bibliográficas (`bib/referencias.bib`):** Adicione as citações no formato BibTeX.
4. **Anexos e Apêndices (`estrutura/3_pos_textuais/`):** Adicione materiais complementares conforme necessário.

---

## Requisitos e Pacientes Utilizados
- Distribuição LaTeX atualizada (TeX Live / MikTeX).
- Pacotes padrão ABNT (`abntex2` ou similares).
- Motor de compilação: `pdfLaTeX`.

---

## Licença

Sinta-se à vontade para utilizar e modificar este modelo conforme as necessidades do seu trabalho acadêmico.
