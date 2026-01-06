## ⚠️ This Project Has Been Archived

**patent_client_examples** has been archived and is no longer actively maintained.

### Why?

The [patent_client](https://github.com/parkerhancock/patent_client) library was originally designed for human developers writing Python scripts. The landscape has changed—AI coding assistants are now the primary consumers of IP data libraries. The new **[ip_tools](https://github.com/parkerhancock/ip_tools)** library is purpose-built for this new paradigm:

- **AI-First Design:** Optimized for use by AI agents like Claude Code
- **Simplified API:** Async-first with straightforward function calls instead of ORM-style queries
- **Modern Stack:** Built on Python 3.12+ with native type parameters
- **Structured Responses:** Pydantic models designed for agent consumption

For new projects, use **[ip_tools](https://github.com/parkerhancock/ip_tools)**:

```bash
pip install ip_tools
```

---

# Patent Client Examples

This is a collection of jupyter notebooks showing some examples of how to use the [patent_client](https://github.com/parkerhancock/patent_client) library. Each walks through solving a particular problem using nothing more than patent_client and standard python data science tools.

Current examples are:

- Introduction - a general introduction to the library
- Patent Expiration Dates - How to calculate patent expiration dates
- Company Ownership - For a company, view its US and international patent portfolio
- Examiner Monitor - Get detailed information on a particular US Patent Examiner
- Continuity Graphs - How to generate continuity graphs for related patent applications
