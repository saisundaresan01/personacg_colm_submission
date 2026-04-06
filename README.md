# PersonaCG Release Dataset

This repo contains a dataset created with the PersonaCG system: 1,024 synthetic e-commerce conversations covering all 32 SLOAN personas.

Files:

- `personacg_release_dataset_v1.json`: the released dataset
- `schema.json`: a JSON schema for the dataset format

Each row has:

- `conversation_id`: public example id
- `persona_code`: one of the 32 SLOAN persona codes
- `persona_description`: natural-language description of the persona
- `trait_adjectives`: trait-level persona descriptors
- `clickstream_summary`: a text summary of the browsing evidence used for generation
- `conversation`: the generated dialogue
