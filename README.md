# Setup-SSL-CertBot

## Setup SSL dengan CertBot


![image](https://user-images.githubusercontent.com/40049149/190854835-64990e08-1c7c-4548-ae86-478cd99f39a7.png)

    mkdir .secret
    cd .secret/
    nano nginx.ini

![image](https://user-images.githubusercontent.com/40049149/190855050-c7ecf17d-ffaf-4b10-97a8-4c8409d0fbd2.png)

    dns_cloudflare_email = "000000@gmail.com"
    dns_cloudflare_api_key = "f4de4535b07667353452b964"

![Screenshot from 2022-09-17 18-46-54](https://user-images.githubusercontent.com/40049149/190855108-0caf3670-fab8-40e7-a931-e168e0925639.png)
    
    chmod 400 nginx.ini
    
![image](https://user-images.githubusercontent.com/40049149/190855221-715924f7-e5e4-4506-9c22-2ffba5b7779c.png)

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
