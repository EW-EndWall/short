<br/>
<p align="center">
  <a href="https://github.com/EW-EndWall/SHORT">
    <img src="https://raw.githubusercontent.com/EW-EndWall/SHORT/e0c874cfa5c556bdbc60c985cf97b8a213a90727/assets/dist/img/logo.svg" alt="Logo" width="220" height="220">
  </a>

  <h3 align="center">SHORT</h3>

  <p align="center">
    Copy Paste Shorten
    <br/>
    <br/>
  </p>
</p>


## Table Of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [License](#license)

## About The Project

![Screen Shot](https://github.com/EW-EndWall/SHORT/assets/43109779/8a658b88-a5d2-4fea-9192-c910ef132a04)

The URL Shortening Application is a tool that turns long web addresses into short and easy-to-share ones. This way, you can share the links you want with less characters on platforms such as social media, email or messaging.

Warning: The link will be deleted after 1 hour, and it does not keep statistics because it is a test application.


## Getting Started

Easy to install, download, put files on server, upload to sql database, update db.php, ready.

### Installation

1. Clone the repo

```sh
git clone https://github.com/EW-EndWall/SHORT.git
```

2. Enter your DB in `db.php`

```php
$servername = "localhost";
$database = "short";
$username = "root";
$password = "";
```

2. Install sql

```php
phpmyadmin import short.sql
```


## License

Distributed under the Apache-2.0 License. See [LICENSE](https://github.com/EW-EndWall/SHORT/blob/main/LICENSE) for more information.
