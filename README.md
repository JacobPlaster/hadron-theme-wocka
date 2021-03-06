[Hadron](https://github.com/hadronjs/hadron)-theme-wocka
==================

### Quick Install
Create app, 'hadorn-wocka' is an example:
```bash
$ mkdir hadron-wocka && cd hadron-wocka
$ git init
```
Grab hadron:
```bash
$ git remote add hadron-seed -m master https://github.com/hadronjs/hadron-seed.git
$ git pull -s recursive -X theirs hadron-seed master
```
Grab plugins (Disqus, google analytics ect..):
```bash
$ npm install
```
Install theme-wocka:
```bash
$ npm install hadron-theme-wocka
```
Install dependancies and build:
```bash
$ gulp install
$ gulp build
```
Lastly, run:
```bash
$ node app.js
```
Navigate to localhost:3000 to witness the beauty. *Note:* Make sure that you navigate to tha admin panel and change the navbar image background, default is plain black.
Check out [hadron](https://github.com/hadronjs/hadron-openshift-seed) for instructions on how to release hadron in production.
<br/>
<br/>
### Take a look!
The home screen. The posts are stored in a fluid display model, this is also very responsive.
![Theme-wocka home](http://i1379.photobucket.com/albums/ah156/jacobplaster1995/14540561639_3993620148_b_zps13ab7cc0.jpg)
<br/>
#### Home screen mobile view:
![Theme-wocka home-mobile](http://i1379.photobucket.com/albums/ah156/jacobplaster1995/14724018191_dc6314be91_b_zpsf619a110.jpg)
<br/>
#### The post view:
![Theme-wocka post-view](http://i1379.photobucket.com/albums/ah156/jacobplaster1995/14726901602_519b68c4c4_b_zps7128ac03.jpg)
<br/>
#### Admin page view:
![Theme-wocka admin-page](http://i1379.photobucket.com/albums/ah156/jacobplaster1995/14726902502_b3747dfa97_b1_zpsbf11f668.jpg)
<br/>
<br/>
##### If you want to see a functioning version, visit my [website](http://www.jacobplaster.net)
Let me know if you have installed my theme on your website, I would love to see it!
