# App

## RFs (Requisitos funcionais)  

- [ ] Deve ser possível o usuário se cadastrar;
- [ ] Deve ser possível o usuário se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o numéro de checki-ins do usuário;
- [ ] Deve ser possível o usuário buscar as academias proximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

## RNs (Regras de Negócios)  

- [ ] O usuário não pode se cadastrar com um email duplicado
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia
- [ ] O usuário não pode fazer check-in se não estiver perto da academia
- [ ] O check-in só poderá ser validado 20 minutos após criado
- [ ] O checkin só pode ser valiado por administradores
- [ ]  A academia só poderá ser cadastrada por administradores

## RNF (Requisitos não funcionais)  
- [ ] A senha do usuário precisa estar criptografada
- [ ] Os dados da aplicação precisam estar persistidos em um banco de dados PostgresSQL
- [ ] Todas as listas dados precisam estar paginadas com 20 itens por página
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token  )