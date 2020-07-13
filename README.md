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
- 📫 How to reach me: [@kidehen.twitter](http://twitter.com/kidehen#this) (Twitter), [@kidehen.linkedin](https://linkedin.com/in/kidehen#this) (LinkedIn), [@kidehen.email](mailto:kidehen@openlinksw.com) (Email)

- 💬 Ask me about ... [Knowledge Graph](https://twitter.com/hashtag/KnowledgeGraph), [Linked Data](https://twitter.com/hashtag/LinkedData), [ODBC](https://twitter.com/hashtag/ODBC), [JDBC](https://twitter.com/hashtag/JDBC), [Data Connectivity](https://twitter.com/hashtag/DataConnectivity), [WebID](https://twitter.com/hashtag/WebID), [Privacy-By-Design](https://twitter.com/hashtag/PrivacyByDesign), [Solid](https://twitter.com/hashtag/SolidHelps), [Read-Write Web](https://twitter.com/hashtag/RWW)

- 🔭 I’m currently working on the free flow of data across personal and enterprise data spaces, without comprising platform independence, performance, or privacy. 

Here is an example of a personal profile document, using [JSON-LD Notaton](https://medium.com/@kidehen/simple-linked-data-deployment-tutorial-using-json-ld-notation-3e753a5d44a3) that's crucial to that effort. For maximum effect, you are encouraged to install the [OpenLink Structured Data Sniffer Browser Extension](https://chrome.google.com/webstore/detail/openlink-structured-data/egdaiaihbdoiibopledjahjaihbmjhdj?hl=en) (for Chrome and other Web Extensions compliant Browsers) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/openlink-structured-data-sniff/). 

```
## JSON-LD Start ##

{
  "@context": {
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "foaf": "http://xmlns.com/foaf/0.1/",
    "schema": "http://schema.org/",
    "xsd": "http://www.w3.org/2001/XMLSchema#",
    "owl": "http://www.w3.org/2002/07/owl#"
  },
  "@graph": [
    {
      "@id": "",
      "@type": [
        "foaf:Document",
        "foaf:PersonalProfileDocument",
        "schema:WebPage",
        "schema:CreativeWork"
      ],
      "schema:creator": {
        "@id": "#i"
      },
      "schema:dateCreated": {
        "@type": "xsd:dateTime",
        "@value": "2020-07-12"
      },
      "schema:mainEntity": {
        "@id": "#i"
      },
      "schema:name": "Kingsley Uyi Idehen's Profile Document",
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
          "@id": "https://www.facebook.com/kidehen/"
        },
        {
          "@id": "https://www.linkedin.com/in/kidehen/"
        },
        {
          "@id": "https://www.twitter.com/kidehen/"
        }
      ],
      "schema:name": "Kingsley Uyi Idehen",
      "owl:sameAs": [
        {
          "@id": "https://www.facebook.com/kidehen#this"
        },
        {
          "@id": "https://www.linkedin.com/in/kidehen#this"
        },
        {
          "@id": "https://www.twitter.com/kidehen#this"
        }
      ]
    }
  ]
}

## JSON-LD End ##

```

Here is the same Profile Information using [RDF-Turtle](https://medium.com/openlink-software-blog/simple-linked-data-deployment-tutorial-a532e568c82f) Notation. 

```
## Turtle Start ##

@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix schema: <http://schema.org/> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix dcterms: <http://purl.org/dc/terms/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix cert: <http://www.w3.org/ns/auth/cert#> . 
@prefix : <#> . 

# Profile Document Metadata
<> rdf:type foaf:Document, foaf:PersonalProfileDocument, schema:WebPage, schema:CreativeWork .
<> foaf:maker :i .
<> foaf:primaryTopic :i .
<> schema:mainEntity :i .
<> schema:dateCreated "2020-07-12"^^xsd:dateTime .
<> schema:creator :i .
<> schema:name "Kingsley Uyi Idehen's Profile Document" .

# Personal Information 
:i schema:mainEntityOf <> .
:i schema:mainEntityOf <https://www.facebook.com/kidehen/> .
:i schema:mainEntityOf <https://www.linkedin.com/in/kidehen/> .
:i schema:mainEntityOf <https://www.twitter.com/kidehen/> .
:i rdf:type schema:Person, foaf:Person .
:i schema:name "Kingsley Uyi Idehen" .
:i owl:sameAs <https://www.facebook.com/kidehen#this> .
:i owl:sameAs <https://www.linkedin.com/in/kidehen#this> .
:i owl:sameAs <https://www.twitter.com/kidehen#this> .

# Crypto Information for Encoding Information that can only be read by me 

## Turtle End ##
```
