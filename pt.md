# REMOTE DNA — Política de privacidade

[English](./) · [العربية](ar.html) · [Français](fr.html) · [Español](es.html) · [中文](zh.html)

> Esta é uma tradução. Em caso de diferença, vale o [texto em inglês](./).

**Data de vigência:** 18 de agosto de 2026 · **Última atualização:** 17 de outubro de 2026

O REMOTE DNA («o App») é um controle remoto universal para TVs e
ares-condicionados, publicado pela **Solar AI Systems** (Mohamed Khocha),
Argélia.

Esta política descreve exatamente o que o App coleta e o que não coleta. Ela é
mantida em dia com a versão publicada.

## Resumo

- Tudo de que você precisa para controlar seus aparelhos funciona **sem
  internet**, no seu celular.
- O App funciona **sem conta**. A conta é opcional e serve só para recuperar uma
  licença Pro paga em um celular novo.
- Nunca vendemos seus dados nem os usamos para perfis de publicidade.

## 1. Dados que ficam só no seu aparelho

O seguinte nunca sai do seu celular:

- Seus aparelhos salvos, seus conjuntos de códigos e qualquer botão que você
  ensinou ao App («Ensinar minha TV», «Consertar um botão»).
- As preferências de idioma, tema e boas-vindas. Até você escolher um idioma, o
  App segue o idioma do seu celular, lido no próprio aparelho.
- Sua chave de licença Pro e seu token de acesso (no Android Keystore, com
  armazenamento criptografado).
- Os dados de pareamento Wi‑Fi das suas TVs: a chave que uma TV LG ou Samsung
  entrega quando você aceita a conexão e, na Android TV, um certificado de
  cliente gerado no Android Keystore junto com a impressão do certificado da TV.
  Eles permitem reconectar sem perguntar de novo e só são usados na sua rede
  doméstica.

Desinstalar o App apaga tudo isso.

## 2. Conta opcional

Se — e somente se — você criar uma conta, guardamos no nosso servidor:

- Seu **e-mail**.
- Um **hash criptográfico** da sua senha (PBKDF2-HMAC-SHA256). Nunca guardamos
  nem vemos sua senha real.
- A data de criação da conta e a licença Pro vinculada a ela.

Finalidade: recuperar sua licença Pro em um celular novo e redefinir sua senha.

Os **e-mails de redefinição de senha** são enviados pelo Resend (resend.com). Só
são transmitidos seu e-mail e um código temporário de 6 dígitos.

Você pode pedir a exclusão da sua conta a qualquer momento — veja a seção 8.

## 3. Pagamentos

O Pro é uma compra única. A forma de pagamento depende de onde você instalou o
App, e esta seção informa o processador de pagamento em cada caso.

- **Se você instalou o App pelo Google Play** — a única forma de compra dentro do
  App é o **Google Play Billing**, gerenciado pelo RevenueCat, que identifica sua
  compra com um identificador anônimo. Não recebemos dados de cartão.
- **Se você instalou o App direto do nosso site** (a versão distribuída fora do
  Google Play) — o pagamento é processado pela **Chargily Pay** na própria página
  segura dela. Os dados do seu cartão são digitados no site da Chargily e
  **nunca são vistos, processados nem guardados pelo App ou por nós**. A Chargily
  nos envia a referência, o valor e o status da transação, e a política de
  privacidade dela vale para o que você digita lá. Essa forma não é oferecida na
  versão do Google Play.

Nos dois casos guardamos só a referência, o valor, o status da transação e a
chave de licença emitida.

## 4. Publicidade

A versão gratuita mostra anúncios do **Google AdMob**:

- um **anúncio ao abrir** o App (nunca na primeira abertura e, ao voltar do
  segundo plano, só depois de uma ausência longa);
- de vez em quando um **anúncio em tela cheia entre telas**;
- um **vídeo curto com recompensa** a cada três usos de «Consertar um botão».

Entre dois anúncios em tela cheia há sempre pelo menos três minutos. Não há
banners. Se nenhum anúncio puder ser mostrado, o App continua sem ele.

- Os anúncios são pedidos só com a **classificação «G» (livre)** e começam
  **sem som**.
- No EEE, no Reino Unido e na Suíça, um **formulário de consentimento (Google
  UMP)** aparece antes de qualquer pedido de anúncio, e sua escolha é respeitada.
