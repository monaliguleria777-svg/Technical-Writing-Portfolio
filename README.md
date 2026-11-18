# Monali Guleria – Technical Writing Portfolio

Technical writer based in London. I write developer, API and integration documentation, work docs-as-code, and use AI tools with a habit of checking their output against the source.

## 1. FastAPI repository – technical documentation review (Aug 2026)

A source-level review of the FastAPI framework:

- Walks through the request lifecycle in `fastapi/routing.py` (`get_request_handler()`): dependency resolution, validation, endpoint execution and response serialisation.
- Reviews the security model: OAuth2 with JWT, API key authentication, dependency-based access control, secrets management and `response_model` data filtering.
- Assesses the public docs and recommends four specific improvements.

📄 [Read the review (PDF)](FastAPI_Documentation_Review.pdf)

## 2. Docs-as-code release workflow (PKWARE)

How I moved documentation for 50+ data security products into Bitbucket, Sphinx and CI/CD, so checks ran in the pipeline on every release instead of relying on review.

- Publishing errors down 40%
- Documentation reuse up 40%

📄 [Read the write-up (PDF)](Docs_as_Code_Automation_Example.pdf)

## 3. In progress: AI-assisted API doc checker

A Claude-based checker that compares draft API docs against an OpenAPI definition and a style guide, and lists every mismatch with its source. I'm testing it on one of my own earlier drafts to measure what it catches, what it misses, and how changing the rules fixes the misses.

## Contact

- Email: monaliguleria777@gmail.com
- LinkedIn: [linkedin.com/in/monali-guleria-03423b215](https://www.linkedin.com/in/monali-guleria-03423b215/)
