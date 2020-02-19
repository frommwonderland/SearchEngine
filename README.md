# SearchEngine

# Description of the Project

Implementation of a search engine for documents and websites based on the PageRank algorithm. The idea is to find those documents that fit the search query the best.

# Background of the Project

This project was done during a semester course at TUM. There were weekly instructions and tasks to solve.


# Test the code

Create the following .txt files (or use the ones you'll find in the code/data folder):

	a.txt
	es war einmal link:b.txt link:c.txt
	
	c.txt
	once upon a time link:d.txt
	
	d.txt
	erase una vez link:c.txt
	
	e.txt
	c era una volta link:b.txt
	
You can test the code by running the TestIt.java function and type ...

	> add b.txt:link:a.txt link:e.txt
	
	> crawl
	
	> pageRank
	
	b.txt; PageRank: 0.14897680763983684
	a.txt; PageRank: 0.0933151432469308
	c.txt; PageRank: 0.34291508382082525
	d.txt; PageRank: 0.32147782204547976
	e.txt; PageRank: 0.0933151432469308
	
	> query einmal
	
	a.txt; Relevanz: 0.285917709527423
	c.txt; Relevanz: 0.1371660335283301
	d.txt; Relevanz: 0.1285911288181919
	b.txt; Relevanz: 0.05959072305593474
	e.txt; Relevanz: 0.03732605729877232
	
	> exit

