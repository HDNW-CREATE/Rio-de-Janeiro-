RIO DE JANEIRO — Praias • Cultura • Natureza
=============================================

TEMA
----
Site sobre o ESTADO DO RIO DE JANEIRO: praias, cartões-postais, fauna e
Mata Atlântica, cultura e samba, destinos turísticos e localização no mapa.

PÁGINAS
-------
- index.html ........ Início: boas-vindas, apresentação, 6 cartões sobre o
                      que torna o Rio especial, 4 destinos e mini galeria.
- turismo.html ...... Turismo: 4 destinos (Rio de Janeiro, Paraty, Arraial
                      do Cabo e Petrópolis), cada um com uma galeria de 5
                      fotos, e dicas de experiências responsáveis.
- curiosidades.html . Curiosidades: 7 cartões que viram (Cristo Redentor,
                      Pão de Açúcar, mico-leão-dourado, Floresta da Tijuca,
                      praias famosas, carnaval e samba, capital do Brasil)
                      e a janela "O carnaval carioca".
- localizacao.html .. Localização: texto sobre o estado, mapa com os 92
                      municípios (malha do IBGE), rios, cidades e 9 atrativos
                      turísticos clicáveis, e fontes oficiais.
- galeria.html ...... Galeria de Imagens: paisagens, flora e fauna, com
                      foto ampliada ao clicar.

O SITE NÃO USA JAVASCRIPT
-------------------------
Tudo funciona só com HTML e CSS (css/style.css):
- Menu do celular: <input type="checkbox" id="menu-toggle"> + o botão ☰
  (label); o menu abre com :checked.
- Janelas (modal do carnaval), janelas do mapa e foto ampliada da galeria:
  abrem com links href="#id" e o seletor :target; fecham pelo botão × ou
  clicando no fundo escuro.
- Galerias de turismo: botões de rádio (input type="radio") + labels como
  setas ‹ › e miniaturas, usando :checked. A última foto volta para a
  primeira.
- Cartões de curiosidades: viram com :hover e :focus-within (tabindex="0"
  permite usar o teclado).
- body:has(.galeria-modal:target) trava a rolagem com a galeria aberta.

IMAGENS LOCAIS (todas do Pexels)
--------------------------------
imagens/
  carnaval-rio.jpg ................ desfile no Sambódromo (Victor carnevale)

imagens/fauna/
  mico-leao-dourado.jpg ........... mico-leão-dourado (Mohan Nannapaneni)
  tucano.jpg ...................... tucano-de-bico-preto, Mata Atlântica do
                                    Rio de Janeiro (Lucas Alcântara)

imagens/flora/
  floresta-da-tijuca.jpg .......... Parque Nacional da Tijuca (Maksim Shiriagin)
  jardim-botanico.jpg ............. palmeiras-imperiais do Jardim Botânico
                                    (Cláudio Castro)

imagens/paisagens/
  rio-de-janeiro-vista-aerea.jpg .. vista aérea com o Pão de Açúcar (Danilo Marcelino)
  corcovado-cristo-redentor.jpg ... Corcovado e o Cristo (Mak Cézar)
  cristo-redentor.jpg ............. Cristo Redentor (Daniel Maforte)
  copacabana-vista-do-alto.jpg .... Copacabana vista do alto (Evandro Kluge)
  copacabana-por-do-sol.jpg ....... Copacabana ao entardecer (Frans van Heerden)
  pao-de-acucar-por-do-sol.jpg .... Pão de Açúcar ao pôr do sol (Claudio Mota)
  bondinho-pao-de-acucar.jpg ...... bondinho do Pão de Açúcar (Anderson Alves)
  baia-de-guanabara.jpg ........... Pão de Açúcar e Baía de Guanabara
                                    (Vinícius Vieira ft)
  ipanema-por-do-sol.jpg .......... Ipanema ao pôr do sol (Mateus Castro)
  praia-de-ipanema.jpg ............ Praia de Ipanema (Willian Santos)
  escadaria-selaron.jpg ........... Escadaria Selarón (Jonathan Borba)
  arcos-da-lapa.jpg ............... bondinho sobre os Arcos da Lapa
                                    (Anderson Rangel)
  carnaval-sambodromo.jpg ......... baianas no Sambódromo (Lua)
  quiosque-praia-rio.jpg .......... quiosque na orla do Rio (Roy Serafin)
  paraty-centro-historico.jpg ..... centro histórico de Paraty (Ruca Souza)
  arraial-do-cabo-barcos.jpg ...... barcos em Arraial do Cabo (Victor Freitas)
  petropolis-museu-imperial.jpg ... Museu Imperial de Petrópolis
                                    (Luciano Rochadel)

IMAGENS EXTERNAS
----------------
As galerias de turismo (20 fotos) e as janelas do mapa (9 fotos) usam
fotos carregadas direto do Pexels (images.pexels.com). Cada uma mostra o
crédito "Foto: Nome do fotógrafo / Pexels" com link para a página da foto.
Essas fotos só aparecem com internet.

CRÉDITOS
--------
Imagens: Pexels (https://www.pexels.com). Créditos aos respectivos autores.
Contornos dos municípios: malha territorial do IBGE.

COMO ABRIR
----------
Dê um duplo clique em index.html. O site abre no navegador, sem instalar
nada. Mantenha as pastas css/ e imagens/ ao lado dos arquivos .html.
