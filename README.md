# United States Fire Administration

The United States Fire Administration (USFA) is a government agency under the Federal Emergency Management Agency (FEMA) that is responsible for providing leadership and support to fire departments across the country. The USFA works to improve fire prevention and safety by disseminating training and education programs, conducting research on fire-related issues, and developing national fire prevention initiatives.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/apis.yml)

**Website:** https://www.usfa.fema.gov  
**Data Portal:** https://www.fema.gov/about/openfema

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Federal Government
- Fire Safety
- Emergency Management
- Public Safety
- FEMA

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

---

## APIs

### OpenFEMA Fire Data API

The OpenFEMA API provides free, read-only REST access to FEMA and USFA datasets including disaster declarations, fire management assistance declarations, and NFIRS annual public fire data. No API key required.

**Human URL:** https://www.fema.gov/about/openfema/api

#### Tags

- Fire Safety, Incident Reporting, Emergency Management, NFIRS, Federal Government

#### Properties

- [Documentation](https://www.fema.gov/about/openfema/api)
- [Portal](https://www.fema.gov/about/openfema/developer-resources)
- [DataSets](https://www.fema.gov/about/openfema/data-sets)
- [OpenAPI](openapi/openfema-fire-data-openapi.yml)
- [SpectralRules](rules/openfema-fire-data-rules.yml)
- [NaftikoCapability](capabilities/fire-incident-data.yaml)

---

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [openfema-fire-data-openapi.yml](openapi/openfema-fire-data-openapi.yml) | OpenFEMA API for fire and disaster data |

### Spectral Rules

| File | Description |
|------|-------------|
| [openfema-fire-data-rules.yml](rules/openfema-fire-data-rules.yml) | Spectral lint rules for OpenFEMA API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | APIs |
|------|------|
| [shared/openfema-fire-data.yaml](capabilities/shared/openfema-fire-data.yaml) | OpenFEMA Fire Data API (4 operations) |

#### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [fire-incident-data.yaml](capabilities/fire-incident-data.yaml) | Fire incident data research and emergency management analysis | 4 tools |

### JSON Schemas

| File | Description |
|------|-------------|
| [usfa-disaster-declaration-schema.json](json-schema/usfa-disaster-declaration-schema.json) | Schema for FEMA disaster declaration records |
| [usfa-nfirs-incident-schema.json](json-schema/usfa-nfirs-incident-schema.json) | Schema for NFIRS fire incident records |

### JSON Structures

| File | Description |
|------|-------------|
| [usfa-disaster-declaration-structure.json](json-structure/usfa-disaster-declaration-structure.json) | Field structure for disaster declaration records |

### JSON-LD Context

| File | Description |
|------|-------------|
| [united-states-fire-administration-context.jsonld](json-ld/united-states-fire-administration-context.jsonld) | Linked data context for FEMA/USFA fire and disaster vocabulary |

### Examples

| File | Operation |
|------|-----------|
| [openfema-get-disaster-declarations-example.json](examples/openfema-get-disaster-declarations-example.json) | Get Fire Disaster Declarations |
| [openfema-list-datasets-example.json](examples/openfema-list-datasets-example.json) | List OpenFEMA Data Sets |

### Vocabulary

| File | Description |
|------|-------------|
| [united-states-fire-administration-vocabulary.yml](vocabulary/united-states-fire-administration-vocabulary.yml) | Fire safety and emergency management vocabulary (NFIRS, FEMA, NFA, OpenFEMA, etc.) |

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
