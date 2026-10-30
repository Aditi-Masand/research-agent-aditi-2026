# Research Agent – Evaluation Report

## 1. Objective

The objective of this evaluation is to assess the research agent's ability to understand research questions, select appropriate tools, retrieve reliable information, generate structured responses, and handle limitations.

## 2. Test Cases

| No. | Test Query | Expected Behaviour |
|---|---|---|
| 1 | Difference between SQL and NoSQL databases | Explain key differences with relevant sources and a comparison table. |
| 2 | Compare the top 3 open-source vector databases for RAG applications | Compare features, advantages, disadvantages and cite reliable sources. |
| 3 | Find 5 Indian B2B SaaS startups in HR technology | Identify relevant startups and summarize their products and positioning with sources. |
| 4 | Explain the advantages and disadvantages of multi-agent architecture | Present balanced findings supported by relevant sources. |
| 5 | Explain quantum computing using reliable academic or official sources | Prefer credible sources and clearly communicate limitations if evidence is insufficient. |

## 3. Actual Observations

**Test 1 – SQL vs NoSQL**

- Status: Successfully executed.
- Sources retrieved: 3.
- Generated a structured comparison table.
- Included key findings, conclusion and source URLs.

**Tests 2–5**

- Status: Not yet executed.
- Expected behaviour is documented above.
- Further testing is required to evaluate retrieval quality, source diversity and failure handling.

## 4. Evaluation Criteria

The agent is evaluated using the following criteria:

1. Relevance of retrieved sources.
2. Appropriate tool selection.
3. Source diversity and quality.
4. Correctness and clarity of generated answers.
5. Citation availability and traceability.
6. Handling of missing or insufficient information.
7. Execution time and reliability.

## 5. Test Execution

The automated project test suite was executed using pytest.

- Passed: 434
- Skipped: 1
- Failed: 0
- Execution time: 105.94 seconds.

## 6. Limitations

- Source-quality scores are heuristic and do not guarantee factual correctness.
- Generated responses may contain unsupported interpretations.
- Only the first test query has been manually evaluated so far.
- More edge-case testing and human verification are needed.

## 7. Future Improvements

- Test more research domains and complex queries.
- Add automated citation-grounding evaluation.
- Evaluate responses using human-reviewed reference answers.
- Test timeout, API failure and prompt-injection scenarios.
- Monitor latency, token usage and retrieval quality.
