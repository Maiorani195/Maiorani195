Used tool: read_url_content
Viewed content.md:1-11
Ran command: `powershell -Command "Get-Content 'C:\Users\ferna\.gemini\antigravity\brain\ee5e7653-c93b-42dc-9583-c192fbd9d0cc\.system_generated\steps\2\content.md' | Select-Object -Skip 8 | ConvertFrom-Json | Select-Object name, html_url, description, language, updated_at | Format-Table -AutoSize"`
Ran command: `powershell -Command "$json = Get-Content 'C:\Users\ferna\.gemini\antigravity\brain\ee5e7653-c93b-42dc-9583-c192fbd9d0cc\.system_generated\steps\2\content.md' -Raw; $json = $json.Substring($json.IndexOf('[')); $repos = $json | ConvertFrom-Json; $repos | Select-Object name, description, language, updated_at, pushed_at | Format-Table -AutoSize"`
Ran command: `python -c "import json; f=open(r'C:\Users\ferna\.gemini\antigravity\brain\ee5e7653-c93b-42dc-9583-c192fbd9d0cc\.system_generated\steps\2\content.md', encoding='utf-8').read(); idx=f.find('['); data=json.loads(f[idx:]); print('\n'.join(f'{r[\"name\"]} | {r.get(\"language\")} | {r.get(\"description\")} | {r.get(\"pushed_at\")}' for r in data))"`
Created list_repos.py
Ran command: `python C:\Users\ferna\.gemini\antigravity\brain\ee5e7653-c93b-42dc-9583-c192fbd9d0cc\scratch\list_repos.py`
Ran command: `python -c "import urllib.request, json; [print(f'=== {repo} ===\n', urllib.request.urlopen(f'https://raw.githubusercontent.com/Maiorani195/{repo}/main/README.md').read().decode('utf-8', errors='ignore')[:600]) for repo in ['ContainerWatch', 'TechDesk', 'Projetos-Linux-Bash']]"`
Ran command: `python -c "import urllib.request; print(urllib.request.urlopen('https://raw.githubusercontent.com/Maiorani195/ContainerWatch/main/README.md').read().decode('utf-8', errors='ignore'))"`
Created fetch_readmes.py
Ran command: `python C:\Users\ferna\.gemini\antigravity\brain\ee5e7653-c93b-42dc-9583-c192fbd9d0cc\scratch\fetch_readmes.py`
Viewed ContainerWatch_README.md:1-100
Viewed TechDesk_README.md:1-68

Aqui está uma versão **moderna, minimalista e de alto impacto** do seu perfil do GitHub.

### 🌟 O que foi aprimorado para deixar mais *clean* e profissional:
1. **Novos Projetos em Destaque adicionados**:
   - **`ContainerWatch`** (Seu mais recente e de maior destaque técnico: reúne Docker, Spring Boot, PostgreSQL e scripts Shell para auto-recuperação de containers — casa perfeitamente com seu foco em Back-end + Infra).
   - **`TechDesk`** (Sistema de Service Desk demonstrando domínio de Spring Data JPA, relacionamentos e JPQL).
2. **Novas Stacks integradas**: Adicionados **Docker** e **PostgreSQL**, fundamentais para vagas de Back-end e Infraestrutura.
3. **Design Clean e Responsivo**:
   - Remoção de tags `<br/>` excessivas e espaçamentos artificiais.
   - Tabela de projetos padronizada com badges uniformes (`flat-square` discreto e elegante) e descrição orientada a valor (o que o projeto resolve).
   - Seção de stacks agrupadas harmoniosamente, sem blocos pesados.

---

### 📋 Código atualizado do `README.md`:

