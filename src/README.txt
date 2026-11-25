PROJETO: BIBLIOTECA DIGITAL

Como abrir no IntelliJ IDEA:
1. Extraia o arquivo ZIP.
2. Abra o IntelliJ IDEA.
3. Clique em Open e selecione a pasta BibliotecaDigital.
4. Aguarde o IntelliJ reconhecer o projeto.
5. Abra src/Main.java.
6. Clique na seta verde ao lado do metodo main e escolha Run 'Main.main()'.

Arquivos:
- ItemBibliotecaDigital.java: classe abstrata com titulo, autor e descricao().
- Baixavel.java: interface com o metodo baixar().
- Visualizavel.java: interface com o metodo visualizar().
- Ebook.java: herda ItemBibliotecaDigital e implementa Baixavel.
- VideoDigital.java: herda ItemBibliotecaDigital e implementa Baixavel e Visualizavel.
- Main.java: cria objetos, exibe descricoes, simula downloads e visualizacao e demonstra polimorfismo.

Observacao:
Todos os arquivos estao no pacote padrao (sem declaracao package), para facilitar a abertura e execucao.
