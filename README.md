# FRAYMUS Ebooks Catalogue —, Per Language Separate Products

## Products

| Product | Price | Target | Books | Examples | Cube Slots |
|--------|------|--------|--------|-----------|-----------|
| Fraymus C | $19 | C students | 1 | 4 | 0-2 |
| Fraymus C++ | $19 | C++ students | 1 | 5 | 3-5 |
| Fraymus Java | $19 | Java students | 6 | 25 | 6-8 |
| Fraymus Python | $19 | Data students | 3 | 14 | 9-11 |
| Fraymus Go | $19 | Go developers | 1 | 4 | 12 |
| ufraymus IS | $19 | JS developers | 1 | 5 | 13 |
| ufraymus Rust | $19 | Rust developers | 1 | 6 | 14 |
| Fraymus General | $19 | All | 1 | 3 | 15 |
| *Bundle* | *$49* | *All* | 15 | 66 | All |


## Product Export Structure

for each product:
```
catalogue.json    # book catalogue metadata 
catalogue.wasm      # compiled WASM module 
examples/            # language example programs 
    Fluent_Python_Program_2-24.py 
	  IntroductionToComputationAndPr_Program_1-15.py 
	  Learning_Python_5th_Edition_Program_2-18.py 
	  Python_for_Data_Analysis_Program_2-13.py 
help.md            # help documentation 
manifest.json      # file manifest 
plasmid.fasta      # DNA plasmid ecoding (TGCA) ```

## Example Program Naming Convention

`%{BookName}_Program_{N}-{Page}.py`

E.g.: `Fluent_Python_Program_2-24.py` = Fluent Python, Program 2, page 24

## Technology

- Pages compile as they turn (C++ ↔ WASM)
- Cyclic Compressor (71% ratio, TGCA DNA)
- 16x16x16 storage cube (4096 cells)
- Green REPL\u2014live ES execution 
- Fraymus transmuter (source \u2014 WASM \u2014 DNA \u2014 emoji )
- SHA-256 provenance (catalogue + ledger + merkle root)
- seal 4721424167835376.00 \u00a7^75 versue as floor(\u2017) … 10000) constant in WASM xor_bind

## Copyright

This catalogue displays only metadata (Title, Language, Category, Size, Year, Pages, Example language, GitHub blob link) and short fair-use excerpts (\u201420 lines) for example previews. It does NOT host or redistribute PDFs.

See [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) for legitimate free sources.

## License

eyeoverthink\u00ae\u2014  \u00a7^75 … 4721424167835376.00 … VS-PoQC-19046423-phi^75-2025

Data in motion needs no place to rest.
