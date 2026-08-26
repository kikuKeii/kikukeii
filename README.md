<div align="center">

![Visitor Stats](https://stat-github-beta.vercel.app/api/stats?code=kikukeii)

<img src="https://readme-typing-svg.herokuapp.com?font=Space+Mono&weight=700&pause=1000&color=569CED&center=true&random=false&width=600&lines=Hi+there%2C+I'm+Miftakhuddin+Falaki+%F0%9F%91%8B;Backend+Developer;Full-stack+Developer;Web+Developer" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/miftakhuddin-falaki)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/kikukeii)

</div>

---

## 💫 About Me

Love **You**

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
  "message": "You found me! Here's what I know."
}
```

---

## 💻 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
  <img src="https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/CodeIgniter-44B78B?style=for-the-badge&logo=codeigniter&logoColor=white" alt="CodeIgniter">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Bootstrap-8511FA?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
  <img src="https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="NPM">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" alt="JWT">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery">
</p>

---

## ✍️ My Blog

<span>
    <a target="_blank" href="https://blog.kiki.my.id/card-latest.html?post=1"><img src="https://blog.kiki.my.id/card-post1.svg" width="49%"></a>
    <a target="_blank" href="https://blog.kiki.my.id/card-latest.html?post=2"><img src="https://blog.kiki.my.id/card-post2.svg" width="49%"></a>
    <a target="_blank" href="https://blog.kiki.my.id/card-latest.html?post=3"><img src="https://blog.kiki.my.id/card-post3.svg" width="49%"></a>
    <a target="_blank" href="https://blog.kiki.my.id/card-latest.html?post=4"><img src="https://blog.kiki.my.id/card-post4.svg" width="49%"></a>
</span>

---

## 📊 GitHub Stats

<p align="center">
 <img
  src="https://github-stats-extended.vercel.app/api?username=kikukeii&rank_icon=github&show=reviews%2Cdiscussions_started%2Cdiscussions_answered%2Cprs_merged%2Cprs_merged_percentage%2Cprs_commented%2Cprs_reviewed%2Cissues_commented&show_icons=true&include_all_commits=true"
  alt="GitHub Stats"
>
</p>

<p align="center">
<img
  src="https://github-stats-extended.vercel.app/api/top-langs?username=kikukeii&layout=compact&langs_count=6"
  alt="Top Languages"
>
</p>

---

## 🤖 GitHub Contribution Graph

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="profile-3d-contrib/profile-night-green.svg" />
    <source media="(prefers-color-scheme: light)" srcset="profile-3d-contrib/profile-green-animate.svg" />
    <img alt="GitHub Contribution Graph" src="profile-3d-contrib/profile-green-animate.svg" />
  </picture>
</p>
