# Wolf Hunter Game

## Project Overview

Wolf Hunter Game is a browser-based endless runner game developed using Django, HTML, CSS, and JavaScript.

The player controls a wolf running along a three-lane path. Goats can be collected for points, while humans act as obstacles. The player can move between lanes, jump, and slide while trying to survive as long as possible.

The game is designed with a retro pixel-art inspired style and an endless-runner gameplay concept.

## Main Features

- Wolf player character
- Three-lane endless runner
- Left and right lane movement
- Jump and slide controls
- Goats as collectible objects
- Humans as obstacles
- Score system
- Increasing game speed
- Game start and game-over screens
- Keyboard controls
- Django-based web application

## Technologies

- Python
- Django
- HTML5
- CSS3
- JavaScript
- Gunicorn
- Nginx
- AWS EC2
- Linux
- Git
- GitHub

## AWS Deployment

The Wolf Hunter Game was deployed on an AWS EC2 instance running Amazon Linux 2023.

The deployment uses:

```text
Internet
   ↓
AWS EC2
   ↓
Nginx
   ↓
Gunicorn
   ↓
Django
   ↓
Wolf Hunter Game