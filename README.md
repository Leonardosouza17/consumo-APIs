# consumo-APIs
Repositório para as demonstrações e aprendizado sobre o consumo de APIs.

As APIs possuem algun elementos que servem à sua utilização:

- **Ponto de Entrada**: Endereço do serviço hospedado e que pode ser acessado através de um navegador ou uma ferramenta de consumo de APIs. Exemplo: <https://dadosabertos.camara.leg.br/api/v2>.
- **Recursos**: São serviços de dados disponíveis para consumo.
Exemplo: /deputados -> <https://dadosabertos.camara.leg.br/api/v2/deputados>.
- **Parâmetros**: são informações ou filtros que servem para enviar dados da pesquisa da consulta ou para serem processados pela API. Os parâmetros podem ser acessados para a API da URL ou no corpo (body) da requisição. Exemplo: ?nome=bebeto -> <https://dadosabertos.camara.leg.br/api/v2/deputados?nome=bebeto>.
- **Métodos**: são os modos de consumo de uma API, que podem ser:

    -POST: inserção (CREATE)
    -GET: consulta/leitura (READ)
    -UPDATE: atualizaçâo (UPDATE)
    -DELETE: deleção (DELETE)

Para este projeto vamos usar o Node.js e o NPM (Node Package Manager):
- Node.js v20.13.0 LTS - Long Term Suport (versão estável)

NPX -> Node Package eXecuter (Executor de pacote do Node)

TO-DO (documentar):
- Instalação e uso do Json Server: <https://github.com/typicode/json-server>
- Criação do .gitignore
- Utilidade dos arquivos package
- Criação do script "start" no package.json
- Observações em relação do uso do JSON5 vs. JSON: <https://github.com/json5/json5>
- Instalação das extensões para a formatação de arquivo .json5
- Chamada do script start com NPM ao invés do NPX

- O que é o Chocolatey (e porque não instalá-lo agora)

**Chocolatey**: é um gerenciador de pacotes para Windows. Ele foi projetado para ser uma estrutura descentralizada para instalar pacotes (aplicativos/ferramentas) mais rapidamente. O Chocolatey é construído sobre a insfraestrutura do NuGet, que atualmente usa o PowerShell por debaixo do capô.

- **Características do Chocolatey**: 
- Facilidade na instalação de pacotes;
- Similaridade com os gerenciadores de pacotes do linux "apt" e "yum";
- Uso simples;
- Possui abordagem automatizada;
- Universal para gerenciar todos os softwares do Windows, entre outras. 




