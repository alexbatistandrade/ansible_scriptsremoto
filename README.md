Para executar um #script remoto usando Ansible, podemos usar o módulo "#script". Por exemplo, para executar um script chamado "backup.sh" em um host #remoto, podemos usar o seguinte comando:

# ansible -i hosts linuxteste -m script -a "/scripts/backup.sh"

#linuxteste é meu grupo dentro do arquivo hosts
#scripts/backup.sh é a minha estrutura de pasta onde esta localizado meu script.

Com esses comandos, podemos facilmente executar comandos e scripts em vários hosts remotos de uma só vez, #economizando #tempo e #esforço em nossas #tarefas de administração do sistema.
