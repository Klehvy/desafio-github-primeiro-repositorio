# desafio-github-primeiro-repositorio
Meu desafio GitHub

*Assuntos Importantes*
## https://web.dio.me/course/trabalhando-em-equipes-ageis/learning/1efc7ad9-a0be-4144-8ed4-dbcdd7c3a948?back=/track/banco-pan-java-developer&tab=undefined&moduleId=undefined
## https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9?back=/track/banco-pan-java-developer&tab=undefined&moduleId=undefined
--------------------------------------------------------------------------------------------------------------------------------------------------------
Primeiro teste em HTML/CSS/JAVASCRIPT

Desenvolvido site simples para teste.

Codigo JAVASCRIPT

'use strict'

const switcher = document.querySelector('.btn');


switcher.addEventListener('click', function() {
    document.body.classList.toggle('dark-theme')

    var className = document.body.className;
    if(className == "light-theme") {
        this.textContent - "dark";
    }
    
    else{
        this.textContent - "ligth";
    }
}); 
