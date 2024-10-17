# Organização de Horários

Este projeto é uma aplicação de gerenciamento de horários escolares desenvolvida em Python, utilizando PySide2 para a interface gráfica. O objetivo é facilitar o cadastro de professores, turmas e disciplinas, além de permitir a geração de horários sem conflitos.

## Funcionalidades

- **Cadastro de Professores**: Adicione os nomes dos professores e defina quantas aulas cada um possui por dia e por semana.
- **Cadastro de Turmas**: Registre as turmas, incluindo o ano e a série.
- **Cadastro de Disciplinas**: Cadastra disciplinas e associa-as aos professores e turmas.
- **Gestão de Horários**: Gere horários automaticamente, evitando sobreposição de aulas.
- **Visualização de Horários**: Exiba o horário semanal completo, com opções de filtragem por professor, turma e disciplina.
- **Validação de Conflitos**: Impede agendamentos simultâneos para o mesmo professor ou turma.
- **Flexibilidade**: Permite ajustes manuais nos horários, com alertas para conflitos.
- **Exportação em PDF**: Salve o horário semanal gerado em formato PDF na pasta de Downloads.

## Etapas para o Desenvolvimento

1. **Adicionar Curso**: Interface para adicionar novos cursos.
2. **Adicionar Disciplina**: Funcionalidade para registrar novas disciplinas.
3. **Adicionar Professores**: Após adicionar um professor, insira a quantidade de aulas por semana e decida se deseja adicionar mais professores.
4. **Organizar a Distribuição de Horários**: Algoritmo que distribui automaticamente os horários respeitando as regras de conflito.
5. **Visualizar na Tela**: Botão para visualizar os horários organizados, mostrando professor, disciplina e a distribuição semanal.
6. **Salvar Documento PDF**: Ao gerar o PDF, arquivos são salvos com auto incremento na pasta Downloads.
7. **Registro de Horário Manual**: Campo para registro manual que tem prioridade sobre os horários automáticos.

## Tecnologias Utilizadas

- Python
- PySide6
- FPDF

## Instalação

Para instalar as dependências do projeto, utilize o seguinte comando:

```bash
pip install PySide6 fpdf
```

## Uso

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/OrganizacaoDeHorario.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd OrganizacaoDeHorario
   ```
3. Execute a aplicação:
   ```bash
   python main.py
   ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

