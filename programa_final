# Probabilidades de visitar cada supermercado
prob_visitar = [0.25, 0.15, 0.05, 0.2, 0.1, 0.15, 0.1]

# Probabilidades de comprar carne dado que visitó cada supermercado
prob_comprar_carne_dado_visita = [0.45, 0.54, 0.6, 0.35, 0.23, 0.12, 0.8]

# a) Probabilidad de visitar el supermercado con índice 2
prob_visitar_2 = prob_visitar[2]
print(f"a) Probabilidad de visitar el supermercado con índice 2: {prob_visitar_2}")

# b) Probabilidad de visitar el supermercado con índice 5 y comprar carne
prob_visitar_5_y_comprar_carne = prob_visitar[5] * prob_comprar_carne_dado_visita[5]
print(f"b) Probabilidad de visitar el supermercado con índice 5 y comprar carne: {prob_visitar_5_y_comprar_carne}")

# c) Probabilidad de que el compañero compre carne
prob_comprar_carne = sum(prob_visitar[i] * prob_comprar_carne_dado_visita[i] for i in range(len(prob_visitar)))
print(f"c) Probabilidad de que el compañero compre carne: {prob_comprar_carne}")

# d) Probabilidad de que visitó el supermercado con índice 3, dado que compró carne
prob_visitar_3_y_comprar_carne = prob_visitar[3] * prob_comprar_carne_dado_visita[3]
prob_visitar_3_dado_comprar_carne = prob_visitar_3_y_comprar_carne / prob_comprar_carne
print(f"d) Probabilidad de que visitó el supermercado con índice 3, dado que compró carne: {prob_visitar_3_dado_comprar_carne}")

# e) Probabilidad de que no visitó el supermercado con índice 1, dado que no compró carne
prob_no_comprar_carne = 1 - prob_comprar_carne
prob_visitar_1_y_no_comprar_carne = prob_visitar[1] * (1 - prob_comprar_carne_dado_visita[1])
prob_no_visitar_1_y_no_comprar_carne = prob_no_comprar_carne - prob_visitar_1_y_no_comprar_carne
prob_no_visitar_1_dado_no_comprar_carne = prob_no_visitar_1_y_no_comprar_carne / prob_no_comprar_carne
print(f"e) Probabilidad de que no visitó el supermercado con índice 1, dado que no compró carne: {prob_no_visitar_1_dado_no_comprar_carne}")
