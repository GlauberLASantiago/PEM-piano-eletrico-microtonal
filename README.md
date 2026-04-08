Piano Elétrico Microtonal (24-TET)

Uma aplicação web interativa que traz a magia dos quartos de tom para o timbre clássico do Piano Elétrico. Este projeto divide cada oitava em 24 intervalos perfeitamente matemáticos (24-TET), permitindo a exploração de harmonias e melodias fora da escala cromática ocidental tradicional.

✨ Funcionalidades

Teclado Microtonal: Layout com duas oitavas completas. As teclas azuis auxiliares estão posicionadas entre as teclas tradicionais, representando os quartos de tom.

Timbre Realista: Utiliza a biblioteca soundfont-player para carregar amostras de áudio de alta qualidade de um Piano Elétrico.

Motor de Áudio Customizado: Lógica de decay e release programada diretamente com a Web Audio API para um decaimento natural do som (travado num máximo de 3 segundos para maior realismo).

Controlos de Execução: Suporte integrado para ecrãs táteis (multitoque e deslize), rato e teclado do computador (mapeamento QWERTY linear).

Interface Moderna: Design responsivo, escuro e minimalista construído com Tailwind CSS.

🚀 Como Usar

Como o projeto é construído inteiramente com tecnologias web front-end (HTML, CSS e Vanilla JavaScript), não é necessária qualquer instalação complexa ou servidor back-end.

Faça o clone deste repositório:

git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)


Navegue até à pasta do projeto no seu computador.

Abra o ficheiro index.html em qualquer navegador web moderno (Chrome, Firefox, Edge, Safari).

Clique no botão "Carregar Motor de Áudio" para inicializar a Web Audio API e baixar o timbre de piano elétrico.

⌨️ Mapeamento do Teclado (QWERTY)

Pode utilizar o teclado do seu computador para tocar as notas. O mapeamento segue um padrão linear contínuo abrangendo as várias fileiras do teclado:

Fileira inferior: Z, X, C, V, B...

Fileira central: A, S, D, F, G...

Fileira superior: Q, W, E, R, T...

Fileira de números: 1, 2, 3, 4, 5...

🛠️ Tecnologias Utilizadas

HTML5 / CSS3

JavaScript (ES6+)

Web Audio API nativa do navegador

Tailwind CSS (via CDN para estilização rápida)

Soundfont-Player (para carregamento e reprodução de fontes sonoras MIDI)

👨‍🏫 Créditos

Desenvolvido pelo professor Glauber Santiago — DAC/UFSCar.


