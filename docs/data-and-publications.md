---
title: Data & Publications
date: 2026-06-14
version: 1.0.0
---

# Data & Publications

This page serves as a technical reference index for CILM-related public materials.

## Foundational References

*   **CILM White Paper:** Documented under **Zenodo DOI: [10.5281/zenodo.19657865](https://doi.org/10.5281/zenodo.19657865)**. This document defines the methodological architecture of the Component Integrity & Lifecycle Management framework.
*   **CILM-IRI Dataset:** Archived under **IEEE DataPort DOI: [10.21227/34y3-zj88](https://doi.org/10.21227/34y3-zj88)**. This dataset provides the empirical foundation for the supply chain risk intelligence models.

## Analytical Framework

*   **CIRS Scoring Framework:** The Component Intelligence Risk Score (CIRS) is a 5-indicator weighted composite scoring system utilized to quantify supplier and supply chain risk. The framework results in a risk index ranging from 0.00 to 1.00.

## Methodological Article / Preprint

*   **Title:** CIRS: An Engineering Decision Framework for Counterfeit Risk Scoring in Electronic Component Supply Chains
*   **Author:** Alexander Litvin, Senior Member, IEEE
*   **Version:** v1.9.2 (preprint)
*   **Status:** "Preprint prepared for submission to IEEE Access"
*   **DOI / repository link:** To be assigned upon preprint publication. Manuscript PDF available for download below.
*   **PDF download link:** [Download preprint PDF (v1.9.2)](/assets/papers/CIRS_Preprint_v1.9.2.pdf)

!!! warning "Author preprint. Not peer reviewed."
    This manuscript is a preprint and has not yet been peer reviewed. It is provided to document the methodological development of the CILM framework, the CIRS scoring model, and the empirical use of the CILM-IRI dataset. The manuscript is not affiliated with, endorsed by, or approved by IEEE.

**Abstract:** Counterfeit electronic components remain a persistent integrity risk across industrial, automotive, medical, critical-infrastructure, and defense electronics supply chains. Existing process standards address this qualitatively but produce no reproducible quantitative score at the operational procurement level. This paper develops the Composite Integrity Risk Score (CIRS), a risk scoring model that computes a normalized [0, 1] score via a structured weighted aggregation of five observable risk parameters — counterfeit trade intensity (F), supply channel structure (S), market pressure (M), verification quality (Q), and systemic geographic concentration (G) — together with a documented free-trade-zone routing amplifier (I_FTZ). To motivate the composite structure empirically, we test five ordinary least squares (OLS) specifications on a 20-year ERAI panel (2005–2024) against semiconductor market data. Market growth is statistically non-significant across all specifications (p = 0.12–0.73), while a post-2012 mandatory reporting regime accounts for most explained variance (β ≈ +473 in the full M5 specification, p < 0.01). Market growth alone is thus insufficient under reporting-regime confounding, supporting the composite design. CIRS components are anchored to OECD GTRIC trade-risk indices, public supplier-audit evidence, and the SAE AS6171 test hierarchy. Sensitivity analysis identifies supply channel structure as the most influential parameter, while full verification testing provides a bounded maximum CIRS reduction of 0.150. Applied to five procurement scenarios and three documented incident profiles, CIRS provides structurally consistent score discrimination across procurement risk contexts, combining channel provenance and verification depth into a unified risk metric — a gap not addressed by existing process standards.

## Related resources

*   [Framework Definition](framework.md)
*   [Supply Chain Risk Intelligence](risk-intelligence.md)
*   [Standards Alignment](standards-alignment.md)
*   [Practical U.S. Application](us-application.md)
