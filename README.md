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
- 💬 HTTP, Linked Data, ODBC, JDBC, ADO.NET ...
- 📫 How to reach me: [@kidehen](http://twitter.com/kidehen) (Twitter) 
```
## JSON-LD Start ##

{
  "@context": {
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "foaf": "http://xmlns.com/foaf/0.1/",
    "schema": "http://schema.org/",
    "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
    "dcterms": "http://purl.org/dc/terms/",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "owl": "http://www.w3.org/2002/07/owl#",
    "cert": "http://www.w3.org/ns/auth/cert#"
  },
  "@graph": [
    {
      "@id": "",
      "@type": "foaf:PersonalProfileDocument",
      "foaf:maker": {
        "@id": "#i"
      },
      "foaf:primaryTopic": {
        "@id": "#i"
      }
    },
    {
      "@id": "#i",
      "@type": [
        "schema:Person",
        "foaf:Person"
      ],
      "schema:mainEntityOf": [
        {
          "@id": ""
        },
        {
          "@id": "https://www.linkedin.com/in/kidehen#"
        },
        {
          "@id": "https://www.facebook.com/kidehen#"
        },
        {
          "@id": "https://www.twitter.com/kidehen#"
        }
      ],
      "schema:name": {
        "@type": "rdf:langString",
        "@value": "Kingsley Uyi Idehen"
      },
      "owl:sameAs": [
        {
          "@id": "https://www.linkedin.com/in/kidehen#this"
        },
        {
          "@id": "https://www.facebook.com/kidehen#this"
        },
        {
          "@id": "https://www.twitter.com/kidehen#this"
        }
      ]
    },
    {
      "@id": "https://raw.githubusercontent.com/kidehen/kidehen/master/README.md#this",
      "@type": [
        "foaf:Document",
        "schema:WebPage"
      ],
      "dcterms:created": {
        "@type": "xsd:dateTime",
        "@value": "2020-07-12"
      },
      "dcterms:creator": {
        "@id": "#i"
      },
      "schema:mainEntity": {
        "@id": "#i"
      },
      "rdfs:name": {
        "@type": "rdf:langString",
        "@value": "Kingsley Uyi Idehen's Profile Document"
      },
      "foaf:primaryTopic": {
        "@id": "#i"
      }
    }
  ]
}

## JSON-LD End ##

```

OR Turtle .

```
## Turtle Start ##

@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix schema: <http://schema.org/> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix dcterms: <http://purl.org/dc/terms/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix : <#> . 

<> rdf:type foaf:PersonalProfileDocument .
<> foaf:maker :i .
<> foaf:primaryTopic :i .

:i rdf:type schema:Person .
:i rdf:type foaf:Person .
:i schema:mainEntityOf <> .
:i schema:mainEntityOf <https://www.facebook.com/kidehen#> .
:i schema:mainEntityOf <https://www.linkedin.com/in/kidehen#> .
:i schema:mainEntityOf <https://www.twitter.com/kidehen#> .
:i schema:name "Kingsley Uyi Idehen" .
:i owl:sameAs <https://www.facebook.com/kidehen#this> .
:i owl:sameAs <https://www.linkedin.com/in/kidehen#this> .
:i owl:sameAs <https://www.twitter.com/kidehen#this> .
:this rdf:type schema:WebPage .
:this rdf:type foaf:Document .
:this dcterms:created "2020-07-12"^^xsd:dateTime .
:this dcterms:creator :i .
:this schema:mainEntity :i .
:this rdfs:name "Kingsley Uyi Idehen's Profile Document" .
:this foaf:primaryTopic :i .

## Turtle End ##
```
