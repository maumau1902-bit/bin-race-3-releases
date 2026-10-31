# Bin Race 3 — Downloads oficiais

Não precisa de conta GitHub para baixar, instalar ou usar o aplicativo.

[Ver a versão mais recente e as novidades](https://github.com/maumau1902-bit/bin-race-3-releases/releases/latest)

| Seu computador | Instalador 0.12.0 |
| --- | --- |
| Windows 10 ou 11, 64 bits | [Baixar para Windows](https://github.com/maumau1902-bit/bin-race-3-releases/releases/download/v0.12.0/Bin-Race-3-Setup-0.12.0.exe) |
| Mac Intel ou com chip Apple (M1/M2/M3/M4 ou posterior compatível) | [Baixar para Mac — Universal](https://github.com/maumau1902-bit/bin-race-3-releases/releases/download/v0.12.0/Bin-Race-3-0.12.0-macOS-universal.dmg) |

No Mac, não precisa identificar o processador: o mesmo download inclui código
nativo para Intel e Apple Silicon; o sistema escolhe automaticamente, sem outro
download de componentes e sem Rosetta. Requer macOS
12 Monterey ou mais recente, conforme o mínimo declarado pelo motor incluído;
os testes nativos desta edição foram em macOS 15 nos dois tipos de processador.
Não é um aplicativo para iPhone/iPad nem compatível com todo Mac antigo.

**Windows:** execute o instalador, siga o assistente e abra pelo atalho.
O SmartScreen pode mostrar aviso: ainda não há certificado de editor verificado.

**Mac:** abra o DMG, arraste Bin Race 3 para Aplicativos, ejete a imagem e abra
pela pasta Aplicativos ou Launchpad. Esta edição Mac de testes usa assinatura
técnica ad-hoc, **sem Developer ID/notarização da Apple**; o Gatekeeper pode
bloquear a primeira abertura. Se confiar na origem oficial, utilize somente a
confirmação oferecida em Ajustes do Sistema > Privacidade e Segurança.
Não desative as proteções. Políticas corporativas podem impedir esta edição;
se não houver opção de aprovação, consulte o responsável pelo computador.

**Atualizações:** o app verifica novas versões ao abrir com internet. Windows baixa e aplica automaticamente após sua confirmação, com pacote
incremental quando compatível. A partir da 0.11.1, o Mac baixa/verifica o DMG
Universal completo, prepara antes de fechar, substitui e reabre automaticamente,
com recuperação se a nova janela não confirmar abertura. Permissões e segurança
do macOS continuam valendo. Quem está no Mac **0.11.0 precisa instalar a versão atual
uma vez pelo Finder** para adquirir o mecanismo. Mac ainda não tem delta.
Sessões e Documentos/Tracks ficam separados do aplicativo.

Análises, comparação, replay/zoom, setores, biblioteca, validade, PDF e vídeo
usam a mesma base entre sistemas. Não depende de GitHub, Codex ou Node.js.
Não há sincronização automática entre computadores. Há cópias locais automáticas e backup/restauração manuais.

**Aparelhos:** seleção de Conexão do computador ajuda quando há VPN ou vários
adaptadores. Erros/permissões UDP/TCP são explicados. Comunicação testada com
sockets nativos e SOLO virtual no aplicativo empacotado dos dois sistemas.
Isso não é ensaio de rádio/firmware/TCC físico. Wi-Fi SOLO 2 confirmado por
usuário no Windows; no Mac ainda
experimental, sem teste físico. Extração USB direta SOLO 1 e envio direto de
pistas/configurações continuam pendentes. Diagnóstico PnP e atalhos Race Studio
são exclusivos do Windows. Os softwares AiM/drivers não acompanham o app.
DRK compatível precisa do RRK do mesmo treino para analisar geometria GPS.

Resultados de validade são diagnósticos dos dados, não cronometragem oficial,
certificação de autenticidade ou prova de fraude. Veja limites nas notas da versão.

Este repositório contém somente pacotes, hashes, instruções e o fluxo público
de publicação. O código de desenvolvimento permanece privado; dados pessoais
de telemetria não são publicados. Repositório privado não impede engenharia
reversa do aplicativo distribuído.

## Novidades 0.12.0

Mínima junto da máxima, relatório/CSV/PDF com extremos de volta e setor, evolução por piloto/pista/moto com seleção explícita, ficha de treino e notas locais de piloto/professor por curva. CSV recortado começa parcial; a confirmação fica em Editar sessão → Voltas CSV. Tempos e amostras originais são preservados.

Backups automáticos em Documentos/Bin Race 3/Backups: até 10 cópias recentes e 1 GB. Em Minhas sessões → Backup e restaurar, revise uma cópia para adicionar os treinos sem substituir os atuais. Originais e auxiliares permanecem em Tracks; vídeos e originais não são embutidos nas cópias. Guarde ambas as pastas também em outro dispositivo para se proteger contra defeito do disco.

## Primeira abertura no Mac, sem Terminal

1. Abra o DMG e arraste Bin Race 3 para Aplicativos.
2. Ejete a imagem e tente abrir o app dentro de Aplicativos.
3. Se a Apple informar que não pôde verificar, feche o aviso e abra  → Ajustes do Sistema → Privacidade e Segurança → Segurança.
4. Encontre o aviso do Bin Race 3, clique em **Abrir Mesmo Assim** e confirme com senha ou Touch ID.

No Monterey, o caminho é Preferências do Sistema → Segurança e Privacidade → Geral. A opção aparece depois da tentativa de abertura. Em Mac gerenciado, consulte o responsável se a opção estiver bloqueada. O DMG inclui o guia ilustrado **Primeira abertura no Mac.html**. Não remova quarentena nem desative as proteções do sistema.
