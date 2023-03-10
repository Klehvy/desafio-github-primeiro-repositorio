# desafio-github-primeiro-repositorio
Meu desafio GitHub

*Assuntos Importantes*
## https://web.dio.me/course/trabalhando-em-equipes-ageis/learning/1efc7ad9-a0be-4144-8ed4-dbcdd7c3a948?back=/track/banco-pan-java-developer&tab=undefined&moduleId=undefined
## https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9?back=/track/banco-pan-java-developer&tab=undefined&moduleId=undefined
--------------------------------------------------------------------------------------------------------------------------------------------------------
Primeiro teste em HTML/CSS/JAVASCRIPT

Desenvolvido site simples para teste.

Codigos CSS/ JAVASCRIP
:root {
    --green: #00FF00;
    --white: #ffffff;
    --black: #000000;
}

*{
    color: var(--fontColor);
    font-family: helvetica;
}

body {
    background: var(--bg);
}

ul {
    font-family: helvetica;
}

li {
    list-style: circle;
}

.list {
    list-style: square;
}

.light-theme {
    --bg: var(--green);
    --fontColor: var(--black);
    --btnbg: var(--black);
    --btnfontColor: var(--white);
}

.dark-theme {
    --bg: var(--black);
    --fontColor: var(--green);
    --btnbg: var(--white);
    --btnfontColor: var(--black);
}

.btn {
    position: absolute;
    top: 20px;
    left: 250px;
    height: 50px;
    width: 50px;
    border-radius: 50%;
    border: none;
    color: var(--btnfontColor);
    background-color: var(--btnbg);
}

.btn:focus{
    outline-style: none;
}
