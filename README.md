<p align="center" width="300">
  <a align="center" href="https://kembec.com" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="/src/avatar_light.png">
      <img alt="Kembec.com" src="/src/avatar_dark.png">
    </picture>
  </a>
  
   <h1 align="center">Hi everyone, let's create something!</h1>
</p>

![GitHub Followers](https://img.shields.io/github/followers/KembecDev?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/kembec?style=social)

I'm passionate about technology ever since I clicked my first mouse. I've studied Marketing and Graphic Design, and I've been Programming since 2009 when I wrote my first "Hello World" in PHP.
## About me

```php
<?php

class AboutMe
{
  private $data = [
    "birth" => [
      "day"   => 4,
      "month" => 4,
      "year"  => 1996,
    ],
    "country"       => "Perú",
    "first_name"    => "Manuel",
    "last_name"     => "Benancio",
  ];

  public function getData()
  {
    $birth = $this->data["birth"];

    return [
      "age"               => date("Y") - $birth["year"] - (date("m") < $birth["month"] || (date("m") == $birth["month"] && date("d") < $birth["day"]) ? 1 : 0),
      "full_name"         => $this->data["first_name"] . " " . $this->data["last_name"],
      "country"           => $this->data["country"],
      "username"          => "Kembec",
      "website"           => "https://kembec.com",
      "langs"             => [
        [
          "name"      => "spanish",
          "native"    => TRUE,
          "status"    => "Ok"
        ],
        [
          "name"      => "english",
          "native"    => FALSE,
          "status"    => "In progress"
        ],
      ],
      "development"       => [
        "ide"           => "Visual Studio Code",
        "docker"        => TRUE,
        "favorites"     => [
          "lang"              => "Typescript", // Yes, my favorite language is Typescript but this code is in PHP.
          "db"                => "MariaDB",
          "ui_design"         => "Figma",
          "icons"             => "FontAwesome",
          "js_runtime"        => "Node",
          "package_manager"   => "Npm", //By habit, really, Yarn is better.
          "frameworks"    => [
            "js"    => "Vue.js",
            "php"   => "Laravel",
            "css"   => "Tailwind",
            "SSR"   => "Next.js",
          ]
        ]
      ],
      "other_knowledge"       => ["marketing", "graphic design"],
      "other_passions"        => ["music", "photography"],
      "available_for_travel"  => TRUE,
    ];
  }
}


```


## Follow me on

[![Twitter](https://img.shields.io/badge/Twitter-@Kembec-FFF?style=for-the-badge&logo=twitter&logoColor=white&labelColor=1DA1F2)](https://twitter.com/kembec)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manuel_Benancio-FFF?style=for-the-badge&logo=LinkedIn&logoColor=white&labelColor=0A66C2)](https://www.linkedin.com/in/kembec/)
[![Devto](https://img.shields.io/badge/Dev.to-Kembec-FFF?style=for-the-badge&logo=Dev.to&logoColor=white&labelColor=0A0A0A)](https://dev.to/kembec)
[![Medium](https://img.shields.io/badge/Medium-Kembec-FFF?style=for-the-badge&logo=Medium&logoColor=white&labelColor=121212)](https://kembec.medium.com/)
[![Polywork](https://img.shields.io/badge/Polywork-Kembec-FFF?style=for-the-badge&logo=Polywork&logoColor=white&labelColor=543DE9)](https://updates.kembec.com/)
[![Behance](https://img.shields.io/badge/Behance-Kembec-FFF?style=for-the-badge&logo=Behance&logoColor=white&labelColor=1769FF)](https://www.behance.net/Kembec/)
[![Figma](https://img.shields.io/badge/Figma-Kembec-FFF?style=for-the-badge&logo=Figma&logoColor=white&labelColor=F24E1E)](https://www.figma.com/@Kembec/)
