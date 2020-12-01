# TG RISC-V Nexus Trace
Working repository of the RISC-V Nexus Trace TG report.  Nexus Trace TG Home page is [here](https://lists.riscv.org/g/tech-nexus).

Reference C code for Nexus Trace dumper/encoder/decoder is [here](./refcode/c) - documentation as README.md file is provided.

File with Nexus Messages is [NexusTrace-TG-Messages.adoc](./docs/NexusTrace-TG-Messages.adoc).

Details of messages is provided here [NexusTrace-TG-MessageDetails.adoc](./docs/NexusTrace-TG-MessageDetails.adoc).

Proposed trace connectors are provided here [NexusTrace-TG-Connectors.adoc](./docs/NexusTrace-TG-Connectors.adoc).

RISC-V Trace Control Interface is [here](./docs/RISC-V-Trace-Control-Interface.adoc) (it was converted from original PDF version [here](https://lists.riscv.org/g/tech-nexus/files/RISC-V-Trace-Control-Interface-Proposed-20200612.pdf)).

Clicking on ADOC file in the github repo viewer will render a usable version as markdown.

For a better rendering, use "asciidoctor name.adoc".

This work is licensed under a Creative Commons Attribution 4.0
International License. See the LICENSE file for details.

### Initial Work (Preserved)

For initial document v0.01 (as PDF from MS Word), click [here](./pdfs/RISC-V-Nexus-Trace-Spec-2019-10-29.pdf).
Same file in ADOC format is here: [TG-RISC-V-Nexus-Trace.adoc](./docs/initial/RISC-V-Nexus-Trace-Spec.adoc).

### Additional Resources

- The [Nexus IEEE-ISTO-5001 Standard (2012-v3.0.1)](http://nexus5001.org/wp-content/uploads/2018/05/IEEE-ISTO-5001-2012-v3.0.1-Nexus-Standard.pdf) PDF file.

### Documentation generator (this section was copied as-is from V-extension page)

Requirements

`node v6+`

**Linux**: install using [nvm](https://github.com/creationix/nvm)

**OSX**: `brew install node`

**Windows**: [nodejs.org](https://nodejs.org/en/download/)

Install documentation generator

`npm i`

Build HTML/PDF documents

`npm run build`

Resulted files

`public/*`

