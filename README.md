# Setup-SSL-CertBot

## Setup SSL dengan CertBot

Jalankan perintah berikut

    sudo apt-get install snapd
    
![Screenshot from 2022-09-08 11-09-43](https://user-images.githubusercontent.com/40049149/189168233-95c77b97-b610-4abd-aa00-b528ab1d6827.png)
    
    sudo snap install core
    sudo snap refresh core
    
![Screenshot from 2022-09-08 11-11-20](https://user-images.githubusercontent.com/40049149/189168421-e31c5a96-61c0-4944-b0b5-69ae66124fbd.png)

    sudo apt-get install certbot python3-certbot-nginx

![Screenshot from 2022-09-08 11-12-42](https://user-images.githubusercontent.com/40049149/189168460-2badc6a2-cc5e-4e25-95fd-85fcfd56a7a7.png)

    sudo certbot --nginx
    
![Screenshot from 2022-09-08 11-13-58](https://user-images.githubusercontent.com/40049149/189168487-41fa0379-754a-40ed-a723-6abd42b5ae65.png)

Ikuti instruksi yang di tampilkan sampai selesai
