# ReviewDL
Review about curriculum DL &amp; Computer Sciece

Review of the Resource Representation in Institutional Repository
========

There are two groups of queries that have been made in **Scopus**, on November 5, 2014. The first group called *Problems of Elements* (**PE**), and the second group called *Problems of Process* (**PP**)


First Group PE
--------

* types OR resources:
	`TITLE-ABS-KEY((resource* OR type*) AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`


Second Group PP
--------

### Ingest process:

* `TITLE-ABS-KEY(ingest* AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(ingest* AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(ingest* AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(ingest* AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* Intersection: `(TITLE-ABS-KEY(ingest* AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(ingest* AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(ingest* AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(ingest* AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*")))`

### Storage process:
