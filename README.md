# aws_cwEvents_crossAccount
IAC para envio de eventos do AWS CloudWatch Events entre contas

# How To
Receiver Account é necessário conceder permissão para que as contas da Organization (Organization ID) e/ou account´s ID enviarem os eventos do serviço Health (PHD).
Nas Products Accounts é preciso criar CloudWatch Rule direcionando qualquer evento do serviço Health (PHD) para a Receiver Account.

![Diagrama](/images/CwEventsCrossAccount.png)
