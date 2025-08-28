# Brand

## Properties

### primaryArchetype
Jungian Archetype
- The Innocent: Seeks happiness, optimism, and simplicity. 
- The Everyman (or Regular Person): Aims to connect with others through relatability and belonging. 
- The Hero: Inspires and empowers others, embodying courage and mastery. 
- The Outlaw (or Rebel): Challenges conventions and seeks to disrupt the status quo. 
- The Explorer: Values freedom, independence, and discovery. 
- The Creator: Driven by imagination and a desire to create something lasting. 
- The Ruler: Seeks control and leadership, often associated with luxury and power. 
- The Magician: Transforms and creates extraordinary experiences, often with a sense of wonder. 
- The Lover: Focuses on passion, intimacy, and sensual experiences. 
- The Caregiver: Driven by compassion and a desire to protect and nurture others. 
- The Jester: Embodies fun, humor, and a playful spirit. 
- The Sage: Seeks knowledge, truth, and wisdom, aiming to share understanding. 

### secondaryArchetype
- The Innocent: Seeks happiness, optimism, and simplicity. 
- The Everyman (or Regular Person): Aims to connect with others through relatability and belonging. 
- The Hero: Inspires and empowers others, embodying courage and mastery. 
- The Outlaw (or Rebel): Challenges conventions and seeks to disrupt the status quo. 
- The Explorer: Values freedom, independence, and discovery. 
- The Creator: Driven by imagination and a desire to create something lasting. 
- The Ruler: Seeks control and leadership, often associated with luxury and power. 
- The Magician: Transforms and creates extraordinary experiences, often with a sense of wonder. 
- The Lover: Focuses on passion, intimacy, and sensual experiences. 
- The Caregiver: Driven by compassion and a desire to protect and nurture others. 
- The Jester: Embodies fun, humor, and a playful spirit. 
- The Sage: Seeks knowledge, truth, and wisdom, aiming to share understanding. 


### humor
Jakob Nielsen
Funny vs serious


### formality
Formal vs casual


### respectfulness
Respectful vs irreverent


### enthusiasm
Enthusiastic vs matter-of-fact


## Example

```
{
      "@type": "Brand",
      "@id": "https://www.test.com#brand",
      "name": "test",
      "url": "https://www.test.com",
      "logo": "https://www.test.com/logo.png",
      "additionalProperty": [
        {
          "@type": "PropertyValue",
          "name": "primaryArchetype",
          "value": "Caregiver"
        },
        {
          "@type": "PropertyValue",
          "name": "secondaryArchetype",
          "value": "Everyman"
        },
        {
          "@type": "PropertyValue",
          "name": "humor",
          "value": "Funny",
          "unitText": "scale 1=Funny, 5=Serious",
          "valueReference": {
            "@type": "QuantitativeValue",
            "value": 4.5,
            "minValue": 1,
            "maxValue": 5
          }
        },
        {
          "@type": "PropertyValue",
          "name": "formality",
          "value": "casual",
          "unitText": "scale 1=Formal, 5=Casual",
          "valueReference": {
            "@type": "QuantitativeValue",
            "value": 4,
            "minValue": 1,
            "maxValue": 5
          }
        },
        {
          "@type": "PropertyValue",
          "name": "respectfulness",
          "value": "respectful",
          "unitText": "scale 1=Respectful, 5=Irreverent",
          "valueReference": {
            "@type": "QuantitativeValue",
            "value": 1.5,
            "minValue": 1,
            "maxValue": 5
          }
        },
        {
          "@type": "PropertyValue",
          "name": "enthusiasm",
          "value": "Enthusiastic",
          "unitText": "scale 1=Matter-of-fact, 5=Enthusiastic",
          "valueReference": {
            "@type": "QuantitativeValue",
            "value": 4,
            "minValue": 1,
            "maxValue": 5
          }
        }
}


```

