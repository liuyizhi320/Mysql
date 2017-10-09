# Mysql

the insert statements:

INSERT INTO t (c1,c2) VALUES ('One',1);<br>
INSERT INTO t (c1,c2) VALUES ('Two',2);<br>
INSERT INTO t (c1,c2) VALUES ('Three',3);<br>

will be rewritten into:

INSERT INTO t (c1,c2) VALUES ('One',1),('Two',2),('Three',3);
