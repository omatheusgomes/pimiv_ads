## Padrão de Mensagens dos Commits

A padronização de mensagens de commits é uma prática importante, pois, além de ajudar na compreensão do histórico de commits, facilita a criação de ferramentas automatizadas baseadas na especificação.  
Existe um padrão convencional de mensagens: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).  
Porém, visando simplificar:

### Tipos de Commit

| Tipo      | Descrição                                                     | Exemplo                                                                                       |
|-----------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| feat      | Quando da adição de um recurso, uma “feature” (funcionalidade)| feat (AB-1243, AB-56): Implementação dos repositories usados nas operações com as tabelas de variações climáticas |
| fix       | Correção de um bug                                            | fix (#45): Correção do componente de seleção de município                                     |
| docs      | Atualização de documentação                                   | docs (#45): inclusão de diagrama de modelo de BD para a aplicação                             |
| style     | Mudança de formatação, sem afetar o código                   | style (AB-1243, AB-56): ajuste de nomes de variáveis para o padrão camelCase                  |
| refactor  | Refatoração do código, sem alterar funcionalidade            | Seguir exemplos anteriores, alterando o tipo, IDs e descrições correspondentes                |
| test      | Adiciona ou modifica testes                                   | Seguir exemplos anteriores, alterando o tipo, IDs e descrições correspondentes                |
| chore     | Atualizações menores que não impactam diretamente a funcionalidade do código | Seguir exemplos anteriores, alterando o tipo, IDs e descrições correspondentes                |

---

- `<id_demandaN>`: Identificador da demanda criada na ferramenta de gestão de Stories/Tasks que o Time estiver usando (GitHub Issues, Jira, GitLab Issues, etc.), podendo estar entre 1 e N.  
- `<descrição da entrega feita no commit>`: Descrição clara sobre o que está sendo entregue no commit criado e enviado para o Git.
