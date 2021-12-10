Hello this is Project "EZBUY" readme
this project needs node js and mongoDB to be setup on the hosting server to run properly (we recomment using mongo db 4.4)

after mongodb installing start the server as follows
create the path "c:\\data\\db"
open cmd and go to this path  c:\\programfiles\MongoDB\Server\4.4\bin
write the command mongod.exe

then open mongoDB compass and connect it to the server then create a cluster with the name "EZBUY"
 

after installing node js, extract the rar file in any folder and open cmd on the folder "NodeApp"

then run this command in the cmd 

npm install bcryptjs body-parser connect-flash cookie-parser ejs express express-session mongoose nodemon passport passport-local path --save

then after it's done installing run this command:

npm start

now the server has started and you can go to localhost:3000 on the browser