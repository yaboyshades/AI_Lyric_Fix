# Persona Imprint Protocol (PIP) v1.4

**Repo:** A structured, JSON‐driven framework for high‐fidelity AI‐driven songwriting.

## 📜 Specification
- **Version:** 1.4  
- **Objective:** Overcome the “Qualia Gap” and “Regression to the Mean” via a Transient Subjective Instance (TSI).  
- **Key Features:**  
  - JSONC payload → TSI instantiation → consistency checks  
  - Conditional IF‐THEN logic + probabilistic weighting (CoReS integration)  
  - Granularity toggles (`integrated_sheet`, `lyrics_only`, `chart_only`)  
  - ClarificationRequest schema for ambiguity resolution  
- **See:** [`pip_v1.4_spec.json`](spec/pip_v1.4_spec.json)  

## 🛠 Usage
1. Edit your JSON payload in `examples/`.  
2. Run your LLM wrapper against `spec/pip_v1.4_spec.json`.  
3. Receive back an “Integrated Session Sheet” artifact.

## 🔖 Version History
- **v1.0** – Initial draft  
- **v1.1** – Meter tweaks & clarity improvements  
- **v1.2** – Added output schema & toggles  
- **v1.3** – Clarification protocol & lifecycle policy  
- **v1.4** – Conditional logic + probabilistic CoReS integration  

## 📄 License
[MIT](LICENSE)
