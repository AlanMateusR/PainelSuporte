# PainelSuporte HTML
Projeto HTML desenvolvido para automação de coleta de dados em CRM a base de Web-Scraping. O RPA utilizado foi UI.VISION sendo assim, é necessário obter aplicação instalada e scripts (MACRO) devidamente exportados e contidos no mesmo diretório do HTML. 

- 👉Programa desenvolvido para fins de aprendizado e de utilidade interna da equipe.

- OBS, no modelo original os botões "buscar" contém chamada href para pagina do google, os mesmos devem ser substituidos pelo link de chamada do MACRO exportada da aplicação UI.VISION

- Documento UI.Vision: https://ui.vision/rpa/docs

- A partir da V6.1.1, o recurso “Exportar para HTML (Autorun)” foi substituído pelo melhor recurso “Criar HTML de execução automática”. Se você selecioná-lo, duas páginas HTML serão criadas:

ui.vision.html - este arquivo é sempre o mesmo para cada macro. Ele cuida de iniciar a extensão UI Vision.

start-macroname.html - este arquivo é quase sempre o mesmo. A única diferença é o link da linha de comando incorporado. Ele contém o nome da macro (abra o arquivo HTML e você entenderá facilmente!). Para executar a macro, abra este arquivo em um navegador. Funciona como um link de atalho. Chama ui.vision.html que inicia a extensão. Claro, você também pode usar a linha de comando incorporada 20 diretamente. o “start-macroname.html” destina-se principalmente como ajuda para “iniciantes em linha de comando” :wink:

Dentro de start-macroname.html apenas a parte em negrito muda para cada macro:

id=“run” href=“ui.vision.html?direct=1&savelog=log.txt&macro=Demo/Core/DemoAutofill.json”>Click here

<img src="https://forum.ui.vision/uploads/db8324/original/2X/f/fc0946ea644075f16a2e82eaf692c0a031bc6921.png" />



👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇



<img src="https://imgur.com/cpRQCks.png"/>


<img src="https://imgur.com/PPm9ikO.png"/>

<img src="https://imgur.com/50CHuTJ.png"/>
