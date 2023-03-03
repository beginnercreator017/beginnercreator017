Olá! Eu sou o Thiago, mais um curioso e aspirante no mundo de códigos, programação e desenvolvimento!

<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>
  
  ##
 
<div _
     <a href = "mailto:contatoemailthiagos@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" alvo ="_blank"></a>
  <a href="https://www.linkedin.com/in/thiago-sales-terra" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-% 230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  
</div>

Nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * */12 * * * "
  workflow_dispatch :

trabalhos :
  construir :
    nome : Jobs para atualizar dados
    run-on : ubuntu-latest
    passos :
      # Animação de Cobra
      - usa : Platane/snk@master
        id : cobra-gif
        com :
          github_user_name : beginnercreator017
          svg_out_path : dist/github-contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : saída
          build_dir : dist
        ambiente :
          GITHUB_TOKEN : ${{ segredos.GITHUB_TOKEN }}
          
          
