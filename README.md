This repository contains the source code of the enhanced version of DES (semantic analysis), developed as part of Javier Amado Lázaro's Bachelor Thesis.

DES is a deductive database system that incorporates SQL in particular as a query language.
One of its distinguishing features is the ability to perform semantic analysis on SQL queries
in order to detect statements that, although syntactically correct, have possible errors from a
semantic point of view.
This work extends the functions of the DES system to improve the detection of semantic
errors in SQL queries. To this end, we have worked with the Prolog programming language,
incorporating new algorithms in the query analysis module that allow us to detect cases of
semantic errors that have not been considered until now.
The main motivation for this project arises from the need to improve the learning experience
of students who use the DES tool in subjects related to databases. In this context, having tools
that not only warn of syntactic errors, but also of semantic problems which are more difficult
to detect and correct, can make a relevant contribution to students’ academic training.
As a starting point, a detailed study of both the inner workings of the semantic analysis
performed by the DES tool and the nature of the most common semantic errors was carried
out. The selection of the errors to be implemented was based on previous studies and statistical
data that analyse the difficulties that students have when writing SQL queries, and support
the need to improve this functionality in order to favour autonomous learning and the correct
understanding of the SQL language.
As a result, the DES system has been improved by incorporating new algorithms capable of
identifying subtle semantic errors in SQL clauses such as GROUP BY, ORDER BY, DISTINCT, UNION
or JOIN. It is important to note that all these algorithms have been developed in the context of
queries using the SELECT clause.