- O AdMob pode processar identificadores do aparelho para exibir anúncios e
  limitar sua frequência, conforme a
  [política de privacidade do Google](https://policies.google.com/privacy).
- **Usuários Pro não veem nenhum anúncio**, e nenhum pedido de anúncio é feito
  para eles.

## 5. Contribuição opcional de códigos (a «rede genética»)

Ela fica **desligada por padrão** e exige seu consentimento explícito.

Se você ativar e escolher compartilhar os códigos de um aparelho, recebemos:

- O protocolo infravermelho, o endereço e os códigos dos botões desse aparelho.
- A marca ou o modelo que você digitou, e a versão do App.
- Um **identificador aleatório gerado no seu aparelho na instalação** — usado só
  para contar colaboradores diferentes, para que os códigos sejam validados por
  maioria.

Isso **não contém nome, e-mail, telefone, localização nem identificador de
publicidade**, e não pode ser ligado a você. Você pode desligar a contribuição
quando quiser nas configurações.

## 6. Relatórios de falhas

Relatórios de falhas anônimos são enviados ao **Sentry** (região de dados da UE)
**só quando o App falha**. Um relatório contém o erro técnico, a versão do App e
o modelo e a versão do sistema do aparelho. Informações pessoais estão
desativadas explicitamente, e os relatórios nunca são usados para publicidade.

## 7. Permissões

- `TRANSMIT_IR` — para emitir sinais infravermelhos pelo emissor IR do seu
  celular. São pulsos de luz em um só sentido e não carregam informação pessoal.
- `CAMERA` — usada **só** quando você escolhe «Importar por QR» para escanear um
  código de aparelho compartilhado, ou «Buscar pelo modelo» para ler o número do
  modelo na etiqueta de um aparelho. Tudo é processado no seu aparelho: a foto de
  uma etiqueta é **apagada assim que é lida**, e **nenhuma foto ou vídeo é
  guardado ou enviado**. Você pode negar, e todo o resto continua funcionando.
- **Escolher uma foto** — em «Buscar pelo modelo» você também pode escolher uma
  foto da etiqueta que já tirou. O seletor de fotos do Android entrega ao App só
  essa foto, sem permissão de armazenamento; ela é lida no seu aparelho, a cópia
  feita para a leitura é apagada e nada é enviado.
- `INTERNET` — só é necessária para os recursos opcionais acima (conta,
  pagamento, anúncios, relatórios de falhas, atualizações do catálogo). Todas as
  funções de controle funcionam com a rede desligada.
- **Descoberta na rede local** — quando você usa o controle por Wi‑Fi, o App
  procura Smart TVs na sua própria rede (SSDP/DIAL e mDNS) e, quando você digita
  o endereço IP de uma TV, verifica quais portas de controle respondem nesse
  único endereço para reconhecer o sistema dela. Ele só conversa com o aparelho
  que você escolhe, e esse tráfego fica dentro da sua rede doméstica.
- `AD_ID` (identificador de publicidade) — declarado pelo Google AdMob para os
  anúncios descritos na seção 4. Usuários Pro não fazem pedidos de anúncio.

O App **não** pede permissões de microfone, localização, contatos, telefone, SMS
nem armazenamento de arquivos.

## 8. Seus direitos e a exclusão de dados

- **Apagar os dados locais:** desinstale o App ou limpe os dados dele nas
  configurações do Android.
- **Excluir sua conta e tudo o que está ligado a ela** (e-mail, hash da senha,
  vínculo com a licença): no App, abra **Eu → Conta → Excluir a conta para
  sempre**. O registro é apagado na hora, sem pedido e sem espera. Uma licença
  Pro que você pagou é **desvinculada, nunca revogada**: a chave continua
  valendo e pode ser ativada de novo. Se você não conseguir abrir o App,
  escreva para o endereço abaixo a partir do e-mail da conta e nós a apagaremos
  em até 30 dias.
- **Retirar o consentimento para contribuir códigos:** desligue nas
  configurações. Os códigos compartilhados antes são anônimos e não podem ser
  ligados a você.

## 9. Crianças

O App é uma ferramenta para todos os públicos. Ele não é voltado a crianças e
não coletamos dados delas conscientemente.

## 10. Mudanças

Se uma versão futura mudar estas práticas, esta política é atualizada **antes**
de essa versão ser publicada, e o link do App aponta para o texto revisado.

## 11. Contato

Dúvidas, pedidos de exclusão de dados ou qualquer outra coisa:

**solar.ai.systems@gmail.com**

Solar AI Systems — Argélia
