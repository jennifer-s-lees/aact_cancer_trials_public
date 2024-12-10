# Study Protocol: Multimorbidity in Clinical Cancer Trials
Dr Jennifer Lees and Prof David McAllister

## Overview

This protocol describes the purpose, trial selection and intended
conduct of Vivli Project ID ***0000xxxx***: Multimorbidity in clinical
cancer trials.

## Background

Since the 1970s, cancer survival has doubled, after an explosion in the
availability of targeted therapies. Both cancer and targeted therapies
are strongly linked to the development of multimorbidity, particularly
cardiometabolic diseases (including kidney disease, cardiovascular
disease and diabetes). These conditions commonly develop in parallel
with each other (Ndumele et al., 2023) and are more likely to develop or
worsen in people who had pre-existing multimorbidity. Moreover,
development of multimorbidity substantially impacts on overall health,
well-being and survival.

Multimorbidity is extremely common in the setting of cancer. Among
people with cancer, around 20-50% have underlying kidney disease, 10-40%
have underlying cardiovascular disease and around 8-18% have diabetes.
We have shown previously that people with pre-existing multimorbidity
(particularly cardiometabolic multimorbidity) are commonly excluded from
clinical cancer trials (Elyan et al., 2023; Rankin et al., 2024),
leaving very limited evidence for the efficacy and safety of cancer
treatments among these high-risk patient groups.

We will use individual participant-level data (IPD) from clinical cancer
trials held within Vivli - Center for Global Clinical Research Data
(Vivli; <https://vivli.org>) to describe the representation of patients
with multimorbidity, explore factors that contribute to participant
attrition and identify to what extent there are differences in the
effectiveness of safety of cancer medicines among people with
pre-existing multimorbidity. Exploration of these data may: i)
justify/negate exclusion of participants with multimorbidity disease
from cancer trials and ii) inform clinical monitoring guidelines in
patients treated for cancer.

## PICO selection criteria

- *Population:* patients with common cancer types
- *Intervention:* systemic anti-cancer therapy
- *Comparator:* placebo or other control (including
  investigator-selected chemotherapy and best supportive care)
- *Outcome(s):* overall survival and/or cancer survival

## Inclusion criteria

- Phase III or IV trials
- Parallel-group trials
- Index condition was one of the following common cancer types: lung,
  colorectal, gastro-oesophageal, renal tract (kidney, ureter, bladder),
  melanoma, ovarian, breast or prostate
- Minimum of 300 participants
- Investigational medical product (IMP) was a systemic-anticancer
  therapy (chemotherapy, hormonal therapy, targeted agent or biological
  compound for the treatment of cancer)
- Trial results posted on clinicaltrials.gov
- Primary outcome(s) included at least one of the specified outcomes of
  interest

## Exclusion criteria

