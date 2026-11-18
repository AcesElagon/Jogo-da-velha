# Jogo da Velha 3D

Jogo da velha num cubo 3×3×3, feito com Three.js em um único arquivo (`index.html`).

- **Jogar:** toque ou clique numa esfera. A esfera escolhida acende na cor da vez antes de confirmar. Vence quem fizer 3 em linha em qualquer direção (49 linhas possíveis, incluindo as diagonais que atravessam o cubo).
- **Camadas:** mostra um andar por vez (Topo, Meio, Base) e apaga os outros; teclas 0–3 também trocam.
- **Espaço:** afasta as esferas para enxergar o miolo do cubo.
- **Câmera:** arraste para girar, pinça/roda do mouse para zoom. "Centralizar" volta ao ângulo em que todas as esferas aparecem; "De longe" afasta a câmera.
- **Opções:** 2 jogadores ou contra o computador, centro bloqueado (desligado por padrão; ao ligar, a esfera central some e ninguém pode marcá-la) e girar sozinho.

Para jogar, abra `index.html` no navegador (precisa de internet para carregar o Three.js do CDN).
