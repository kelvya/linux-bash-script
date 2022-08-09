# Infraestrutura como Código: Script de criação de estrutura de usuários, diretórios e permissões

## Conteúdo

### O que é infraestrutura como código?
<p> Ingraestrutura como código (IaC) é o gerenciamento e provisionamento da infraestrutura por meio de códigos,em vez de processos manuais.</p>
<p> Com a IaC, são criados arquivos de configuração que incluem as especificações da sua infraestrutura, facilitando a edição e  distribuição de configurações. Ela também assegura o provisionamento do mesmo ambiente todas as vezes.</p>

### Controle de versão
<p>O controle de versão é uma parte importante da IaC. os arquivos de configuração devem pertencer à fonte como qualquer outro código-fonte de software. Ao implantar a infraestrutura como código, também é possível separá-la emmódulos, que podem ser combinados de diferentes maneiras por meio da automação.</p>
- Princial benefício:
<p>Ao automatizar o provisionamento da infraestrutura com a IaC, os desenvolvedores não precisam provisionar e gerenciar manualmente servidores, sistemas operacionais, armazenamento e outros componentes de infraestrutura sempre que criam ou implantam uma aplicação.</p>

### Sobre o desafio:
<p>Neste desafio de projeto foi criado um script onde toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões foram criadas automaticamente. Assim, toda nova máquina virtual que for iniciada já estará pronta para uso quando o script for executado.</p>


### Definições:
- Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;
- O dono de todos os diretórios criados será o usuário root;
- Todos os usuários terão permissão total dentro do diretório público;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertençam;
- Subir arquivo de Script criado para a sua conta do Github.
