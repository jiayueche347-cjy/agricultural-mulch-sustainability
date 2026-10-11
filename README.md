# Sustainability Assessment of Agricultural Mulching Practices

This repository contains a group project completed for the course **12101 Quantitative Methods to Assess Sustainability (Polytechnical Foundation)** at the Technical University of Denmark (DTU).

The project evaluates the sustainability of different **agricultural mulching practices for organic strawberry cultivation**, integrating environmental, health-related, and socio-economic indicators.

Four cultivation scenarios were compared, ranging from no mulch to conventional LDPE mulch, recycling, and biodegradable mulch. The analysis highlights the trade-offs between environmental performance, farm profitability, labour requirements, and end-of-life management.

---

## Project Overview

The project compares four agricultural cultivation scenarios:

- **S1:** Organic cultivation without mulching and without irrigation
- **S2:** Organic cultivation with LDPE mulch film, irrigation, and no end-of-life management
- **S3:** Organic cultivation with LDPE mulch film, irrigation, and recycling
- **S4:** Organic cultivation with biodegradable mulch film and irrigation

The primary functional unit was defined as:

> **1 kg of market-ready organic strawberries**

This functional unit allows cultivation systems with different productivity levels to be compared based on their agricultural output.

The assessment considers the life cycle of the different systems, including raw material production, mulch manufacturing, agricultural use, and end-of-life management.

---

## Sustainability Indicators

Five key indicators were selected to represent environmental, health-related, and socio-economic dimensions:

### Environmental and Health Indicators

- **Climate change** — kg CO₂-eq
- **Fossil resource use** — MJ
- **Human toxicity, non-cancer** — CTUh

### Socio-Economic Indicators

- **Profitability** — €/ha
- **Labour hours saved** — h/ha

The indicators were selected from a broader set of available sustainability metrics to provide a manageable comparison across the major sustainability dimensions.

---

## Assessment Approach

The project combines several elements of quantitative sustainability assessment:

### Life-Cycle Perspective

The cultivation systems were evaluated across their major life-cycle stages, including:

- Raw material extraction or cultivation
- Polymer and mulch-film production
- Transport
- Agricultural use
- End-of-life treatment

### Quantitative Scenario Comparison

Environmental and socio-economic performance was compared across the four scenarios using quantitative indicator values.

The indicators were normalised to allow comparison across dimensions, with higher normalised scores representing better performance.

### Multi-Criteria Comparison

Normalised indicator scores were compared using:

- Multi-indicator comparison
- Radar-chart visualisation
- Sustainability ranking
- Environmental–economic trade-off analysis

### Absolute Sustainability Assessment

Climate performance was additionally examined using absolute sustainability concepts.

Two allocation approaches were considered:

- **Grandfathering**
- **Economic allocation**

This provided an additional perspective beyond relative comparisons between the four cultivation scenarios.

---

## Key Findings

### 1. No single scenario performs best across all sustainability dimensions

A clear trade-off exists between environmental and socio-economic performance.

The no-mulch scenario (**S1**) performs best across the environmental and health indicators but provides no profitability and no labour-saving benefit.

In contrast, biodegradable mulch (**S4**) provides the highest profitability and labour-saving benefits but performs worst on several environmental indicators.

### 2. Biodegradable mulch is not automatically the most environmentally sustainable option

One of the most important findings was that the biodegradable mulch scenario (**S4**) had the **highest climate impact**, approximately:

**0.242 kg CO₂-eq per functional unit**

This contradicted the initial expectation that a bio-based and biodegradable material would necessarily have the lowest carbon footprint.

The result demonstrates the importance of evaluating materials from a full life-cycle perspective rather than assuming environmental superiority based on material labels alone.

### 3. Recycling provides a systemic rather than production-stage benefit

The environmental indicator profiles of conventional LDPE (**S2**) and recycled LDPE (**S3**) are very similar.

Recycling does not substantially reduce the production-stage impacts represented by the selected indicators.

However, S3 provides an important systemic benefit by introducing an end-of-life pathway for agricultural plastic and reducing the risk of persistent plastic waste accumulation.

### 4. Sustainability depends strongly on indicator selection

The assessment used five indicators from a larger set of available sustainability indicators.

