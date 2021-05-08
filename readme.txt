# This is a Blogging Application
#This application was developed using pycharm community

its a python3-based cross-platform blogging application built using Kivy framework and KivyMD widgets.

![blogging-application-mp4](assets/blogging-application.mp4)

## Features
* Register new user
* Create new posts (public/private)
* View posts
  * Public - Accessible by everyone
  * Private - Accessible by creator only
* Attach file to the posts
* Delete posts (admin only)
* View activity log (admin only)
  * Date & Time
  * Activity Type
  * User
  * IP Address
  * Location
  * Browser

![blogging-application-1](assets/blogging-application-1.png)

![blogging-application-2](assets/blogging-application-2.png)

![blogging-application-3](assets/blogging-application-3.png)

![blogging-application-4](assets/blogging-application-4.png)

## Usage
1. Setup python virtual environment using [pyenv](https://github.com/pyenv/pyenv) (in the project directory)
   ``` 
   pyenv install 3.7.7
   pyenv virtualenv 3.7.7 blogging-application
   pyenv local blogging-application
   ```
2. Install dependencies
   ```
   pip3 install -r requirements.txt
   ```
3. Run application
   ```
   python3 main.py
   ```
   ---
   
   :file_cabinet: An SQLite database (blog.db) will be created in the root directory during the first run.

   :key: **Default credentials** { Email Address: `kivy@fot.com` Password: `Kivy@2021` }
