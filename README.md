# 7DayOfCode
 Desafio alura
# First day

O que deve ser feito:


1 - Consumir API
2 - Imprimir o resultado no terminal
3 - Fazer com que traga os 250 melhores filmes
4 - Imprimir no formato JSON
endereço do webservice ou api https://imdb-api.com/api
parametros de chamadas
parametros de retorno
5 - Gerar um API key com email 


Passo a passo instrutor:

1 - Criar conta IMDb - OK
2 - Criar código Java que executa uma requisição HTTP do tipo GET. 
Você pode usar o pacote java.net.http e as classes HttpRequest, HttpClient e HttpResponse, além da classe URI
3 - Executar a requisição e pegar a resposta (o JSON)
4 - imprimir no console


Regras:  Para construir um objeto da classe HttpRequest, você deve primeiro criar um Builder usando o método newBuilder:

   HttpRequest request = HttpRequest
            .newBuilder()
            .uri(new URI("http://www.imdb..."))
            .GET()
            .build();
