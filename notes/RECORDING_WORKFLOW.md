# Recording Workflow

## Human Contributor Path

1. approve contributor terms
2. define clinic or deck scope
3. export line sheet from source deck
4. record dry, quiet audio per line
5. review naming, levels, and clipping
6. upload approved files to object storage
7. update pack manifest with public URLs and contributor IDs

## Cloud TTS Path

1. extract line sheet from source deck
2. render `normal` and `slow` variants
3. upload canonical files to object storage
4. record object URLs in pack manifest
5. let human voice files override by line when available
