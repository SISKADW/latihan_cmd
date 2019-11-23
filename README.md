# latihan_cmd
///input perintah create databases, insert, update, delete, rename, add file pada table///
MEMBUAT DATABASE MENGGUNAKAN CMD
 CD..
 CD..
 DIR..
 CD XAMPP
 DIR
 CD MYSQL
 Cd bin
 Mysql –u root –p
 
 show databases;
  create database (nama database); >>>> <membuat database baru> <<<<
 use (nama databases);
 create table (nama table)(
 -> nidn int(15),
 -> nama varchar(20),
 -> alamat(30),
 -> jenjang_pendidikan varchar(10),
 -> hobby varchar(20));
 
 use (nama database);
 show tables;
 desc (nama teble);
 insert into (nama table) values('1234','fahru','mengoding');  >>>> <membuat isi table> <<<<
 select *from (nama table);
 
 delete from (nama table) where (nama_dosen<isi table>)='';  >>>> <delete> <<<<
 selesct *from (nama table);
 
 rename table (nama table lama) to (nama table baru;  >>>> <rename table> <<<<
 desc (nama table lama);
 desc (nama table baru);
