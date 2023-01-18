## Bem-vindo(a) ao perfil do Diogo 😃

 <div>
   <a href="https://github.com/diogo-lima12">
   <img height="180em" src="https://github-readme-stats.vercel.app/api?username=diogo-lima12_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
   <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=diogo-lima£layout=compact&langs_count=6&theme=tokyonight"/>

</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg ">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg ">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg ">
</div>
 
 <br>
 
  ### Pra conteúdo sobre programação me segue a gente nas redes abaixo!
 
<div>
  <a href="target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the- badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:gemeos@devemdobro.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" alvo ="_blank"></a>
  <a href="https://www.linkedin.com/in/ricardohdias" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style= for-the-badge&logo=linkedin&logoColor=white" target="_b


Nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * */12 * * * "
  workflow_dispatch :

empregos :
  construir :
    nome : Jobs para atualizar dados
    run-on : ubuntu-latest
    passos :
      # Animação de Cobra
      - usa : Platane/snk@master
        id : cobra-gif
        com :
          github_user_name : diogo
          svg_out_path : dist/github-contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : saída
          build_dir : dist
        ambiente :
          GITHUB_TOKEN : ${{ segredos.GITHUB_TOKEN }}