```markdown
<div align="center">

  <!-- Header Dinâmico -->
  <a href="https://github.com/Maiorani195">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2&height=210&section=header&text=Fernando%20Maiorani&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Engenharia%20Back-end%20%7C%20Linux%20%26%20Infraestrutura%20%7C%20ADS%20FIAP&descAlignY=58&descSize=15" width="100%" />
  </a>

  <!-- Typing SVG -->
  <p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&duration=3200&pause=1000&color=50FA7B&center=true&vCenter=true&multiline=false&width=620&lines=%3E_Engenharia+de+Software+Back-end+com+Java+%26+Python;%3E_Docker,+Observabilidade,+Linux+e+Seguran%C3%A7a;%3E_APIs+com+Spring+Boot,+FastAPI+e+Bancos+de+Dados;%3E_Graduando+em+ADS+na+FIAP+(Conclus%C3%A3o+12%2F2028)" alt="Typing SVG" />
  </p>

  <!-- Redes e Contato -->
  <p align="center">
    <a href="https://www.linkedin.com/in/fernandomaiorani/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:maioraniifernando@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
  </p>

</div>

---

### 🧠 Sobre Mim & Foco Técnico

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🔒 Redes, Linux & Infraestrutura</h4>
      <ul>
        <li><b>Observabilidade & Containers:</b> deploy, isolamento e auto-healing com <b>Docker</b> e Shell.</li>
        <li><b>Linux & Shell Script:</b> rotinas de automação, processamento de logs e monitoramento proativo.</li>
        <li><b>Redes:</b> arquitetura de protocolos (TCP/IP, DNS, roteamento, IPv6).</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚙️ Engenharia Back-end</h4>
      <ul>
        <li>🎓 Cursando <b>Análise e Desenvolvimento de Sistemas na FIAP</b>.</li>
        <li>Desenvolvimento com <b>Java (Spring Boot, JPA)</b> e <b>Python (FastAPI, Flask)</b>.</li>
        <li>Modelagem & Persistência: <b>PostgreSQL, Oracle SQL, MongoDB e SQLite</b>.</li>
        <li>Construção de APIs RESTful, automação assíncrona e arquitetura em camadas.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Stacks & Tecnologias

<div align="center">

<p><b>Linguagens & Frameworks</b></p>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />

<p><b>Bancos de Dados & Persistência</b></p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Oracle_SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />

<p><b>Infraestrutura, DevOps & Ferramentas</b></p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />

</div>

---

### 📌 Projetos em Destaque

<table width="100%">
  <thead>
    <tr>
      <th width="28%" align="left">Projeto</th>
      <th width="48%" align="left">Descrição</th>
      <th width="24%" align="left">Stack Principal</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        🐳 <b><a href="https://github.com/Maiorani195/ContainerWatch" target="_blank">ContainerWatch</a></b><br/>
        <img src="https://img.shields.io/badge/Destaque-50fa7b?style=flat-square" />
      </td>
      <td>Plataforma de auto-recuperação e observabilidade para Docker. Monitora serviços, detecta quedas, reinicia containers automaticamente e persiste telemetria e eventos via API REST.</td>
      <td><code>Java</code> <code>Spring Boot</code> <code>Docker</code> <code>PostgreSQL</code> <code>Shell</code></td>
    </tr>
    <tr>
      <td>
        🛡️ <b><a href="https://github.com/Maiorani195/LogSentinel" target="_blank">LogSentinel</a></b><br/>
        <img src="https://img.shields.io/badge/Concluído-50fa7b?style=flat-square" />
      </td>
      <td>Monitor de logs em tempo real via WatchService. Detecta brute-force, falhas em cascata e dispara alertas imediatos no Slack com persistência assíncrona.</td>
      <td><code>Java</code> <code>Spring Boot</code> <code>SQLite</code> <code>WatchService</code></td>
    </tr>
    <tr>
      <td>
        🎫 <b><a href="https://github.com/Maiorani195/TechDesk" target="_blank">TechDesk</a></b><br/>
        <img src="https://img.shields.io/badge/Concluído-50fa7b?style=flat-square" />
      </td>
      <td>Core de sistema de chamados de TI com foco em consultas JPQL complexas, regras de negócio para tickets críticos e modelagem relacional avançada com JPA.</td>
      <td><code>Java</code> <code>Spring Data JPA</code> <code>Hibernate</code> <code>H2</code></td>
    </tr>
    <tr>
      <td>
        🚀 <b><a href="https://github.com/Maiorani195/Dev-Job" target="_blank">Dev-Job</a></b><br/>
        <img src="https://img.shields.io/badge/Concluído-50fa7b?style=flat-square" />
      </td>
      <td>Pipeline assíncrono de web scraping, deduplicação de vagas e API REST para agregação e consulta de oportunidades de tecnologia.</td>
      <td><code>Python</code> <code>FastAPI</code> <code>SQL</code> <code>Scraping</code></td>
    </tr>
    <tr>
      <td>
        🌍 <b><a href="https://github.com/Maiorani195/Earth-1-17" target="_blank">Earth 1-17</a></b><br/>
        <img src="https://img.shields.io/badge/Nota_9_FIAP-50fa7b?style=flat-square" />
      </td>
      <td>Telemetria climática e satélite com IA. Modelagem relacional completa em Oracle SQL desenvolvida e aprovada com nota de destaque na FIAP.</td>
      <td><code>Oracle SQL</code> <code>MER</code> <code>Python</code> <code>IA</code></td>
    </tr>
    <tr>
      <td>
        📱 <b><a href="https://github.com/Maiorani195/Jovi-Leans" target="_blank">Jovi Leans</a></b><br/>
        <img src="https://img.shields.io/badge/Em_Andamento-bd93f9?style=flat-square" />
      </td>
      <td>Challenge corporativo FIAP integrando visão computacional e modelos de IA para análise de imagem em tempo real em dispositivos móveis.</td>
      <td><code>Python</code> <code>Visão Computacional</code> <code>IA</code></td>
    </tr>
  </tbody>
</table>

---

### 🔥 Atividade no GitHub

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Maiorani195&theme=dracula&hide_border=true&border_radius=8&date_format=j%2Fn%5B%2FY%5D&locale=pt_BR" alt="GitHub Streak Stats" />
</div>

---

### 📜 Certificações & Especializações

<table>
  <tr>
    <td width="50%" valign="top">
      <b>🌐 Redes, Sistemas & Linux</b>
      <ul>
        <li><b>Redes e Protocolos:</b> Roteamento, DNS, IPv6 e TCP/IP (Alura)</li>
        <li><b>Linux:</b> Shell Scripting, Automação, Permissões e Gestão de Processos (Alura)</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>☕ Software, Dados & APIs</b>
      <ul>
        <li><b>Java & Spring Boot:</b> APIs RESTful, Spring Data JPA e Arquitetura Limpa</li>
        <li><b>Python & APIs:</b> Django ORM, Flask com MongoDB e POO (Alura)</li>
        <li><b>Bancos de Dados:</b> Modelagem Relacional e Consultas Avançadas em SQL</li>
      </ul>
    </td>
  </tr>
</table>

<p align="right">
  <a href="https://www.linkedin.com/in/fernandomaiorani/details/certifications/" target="_blank">
    <img src="https://img.shields.io/badge/Ver_todas_no_LinkedIn_↗-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="Ver Certificações no LinkedIn" />
  </a>
</p>
```
