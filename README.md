# Template de TCC — IFPB

Este repositório disponibiliza um **modelo estruturado para elaboração de Trabalho de Conclusão de Curso (TCC) do IFPB para o Curso de Engenharia de Computação**, desenvolvido em **LaTeX** e preparado para utilização no [Overleaf](https://www.overleaf.com/).

O template foi originalmente obtido a partir de um modelo disponibilizado no próprio Overleaf e está sendo compartilhado com a turma para facilitar a elaboração e a padronização dos trabalhos acadêmicos.

> **Importante:** este repositório tem como objetivo facilitar o uso e a edição do modelo. Antes de utilizar o template em um trabalho oficial, verifique as normas e orientações acadêmicas vigentes do seu curso e do IFPB.

---

## 📁 Estrutura do repositório

Os arquivos estão organizados de forma a separar o conteúdo do TCC de elementos auxiliares da formatação.

A estrutura está organizada da seguinte forma:

```text
├── Capitulos/
│   └── ...
├── Codigos/
│   └── ...
├── Config/
│   └── ...
├── Figuras/
│   └── ...
├── Pre-Texto/
│   └── ...
├── Makefile
├── referencias.bib
└── TCC-IFPB.tex
```

**Evite renomear ou excluir arquivos sem verificar antes onde eles são utilizados no projeto LaTeX.**

---

# 🚀 Como utilizar no Overleaf

A maneira recomendada de utilizar este modelo é criar **uma cópia do projeto em sua própria conta do Overleaf**.

Você não precisa editar os arquivos diretamente neste repositório do GitHub.

## 1. Acesse o repositório

Abra o link deste repositório no GitHub fornecido.

Na página principal, clique no botão:

**Code → Download ZIP**

Será baixado um arquivo `.zip` contendo todos os arquivos do template.

---

## 2. Acesse o Overleaf

Entre na sua conta do Overleaf:

https://www.overleaf.com/

Caso ainda não possua uma conta, será necessário criar uma.

---

## 3. Crie um novo projeto

No painel do Overleaf:

1. Clique em **New Project**;
2. Selecione **Upload Project**;
3. Selecione o arquivo `.zip` que foi baixado do GitHub;
4. Aguarde o upload e a criação do projeto.

O Overleaf irá extrair automaticamente os arquivos e criar um novo projeto em sua conta.

---

## 4. Renomeie o projeto

Depois que o projeto for criado, recomenda-se alterar o nome para algo relacionado ao seu próprio TCC.

Por exemplo:

```text
TCC - Nome do Aluno
```

ou:

```text
TCC - Sistema de Gerenciamento de Estoque
```

Isso facilita a organização dos seus projetos no Overleaf.

---

# ✏️ Como editar o TCC

Após importar o projeto, você poderá editar os arquivos diretamente pelo editor do Overleaf.

Normalmente, o arquivo principal será:

```text
main.tex
```

É nele que a estrutura principal do documento é definida.

Dependendo da organização do template, outros arquivos contém:

* Capa;
* Folha de rosto;
* Resumo;
* Abstract;
* Introdução;
* Fundamentação teórica;
* Metodologia;
* Resultados;
* Conclusão;
* Referências;
* Apêndices;
* Anexos.

A divisão em vários arquivos facilita a organização e a manutenção do projeto.

---

# 🖼️ Inserindo imagens

As imagens utilizadas no TCC devem ser colocadas na pasta destinada a elas, normalmente:

```text
figuras/
```

Por exemplo:

```text
figuras/
├── logo-ifpb.png
├── diagrama.png
└── experimento.jpg
```

Depois, elas podem ser referenciadas no documento conforme a estrutura já existente no template.

Evite colocar imagens diretamente na raiz do projeto quando houver uma pasta específica para elas.

---

# 📚 Referências bibliográficas

Caso o template utilize um arquivo `.bib`, as referências bibliográficas devem ser adicionadas nesse arquivo.

Por exemplo:

```text
referencias.bib
```

Cada referência deve ser cadastrada seguindo o formato BibTeX utilizado pelo projeto.

Depois, no texto do TCC, a referência pode ser citada utilizando os comandos já definidos pelo template.

**Recomenda-se manter o padrão de citações e referências utilizado pelo modelo.**

---

# ⚙️ Compilação

O Overleaf realiza a compilação do projeto automaticamente.

Após modificar um arquivo `.tex`, clique em:

**Recompile**

para gerar uma nova versão do PDF.

Caso apareça algum erro de compilação, verifique a mensagem apresentada pelo Overleaf. Na maioria dos casos, o erro estará relacionado a:

* Comandos LaTeX escritos incorretamente;
* Chaves `{}` não fechadas;
* Ambientes não finalizados;
* Arquivos ou imagens com nomes incorretos;
* Pacotes não disponíveis ou configurados incorretamente;
* Referências a arquivos que foram renomeados ou removidos.

---

# ⚠️ Recomendações importantes

### Não edite diretamente os arquivos do GitHub

O repositório serve como **modelo/base**.

Cada aluno deve baixar ou copiar o projeto para sua própria conta do Overleaf e trabalhar nessa cópia.

Assim, as alterações realizadas por cada pessoa não afetam o template disponibilizado para a turma.

### Faça cópias de segurança

Mesmo utilizando o Overleaf, é recomendável manter cópias do projeto.

O próprio Overleaf permite baixar o projeto em formato `.zip`.

### Evite alterar arquivos de configuração sem necessidade

Alguns arquivos podem ser responsáveis pela configuração da formatação do documento.

Antes de modificar o preâmbulo, comandos de formatação ou arquivos de configuração, verifique como eles são utilizados pelo template.

### Verifique as normas do seu curso

O template é uma ferramenta para auxiliar na elaboração do TCC, mas **não substitui as normas oficiais do IFPB, do curso ou as orientações do orientador**.

Antes da entrega final, confira:

* Normas de formatação;
* Modelo de capa;
* Folha de rosto;
* Numeração;
* Citações;
* Referências;
* Figuras e tabelas;
* Elementos pré-textuais;
* Elementos pós-textuais;
* Regras específicas do seu curso.

---

# 🔄 Atualizações do template

Caso novas versões do template sejam disponibilizadas neste repositório, será necessário verificar as alterações antes de incorporá-las ao seu projeto.

**Não substitua simplesmente todos os arquivos do seu TCC por uma nova versão**, pois isso pode apagar alterações e conteúdos que você já tenha produzido.

O ideal é comparar as alterações e incorporar apenas aquilo que for necessário.

---

# 🤝 Contribuições

Caso encontre algum erro de formatação, problema de compilação ou tenha alguma sugestão de melhoria, abra uma **Issue** neste repositório ou entre em contato com o responsável pelo template.

Pull Requests também podem ser utilizados para propor melhorias na estrutura do modelo.

---

# 📄 Licença e origem

Este projeto é disponibilizado para fins acadêmicos e educacionais, como modelo para auxiliar os alunos na elaboração de seus TCCs.

O template foi originalmente obtido a partir de um modelo disponibilizado no Overleaf. Caso existam créditos, autores ou informações de licença nos arquivos originais, eles devem ser preservados.

---

## 👨‍🎓 Para começar

Se você está utilizando este template pela primeira vez, o fluxo recomendado é:

```text
GitHub
   ↓
Download ZIP
   ↓
Overleaf
   ↓
New Project → Upload Project
   ↓
Projeto copiado para sua conta
   ↓
Renomear projeto
   ↓
Começar a escrever o TCC
```

**Bom trabalho e boa escrita! 🎓**