- IMP is not currently approved by the Food and Drug Administration
  (FDA) for use in clinical practice for a cancer indication (via
  <Drugs@FDA>: <https://open.fda.gov/data/drugsfda/>)

## Primary exposures

1.  **Multimorbidity**

Long-term conditions will be identified based on a published Delphi
consensus statement on the quantification of multimorbidity in research
(Ho et al., 2022). Conditions will be identified using MedDRA preferred
terms where available. Where medical history is not available,
concomitant medications will be used as proxies for individual
conditions/groups of conditions (Hanlon et al., 2019). We will then
quantify:

- Number of long-term conditions
- Number of cardiometabolic/non-cardiometabolic long-term conditions
- Weighted comorbidity scores (Charlson and Elixhauser comorbidity
  indices, Comorbidity-Polypharmacy Score \[CPS\] and Adult Comorbidity
  Evaluation 27 score \[ACE-27\])

1.  **Cardiometabolic disease**

The definitions are based on likely availability of data to define these
conditions from the individual participant-level data:

- *Chronic kidney disease:* based on documented history and/or estimated
  glomerular filtration rate (eGFR). Most or all trials of systemic
  anti-cancer therapies have listed one or more kidney disease markers
  as exclusion criteria which are predominantly creatinine-based
  measures of kidney function (Elyan et al., 2023; Kitchlu et al.,
  2018). Using serum creatinine (likely to be available in all or most
  trials), we will be able to calculate estimated glomerular filtration
  rate (the most widely used marker of kidney function in clinical
  practice) using various formulae and compare with other kidney
  function estimates (creatinine clearance \[CrCl\]: the most widely
  used marker of kidney function in clinical trials). We will assess
  treatment effects across the spectrum of eGFR/CrCl, by 10mL/min
  decrements and across the threshold for diagnosis of CKD stage 3 (60
  mL/min/1.73m2) and CKD stage 4 (30 mL/min/1.73m2).

- *Diabetes mellitus (type 1 and type 2):* based on documented medical
  history and/or concomitant medications suggestive of treatment for
  diabetes.

- *Cardiovascular disease (ischaemic heart disease, arrhythmia, heart
  failure, peripheral vascular disease, transient ischaemic attack,
  stroke, heart failure):* based on documented medical history and/or
  concomitant medications suggestive of treatment for cardiovascular
  disease.

- *Metabolic-associated steatohepatitis:* based on documented medical
  history and/or biomarker-based risk scores (e.g. Fibrosis-4 Score
  \[FIB-4\] or the NAFLD Fibrosis Score \[NFS\]).

## Outcomes

**Efficacy outcomes:**

- *Overall survival* (time from randomization to death)
- *Cause-specific survival* (time from randomization to death attributed
  to cancer in the absence of other causes of death)

**Safety outcomes:**

Safety outcomes will be defined as per the Common Terminology Criteria
for Adverse Events (CTCAE). CTCAE is a standardized method of recording
adverse events in clinical cancer trials. It was developed by the United
States Department of Health and Human Services and defines adverse
events according to System Organ Class (SOC; the highest level of MedDRA
hierarchy) and accompanied by a description of severity. Severity is
graded as 1 (mild) to 5 (death related to adverse event). A grade of 3
or above indicates a serious adverse event (SAE; enough to warrant
hospitalization). Events will be assessed as related or unrelated to
IMP.

The list of adverse events of interest are as follows:

- *Drug discontinuation* (due to adverse event)
- *All-cause hospitalization* (any SOC; severity grade 3 or 4): time to
  first event and number of events during follow-up
- *Hospitalization associated with IMP* (any SOC with severity grade 3
  or 4, where thought related to IMP): time to first event and number of
  events during follow-up

Organ class-specific outcomes of interest (adverse event grade 2, 3 or
4; related or unrelated to IMP) will be explored also as time to first
event and/or number of events during follow-up. It is expected that the
following SOC adverse events will be particularly common due to a known
biological association between cancer, systemic anti-cancer therapies
and cardiometabolic disease: Cardiac, Vascular, Infections and
infestations, Renal and urinary disorders.

Where data are available, we will assess the impact of systemic
anti-cancer therapies on biochemical markers of cardiometabolic risk and
disease, such as blood pressure, body mass index, lipid profiles, eGFR
and HbA1c.

## Statistical analysis

All analyses will be performed using a two-stage approach:

- **Stage 1:** Models will be fit to individual trials. The model
  outputs (coefficients and variance-covariance matrices) alongside
  summary statistics for study variables, will then be obtained.

- **Stage 2:** Model outputs will be treated as outcomes in
  meta-analyses, with predictor variables being trial-level
  characteristics such as index condition, treatment comparisons and
  trial phase.

This approach has been used in our prior publications using the Vivli
resource (Hanlon et al., 2020, 2021, 2022, 2023; Lees et al., 2024; Lees
et al., 2022).

The meta-analysis level models will have normal likelihoods (or when
multiple coefficients are being simultaneously modelled, multivariate
normal likelihoods). For the intercepts, trial will be treated as a
random effect. For other predictors (condition, index condition, etc) we
will explore fixed and random effects. Meta-analysis models will be
fitted using the Bayesian modelling software Stan.

For the trial-level models, the choice of model depends on the outcome
and so is described separately for each outcome below. For all models,
we will explore non-linearity for continuous variables using fractional
polynomials or restricted cubic splines. Having decided on appropriate
polynomials (or knots) for continuous variables, we will include
interaction terms between treatment effect and these transformed
variables (or components of the splines) to estimate treatment/covariate
interactions (Riley et al., 2020; Royston & Parmar, 2002). Generalised
linear models will be fit in R using the GLM function and survival
models will be fit in R using Cox regression.

**Objective specific analysis details:**

*1. The prevalence and distribution of multimorbidity within trials*

- Data will be summarised as the prevalence, distribution and overlap of
  multimorbidity and cardiometabolic disease as well as other baseline
  characteristics and frailty (Hanlon et al., 2019). Distributions will
  be assessed by selecting a parametric distribution which fits the data
  well.

*2. Whether the rates of target and incident and total adverse outcomes
differ by presence of multimorbidity*

- We will fit Poisson regression models of adverse events on these
  characteristics, with and without adjustment for potential
  confounders, using the log of the person-time to follow-up as an
  offset variable. If there is evidence of over-dispersion we will use
  alternative methods such as quasi-Poisson or negative binomial models.

*3. Whether treatment effects on target and adverse outcomes differ by
the presence and extent of multimorbidity*

- For binary, count and time to event variables we will perform
  logistic, Poisson and Cox regression modelling respectively. For
  continuous outcomes which are approximately normally distributed we
  will fit linear regression models. For continuous outcomes which are
  not approximately normally distributed we will perform an appropriate
  transformation. The influence of multimorbidity on treatment effects
  will be tested by fitting treatment/covariate interaction terms as
  above.

*4. Whether (a) presence of multimorbidity affects risk of failing trial
screening, and b) whether these characteristics feature in/improve a
prediction model estimating the risk of screen failure, which we will
develop.*

