# LeaseLens 🔍  
**AI-powered lease intelligence platform for renters and landlords**

---

## Product Overview  
LeaseLens helps users **understand, evaluate, and act on lease agreements** using state-specific legal grounding. It transforms dense legal documents into **clear insights, risk signals, and actionable next steps**.

---

## Core Value Proposition  
- **Tenants:** Identify unfair or illegal clauses before signing  
- **Landlords:** Ensure leases comply with state regulations  
- **Both:** Reduce ambiguity and make informed decisions faster  

---

## Key Features  

### Clause Intelligence  
- Clause-by-clause analysis with risk classification:  
  - Red — Potentially illegal  
  - Orange — Needs review  
  - Green — Compliant  
- Includes **state statute citations**

### Personalized Insights  
- Role-based summaries (Tenant vs Landlord)  
- Converts legal language into clear, plain English  

### Actionable Next Steps  
- Generates prioritized checklists  
- Focused on resolving high-risk clauses  

### Ask AI (RAG Chat)  
- Context-aware chatbot grounded in:  
  - Uploaded lease  
  - State-specific legal data  
- Enables reliable follow-up questions  

### Draft Assistant  
- Supports lease drafting and clause improvements  
- Aligns documents with compliance standards  

---

## 🚀 Live Demo  
Watch here:(https://youtu.be/1N-UMN8xVAE)
---

## User Flow  

1. Select role (Tenant or Landlord)  
2. Select state (CT or NY)  
3. Upload lease PDF  
4. Receive:
   - Clause health analysis  
   - Summary insights  
   - Actionable next steps  
5. Ask follow-up questions via AI  

---

## System Architecture  

### Lease Analysis Pipeline  
- Document ingestion and parsing  
- State classification  
- Legal knowledge retrieval  
- Clause-level LLM analysis  
- Structured output (JSON)

### Conversational Layer  
- RAG-based chatbot  
- Context-aware responses  
- Dynamic retrieval by state and lease  

### Knowledge Layer  
- Curated legal datasets for:  
  - Connecticut landlord-tenant law  
  - New York landlord-tenant law  
- Hybrid semantic + embedding search  

<img width="1561" height="594" alt="image" src="https://github.com/user-attachments/assets/5739fa81-2b2d-40bb-a6d4-c57a09670026" />

<img width="1698" height="286" alt="image" src="https://github.com/user-attachments/assets/e3bf6da5-84e0-4e80-9067-18b64d72fcd1" />

---

## Tech Stack  

**Frontend**  
- React (Google AI Studio)

**Backend**  
- Dify (workflows + chatflows)

**AI / ML**  
- GPT-4o-mini  
- text-embedding-3-large  
- Retrieval-Augmented Generation (RAG)

---

## Product Decisions  

### Grounded AI over Hallucination  
Uses retrieval-based pipelines to ensure outputs are tied to real statutes.

### Dual-Sided Design  
Built for both tenants and landlords to reflect real-world usage.

### Structured Outputs  
JSON-based responses enable scalable UI and future integrations.

### Risk-First UX  
Prioritizes high-risk clauses instead of overwhelming users.

---

## Current Coverage  
- Connecticut (CT)  
- New York (NY)  

---

## Future Roadmap  
- Multi-state expansion  
- Lease editing + e-sign workflows  
- Property management integrations  
- Compliance scoring systems  

---

## Why This Matters  
LeaseLens makes legal understanding **accessible, transparent, and actionable**, reducing risk and improving decision-making for both renters and landlords.
