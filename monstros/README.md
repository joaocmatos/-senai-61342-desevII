 # Semana 01
 
 Cada monstro deve possuir:

   * nome
   * tipo (fogo, agua, etc)
   * poder de ataque (0 a 10 sempre inteiro)
   * poder de defesa (0 a 10 sempre inteiro)
   * pontos de vida
   * grau de evolução (quanto maior melhor)
   * nível (de 1 a 10)
   * método de ataque - explicado a seguir
   * método de defesa - explicado a seguir

O método de ataque deverá calcular quanto dano ele causa, para isso vcs devem fazer uma multiplicação, e retornar este valor

**pode de ataque * grau de evolução * nível * numero randômico de 1 a 5**

O método de defesa deverá usar algo similar:

**poder de defesa * grau de evolução * nível * numero randômico de 1 a 3**

a diferença entre eles será subtraída dos pontos de vida do monstro.

# Semana 02

Cada jogador deverá criar dois monstros

Cada monstro deverá calcular 10 ataques e 10 defesas e por num array

Para a luta voce deve comparar o ataque de um e a defesa do segundo subtraindo a diferença dos pontos de vida de quem recebeu o ataque

Por fim, vocês deverão implementar um sistema de torneio em chaves com 16 monstros diferentes.

# Semana 03

Por último vocês devem implementar a criação de monstros através da leitura de um arquivo json.
