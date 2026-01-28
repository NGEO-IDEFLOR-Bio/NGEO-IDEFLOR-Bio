# NGEO/IDEFLOR-Bio: Espaço de Colaboração e Desenvolvimento

Esta organização constitui o ambiente de trabalho institucional do NGEO/IDEFLOR-Bio no GitHub. Este espaço centraliza a governança de projetos, o desenvolvimento de scripts de automação e o versionamento de toda a documentação técnica produzida pelo Núcleo de Geotecnologias, assegurando a padronização e a rastreabilidade dos ativos digitais

---

## 1. Composição da Equipe Técnica

A equipe do Núcleo de Geotecnologias (NGEO) é composta pelos seguintes membros:

| Nome | Função / Cargo |
| --- | --- |
| **Samuel Santos** | Coordenador |
| **Elberth Sales** | Analista Ambiental |
| **Marcus Vinícius** | Analista Ambiental |
| **Samyra Neves** | Analista Ambiental |
| **Mônica Dias** | Estagiária |
| **Mateus Dias** | Técnico Administrativo |

---

## 2. Acesso aos Projetos e Repositórios

Diferente dos repositórios de projeto, este espaço organizacional não armazena ativos de código, scripts ou bases de dados. Cada iniciativa possui seu próprio repositório dedicado, onde o versionamento é realizado de forma isolada, respeitando os níveis de visibilidade (público ou privado) conforme a sensibilidade dos dados.

Acesse a lista completa de projetos em:
**[Repositórios da Organização NGEO-IDEFLOR-Bio](https://github.com/orgs/NGEO-IDEFLOR-Bio/repositories)**

---

## 3. Diretrizes de Segurança e Protocolos de Commit

Para assegurar a integridade das automações e a proteção dos dados institucionais, todos os colaboradores devem aderir aos seguintes protocolos:

### 3.1. Segurança da Informação

* **Credenciais e Segredos:** É terminantemente proibido o armazenamento de senhas, chaves de API, tokens de acesso ou strings de conexão em texto claro. Utilize variáveis de ambiente ou o recurso de *GitHub Secrets* do repositório correspondente.
* **Proteção de Dados:** Não realize commits contendo bases de dados brutas ou informações que violem a segurança da informação institucional, a menos que o repositório seja privado e autorizado para tal fim.

### 3.2. Padronização de Mensagens de Versionamento

As mensagens de commit devem ser redigidas de forma técnica, impessoal e descrever objetivamente a alteração:

* `feat`: Inclusão de nova funcionalidade ou script de automação.
* `fix`: Correção de erros lógicos ou bugs em scripts existentes.
* `docs`: Atualizações exclusivas em arquivos de documentação e manuais.
* `refactor`: Melhorias na estrutura do código que não alteram sua funcionalidade.

---

## 4. Organização de Projetos

Cada repositório dentro desta organização deve conter seu próprio arquivo `README.md` detalhando:

1. **Objetivo do projeto.**
2. **Pré-requisitos de software** (versões de Python, extensões do QGIS, dependências de banco de dados).
3. **Instruções de configuração e execução.**
4. **Dicionário de dados** (para scripts de manipulação de tabelas).

---

Gostaria que eu elaborasse um **template padrão de README** para ser replicado nos novos repositórios de projetos de automação da equipe?
