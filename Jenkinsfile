node {
 def applicationtitle = 'learning project';
 stage ('checkout code'){
     git branch: 'master' , url: 'https://github.com/Mksiddique07/apache-project.git'
 }
 stage ('Copy HTML') {
     sh 'cp index.html /var/www/html'
 }
 stage ('Copy Images') {
     sh 'cp -r images/ /var/www/html'
 }
 satge ('Notify Email'){
     sh 'Sending Email'
 }
}
