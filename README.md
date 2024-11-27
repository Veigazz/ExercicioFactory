# Exercício: Padrão de Projeto Factory Method
Este projeto foi desenvolvido como parte de uma apresentação acadêmica para a disciplina de **Fundamentos de Desenvolvimento de Sistemas Computacionais** da **Turma 3A (2024/2)**, no **IFSUL - Campus Sapucaia do Sul**.

## Descrição
O padrão **Factory Method** é um padrão de criação que fornece uma interface para instanciar objetos, permitindo que subclasses definam qual classe será instanciada. Ele reduz o acoplamento entre o código que usa os objetos e suas implementações concretas.

### Exemplo Implementado: Polígonos
O sistema foi desenvolvido para gerar diferentes tipos de polígonos com base no número de lados.

**Triângulo**: 3 lados.

**Quadrado**: 4 lados.

**Pentágono**: 5 lados.

### Estrutura do Projeto
**Interface base** (Poligono): Define o contrato para os polígonos.

**Classes concretas**: Representam diferentes tipos de polígonos.

**Fábrica** (PoligonoFactory): Método responsável por criar os objetos baseados no número de lados.

**Classe principal** (MainTeste): Demonstra o uso do padrão Factory Method.

### Benefícios do Padrão
Reduz o acoplamento entre o criador e os produtos concretos.

Segue os princípios **Aberto/Fechado** e **Responsabilidade Única**.

### Arquivo PDF da apresentação
[Aula 1 – Padrões de Criação.pdf](https://github.com/user-attachments/files/17938532/Aula.1.Padroes.de.Criacao.pdf)

