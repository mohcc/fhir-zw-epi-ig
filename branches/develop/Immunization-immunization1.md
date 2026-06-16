# Example Immunization (BCG) - Zimbabwe EPI IG v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Example Immunization (BCG)**

## Example Immunization: Example Immunization (BCG)

Profile: [Zimbabwe Immunization](StructureDefinition-zw-immunization.md)

**status**: Completed

**vaccineCode**: BCG

**patient**: `zw-patient-example`

**occurrence**: 1985-06-15

**primarySource**: true

**location**: `location1`

**lotNumber**: BCG-2026-001

### Performers

| | |
| :--- | :--- |
| - | **Actor** |
| * | `practitioner1` |



## Resource Content

```json
{
  "resourceType" : "Immunization",
  "id" : "immunization1",
  "meta" : {
    "profile" : ["http://mohcc.gov.zw/fhir/epi/StructureDefinition/zw-immunization"]
  },
  "status" : "completed",
  "vaccineCode" : {
    "coding" : [{
      "system" : "http://hl7.org/fhir/sid/cvx",
      "code" : "19"
    }],
    "text" : "BCG"
  },
  "patient" : {
    "reference" : "zw-patient-example"
  },
  "occurrenceDateTime" : "1985-06-15",
  "primarySource" : true,
  "location" : {
    "reference" : "location1"
  },
  "lotNumber" : "BCG-2026-001",
  "performer" : [{
    "actor" : {
      "reference" : "practitioner1"
    }
  }]
}

```
