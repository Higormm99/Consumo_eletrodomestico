# Consumo_eletrodomestico 🐍
# Programa para calcular o consumo mensal de um eletrodoméstico ♻️
# Variaveis 🧊
eletrodomestico = (input('Digite o nome do eletrodoméstico:'))
potencia = float(input('Digite a potência do eletrodoméstico (em watts):'))
tempo_uso = float(input('Digite o tempo de uso diário do eletrodoméstico (em horas):'))
# Custo do kWh
custo= 0.75
consumo_mensal = (potencia * tempo_uso * 30) / 1000
# Exibe o resultado
print(f'O consumo mensal do {eletrodomestico} é de {consumo_mensal:.2f} kWh, então o consumo real é de R${consumo_mensal * custo:.2f}.')

