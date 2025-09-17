<p align="center">
  <img
    src="https://github.com/Mestre-Tramador/Mestre-Tramador/blob/main/assets/data/professional/projects/Smart-Destination/logo.png"
    alt="Smart Destination logo"
    width="300"
    height="205"
  />
</p>

<p align="center">
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/laravel/laravel-original.svg"
    alt="Laravel"
    width="96"
    height="96"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg"
    alt="Vue.js"
    width="96"
    height="96"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/inertiajs/inertiajs-original.svg"
    alt="Inertia.js"
    width="96"
    height="96"
  />
</p>

<p align="center">
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg"
    alt="PHP"
    width="64"
    height="64"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/composer/composer-original.svg"
    alt="Composer"
    width="64"
    height="64"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg"
    alt="JavaScript"
    width="64"
    height="64"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg"
    alt="CSS"
    width="64"
    height="64"
  />  
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/npm/npm-original-wordmark.svg"
    alt="npm"
    width="64"
    height="64"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg"
    alt="MySQL"
    width="64"
    height="64"
  />
  &nbsp;
  <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ionic/ionic-original.svg"
    alt="Ionic"
    width="64"
    height="64"
  />  
</p>

**[Return][back]**

Smart Destination is the second project from Brazilian company Smart Tour and its most successful,
built using Laravel for backend and Vue.js (with Inertia.js) for frontend. A monolith designed to help
Brazilian city governments regarding their tourism. Later the software would also work as an expert system
with the help of Chat GPT, providing useful insight measured using data from Brazilian government organizations,
like IBGE, and data from the cities themselves collected with an integration with the QuestionPro platform.

All data was stored in a MySQL, also monolithic, instance, while other data was maintained as plain
JSON files stored in the filesystem of the project. Even so, the system didn't suffered with slow requests,
the most consuming being the ones where all the data was crossed and integrated with Chat GPT, which,
fairly, would take less than 30 seconds. There is also an mobile app made with Ionic that can be used
to provide additional data to the system, which use the GPS of the smartphone to send and retrieve
points of interest to the user.

The project is still maintained and is online, but I can't provide any useful information about the
new features or the status of the system at the current state due to me not being working on it anymore.
If you want to read more information, it can be done by this site: <https://smarttourbrasil.com.br>

<!--                              WHY THE REFERENCES IN ENGLISH?                               -->
<!-- You'll notice that the below references are in English.                                   -->
<!-- It was done this way so the exact hyperlinks among all languages can easily identifiable. -->
[back]: ../README.EN.md
