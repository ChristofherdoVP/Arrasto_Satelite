# Arrasto Satelite
Simulação de Arrasto Atmosférico em Satélites LEO durante Tempestades Geomagnéticas

🛰️ Simulação de Decaimento Orbital: O Impacto do Sol na TermosferaEste projeto apresenta uma ferramenta interativa para visualizar como as tempestades geomagnéticas afetam a órbita de satélites em regiões de baixa altitude (LEO).Muitas vezes esquecemos que, embora o espaço seja considerado "vácuo", a atmosfera da Terra não acaba abruptamente. Existe uma camada tênue de gases que, sob a influência do Sol, pode se tornar um verdadeiro obstáculo para a navegação espacial.

🌍 O Fenômeno: Por que o satélite cai? Mesmo a centenas de quilômetros de altura, os satélites enfrentam uma resistência constante: o arrasto atmosférico. É como um "vento" muito leve, mas persistente, que rouba energia da órbita.O Efeito "Pipoca" da AtmosferaQuando o Sol emite uma grande quantidade de energia (tempestades solares), a atmosfera superior da Terra absorve esse calor e se expande, como um milho de pipoca estourando.Em dias calmos, o satélite viaja em uma região quase vazia.Em dias de tempestade, essa "nuvem" de gases sobe, e o satélite passa a colidir com muito mais partículas, aumentando a força de resistência.

🎮 A Simulação é uma ferramenta que permite comparar, lado a lado, dois cenários idênticos que divergem apenas pela atividade solar.Variáveis que você pode controlar:Intensidade Kp (Nível da Tempestade): O índice Kp mede a perturbação no campo magnético da Terra. No simulador, aumentar o Kp faz a atmosfera "inchar", aumentando a densidade de partículas no caminho do satélite vermelho.Tipo de Satélite:Nem todo satélite reage igual. O simulador permite alternar entre: 
CubeSats: Pequenos e leves, são muito sensíveis ao arrasto. 
Satélites Médios e Grandes: Possuem diferentes relações entre sua área de superfície e sua massa, o que muda o quão rápido eles perdem altitude.
Altitude Inicial: Quanto mais baixo o satélite começa, mais "densa" é a atmosfera e mais rápido é o decaimento.

📈 O que observar na prática? Ao rodar a simulação, preste atenção nestes pontos didáticos: O Diferencial de Altitude: Note que o satélite sob tempestade (vermelho) começa a "perder a corrida" para o azul. Essa diferença acumulada é o que, na vida real, exige que os operadores de satélite gastem combustível para corrigir a órbita.A Densidade das Partículas: As partículas flutuando no fundo representam visualmente a densidade da atmosfera. Veja como a parte inferior (tempestade) fica muito mais "congestionada" conforme o Kp aumenta.O Efeito do Design: Teste o CubeSat em uma tempestade forte e compare com um satélite Grande. Você verá como a engenharia do objeto influencia sua sobrevivência no espaço.Nota de Realismo: Para que os efeitos sejam visíveis em segundos na tela, o decaimento foi visualmente acelerado. Em condições reais, esse processo pode levar dias, semanas ou meses.

🛠️ Este simulador foi construído puramente com:HTML5 & CSS3 (Interface e Layout)JavaScript & Canvas (Lógica de física e renderização gráfica)

💡 Ideia para Sala de AulaTente encontrar a altitude "segura" para um CubeSat sobreviver a uma tempestade de Kp 7 sem perder mais de 2 km de altitude em uma volta completa. Esse é o tipo de desafio que engenheiros de missão enfrentam todos os dias!
