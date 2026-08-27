<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:6C3EF4,100:00D9FF&height=220&section=header&text=Guilherme%20Lima%20Lopes&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=Code%20%2B%20Data%20%2B%20AI&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=650&lines=%24+whoami;Desenvolvedor+na+2WP+%7C+WordPress;Ci%C3%AAncia+de+Dados+na+FIAP;Formado+em+Dev+pelo+SENAI;Prototipando+com+IA%3A+Claude+%2F+Codex+%2F+Antigravity" alt="typing" />
<br/>
![LinkedIn](https://img.shields.io/badge/-guilherme--lima--lopes-1a1a2e?style=flat-square&logo=linkedin&logoColor=00D9FF)
![Instagram](https://img.shields.io/badge/-_whoslima-1a1a2e?style=flat-square&logo=instagram&logoColor=00D9FF)
![Gmail](https://img.shields.io/badge/-guilopes0510%40gmail.com-1a1a2e?style=flat-square&logo=gmail&logoColor=00D9FF)
</div>
<br/>
```bash
guilherme@dev:~$ cat sobre_mim.txt
------------------------------------------------------------------
> Desenvolvedor na 2WP, atuando com WordPress no dia a dia
> Estudante de Ciência de Dados na FIAP
> Formado em Desenvolvimento de Sistemas pelo SENAI
> Integrando IA (Claude, Codex, Antigravity) ao fluxo de trabalho
> Aprendendo a transformar dado em decisão e código em produto
------------------------------------------------------------------
guilherme@dev:~$ _
```
<br/>
<img src="https://skillicons.dev/icons?i=react&theme=dark" width="26"/> Stack
<table width="100%">
<tr>
<td width="50%" valign="top">
Back-end & Dados
<br/>
<img src="https://skillicons.dev/icons?i=python,django,mysql,nodejs&theme=dark" />
</td>
<td width="50%" valign="top">
Front-end & Web
<br/>
<img src="https://skillicons.dev/icons?i=javascript,html,css,wordpress&theme=dark" />
</td>
</tr>
<tr>
<td width="50%" valign="top">
Banco de Dados
<br/>
<img src="https://skillicons.dev/icons?i=mysql,sqlite&theme=dark" />
</td>
<td width="50%" valign="top">
IA no fluxo de trabalho
<br/>
<img src="https://img.shields.io/badge/Claude-1a1a2e?style=flat-square&logo=anthropic&logoColor=D97757"/> <img src="https://img.shields.io/badge/Codex-1a1a2e?style=flat-square&logo=openai&logoColor=ffffff"/> <img src="https://img.shields.io/badge/Antigravity-1a1a2e?style=flat-square&logo=google&logoColor=4285F4"/>
</td>
</tr>
</table>
<br/>
<img src="https://skillicons.dev/icons?i=vscode&theme=dark" width="26"/> Trajetória
```mermaid
graph LR
    A[SENAI<br/>Dev de Sistemas<br/>✅ Concluído] --> B[2WP<br/>Dev WordPress<br/>💼 Atual]
    B --> C[FIAP<br/>Ciência de Dados<br/>🔄 Em andamento]
    C --> D[( Próximo capítulo )]

    style A fill:#1a1a2e,stroke:#00D9FF,stroke-width:2px,color:#ffffff
    style B fill:#1a1a2e,stroke:#6C3EF4,stroke-width:2px,color:#ffffff
    style C fill:#1a1a2e,stroke:#00D9FF,stroke-width:2px,color:#ffffff
    style D fill:#0d0d1a,stroke:#6C3EF4,stroke-width:1px,stroke-dasharray: 4 4,color:#8888aa
```
<br/>
<img src="https://skillicons.dev/icons?i=githubactions&theme=dark" width="26"/> Métricas
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Gui-Lops&show_icons=true&theme=dracula&hide_border=true&bg_color=0d0d1a&title_color=00D9FF&icon_color=6C3EF4&text_color=e0e0f0&count_private=true&cache_seconds=1800" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gui-Lops&layout=compact&theme=dracula&hide_border=true&bg_color=0d0d1a&title_color=00D9FF&text_color=e0e0f0&cache_seconds=1800" height="165"/>
<img src="https://streak-stats.demolab.com?user=Gui-Lops&theme=dracula&hide_border=true&background=0D0D1A&stroke=00D9FF&ring=6C3EF4&fire=00D9FF&currStreakLabel=00D9FF" />
</div>
> [!NOTE]
> Esses cartões são gerados em tempo real por serviços públicos (Vercel). Se algum aparecer quebrado, geralmente é rate-limit temporário — dá um refresh na página em alguns minutos que volta ao normal.
<br/>
<img src="https://skillicons.dev/icons?i=github&theme=dark" width="26"/> Snake da contribuição
<div align="center">
<img src="https://raw.githubusercontent.com/Gui-Lops/Gui-Lops/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>
<details>
<summary><b>Como ativar (leva 2 minutos)</b></summary>
<br/>
No repositório `Gui-Lops/Gui-Lops`, crie o arquivo `.github/workflows/snake.yml` com o conteúdo abaixo.
Vá em Settings → Actions → General → Workflow permissions e marque Read and write permissions.
Rode o workflow uma vez em Actions → generate snake → Run workflow.
```yaml
name: generate snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Gui-Lops
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
</details>
<br/>
<img src="https://skillicons.dev/icons?i=github&theme=dark" width="26"/> Formação
Instituição	Curso	Status
FIAP	Ciência de Dados	🔄 Em andamento
SENAI	Desenvolvimento de Sistemas	✅ Concluído
<br/>
<div align="center">
<img src="https://komarev.com/ghpvc/?username=Gui-Lops&label=Visitantes+do+perfil&color=6C3EF4&style=flat-square"/>
<br/><br/>
"Aprendendo, construindo e explorando o mundo do código e dos dados."
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,50:6C3EF4,100:1a1a2e&height=100&section=footer" width="100%"/>
</div>
