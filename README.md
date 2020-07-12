### Hi there 👋

<!--
**kidehen/kidehen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!-- My Profile using Nanotation -->
## Turtle Start ##
## TURTLE Notation base Review Template
## A derivative (or rendition) of the JSON-LD based Google Review Guide Document
## Identified by the hyperlink: https://developers.google.com/webmasters/structured-data/critic-reviews .
## In regards to {native-language-code}" for English it would be:
## en
## For French it would be:
## fr


@prefix schema: <http://schema.org/> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .
@prefix dcterms: <http://purl.org/dc/terms/> .
@prefix terms: <http://purl.org/dc/terms/> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> . 
@prefix owl:  <http://www.w3.org/2002/07/owl#> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> . 
@prefix cert: <http://www.w3.org/ns/auth/cert#> . 
@prefix like: <http://ontologi.es/like#> .
@prefix linkedin-page: <https://www.linkedin.com/in/kidehen#> . 
@prefix facebook-page: <https://www.facebook.com/kidehen#> . 
@prefix twitter-page: <https://www.twitter.com/kidehen#> .
@prefix this-doc: <> .  
@prefix : <#> . 

## Optional Document Metadata

:this
a foaf:Document, schema:WebPage;
rdfs:name "Kingsley Uyi Idehen's Profile Document"@en ;
dcterms:created "2000-01-01"^^xsd:dateTime ;
dcterms:creator :i ;
schema:mainEntity :i ;
foaf:primaryTopic :i . 

## About You

:i
a schema:Person ;
owl:sameAs linkedin-page:this, facebook-page:this, twitter-page:this ;
schema:name "Kingsley Uyi Idehen"@en ;
# like:likes <{hyperlink-that-identifies-a-website-about-something-you-like}#likes> ;
# like:dislikes <{hyperlink-that-identifies-a-website-about-something-you-dislike}#dislikes> ;
# foaf:knows <{hyperlink-that-identifies-a-website-about-someone-you-know}#webid> .
schema:mainEntityOf this-doc:, linkedin-page:, facebook-page:, twitter-page: .

## Meshing X.509 Tokenized Credentials with those in this documents, courtesy of the YouID Generator 

  this-doc:
    a foaf:PersonalProfileDocument ;
    foaf:maker <https://kingsley.idehen.net/DAV/home/kidehen/Public/Linked%20Data%20Documents/Nanotations/kingsley-idehen-profile-doc.txt#i> ;
    foaf:primaryTopic <https://kingsley.idehen.net/DAV/home/kidehen/Public/Linked%20Data%20Documents/Nanotations/kingsley-idehen-profile-doc.txt#i> .

  :i
    a foaf:Person ;
    a schema:Person ;
    foaf:name "Kingsley Uyi Idehen (Data Island PdP)" ;
    cert:key :PublicKey.


  :PublicKey
    a cert:RSAPublicKey;
    terms:created "2020-07-02T16:26:37.461Z"^^xsd:dateTime;
    terms:title "Created by YouID";
    rdfs:label "Kingsley Uyi Idehen (Data Island PdP)";
    cert:exponent "65537"^^xsd:int;
    cert:modulus "abf0d419141a3f8545e451f6ce575d6f1592507ff912b9e972d8917eda663f142665790f06d3fc633fcbcd24b560c5a118fcf4b1bdf2af5f481b982ff05a4bc0623fd61c7a71c00477b4a533e88513457f9d17e65f2ea4e2ed4062acc0e272fc54b9a8dd48438edaa94e0701f566f62311c61c37f227e6b4ec68593d7cc79581be585152956469f357526115d88287579e0639e5528ad0a6ed2137077fcd4662d884ba30c21d78ada62152e7646ee23c65dbc86b3b2689e53df8bb583a154a6555913c95a09e91659c098d4213dd13ac3a268089a4fc20c36a01933fc63a86482ff4d15fa72452b106f4567d821b69c8083a5d2d19a0ace6460615d15a09342f"^^xsd:hexBinary.

:i cert:key :pubKey2 . 


:pubKey2
    a cert:RSAPublicKey;
    terms:created "2020-07-03T21:33:21.071Z"^^xsd:dateTime;
    terms:title "Created by YouID";
    rdfs:label "Kingsley Uyi Idehen (Text based PdP Demo Identity)";
    cert:exponent "65537"^^xsd:int;
    cert:modulus "84b9b4850703ec77a2202c19fa992926f692b2b31641e0162cb9116647e410e88a32bd7174a4cbec56302fdadceafb1c3e503055dba1951c3400a0e3ed83b7b2101f436e94869a44ff22ffc4fb12c3a9f99c234a9bece086e840794106e5fcc2d0e5c3c8a38a86f6b667906290e57e325e7e15c364d50170d49f4c5d151c96e339c34ee57e17a0d9a797536f5988de1515ecd7a2b694e027d084b287d96ca04946b89b8fcef1cac8c4c0addb621290550a5ec0449901b288a6e83ebfb91a25493af4990d5d267fd7bd34f9ba4bfd3ab93ba71d3e20e04b37ba06361f7b4e098a6a5bb26ec9482f2192f4975a4b22a7cd7a53c437223d7f0a765aeedb52cd017d"^^xsd:hexBinary.
  
## Turtle End ##
