<h1>Readme in process<h1>
    <img style="width:400px; height:250px; margin:12px" src="https://user-images.githubusercontent.com/116546588/213402788-585bfa53-121f-42ac-8058-15d968106c40.gif" alt="Preliminary project demo"/>
    
<h1>Project: "Nevermore Academy"</h1>

<h2>1. Project description:</h2>
<ul>
<li>The client has asked us to design and develop a scholar aplication for students and Teachers.</li>
<li>First, both of them must to log in to identify themselves as user or admin.</li>
<li>In this app, students (users) should be able to visualize their grades while the teacher (admin) can see the students list with the quarterly grades, and add students if needed; they can also see the student profile where edit the student data or add (and edit) their respective exam grades.</li>

</ul>

<h2>2. User stories:</h2>

<h3>2.2 User Story (User):</h3>
<ul>
<li>Being able to register in the app as user.</li>
<li>See the subjects and their respective exam grades.</li>
<li>See the average grade (trimestral and final).</li>
</ul>

<h3>2.3 User Story (Administrator):</h3>
<ul>
<li>Enter app as admin.</li>
<li>View student list with trimestral average.</li>
<li>Add new student.</li>
<li>See student profile.</li>
<li>Edit student data.</li>
<li>Edit student exam grades.</li>
<li>Add student grades.</li>
<li>Close trimester and year.</li>
</ul>

<h2>3. Fullstack Developer Team</h2>

<ul>
<li>Veronika Komarova https://github.com/VeronikaKoma</li> 
<li>Noa Trujillo https://github.com/mintybubblegum</li>
<li>Alesia Baldeon https://github.com/AlesiaCoder</li>
<li>Natalia Palomo https://github.com/Nataliaplm</li> 
<li>Sandra León https://github.com/sandraldr27</li>   
</ul>


<h2>4. Project Demo (Preview)</h2>
<div style="display:flex; flex-wrap:wrap; justify-content:center; margin:auto">
<img style="width:400px; height:250px; margin:12px" src="" alt="Preliminary project demo"/>
</div>


<h2>5. Initial Sketch</h2>
<div style="display:flex; flex-wrap:wrap; justify-content:center; margin:auto">
<img style="width:600px; height:400px; margin:12px" src="https://user-images.githubusercontent.com/116545731/216052528-26ba1e22-fbeb-4e5d-ba67-d899dfff8117.png" alt="initialSketch"/>
</div>

<h2>6. Atomic Design</h2> 
<div style="display:flex; flex-wrap:wrap; justify-content:center; margin:auto">
<img style="width:250px; height:400px; margin:12px" src="" alt="Atomic Design"/>
</div>

<h2>7. Final Design</h2> 
<div style="display:flex; flex-wrap:wrap; justify-content:center; margin:auto">
<img style="width:600px; height:500px; margin:12px" src="" alt="PFinal Design "/>
</div>

<h2>8. Stacks</h2>
<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>PHP</li>
<li>Laravel</li>
<li>Boostrap</li>
<li>NPM</li>
</ul>

<h2>9. Required:</h2>
<li>Composer & Laravel Installed.</li>
<li>XAMPP/LAMPP Installed.</li>
<li>NPM Installed.</li>
<li>MySQL.</li>
<li>PHP Artisan Serve.</li>
<li>PHP (Minimum, version 7.4).</li>

<h3>To install Project</h3>
<li>Open the IDE</li>
<li>In the link .. the CODE tab.</li>
<li>Within the CODE tab copy the link that appears in HTTPS.</li>
<li>In the IDE run <b>git clone</b> command, an paste the HTTPS.</li>
<li>Write in the IDE terminal the command: <b>composer install </b>or <b>composer update</b> (If you have previously installed composer), and press intro.</li>
<li>Write in the IDE terminal the command: <b>composer create-project --prefer-dist</b> and press intro.</li>
<li>An <b>.env</b> file (in the form of a little wheel) will be downloaded. Go into it and rename the line <b>DB_DATABASE</b>. Change the name generated by default and write <b>nevermoreacademy.</b></li>
<li>Open XAMPP or LAMPP.</li>
<li>Login to <b>phpMyAdmin</b> and create a new table named <b>nevermoreacademy.</b></li>
<li>Type in the IDE terminal: <b>php artisan migrate:fresh --seed</b> and press intro.</li>
<li>Type in the IDE terminal: <b>composer require laravel/ui</b> and press intro.</li>
<li>Type in the IDE terminal: <b>php artisan ui bootstrap --auth</b> and press intro.</li>
<li>Type in the IDE terminal: <b>npm install</b> and press intro.</li>
<li>Type in the IDE terminal: <b>npm run dev</b> and press intro. Then open another terminal in the IDE without closing the previous one</li>
<li>Type in the IDE terminal: <b>php artisan migrate</b> and press intro</li>
<li>Type in the IDE terminal: <b>php artisan serve</b> and press intro.</li>

<h3>Warning & Testing</h3>
<ol>
<li><b>Important</b>: If we then need to run more commands in the IDE, we'll open a third terminal without closing the previous two.</li>
<li><b>Test</b>: Run in the IDE <b>php artisan test</b> & <b>vendor/bin/phpunit</b> where it should return the following result:<b> 5 passed</b> and <b> OK (5 test, 14 assertions)</b></li>
</ol>

<div style="display:flex; flex-wrap:wrap; justify-content:center; margin:auto">
<img style="width:600px; height:500px; margin:12px" src="" alt="finalTest"/>
</div>

<h2>10. Methodology:</h2>
<ul>
<li>Mob programming.</li>
<li>Pair programming.</li>
<li>Agile with SCRUM</li>
</ul>


<h2>11. Next Steps</h2>
<ul>
<li>Continue to implement the CRUD.</li>
<li>Continue implementing the design.</li>
<li>Continue implementing functionalities.</li>
</ul>

