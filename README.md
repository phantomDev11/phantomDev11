<div align="center">
    <img 
        width="100%" 
        src="https://cdn.jsdelivr.net/gh/nocturnalDev11/nocturnalDev11/header-3.gif" 
    />
</div>

<details>
    <summary>
        <h3> About me (Click to expand)</h3>
    </summary>

```PHP
@php
    $introduction = [
        "name" => "Lutreze Hue Jacinto",
        "current_year" => "4th-year",
        "course" => "Information Technology",
        "role" => "Student Developer",
        "skills" => ["HTML", "CSS", "JavaScript", "MySQL", "PHP"],
        "frameworks_i_used" => ["Tailwind", "Laravel"],
        "software_skills" => ["Photoshop", "Adobe Illustrator", "Adobe Lightroom", "Figma"],
        "future_learning_goals" => "MERN stack"
    ];

    $skills_list = array_map(fn($skill) => $skill === "CSS" ? "$skill (including Tailwind)" : $skill, $introduction['skills']);
    $frameworks_list = implode(', ', $introduction['frameworks_i_used']);
@endphp

<div>
    <p>
        Hello! My name is {{ $introduction['name'] }}. I'm a {{ $introduction['current_year'] }} 
        {{ $introduction['course'] }} student and a self-taught web developer with experience in PHP 
        frameworks, including {{ in_array('Laravel', $introduction['frameworks_i_used']) ? 'Laravel' : 'other frameworks' }}.
        I'm constantly learning and expanding my skillset, which currently includes {{ implode(', ', $skills_list) }}.
    </p>
    
    <p>
        In addition to web development, I'm passionate about design and enjoy using tools like 
        {{ implode(', ', $introduction['software_skills']) }}. I'm also eager to learn the 
        {{ $introduction['future_learning_goals'] }} and delve into it in the near future.
    </p>
</div>
```
</details>

### Languages, Frameworks, Tools and IDE's

<div align="center">
    <img src="https://skillicons.dev/icons?i=html" height="45" alt="html5 logo" title="HTML" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=css" height="45" alt="css3 logo" title="CSS"/>
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=js" height="45" alt="javascript logo" title="JavaScript"/>
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=cpp" height="45" alt="cplusplus logo" title="C++" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=py" height="45" alt="python logo" title="Python" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=dart" height="45" alt="dart logo" title="Dart" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=php" height="45" alt="php logo" title="PHP" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=laravel" height="45" alt="laravel logo" title="Laravel" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=alpinejs" height="45" alt="alpinejs logo" title="AlpineJS" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=vue" height="45" alt="vue logo" title="Vue" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=tailwind" height="45" alt="tailwindcss logo" title="Tailwind Css" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=jquery" height="45" alt="jquery logo" title="JQuery" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=vite" height="45" alt="vite logo" title="Vite" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=flutter" height="45" alt="flutter logo" title="Flutter" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=npm" height="45" alt="npm logo" title="npm" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=androidstudio" height="45" alt="androidstudio logo" title="Android Studio" />
    <img width="10" />
    <img src="https://go-skill-icons.vercel.app/api/icons?i=livewire" height="45" alt="livewire logo" title="Livewire"/>
    <img width="10" />
    <img src="https://go-skill-icons.vercel.app/api/icons?i=wsl" height="45" alt="wsl logo" title="WSL"/>
    <img width="10" />
    <img src="https://go-skill-icons.vercel.app/api/icons?i=lightroom" height="45" alt="lightroom logo" title="Lightroom"/>
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=vscode" height="45" alt="vscode logo" title="VS Code" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=visualstudio" height="45" alt="visualstudio logo" title="Visual Studio" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=git" height="45" alt="git logo" title="Git" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=bash" height="45" alt="bash logo" title="Bash" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=ubuntu" height="45" alt="ubuntu logo" title="Ubuntu" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=powershell" height="45" alt="powershell logo" title="Powershell" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=mysql" height="45" alt="mysql logo" title="MySQL" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=firebase" height="45" alt="firebase logo" title="Firebase" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=ps" height="45" alt="photoshop logo" title="Photoshop" />
    <img width="10" />
    <img src="https://skillicons.dev/icons?i=figma" height="45" alt="figma logo" title="Figma" />
    <img width="10" />
</div>

### GitHub Stats 
<div align="center">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=phantomDev11&theme=cobalt" width="100%" height="auto" />
</div>
<div align="center">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=phantomDev11&theme=cobalt" width="49%" height="auto" style="display: inline;" />
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=phantomDev11&theme=cobalt" width="49%" height="auto" style="display: inline;" />
</div>
<div align="center">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=phantomDev11&theme=cobalt" width="49%" height="auto" style="display: inline;" />
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=phantomDev11&theme=cobalt&utcOffset=+6.5" width="49%" height="auto" style="display: inline;" />
</div>

<div align="center">
    <img src="https://raw.githubusercontent.com/phantomDev11/phantomDev11/output/snake.svg" alt="Snake animation" width="100%" height="auto" />
</div>


