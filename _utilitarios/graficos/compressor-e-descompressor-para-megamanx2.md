---
title: "Compressor e descompressor para Megaman X 2"
program_name: "Compressor e descompressor para Megaman X 2"
author: "denim"
group: "Monkey's Traduções"
category: "Gráficos"
platform: "Windows"
system: "Super Nintendo"
language: "Português"
release_date: "06/08/2013"
version: "1.0"
site: "http://www.monkeystraducoes.com/ (fora do ar)"
---
Este conjunto de ferramentas possui a finalidade de descomprimir e comprimir gráficos para o jogo <b>Megaman X 2</b> do sistema Super Nintendo.

<b>MODO DE USAR</b>:

Existem dois programas: o compressor e o descompressor. Ambos são executados através de linha de comando. Há dois arquivos <i>batch</i> de exemplo.

- Descompressor: para usar o compressor a sintaxe é a seguinte: <b>descompressor.exe -i</b>. O parâmetro deverá ser modificado para o caminho completo de onde encontra-se a rom, bem como o seu nome. Exemplo prático: Supondo que a o arquivo da rom seja megamanx2.smc e esteja em C:\roms. Você deverá utilizar o seguinte comando: <b>descompressor.exe -i "c:\roms\megamanx2.smc"</b>. Após a execução do programa serão criados diversos arquivos com os gráfico descomprimidos na pasta 'arquivos'. Será gerado também um arquivo chamado log.txt. IMPORTANTE: Não altere ou apague os conteúdos deste arquivo.

- Compressor: após a edição realizada nos gráficos, é necessária a inserção dos mesmos na ROM novamente. Para isso, utilize o programa compressor, cuja sintaxe é: <b>compressor.exe [-p ]</b>. A opção <b>-p</b> é opcional. Ela indica a posição na ROM para quem deseja inserir os dados comprimidos, seguido do tamanho máximo disponível para a área de dados. Esta opção deve ser utilizada caso a compressão seja insuficiente e seja necessária a expansão da ROM. O valor do ponteiro deve ser dado no endereçamento do SNES, LOROM. O tamanho deve ser dado em hexadecimal, sem prefixos do tipo <b>0x</b> ou <b>$</b>.
