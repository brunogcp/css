<div align="center">
  <h3 align="center">CSS</h3>
  <div>
  <a href="https://bgcp.com.br/article/581812ec-16be-4e92-8925-ac325d1f76a6">
  <img src="https://img.shields.io/badge/Download PDF (ENGLISH)-black?style=for-the-badge&logoColor=white&color=000000" alt="three.js" />
  </a>
  </div>
</div>

## 🎨 Introdução à Animação com CSS

Animações em CSS são uma forma poderosa e divertida de dar vida às suas páginas web! Com elas, você pode criar movimentos suaves, transições de estado e efeitos visuais que capturam a atenção do usuário e melhoram a interatividade do seu site. Neste tutorial, vamos mergulhar no mundo das animações CSS, criando um exemplo simples que demonstra como você pode implementar animações eficazes com apenas algumas linhas de código. Vamos lá?

### 🌟 Principais Características:

- **💫 Animações Suaves**: Crie movimentos e efeitos visuais fluidos.
- **🔄 Transições Automáticas**: Faça elementos transitarem entre estados com estilo.
- **🎭 Efeito Hover**: Adicione interatividade com animações que reagem ao mouse.
- **✨ Fácil de Implementar**: Use propriedades simples de CSS para criar efeitos complexos.

## 🛠️ Setup do Projeto Frontend

1. **Criação do Arquivo HTML**:
   - Crie um arquivo `index.html` e adicione a estrutura básica do HTML.
   - Inclua um elemento para animar, como um `<div>` com uma classe `animated-box`.

2. **Criação do Arquivo CSS**:
   - Crie um arquivo `styles.css` para adicionar os estilos e animações do seu elemento.

3. **Vinculação do CSS ao HTML**:
   - No `<head>` do seu `index.html`, adicione um link para o seu arquivo CSS.

## 📊 Implementação

### Arquivo HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Animação CSS</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="animated-box"></div>
</body>
</html>
```

### Arquivo CSS

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f0f0f0;
}

.animated-box {
  width: 100px;
  height: 100px;
  background-color: #007bff;
  transition: transform 0.5s ease;
}

.animated-box:hover {
  transform: scale(1.5) rotate(45deg);
}

@keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.1);
  }
  100% {
    transform: scale(1);
  }
}

.animated-box:hover {
  animation: pulse 1s infinite;
}
```

Neste exemplo, a `.animated-box` cresce e rotaciona quando o mouse passa sobre ela, criando um efeito visual dinâmico e atraente. A animação `pulse` faz a caixa "pulsar", alternando entre diferentes escalas.

## 🏆 Conclusão

Parabéns! 🎉 Você acabou de adicionar animações CSS ao seu projeto web. Com esse conhecimento, você pode começar a explorar ainda mais possibilidades, criando interfaces ricas e interativas. Lembre-se de que a chave para animações eficazes é a sutileza e o uso moderado - um pouco já pode adicionar muito ao seu design sem sobrecarregar seus usuários. Continue experimentando e divirta-se criando!