Important dimensions such as:

- Microplastic pollution
- Soil biodiversity
- Soil organic carbon
- Social acceptance

were not quantitatively represented.

The final sustainability ranking is therefore sensitive to the selected indicators and system boundaries.

### 5. None of the scenarios is absolutely sustainable from a climate perspective

The absolute sustainability assessment showed that all four cultivation systems retain climate impacts under the allocation approaches considered.

Under the grandfathering comparison, the mulching scenarios exceed the no-mulch baseline.

This illustrates an important distinction between **relative sustainability** and **absolute sustainability**: the best-performing option within a set of alternatives is not necessarily sustainable in absolute terms.

### 6. LDPE mulch with recycling provides the most balanced overall solution

The overall sustainability comparison ranked the scenarios as:

**S3 > S1 > S4 > S2**

Based on the combined assessment, **S3 — LDPE mulch with irrigation and dedicated recycling — was recommended as the most balanced option**.

S3 combines strong profitability with an explicit end-of-life solution while avoiding some of the environmental disadvantages associated with biodegradable mulch.

---

## Sustainability Trade-Offs

The project demonstrates several important sustainability trade-offs.

**Environmental vs. economic performance:**  
The environmentally strongest scenario is not economically attractive, while the most profitable scenario carries higher environmental burdens.

**Conventional vs. biodegradable materials:**  
A biodegradable material does not necessarily produce lower life-cycle impacts than a conventional fossil-based material.

**Relative vs. absolute sustainability:**  
A scenario may perform best relative to alternatives while still exceeding environmental limits.

**Recycling vs. upstream impacts:**  
Recycling may provide important circular-economy benefits even when conventional environmental indicators show little improvement in upstream emissions.

These trade-offs illustrate why sustainability decisions cannot be based on a single indicator.

---

## Uncertainty and Limitations

Several assumptions and data limitations influence the assessment:

- Only a subset of the available sustainability indicators was included.
- Microplastic impacts were not quantitatively represented.
- Long-term soil biodiversity and soil organic carbon effects were excluded.
- The analysis assumes comparable yields among the mulched scenarios.
- Biodegradable-film performance may vary under different climatic conditions.
- Sustainability rankings depend partly on indicator selection and value judgements.

These limitations highlight the importance of transparent assumptions when interpreting multi-criteria sustainability assessments.

---

## Circular Economy Perspective

The analysis identifies **mechanical recycling of LDPE mulch film** as an important circular-economy strategy.

Although recycling provides only modest improvements in the selected upstream environmental indicators, it can:

- Reduce plastic leakage into agricultural soils
- Reduce dependence on virgin polymer
- Improve end-of-life management

However, practical implementation is constrained by:

- Collection logistics
- Soil contamination of used films
- Limited recycling infrastructure
- Farmer incentives
- Material-quality requirements

This means that technological improvements alone may not be sufficient; policy instruments and coordinated value-chain solutions may also be required.

---

## Tools & Methods

**Sustainability assessment**

- Life-cycle thinking
- Functional-unit definition
- Sustainability indicator selection
- Quantitative scenario comparison
- Indicator normalisation
- Multi-criteria comparison
- Absolute sustainability assessment

**Environmental assessment**

- Climate change impacts
- Fossil resource use
- Human toxicity
- System boundaries
- End-of-life management

**Socio-economic assessment**

- Profitability
- Labour requirements
- Environmental–economic trade-off analysis

**Circular economy**

- Mechanical recycling
- Plastic waste management
- End-of-life strategies

---

## Repository Structure

```text
agricultural-mulch-sustainability/
├── README.md
└── report/
    └── agricultural-mulch-sustainability-report.pdf
```

The `report/` directory contains the complete project report, including the problem formulation, quantitative sustainability assessment, systemic interpretation, uncertainty analysis, and final recommendation.

---

## Project Information

**Course:** 12101 Quantitative Methods to Assess Sustainability (Polytechnical Foundation)  
**Institution:** Technical University of Denmark (DTU)  
**Semester:** Spring 2026  
**Project:** Sustainability Assessment of Agricultural Mulching Practices  
**Case Study:** Organic Strawberry Cultivation
