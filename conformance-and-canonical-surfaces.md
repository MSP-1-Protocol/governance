# Conformance and Canonical Surfaces

This statement records where the MSP-1 specification is published, what determines
whether a declaration conforms to it, and what the project does and does not assert
about implementations. It is descriptive. It grants no permissions and imposes no
obligations beyond those in the published license.

## Canonical surfaces

MSP-1 Mark Semantic Protocol publishes through the following surfaces:

| Surface | Role |
| --- | --- |
| `msp-1.org` | Canonical specification, schema, namespace, validator, tools, governance |
| `msp-1.com` | Editorial and educational content |
| `msp-1.net` | Adoption, enterprise, and developer resources |
| `github.com/MSP-1-Protocol` | Source repositories |
| `doi.org/10.5281/zenodo.21467147` | Archived, citable specification of record |

Where these surfaces differ, the specification and schema at `msp-1.org` are
authoritative. No other domain, repository, or archive is a canonical surface of
the MSP-1 Mark Semantic Protocol.

## What determines conformance

A declaration conforms to MSP-1 when it validates against the published schema for
its declared protocol version. Conformance is a property of the declaration, not of
the party that produced it, the software that generated it, or the domain that hosts
that software.

Every MSP-1 declaration carries its own anchor: the `@context` value resolves to the
canonical schema at `msp-1.org`. A declaration is therefore verifiable against the
specification independently of how or where it was authored.

## Implementations

MSP-1 is an open protocol released under an open license. Independent
implementations — generators, validators, editors, CMS integrations, libraries, and
tooling of any kind — require no permission, registration, or notification.
Third-party tooling that emits schema-valid output produces conformant declarations
regardless of where that tooling is hosted or who operates it.

The project does not operate a certification program, an accreditation scheme, a
conformance mark, a partner register, or a list of preferred implementers. No
implementation, vendor, agency, or consultancy holds any status conferred by the
MSP-1 Protocol, and none is endorsed by it. This applies without exception, including
to any party with a relationship to the project's contributors.

The reference tools published at `msp-1.org` are reference implementations. They
demonstrate the specification; they do not define it, and using them confers no
standing that other implementations lack.

## What the protocol does not claim

MSP-1 is a declarative metadata protocol. A declaration states intent, authorship,
provenance, authority, and interpretive framing in machine-readable form. Whether
and how any agent consumes a declaration is entirely at that agent's discretion.

The MSP-1 Protocol makes no claim that publishing a declaration will produce any
particular outcome, including improved retrieval, ranking, citation, visibility,
inclusion in any index, or treatment by any specific model or service. No such
outcome is guaranteed by the specification, and none is measured or certified by
the project.

Claims of guaranteed outcomes, certified conformance, accredited status, or endorsed
implementer standing do not originate with the MSP-1 Protocol and are not supported
by it. Anyone evaluating such a claim can verify it against this statement and
against the published specification.

## Use of the name

The name "MSP-1" and the term "Mark Semantic Protocol" may be used factually to
describe implementation of, support for, or commentary on the protocol. Such use
does not indicate any relationship with the MSP-1 Protocol, and the project does not
represent that it has reviewed or approved any implementation described in those
terms.

---

*MSP-1 Mark Semantic Protocol*
