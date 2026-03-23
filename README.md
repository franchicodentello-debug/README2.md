# 🖩 Calculadora de consumo mensal
Este projeto serve para calcular o consumo mensal do aparelho selecionado.

- **Linguagem usada:** Python
- **Fórmula usada:** Consumo mensal em kWh = (Potência em W * Uso diário em horas * 30) / 1000
- **Instruções de execução:** Digitar todas as informações solicitadas pelo programa
[![My Skills](https://skillicons.dev/icons?i=python,github)](https://skillicons.dev)

[app.py](https://github.com/user-attachments/files/26170946/app.py)
# Entrada de dados
aparelho = input("Digite o aparelho: ")
potencia_w = input("Digite a potência do aparelho em watts: ")
usodia_h = input("Digite o tempo médio diário de uso em horas: ")
# Processamento
consumo_mensal = (float(potencia_w) * float(usodia_h) * 30) / 1000  # Convertendo para kWh
# Cálculo de consumo mensal
print(f"O aparelho selecionado é {aparelho}, que contém uma potência de {potencia_w} watts.")
print(f"Considerando que, em média, este aparelho é utilizado diariamente por {usodia_h} horas, o consumo estimado será de {consumo_mensal} kWh por mês.")
