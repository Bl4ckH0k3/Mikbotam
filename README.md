Mikbotamv1.8
#Changelogs

#01/04/2019 Mikbotam V1.8 krakatau

Fixo * :

Adicionado limite de tempo de atividade nas configurações de vouchers Melhoria do limite de tempo de atividade e aumento do limite de cota Melhorias no script Add Profile hotspot (bloquear usuário e validade = período de carência / usuário é excluído automaticamente após atingir a validade) Melhorias para adicionar perfil PPP Melhorias nos relatórios mensais

Bot fixo*:

Adicionado recurso de histórico de transações de bot Adicionado recurso de verificação de saldo pop-up Melhorias e adições a solicitações de recarga/depósito Adicionado Rejeitar pedidos de depósito Adicionado login Goto Adicionado uma confirmação de depósito acompanhada de uma foto #confirmação do depósito (valor do depósito) Manipule se você configurar a configuração errada do voucher ou o result for um array será considerado erro, se ocorrer um erro, o usuário que foi criado no proxy será automaticamente deletado. Manipule se não inserimos http:// nas configurações do nome do dns. A última vez que substituímos o balance pasta durante Update.zip Notas Como atualizar:

Substitua a pasta existente, não se esqueça de fazer backup da pasta antes de substituir

Tenha cuidado Update.zip substituirá Core.php se você editou o arquivo Core.php, copie-o primeiro ou renomeie o Core.php anterior! Para versões anteriores v1.2, v1.3, v1.4, v1.5, v1.6, v1.7, você pode atualizar diretamente.zip. Se tiver, ajuste o bot para o que você edita, basta copiar e colar complicado? Aprenda o tempo todo. Se você deseja atualizar, faça o download
Substituir a pasta existente, não se esqueça de fazer backup da pasta antes de substituir. Se você é novo / deseja usar o sqlite, baixe o tutorial Plug N Play no Facebook. você é novo/quer usar mysql faça o download

O desbalanceamento pode ser executado simultaneamente com o sistema de balanceamento com desbalanceamento em 1 bot. Por padrão, o bot executará apenas saldos, portanto:

Método de webhook (hospedagem)

se você deseja que ambos sejam executados, alterne seu webhook para Balance/Core_Saldo_Nonsaldo.php se você deseja apenas execução não balanceada, aponte o webhook para /Balance/Core_Nonsaldo.php Se você deseja apenas execução balanceada, aponte o webhook para /Balance /Core.php Pesquisa de método longo

Como um webhook, se você deseja que ambos sejam executados, execute seu bot. php Core_Saldo_Nonsaldo.php. Se você deseja apenas execução não balanceada, execute seu bot. php Core_Nonsaldo.php. Se você deseja apenas execução balanceada, execute seu bot .php Core.php

Grandes saudações. . . .

#23/04/2019 Mikbotam V1.7 Corrigir bugs Ep : 2

BOTs fixos *

Corrigido Script Bot/depósito e retornos de chamada de dados Adicionado qualquer comando para ser bloqueado com texto para que comandos que não existem sejam bloqueados com texto Corrigido web ui *

Melhorias na configuração da lista de texto do comprovante Notas Como atualizar:

Tenha cuidado Update.zip substituirá Core.php se você editou o arquivo Core.php, copie-o primeiro ou renomeie o Core.php anterior! Se tiver, por favor ajuste o bot para o que você edita, basta copiar e colar complicado? Enquanto aprende. Se você deseja atualizar, faça o download
Substituir a pasta existente. Não se esqueça de fazer backup da pasta antes de substituir. Se você é novo / deseja usar o SQLite, faça o download do tutorial Plug N Play no Facebook. Se você é novo / deseja usar o MySQL, faça o download Grandes
saudações. . . .

#23/04/2019 Mikbotam V1.7

BOTs fixos *

Script Bot Repair (Desmontagem total) script de reconstrução Reparar /resource Command Fix Comando adicional /deposit ou /request para funções de usuário solicitar saldo de recarga Interface web fixa *

Melhorias na notificação de erro de configurações do voucher Melhorias no script de perfil do usuário *Relatório Verde Net. Corrige pass=user to voucher ID. Remove o limite de tempo de atividade nas configurações do voucher. Observações Como atualizar:

Substitua a pasta existente, não se esqueça de fazer backup da pasta antes de substituir, tenha cuidado Update.zip substituirá Core.php se você editou o arquivo Core.php, copie-o primeiro ou renomeie o Core.php anterior! Se tiver, por favor ajuste o bot para o que você edita, basta copiar e colar complicado? Enquanto aprende. Se você deseja atualizar, faça o download
Substituir a pasta existente. Não se esqueça de fazer backup da pasta antes de substituir. Se você é novo / deseja usar o SQLite, faça o download do tutorial Plug N Play no Facebook. Se você é novo / deseja usar o MySQL, faça o download Grandes
saudações. . . .

#21/04/2019 Mikbotam V1.6 SQLITE bugs corrigidos

Funcionalidade *

Melhorias de bot de script Existem correções relacionadas a scripts de bot que não correspondem às configurações,

Como atualizar e Nota:

