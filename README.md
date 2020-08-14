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
      "cert": "http://www.w3.org/ns/auth/cert#",
      "dcterms": "http://purl.org/dc/terms/",
      "xsd": "http://www.w3.org/2001/XMLSchema#",
      "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
      "schema": "http://schema.org/"
    },
    "@graph": [
      {
        "@id": "",
        "@type": "foaf:PersonalProfileDocument",
        "foaf:maker": {
          "@id": "https://github.com/kidehen#i"
        },
        "foaf:primaryTopic": {
          "@id": "https://github.com/kidehen#i"
        }
      },
      {
        "@id": "https://github.com/kidehen#i",
        "@type": [
          "foaf:Person",
          "schema:Person"
        ],
        "cert:key": {
          "@id": "https://github.com/kidehen#PublicKey"
        },
        "foaf:name": "Kingsley Uyi Idehen's Profile Document (Github)"
      },
      {
        "@id": "https://github.com/kidehen#PublicKey",
        "@type": "cert:RSAPublicKey",
        "dcterms:created": {
          "@type": "xsd:dateTime",
          "@value": "2020-08-14T20:17:45.138Z"
        },
        "dcterms:title": "Created by YouID",
        "rdfs:label": "Kingsley Uyi Idehen's Profile Document (Github)",
        "cert:exponent": {
          "@type": "xsd:int",
          "@value": "65537"
        },
        "cert:modulus": {
          "@type": "xsd:hexBinary",
          "@value": "d1ba238ac601db8bab06b3e49b999f7d609ae032a6ee16b335af0f0166aae67728f2ca72ed0b00e239f929637b0ec6e45e6713c392188cee3037cdde38835c1846057b2fcf927c350c147fdb26e9dadb9c2009389ac3efd80ac16efe9fb43517d42f8698870fde9678c530f3a0a3795c7d4cc2cb347800bafaa6f126dc9a0352185ade0f67d61f5cdb13a6418d2fe70a4792a0d2f259a0c0f2501a68f115d9fd2501978e5ddf59087e64f0b8e1d556ae8e761347bafc8b807af9124970e61762f9a674a748105887b59c6a8778b3bc5aa60f29ec03e152b393bc7c303040e1dca6f88a1c281bbe3d315df28c74a837c0445753e7906b57ed8c48b06812701c17"
        }
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
:i schema:mainEntityOfPage <> .
:i schema:mainEntityOfPage <https://www.facebook.com/kidehen/> .
:i schema:mainEntityOfPage <https://www.linkedin.com/in/kidehen/> .
:i schema:mainEntityOfPage <https://www.twitter.com/kidehen/> .
:i schema:mainEntityOfPage <https://community.openlinksw.com/u/kidehen/> . 
:i schema:mainEntityOfPage <https://stackoverflow.com/users/213503/kingsley-uyi-idehen/> . 
:i schema:mainEntityOfPage <https://www.quora.com/profile/Kingsley-Uyi-Idehen/> . 
:i schema:mainEntityOfPage <https://stackexchange.com/users/74272/kingsley-uyi-idehen/> . 
:i rdf:type schema:Person, foaf:Person .
:i schema:name "Kingsley Uyi Idehen" .
:i owl:sameAs <https://www.facebook.com/kidehen#this> .
:i owl:sameAs <https://www.linkedin.com/in/kidehen#this> .
:i owl:sameAs <https://www.twitter.com/kidehen#this> .
:i owl:sameAs <https://community.openlinksw.com/u/kidehen#this> . 
:i owl:sameAs <https://stackoverflow.com/users/213503/kingsley-uyi-idehen#this> . 
:i owl:sameAs <https://www.quora.com/profile/Kingsley-Uyi-Idehen#this> . 
:i owl:sameAs <https://stackexchange.com/users/74272/kingsley-uyi-idehen#this> . 

# Crypto Information for Encoding Information that can only be read by me 

## Turtle End ##
```
```
## JSON-LD Start ##

  {
    "@context": {
      "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
      "foaf": "http://xmlns.com/foaf/0.1/",
      "schema": "http://schema.org/",
      "cert": "http://www.w3.org/ns/auth/cert#",
      "dcterms": "http://purl.org/dc/terms/",
      "xsd": "http://www.w3.org/2001/XMLSchema#",
      "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
      "schema": "http://schema.org/"
    },
    "@graph": [
      {
        "@id": "",
        "@type": "foaf:PersonalProfileDocument",
        "foaf:maker": {
          "@id": "https://github.com/kidehen/kidehen#i"
        },
        "foaf:primaryTopic": {
          "@id": "https://github.com/kidehen/kidehen#i"
        }
      },
      {
        "@id": "https://github.com/kidehen/kidehen#i",
        "@type": [
          "foaf:Person",
          "schema:Person"
        ],
        "cert:key": {
          "@id": "https://github.com/kidehen/kidehen#PublicKey"
        },
        "foaf:name": "Kingsley Uyi Idehen's Profile Document (Github)"
      },
      {
        "@id": "https://github.com/kidehen/kidehen#PublicKey",
        "@type": "cert:RSAPublicKey",
        "dcterms:created": {
          "@type": "xsd:dateTime",
          "@value": "2020-08-07T19:30:10.534Z"
        },
        "dcterms:title": "Created by YouID",
        "rdfs:label": "Kingsley Uyi Idehen's Profile Document (Github)",
        "cert:exponent": {
          "@type": "xsd:int",
          "@value": "65537"
        },
        "cert:modulus": {
          "@type": "xsd:hexBinary",
          "@value": "a75b75af5eae39f046af56364c558376ccd1edd4e99ca7ec96565c1f6441acfafa60071aa4799fe67aa76e5064c866cc8d7d47b4ce64fbeb58a97fff61443d868a8e017ffd766614086c51c4ea412b276ddf61adebd7962a0d0f8c5d6ff1d565ed31005ce78ec7733013a34477185d671f5dbcc2b6e93086929b3dee10748194c33a4af8f3535776546d4647b78c4366c8814deff466258a6e1797e4c0ef4902ec35b5cf38693c255045bc4efc7c0ce6d0757d29ac4ec2382ed052eeca19fe09db2f804aa339dffd18906071e23079c36a4c2fe0a075b96d934f5119abcb31b109ebaf1de1aefde0d1bb415e80eb7e321d8caf3bff457eb6ad31c55f3a992217"
        }
      }
    ]
  }

## JSON-LD End ##
```
