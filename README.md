<a href="https://github.com/kikukeii"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FkikuKeii&count_bg=%23000884&title_bg=%23569CED&icon=php.svg&icon_color=%23FFFFFF&title=Visited&edge_flat=true"/></a>

##  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png?size=48" width="20" alt="SQL"> SQL
```sql
SELECT p.*, c.country_name, ct.contact_info
FROM peopleMaster p
LEFT JOIN countryMaster c ON p.country_id = c.id
LEFT JOIN contactMaster ct ON p.id = ct.person_id
WHERE p.id IN (
    SELECT DISTINCT p.id
    FROM peopleMaster p
    JOIN skills s ON p.id = s.person_id
    WHERE p.job_title IN ('Full Stack Developer', 'Web Developer', 'Backend Developer')
       OR s.skill_name IN ('PHP', 'Javascript', 'Codeigniter 4', 'Laravel', 'Express js', 'Nodejs')
)
AND p.status = 'available';

```

```json
{
  "status": "success",
  "message": "Thank you for coming here! Results will be displayed if you click on the results below."
}
```

<details>
   <summary>↲ results ⟪23/11/2024⟫  </summary>

<h1 align="center">Hi 👋, I'm Miftakhuddin Falaki</h1>

<h3 align="center"><a href="#"><img src="https://readme-typing-svg.herokuapp.com?font=Poppies&weight=1000&pause=1000&color=EE4D2D&center=true&random=false&width=435&lines=I'm+Programmer;+Back-end+Developer;Full-stack+Developer;Web+Developer" alt="Typing SVG" /></a></h3> 

<h1 id="-about-me-">💫 About Me:</h1>
<p>Experienced in developing applications using PHP, JavaScript, RESTful API, and databases such as MySQL, PostgreSQL, and MS SQL Server. Proficient in frameworks like Laravel, CodeIgniter 4, and ExpressJS. Also experienced in providing technical support for user issues and handling application deployment.</p>

---

<h2 id="-socials-">🌐 Socials:</h2>
<p><a href="https://linkedin.com/in/miftakhuddin-falaki"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a> </p>
<h1 id="-tech-stack-">💻 Tech Stack:</h1>
<p><img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&amp;logo=openjdk&amp;logoColor=white" alt="Java"> <img src="https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&amp;logo=kotlin&amp;logoColor=white" alt="Kotlin"> <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&amp;logo=javascript&amp;logoColor=%23F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&amp;logo=Cloudflare&amp;logoColor=white" alt="Cloudflare"> <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Vercel"> <img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&amp;logo=bootstrap&amp;logoColor=white" alt="Bootstrap"> <img src="https://img.shields.io/badge/CodeIgniter-%23EF4223.svg?style=for-the-badge&amp;logo=codeIgniter&amp;logoColor=white" alt="Code-Igniter"> <img src="https://img.shields.io/badge/ejs-%23B4CA65.svg?style=for-the-badge&amp;logo=ejs&amp;logoColor=black" alt="EJS"> <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&amp;logo=express&amp;logoColor=%2361DAFB" alt="Express.js"> <img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&amp;logo=jquery&amp;logoColor=white" alt="jQuery"> <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&amp;logo=JSON%20web%20tokens" alt="JWT"> <img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&amp;logo=laravel&amp;logoColor=white" alt="Laravel"> <img src="https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&amp;logo=npm&amp;logoColor=white" alt="NPM"> <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&amp;logo=next.js&amp;logoColor=white" alt="Next JS"> <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&amp;logo=node.js&amp;logoColor=white" alt="NodeJS"> <img src="https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&amp;logo=nodemon&amp;logoColor=%BBDEAD" alt="Nodemon"> <img src="https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&amp;logo=vuedotjs&amp;logoColor=%234FC08D" alt="Vue.js"> <img src="https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&amp;logo=vuetify&amp;logoColor=AEDDFF" alt="Vuetify"> <img src="https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&amp;logo=apache&amp;logoColor=white" alt="Apache"> <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&amp;logo=nginx&amp;logoColor=white" alt="Nginx"> <img src="https://img.shields.io/badge/firebase-a08021?style=for-the-badge&amp;logo=firebase&amp;logoColor=ffcd34" alt="Firebase"> <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&amp;logo=mariadb&amp;logoColor=white" alt="MariaDB"> <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&amp;logo=microsoft%20sql%20server&amp;logoColor=white" alt="MicrosoftSQLServer"> <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white" alt="Postgres"> <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" alt="MySQL"> <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&amp;logo=git&amp;logoColor=white" alt="Git"> <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="GitHub"> <img src="https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&amp;logo=jira&amp;logoColor=white" alt="Jira"> <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&amp;logo=firebase" alt="Firebase"> <img src="https://img.shields.io/badge/astro-%232C2052.svg?style=for-the-badge&amp;logo=astro&amp;logoColor=white" alt="Astro"> <img src="https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&amp;logo=gitlab&amp;logoColor=white" alt="GitLab"> <img src="https://img.shields.io/badge/gitlab%20CI-%23181717.svg?style=for-the-badge&amp;logo=gitlab&amp;logoColor=white" alt="GitLab CI"> <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions"> <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&amp;logo=php&amp;logoColor=white" alt="PHP"> <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript"></p>

---

### 👾 Most used languages & 🔝 Top Contributed Repo

<picture>
  <!-- Dark mode -->
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=kikukeii&theme=algolia&hide_border=true&langs_count=5" />
  
  <!-- Light mode -->
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=kikukeii&theme=flat&hide_border=true&langs_count=5" />
  
  <!-- Default fallback -->
  <img alt="GitHub Contributor Stats" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kikukeii&theme=flat&hide_border=true&langs_count=5" />
</picture>

<picture>
  <!-- Dark mode -->
  <source media="(prefers-color-scheme: dark)" srcset="https://github-contributor-stats.vercel.app/api?username=kikukeii&limit=5&theme=algolia&combine_all_yearly_contributions=true" />
  
  <!-- Light mode -->
  <source media="(prefers-color-scheme: light)" srcset="https://github-contributor-stats.vercel.app/api?username=kikukeii&limit=5&theme=flat&combine_all_yearly_contributions=true" />
  
  <!-- Default fallback -->
  <img alt="GitHub Contributor Stats" src="https://github-contributor-stats.vercel.app/api?username=kikukeii&limit=5&theme=flat&combine_all_yearly_contributions=true" />
</picture>

---

<h3 align="left">💳 Support:</h3>
<p>  <a href="https://ko-fi.com/kikukeii"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&amp;logo=ko-fi&amp;logoColor=white" alt="Ko-Fi"></a> </p>

---

### 🤖 Github Contribution

<picture>
  <!-- Dark mode -->
  <source media="(prefers-color-scheme: dark)" srcset="profile-3d-contrib/profile-night-green.svg" />
  
  <!-- Light mode -->
  <source media="(prefers-color-scheme: light)" srcset="profile-3d-contrib/profile-green-animate.svg" />
  
  <!-- Default fallback -->
  <img alt="GitHub Contributor Stats" src="profile-3d-contrib/profile-green-animate.svg" />
</picture>

</details>