Substitua a pasta existente, não se esqueça de fazer backup da pasta antes de substituir, tenha cuidado Update.zip substituirá Core.php se você editou o arquivo Core.php, copie-o primeiro ou renomeie o Core.php anterior! Se tiver, por favor ajuste o bot para o que você edita, basta copiar e colar complicado? Enquanto estiver aprendendo. Se você está usando a versão anterior V1.5.3 e deseja atualizar, faça o download.
Se você é novo / deseja usar SQLite, faça o download do tutorial Plug N Play em
Se você é novo / deseja usar o Mysql, faça o download Grandes
saudações. . . .

#21/04/2019 Mikbotam V1.6 SQLITE

Funcionalidade *

Corrigidos logs de bugs do PHP 7 Corrigidos Tabela de lista de usuários Corrigido js e otimização de velocidade Corrigido bot não Voucher Corrigido senha oculta para ID Voucher

Corrigido o Live Edit Bot Corrigido o Dasboard remover o erro do voucher do widget Ativar Enviar foto de transmissão para hospedagem na web Adicionar menu Hostpot Adicionar gerenciador de hostpot web ui Adicionar gerenciador de PPP web ui

Adicione o tempo de atividade limite opcional nas configurações do voucher ATENÇÃO PARA V 1.6

Existem dois métodos nesta versão e provavelmente continuará para versões futuras Sqlite Version e Mysql Version

Versão Sqlite - Plug n play Banco de dados portátil armazenado não pode ser aberto com outros aplicativos exceto usando mikbotam e criptografado com 100 caracteres Versão Mysql - Banco de dados armazenado em mysql e geralmente uso phpmyadmin para gerenciador de banco de dados Recomendo usar mysql para grande tráfego de vendas Pasta mikbotam must chmod para 0775 ou 0777 versão Sqlite faça o download e extraia e faça o login imediatamente, Se estiver usando um servidor local ao invés de hospedagem por favor ative o módulo sqlite no php Este tutorial Por favor consulte o post.

A atualização do zip se aplica a todas as versões do SQLite e mysql

Como atualizar e Nota:

Substitua a pasta existente, não se esqueça de fazer backup da pasta antes de substituir, tenha cuidado Update.zip substituirá Core.php se você editou o arquivo Core.php, copie-o primeiro ou renomeie o Core.php anterior! Se tiver, por favor ajuste o bot para o que você edita, basta copiar e colar complicado? Enquanto estiver aprendendo. Se você está usando a versão anterior V1.5.3 e deseja atualizar, faça o download.
Se você é novo / deseja usar SQLite, faça o download do tutorial Plug N Play em
Se você é novo / deseja usar o Mysql, faça o download Grandes
saudações. . . .

#14/04/2019 Mikbotam V1.5.3 Azkal

Funcionalidade *

Corrigido PHP 7 Corrigido logs de Bugs Corrigido tabela de lista de usuários Corrigido js e otimização Corrigido perfil de usuário add (fix) Acelerar web ui Corrigido Nonsaldo Voucher Adicionar Editar bot Core.php na web ui

Adicionar marcação de registro

Preparação para impressão manual do comprovante Alterar a página atual antes do tempo limite da sessão E muito mais Atualização de bot

Nonsadolo Fixo Pode rodar Topdown Fixo

ATENÇÃO PARA V 1.5

Sistemas não balanceados já podem rodar simultaneamente com o sistema balanceado com não balanceamento em 1 bot. Por padrão, o bot executará apenas saldos, portanto:

Método de webhook (hospedagem)

se você deseja que ambos sejam executados, alterne seu webhook para Balance/Core_Saldo_Nonsaldo.php se você deseja apenas execução não balanceada, aponte o webhook para /Balance/Core_Nonsaldo.php Se você deseja apenas execução balanceada, aponte o webhook para /Balance /Core.php Pesquisa de método longo

Como um webhook, se você deseja que ambos sejam executados, execute seu bot. php Core_Saldo_Nonsaldo.php. Se você deseja apenas execução não balanceada, execute seu bot. php Core_Nonsaldo.php. Se você deseja apenas executar balance, execute seu bot .php Core.php. Observações:

Substitua a pasta existente, não se esqueça de fazer backup da pasta antes de substituir, tenha cuidado Update.zip substituirá Core.php se você editou o arquivo Core.php, copie-o primeiro ou renomeie o Core.php anterior! Se tiver, por favor ajuste o bot para o que você edita, basta copiar e colar complicado? Enquanto aprende Grandes saudações. . . .

Transferências:

12/04/2019 Mikbotam V1.5 Estável
Funcionalidade *

Corrigido PHP 7 Corrigido Bugs logs Adicionar tipo caractere Adicionar cor Qrcode Adicionar recurso sem saldo /Ainda não corrigido será atualizado em breve Adicionar exportação por mês Adicionar atualização de notícias Adicionar nova tabela Banco de dados Adicionar ferramentas Definir webhook Para hospedar outros ATENÇÃO PARA V 1.5

Como há um novo recurso, crie um novo banco de dados de importação com o banco de dados Newdatabase.sql, se você quiser usar o banco de dados antigo, importe novamente o banco de dados com o arquivo Dropandinsert.sql anterior. Portanto, há a necessidade de redefinir a interface do usuário da web do mikbotam, pedimos desculpas pela magnitude,

Se não atualizar o banco de dados

1.bot irá travar e travar 2.Você não pode usar novos recursos. 3.Você não pode receber a próxima atualização porque ela usará esse novo banco de dados posteriormente,

Mais uma vez pedimos desculpas por este momento, pela atenção e apoio, agradecemos, não se esqueça de ser feliz :-D
