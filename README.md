# formulario-animadoFormulário animado com JS puro e CSS Animation
Desafios
 Fazer o formulário aparecer, suavemente, quando a página abrir
 Fazer os campos aparecem da esquerda pra direita, suavizando a entrada e fazendo-os entrar em momentos distintos
 Quando clicar em Login, fazer o formulário sair da tela, indo para baixo
 Remover formulário do html e não mostrar rolagem enquanto o formulário está saindo da tela
 Adicionar um efeito diferente de timing para a saída do formulário
 Fazer o formulário dizer não-não (vibrar) caso haja campos vazios.
 Criar alguns quadrados animados (que fiquem girando) e que saem de baixo da tela (fora do campo de visão) e vão para cima da tela (que saia do campo de visão também). Detalhes: Deve ter tamanhos diferentes, sairem em momentos diferentes, terem timing diferente, animação contínua.
Animation
8 propriedades:

animation-name: animationname;
animation-duration: 2s;
animation-delay: 3s;
animation-fill-mode: none;
animation-play-state: running;
animation-timing-function: ease;
animation-direction: reverse;
animation-iteration-count: infinite;
@keyframes animationname {
  0% {

  }

  100%{

  }
}
podemos ter múltiplas animações no mesmo elemento

.animate {
  animation: slide-top 2s, bounce 1s, fade 0.2s;
}
References
CSS Animation Docs

Animation Timing Docs

Site para criar animações

Site para criar cubic Bézier timming
