##  Database Seeder & Initializer v5.0

O trigésimo segundo projeto foca na automação de infraestrutura de dados. O objetivo é garantir que o sistema de biblioteca tenha um ambiente de teste pronto com dados reais e consistentes.

##  Funcionalidades Técnicas
- **Database Reset:** Limpeza automática de tabelas pré-existentes para evitar conflitos de ID.
- **Batch Processing:** Uso de `executemany` para inserção otimizada de listas de autores, livros e registros de empréstimo.
- **Data Integrity:** Implementação rigorosa de relacionamentos entre tabelas (Autores -> Livros -> Empréstimos).

##  Conteúdo do Acervo Inicial
- Autores renomados como J.K. Rowling e Stephen King.
- Gêneros diversificados (Fantasia, Mistério, Terror).
- Histórico de empréstimos com status de devolução (Ativos e Finalizados).

##  Aprendizados
- Manipulação de listas e tuplas para alimentação de SQL.
- Formatação de datas em formato TEXT (padrão ISO 8601: YYYY-MM-DD) para compatibilidade futura.
