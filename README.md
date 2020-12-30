RESPONSI CLOUD


pertama kita git clone pada terminal :

                    git clone https://github.com/Arum18/responsi.git
                    
selanjutnya pull image dari dockerhub ke terminal anda :

                     docker pull bintimukaromah/responsi
                     
kemudian masuk kedalam direktori file yang diambil dari github :

                     cd responsi
setelah masuk kedalam direktori responsi kemudian jalankan perintah berikut ini:

                     docker-compose up -d
setelah selesai buka web browser lalu masuk ke localhost :

                     localhost --> masuk ke menu web
                     
                     localhost:8080 --> masuk database
untuk membuat web kita bisa melakukan CRUD dengan melakukan setting pada database, Log in ke database :

                    Username : root
                    password : example
                    Database : (kosongkan)
                    
lalu create database dengan nama : data                    

selanjutnya buat tabel dengan nama : tb_blog

lalu buat kolom :

            id  | int | length (kosongkan) |  options (koosngkan) | NULL (kosongkan)  | AI (conteng, ini primary key) 
            
            nama  | varchar | lenght (20) | options (default) 
            
            nim | int | length (9)  
            
            alamat  | varchar | lenght (30) | options (default) 
            
            lalu save.
            
kemudian buka lagi localhost. sekarang kita bisa melakukan proses CRUD pada web ini.

