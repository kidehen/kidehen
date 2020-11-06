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
- ⚡ #SHA1 Fingerprint:C80773380FA5E0D510667D8A4C3BFCC47C2434F4
- ⚡ #SHA1 Fingerprint:🚬🐜🇮💨💈👉⛺🌻🛁✔💄🎹💾🐶✖😪🍋🐱😢🎻
- ⚡ #SHA1 Fingerprint:💉🍌⚓™✖🚎🔮🌴💰🔬🗿☂👪🔥💰🔪🐷🍭🐰🚀

![Profile views](https://gpvc.arturio.dev/kidehen)

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
Delegate Credentials for WebID-TLS+Delegation Authentication Protocol

```
## JSON-LD Start ##

{
  "@context": {
    "acl": "http://www.w3.org/ns/auth/acl#",
    "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
    "cert": "http://www.w3.org/ns/auth/cert#",
    "xsd": "http://www.w3.org/2001/XMLSchema#"
  },
  "@graph": [
    {
      "@id": "_:b2_b1",
      "@type": "cert:RSAPublicKey",
      "cert:exponent": {
        "@type": "xsd:int",
        "@value": "65537"
      },
      "cert:modulus": {
        "@type": "xsd:hexBinary",
        "@value": "951eb7b237add2009db7113bfa676b3f4141902191cab8b0824903b9ca90c138f46568d0248d075e496dd684487dc34a7f02c66b7d60ee4cd2c14a0043b66272257de50df06e1a4a3ccf102666fff235f5e3c65ae0e066c712773d2fad2cb89f4aad092c9dd767ecdfb3f9ef2af709bfe52590ca795d52c48992ff0162919d809890f43b2e73fae52a3347dd1a3b5e2a752a5e3c068367f9c379a26055ff60139058274a02a682c351e8685af84e4c1f5d700941d92dc3054f5f1533c1117decf0e12b4086390bbe3623aec2a7d25814ccd423cbb3c61fb2c3bbdc30efa9d557658fa243b6fa0f23848d864793cc199c95b2c83e7bb9d2449e1576ea0c6861c1"
      }
    },
    {
      "@id": "https://kidehen5.solid.openlinksw.com:8444/profile/card#me",
      "cert:key": {
        "@id": "_:b2_b1"
      }
    },
    {
      "@id": "https://github.com/kidehen#i",
      "acl:delegates": {
        "@id": "https://kidehen5.solid.openlinksw.com:8444/profile/card#me"
      }
    }
  ]
}
## JSON-LD End ##
```
Another Credentials Chunk

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
        "foaf:name": "Kingsley Uyi Idehen's Profile Document (Github Personal)"
      },
      {
        "@id": "https://github.com/kidehen#PublicKey",
        "@type": "cert:RSAPublicKey",
        "dcterms:created": {
          "@type": "xsd:dateTime",
          "@value": "2020-08-20T00:14:35.717Z"
        },
        "dcterms:title": "Created by YouID",
        "rdfs:label": "Kingsley Uyi Idehen's Profile Document (Github Personal)",
        "cert:exponent": {
          "@type": "xsd:int",
          "@value": "65537"
        },
        "cert:modulus": {
          "@type": "xsd:hexBinary",
          "@value": "840dda2d95e5b3eb6f84d9a113a8f7838810a3b03d517291ddafc82a1fa7fbf92bab96ce1065354060d23a1c03e450f802800ff52142b3931ed64d2dc6f300bf27ef87cfcba7695799bb5683f350f4b9f3e3ba1f5d8cac89f7b07eb92f3ba25e00df9f92e5fffb77e27db3a74659fda70e9b20789f8a21a0a4d2e797c353abe5f178ad850f4fa2a2d9f4a9d1763c6ce897f667e3926ea66e570d8ebac78f1c8eedd0d40f2b889b81a769992d044b5f25a52677d0ef15b31eb17de5ecc25d09a1ca694614d040098441860ca5e784e2b8907766298baf6c3edc153bf6bc95944b86833c22e87b6d09278f6c05b69696e13f7e2347c1461024061bc887df088461"
        }
      }
    ]
  }
## JSON-LD End ##
