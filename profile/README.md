# Synapse — mais tempo para o que importa

A vida nem sempre dá espaço para parar, abrir a agenda e registrar cada detalhe. Entre trabalho, estudos, família e compromissos, é fácil deixar algo passar — ou gastar um tempo precioso tentando manter tudo em ordem.

O **Synapse** está sendo criado para ajudar justamente nesses dias corridos. A ideia é tornar mais simples transformar aquilo que a pessoa precisa lembrar em um lembrete organizado, para que ela possa cuidar da rotina com menos esforço e dedicar mais atenção ao que realmente importa.

## Uma agenda que acompanha o seu ritmo

Com o Synapse, a pessoa pode registrar um lembrete por texto ou voz, como quem fala com alguém: “me lembra de enviar o relatório amanhã às dez”. O projeto interpreta essa intenção e organiza as informações para criar o lembrete. A proposta é reduzir passos e evitar que a organização da rotina vire mais uma tarefa pesada.

O Synapse também está sendo preparado para facilitar o acesso e manter os compromissos reunidos em um só lugar. O login e os recursos de agenda fazem parte dessa experiência, sempre com atenção à privacidade e ao controle das informações de cada pessoa.

Nosso objetivo é simples: **devolver alguns minutos e um pouco de tranquilidade para quem sente que o dia nunca tem horas suficientes**. Não queremos substituir a forma de cada pessoa se organizar; queremos oferecer uma ajuda prática que caiba na vida real.

## Como o projeto está organizado

O Synapse é formado por três partes que trabalham juntas:

- **`Frontend/`** — o aplicativo que a pessoa usa para acessar a agenda, registrar lembretes e acompanhar sua rotina.
- **`backend-agenda/`** — a parte que organiza as contas e os lembretes e conecta os componentes do projeto.
- **`microservice/`** — o componente que ajuda a entender frases de lembrete em português e identificar informações como data e horário.

Em conjunto, essas partes recebem o pedido da pessoa, ajudam a transformá-lo em um lembrete e devolvem o resultado para o aplicativo.

## Um projeto em evolução

Estamos construindo e aprimorando o Synapse passo a passo. Isso inclui melhorar a compreensão de pedidos em português, facilitar o acesso à agenda e tornar os lembretes mais confiáveis. O projeto ainda exige configuração e validação antes de ser usado em produção; os detalhes para desenvolvimento e execução estão nos READMEs de cada pasta.

Quem for colaborar pode começar entendendo a experiência que queremos criar: **menos tempo tentando lembrar de tudo, mais tempo vivendo o próprio dia**.
