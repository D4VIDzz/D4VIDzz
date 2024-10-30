<br clear="both">

<h3 align="center">| Sobre mim |</h3>

###

<br clear="both">

<p align="center">| Estudante de programaçã | Em busca de uma carreira |</p>

###

<div align="center">
  <a href="https://www.linkedin.com/in/lucasbezerra2002/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://www.instagram.com/d4vidls/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="52" height="40" alt="instagram logo"  />
  </a>
  <a href="contatolucasbezerraa@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
  </a>
</div>

###

<br clear="both">

<h3 align="center">| Linguagens |</h3>

###

<div align="center">
  <img src="https://skillicons.dev/icons?i=py" height="40" alt="python logo"  />
</div>

###

<br clear="both">

<h3 align="center">| Estatísticas |</h3>

###

<br clear="both">

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=D4VIDz&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=radical&locale=pt-br&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=D4VIDz&locale=pt-br&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=radical&hide_border=false&order=2" height="150" alt="languages graph"  />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=D4VIDz&radius=16&theme=redical&area=true&order=5" height="300" alt="activity-graph graph"  />
</div>

###

<div align="center">
  <a href="https://open.spotify.com/user/3176jmmxkz62r4jjpgnwvjikms54">
    <img src="https://spotify-recently-played-readme.vercel.app/api?user=3176jmmxkz62r4jjpgnwvjikms54&count=1&unique=true" alt="Spotify recently played"  />
  </a>
</div>

      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
