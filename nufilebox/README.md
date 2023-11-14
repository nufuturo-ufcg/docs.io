## NuFileBox documentations

Official repository of the documentations produced in the NuFileBox project, a partnership between NuBank and UFCG (NuFuture)

## How to use/contribute

The repository is written primarily in [Markdown](https://guides.github.com/features/mastering-markdown/).

The contents of the repository are organized into directories (or folders) that group 
documents by areas. Each folder should have its own set of _markdown_ files. 
files for reading the documentation, and its own internal organization into directories.
All documents in other formats (PDF, docs, etc.) must be accessible via links
in the _markdown_ documents. It is also possible to have multiple _markdown_ documents with links
between them.

## Architecture

### NuFileBox Backend Doc

[Backend API Documentation](https://nufuturo-ufcg.github.io/docs.io/nufilebox/)

#### How to generate the API doc in html format
1. Make sure you have Node.js and npm (Node Package Manager) installed on your system. If you don't have them yet, you can download and install them from the official Node.js website: https://nodejs.org/
2. Run the `npx @redocly/cli build-docs <path to json>` command, replacing `<path to json>` with the full path to the JSON file that contains the API definition.
3. The command will generate a redoc-static.html file in the same directory as the JSON file, which contains the API documentation in HTML format.

### NuFileBox architectural documents

[Visão Arquitetura - v1.2.0 (full-s3)](https://docs.google.com/document/d/1axun9S-qKwrxY30AiO05xBbyEXcVo3aM0jjS-seGhPU/edit#heading=h.sst3kgdscfek)

# State of the Art
### Documents produced as search results and analysis of systems similar to BitBox (used by Nubank):

[Alternative systems to NuFileBox](https://docs.google.com/spreadsheets/d/1QFVuhiwmJ9X8vttyk-30-U7BdtQZ2irCZnYsoBWJ1OM/edit#gid=0)

# Team schedules

[Timetables](https://docs.google.com/spreadsheets/d/1NKBBje-6tm3m1CY5tWgd4hLUrcsEpesllb9VN1mTuoI/edit#gid=0)

# Management and Administrative documents

[Project Management](https://docs.google.com/spreadsheets/d/1U7NTeR2sRo-pyBu3Yh42_lYYnLcwCVk2/edit#gid=811852554) 
