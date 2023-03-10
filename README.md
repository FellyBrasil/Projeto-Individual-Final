# *Projeto-Individual-Final*

Nossa equipe teve diversas ideias para a criação do que seria o nosso site e nossa API, alguns deram ideias parecidas e ouros deram ideias diferente, nossa squad 3 se reuniu com o objetivo de pensar e criar algo que fosse de interessante para o governo ou algum órgão de educação que fosse acessível e de fácil acesso para todas as idades para a compreensão de todo público, principalmente com aqueles que apresentam alguma dificuldade em interagir com tecnologias diversas.
Aqui a baixo irei mostrar as diversas ideias que teve na equipe:

•	**Uma das ideias**: Uma ideia de criar uma API, que organizasse e auxiliasse o publico no geral a encontrar shoppings/cinemas, poder comprar os ingressos, comprar alimentos, brindes e claro que mostrasse quais filmes estarão em cartaz e de extra que mostrasse datas de próximos lançamentos que terão ainda no ano.

•	**Outra ideia foi**: Uma ideia de criar um site com API focado em realização de provas relacionadas a órgãos de educação e de pré-militar.

•	**Ideia final**: Foi a ideia escolhida, que estamos utilizando e que irá ser apresentada no projeto final.


# [ API ] Programadores Cariocas
### 📑 Descrição
Desenvolvimento da <em>**API REST**</em> no **padrão MVC** que retorna informações das entidades de um aplicatico de administrção que efetua todas as operações **CRUD**: ``polos``, ``candidatos``, ``resultados``, ``zonas``.

**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>SQLite3</em> | <em>Express</em> | <em>Insomnia</em> | <em>CORS</em> | <em>npm</em> | <em>Nodemon</em>
  
</samp>

## Rotas CRUD

### [ 1 ] <em>polos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/polos** | Retorna todos os fisioterapeutas. |
|  **`GET`** | **/polos/id** | Retorna um fisioterapeuta. |
|  **`POST`** | **/polos** | Cria um novo fisioterapeuta.  |
|  **`PUT`** | **/polos/id** | Altera os dados do fisioterapeuta.
|  **`DELETE`** | **/polos/id** | Remove o fisioterapeuta.
  
### [ 2 ] <em>candidatos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/candidatos** | Retorna todos os Pacientes. |
|  **`GET`** | **/candidatos/id** | Retorna um Paciente. |
|  **`POST`** | **/candidatos** | Cria um novo Paciente.  |
|  **`PUT`** | **/candidatos/id** | Altera os dados do Paciente.
|  **`DELETE`** | **/candidatos/id** | Remove o Paciente.
  
  
### [ 3 ] <em>resultados</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/resultados** | Retorna todos os agendamentos. |
|  **`GET`** | **/resultados/id** | Retorna um agendamento. |
|  **`POST`** | **/resultados** | Cria um novo agendamento.  |
|  **`PUT`** | **/resultados/id** | Altera os dados do agendamento.
|  **`DELETE`** | **/resultados/id** | Remove o agendamento.


### [ 4 ] <em>zonas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/zonas** | Retorna todos os equipamentos. |
|  **`GET`** | **/zonas/id** |  Retorna um equipamento. |
|  **`POST`** | **/zonas** | Cria um novo mequipamento.  |
|  **`PUT`** | **/zonas/id** | Altera os dados do equipamento.
|  **`DELETE`** | **/zonas/id** | Remove o equipamento.
  



