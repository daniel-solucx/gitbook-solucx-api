---
description: Manual de Boas Práticas para Uso de APIs
---

# Boas Práticas

As APIs passivas são essenciais para a integração e comunicação entre sistemas e serviços. Este manual visa estabelecer diretrizes claras e boas práticas para o uso adequado e eficiente das APIs passivas, garantindo a segurança, confiabilidade e desempenho dos sistemas envolvidos.

## 1. Conhecendo a API:

* Antes de começar a utilizar uma API passiva, é crucial compreender sua documentação oficial, incluindo endpoints disponíveis, métodos de autenticação, limites de taxa, e possíveis parâmetros e respostas.

## 2. Autenticação e Autorização:

* Sempre utilize métodos de autenticação adequados, como chaves de API ou tokens de acesso, conforme especificado pela documentação da API.
* Mantenha as credenciais de autenticação seguras e evite compartilhá-las desnecessariamente.

Para consumir a API SoluCX, são necessárias duas informações a saber:

* API Key da instância `(x-solucx-api-key).`
* Token de acesso da API. `(x-solucx-user-token).`

Ambos são chaves que deverão ser informadas no header para autorização de cada chamada.

### Passos para integração

* &#x20;Necessário obter uma chave de conexão (x-solucx-api-key) e token (x-solucx-user-token) ao aplicativo com a equipe técnica da SoluCX.
* x-solucx-api-key e x-solucx-user-token são obrigatórios em todas as chamadas.
* &#x20;Criar unidades de referência que serão avaliadas pelo cliente. Ex: Lojas de uma rede, setores de departamento, áreas de uma empresa.
* &#x20;Criar colaboradores que participam ou participaram da experiência do cliente. Ex: Vendedor de uma loja de uma rede, Médico de um hospital, atendente de call center Obs: em caso de não ter colaboradores, criar um genérico para informar na experiência
* Criar o cliente que avaliará a experiência Ex: Cliente atendido em uma unidade por um vendedor de uma loja, Paciente de hospital atendido por um médico, Cliente solicitando ajuda em call center a um atendente.
* Criar a transação ou experiência, juntando todas as entidades criadas anteriormente.

## 3. Respeitando Limites de Consultas:



* Esteja ciente dos limites de consultas estabelecidos pela API para evitar sobrecarregar o servidor, pois caso as consultas realizadas via integração exceda o limite saudável de usabilidade, nossa equipe entrara em contato para orientar como tirar melhor proveito da integração.
* Implemente mecanismos de controle para lidar com possíveis erros de taxa limite excedida de forma adequada e elegante.

Para a Infraestrutura atual, consultas que somam transações em períodos longos são grande ofensores, pois sobrecarrega nossos servidores e geram lentidão tanto na consulta em questão quanto nas próximas,  portanto orienta-se o uso do **transaction\_id**, **contemplado na sessão de transações**.



## 4. Manipulação de Dados:

* Valide sempre os dados de entrada antes de enviar requisições para a API passiva.
* Trate e interprete corretamente as respostas da API, considerando cenários de sucesso e de falha.

## 5. Monitoramento e Logs:

* Implemente sistemas de monitoramento para acompanhar o desempenho e a integridade das chamadas de API.
* Registre de forma adequada todos os logs relacionados às interações com a API, facilitando a detecção e resolução de problemas.

## 6. Segurança:

* Utilize conexões seguras (HTTPS) para todas as comunicações com a API.
* Considere a implementação de práticas de segurança adicionais, como criptografia de dados sensíveis e assinaturas de mensagem.

## 7. Manutenção e Atualizações:

* Mantenha-se atualizado com as mudanças na API, verificando regularmente por atualizações e novas versões.
* Esteja preparado para lidar com depreciações de funcionalidades e ajustes de comportamento conforme necessário.

## 8. Documentação Interna:

* Mantenha uma documentação interna detalhada sobre a integração com a API, incluindo exemplos de código, procedimentos de configuração e troubleshooting.

## Conclusão:

O uso responsável e eficaz de APIs passivas é fundamental para garantir a interoperabilidade e o sucesso de sistemas e serviços. Ao seguir as boas práticas delineadas neste manual, você estará contribuindo para a estabilidade, segurança e eficiência das suas integrações com APIs passivas.

\
