# Campus FacePass: Decision Cards Activity 🃏🏫

An interactive 25–35 minute board-game style discussion activity designed for university data science, AI ethics, and organizational governance courses (IDS704).

🌐 **Live Activity Web App**: [https://ammylin.github.io/IDS704-wk6-discussion/](https://ammylin.github.io/IDS704-wk6-discussion/)

---

## 🎯 Activity Overview & Purpose

This activity is designed to spark deep, evidence-based discussions on **algorithmic fairness** and **biometric governance** without giving students a pre-packaged answer upfront. 

Students are placed in a fictional university scenario where they must evaluate **Campus FacePass**—a proposed facial recognition system for campus access. Working in small teams, students navigate 4 staged investigation rounds using limited single-use decision cards. Each card uncovers disaggregated technical metrics, missing populations, stakeholder perspectives, contextual risk maps, or procedural recourse data.

### Fictional Scenario
The university is preparing to launch *Campus FacePass* to allow cardless access for students, faculty, and staff. The vendor claims an **overall accuracy of 98.0%**.

Teams evaluate deployment across three distinct use cases:
1. **Library & Gym Access** *(Lower-Risk Convenience Use)*
2. **Dorm & Lab Access** *(Medium/High-Risk Access Control)*
3. **Campus Police ID Support** *(High-Risk Enforcement Use)*

---

## 🕹️ Key Game Features & Mechanics

* **Single-Use Investigation Deck**: 6 cards covering aggregate metrics, disaggregated intersectional audits, category expansion, stakeholder voices, contextual risk mapping, and procedural transparency. Each card can only be played once.
* **Evidence Unlocking & Disaggregation**: Playing a card reveals concrete scenario data (e.g., disaggregated False Match Rates from 0.8% for lighter males up to 6.2% for darker females, and False Non-Match Rates up to 8.5%).
* **Missing Evidence Notices**: Highlights important information teams missed by choosing one investigation path over another.
* **Stakeholder Lenses**: Teams can optionally adopt specific participant perspectives (*Student Rep, Disability-Access Advocate, Privacy Advocate, Campus Security, Faculty/Lab Rep, Administrator*).
* **Breaking Events**: Unexpected mid-game scenarios (such as a *False Match Access Denial Incident* or *Off-Label Police Surveillance Requests*).
* **Conditional Deployment & Safeguards**: Teams assign deployment stances (*Launch*, *Limited Launch*, *Pause*) alongside customizable safeguards (*Human review, Appeal process, Independent audit, Monitoring*).
* **Non-Blocking Reflection**: All text fields (*Cited Evidence, What Would Change Your Mind, Uncertainty*) are optional and non-blocking, ensuring smooth classroom pacing.
* **Classroom Team Comparison & Theoretical Debrief**: Provides cross-group comparison prompts and connects team outcomes to **Distributive**, **Procedural**, and **Informational Fairness**, as well as the landmark **Gender Shades** study (*Buolamwini & Gebru, 2018*).

---

## 📘 Facilitator Guide & Pacing

| Stage | Duration | Core Action |
| :--- | :--- | :--- |
| **1. Setup & Role Lens** | 3–5 mins | Introduce scenario and assign team stakeholder perspectives. |
| **2. Investigation Rounds** | 12–15 mins | Teams play cards across 4 rounds and respond to breaking events. |
| **3. Deployment & Safeguards** | 5–8 mins | Select Launch / Limited Launch / Pause and assign safeguards for all 3 use cases. |
| **4. Trail Review & Comparison** | 5–7 mins | Compare decisions across teams and debrief Gender Shades concepts. |

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

*Disclaimer: Campus FacePass and all numerical metrics in this activity are fictional scenario data created for classroom instruction.*