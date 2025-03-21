<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Elxss/CloudFlare-Email-Obfuscation-Fucker">
    <img src="https://raw.githubusercontent.com/Elxss/Elxss.github.io/main/src/img/logo.png" alt="Logo" width="300" height="300">
  </a>

  <a href="https://github.com/Elxss/CloudFlare-Email-Obfuscation-Fucker">
    <h3 align="center">CloudFlare-Email-Obfuscation-Fucker</h3>
  </a>

  <p align="center">
    <br />
    <a href="https://github.com/Elxss/CloudFlare-Email-Obfuscation-Fucker/issues">Report Bug</a>
    ·
    <a href="https://github.com/Elxss/CloudFlare-Email-Obfuscation-Fucker/issues">Request Feature</a>
  </p>
</div>

<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#About The Project">About The Project</a></li>
    </li>
    <li><a href="#Installation">Installation</a></li>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

### About The Project
If you are intersted in this project you may be Scrapping data and you came across
a CloudFlare Protection that obfuscates data like this:

```html
<span class="__cf_email__" data-cfemail="e4aa81928196bbb7908b94bbd6bba88185968abbb48881859781bb8881859281bb85bb97908596bb8b8abb908c81bb9681948b">[email protected]</span>
```

This module will help you remove this Protection
this will output when processed by the module

```
Never_Stop_2_Learn
```

**Please, If you like the project don't forget to leave a Star ⭐ ! it motivates me to keep going and possibly to share more things i wrote**

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Prerequisites

To use this script, you will need [Python](https://www.python.org/)

### Installation

_The installation is fast (less than 1 mins)_

1. Install the Package using the command :
```
pip install CloudFlare-EOF
```

2. Then, you can import and use the module as is
    ```python
    import CloudFlare-EOF

    html = '''<span class="__cf_email__" data-cfemail="e4aa81928196bbb7908b94bbd6bba88185968abbb48881859781bb8881859281bb85bb97908596bb8b8abb908c81bb9681948b">[email protected]</span>'''
    print(CloudFlare-EOF.decode_cf_email(html)) # Returns "Never_Stop_2_Learn"
    ```

3. Alles gut ! Leave a star ⭐ if you like this project!



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Elxss - discord: eliasss8886_ - elxssgitcontact@gmail.com - website: [elxss.github.io](https://elxss.github.io/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="center">This is a Readme.md <a href="https://github.com/othneildrew/Best-README-Template/blob/master/README.md">Template</a></p>
