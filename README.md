Este projeto é um Conversor de Moedas desenvolvido como parte de um desafio da Alura Latam em parceria com o programa Oracle Next Education. Ele permite a conversão entre diferentes moedas, com taxas de câmbio atualizadas via API.

Funcionalidades
Conversão de Moeda: Converte valores entre moedas usando a API ExchangeRate.
Histórico de Conversões: Armazena e exibe o histórico ao usuário.
Salvar Histórico: Exporta o histórico de conversões para um arquivo de texto.
Consulta em Tempo Real: Usa as taxas de câmbio mais recentes.
Tratamento de Erros: Lida com erros de entrada, conexão e manipulação de dados JSON.

Tecnologias Utilizadas
Funcionalidade: Conversão BRL, USD, EUR; menu interativo
Integração: API ExchangeRate-API para taxas em tempo real
Erros: Entradas inválidas e falhas de conexão

Estrutura do Projeto
exchangerateapi: Responsável por interagir com a API ExchangeRate para buscar as taxas de câmbio.
modelo: Contém classes relacionadas às moedas e ao histórico de conversões.
principal: Contém a execução principal do programa.