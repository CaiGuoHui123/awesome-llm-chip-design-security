# Awesome LLM Chip Design & Security

A curated reading list on LLM-driven chip design automation and hardware security, organized by:
**Intelligent EDA Closed-Loop (Generation–Optimization–Verification–Fixing) + Lifecycle Security (Design–Verification–Deployment/Operation)**.

**Note:** The complete bibliography covered in our survey will be released soon.

## Taxonomy

### Part A. Intelligent EDA Closed-Loop
1) Spec Understanding & Architecture/RTL Generation  
2) Constraint Optimization & PPA Convergence  
3) Verification & Property Checking (incl. security properties)  
4) Defect Localization & Debugging/Fixing (incl. security defects)

### Part B. Lifecycle Security
- Design-time security (trojans/backdoors, secure coding, IP protection)
- Verification-time security (security assertions, formal, fuzzing)
- Deployment/Operation (monitoring, patching, supply chain, side-channel, etc.)

## Papers (with tags)

**Task tags:** rtl-gen, constraint-ppa, verification, debug-fix, trojan-detect, vuln-analysis  
**Method tags:** prompt, finetune, rag, tool-in-the-loop, multi-agent

| Year | Venue | Title | Task | Method | Benchmarks/Datasets | Code | Notes |
|---|---|---|---|---|---|---|---|
| 2025 | arXiv | Paper Title | rtl-gen | rag; tool-in-the-loop | verilogeval | ✔️ | short takeaway |

## Datasets & Benchmarks
- VerilogEval / RTLLM / ...
- Security datasets (HW-CWE / CVEs / ...)

## Reproducibility Checklist
- Code available?
- Dataset available?
- Evaluation script?
- Toolchain details (EDA stack / simulator / formal tool)?
- Random seeds / configs?

## How to Contribute
- Add a paper via PR using the template
- Follow the tagging rules above

## Citation
If you find this repo useful, please cite our survey.

