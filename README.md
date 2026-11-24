# Nyrox · FiveM e desenvolvimento web

[Descarregar o portfólio completo](./Nyrox-Portfolio.zip). Extrai o ZIP para navegar pelas pastas indicadas abaixo.

Seleção de código e interfaces da base de roleplay e de projetos web. Os recursos FiveM incluem integrações vRP e dependências de terceiros, com os créditos originais nos respetivos ficheiros.

| Projeto | O que explorar |
| --- | --- |
| **Base FiveM** · `fivem/base/` | Configuração do servidor, ordem de arranque dos recursos e identidade visual QUINAS RP. |
| **Recursos de roleplay** · `fivem/recursos/` | Hospital Maralto, elevadores, contentores, blackjack, administração e módulos vRP. |
| **Smartphone** · `fivem/recursos/smartphone/` | Interface do telemóvel, integração com o banco e testes da comunicação entre cliente e servidor. |
| **FM Audio** · `sites/fm-audio/index.html` | Leitor de música local com controlos de áudio para utilização com um transmissor FM. |
| **Probabilidades** · `sites/probabilidades/` | Calculadora educativa e normalização de dados de três fornecedores. Inclui testes do serviço e da interface. |
| **Academia Automóvel** · `sites/academia-automovel/` | Cinco páginas HTML de aprendizagem de mecânica e eletromecânica, incluindo desafios e versões para telemóvel. |

## Executar os projetos web

Abre o ficheiro HTML de FM Audio ou da Academia Automóvel no navegador. Em Probabilidades, abre `app.html` para explorar a interface. A consulta a fornecedores externos requer o serviço e credenciais próprias.

## Verificar o código

Na pasta `sites/probabilidades`, executa `npm run build` e `npm test`. Na pasta `fivem/recursos/smartphone`, executa `node --test tests/*.test.cjs`.

## Âmbito da base

Esta seleção documenta o trabalho de integração. Para executar uma cidade são necessários FXServer, a configuração privada, a base de dados e os recursos externos referidos nos manifestos, incluindo os modelos e o áudio usados pelo blackjack.
