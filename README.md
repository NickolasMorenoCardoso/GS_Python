# GS_Python

Monitoramento de Qualidade da Água com Drones
Este projeto implementa um sistema de monitoramento de qualidade da água utilizando drones. Cada drone coleta dados como temperatura, pH e nível de contaminantes da água em diferentes localizações, analisa esses dados e pode se mover para novas localizações para continuar o monitoramento.

Funcionalidades:
Inicialização de Drones: Criação de drones com identificadores únicos e localizações iniciais.
Coleta de Dados: Drones coletam dados de temperatura, pH e nível de contaminantes da água.
Envio de Dados: Drones enviam os dados coletados para análise.
Análise da Qualidade da Água: Os dados coletados são analisados para verificar se estão dentro dos padrões aceitáveis.
Movimentação dos Drones: Drones podem ser movidos para novas localizações para monitorar outras áreas.

Estrutura do Código
Classe Drone
Métodos

__init__(self, id, localizacao): Inicializa um drone com um ID único e uma localização inicial.
coletar_dados(self): Coleta dados simulados de temperatura, pH e contaminantes.
enviar_dados(self): Envia (imprime) os dados coletados.
mover_para(self, nova_localizacao): Move o drone para uma nova localização e imprime a nova posição.

Funções Auxiliares
analisar_qualidade_agua: Analisa os dados coletados pelo drone e identifica possíveis problemas com a qualidade da água.
inicializar_drones(): Inicializa uma lista de drones com localizações predefinidas.
coletar_dados_drones(drones): Coleta e envia dados de cada drone na lista, analisando a qualidade da água.
mover_drones(drones, novas_localizacoes): Move cada drone para uma nova localização.

Função Principal
main(): Orquestra a execução do programa, inicializando drones, coletando e analisando dados, movendo os drones para novas localizações e coletando e analisando dados novamente.

Como Executar
Certifique-se de ter o Python instalado na sua máquina.
Copie o código para um arquivo com extensão .py, por exemplo, monitoramento_agua.py.
Execute o arquivo usando o comando:
python monitoramento_agua.py
