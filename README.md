# Web-design-Boilerplate-source-code
<br>## Getting Started create the new Boilerplate
<hr>
<br>#1.node.js software download & install
<br>#2.git-32_bit software download & install
<br>#3.npm init <br>
    	   package name:--Enter <br>
           varsion     :--Enter <br>
           description :Bootstrap Starter Package <br>
           entery point:--Enter <br>
           test command:--Enter <br>
        git repository :--Enter <br>
             keywords  :--Enter <br>
             author    :Habib   <br>
             license   :MIT     <br>
         Is this ok?   :--Enter <br>

#4.npm install bootstrap jquery popper.js font-awesome --save <br>
#5.npm install --global gulp-cli <br>
#6.npm install gulp browser-sync gulp-sass --save-dev (this option Not-work) <br>
#7.npm install gulp@3.9.1 --save-dev <br>
#8.create the new folder <br>
  src <br>
   ->css <br>
   ->js  <br>
   ->fonts <br>
   ->scss <br>
        ->style.css<br>
   ->img  <br>
   ->gulpfile.js <br>
    Copy the source and past this file <br><br>
  #9. gulp <br>
  #10.npm start <br>
     একটি Error দেখা যাবে এবং এটিকে Solve করার জন্য যা করতে হবে| <br>
    Edit the package.json file <br>
  "scripts":{ <br>
     "test":"echo \"Error: no test specified\" && exit 1"<br>
     },<br>

"scripts":{ <br>
     "start":"gulp" <br>
  },<br>   
 than use this command again <br>
#10.npm start

<hr>
<br><br><br>#--------------------Otherwise-Download this file and command-----------------
<br>#1.node.js software download & install
<br>#2.git-32_bit software download & install
<br>#3.Delete this file (css / fons /js) and don't delete scss file
<br>#4.npm install
<br>#5.npm start
