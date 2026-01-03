🤖 Projeto de Automação de Robô Educacional

Projeto desenvolvido em parceria com a Escola Estadual Presidente Tancredo Neves.

O objetivo inicial era criar um robô totalmente autônomo. No entanto, após conversas e alinhamentos com os organizadores, optamos por um modelo semiautônomo, inspirado no funcionamento de robôs industriais utilizados em linhas de produção.

Fui responsável pela programação e lógica de automação do robô, implementando um sistema no qual ele executa comandos iniciais controlados manualmente e, em seguida, repete automaticamente os movimentos previamente gravados. Essa abordagem simula processos industriais reais, onde uma sequência de ações é ensinada ao robô e depois reproduzida de forma precisa.

Além disso, o robô foi projetado para participar de atividades práticas e desafios propostos pela escola, demonstrando resistência, versatilidade e estabilidade operacional em diferentes cenários.

🎥 Confira o resultado final do projeto neste vídeo:
👉 https://youtube.com/shorts/QqRt7IM0RXs?feature=share


<p align="center">
  <img width="389" height="493" alt="robo-escola" src="https://github.com/user-attachments/assets/fbd73448-7ad9-4c45-8fb6-809dd89f2f33" />
</p>

<br>

💻 Código do Projeto

Abaixo está parte do código desenvolvido para o robô.
Para um melhor entendimento da lógica de automação, consulte o arquivo automacao.py, onde está centralizada a implementação principal do sistema.

Estrutura do Código:

ESP32 como unidade de controle

Controle PS4 para gravação e execução de comandos

Servomotores para movimentação

Memória interna (Preferences) para salvar e reproduzir rotas automatizadas

📌 A lógica permite:

Gravar movimentos manualmente

Armazenar comandos na memória

Reproduzir rotas automaticamente

Interromper a execução em tempo real

(O código completo está disponível no aqrquivo automacao.py.)
