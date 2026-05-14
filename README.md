Sistema de monitoramento e irrigação automática utilizando ESP32, sensor de umidade do solo e controle de relé via Tasmota. Possui interface web integrada, envio de dados para API, sincronização automática de horário (NTP) e atualização OTA via navegador.

//FUNCIONALIDADES//

Leitura da umidade do solo
Conversão da leitura para porcentagem
Controle automático de irrigação
Controle manual via navegador
Interface web responsiva
Envio periódico de dados para API REST
Sincronização automática de horário (Brasília)
Failover entre duas redes Wi-Fi
Atualização OTA via navegador
Proteção por senha na rota de atualização
Compatível com Tasmota
Economia de energia com Wi-Fi Sleep

//OPERAÇÃO//

conecta em uma das redes Wi-Fi configuradas
sincroniza o horário via NTP
lê a umidade do solo periodicamente
decide automaticamente ligar/desligar a irrigação
envia os dados para uma API
disponibiliza uma interface web local
permite atualização remota do firmware via OTA

//ROTAS DISPONÍVEIS//

URL	Função
/	Painel web
/data	Dados JSON
/setnivel?valor=40	Ajusta nível mínimo
/manual	Alterna modo manual
/toggle	Liga/desliga bomba
/update	Atualização OTA
