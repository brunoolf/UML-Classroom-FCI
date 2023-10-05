<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da computação</a></h3>


# Escola infinita, sistema de presenças

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

- Bruno Lauand Ferrão - 32217994
- Raul Vilhora Cardoso Matias - 32267274


# Descrição do projeto

É um projeto no qual simula um sistema de presenças de uma escola, ele irá utlizar de diagramas UML para um bom funcionamento, além disso terá informações como, casos de uso, objetivos funcionais e não funcionais, etc...

# Análise de requisitos funcionais e não-funcionais

**Requisitos funcionais:**

- Fazer a chamada 2x ao dia.
- Criar relatórios de faltas com os seguintes dados: data, ano do ensino, turma, professor, disciplina e aluno.
- Enviar notificações por e-mail para pais ou responsáveis caso as faltas estiverem acima de 20%.
- Gerar acessibilidade se necessário para os alunos.
- Reprovar alunos com mais de 25% de faltas.

**Requisitos não-funcionais:**

- O sistema deve ser implementado utilizando programação web.
- O sistema deve ser compatível com todos os navegadores web e dispositivos móveis e permitir acessos simultâneos.
- O sistema tem que possuir um banco de dados e se comunicar com ele.
- O usuário deve criar um cadastro com senha no site.
- O sistema de semana em semana verificará as porcentagens de presença a partir de um relatório individual gerado, essa verificação ocorrerá de sabádo. Caso esteja acima de 20% comunicar os pais ou responsável.

# Diagrama de casos de uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos casos de uso

**Relatório de faltas:**

1. Ator: Professor
2. Descrição: Gera um relatório com o histórico de presença.
3. Fluxo básico
   - O professor acessa a funcão "Relatório de Faltas".
   - O sistema mostra o relatório de faltas com o filtro escolhido.

**Registro de faltas:**

1. Ator: Professor
2. Descrição: O professor faz a chamada e registra se o aluno está presente.
3. Fluxo básico
   - O sistema apresenta a lista de alunos.
   - O professor seleciona os alunos à dar falta de acordo com a chamada.
   - A falta é registrada no momento atual.
   - O sistema armazena a falta.

**Verificar presença:**

1. Ator: Pais / Responsáveis
2. Descrição: Notificação enviada aos pais/responsáveis de acordo com sua presença em aula.
3. Fluxo básico
   - No dia de sábado
   - O sistema monitora as faltas dos alunos.
   - Caso aluno tenha suas faltas acima de 20%, o sistema envia um e-mail aos pais/responsáveis.


# Diagrama de sequencia

## Relatório de faltas

<img src="/docs/assets/relDeFaltas.svg">

## Registro de faltas

<img src="/docs/assets/regDeFaltas.svg">

## Verificar presença

<img src="/docs/assets/verPresenca.svg">

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*Material disponibilizado no moodle.*<br>
*Site ( draw.io ) para criação dos diagramas.*
