node (Test) {
      stage('Checkout'){
      'https://github.com/Kiran-29/Website-29.git'
      }
      stage('Build'){
       sh  'mvn -B -V -U -e clean package'
     }
     stage('Deploy'){
      sh 'cd /var/www/html sudo cp /home/ubuntu/jenkins/workspace/Test/* .'
}
}      
