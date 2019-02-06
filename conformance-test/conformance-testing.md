# OpenAPI Conformance Test Suite

As OpenAPI gains broader adoption and tool support, there is a need to ensure interoperability across implementations. Enabling OpenAPI adopters to use different implementations interchangeably gives meaning to OpenAPI's stated commitment to vendor-neutrality.

The OpenAPI Conformance Test Suite, currently a Draft Specification, codifies rules, test inputs, and expected results so that implementers can verify and demonstrate conformance to the OpenAPI specification. 

This is an early step towards a formal certification process for OpenAPI implementations. The process of building the Test Suite should also expose any ambiguities or disagreements in the meaning of the specification, and force resolution of these issues.

## Scope

The initial scope of the Test Suite is limited to OpenAPI _consumers_, implementations that taken OpenAPI documents as inputs. This category includes, for example:

* Parsers
* Editors
* Linters
* Code Generators

These implementations are expected to verify that all valid input is handled without errors, and that invalid input produces the expected errors & warnings.

These implementations may also provide some form of output, but in the current phase, the Test Suite is only concerned with input verification.

## Current Status

This is currently a draft specification.

## Available Resources

(To be completed...)

## Roadmap

(To be completed...)

