Funcionamento:
É feita uma imagem com poucos pixels atraves do paint e salva em uma pasta que é referida na string file. <br>
Em letras, é posto o nome dos arquivos de imagem que serão lidos, e em compiler é definido se o código gerado será em python para ser usado no testador, ou em VHDL para sua implementação direta.<br>
Ao rodar o código, é gerado um código para a implementação das imagens lidas, sempre considerando que o tamanho de cada pixel da imagem lida pode representar diferentes numeros de pixels na implementação, sendo esse numero representado por SIZE no codigo gerado