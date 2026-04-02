# 🖼️ Assets - Recursos Visuais

Esta pasta é destinada a armazenar **imagens, diagramas e recursos visuais** usados na documentação.

## 📁 Organização

Mantenha os arquivos organizados e com nomes descritivos:

### Bons nomes de arquivo

```
git-workflow-diagram.png
merge-conflict-example.png
github-pr-process.jpg
branch-visualization.svg
```

### Evite

```
imagem1.png
screenshot.png
foto.jpg
```

## 📝 Como Adicionar Imagens

1. Salve sua imagem nesta pasta (`docs/assets/`)
2. Referencie no arquivo markdown:

```markdown
![Descrição da imagem](assets/nome-arquivo.png)
```

## 🎨 Tipos de Arquivos Recomendados

- **PNG**: Screenshots, diagramas com transparência
- **JPG**: Fotos, imagens complexas
- **SVG**: Diagramas vetoriais (escaláveis)
- **GIF**: Animações simples (tutoriais passo-a-passo)

## 📏 Boas Práticas

- **Tamanho**: Comprima imagens para web (< 500KB quando possível)
- **Dimensões**: Máximo de 1200px de largura
- **Descrição**: Sempre use texto alternativo (alt text) descritivo
- **Copyright**: Use apenas imagens que você criou ou tem direito de usar

## 🛠️ Ferramentas Úteis

- **Criar Diagramas**: [Excalidraw](https://excalidraw.com/), [draw.io](https://draw.io)
- **Editar Imagens**: [GIMP](https://www.gimp.org/), Photoshop
- **Comprimir**: [TinyPNG](https://tinypng.com/), [Squoosh](https://squoosh.app/)
- **Screenshots**: Windows Snipping Tool, macOS Screenshot, Flameshot (Linux)

## 📋 Imagens Sugeridas

Exemplos de imagens úteis para a documentação:

- [ ] Diagrama de fluxo Git (working directory → staging → repository)
- [ ] Exemplo visual de merge
- [ ] Exemplo visual de conflito de merge
- [ ] Fluxo de Pull Request
- [ ] Diagrama de branching strategies
- [ ] Screenshot da interface do GitHub
- [ ] Exemplo de git log --graph
- [ ] Comparação Git vs GitHub

## 🤝 Contribuindo

Ao adicionar imagens:

1. Certifique-se de que a imagem é relevante e útil
2. Use nomes descritivos
3. Comprima a imagem antes de commitar
4. Referencie a imagem no arquivo markdown apropriado
5. Adicione texto alternativo descritivo

---

**Nota**: Arquivos muito grandes (> 1MB) devem ser evitados. Considere usar links externos ou otimizar a imagem.
