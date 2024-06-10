# C-digo-Ofuscado
import random

# Variáveis e funções ofuscadas
def p(x): return "".join([chr(ord(c) - 3) for c in x])
v = lambda y: "".join([chr(ord(c) + 3) for c in y])

# Mensagem ofuscada
m = 'lqirupdfrhv#vsfrgh#orwrlp#dolfdu'
print(p(m))  # Desofusca e imprime a mensagem

# Função complexa
def o(vs, n): return [i * n for i in vs]
def z(d): return sum(d)

x = o([random.randint(1, 10) for _ in range(5)], 2)
print(z(x))

# Parte de código irrelevante para confundir
q = ['g', 'a', 'h', 'z']
a = sorted(q)
b = ''.join(a)
print(b)
