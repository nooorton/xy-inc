# xy-inc

Testado em:

* Servidor : Wildfly-10.1.0
* Banco de Dados: MongoDB 3.4.1
* JDK: 1.8.0_111
* IDE: Eclipse Neon 2.0
* Download de dependencias: Maven

Configurando/Executando o projeto:

- Importar o projeto como "Existing Maven Project"
- Criar um novo servidor "New -> Server -> WildFly 10.x"
- Garantir que a versão do jdk instalado seja 1.8 e esta configurada no build path do projeto/servidor
- Iniciar o Mongo DB
- Realizar um clean install do projeto utiizando o seguinte caminho "Run ass -> Maven Build" com o parametro "clean install compile package"
- Inicializar o servidor da Aplicação

Para acessar a aplicação via Browser:
