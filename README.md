# GoFifa (Built with PHP and MongoDB)

<a href="https://gofifa.herokuapp.com"><img src="https://i.ibb.co/CM8V5cM/logo.png" width="202" height="237"></a>

## Important Links 

#### Demo 
Link to Application Demo: https://gofifa.herokuapp.com

#### Presentation
Link to Presentation: https://tinyurl.com/gofifa-ppt

#### Data Crawler
Link to Crawler: https://tinyurl.com/data-crawler

#### Demo Video
<a href="https://www.youtube.com/watch?v=YGNDGTnQdNQ"><img src="https://i.ibb.co/3d9ff1J/screely-1608005305630.png" alt="video"></a>

## Functionalities 
- Customized Search (Multi-Select, Range Slider)
- Completely Responsive Data-Table
- Geo Near Querying (Using Mongo and Leaflet.js)
- Image Storage using GridFS
- Radar Chart for Player Evaluations
- Counters and Progress Bars (Player Stats)
- Position based Rating (Soccer Field View)
- Live Communication Thread 
- Leaflet Map (Location and Player Details)
- Direct Text Search 
- Completely Responsive Design

## Installation

### If you're using Ubuntu on your local machine, and you want to install the prerequisites at first and then add the source, follow the following steps:

Instruction to setup php (apache)

Install Apache
```
1. sudo apt-get update -y #using the -y option will automatically accept the conditions of the source update
2. sudo apt-get install apache2 -y #install apache
3. sudo systemctl start apache2.service #start apache
```

Install PHP
```
1. sudo apt-get install php -y
2. sudo apt-get install -y php-{bcmath,bz2,intl,gd,mbstring,mcrypt,mysql,zip} && sudo apt-get install libapache2-mod-php -y
```

Start Apache on boot
```
sudo systemctl enable apache2.service
```

Finally, restart Apache to allow PHP to run.
```
systemctl restart apache2.service
```

To know more visit: https://www.vultr.com/docs/how-to-install-apache-mysql-and-php-on-ubuntu-17-04

Placing and verifying setup for the client files
```
1. cd /var/www/html
2. mkdir gofifa
3. add the contents of the web folder in the repository to the newly created directory gofifa.
4. run php from web folder
4. visit http://localhost:<YOUR_PORT> in your browser to verify if application has been setup correctly.
```
Add the mongo data folder to your local machine's mongodb path.
Add the PHP scripts from the scripts folder in the repository. (Change path to local php scripts for connecting with mongo in gofifa php files).  

## Built With:
- PHP
- MongoDB
- Python
- HTML5
- Bootstrap 4
- JavaScript
- Jquery
- GitHub
- Leaflet
    
## License
This project is licensed under the MIT License - see the LICENSE.md file for details. 

## Developers:
- Nirbhay Pherwani - @nirbhayph - https://github.com/nirbhayph 
- Dhiren Chandnani - @dhirensc - https://github.com/dhirensc 

## Acknowledgements and Mentions:
- @leafletjs - https://leafletjs.com/
- @beautifulsoup - https://www.crummy.com/software/BeautifulSoup/bs4/doc/
- @heroku - https://heroku.com
- @mongodb - https://mongodb.com
- @ionrangeslider - http://ionden.com/a/plugins/ion.rangeSlider/
- @jquery - https://jquery.com
- @select2 - https://select2.org/
- @jqueryui - https://jqueryui.com/
- @datatable - https://datatables.net/
- @osm - https://www.openstreetmap.org/
- @jquery-knob - https://github.com/aterrien/jQuery-Knob
- @chartjs - https://www.chartjs.org/
- @php-mongo - https://docs.mongodb.com/drivers/php
- @kaggle - https://kaggle.com
- @sofifa - https://sofifa.com

## Screenshots
<p align="center">
    <b>Geo Near Querying</b>
    <img src="https://i.ibb.co/S6SNxRg/1.png" alt="1">
</p>
<p align="center">
    <b>Custom Search View</b>
    <img src="https://i.ibb.co/9wL64vr/2.png" alt="2">
</p>
<p align="center">
    <b>Responsive Data Table</b>
    <img src="https://i.ibb.co/Ct2z4W4/3.png" alt="3">
</p>
<p align="center">
    <b>Player Statistics Radar Chart</b><br/>
    <img src="https://i.ibb.co/hCvRmxy/4.png" alt="4">
</p>
<p align="center">
    <b>Positional Rating (Soccer Field View)</b>
    <img src="https://i.ibb.co/NtcWyc2/5.png" alt="5">
</p>
<p align="center">
    <b>Counters</b><br/>
    <img src="https://i.ibb.co/Tv4LnB1/6.png" alt="6">
</p>
<p align="center">
    <b>Skill Indicators</b><br/>
    <img src="https://i.ibb.co/HgbKP2C/7.png" alt="7">
</p>
<p align="center">
    <b>Player Location and Details</b>
    <img src="https://i.ibb.co/xgTf66z/8.png" alt="8">
</p>
<p align="center">
    <b>Anonymous Comments' Section</b>
    <img src="https://i.ibb.co/KFSPvc0/9.png" alt="9">
</p>
<p align="center">
    <b>About Player</b>
    <img src="https://i.ibb.co/9hBW5MQ/10.png" alt="10">
</p>



