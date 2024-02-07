# README.md

## Sistema de Gerenciamento de Alunos

Este é um simples sistema de gerenciamento de alunos implementado em Python, utilizando classes e herança. O sistema inclui uma classe abstrata `Pessoa` que serve como base para a classe concreta `AlunoGraduacao`. O código está organizado em três arquivos:

- `Pessoa.py`: Define a classe abstrata Pessoa, que contém métodos e propriedades comuns a todas as pessoas. Possui métodos abstratos que devem ser implementados por subclasses.

- `AlunoGraduacao.py`: Implementa a classe `AlunoGraduacao`, que herda da classe `Pessoa`. Adiciona propriedades específicas de um aluno de graduação, como matrícula e controle de presença. Implementa os métodos abstratos definidos na classe base.

- `main.py`: Utiliza a classe `AlunoGraduacao` para criar instâncias de alunos, matriculá-los, marcar presença, definir matrículas e exibir informações sobre cada aluno.

### Executando o Sistema

Para executar o sistema, basta rodar o arquivo `main.py`. O código de exemplo cria três instâncias de `AlunoGraduacao` e realiza algumas operações, como matrícula, marcação de presença e exibição de informações.

```bash
python main.py
```

### Estrutura do Código

A estrutura do código segue uma hierarquia de classes, onde a classe base `Pessoa` é estendida pela classe `AlunoGraduacao`. As propriedades e métodos específicos de cada classe são definidos para garantir uma organização e reutilização de código.

### Notas

1. **Classe Abstrata Pessoa**: A classe `Pessoa` é uma classe abstrata que contém métodos abstratos. Certifique-se de implementar corretamente esses métodos em subclasses concretas.

2. **Encapsulamento**: Algumas propriedades são definidas como privadas usando duplo underscore (`__`). O acesso a essas propriedades é feito por meio de métodos getter e setter.

3. **Herança e Polimorfismo**: O sistema utiliza herança para estender a classe base e polimorfismo para sobrescrever métodos conforme necessário.

4. **Entrada do Usuário**: O código pode solicitar entrada do usuário para adicionar o número de matrícula e marcar presença.
