# Mysql

the insert statements:

INSERT INTO t (c1,c2) VALUES ('One',1);<br>
INSERT INTO t (c1,c2) VALUES ('Two',2);<br>
INSERT INTO t (c1,c2) VALUES ('Three',3);<br>

will be rewritten into:

INSERT INTO t (c1,c2) VALUES ('One',1),('Two',2),('Three',3);



# 截取问号前字符

(CASE WHEN visit.referer_name LIKE '%?%' THEN LEFT(visit.referer_name,(INSTR(visit.referer_name, '?') - 1)) ELSE visit.referer_name END) as pk_campaign,




* substring_index(str,delim,count)<br>
      str:要处理的字符串<br>
      delim:分隔符<br>
      count:计数<br>
