# 💌 Carta - Projeto Interativo

Um projeto web emocionante que simula uma carta física que pode ser aberta e fechada, criada especialmente para o Dia das Mães.

## ✨ Características

- **Animação Realista**: Envelope que se abre e fecha com animações suaves
- **Design Romântico**: Cores quentes e elementos visuais afetuosos
- **Interatividade**: Botões para abrir e fechar a carta
- **Corações Flutuantes**: Efeito de corações subindo com animações
- **Tipografia Elegante**: Fonte cursiva "Dancing Script" para um toque especial
- **Responsivo**: Adaptado para diferentes tamanhos de tela

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Animações, transformações e estilização avançada
- **JavaScript**: Interatividade e controle das animações
- **jQuery**: Simplificação da manipulação DOM
- **Google Fonts**: Tipografia elegante

## 📦 Estrutura do Projeto

```
carta/
├── carta.html          # Página principal
├── carta.css           # Estilos e animações
├── carta.js            # Lógica de interação
└── README.md           # Documentação
```

## 🚀 Como Utilizar

1. Abra o arquivo `carta.html` em qualquer navegador moderno
2. Interaja com a carta:
   - Clique no envelope para abrir
   - Use o botão "Abrir" para revelar a mensagem
   - Use o botão "Fechar" para fechar a carta
   - Observe os corações animados subindo

## 💝 Mensagem Personalizável

O conteúdo da carta pode ser facilmente editado no HTML:

```html
<div class="letter">
  <div class="words line1">Para Mãe</div>
  <div class="words line2">Feliz dia da Mãe</div>
  <div class="words line3">Mãe a senhora é foda</div>
  <div class="words line4">Amo a senhora</div>
</div>
```

## 🎨 Personalização

### Cores
Modifique no arquivo `carta.css`:
```css
#envelope {
  background-color: #d9534f; /* Cor principal do envelope */
}

.words {
  background-color: #ffe6e6; /* Cor de fundo do texto */
}
```

### Animações
Ajuste as animações dos corações:
```css
.a1 {
  animation: slideUp 4s linear 1, sideSway 2s ease-in-out 4 alternate;
}
```

## 🌐 Compatibilidade

- Navegadores modernos (Chrome, Firefox, Safari, Edge)
- Dispositivos desktop e móveis
- Compatível com touch events em tablets e smartphones

## 📝 Licença

Este projeto foi criado para fins educacionais e de demonstração. Sinta-se à vontade para usar e personalizar para presentear sua mãe!

## 🎁 Ideias de Melhoria

- Adicionar mais páginas na carta
- Incluir efeitos sonoros ao abrir/fechar
- Adicionar funcionalidade de impressão
- Criar versão para diferentes ocasiões (aniversário, natal, etc.)

---

⭐ Este projeto é perfeito para demonstrar carinho e apreço pela pessoa mais especial: sua mãe!
