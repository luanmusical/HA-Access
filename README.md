# HA-Access

Programa para Windows, totalmente acessível por leitor de tela, que faz duas coisas com o [Home Assistant](https://www.home-assistant.io/) — pensado desde o início para o [NVDA](https://www.nvaccess.org/):

- **Controla a casa** por teclado e com retorno falado: aparelhos por cômodo (Espaço liga e desliga, Ctrl+setas ajustam volume, brilho, temperatura e canal), pessoas, cenas, scripts e automações (criar e remover), notificações, integrações, aplicações (add-ons) e a parte de sistema do Home Assistant (configuração geral, reparos, backups, usuários, reiniciar).
- **Coloca este computador dentro do Home Assistant**: sensores (janela ativa, volume, microfone e câmera em uso, processador, memória, bateria e muitos outros), comandos (bloquear, desligar a tela, suspender, rodar programas...), notificações com botões e resposta, e o player de mídia do Windows.

Tudo tem nome para o leitor de tela, toda ação é falada e o foco sempre volta para onde estava. Tema escuro.

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)** deste repositório. O pacote já vem pronto pra rodar no Windows — não precisa instalar Python nem compilar nada. O programa se atualiza sozinho pelas Releases.

Cada Release traz as notas da versão com o hash **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali — cópias obtidas por qualquer outro canal não têm garantia de integridade.

## Requisitos

- Windows 10/11 (64 bits).
- Um Home Assistant na rede (ou por endereço externo: Nabu Casa, túnel da Cloudflare), com um usuário administrador.
- Para o computador aparecer no Home Assistant: a integração **[HA-Access-Integration](https://github.com/luanmusical/HA-Access-Integration)** (código aberto; o programa instala sozinho se o Home Assistant tiver o HACS). Também funciona pelo MQTT.
- [NVDA](https://www.nvaccess.org/) é o leitor de tela com suporte principal (o programa também fala pelo System Access e pela voz do Windows).

## Manual

O manual completo, em English/Français/Español/Português, vem incluso dentro do zip do programa e também disponível como arquivo separado na página de Releases.

## Licença

Veja [LICENSE](LICENSE) para termos de uso e créditos de terceiros.
