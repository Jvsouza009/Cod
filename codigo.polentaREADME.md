#================================================================
# Descrição: O programa retorna uma string a partir de um dado
#            intervalo: [start, end[
#================================================================
 
# Lê a url e remove o "enter" do fim da string com o método chomp
print "Digite a string: "
str = gets().chomp
# Lê a posição inicial
print "Digite a posicao inicial: "
start = gets().to_i
# Lê a posição final
print "Digite a posicao final: "
ended = gets().to_i
 
# Gera substring
sub = str[start...ended]
 
# Imprime a substring
print "A substring: " + sub + "\n"
 
system("pause");
