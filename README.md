# Hello ! 🙏🏻 I'm Anthony Perrier ! 👋

Welcome on my Github.
I'm a self taught french web developer.

## Let's see a bit more about me !

### AboutMe.php
```php
<?php
namespace AnthonyPerrier;

class AboutMe extends Introduction
{
  private const TEA_REMAINING = true;

  public $available_for_hire = true;

  public function getKnowledge()
  {
    return [
      PHP::class,
      Symfony::class,
      JavaScript::class,
      JQuery::class,
      React::class,
      ApiPlatform::class,
      Sass::class,
      SQL::class,
      Figma::class
    ];
  }

  public function getPublicProjects()
  {
    return [
      "E-Shop" => "https://github.com/A-Perrier/ningen_shoppu",
      "Project Management" => "https://github.com/A-Perrier/goalmatcher",
      "Agenda" => "https://github.com/A-Perrier/agenda"
    ];
  }

  public function getOnlineProjects()
  {
    return [
      "https://www.aurapapillon.fr"
    ];
  }

  public function getCurrentProject()
  {
    return "I'm working on Goalmatcher, a project management platform. Check the repository !";
  }

  public static function paramountGoal()
  {
    return "I want to create a website based on the 'Book where you\'re the hero' concept, as author and developer";
  }

  public function getHobbies()
  {
    return [
      HardSkillsLearning::class,
      Hiking::class,
      Yoga::class,
      SelfDevelopment::class,
      VeganCooking::class,
      Writing::class,
      Reading::class
    ];
  }

  public function contactMe()
  {
    return "perrier_anthony@live.fr";
  }
}


```


## Some stats (everybody like stats) ...
![Such Impressive Stats, Wow](https://github-readme-stats.vercel.app/api?username=A-Perrier&hide=prs,stars&count_private=true&show_icons=true&theme=merko&custom_title=Such%20Impressive%20Stats,%20Wow)

![Me and the boys](https://github-readme-stats.vercel.app/api/top-langs/?username=A-Perrier&layout=compact&theme=merko&custom_title=Me%20and%20the%20boys)


## Finally ...
**Thanks for your visit** !  
*Feel free to contact me* 😁

<!--
**A-Perrier/A-Perrier** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
