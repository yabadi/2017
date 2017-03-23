---
# Sana PCHR (Spring 2017)
---

# Scope
The Spring 2017 PCHR project involves the refinement for the ongoing Sana PCHR Lebanon project to allow for wider dissemination, as well as retrospective and real-time data analytics (pending data availability) and actionable reporting for physicians, clinic/hospital administrators, sponsors, and ministries of health.

## Sana PCHR platform overview
The Sana patient-controlled health record (PCHR) platform is a mobile-health tool in the form of an electronic medical record covering the needs of vulnerable populations. The overarching goal of Sana PCHR is to reduce the rates and severity of non-communicable diseases (NCDs) among refugee populations in resource-limited settings worldwide. The inception of this project and its initial target population focused on Syrian refugees; nonetheless, it is expected that its use will eventually extend beyond this niche into other nation-wide healthcare systems. 

### Relevance of non-communicable diseases

Noncommunicable diseases (NCDs), also known as chronic diseases, are not passed from person-to-person. They are of long duration and generally slow progression. The 4 main types of noncommunicable diseases are (http://www.who.int/mediacentre/factsheets/fs355/en/):
- Cardiovascular diseases (e.g. heart attacks and stroke)
- Cancers
- Chronic respiratory diseases, such as chronic obstructive pulmonary disease (COPD) and asthma 
- Diabetes

Key facts on global burden of NCDs are (http://www.who.int/mediacentre/factsheets/fs355/en/):

- Noncommunicable diseases (NCDs) kill 38 million people each year.
- Almost three quarters of NCD deaths - 28 million - occur in low- and middle-income countries.
- Sixteen million NCD deaths occur before the age of 70; 82% of these "premature" deaths occur in low- and middle-income countries.
- Cardiovascular diseases account for most NCD deaths, or 17.5 million people annually, followed by cancers (8.2 million), respiratory diseases (4 million), and diabetes (1.5 million).
- These 4 groups of diseases account for 82% of all NCD deaths.
- Tobacco use, physical inactivity, overuse of alcohol, and unhealthy diets all increase the risk of dying from an NCD.
- NCDs in general require *continuous* care to prevent further complicationn; for example, a diabetic foot ulcer if detected early is much easier to treat.
- Global costs associated with treating NCDs surpass the trillion dollar mark every year, due to lengthy treatment regimens.

Key facts on burden of NCDs in Lebanon and Syria are (http://www.who.int/nmh/countries/syr_en.pdf):
- NCDs are highly prevalent in the Syrian population and are responsible for almost half of deaths within the region.
- Syrian refugees do not generally have continuous care for NCDs, because they encounter different physicans who treat them without understanding their prior medical history.
- Continuous treatment of NCDs require substantial behavioral changes and strict medication adherence, something particularly difficult to achieve in refugee populations where patient follow-up is uniquely difficult.

### Sana PCHR history and current status (as of March 22, 2017)
Starting in early 2015, Sana PCHR was envisoned as a mobile health tool for chronic disease management in refugee populations as a project developed by the Massachusetts Institute of Technology (MIT) in conjunction with the Johns Hopkins University (JHU). Working closely with the government of Lebanon, this system was designed specifically to meet the needs of Syrian refugees. The first iteration of Sana PCHR was deployed for pilot testing and evaluation in February 2017, which is expected to continue until September 2017. Data in the form of digital health records has already been obtained through this platform (from approx. 3,000 patients). Current data reporting capabilities for Sana PCHR are limited to retrieval of the full database for analysis in external software such as SAS and R (no real-time analytics have been implemented). Easy to use reporting schemes are also non-existent in the current implementation of Sana PCHR. Preliminary evaluation of the clinical utility of this system is still inconclusive and further analysis is required to assess its field utility; nonetheless, data is suggestive of a positive effect in the use of this system for improving care in the aforementioned refugee population.

### Sana PCHR strategy
The PCHR system aims to provide a secure, easy-to-use, and actionable open-source medical record system for vulerable populations that allows physicians to acces the medical history of patients *as recorded by previously encountered physicans* to inform further care of patients (see Care Flow Diagram below from PCHR 2016). With this in mind, the system should allow for communication of actionable information across physicians, allowing them to access the medical record at different timepoints and locations to provide evidence-based care, reduce adverse effects, reduce costs, and improve outcomes. Ideally, the system should also incorporate real-time data analytics and reporting of aggregated patient data to facilitate population-based interventions and provide better accountability for sponsors.

### Sana PCHR framework
The PCHR system contains (see Data Flow below):
- SMS reminders sent to patients to assist with medication adherence and to remind patients about patient appointments
- An Android Client for physicians to record information during an appointment
- A Decision Support System to assist with the interpretation of certain clinical scores with respect to NCDs

Care Flow             |  Data Flow
:-------------------------:|:-------------------------:
![Care Flow](images/care_flow.png)  |  ![Data Flow](images/data_flow.png)

### Sana PCHR value proposition
The desired value proposition for this system is:
- Measurable reduction in the incidence and prevalence of NCDs (i.e. by providing higher-quality and more continuous healthcare to refugee populations)
- Measurable reduction of complications derived from NCDs
- Measurable reduction in costs for healthcare providing organizations (i.e. by providing a less expensive option for collection of patient data avoiding in-person paper surveying at local clinics)
- Automated real-time analysis reporting of population-level agregate data to guide interventions and justify funding from sponsors

See this [Introductory Video](https://vimeo.com/90270531) for furter detail. 

## Spring 2017 Sana PCHR project requirements
### Mandatory requirements 
- Improve dissemination of Sana PCHR platform
  1)	Evaluation of current website (Sana PCHR), including usability, strengths, and challenges (Krysla)
  2)	Development of a website roadmap based on user input (Krysla)
  
- Retrospective data analytics to enable evidence-based actionable interventions
  1)	Given existing data model, brainstorm what additional data should be collected in the future to better meet the needs of stakeholders by addressing questions such as (Maia):
        - What are the core needs of various stakeholders?
        - How well does the current data model address the needs of various stakeholders?
        - Which stakeholders are most under-served by the current data model?
        - What additions to the data model would yield the greatest usability for multiple stakeholders?
  2)	Analysis, development, and implementation of epidemiological models to analyse reportable data (pending data availability) (Maia)
  3)  Analysis, development, and implementation of basic deep learning framefok for data mining (pending data availability) (Luis)

