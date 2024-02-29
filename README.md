<h2>Protheus 12.1.2310  - Postgres </h2>

Procedimentos:
1. Instalar o <b>Docker</b> ( https://www.docker.com/products/docker-desktop/ )
2. Criar uma pasta e copiar os arquivos <b>docker-compose.yml</b> ( https://github.com/emebatista/docker-protheus-2310/blob/main/docker-compose.yml )  e <b>conf.inf</b> ( https://github.com/emebatista/docker-protheus-2310/blob/main/conf.inf )
3. Abrir o terminal dentro da pasta criada e que contém os dois arquivos anteriores e dar o comando: <b>docker-compose up -d </b>. Se as imagens já estiverem em cache e quiser forçar baixá-las de novo, o comando é docker-compose up -d --pull. No Docker Desktop, o nome do grupo de conteiners será o mesmo do nome da pasta onde foi dado o comando.
4. Acessar o <b>Protheus</b> através do smartclient através na porta <b>1234</b>. O nome do ambiente é <b>P2310</b>. Após subida dos containeres, aguarde 5 minutos até entrar pela primeira vez no sistema, pois logo na primeira construção do container o banco de dados será criado e restaurado o backup inicial. 
5. Acessar o <b>Protheus WebApp</b> através do navegador do endereço <b>http://localhost:4321</b>.
6. Usuário: Admin , senha: espaço em branco.