<table width="100%" border="0" cellspacing="0" cellpadding="0" style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="left" width="20%" style="border: none;">
      <img src="logo_ngeo.png" alt="Logo NGEO" height="100">
    </td>
    <td width="60%" style="border: none;"></td>
    <td align="right" width="20%" style="border: none;">
      <img src="logo-Ideflor-bio.png" alt="Logo IDEFLOR-Bio" height="100">
    </td>
  </tr>
  <tr style="border: none;">
    <td style="border: none;"></td>
    <td align="center" style="border: none;">
      <h1>NGEO/IDEFLOR-Bio</h1>
    </td>
    <td style="border: none;"></td>
  </tr>
  <tr style="border: none;">
    <td style="border: none;"></td>
    <td align="center" style="border: none;">
      <b>Espaço de Colaboração e Desenvolvimento</b>
    </td>
    <td style="border: none;"></td>
  </tr>
</table>

<img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIzIiB2aWV3Qm94PSIwIDAgMTAwIDMiIHByZXNlcnZlQXNwZWN0UmF0aW89Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjEwMCIgaGVpZ2h0PSIzIiBmaWxsPSIjMmU3ZDMyIi8+PC9zdmc+" width="100%" height="3" style="display: block; margin: 10px 0;">

<p align="center">
Esta organização constitui o ambiente de trabalho institucional do <b>NGEO/IDEFLOR-Bio</b> no GitHub. Este espaço centraliza a governança de projetos, o desenvolvimento de scripts de automação e o versionamento de toda a documentação técnica produzida pelo Núcleo de Geotecnologias, assegurando a padronização e a rastreabilidade dos ativos digitais.
</p>

---

<div align="center">

> **Bem-vindo(a), Visitante!**
> 
> Você chegou ao espaço de colaboração do **Núcleo de Geotecnologias (NGEO)** do **IDEFLOR-Bio**. Se você não é membro da equipe, confira nossos [repositórios públicos](https://github.com/orgs/NGEO-IDEFLOR-Bio/repositories) e a documentação de cada projeto.

</div>

---

## 1. Composição da Equipe Técnica

A equipe do Núcleo de Geotecnologias (NGEO) é composta pelos seguintes membros:

| Nome | Cargo / Função |
| :--- | :--- |
| **Samuel Santos** | Coordenador |
| **Elberth Sales** | Analista Ambiental |
| **Marcus Vinícius** | Analista Ambiental |
| **Samyra Neves** | Analista Ambiental |
| **Mônica Dias** | Estagiária |
| **Mateus Dias** | Técnico Administrativo |

<br>

<div align="center">
  <a href="https://github.com/orgs/NGEO-IDEFLOR-Bio/repositories">
    <b>Acessar Repositórios da Organização</b>
  </a>
</div>

---

## 2. Acesso aos Projetos e Repositórios

Diferente dos repositórios de projeto, este espaço organizacional não armazena ativos de código, scripts ou bases de dados. Cada iniciativa possui seu próprio repositório dedicado, onde o versionamento é realizado de forma isolada, respeitando os níveis de visibilidade (público ou privado) conforme a sensibilidade dos dados.

<div align="center">

**[Repositórios da Organização NGEO-IDEFLOR-Bio](https://github.com/orgs/NGEO-IDEFLOR-Bio/repositories)**

</div>

---

## 3. Diretrizes de Segurança e Protocolos de Commit

Para assegurar a integridade das automações e a proteção dos dados institucionais, todos os colaboradores devem aderir aos seguintes protocolos:

### 3.1. Segurança da Informação

* **Credenciais e Segredos:** É terminantemente proibido o armazenamento de senhas, chaves de API, tokens de acesso ou strings de conexão em texto claro. Utilize variáveis de ambiente ou o recurso de *GitHub Secrets* do repositório correspondente.
* **Proteção de Dados:** Não realize commits contendo bases de dados brutas ou informações que violem a segurança da informação institucional, a menos que o repositório seja privado e autorizado para tal fim.

### 3.2. Padronização de Mensagens de Versionamento

As mensagens de commit devem ser redigidas de forma técnica, impessoal e descrever objetivamente a alteração:

| Tipo | Descrição |
| :--- | :--- |
| `feat` | Inclusão de nova funcionalidade ou script de automação |
| `fix` | Correção de erros lógicos ou bugs em scripts existentes |
| `docs` | Atualizações exclusivas em arquivos de documentação e manuais |
| `refactor` | Melhorias na estrutura do código que não alteram sua funcionalidade |

---

## 4. Organização de Projetos

Cada repositório dentro desta organização deve conter seu próprio arquivo `README.md` detalhando:

1. **Objetivo do projeto.**
2. **Pré-requisitos de software** (versões de Python, extensões do QGIS, dependências de banco de dados).
3. **Instruções de configuração e execução.**
4. **Dicionário de dados** (para scripts de manipulação de tabelas).