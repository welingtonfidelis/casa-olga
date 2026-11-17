# Casa Olga

Modelo 3D interativo da casa desenhada no rascunho à mão: uma página HTML só, com [three.js](https://threejs.org) r128 por CDN. A parte técnica veio da Casa Alto da Colina; o desenho da casa é outro.

- Pé-direito único de 3,00 m e laje plana convencional por cima.
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

As medidas são o vão livre de cada cômodo; as paredes têm 15 cm. Os quartos e a lavanderia já estão nas medidas novas pedidas depois do rascunho.

| Cômodo | Medida |
| --- | --- |
| Sala | 3,00 × 3,50 |
| Cozinha | 3,00 × 4,80 |
| Quarto 1 (frente, direita) | 3,00 × 3,00 |
| Suíte | 3,00 × 3,00 |
| Banheiro da suíte | 3,00 × 2,00 |
| Banheiro | 3,00 × 2,00 |
| Quarto 2 (esquerda) | 2,70 × 3,00 |
| Lavanderia | 2,70 × 1,50 |
| Área coberta dos fundos | 5,85 × 2,00 |
| Cozinha de fundo | 3,00 × 2,00 |
| Banheiro da edícula | 1,10 × 2,00 |
| Área coberta da edícula | 4,60 × 2,00 |

A sala e a cozinha são um ambiente só, dividido pelo balcão. O balcão fica na linha da parede do Quarto 2 com a garagem, e a cozinha vai dele até a linha entre os banheiros.

As portas têm 2,10 m de altura: P8 0,90, P2/P3/P6/P7 0,80, P4/P5/P9 0,70. A P1 (no rascunho, 1,50) e a P10 (fora do rascunho) viraram portas de vidro de correr de 2,00 m. As janelas seguem a lista do rascunho e têm o topo a 2,10 m: J1, J2, J3 e J7 (1,20 × 1,00) com peitoril de 1,10; J4, J5, J6 e J8 (0,40 de altura) com peitoril de 1,70.

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
  - Nos três quartos sobram cerca de 50 cm entre o pé da cama e o guarda-roupa.

## Suposições a confirmar

1. A faixa de 2 m atrás da lavanderia e da cozinha virou uma área coberta sob a laje, aberta para o quintal. A lavanderia (P7) e o banheiro (P5) abrem para ela.
2. A cozinha de fundo é o cômodo de 3 × 2,0 do meio da edícula (o rótulo está escrito em cima da linha). A P8 é a entrada dela, vinda da parte da esquerda, que virou área coberta aberta para o quintal.
3. A P9 abre para dentro da cozinha de fundo, porque o banheiro tem só 1,10 m de largura.
4. A área da frente, à esquerda da sala (2,85 × 3,65), é descoberta. Somada ao recuo, cabe um carro.
5. O quintal entre a casa e a edícula tem 3,00 m.
6. O recuo da frente tem 3,00 m. O corredor lateral à direita tem 1,50 m: as janelas J2 a J5 dão para ele. O lado esquerdo fica na divisa, sem janelas.
7. A barra preta entre a sala e a cozinha virou um balcão de alvenaria de 1,60 × 0,35 m, com 1,10 m de altura e tampo de granito.
8. O quadradinho preto na lavanderia virou o tanque.
9. A laje é plana, sem telhado e sem platibanda.
