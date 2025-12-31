# Missouri Rules (Akoma Ntoso XML)

Missouri statutes and regulations encoded in [Akoma Ntoso](http://www.akomantoso.org/) XML format for machine-readable legal text processing.

## Structure

```
rules-us-mo/
├── statutes/                    # Missouri Revised Statutes
│   ├── title-x-taxation/        # Title X - Taxation and Revenue
│   └── title-xiii-social-services/  # Title XIII - Social Services
└── regulations/                 # Code of State Regulations (CSR)
```

## Sources

- **Statutes**: [Missouri Revised Statutes](https://revisor.mo.gov/main/Home.aspx)
- **Regulations**: [Code of State Regulations](https://www.sos.mo.gov/cmsimages/adrules/csr/csr.asp)

## Coverage

### Statutes (Missouri Revised Statutes)

| Title | Subject | Status |
|-------|---------|--------|
| X | Taxation and Revenue | Planned |
| XIII | Social Services | Planned |

### Regulations (Code of State Regulations)

| Division | Subject | Status |
|----------|---------|--------|
| 12 CSR 10 | Department of Social Services | Planned |
| 12 CSR 40 | Family Support Division | Planned |

## Akoma Ntoso Format

Files follow the [Akoma Ntoso 3.0](http://docs.oasis-open.org/legaldocml/akn-core/v1.0/akn-core-v1.0.html) standard for legal documents. Each XML file includes:

- Full hierarchical structure (titles, chapters, sections)
- Cross-references and citations
- Temporal versioning metadata
- Original source attribution

## Related Repositories

- [CosilicoAI/arch](https://github.com/CosilicoAI/arch) - Policy document archive
- [CosilicoAI/rac](https://github.com/CosilicoAI/rac) - Rules as Code DSL
- [CosilicoAI/rac-us](https://github.com/CosilicoAI/rac-us) - US federal rules

## License

Source legal texts are public domain. Encoding and tooling are Apache 2.0.
