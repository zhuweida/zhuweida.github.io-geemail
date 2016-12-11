g++ -o check_login check_login.cpp -lsqlite3 -lgcrypt    
./check_login [username] [passwd]


g++ -o register register.cpp -lsqlite3 -lgcrypt
./register [username] [passwd]

g++ -I/usr/local/include/cryptopp -o write_message write_message.cpp -lgcrypt -lsqlite3 -lcryptopp
./write_message [sender] [receiver] ['message'] ['passphrase']

g++ -I/usr/local/include/cryptopp -o read_message read_message.cpp -lgcrypt -lsqlite3 -lcryptopp
./read_message [message_id] ['passphrase']

And the php file can not be compiled locally but if you want to see the whole website you can enter https://geemail-cloned-parkhe.c9users.io/login.php .Unfortunately this website can not run all the time but if you really want to see it you can email me:zhuweida@udel.edu and I can open the server.
