# Sistema de Monitoramento de Projetos de Hidrogênio Verde no Estado do Piauí

Olá Pessoal!!

🚀 Apresento a vocês o Sistema de Monitoramento de Projetos de Hidrogênio Verde no Estado do Piauí! 

💡Estou empolgado em compartilhar o resultado de 4 meses de trabalho dedicado na implementação de uma ferramenta para impulsionar a produção sustentável de hidrogênio em nosso amado Estado do Piauí. 

🔍A página Inicial aberta ao público tem como objetivo mostrar os avanços dos nosso estado nessa área, e no mundo. Internamente temos informações mais detalhadas sobre cada projeto e seus progressos.

## 🌿 O que é o Sistema de Monitoramento?
Este software foi criado para rastrear e analisar o progresso de iniciativas focadas na produção sustentável de hidrogênio. Seus objetivos primordiais incluem a supervisão eficiente do desenvolvimento de infraestrutura, gestão otimizada de recursos e a promoção da transparência no setor.

## 🌱 Contribuindo para um Futuro Sustentável
Ao oferecer uma visão abrangente do cenário dos projetos de hidrogênio verde, nosso sistema visa facilitar a tomada de decisões informadas, impulsionar a eficiência operacional e promover práticas sustentáveis. Estamos comprometidos em contribuir para um futuro mais verde e sustentável para o Piauí e além.

## 🚀 Principais Recursos:
- Acompanhamento em tempo real do progresso dos projetos.
- Análises detalhadas para uma gestão eficiente de recursos.
- Relatórios transparentes para promover a responsabilidade e confiança.

## 🛠️ Tecnologias Utilizadas
- **Ruby on Rails:** Framework para desenvolvimento da aplicação.
- **MySQL/PostgreSQL:** Bancos de dados.
- **Passenger/Unicorn:** Servidores de aplicação.
- **Apache/Nginx:** Servidores web.
- **Docker:** Para contêineres de desenvolvimento e produção.
- **Redis:** Para cache.
- **Sidekiq:** Gerenciamento de filas.

## 🚀 Executando o Projeto

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/luiseduardoalencar/smph2v.git
   cd smph2v
   ```

2. **Configurar o Docker:**
   Certifique-se de ter o Docker e Docker Compose instalados em sua máquina. Configure o ambiente usando o Docker Compose:
   ```sh
   docker-compose up
   ```

3. **Configurar o Banco de Dados:**
   Execute as migrações para configurar o banco de dados:
   ```sh
   docker-compose run web rake db:create db:migrate
   ```

4. **Iniciar o Servidor:**
   Inicie o servidor web:
   ```sh
   docker-compose up
   ```

5. **Acessar a Aplicação:**
   A aplicação estará disponível em `http://localhost:3000`.

---

