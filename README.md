# detection-lab

This repository serves as an index of hands-on detection engineering and security automation projects.

My focus areas include:

- Log parsing and normalization
- Python-based enrichment workflows
- API integration
- Regex-based detection logic
- MITRE ATT&CK alignment
- Detection rule development and tuning

The goal is to build practical detection engineering skills with clean, modular code.

---

## Projects

### Log Parsing Lab
Practical JSON and raw log parsing using Python and regex.
- Structured extraction of key fields
- CSV normalization
- Named capture groups
- Pattern-based event parsing
 
Repo: [log-parsing](https://github.com/matt-detects/log-parsing)

---

### API Enrichment Lab
Python-based enrichment workflows using REST APIs.
- IP reputation lookups
- JSON parsing
- Error handling
- Structured output formatting

Repo: [API-enrichment](https://github.com/matt-detects/API-enrichment)

---

### Sigma Detection Rules
Detection rule development aligned to MITRE ATT&CK.
- ATT&CK technique mapping
- Rule documentation
- False-positive considerations

Repo: [sigma-rules](https://github.com/matt-detects/sigma-rules)

---

### Lab Environment

The detection work in this repository runs against a self-hosted ELK lab built on commodity hardware: two ThinkPad X1 Carbon laptops running Debian 13, with Elasticsearch, Kibana, Logstash, and Fleet Server in Docker alongside Zeek (network sensor), Suricata (IDS), and MISP (threat intelligence platform). Windows endpoint telemetry is collected via Sysmon and Elastic Agent.

A full description of the architecture, component rationale, ATT&CK coverage map, and data flows is in the dedicated repo:

Repo: [lab-environment](https://github.com/matt-detects/lab-environment)

---

## Approach

These labs are focused on practical detection engineering skills:

- Writing clean, modular Python
- Building enrichment pipelines
- Improving signal quality
- Reducing false positives
- Thinking in terms of detection lifecycle

Projects use synthetic data, publicly available attack datasets, open-source threat intelligence feeds, and telemetry collected from the lab environment itself.

---

More projects will be added as development continues.
