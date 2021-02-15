---
title: "Command-Line Pack (Código-fonte)"
program_name: "Command-Line Pack"
author: "Neill Corlett"
group: ""
category: "Outros"
platform: "Multiplataforma"
system: "Vários"
language: "Inglês"
release_date: "25/05/2011"
version: "1.01"
site: "http://www.neillcorlett.com/cmdpack/ (fora do ar)"
---
Conjunto de utilitários desenvolvidos por <b>Neill Corlett</b> ao longo dos tempos, muitos são novos e todos agora são licenciados pela GPL v3 (ou posterior). Segue uma breve descrição dos programas novos mais interessantes:

- <b>bin2iso</b>: converte imagens BIN (até 2352 bytes por setor) em ISO9660, apesar de não fazer o trabalho contrário, avisa caso haja perda de dados (modo 2 formato 2, vulgarmente conhecido como o formato de playstation);

- <b>brrrip</b>: extrai as amostras de som do tipo "Bit Rate Reduction", das ROMs de SNES ou arquivos SPC descomprimidos, podendo criar uma saída em WAV com qualquer taxa de som;

- <b>cdpatch</b>: extrai e insere (não foi testado nem se sabe o resultado com arquivos de tamanho diferentes, mas o autor dá a entender que funciona) arquivos de imagens binárias (até 2352 bytes por setor) ou ISO9660, também conseguindo lidar com o "formato de playstation";

- <b>hax65816</b>: um disassembler simples de 65816 (programa para interpretar as instruções em binário), foi usado em projetos como a tradução de Seiken Densetsu 3 (Secret of Mana 2);

- <b>rels</b>: programa de busca relativa, capaz de tratar curingas para buscas de 16 bits e afins;

- <b>screamf</b>: programa para converter do formato AMF (usado em antigos jogos de DOS, sendo um MOD convertido) para S3M (um formato da linha do MOD, mais conhecido e suportado);

- <b>vb2rip</b>: programa para extrair sons (músicas, se você der sorte) no formato VAB (não trata o SEQ, que é um pacote de VABs), VB2 (VAB do PlayStation 2) e alguns derivados similares. É possível definir a taxa de saída em WAV, assim como no brrrip;

<b>Atenção</b>: este código-fonte NÃO é a distribuição original! Foi removida a estrutura de diretórios e o "mkgcc" genérico, e adicionado um arquivo "Makefile" para facilitar o processo de compilação.

<b>Nesta nova versão 1.01</b>: recolocada a opção de execução simples no ecm (também como unecm), para que funcionasse novamente com o ambiente de arrastar os arquivos para o programa do Windows e similares.
