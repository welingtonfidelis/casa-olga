# Casa Olga

Modelo 3D interativo da casa desenhada no rascunho à mão: uma página HTML só, com [three.js](https://threejs.org) r128 por CDN. A parte técnica veio da Casa Alto da Colina; o desenho da casa é outro.

- Pé-direito único de 3,00 m. A casa tem laje plana com caixote em volta, menos na divisa da esquerda; a edícula tem telhado de telha de barro.
- Casa em L (9,30 × 10,75 m, sem o canto da frente à esquerda) e edícula nos fundos (9,30 × 2,30 m): 110,96 m² construídos.
- Modos: casa completa, sem teto e planta (paredes cortadas a 1,20 m; a janela acima do corte vira uma faixa azul).
- Câmeras: isométrica, de cima, fachada e fundos (quintal e frente da edícula).
- Toque num cômodo para ver nome, área, medidas, cotas e as portas e janelas dele.
- Camadas: móveis e nomes dos cômodos (os nomes aparecem sem o teto). Os códigos P e J aparecem no cartão do cômodo.
- Controles responsivos: barra inferior no celular e painéis laterais em telas grandes; manete ou W A S D para girar e andar.

## Como abrir

- Online, pelo GitHub Pages: https://welingtonfidelis.github.io/casa-olga/
- No computador: abra `index.html` no navegador.
- No celular, na mesma rede Wi-Fi: rode `python3 -m http.server 5212 --bind 0.0.0.0` nesta pasta e abra `http://<IP do Mac>:5212`.

## Medidas

As medidas são o vão livre de cada cômodo; as paredes têm 15 cm. Os quartos, a lavanderia e a edícula já estão nas medidas novas pedidas depois do rascunho.

| Cômodo | Medida |
| --- | --- |
| Sala | 3,00 × 3,50 |
| Cozinha | 3,00 × 4,80 |
| Quarto 1 (frente, direita) | 3,00 × 3,00 |
| Suíte | 3,00 × 3,00 |
| Banheiro da suíte | 3,00 × 2,00 |
| Banheiro | 3,00 × 2,00 |
| Quarto 2 (esquerda) | 2,70 × 4,65 |
| Lavanderia (aberta, na área coberta dos fundos) | 1,50 × 2,00 |
| Área coberta dos fundos | 4,35 × 2,00 |
| Cozinha de fundo | 4,40 × 2,00 |
| Área coberta da edícula | 4,60 × 2,00 |

A sala e a cozinha são um ambiente só, dividido pelo balcão. O balcão fica na linha da parede do Quarto 2 com a garagem, e a cozinha vai dele até a linha entre os banheiros.

As portas têm 2,10 m de altura: P2/P3/P6 0,80, P4/P5 0,70. A P1 (no rascunho, 1,50) e a P10 (fora do rascunho) viraram portas de vidro de correr de 2,00 m. As janelas seguem a lista do rascunho e têm o topo a 2,10 m: J1, J2, J3 e J7 (1,20 × 1,00) com peitoril de 1,10; J4 e J5 (0,40 de altura) com peitoril de 1,70. A P7, a P8, a P9, a J6 e a J8 saíram junto com a lavanderia de dentro, a parede da cozinha de fundo e o banheiro da edícula; os outros códigos continuam os do rascunho.

## Alterações pedidas depois do rascunho

- **P10:** porta de vidro de correr no fundo da cozinha, de 2,00 × 2,10 m, para a área coberta dos fundos. São 2 folhas, uma fixa e uma que corre. Ela fica onde antes estava a pia, no meio do trecho entre a bancada e a parede da direita.
- **Cozinha:** os armários e a bancada correm ao longo da parede da esquerda, com pia, cooktop com coifa e geladeira perto da P6. A mesa para 4 fica encostada na parede da direita.
- **P1:** a entrada da fachada virou porta de vidro de correr de 2,00 × 2,10 m, no meio da parede da sala. No rascunho ela tinha 1,50 m. É igual à P10: 2 folhas.
- **Sala:** a parede da TV tem um painel ripado de madeira do piso ao teto, da P2 até o canto da fachada, com 2,00 m. Sobre o balcão entre a sala e a cozinha ficam 3 pendentes de cúpula preta.
- **Medidas novas:**
  - Quarto 1: 3,00 × 3,00.
  - Suíte: 3,00 × 3,00.
  - Quarto 2 (esquerda): 2,70 × 3,00.
  - Lavanderia: 2,70 × 1,50.
  - O resto andou para a frente: os banheiros, a área coberta dos fundos, o quintal e a edícula. A casa ficou 2 m mais curta, e a área livre da frente passou a ter 2,85 × 3,65.
  - A P2 continua no fundo do Quarto 1, e por isso agora fica no meio da parede da TV da sala.
- **Balcão:** foi para a linha da parede do Quarto 2 que dá para a garagem, como se continuasse essa parede. Os pendentes e as banquetas foram junto. A sala ficou com 3,00 × 3,50 e a cozinha com 3,00 × 4,80.
- **P3 e P6:** foram para o canto das paredes do lado do balcão, a 10 cm da quina. As folhas abrem para dentro do quarto e ficam encostadas na parede da frente. No outro canto não cabem: lá estão a geladeira (P6) e a mesa de jantar (P3).
- **Quartos:**
  - Quarto 1: cabeceira na fachada e guarda-roupa no fundo.
  - Suíte: cama de casal (1,38) na vertical, encostada na parede da J3, com a cabeceira na parede da frente e o criado-mudo do lado livre. O guarda-roupa fica no fundo.
  - Quarto 2: cama na vertical, com a cabeceira sob a J1. Ela foi puxada para a esquerda para a P6 abrir, e o criado-mudo fica desse lado. O guarda-roupa ocupa a parede do fundo.
  - No Quarto 1 e na Suíte sobram cerca de 50 cm entre o pé da cama e o guarda-roupa.
- **Caixote:** a laje da casa avança 0,60 m e fecha numa caixa de 0,50 m de altura, que desce 0,18 abaixo da laje e sobe 0,20 acima dela. Ele contorna a frente, a lateral direita, o fundo e os dois lados que dão para a área livre da frente. A lateral esquerda faz divisa com o vizinho e fica sem caixote, com a laje rente à parede.
- **Telhado da edícula:** a laje aparente deu lugar a um telhado de telha de barro (capa e canal) em meia-água de 35%, que cai para o quintal. A laje continua por baixo, como forro, e as paredes laterais sobem em oitão até o telhado.
  - O beiral tem 0,60 m para o quintal e 0,30 m para a direita, com tabuado e testeira de madeira.
  - Na esquerda e no fundo, que fazem divisa, não há beiral; no alto, junto do fundo, há um rufo.
- **J2:** a janela do Quarto 1 saiu da lateral direita e foi para a fachada, no meio da parede do quarto. A cama foi para o meio do quarto, com a cabeceira sob a janela, como no Quarto 2.
- **Lavanderia:** saiu de dentro da casa e foi para o canto esquerdo da área coberta dos fundos, encostada na divisa. É aberta, com a máquina e o tanque na parede da divisa, num piso de 1,50 × 2,00.
- **Quarto 2:** ficou com o lugar da lavanderia e foi até a parede do fundo, com 2,70 × 4,65 (no rascunho eram 2,70 × 4,00).
  - A P7 e a J6, que eram da lavanderia, saíram, e o fundo do quarto ficou fechado.
  - O guarda-roupa foi para a nova parede do fundo, e no meio do quarto entrou uma escrivaninha na parede da esquerda.
- **Edícula:**
  - Saiu a parede entre a cozinha de fundo e a área coberta, e a cozinha ficou aberta para a mesa.
  - O banheiro saiu, com a P9, a J8 e a parede dele. A cozinha de fundo passou a ter 4,40 × 2,00, com a geladeira no canto onde era o banheiro.

## Suposições a confirmar

1. A faixa de 2 m atrás do Quarto 2 e da cozinha virou uma área coberta sob a laje, aberta para o quintal. A cozinha (P10) e o banheiro (P5) abrem para ela, e a lavanderia fica no canto da esquerda.
2. A cozinha de fundo fica no meio e na direita da edícula (o rótulo do rascunho está escrito em cima da linha). A parte da esquerda virou área coberta aberta para o quintal.
3. A área da frente, à esquerda da sala (2,85 × 3,65), é descoberta. Somada ao recuo, cabe um carro.
4. O quintal entre a casa e a edícula tem 3,00 m.
5. O recuo da frente tem 3,00 m. O corredor lateral à direita tem 1,50 m: as janelas J3, J4 e J5 dão para ele. O lado esquerdo fica na divisa, sem janelas.
6. A barra preta entre a sala e a cozinha virou um balcão de alvenaria de 1,60 × 0,35 m, com 1,10 m de altura e tampo de granito.
7. O quadradinho preto na lavanderia virou o tanque, que foi junto para a área coberta.
8. A laje da casa é plana, sem telhado. O caixote tem 0,60 m de beiral e 0,50 m de altura.
9. O telhado da edícula cai para o quintal porque o fundo do terreno também faz divisa. A inclinação de 35% é a de costume para telha de barro.