- For both (a) and (b) we will model screen failure using logistic
  regression models. These will be two-stage analyses as per Objective
  3.

*5. Whether (a) presence of multimorbidity affects the risk of trial
attrition, and whether (b) these characteristics improve a prediction
model estimating the risk of trial attrition, which we will develop.*

- For both (a) and (b) we will model screen failure using time to event
  models. We hope to use parametric survival models (e.g. Weibull,
  Generalised Gamma) provided these fit the data adequately.

*6. Whether calibrating trials to routine data populations richer in
people with multimorbidity modifies trial findings*

- The outputs from Objective 3 will be meta-analysed, then subsequently
  used to “predict” treatment effects in a target populations from
  routine care as described in previous work (Butterly et al., 2022).
  This will be a weighted summation of treatment main effects and
  covariate-treatment interactions over the distribution of patients in
  a real-world setting.

**Missing data**

Due to the complexities of these analyses, either simple single
imputation or complete case analysis will be used. The limitations of
using this approach will be stated in any publication.

## Analysis timelines and prioritisation

Project funding spans 2024-2029. Management and harmonisation of trial
IPD may be resource-intensive due to differences in access
permissions/speed of access, data formats, coding systems and metadata:
the greatest source of variation is expected to exist across trial
sponsors. We will therefore conduct analysis serially, taking each
indication in turn, using the following to prioritise the selection of
indications:-

- *Data consistency:* Higher priority will be allocated where there are
  more trials available for a single lead sponsor and cancer type and/or
  IMP class.

- *Data availability:* Higher priority will be allocated where relevant
  data are available for analysis.

There will be a decision point with respect to the feasibility and value
of additional analyses before starting work on each new indication. We
will update this protocol when a new indication has been selected.

**TABLE**

*Cross-tabulation of number of requested trials by lead sponsor and
cancer type*

