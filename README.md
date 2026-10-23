# Questbound — Releases

Instaladores do **Questbound**, um VTT (Virtual Tabletop) modular e offline-first.

Este repositório publica só as releases (instaladores e o manifesto de atualização automática).
O código-fonte fica em outro repositório, privado.

## Instalar

Baixe o instalador do seu sistema na página de [Releases](../../releases):

- Linux: `.AppImage` ou `.deb`
- macOS: `.dmg`
- Windows: `.msi`

O Alpha ainda não tem assinatura de código dos sistemas, então o Windows (SmartScreen) e o macOS (Gatekeeper)
avisam na primeira abertura. Isso é esperado nesta fase.

## Atualização automática

O app instalado consulta a release fixa `updater` (arquivo `latest.json`) e avisa quando há versão nova.
As atualizações são assinadas; o app só instala o que foi assinado com a chave do projeto.
Não apague a release `updater`.
