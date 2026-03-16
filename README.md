# neo4j-Aura-assignment-
knowledge graph ontology
This tool helps me to store data with relationship in graphical model
I learnt basic cypher code inorder to visualize the relationship 

Used cypher codes:
1. MATCH(n) RETURN n = to see overall relationship 
2. CALL db.relationshipTypes() = to see created relationship type
3. CALL db.labels() = to see created label 
4. MATCH (character), (movie_title) RETURN character, movie_title LIMIT 50 = relationship btw character & movie title with limit of "50"
5. MATCH p=()-[:`avg.vote`]->() RETURN p LIMIT 25; = to see avgrage vote that movie got.
6.CALL db.schema.visualization() - too see the schema 

learn cypher basic code :
1.Match
2.where
3.return 
4.limit
5.call
6.db.relationshipTypes()
7.db.labels()
8.CALL db.schema.visualization()