| Lead Sponsor               | Breast | Colorectal | Gastroesophageal | Lung | Melanoma | Ovarian | Prostate |
|:---------------------------|:------:|:----------:|:----------------:|:----:|:--------:|:-------:|:--------:|
| AstraZeneca                |        |            |                  |  7   |          |         |          |
| Bayer                      |        |            |                  |      |          |         |    1     |
| Boehringer Ingelheim       |   1    |     1      |                  |  7   |          |    1    |          |
| Eli Lilly and Company      |   3    |     1      |        2         |  10  |          |         |          |
| Genentech, Inc.            |   3    |            |        1         |  2   |          |    1    |          |
| Genzyme, a Sanofi Company  |        |            |                  |  3   |          |         |          |
| Hoffmann-La Roche          |   14   |     3      |        2         |  9   |    3     |    1    |          |
| Ono Pharmaceutical Co. Ltd |        |            |        1         |      |          |         |          |
| Pfizer                     |   2    |            |                  |      |          |         |          |
| Sanofi                     |        |     1      |                  |      |          |         |    3     |

## Funding

This project is funded by a Wellcome Trust Early Career Award
(301005/Z/23/Z).

## References

Butterly, E., Wei, L., Adler, A. I., Almazam, S. A. M., Alsallumi, K.,
Blackbourn, L. A. K., Dias, S., Hanlon, P., Hughes, K., Lewsey, J.,
Lindsay, R., McGurnaghan, S., Petrie, J., Phillippo, D., Sattar, N.,
Tomlinson, L. A., Welton, N., Wild, S., & McAllister, D. (2022).
Calibrating a network meta-analysis of diabetes trials of sodium glucose
cotransporter 2 inhibitors, glucagon-like peptide-1 receptor analogues
and dipeptidyl peptidase-4 inhibitors to a representative routine
population: a systematic review protocol. BMJ Open, 12(10), e066491.
<https://doi.org/10.1136/bmjopen-2022-066491>

Elyan, B. M. P., Rankin, S., Jones, R., Lang, N. N., Mark, P. B., &
Lees, J. S. (2023). Kidney Disease Patient Representation in Trials of
Combination Therapy With VEGF-Signaling Pathway Inhibitors and Immune
Checkpoint Inhibitors: A Systematic Review. Kidney Medicine, 100672.
<https://doi.org/10.1016/j.xkme.2023.100672>

Hanlon, P., Butterly, E., Lewsey, J., Siebert, S., Mair, F. S., &
McAllister, D. A. (2020). Identifying frailty in trials: an analysis of
individual participant data from trials of novel pharmacological
interventions. BMC Medicine, 18(1).
<https://doi.org/10.1186/s12916-020-01752-1>

Hanlon, P., Butterly, E., Shah, A. S. V, Hannigan, L. J., Wild, S. H.,
Guthrie, B., Mair, F. S., Dias, S., Welton, N. J., & McAllister, D. A.
(2022). Assessing trial representativeness using serious adverse events:
an observational analysis using aggregate and individual-level data from
clinical trials and routine healthcare data. BMC Medicine, 20(1), 410.
<https://doi.org/10.1186/s12916-022-02594-9>

Hanlon, P., Butterly, E. W., Shah, A. S., Hannigan, L. J., Lewsey, J.,
Mair, F. S., Kent, D. M., Guthrie, B., Wild, S. H., Welton, N. J., Dias,
S., & McAllister, D. A. (2023). Treatment effect modification due to
comorbidity: Individual participant data meta-analyses of 120 randomised
controlled trials. PLOS Medicine, 20(6), e1004176.
<https://doi.org/10.1371/journal.pmed.1004176>

Hanlon, P., Corcoran, N., Rughani, G., Shah, A. S. V, Mair, F. S.,
Guthrie, B., Renton, J. P., & McAllister, D. A. (2021). Observed and
expected serious adverse event rates in randomised clinical trials for
hypertension: an observational study comparing trials that do and do not
focus on older people. The Lancet Healthy Longevity, 2(7), e398–e406.
<https://doi.org/10.1016/s2666-7568(21)00092-1>

