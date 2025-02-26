# Projeto SPOTIFY

Uma aplicação web simples que permite a busca de músicas, simulando uma funcionalidade do Spotify.

## Funcionalidade

- **Busca de músicas**: Encontre suas músicas favoritas digitando o nome da música ou do artista.

## Tecnologias Utilizadas

- **HTML**: Estruturação das páginas.
- **CSS**: Estilização das páginas para uma interface agradável.
- **JavaScript**: Funcionalidades e interatividade.

## Como Rodar o Projeto

1. Clone este repositório:
    ```bash
    git clone https://github.com/Matheuzinho1/Projeto-SPOTIFY.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd Projeto-SPOTIFY
    ```
3. Desinstale a versão atual do `json-server`:
    ```bash
    npm uninstall -g json-server
    ```
4. Instale a versão 0.17 do `json-server`:
    ```bash
    npm install -g json-server@0.17
    ```
5. Inicie o servidor JSON:
    ```bash
    json-server --watch API/Artists.json
    ```
6. Abra o arquivo `index.html` em um navegador para ver a aplicação em execução.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações, abra uma Issue. Obrigado!
