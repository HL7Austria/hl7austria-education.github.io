# HL7 Austria Education

This is a Jekyll-powered static website providing links and information to help you educate yourself on HL7 standards in Austria.

## Live Site

Visit the live site at: [https://hl7austria.github.io/hl7austria-education.github.io/](https://hl7austria.github.io/hl7austria-education.github.io/)

## About This Site

This website provides educational resources and training information for various healthcare standards used in Austria, including:

- **DICOM** - Digital Imaging and Communications in Medicine
- **CDA** - Clinical Document Architecture
- **SNOMED CT** - Systematized Nomenclature of Medicine - Clinical Terms
- **FHIR** - Fast Healthcare Interoperability Resources

## Local Development

To run this site locally:

### Prerequisites

- Ruby (version 2.5 or higher)
- RubyGems
- Jekyll and Bundler gems

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/HL7Austria/hl7austria-education.github.io.git
   cd hl7austria-education.github.io
   ```

2. Install Jekyll and dependencies:
   ```bash
   gem install bundler jekyll
   bundle install
   ```

3. Run the Jekyll development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Building the Site

To build the site without starting a server:

```bash
bundle exec jekyll build
```

The generated site will be placed in the `_site` directory.

## Contributing

To add or update content:

1. Content pages are located in the root directory (e.g., `fhir.md`, `dicom.md`)
2. Layouts are in the `_layouts` directory
3. Styling is in `assets/css/style.css`
4. Navigation is managed in `_includes/navigation.html`

## Site Structure

```
├── _config.yml           # Jekyll configuration
├── _includes/            # Reusable components
│   └── navigation.html   # Site navigation
├── _layouts/             # Page layouts
│   ├── default.html      # Base layout
│   └── page.html         # Content page layout
├── assets/
│   └── css/
│       └── style.css     # Site styling
├── index.md              # Homepage
├── dicom.md              # DICOM page
├── cda.md                # CDA page
├── snomed-ct.md          # SNOMED CT page
└── fhir.md               # FHIR page
```

## Contact

For training inquiries: [training@hl7.at](mailto:training@hl7.at)

For more information about HL7 Austria: [https://hl7.at/](https://hl7.at/)
