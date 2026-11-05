# AndromedaHosts

Aplicativo para Windows para administrar hosts: **conexões remotas** (SSH, Telnet e SFTP, no estilo de um cliente de terminal), **VPN** escolhida só para o módulo de conexões remotas e um **cofre de senhas** criptografado que acompanha as conexões.

Este repositório existe **só para distribuir os instaladores e as atualizações** do app (aba **Releases**). Ele não contém código-fonte, não aceita contribuições e não oferece suporte por aqui: Issues, Wiki e interações de terceiros estão desligadas.

## Instalação

1. Em **Releases**, baixe o `AndromedaHosts_<versão>_x64-setup.exe` da versão mais recente.
2. Execute o instalador. O Windows pode mostrar o aviso "O Windows protegeu o computador" (o instalador ainda não tem certificado de editora): clique em **Mais informações** e depois em **Executar assim mesmo**.
3. Ao abrir, entre com o Google ou crie uma senha mestra, que protege no seu computador as credenciais que você salvar.

## Atualizações

O app verifica novas versões sozinho e só instala se a assinatura do instalador conferir com a chave pública que já vem dentro dele. Cada versão publicada traz um `latest.json` com essa assinatura.

## Aviso

Software em fase de testes, fornecido "no estado em que se encontra", sem garantia de qualquer tipo.
