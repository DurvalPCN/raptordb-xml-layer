<html>
<body>
<h1>An Abstract Layer for NoSQL and XML databases</h1>

The main goal of this project is to develop an abstract layer that can connect with different databases (being NoSQL [1] or XML [2]), able to interact in real time with its data, inserting, consulting or editing.  The current version only implemented the utilization of RaptorDB and Sedna, but other databases are being inserted in the project.

This project was made to be graded at the course of <a href="https://sites.google.com/a/ic.ufal.br/comp309/" target="_blank">Special Topics in Database: Management of Semistructured Data</a>, lectured by <a href="http://buscatextual.cnpq.br/buscatextual/visualizacv.do?metodo=apresentar&id=K4764054Y6" target="_blank">Professor Fabio Coutinho</a> and available at <a href='http://www.ufal.edu.br/unidadeacademica/ic/graduacao/ciencia-da-computacao' target='_blank'>Computer Science</a> and <a href='http://www.ufal.edu.br/unidadeacademica/ic/graduacao/engenharia-de-computacao' target='_blank'>Computer Engineering</a> degrees of the <a href="http://www.ic.ufal.br" target="_blank">Institute of Computing</a> at <a href="http://www.ufal.edu.br" target="_blank">UFAL - Federal University of Alagoas</a>.

In the source files, you can find:

<ul>
	<li><i>presentation.pdf</i>, a slide presentation presented at the course;</li>
	<li>source files for the project.</li>
</ul>

We recommend you to use the Visual Studio to avoid compiling/execution errors, since the development of the project was made at this IDE.

Feel free to perform a pull request and help us growing this project.

<h2>Used Databases</h2>

<h3>NoSQL databases</h3>

<h4>RaptorDB</h4>

RaptorDB is a NoSQL, JSON [3] based, Document store database with compiled .net map functions and automatic hybrid bitmap indexing and LINQ query [4] filters.

To know more about <b>RaptorDB</b>, visit the official website <a href="https://raptordb.codeplex.com" target="_blank">here</a>.

<h3>XML Databases</h3>

<h4>Sedna</h4>

Sedna is a free native XML database which provides a full range of core database services - persistent storage, ACID transactions, security, indices, hot backup. Flexible XML processing facilities include W3C [5] XQuery implementation, tight integration of XQuery with full-text search facilities and a node-level update language.

To know more about <b>Sedna</b>, visit the official website: <a href="http://www.sedna.org/" target="_blank">Sedna.org</a>
<!--
<h4>BaseX</h4>

BaseX is a light-weight, high-performance and scalable XML Database engine and XPath/XQuery 3.1 Processor, which includes full support for the W3C Update and Full Text extensions. An interactive and user-friendly GUI frontend gives you great insight into your XML documents.

To know more about <b>BaseX</b>, visit the official website: <a href="http://basex.org/" target="_blank">basex.org</a>

<h4>eXist</h4>

To do.

To know more about <b>eXist</b>, visit the official website: <a href="http://exist-db.org/" target="_blank">exist-db.org</a>
-->
<!--
<h2>Preparing your environment</h2>

To do.

<h3>Microsoft Visual Studio</h3>

To do.

<h3>Databases</h3>

To do.

<h2>Queries in the Abstract Layer</h2>

For < consulta >,:

SELECT * FROM doc("futebol")/Estadios WHERE Cidade = '@cidade'

"{
	'estadio': {
		'nome': query<sedna>/@Nome,	
		'propriedade': query<sedna>/@Propriedade,
		'capacidade': query<sedna>/@Capacidade,
		'longitude': query<sedna>/@Longitude,
		'lagitude': query<sedna>/@Lagitude,
		'cidade': {
			'name': query<sedna>/@Cidade,
			<EXTRACAO JSON>
		}
	}
}"
-->
<h2>References</h2>

[1] NoSQL, available at < http://nosql-database.org/ > <br>
[2] XML, available at < https://www.w3.org/XML/ > <br>
[3] JSON, available at < http://www.json.org/ > <br>
[4] LINQ Query, available at < https://en.wikipedia.org/wiki/Language_Integrated_Query > <br>
[5] W3C - World Wide Web Consortium, available at < https://www.w3.org/ > <br>	

<h2>Credits</h2>

<a href="http://www.durvalpereira.com.br" target="_blank">Durval Pereira</a>. Contact me <a href="mailto:contato@durvalpereira.com.br">here</a>.<br>
<a href="http://bit.ly/durvallattes" target="_blank">Lattes</a> <a href="http://www.linkedin.com/in/DurvalPereira" target="_blank">LinkedIn</a> <a href="http://twitter.com/durvalpcn" target="_blank">Twitter</a> <a href="http://www.facebook.com/durvalpereiracn" target="_blank">Facebook</a> <a href="http://plus.google.com/+DurvalPereiraCesar" target="_blank">Google+</a><br><br>

Adeilson Lima<br>
<a href="#" target="_blank">GitHub</a><br><br>

Mário André<br>
<a href="#" target="_blank">GitHub</a><br><br>

Luciano Costa<br>
<a href="#" target="_blank">GitHub</a><br><br>

</body>
<html>