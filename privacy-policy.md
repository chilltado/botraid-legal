---
title: Privacy Policy — BotRaid
---

# Privacy Policy

**BotRaid: Robot Puzzle Battles** (Android app `com.chilltado.botconquest`)
Developer: chilltado, independent developer based in Brazil
Contact: chilltadolab@gmail.com
Last updated: 28 October 2026

[Leia em português (Brasil)](#pt)

---

## Summary

- **No account with us and no server of ours.** Your game is saved on your device.
- **Ads** come through **Unity LevelPlay**, with **Google AdMob**, **Unity Ads** and **Liftoff (Vungle)**. These companies use your advertising ID and device data to show and measure ads.
- **Google Firebase** measures how the game is played (Analytics), reports crashes (Crashlytics) and sends game settings (Remote Config).
- **Google Play Games** (optional): sign-in, a stars leaderboard, achievements and a cloud backup of your save, kept in your Google account.
- **Purchases** go through **Google Play**. The game remembers on your device that you have bought something; that changes some game rules, described in section 6.
- **Reminders** are local notifications you can turn off.
- In the EEA, UK and Switzerland, personalised ads, analytics and crash reports stay **off until you agree**.

---

## 1. Data on your device

The game saves on your device, in the app's private storage:

- your progress: robots, parts, crystals, gold, campaign, season, missions and settings;
- a device identifier that Unity derives from Android's device ID, stored in the save;
- the Google Play order IDs of your purchases and a "has paid" flag;
- your privacy choices (with the date), reminder settings and local backup copies of the save.

Other apps cannot read it. It is removed when you uninstall the game or clear its storage.

---

## 2. Google Play Games (optional)

Linking is offered in **Settings → Link Google account** and on the leaderboard screen. The game never uploads anything for a player who has not linked. Once you link, the game signs you in automatically on later launches. Google's Play Games SDK is initialised at start, and Google may recognise your Play Games profile on its own.

If you link:

- your **Play Games player ID, display name and avatar** are used for the leaderboard and the cloud save;
- your **total campaign stars** go to a public leaderboard, next to your Play Games name;
- **achievements** (18) are reported to your Play Games profile;
- a **copy of your save** (including the device identifier and order IDs above) and backup copies are stored in **Saved Games**, in your Google account.

**Settings → Sign out** backs up your save to your Google account and removes it from this device; the cloud copy stays. To delete the cloud copy, the leaderboard entry and achievements, see section 10.

---

## 3. Advertising

The game shows a bottom banner, interstitial ads between boards and optional rewarded videos. **No Ads** turns off banner and interstitial ads.

The ad companies collect: advertising ID, app set ID, IP address and the approximate location derived from it, device information (model, OS, language, screen, network), ad interactions (impressions, clicks, video completion) and SDK diagnostics. They use it to show, measure and (if allowed) personalise ads, to limit repetition and to prevent fraud, under their own policies, and may pass ad requests to their advertising partners. Ads are not loaded on Android versions older than 9.

---

## 4. Firebase: analytics, crash reports and remote settings

**Firebase Analytics** records, with a random app-instance ID (no name, no email, no account):

- your progress: tutorial completed, career steps, territory held, milestone boards;
- each board: started, finished or skipped, with world, difficulty, result, time, stars, whether auto-play was on and how many parts you own and their levels;
- screens opened;
- ads: each attempt (placement, format, outcome) and whether a rewarded video was watched to the end;
- store offers opened and bought;
- what Firebase records by itself: first open, sessions, app updates, in-app purchases, country, device model, OS and app version. On Android, Firebase can also read the advertising ID.

**Firebase Crashlytics** sends crash and error reports: stack trace, device model, OS, app version, a Crashlytics installation ID, recent log lines and four game counters (boards on the field, boards held, roster size, career step).

**Firebase Remote Config** downloads game settings (balance, ad frequency, offers, event switches) **at every launch, before any consent question**. To do so it sends a Firebase installation ID, the app version and device locale. It does not send gameplay data.

We see analytics as reports and can inspect events per app-instance ID; we cannot link them to your name or Google account.

---

## 5. Purchases

In-app purchases (crystal packs, No Ads, Special Offer, season packs) are processed by **Google Play Billing** through Unity IAP. We never see your payment card, billing address or Google account. The game receives the order ID, keeps it on your device and in the cloud save, and checks it on the device; there is no purchase server of ours. Refunds follow Google Play's refund policy.

---

## 6. Gacha odds and the supporter bonus

- Part crates give random parts. **Show crate odds** in the store lists the odds of each rarity before you open a crate. Pity guarantees a high rarity after a set number of pulls, and target robots steer which robot's parts drop.
- **Supporter bonus.** If you have ever made a real purchase, the game raises the chance of Rare and better parts: their weights are multiplied by **1.5** (a value we can change with Remote Config, or switch off). With the default weights the odds become about 57.0 / 32.1 / 7.7 / 2.6 / 0.64 % instead of 66.5 / 25.0 / 6.0 / 2.0 / 0.5 % (Standard / Rare / Epic / Prototype / Legendary). The odds shown to a supporter already include the bonus and say so.
- The same "has paid" flag also lets us set a shorter wait between ads for paying players (Remote Config).
- The season **Order Crate** uses the base rarity weights (no supporter bonus).

This uses only the flag on your device; it is not sent to us.

---

## 7. Reminders

The game can schedule **local notifications**: daily parts and missions, streak, boss window and a reminder after 7 days away. Android asks your permission first. Turn them off in **Settings → Reminders** or in Android settings. No push server is used.

---

## 8. Other Google Play services

The game uses Google Play In-App Review (rating prompt), In-App Update, Play Asset Delivery (downloading game content) and the Install Referrer (how the app was installed, read by the SDKs).

---

## 9. Consent and your choices

- **EEA, EFTA, UK and Switzerland** (by your device's region setting, or when it is unknown): before ads start, a screen asks whether partners may use your advertising ID and activity to personalise ads. Until you agree, **analytics and crash reports are off**; if you refuse, ads are non-personalised and analytics and crash reports stay off.
- **Everywhere:** **Settings → Privacy → Change ad privacy choice** reopens that screen. Refusing there turns off personalised ads, analytics and crash reports. Remote Config keeps working.
- **United States:** **Settings → Privacy → Sharing of your information** tells the ad networks not to sell or share your information. It does not turn off analytics or crash reports; use "Change ad privacy choice" for that. We do not sell personal information for money.
- **Advertising ID:** in Android settings (**Privacy → Ads**) you can delete or reset it.
- **Reminders and Play Games** are opt-in.

Legal bases (GDPR, UK GDPR, LGPD): consent for personalised ads, analytics and crash reports where the law requires it; legitimate interest for non-personalised ads, Remote Config, analytics and crash reports elsewhere, and fraud prevention; contract for purchases and the cloud save.

---

## 10. Deleting your data

- **On this device:** uninstall the game, or Android **Settings → Apps → BotRaid → Storage → Clear storage**. The game has no in-app "delete everything" button.
- **Cloud save, leaderboard and achievements:** Google Play Games app → **Settings → Delete Play Games account & data** (for BotRaid only, or all games), or <https://myaccount.google.com/> → Data & privacy.
- **Analytics and crash reports:** turn them off with **Change ad privacy choice**. What was already collected is tied to a random ID, not to you, so we usually cannot find it; it is deleted automatically when its retention ends: 90 days for crash reports, and the retention period set in our Google Analytics settings for analytics (at most 14 months). You can still email us and we will do what we can.
- **Advertising data:** delete or reset your advertising ID and use the ad companies' own forms.

We will answer requests within 15 days.

---

## 11. Third parties

| Service | Role | Privacy policy |
| --- | --- | --- |
| Unity LevelPlay, Unity Ads (Unity Technologies, incl. ironSource Ads) | ad mediation and ads; engine diagnostics | <https://unity.com/legal/game-player-and-app-user-privacy-policy> |
| Google AdMob | ads | <https://policies.google.com/technologies/partner-sites> |
| Liftoff Monetize (Vungle) | ads | <https://liftoff.io/privacy-policy/> |
| Google Firebase (Analytics, Crashlytics, Remote Config) | measurement, crash reports, settings | <https://firebase.google.com/support/privacy> |
| Google Play, Play Games, Play Billing | download, sign-in, leaderboard, cloud save, purchases | <https://policies.google.com/privacy> |

These companies may process data outside your country, including in the United States.

---

## 12. Children

BotRaid is for a general audience and is **not directed to children under 13**. The game tells the ad networks it is not child-directed. We do not knowingly collect personal information from children under 13 (or the minimum age in your country). If you believe a child's data was collected, contact us and we will help remove it.

---

## 13. Security

Data stays in the app's private storage, the cloud save in your Google account, and the services send data over HTTPS. No method is completely secure.

---

## 14. Your rights

Depending on where you live (GDPR, UK GDPR, LGPD, US state laws), you may have the right to access, correct, delete or port your data, to object or restrict processing, to withdraw consent and to opt out of targeted advertising. Contact chilltadolab@gmail.com. You may also complain to your data protection authority (in Brazil, the ANPD).

---

## 15. Permissions

Internet and network state; Google Play billing; advertising ID and Android ad-services (attribution, topics); basic phone state (non-sensitive, used by an ad SDK); install referrer; notifications (reminders); wake lock and foreground service (data sync, used by Play Asset Delivery downloads); Amazon device attestation (ad SDK, Amazon devices only). No location, contacts, camera, microphone, photos or files.

---

## 16. Changes

We publish changes at this address and update the date above, before the app update that needs them.

---

## 17. Contact

chilltado — chilltadolab@gmail.com

---

<a id="pt"></a>

# Política de Privacidade (português)

**BotRaid: Robot Puzzle Battles** (app Android `com.chilltado.botconquest`)
Desenvolvedor: chilltado, desenvolvedor independente no Brasil
Contato: chilltadolab@gmail.com
Atualizada em: 28 de outubro de 2026

---

## Resumo

- **Sem conta conosco e sem servidor nosso.** Seu jogo fica salvo no aparelho.
- **Anúncios** vêm pelo **Unity LevelPlay**, com **Google AdMob**, **Unity Ads** e **Liftoff (Vungle)**. Essas empresas usam seu ID de publicidade e dados do aparelho para mostrar e medir anúncios.
- O **Google Firebase** mede como o jogo é jogado (Analytics), relata falhas (Crashlytics) e envia configurações do jogo (Remote Config).
- **Google Play Games** (opcional): login, placar de estrelas, conquistas e backup do save na nuvem, guardados na sua conta Google.
- **Compras** passam pelo **Google Play**. O jogo guarda no aparelho que você já comprou algo; isso muda algumas regras do jogo, descritas na seção 6.
- **Lembretes** são notificações locais que você pode desligar.
- No EEE, Reino Unido e Suíça, anúncios personalizados, analytics e relatórios de falha ficam **desligados até você concordar**.

---

## 1. Dados no seu aparelho

O jogo salva no armazenamento privado do app:

- seu progresso: robôs, peças, cristais, ouro, campanha, temporada, missões e configurações;
- um identificador do aparelho que a Unity deriva do ID do Android, guardado no save;
- os IDs de pedido do Google Play das suas compras e uma marca de "já pagou";
- suas escolhas de privacidade (com a data), configurações de lembretes e cópias locais de backup do save.

Outros apps não conseguem ler. Tudo é apagado ao desinstalar o jogo ou limpar o armazenamento.

---

## 2. Google Play Games (opcional)

O vínculo é oferecido em **Ajustes → Vincular conta Google** e na tela do placar. O jogo nunca envia nada de quem não vinculou. Depois de vincular, o jogo faz login sozinho nas aberturas seguintes. O SDK do Play Games é iniciado na abertura, e o Google pode reconhecer seu perfil do Play Games por conta própria.

Se você vincular:

- seu **ID de jogador, nome de exibição e avatar do Play Games** são usados no placar e no save na nuvem;
- seu **total de estrelas da campanha** vai para um placar público, ao lado do seu nome no Play Games;
- **conquistas** (18) são registradas no seu perfil do Play Games;
- uma **cópia do save** (com o identificador do aparelho e os IDs de pedido acima) e cópias de backup ficam no **Saved Games**, na sua conta Google.

**Ajustes → Sair** faz backup do save na sua conta Google e o remove deste aparelho; a cópia na nuvem continua. Para apagar a cópia na nuvem, o placar e as conquistas, veja a seção 10.

---

## 3. Anúncios

O jogo mostra um banner embaixo, intersticiais entre fases e vídeos recompensados opcionais. **Sem anúncios** desliga o banner e os intersticiais.

As empresas de anúncios coletam: ID de publicidade, app set ID, endereço IP e a localização aproximada derivada dele, dados do aparelho (modelo, sistema, idioma, tela, rede), interações com anúncios (impressões, cliques, vídeo concluído) e diagnósticos do SDK. Usam isso para mostrar, medir e (se permitido) personalizar anúncios, limitar repetição e prevenir fraude, conforme as políticas delas, e podem repassar pedidos de anúncio a parceiros. Anúncios não são carregados em Android anterior ao 9.

---

## 4. Firebase: analytics, relatórios de falha e configurações remotas

O **Firebase Analytics** registra, com um ID aleatório de instalação (sem nome, sem e-mail, sem conta):

- seu progresso: tutorial concluído, etapas de carreira, território, fases-marco;
- cada fase: iniciada, terminada ou pulada, com mundo, dificuldade, resultado, tempo, estrelas, se o auto-play estava ligado e quantas peças você tem e seus níveis;
- telas abertas;
- anúncios: cada tentativa (posição, formato, resultado) e se o vídeo recompensado foi assistido até o fim;
- ofertas da loja abertas e compradas;
- o que o Firebase registra sozinho: primeira abertura, sessões, atualizações, compras no app, país, modelo do aparelho, sistema e versão do app. No Android, o Firebase também pode ler o ID de publicidade.

O **Firebase Crashlytics** envia relatórios de falha: rastreamento, modelo do aparelho, sistema, versão do app, um ID de instalação do Crashlytics, linhas recentes de log e quatro contadores do jogo (fases em campo, fases conquistadas, tamanho do elenco, etapa de carreira).

O **Firebase Remote Config** baixa configurações do jogo (balanceamento, frequência de anúncios, ofertas, eventos) **a cada abertura, antes de qualquer pergunta de consentimento**. Para isso envia um ID de instalação do Firebase, a versão do app e o idioma do aparelho. Não envia dados de jogo.

Vemos o analytics em relatórios e podemos consultar eventos por ID de instalação; não conseguimos ligá-los ao seu nome ou conta Google.

---

## 5. Compras

As compras no app (pacotes de cristais, Sem anúncios, Oferta especial, pacotes de temporada) são processadas pelo **Google Play Billing** por meio do Unity IAP. Nunca vemos cartão, endereço de cobrança ou conta Google. O jogo recebe o ID do pedido, guarda no aparelho e no save na nuvem e confere no próprio aparelho; não temos servidor de compras. Reembolsos seguem a política do Google Play.

---

## 6. Chances do gacha e bônus de apoiador

- As caixas de peças dão peças aleatórias. **Ver chances da caixa** na loja mostra a chance de cada raridade antes de abrir. A garantia (pity) assegura raridade alta depois de um número de puxadas, e os robôs-alvo direcionam de qual robô vêm as peças.
- **Bônus de apoiador.** Se você já fez uma compra real, o jogo aumenta a chance de peças Raras ou melhores: os pesos delas são multiplicados por **1,5** (valor que podemos mudar pelo Remote Config ou desligar). Com os pesos padrão, as chances passam a ser cerca de 57,0 / 32,1 / 7,7 / 2,6 / 0,64 % em vez de 66,5 / 25,0 / 6,0 / 2,0 / 0,5 % (Padrão / Rara / Épica / Protótipo / Lendária). As chances mostradas a um apoiador já incluem o bônus e avisam isso.
- A mesma marca de "já pagou" também permite um intervalo menor entre anúncios para quem pagou (Remote Config).
- A **Caixa de Ordens** da temporada usa os pesos base (sem bônus de apoiador).

Isso usa só a marca no seu aparelho; ela não é enviada para nós.

---

## 7. Lembretes

O jogo pode agendar **notificações locais**: peças e missões diárias, sequência, janela do chefe e um lembrete após 7 dias fora. O Android pede sua permissão antes. Desligue em **Ajustes → Avisos** ou nas configurações do Android. Não há servidor de push.

---

## 8. Outros serviços do Google Play

O jogo usa o In-App Review do Google Play (pedido de avaliação), In-App Update, Play Asset Delivery (download de conteúdo) e o Install Referrer (como o app foi instalado, lido pelos SDKs).

---

## 9. Consentimento e suas escolhas

- **EEE, AELC, Reino Unido e Suíça** (pela região configurada no aparelho, ou quando ela é desconhecida): antes dos anúncios, uma tela pergunta se os parceiros podem usar seu ID de publicidade e sua atividade para personalizar anúncios. Até você concordar, **analytics e relatórios de falha ficam desligados**; se recusar, os anúncios são não personalizados e analytics e relatórios de falha continuam desligados.
- **Em qualquer lugar:** **Ajustes → Privacidade → Mudar escolha de privacidade** reabre essa tela. Recusar ali desliga anúncios personalizados, analytics e relatórios de falha. O Remote Config continua funcionando.
- **Estados Unidos:** **Ajustes → Privacidade → Compartilhamento das suas informações** avisa as redes de anúncios para não vender nem compartilhar suas informações. Isso não desliga analytics nem relatórios de falha; para isso use "Mudar escolha de privacidade". Não vendemos dados pessoais por dinheiro.
- **ID de publicidade:** nas configurações do Android (**Privacidade → Anúncios**) você pode excluir ou redefinir.
- **Avisos (lembretes) e Play Games** só funcionam se você ativar.

Bases legais (LGPD, GDPR, UK GDPR): consentimento para anúncios personalizados, analytics e relatórios de falha onde a lei exige; legítimo interesse para anúncios não personalizados, Remote Config, analytics e relatórios de falha nas demais regiões, e prevenção de fraude; execução de contrato para compras e o save na nuvem.

---

## 10. Como apagar seus dados

- **Neste aparelho:** desinstale o jogo ou, no Android, **Configurações → Apps → BotRaid → Armazenamento → Limpar armazenamento**. O jogo não tem um botão de "apagar tudo".
- **Save na nuvem, placar e conquistas:** app Google Play Games → **Configurações → Excluir conta e dados do Play Games** (só do BotRaid ou de todos os jogos), ou <https://myaccount.google.com/> → Dados e privacidade.
- **Analytics e relatórios de falha:** desligue com **Mudar escolha de privacidade**. O que já foi coletado está ligado a um ID aleatório, não a você, então em geral não conseguimos encontrá-lo; é apagado automaticamente ao fim da retenção: 90 dias para relatórios de falha e o período configurado no nosso Google Analytics para analytics (no máximo 14 meses). Mesmo assim, mande um e-mail e faremos o possível.
- **Dados de anúncios:** exclua ou redefina o ID de publicidade e use os canais das empresas de anúncios.

Respondemos pedidos em até 15 dias.

---

## 11. Terceiros

| Serviço | Função | Política de privacidade |
| --- | --- | --- |
| Unity LevelPlay, Unity Ads (Unity Technologies, incl. ironSource Ads) | mediação e anúncios; diagnósticos do motor | <https://unity.com/legal/game-player-and-app-user-privacy-policy> |
| Google AdMob | anúncios | <https://policies.google.com/technologies/partner-sites> |
| Liftoff Monetize (Vungle) | anúncios | <https://liftoff.io/privacy-policy/> |
| Google Firebase (Analytics, Crashlytics, Remote Config) | medição, falhas, configurações | <https://firebase.google.com/support/privacy> |
| Google Play, Play Games, Play Billing | download, login, placar, save na nuvem, compras | <https://policies.google.com/privacy> |

Essas empresas podem tratar dados fora do seu país, inclusive nos Estados Unidos.

---

## 12. Crianças

O BotRaid é para o público geral e **não é direcionado a menores de 13 anos**. O jogo informa às redes de anúncios que não é direcionado a crianças. Não coletamos intencionalmente dados pessoais de menores de 13 anos (ou da idade mínima no seu país). Se acredita que dados de uma criança foram coletados, fale conosco e ajudamos a removê-los.

---

## 13. Segurança

Os dados ficam no armazenamento privado do app, o save na nuvem na sua conta Google, e os serviços enviam dados por HTTPS. Nenhum meio é totalmente seguro.

---

## 14. Seus direitos

Conforme onde você mora (LGPD, GDPR, UK GDPR, leis estaduais dos EUA), você pode ter direito de acessar, corrigir, apagar ou portar seus dados, de se opor ou limitar o tratamento, de revogar o consentimento e de recusar publicidade direcionada. Escreva para chilltadolab@gmail.com. Você também pode reclamar à autoridade de proteção de dados (no Brasil, a ANPD).

---

## 15. Permissões

Internet e estado da rede; cobrança do Google Play; ID de publicidade e serviços de anúncios do Android (atribuição, tópicos); estado básico do telefone (não sensível, usado por um SDK de anúncios); install referrer; notificações (lembretes); wake lock e serviço em primeiro plano (sincronização de dados, usado pelos downloads do Play Asset Delivery); atestado de aparelho da Amazon (SDK de anúncios, só aparelhos Amazon). Sem localização, contatos, câmera, microfone, fotos ou arquivos.

---

## 16. Alterações

Publicamos as mudanças neste endereço e atualizamos a data acima, antes da atualização do app que precisar delas.

---

## 17. Contato

chilltado — chilltadolab@gmail.com
