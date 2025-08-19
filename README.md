# 🏁 Corrida 2D Top-Down

Um jogo de corrida 2D desenvolvido com HTML5 Canvas e JavaScript vanilla, apresentando um sistema de física realista e controles responsivos.

## ✨ Características

### 🚗 Sistema de Física Avançado
- **Classe Car**: Implementação completa com propriedades físicas
- **Física Realista**: Aceleração, desaceleração, atrito e inércia
- **Efeito de Drift**: Sistema de derrapagem baseado na velocidade e direção
- **Inércia nas Curvas**: Movimento realista que simula a física de um carro real
- **Colisão com Bordas**: Sistema de rebatimento com perda de velocidade

### 🎮 Controles Multiplataforma
- **PC**: WASD ou Setas direcionais
- **Mobile**: Botões touch responsivos
- **Controles Responsivos**: Movimento suave e gradual (não instantâneo)

### 🎨 Interface e Visual
- **Canvas Responsivo**: Adapta-se automaticamente ao tamanho da tela
- **UI Completa**: Velocidade, voltas e cronômetro em tempo real
- **Design Moderno**: Interface com gradientes e efeitos visuais
- **Indicador de Drift**: Visual feedback quando o carro está derrapando

## 🚀 Como Jogar

1. **Abra o arquivo** `index.html` em qualquer navegador moderno
2. **Clique em "Iniciar Jogo"** para começar
3. **Use os controles** para dirigir o carro:
   - **W/↑**: Acelerar
   - **S/↓**: Frear/Ré
   - **A/←**: Virar à esquerda
   - **D/→**: Virar à direita
4. **Experimente o drift**: Faça curvas em alta velocidade para ativar o efeito

## 🔧 Tecnologias Utilizadas

- **HTML5 Canvas**: Para renderização 2D
- **JavaScript ES6+**: Classes, arrow functions, destructuring
- **CSS3**: Gradientes, animações, media queries responsivas
- **Física Customizada**: Sistema de partículas e movimento realista

## 📱 Responsividade

- **Desktop**: Interface otimizada para telas grandes
- **Tablet**: Adaptação automática para dispositivos médios
- **Mobile**: Controles touch e layout otimizado para telas pequenas

## 🎯 Funcionalidades Técnicas

### Classe Car
```javascript
class Car {
    // Propriedades físicas: posição, ângulo, velocidade, aceleração
    // Física realista: atrito, resistência do ar, inércia
    // Sistema de drift: detecção automática e efeitos visuais
    // Colisão com bordas: rebatimento realista
}
```

### Sistema de Física
- **Delta Time**: Física consistente independente do FPS
- **Atrito**: Desaceleração natural baseada em constantes físicas
- **Inércia**: Movimento que continua mesmo após soltar os controles
- **Drift**: Sistema que simula derrapagem realista

### Controles
- **Input Mapping**: Sistema unificado para teclado e touch
- **Responsividade**: Movimento gradual e suave
- **Feedback Visual**: Indicadores de estado do carro

## 🎮 Próximas Funcionalidades

- [ ] Sistema de voltas automático
- [ ] Múltiplas pistas
- [ ] Obstáculos e power-ups
- [ ] Sistema de pontuação
- [ ] Efeitos sonoros
- [ ] Partículas de drift
- [ ] Modo multiplayer local

## 🌟 Destaques

- **Performance Otimizada**: Game loop com requestAnimationFrame
- **Código Limpo**: Arquitetura modular e bem estruturada
- **Física Realista**: Comportamento de carro autêntico
- **Cross-Platform**: Funciona em qualquer dispositivo

## 📄 Licença

Este projeto é open source e está disponível para uso educacional e pessoal.

---

**Desenvolvido com ❤️ usando HTML5 Canvas e JavaScript vanilla**
