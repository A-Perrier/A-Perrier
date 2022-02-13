# Hello, I'm Anthony Perrier !

Welcome on my Github.
I'm a self taught french web developer.

## Let's see a bit more about me !

### AboutMe.php
```php
<?php
namespace AnthonyPerrier;

class Introduction extends AboutMe
{
  private const TEA_REMAINING = true;

  public $available_for_hire = true;

  public function getKnowledge()
  {
    return [
      PHP::class,
      Symfony::class,
      WordPress::class,
      JavaScript::class,
      React::class,
      ReactNative::class,
      Vuejs::class,
      ApiPlatform::class,
      Sass::class,
      SQL::class,
      Figma::class,
      AdobeXD::class
    ];
  }

  public function getRecommandedProjects()
  {
    return [
      "reactsimplesurvey"  => [
                               "stack"       => "React",
                               "released_at  => "February 2022",
                               "url"         => "https://github.com/A-Perrier/reactsimplesurvey",
                               "description" => "An easy-to-use survey builder and renderer in React"
                              ],
      "goalmatcher"        => [
                               "stack"       => ["Symfony", "React"],
                               "released_at  => "August 2021",
                               "url"         => "https://github.com/A-Perrier/goalmatcher",
                               "description" => "A project management tool such as Trello or Clickup --- WIP ---"
                              ],
      "agenda"             => [
                               "stack"       => "React",
                               "released_at  => "July 2021",
                               "url"         => "https://github.com/A-Perrier/agenda",
                               "description" => "A tool created from scratch allowing to access a calendar and save events by date and time"
                              ],
      "Dungeon of Fitness" => [
                               "stack"       => "React Native",
                               "released_at  => "July 2021",
                               "url"         => "https://github.com/A-Perrier/DoF-Game-Simulator",
                               "description" => "A one shot project which is a simulator of the card game Dungeon of Fitness that I made because the Kickstarter shipping made my waiting a bit too long for my taste (:"
                              ],                      
    ];
  }

  public function getOnlineProjects()
  {
    return [
      "laura-julien.fr" => [
                              "stack"       => ["Symfony", "React"],
                              "released_at  => "January 2022",
                              "url"         => "https://laura-julien.fr",
                              "description" => "A multi-service website where you'll find a shop based on PayPal API, a care reservation system and a blog"
                           ],
      "jerome-segal.eu" => [
                              "stack"       => ["Symfony", "React"],
                              "released_at  => "October 2021",
                              "url"         => "https://jerome-segal.eu",
                              "description" => "A trilingual platform made to map all speeches, public appearances and books from a franco-austrian speaker and researcher"
                           ],
      "haikusan.fr"     => [
                              "stack"       => ["Symfony", "Vanilla JS"],
                              "released_at  => "April 2021",
                              "url"         => "https://haikusan.fr",
                              "description" => "My personal collection of haiku, a japanese style poetry based on the contemplation of the present moment"
                             ]
    ];
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
![Such Impressive Stats, Wow](https://github-readme-stats.vercel.app/api?username=A-Perrier&hide=prs&count_private=true&show_icons=true&theme=merko&custom_title=Such%20Impressive%20Stats,%20Wow)

![Me and the boys](https://github-readme-stats.vercel.app/api/top-langs/?username=A-Perrier&layout=compact&theme=merko&custom_title=Me%20and%20the%20boys)


## Finally ...
**Thanks for your visit** !  
*Feel free to contact me !*

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
