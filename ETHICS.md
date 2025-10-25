## Ethical Statement

- Data sources are open and public.
- No personally identifiable information (PII) is collected.
- All API usage complies with provider Terms of Service and rate limits.
- API keys usage complies with NIST NVD are stored securely using environment variables.
- Every dataset generated is logged with parameters, timestamps, and hashes in `DATA_README.md`.
- This workflow aligns with academic integrity and reproducibility standards at Dakota State University.

- Potential risks (bias, privacy, security)
--Actionable Intellegince, the raw data contains descriptions of known, exploitable flaws (CVEs). This information can be used to exploit systems if used by unauthorized individuals
--Risk Biased Coverage, this is fovused on public vulnerabilities and may not include zero days or private threats

- Mitigations (data handling, bias checks)
--Control access - the NVD API key is handled securely and is not commited to the public Github repo.
--Responsible sharing the collected sample data is small and public. the code is designed for read only collection

- Limitations (known constraints)
--Latency, data may not be in real time since there is a delay between the publish date and when is analyzed
--Collection is limited by the NVD's rate limits, so there won't be massive data pulls.