- Integrated real-time data analytics and reporting to improve accountability with sponsors and facilitate continued funding
  1)	How should aggregate statistics be presented for various stakeholders (i.e. information slicing and visualization by provider, patient type, billing, operational variables, etc.)? (Luis)
  2)  Which specific aggregate statistics should be presented for various stakeholders? (Luis)

### Optional requirements 
- Securement of additional grants to continue improvements and implementation
- UX redesign to further ease use of platform

## Relevant stakeholders
- Current Sana PCHR sponsors
- Current Sana PCHR collaborators (e.g. UNHCR)
- Local clinics administrators (e.g. clinics using Sana PCHR)
- Local clinical personnel (e.g. nurses, physicians, voluntaries, technicians)
- Ministries of Health (e.g. Lebanon Gov)
- Potential future Sana PCHR sponsors
- Potential future Sana PCHR collaborators (e.g. UNHCR)

## Limitations
- Involved developers: 3 students 12 credits + 1 student 4 credits
- Development time < 2 months

## Process
- Scrum will be used as an iterative and incremental agile software development framework for managing product development of Spring 2017 Sana PCHR objectives.

### SCRUM roles 

- Product Owner (Kenneth Paik)
- Scrum Master (TBD).- accountable for removing impediments to the ability of the team to deliver the product goals and deliverables. The Scrum Master is not a traditional team lead or project manager, but acts as a buffer between the team and any distracting influences. The Scrum Master ensures that the Scrum framework is followed. The Scrum Master helps to ensure the team follows the agreed processes in the Scrum framework, often facilitates key sessions, and encourages the team to improve. The role has also been referred to as a team facilitator[20] or servant-leader to reinforce these dual perspectives.
- Development Team (TBD)

## Timeline
- Final class deliverable: May 12, 2017

## Deliverables
- Mandatory requirements: May 12, 2017

### Project outputs

### Semester progress

## Team members

Krysla Grothe

Maimuna (Maia) Majumder, M.P.H. (Ph.D. Candidate | ESD/IDSS | Massachusetts Institute of Technology)

Neha Safaya

Luis R Soenksen (Ph.D. Candidate | Mech. Eng. | Massachusetts Institute of Technology)

Advising by Dr. Kenneth Paik
