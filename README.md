# Designs Patterns

Foi feito um jogo em java seguindo os padrões de POO(Programação Orienatda a Objeto).
Nesse jogo funciona como um RPG de turno, ou seja, uma hora o personagem ataca e outra ele defende.

Existem quatros botões na interface realizam o funcionamento desse jogo.
- Ataque
- Defesa
- Poder Especial
- Trocar Personagem

O jogo consiste em 4 fases de níveis incrementais, ou seja, a cada inimigo derrotado fica mais difícil de derrotar o próximo

## 1. Factory - Criacional
<img width="292" alt="Factory" src="https://github.com/user-attachments/assets/43db4cad-6b20-4e08-a12a-63db3aa17878">
<p></p>
A classe Character é abstrata, o que implica que serão criadas subclasses concretas (como Warrior, Mage, etc.) que instanciam personagens específicos.

---

## 2. State - Comportamental
![Captura de tela 2024-12-09 144841](https://github.com/user-attachments/assets/1108962f-3a61-4294-8cf1-54ad48191fb2)
<p></p>
O uso de variáveis como action e currentHero para determinar o comportamento do sistema com base no estado atual é uma forma de implementar o padrão State.

---

## 3. Command - Comportalmental
![Captura de tela 2024-12-09 140151](https://github.com/user-attachments/assets/446ba638-68d9-4d9c-8f7e-4e0cd14309e9)
<p></p>
Os botões criados (JButton) encapsulam comandos que são executados quando clicados. O comportamento associado a cada botão pode ser interpretado como a execução de um comando.

---

## 4. Composite - Estrutural
![Captura de tela 2024-12-09 141102](https://github.com/user-attachments/assets/7cf4e93e-c677-49b3-915d-e60e3bd09ce9)
<p></p>
O uso de JPanel como um contêiner para organizar botões e outros componentes reflete o padrão Composite. Cada JPanel pode conter outros componentes, e o layout é configurado recursivamente.

---

## 5. Mediator - Comportamental
![Captura de tela 2024-12-09 142323](https://github.com/user-attachments/assets/0e6ff7d5-387c-4846-9bc6-7c2b51556014)
<p></p>
O PopUp atua como um mediador para gerenciar a interação entre o jogador e a escolha do personagem. Ele encapsula as interações e comunica o resultado ao sistema principal.


