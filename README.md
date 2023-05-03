Download Link: https://assignmentchef.com/product/solved-cs213-assignment-5-part-2-php2-part-2-statement
<br>
5/5 - (1 vote)




<ul>

 <li>Create a directory called “rollno-lab5-part2” where “rollno” is your roll number.</li>

 <li>Keep all your scripts, html pages and all relevant files in this directory</li>

 <li>Use following command to create a tar ball :tar -czvvf rollno-lab5-part2.tgz rollno-lab5-part2/(Note that you have to outside this directory to run this command).</li>

 <li>Upload this tarball “rollno-lab5-part2.tgz” on moodle.</li>

 <li>Do not change cases, and do not deviate from the naming scheme for yourscripts, directory or tar file to be uploaded.</li>

</ul>

1. PHOTO ALBUMCreate a photo album with following features

• Login Form: index.php has the form, login.php has authentication Authenticate using standard credentials:

user:eval pass:eva

• album.php: Browsing through the album using next, prev, last, first buttons

• Image upload page that allows you to add an image to the album: newupload.php has the form and upload.php does the processing:

– Check for image format as jpg in php.– Check for image size to be less than 200KB in php

1

<ul>

 <li>–  Maximum of 10 images to upload- check in php</li>

 <li>–  Images to be uploaded to images/ directory</li>

 <li>–  Errors can be displayed on upload.php itself with a back buttonto enable navigation to the previous page</li>

 <li>–  deleting imagesWe expect index.php, login.php, upload.php, newupload.php in the directory.</li>

</ul>

• Optional (not for credit): Use sessions to validate login sessions while accessing album.php, newuplod.php and upload.php. Session has to be initialized at login.