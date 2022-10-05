# DoguitoPetShop
 Aplicação desenvolvida durante o curso JavaScript na Web: validação de Formulários e HTML5 da Alura.
 
 Objetivo do projeto, foi criar validações dos dados digitados no campos de cadastro.
 Para realizar as validações dos dados, foi utilizado o regex (no prórpio HTML) e o JavaScript.
 Caso os dados cadastrados não estivessem de acordo com o esperado, é apresentado uma mensagem de erro em baixo do campo em questão.
 
 Lista de mensagem de erro:
 
![image](https://user-images.githubusercontent.com/65188908/194065561-62c6ad22-52a8-44ee-9080-fbc00cb43d47.png)
![image](https://user-images.githubusercontent.com/65188908/194065661-9bb6f118-4cf0-488c-9aa3-4a6d7c80d075.png)


Na tela de cadastro também foi utilizado uma API (viaCEP) para obter o logradouro, cidade e estado, através do CEP digitado.
Após o CEP digitado corretamente e sendo válido no viacep, mapeamos o retorno do mesmo e preechemos os campos em questão automaticamente.

![image](https://user-images.githubusercontent.com/65188908/194066275-1d9cefea-309c-4192-874c-12b59430ae4a.png)


![image](https://user-images.githubusercontent.com/65188908/194066397-cb859c38-f7bf-4b42-b936-005bfc0f4f47.png)


Na tela de cadastro de produtos, no campos preço, utilizamos uma máscara monetária para determinar o que será digitado pelo usuário.

![image](https://user-images.githubusercontent.com/65188908/194066690-a0124438-2bc0-4a48-b7bf-6f036a77252e.png)

Para aplicar a máscara, foi utilizado o seguinte script:

<code> <script src="https://github.com/codermarcos/simple-mask-money/releases/download/v3.0.0/simple-mask-money.js"></script> <code>

Formatação da máscara:

![image](https://user-images.githubusercontent.com/65188908/194066981-a47c3f19-dc3d-416d-930a-dfa63f53693e.png)


# Fonte da Máscara:

https://github.com/codermarcos/simple-mask-money

# :rocket: Técnologias utilizadas:
* HTML 5
* CSS 3
* JavaScrip
