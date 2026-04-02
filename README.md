# Documentação Colaborativa: Git & GitHub

[![GitHub issues](https://img.shields.io/github/issues/iaglourenco/gh0)](https://github.com/iaglourenco/gh0/issues)
[![GitHub forks](https://img.shields.io/github/forks/iaglourenco/gh0)](https://github.com/iaglourenco/gh0/network)
[![GitHub stars](https://img.shields.io/github/stars/iaglourenco/gh0)](https://github.com/iaglourenco/gh0/stargazers)
[![GitHub license](https://img.shields.io/github/license/iaglourenco/gh0)](https://github.com/iaglourenco/gh0/blob/main/LICENSE)

> Projeto colaborativo de documentação sobre Git e GitHub, construído por estudantes para estudantes na disciplina GitHub do Zero. O objetivo é aprender na prática versionamento, colaboração e boas práticas usando Git e GitHub.

## Sobre o Projeto

Este é um projeto educacional **intensivo de 1 semana (20h)** onde alunos colaboram para criar uma documentação completa sobre Git e GitHub. O objetivo é aprender na prática:

- ✅ Versionamento de código com Git
- ✅ Colaboração via GitHub (fork, branch, pull requests)
- ✅ Code review e boas práticas
- ✅ Resolução de conflitos de merge
- ✅ Trabalho em equipe assíncrono
- ✅ Documentação técnica clara e didática

## Para Estudantes

### Começando Rápido

**PASSO 1**: Leia o **[Guia de Contribuição](CONTRIBUTING.md)** (OBRIGATÓRIO!)

**PASSO 2**: Escolha uma [issue disponível](../../issues?q=is%3Aissue+is%3Aopen+label%3Astatus%3Adisponivel)

**PASSO 3**: Comente na issue: "Gostaria de trabalhar nesta issue"

**PASSO 4**: Aguarde ser atribuído à issue

**PASSO 5**: Siga o fluxo de trabalho:

```
📌 Fork → 💻 Clone → 🌿 Branch → ✍️ Commit → 🚀 Push → 🔀 Pull Request → 👀 Review → ✅ Merge
```

### Fluxo de Trabalho Detalhado

```bash
# 1. Fork este repositório (botão Fork no GitHub)

# 2. Clone SEU fork (não o repositório original!)
git clone https://github.com/iaglourenco/gh0.git
cd gh0

# 3. Configure upstream (repositório original)
git remote add upstream https://github.com/PROFESSOR-USUARIO/gh0git

# 4. Crie uma branch descritiva
git checkout -b seu-nome/adiciona-secao-git-init

# 5. Faça suas alterações nos arquivos
# (Edite o arquivo indicado na issue)

# 6. Veja o que mudou
git status
git diff

# 7. Adicione as mudanças
git add docs/02-comandos-essenciais.md

# 8. Faça commit com mensagem descritiva
git commit -m "docs: adiciona explicação sobre git init"

# 9. Envie para SEU fork
git push origin seu-nome/adiciona-secao-git-init

# 10. Abra Pull Request no GitHub
# (GitHub vai mostrar um banner para criar PR)
```

### Como Contribuir

1. **Leia o guia de contribuição**: [CONTRIBUTING.md](CONTRIBUTING.md)
2. **Escolha uma issue disponível**: Veja as [issues abertas](../../issues)
3. **Fork este repositório**: Clique no botão "Fork" no canto superior direito
4. **Faça suas alterações**: Siga o fluxo de trabalho descrito no CONTRIBUTING.md
5. **Envie um Pull Request**: Submeta sua contribuição para revisão

### Documentação Disponível

- [01 - Conceitos Básicos](docs/01-conceitos-basicos.md)
- [02 - Comandos Essenciais](docs/02-comandos-essenciais.md)
- [03 - Branching e Merge](docs/03-branching-e-merge.md)
- [04 - Pull Requests e Review](docs/04-pull-requests-e-review.md)
- [05 - Boas Práticas](docs/05-boas-praticas.md)
- [06 - Resolução de Conflitos](docs/06-resolucao-conflitos.md)
- [07 - Workflows no GitHub](docs/07-workflows-github.md)
- [08 - Ferramentas e Recursos](docs/08-ferramentas-e-recursos.md)

Veja o [índice completo da documentação](docs/README.md).


## Regras do Projeto

- ✅ Cada aluno deve contribuir com **pelo menos 1 Pull Request**
- ✅ Cada aluno deve revisar **pelo menos 1 Pull Request**
- ✅ Conflitos de merge devem ser resolvidos pelo autor da PR
- ✅ Todas as contribuições passam por code review
- ✅ Seja respeitoso e construtivo nas revisões
- ✅ Siga o [Código de Conduta](CODE_OF_CONDUCT.md)

## Contribuidores

<a href="https://github.com/iaglourenco/gh0/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=iaglourenco/gh0" />
</a>

Este projeto existe graças a todos os estudantes que contribuíram!

## Precisa de Ajuda?

- **Dúvidas sobre Git/GitHub?** Abra uma [issue de pergunta](../../issues/new/choose)
- **Encontrou um erro?** Abra uma [issue de bug](../../issues/new/choose)
- **Problemas técnicos?** Consulte o [CONTRIBUTING.md](CONTRIBUTING.md)
- **Dúvidas sobre a disciplina?** Entre em contato com o professor

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Recursos Externos

### Documentação Oficial

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs em Português](https://docs.github.com/pt)
- [Pro Git Book (PT-BR)](https://git-scm.com/book/pt-br/v2)

### Tutoriais Interativos

- [Learn Git Branching](https://learngitbranching.js.org/) - Visualização interativa
- [GitHub Learning Lab](https://lab.github.com/) - Cursos práticos
- [Git Immersion](http://gitimmersion.com/) - Tutorial hands-on

### Cheat Sheets

- [GitHub Git Cheat Sheet (PDF)](https://education.github.com/git-cheat-sheet-education.pdf)
- [Atlassian Git Cheat Sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)

---