import re

f = open('processos.txt')

for line in f:


#procurar por um padrão na linha
#procurar todas as linhas que tem Baptista ou Batista, sendo que o B ser
#minúsculo ou maiúsculo, ou Polidoro
   # if re.search(r'[Ba]ap?tista|Polidoro', line):
        #print(line)
#procurar todos os comes que começam em 'D' mas que acabam em 'A'
    #if re.search(r'[^a-z][Bb][a-z]*a[^a-z]', line):
        print(line)
#procurar todos os nomes compleptps que tenha como primeiro 'Adelino´ e como último 'Ferreira'
    if re.search(r'Adelino([A-Z][a-z]+_)*Ferreira', line):
        print(line)