Hanlon, P., Hannigan, L., Rodriguez-Perez, J., Fischbacher, C., Welton,
N. J., Dias, S., Mair, F. S., Guthrie, B., Wild, S., & McAllister, D. A.
(2019). Representation of people with comorbidity and multimorbidity in
clinical trials of novel drug therapies: An individual-level participant
data analysis. BMC Medicine, 17(1).
<https://doi.org/10.1186/s12916-019-1427-1>

Ho, I. S. S., Azcoaga-Lorenzo, A., Akbari, A., Davies, J., Khunti, K.,
Kadam, U. T., Lyons, R. A., McCowan, C., Mercer, S. W., Nirantharakumar,
K., Staniszewska, S., & Guthrie, B. (2022). Measuring multimorbidity in
research: Delphi consensus study. BMJ Medicine, 1(1), e000247.
<https://doi.org/10.1136/bmjmed-2022-000247>

Kitchlu, A., Shapiro, J., Amir, E., Garg, A. X., Kim, S. J., Wald, R., &
Harel, Z. (2018). Representation of patients with chronic kidney disease
in trials of cancer therapy. Journal of the American Medical
Association, 319(23), 2437–2439.
<https://doi.org/10.1001/jama.2018.7260>

Lees, J., Crowther, J., Hanlon, P., Butterly, E. W., Wild, S. H., Mair,
F., Guthrie, B., Gillies, K., Dias, S., Welton, N. J., Katikireddi, S.
V., & McAllister, D. A. (2024). Participant characteristics and
exclusion from phase 3/4 industry funded trials of chronic medical
conditions: meta-analysis of individual participant level data. BMJ
Medicine, 3(1), e000732. <https://doi.org/10.1136/bmjmed-2023-000732>

Lees, J. S., Hanlon, P., Butterly, E. W., Wild, S. H., Mair, F. S.,
Taylor, R. S., Guthrie, B., Gillies, K., Dias, S., Welton, N. J., &
McAllister, D. A. (2022). Effect of age, sex, and morbidity count on
trial attrition: meta-analysis of individual participant level data from
phase 3/4 industry funded clinical trials. BMJ Medicine, 1(1), e000217.
<https://doi.org/10.1136/bmjmed-2022-000217>

Ndumele, C. E., Rangaswami, J., Chow, S. L., Neeland, I. J., Tuttle, K.
R., Khan, S. S., Coresh, J., Mathew, R. O., Baker-Smith, C. M.,
Carnethon, M. R., Despres, J.-P., Ho, J. E., Joseph, J. J., Kernan, W.
N., Khera, A., Kosiborod, M. N., Lekavich, C. L., Lewis, E. F., Lo, K.
B., … Elkind, M. S. V. (2023). Cardiovascular-Kidney-Metabolic Health: A
Presidential Advisory From the American Heart Association. Circulation,
148(20), 1606–1635. <https://doi.org/10.1161/CIR.0000000000001184>

Rankin, S., Elyan, B., Jones, R., Venugopal, B., Mark, P. B., Lees, J.
S., Petrie, M. C., & Lang, N. N. (2024). Cardiovascular Eligibility
Criteria and Adverse Event Reporting in Combined Immune Checkpoint and
VEGF Inhibitor Trials. JACC: CardioOncology, 6(2), 267–279.
<https://doi.org/10.1016/j.jaccao.2023.12.010>

Riley, R. D., Debray, T. P. A., Fisher, D., Hattle, M., Marlin, N.,
Hoogland, J., Gueyffier, F., Staessen, J. A., Wang, J., Moons, K. G. M.,
Reitsma, J. B., & Ensor, J. (2020). Individual participant data
meta‐analysis to examine interactions between treatment effect and
participant‐level covariates: Statistical recommendations for conduct
and planning. Statistics in Medicine, 39(15), 2115–2137.
<https://doi.org/10.1002/sim.8516>

Royston, P., & Parmar, M. K. B. (2002). Flexible parametric
proportional‐hazards and proportional‐odds models for censored survival
data, with application to prognostic modelling and estimation of
treatment effects. Statistics in Medicine, 21(15), 2175–2197.
<https://doi.org/10.1002/sim.1203>
