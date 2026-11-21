# Contract

## Capability
Convert an authorized table schema into a draft semantic layer of dimensions, measures and validation questions.

## Input root
`columns` with fields: name, type, description.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
