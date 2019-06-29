#Análise de similaridade entre congressistas (em escrita)

##Descrição do dataset

##Problema 1
Escreva uma função que recebe como argumento os IDs de dois congressistas e um dicionário que mantém a votação dos congressistas. Essa função deve retornar o grau de similaridade entre os votos dos dois congressistas especificados. A função deve seguir a seguinte assinatura.

compare (congress_id1, congress_id2, votos_dict) ~> float

##Problema 2
Escreva uma função que recebe o ID de um congressista e um dicionário que mantém a votação dos congressistas. Essa função deve retornar o ID de um outro congressista que seja o mais similar ao que foi passado como parâmetro para a função. A função deve seguir a seguinte assinatura.

most_similar (congress_id, votos_dict) ~> int

##Problema 3
Escreva uma função que recebe o ID de um congressista e um dicionário que mantém a votação dos congressistas. Essa função deve retornar o ID de um outro congressista que seja o menos similar ao que foi passado como parâmetro para a função. A função deve seguir a seguinte assinatura.

least_similar (congress_id, votos_dict) ~> int

##Problema 4
Escreva um procedimento para indicar quão similares são os senadores de cada estado brasileiro.

##Problema 5
Escreva um procedimento para indicar quão simular um congressista é de um conjunto de outros congressista. Sua função pode seguir a seguintes assinatura

average_similarity (congress_id, congress_set, votos_dict) ~> float

Nesse caso, queremos comparar o congressista com ID congress_id com todos os congressistas indicados em congress_set, segundo as votações em votos_dict. Use essa função para achar o congressista menos similar ao partido do qual faz parte.

##Problema 6
Escreva um procedimento (que pode usar as funções anteriores) que descubra o par de congressistas mais parecidos.

##Problema 7
Escreva um procedimento (que pode usar as funções anteriores) que descubra o par de congressistas mais diferentes.

##Problema 8
Escreva um procedimento (que pode usar as funções anteriores) que descubra o partido mais coerente (aquele em que seus congressistas são mais similares).

##Problema 9
Escreva um procedimento (que pode usar as funções anteriores) que descubra o partido menos coerente (aquele em que seus congressistas são menos similares).

