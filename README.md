# Campus FacePass: Interactive Governance Simulation 🏫⚖️

An interactive 25–35 minute governance simulation designed for university data science, AI ethics, and organizational governance courses (IDS704).

🌐 **Live Activity Web App**: [https://ammylin.github.io/IDS704-wk6-discussion/](https://ammylin.github.io/IDS704-wk6-discussion/)

---

## 🎯 Simulation Overview & Purpose

This activity is an **interactive governance simulation** exploring model evaluation, intersectional fairness, stakeholder perspectives, procedural safeguards, and risk-based deployment without providing a pre-packaged answer.

Participants evaluate **Campus FacePass**—a proposed facial recognition system allowing cardless campus access. The vendor claims an **overall accuracy of 98.0%**.

Teams evaluate deployment across three distinct use cases:
1. **Library & Gym Access** *(Lower-Risk Convenience Use)*
2. **Dorm & Lab Access** *(Medium/High-Risk Access Control)*
3. **Campus Police ID Support** *(High-Risk Enforcement Use)*

---

## 🕹️ Key Features & Mechanics

* **Stakeholder Lenses with Explicit Priorities**:
  * 🎓 *Student Representative*: Informed consent and protection from wrongful access denial
  * ♿ *Disability-Access Advocate*: Equitable and reliable access across conditions and disabilities
  * ⚖️ *Privacy / Civil Liberties Advocate*: Purpose limitation, data minimization, and protection from surveillance expansion
  * 🛡️ *Campus Security Representative*: Emergency responsiveness and facility protection
  * 🔬 *Faculty / Lab Representative*: Reliable access and continuity of research
  * 🏛️ *University Administrator*: Operational feasibility, institutional risk, and public trust
* **Investigation Token Budget**: Each team receives **4 Investigation Tokens** to investigate a deck of 6 evidence cards. Teams must choose which areas to investigate and which 2 cards to leave uninvestigated.
* **Evidence Unlocking & Disaggregation**: Uncovers concrete disaggregated metrics (e.g., False Match Rates from 0.8% up to 6.2% and False Non-Match Rates up to 8.5%).
* **Breaking Events**: Unexpected scenarios (*False Match Access Denial Incident* or *Off-Label Police Search Requests*) test policy choices without consuming tokens.
* **Step-by-Step Deployment Policy & Evidence Chips**: Single use case views with selectable evidence chips. Progression requires selecting a deployment stance (*Launch*, *Limited Launch*, *Pause*), safeguards, at least 2 evidence chips, and answering *"What would change your mind?"*.
* **Clean Rationale & Class Share-Out**: Omits blank fields from summary reports and facilitates cross-team share-outs to discuss how different stakeholder priorities and token choices led to defensible governance decisions.
* **Theoretical Debrief**: Connects outcomes to **Distributive**, **Procedural**, and **Informational Fairness**, as well as the landmark **Gender Shades** study (*Buolamwini & Gebru, 2018*).

---

## 📘 Facilitator Guide & Pacing (25–35 Mins Total)

| Stage | Duration | Core Action |
| :--- | :--- | :--- |
| **1. Role & Briefing** | 3–5 mins | Introduce simulation and assign stakeholder role priorities. |
| **2. Investigation Stage** | 12–15 mins | Teams spend 4 Investigation Tokens across 6 evidence cards and respond to breaking events. |
| **3. Deployment Decisions** | 5–8 mins | Step-by-step policy decisions citing evidence chips for all 3 use cases and answering shared governance questions. |
| **4. Evidence Trail & Share-Out** | 5–7 mins | Review uncovered vs uninvestigated evidence, conduct class share-out, and debrief Gender Shades concepts. |

---

## 🛠️ Local Development & Deployment

This application is built as a zero-dependency, single-file web application (`index.html`) using semantic HTML5, CSS custom properties, and vanilla JavaScript.

### Running Locally
Simply open `index.html` in any web browser, or serve it using Python:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

### GitHub Pages Deployment
1. Push `index.html` to the `main` branch.
2. In GitHub repository settings, navigate to **Pages**.
3. Set **Source** to **Deploy from a branch** (`main` branch, `/ (root)` directory).

---

## 📖 Research Citation & Case Study Reference

This classroom exercise is inspired by algorithmic fairness research:

* **Buolamwini, J., & Gebru, T. (2018).** *Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification.* Proceedings of Machine Learning Research, 81, 77–91. [Read Paper (PMLR)](https://proceedings.mlr.press/v81/buolamwini18a.html)

*Disclaimer: Campus FacePass and all numerical metrics in this simulation are fictional scenario data created for classroom instruction.*