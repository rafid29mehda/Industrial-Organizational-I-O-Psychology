# **LECTURE 2: RESEARCH METHODOLOGY AND STATISTICAL FOUNDATIONS**

***

## **PART 1: QUANTITATIVE VS. QUALITATIVE RESEARCH**

Before diving into specific research designs, we need to understand the two broad approaches to research in I/O Psychology.  

### **1.1 Quantitative Research**

**Definition**: Research that uses numerical data and statistical analysis to test hypotheses.  

**Characteristics:**
- **Numerical measurement**: Variables are quantified (e.g., satisfaction rated 1-5, performance measured in units)
- **Large samples**: Typically studies hundreds or thousands of participants  
- **Statistical testing**: Uses inferential statistics to test hypotheses  
- **Hypothesis-driven**: Tests specific predictions
- **Objective**: Minimizes researcher subjectivity

**Examples:**
- Survey of 500 employees measuring job satisfaction and turnover intentions
- Experiment comparing two training methods using performance test scores
- Analysis of HR database with 10,000 employees to predict turnover

**Advantages:**
- Can establish statistical significance
- Generalizable to larger populations (with proper sampling)
- Allows hypothesis testing
- Replicable and objective

**Disadvantages:**
- May miss nuanced, contextual information
- Reduces complex phenomena to numbers
- Limited understanding of "why" behind relationships

### **1.2 Qualitative Research**

**Definition**: Research that uses non-numerical data (words, observations, documents) to understand phenomena in depth.  

**Characteristics:**
- **Non-numerical data**: Interviews, observations, documents, videos  
- **Small samples**: Typically studies few participants in depth  
- **Narrower focus**: Deep understanding of specific cases  
- **Long-term observation**: Extended engagement with participants  
- **Exploratory**: Generates insights and theories rather than testing them

**Examples:**
- In-depth interviews with 15 CEOs about their leadership philosophy
- Ethnographic observation of team dynamics over 6 months
- Analysis of exit interview transcripts to identify turnover themes

**Advantages:**
- Rich, detailed understanding
- Captures context and complexity
- Explores "why" and "how" questions
- Good for theory development

**Disadvantages:**
- Not generalizable statistically
- Time-consuming and expensive
- Researcher bias in interpretation
- Cannot test statistical significance

### **1.3 Which Approach to Use?**

**Use Quantitative When:**
- You have specific hypotheses to test
- You need to generalize to a population
- You want to measure strength of relationships
- Theory is well-developed

**Use Qualitative When:**
- Exploring new, poorly understood phenomena
- Seeking deep understanding of experiences
- Theory is underdeveloped
- You need contextual richness

**Mixed Methods:**
Many I/O researchers use both:
- Qualitative first (exploratory interviews) → Quantitative second (test patterns in large sample)
- Quantitative first (survey identifies issue) → Qualitative second (interviews explain why)

***

## **PART 2: TYPES OF QUANTITATIVE RESEARCH DESIGNS**

I/O Psychology uses three primary quantitative research designs. They differ critically in:  
- Ability to infer **causation**
- Level of **control**
- **Realism** of setting
- **Feasibility** in organizations

### **2.1 The Hierarchy of Causal Inference**

```
TRUE EXPERIMENT
↓ (can infer causation)
QUASI-EXPERIMENT  
↓ (suggestive, but not definitive)
CORRELATIONAL STUDY
↓ (cannot infer causation)
```

**The Central Question**: Did X **cause** Y, or are they just associated?

Only **true experiments** can answer this definitively.  

***

## **2.2 TRUE EXPERIMENTS**

### **Definition**

A research design where the researcher **manipulates** the independent variable and **randomly assigns** participants to conditions. This is the **only** design that allows causal conclusions.  

### **Three Essential Requirements**

#### **Requirement 1: Randomization**

**What It Means**: Participants are **randomly assigned** to experimental conditions.  

**Why It's Critical**:
- Makes groups equivalent **before** the treatment
- Eliminates selection bias
- Ensures any post-treatment differences are due to the treatment, not pre-existing differences

**Example:**
```
100 managers volunteer for a leadership training study

Random Assignment Process:
1. List all 100 names
2. Use random number generator
3. First 50 random numbers → Experimental Group (receive training)
4. Remaining 50 → Control Group (no training)

Result: Groups are equivalent before training begins
- Similar average age, experience, education
- Similar baseline leadership skills
- Any differences are due to chance, not systematic bias
```

#### **Requirement 2: Manipulation**

**What It Means**: The researcher **actively controls and varies** the independent variable.  

**Key Point**: The researcher creates the conditions, doesn't just observe existing differences.

**Example:**
```
IV: Type of performance feedback
- Condition 1: Specific feedback ("Your report had 3 errors in the data analysis section")
- Condition 2: General feedback ("Good job overall, but needs improvement")

The researcher CREATES these feedback types
(Not just observing what feedback supervisors naturally give)
```

#### **Requirement 3: Control**

**What It Means**: Include a **control group** that receives no treatment or standard treatment.  

**Why It's Necessary**: Provides a baseline comparison to isolate the treatment effect.

**Control Group Options:**
- **No treatment**: Group receives nothing (if ethical)
- **Placebo**: Group receives inactive treatment (controls for attention effects)
- **Standard treatment**: Group receives existing/usual treatment
- **Waitlist control**: Group receives treatment after study ends (ethical compromise)

### **Example: Complete True Experiment**

**Research Question**: Does mindfulness training reduce employee stress?

**Step 1: Identify Participants**
- Recruit 120 employees from various departments
- All report elevated stress (score ≥ 4 on 1-7 stress scale)

**Step 2: Random Assignment**
```
Use random number generator:
- 60 employees → Experimental Group (mindfulness training)
- 60 employees → Control Group (no training)

Check equivalence:
- Experimental: M age = 35.2, M baseline stress = 5.1
- Control: M age = 34.8, M baseline stress = 5.0
Groups are equivalent ✓
```

**Step 3: Manipulation**
```
Experimental Group:
- 8-week mindfulness training program
- 1 hour per week
- Taught by certified instructor
- Homework: daily 10-minute meditation

Control Group:
- No training (waitlist)
- Told they'll receive training after study
```

**Step 4: Measurement**
```
Measure stress at three time points:
- Baseline (before training)
- Post-treatment (immediately after 8 weeks)
- Follow-up (3 months later)

DV: Perceived stress scale (1-7)
```

**Step 5: Analysis**
```
Results (Hypothetical):

Baseline:
- Experimental: M = 5.1
- Control: M = 5.0
- No difference (as expected from randomization)

Post-Treatment:
- Experimental: M = 3.2 (decreased by 1.9 points)
- Control: M = 4.9 (essentially unchanged)
- Significant difference: t(118) = 8.45, p < .001

Follow-Up (3 months later):
- Experimental: M = 3.6 (still improved)
- Control: M = 5.1 (still unchanged)
- Sustained effect ✓
```

**Step 6: Conclusion**
✓ **Can infer causation**: Mindfulness training **caused** stress reduction
✓ Why? Random assignment ruled out alternative explanations:
  - Groups were equivalent before training
  - Only difference was the training
  - Control group shows stress didn't decrease naturally over time

### **Why True Experiments Are Rare in I/O Psychology**

Despite being the gold standard, true experiments face practical barriers in workplace settings:

#### **Ethical Constraints**
- Cannot randomly deny people promotions, raises, or training they deserve
- Cannot randomly assign people to "bad leadership" or "poor working conditions"
- Cannot experimentally manipulate sensitive variables (discrimination, harassment)

#### **Organizational Resistance**
Organizations often resist because:
- "We want to send our **best** employees to training, not random ones"
- Random assignment seems unfair to high performers
- Control groups feel cheated (Hawthorne effect: demoralization)
- Disrupts normal operations

#### **Practical Constraints**
- Expensive and time-consuming
- Requires researcher control that companies rarely grant
- High attrition (people leave company during study)
- Contamination (control group learns about treatment from experimental group)

#### **Artificiality**
- Workplace manipulations may not reflect realistic organizational implementation
- Short-term lab manipulations may not capture long-term workplace dynamics

### **When True Experiments ARE Used**

**Laboratory Studies with Student Participants**
```
Example: Resume screening bias

Setting: University computer lab
Participants: 200 undergraduate students
Task: Rate 20 resumes for job suitability

IV: Applicant name (manipulated to signal race/gender)
- Condition 1: "James Williams" (signals White male)
- Condition 2: "Lakisha Williams" (signals Black female)
- Resume content identical

DV: Hiring recommendation (1-7 scale)

This is feasible in lab, not in real organizations
```

**Field Experiments (When Organizations Cooperate)**
```
Example: Recruitment message effectiveness

Setting: Real job postings from a company
Participants: 10,000 job seekers who view postings

IV: Job posting message (randomly assigned)
- Version A: Emphasizes competitive salary
- Version B: Emphasizes work-life balance
- Version C: Emphasizes career growth

DV: Application rate (% who apply)

Random assignment is feasible here because:
- Applicants don't know about different versions
- No one is being denied an opportunity
- Easy to implement online
```

**A/B Testing in Digital Platforms**
```
Example: LinkedIn premium feature

IV: Price point (randomly shown to users)
- Group 1: $29.99/month
- Group 2: $39.99/month
- Group 3: $49.99/month

DV: Conversion rate (% who subscribe)

Common in tech, rare in traditional I/O research
```

***

## **2.3 QUASI-EXPERIMENTS**

### **Definition**

Research that involves **manipulation** but **lacks randomization**. Participants are not randomly assigned—they come in pre-existing groups or self-select into conditions.  

**Why "Quasi" (meaning "resembling")?**
It looks like an experiment (you manipulate an IV and measure a DV), but without randomization, you cannot definitively rule out alternative explanations.  

### **Key Limitation**

**Cannot infer causation**. Can only say the intervention was "associated with" or "suggestive of" effects, not that it "caused" them.  

**Why?** Without random assignment, groups may differ systematically before treatment. Post-treatment differences might be due to:
- Pre-existing group differences (selection bias)
- Other events happening simultaneously (history effects)
- Natural maturation or change over time
- Regression to the mean

### **Common Quasi-Experimental Designs**

#### **Design 1: Pre-Existing Groups (Non-Equivalent Groups Design)**

**Structure**: Compare two or more groups that naturally exist, without random assignment.  

**Example: Comparing Office Layouts**
```
Research Question: Does open-office layout improve collaboration?

Design:
- Department A (Marketing): Moved to open-office layout (Experimental)
- Department B (Finance): Remains in cubicles (Control)

Measurement:
- DV: Collaboration frequency (measured via survey and observation)
- Measure BEFORE and AFTER the office move

Problem: NOT RANDOM ASSIGNMENT
Departments might differ in ways that affect collaboration:
- Marketing naturally collaborates more than Finance
- Different managers with different leadership styles
- Different types of work (creative vs. analytical)
- Different employee personalities (Marketing attracts extraverts)

Analysis: Compare change in collaboration
- If Department A shows increased collaboration, is it due to:
  a) The open layout? (intended interpretation)
  b) Pre-existing differences? (confound)
  c) New marketing campaign requiring more teamwork? (history effect)
  d) Hawthorne effect (knowing they're being studied)? (reactivity)

Cannot determine definitively!
```

**Strengthening This Design:**
- **Measure groups at baseline**: Document pre-existing differences
- **Statistical controls**: Use ANCOVA to adjust for baseline differences
- **Multiple measurements**: Measure repeatedly before and after
- **Match groups**: Select comparison group similar on key characteristics
- **Acknowledge limitations**: "Findings are suggestive but not definitive"

#### **Design 2: One-Group Pretest-Posttest**

**Structure**: Measure the same group before and after an intervention, with no control group.  

**Example: Evaluating Training**
```
Research Question: Does conflict resolution training reduce workplace disputes?

Design:
- Measure all employees' conflict management skills (Pretest)
- Provide 2-day conflict resolution training to all employees
- Measure conflict management skills again 1 month later (Posttest)

Results (Hypothetical):
- Pretest: M = 3.2 (out of 5)
- Posttest: M = 4.1
- Improvement = 0.9 points

Problem: NO CONTROL GROUP
If skills improved, is it due to training?
Or due to:
- Practice effect (employees got better at taking the test)
- History (company implemented new conflict policy unrelated to training)
- Maturation (employees naturally developed skills over time)
- Regression to the mean (skills were unusually low at pretest)
- Hawthorne effect (attention from researcher improved behavior)

Cannot isolate training effect!
```

**Strengthening This Design:**
- **Add control group**: Find similar organization without training
- **Multiple pretests**: Establish stable baseline before intervention
- **Multiple posttests**: Track change over time
- **Remove other interventions**: Ensure nothing else changed during study period

#### **Design 3: Time Series Design**

**Structure**: Multiple measurements before and after intervention.  

**Example: Policy Change Impact**
```
Research Question: Did new flexible work policy improve job satisfaction?

Design:
Measure job satisfaction quarterly for 2 years:

Quarterly Measurements:
Q1: 3.2
Q2: 3.3
Q3: 3.1
Q4: 3.2 ← Stable baseline
--- POLICY IMPLEMENTED ---
Q5: 3.8 ← Jump after policy
Q6: 4.0
Q7: 3.9
Q8: 4.1 ← Sustained improvement

Interpretation:
- Clear baseline pattern (stable around 3.2)
- Immediate jump after policy (to 3.8)
- Sustained elevation (remains around 4.0)
- Pattern suggests policy had effect

Stronger than single pretest-posttest because:
✓ Shows stability before intervention
✓ Shows immediate change after intervention
✓ Shows sustained change (not temporary)
```

**Limitation**: Still no control group
- Could be coincidental timing (economy improved, new CEO, industry trend)
- But pattern is more convincing than one-shot design

#### **Design 4: Non-Equivalent Control Group Design**

**Structure**: Compare treatment and control groups, with pretest and posttest, but no random assignment.  

**Example: Wellness Program**
```
Research Question: Does wellness program reduce absenteeism?

Design:
- Site A (treatment): Implements wellness program
- Site B (control): No wellness program

Measure absenteeism before and after:

Site A (Treatment):
- Baseline: 5.2 days absent per year
- Post-program: 3.1 days absent per year
- Change: -2.1 days

Site B (Control):
- Baseline: 4.8 days absent per year
- One year later: 4.5 days absent per year
- Change: -0.3 days

Analysis:
Treatment group improved MORE than control group
Difference-in-differences: (-2.1) - (-0.3) = -1.8 days

Interpretation:
✓ Treatment group's improvement exceeds control group
✓ Control group shows absenteeism didn't decrease naturally
✓ Suggestive that program had effect

Limitation: Sites weren't randomly assigned
- Site A might have healthier employees to begin with
- Site A might have better management (reason they adopted program)
- Site differences might explain results
```

**Strengthening This Design:**
- **Match sites carefully**: Select control site similar in size, industry, demographics
- **Measure multiple times**: Establish parallel trends before intervention
- **Statistical adjustment**: Control for site differences in analysis

### **Conclusions from Quasi-Experiments**

**What You CAN Say**:  
- "The intervention was **associated with** improvements"
- "Results are **suggestive of** a causal relationship"
- "Findings are **consistent with** the hypothesis that X affects Y"

**What You CANNOT Say**:  
- "The intervention **caused** improvements"
- "X leads to Y"
- "We can conclude definitively that..."

**When Quasi-Experiments Are Acceptable:**
- True experiments are impossible or unethical
- Exploratory research in new areas
- Studying naturally occurring interventions (policy changes, organizational restructuring)
- Complementing experimental research (external validity check)

***

## **2.4 CORRELATIONAL STUDIES**

### **Definition**

Research that observes how variables are **naturally related** in a single group, without manipulation, grouping, or control. The researcher is a **passive observer**.  

### **Characteristics**

- **No manipulation**: Researcher doesn't change anything  
- **No random assignment**: Everyone is in one group  
- **Observational**: Measures variables as they naturally exist
- **Association-focused**: Examines relationships, not causes

### **What You Can Learn**

✓ Whether two variables are associated  
✓ Direction of relationship (positive or negative)  
✓ Strength of relationship (weak, moderate, strong)  
✓ Prediction (X predicts Y)

### **What You CANNOT Learn**

✗ Whether one variable **causes** the other  
✗ Direction of causation (does X cause Y, or Y cause X?)
✗ Whether a third variable causes both

### **Example: Job Satisfaction and Performance**

**Research Question**: Is job satisfaction related to job performance?

**Design:**
- Survey 500 employees (single group)
- **Variable 1 (IV)**: Job satisfaction (measured on 1-5 scale via survey)
- **Variable 2 (DV)**: Job performance (supervisor ratings on 1-5 scale)
- Calculate correlation: r = 0.35, p < .001

**Findings:**

**What You CAN Conclude**:  
✓ "Job satisfaction and performance are positively correlated"
✓ "Employees with higher satisfaction tend to have higher performance"
✓ "Satisfaction explains 12% of variance in performance" (r² = .35² = .12)
✓ "Satisfaction is a significant predictor of performance"

**What You CANNOT Conclude**:  
✗ "Job satisfaction **causes** better performance"
✗ "Improving satisfaction will improve performance"
✗ "Satisfaction leads to performance"

### **Why You Cannot Infer Causation: The Three Interpretations Problem**

When X and Y are correlated, there are always at least three possible explanations:

**Explanation 1: X → Y (X causes Y)**
```
Job Satisfaction → Job Performance
Mechanism: Happy employees work harder and better
```

**Explanation 2: Y → X (Y causes X - Reverse Causation)**
```
Job Performance → Job Satisfaction
Mechanism: High performers feel competent and receive praise, making them satisfied
```

**Explanation 3: Z → X and Z → Y (Third Variable)**
```
Conscientiousness → Job Satisfaction
                  → Job Performance

Mechanism: Conscientious people both:
- Work hard (high performance)
- Take responsibility and pride in work (high satisfaction)

Correlation between satisfaction and performance is SPURIOUS
(Both caused by conscientiousness)
```

**Correlational studies cannot distinguish these explanations!**  

### **Classic Example: The Third Variable Problem**

**Observation**: Ice cream sales and drowning deaths are strongly correlated (r = 0.85)

**Three Interpretations:**
```
1. Ice Cream → Drowning
   Interpretation: Eating ice cream causes drowning?
   Plausibility: Absurd

2. Drowning → Ice Cream
   Interpretation: Drowning makes people buy ice cream?
   Plausibility: Absurd

3. Temperature → Ice Cream
                → Drowning
   Interpretation: 
   - Hot weather → People buy more ice cream
   - Hot weather → More people swim → More drownings
   
   Plausibility: Makes sense! ✓
```

The correlation is **real**, but it's not **causal**. Both variables are influenced by a third variable (temperature).

### **I/O Psychology Example: Training and Performance**

**Observation**: Employees who receive more training have higher performance (r = 0.42)

**Interpretation 1: Training → Performance**
```
Training causes performance improvement
Mechanism: Training develops skills, skills improve performance
Implication: Provide more training to boost performance
```

**Interpretation 2: Performance → Training (Reverse Causation)**
```
High performers get selected for training
Mechanism: Managers nominate best employees for development opportunities
Reality: Training doesn't cause performance; performance causes training selection
Implication: Training relationship is spurious
```

**Interpretation 3: Third Variable (Conscientiousness)**
```
Conscientiousness → Seeks training opportunities
                  → Works hard and performs well

Mechanism: Conscientious employees both:
- Volunteer for training (development-oriented)
- Perform well naturally (hardworking)

Reality: Conscientiousness causes both training participation and performance
Implication: Training effect may be overestimated
```

**Correlational study cannot distinguish these!**

### **Why Correlational Studies Are Most Common in I/O Psychology**

Despite causal ambiguity, correlational designs dominate I/O research:  

**Advantages:**

**1. Realistic**  
- Studies actual workplace behavior in natural settings
- High external validity (generalizable to real work contexts)
- Captures complexity of organizational life

**2. Ethical**
- No need to deny people opportunities (training, promotions, fair treatment)
- No manipulation of sensitive variables
- Studies things that can't be manipulated ethically

**3. Practical**
- Can use archival data (HR databases, performance records)
- No need for expensive experimental apparatus
- Organizations more willing to allow non-intrusive observation

**4. Large Samples**
- Can survey thousands of employees across many organizations
- High statistical power
- Can examine rare phenomena (turnover, promotion to executive)

**Disadvantages:**

**1. Causal Ambiguity**  
- Cannot determine cause-effect
- Cannot rule out third variables
- Cannot determine direction of causation

**2. Common Method Bias**
- If IV and DV both from same source (e.g., self-report survey), correlations inflated
- Shared method variance creates spurious relationships

**3. Temporal Ambiguity**
- If both variables measured at same time, cannot determine which came first
- Cross-sectional correlational studies especially problematic

### **Strengthening Correlational Research**

**Strategy 1: Establish Temporal Precedence**
```
Instead of: Measure satisfaction and turnover at same time

Better: 
- Time 1: Measure job satisfaction
- Time 2 (6 months later): Measure turnover
- Now satisfaction temporally precedes turnover
- Strengthens (but doesn't prove) causal inference
```

**Strategy 2: Longitudinal Designs**
```
Measure variables at multiple time points:

Time 1: Satisfaction, Performance
Time 2: Satisfaction, Performance  
Time 3: Satisfaction, Performance

Analyze cross-lagged effects:
- Does Time 1 Satisfaction predict Time 2 Performance?
- Does Time 1 Performance predict Time 2 Satisfaction?

Can partially disentangle causal direction
```

**Strategy 3: Statistical Controls**
```
Use multiple regression to control for confounds:

Example:
DV: Job Performance
IV: Job Satisfaction
Controls: Conscientiousness, Cognitive Ability, Tenure

If satisfaction predicts performance AFTER controlling for these,
the relationship is more likely genuine (not spurious)
```

**Strategy 4: Theory-Driven Research**
```
Ground predictions in theory that specifies causal mechanisms

Example:
"Based on Social Exchange Theory, perceived organizational support
should increase satisfaction through reciprocity norms."

Theory provides rationale for causal direction
Makes research more interpretable
```

**Strategy 5: Replicate Across Samples**
```
If satisfaction-performance correlation appears in:
- Multiple organizations
- Multiple industries
- Multiple countries
- Multiple time periods

The relationship is more robust and likely generalizable
```

### **Common Correlational Techniques**

**Bivariate Correlation (r)**
- Relationship between two continuous variables
- Example: Satisfaction (1-5) and performance (1-5)

**Multiple Regression**
- Predict DV from multiple IVs simultaneously
- Control for confounding variables
- Identify unique contribution of each predictor

**Structural Equation Modeling (SEM)**
- Test complex models with multiple variables
- Examine direct and indirect (mediated) effects
- Assess model fit to data

**Logistic Regression**
- When DV is categorical (turnover: yes/no; promoted: yes/no)
- Predicts probability of outcome

***

## **PART 3: RESEARCH SETTINGS**

Where you conduct research affects both **internal validity** (confidence in causal conclusions) and **external validity** (generalizability to real workplaces).  

### **The Control-Realism Tradeoff**

```
HIGH CONTROL ←──────────────────────→ HIGH REALISM
(Laboratory)                          (Field)

HIGH Internal Validity                HIGH External Validity
LOW External Validity                 LOW Internal Validity
```

### **3.1 Laboratory Studies**

**Definition**: Research conducted in controlled, artificial settings (university labs, simulated work environments).  

**Characteristics:**

**High Control**:  
- Researcher manipulates all variables precisely
- Eliminates distractions and extraneous influences
- Standardizes conditions across participants
- Can use specialized equipment (eye-tracking, physiological measures)

**Standardization**:
- All participants experience identical procedures
- Ensures comparability
- Increases reliability

**Precision**:
- Accurate measurement of variables
- Can study micro-level processes (millisecond reaction times, subtle behavioral cues)

**Advantages:**

✓ **Establish causation**: High control allows true experiments  
✓ **Test specific hypotheses**: Isolate variables of interest
✓ **Study rare/unethical phenomena**: Simulate situations that don't naturally occur
✓ **Cost-effective**: Use student participants (convenient, inexpensive)
✓ **Replicable**: Standardized procedures allow exact replication

**Disadvantages:**

✗ **Artificiality**: Simulated tasks don't reflect real job complexity  
✗ **Participant differences**: Students ≠ employees  
  - Different motivation (course credit vs. livelihood)
  - Different experience (no work history)
  - Different stakes (no real consequences)
✗ **Limited generalizability**: Lab findings may not translate to actual workplaces  
✗ **Demand characteristics**: Participants guess study purpose and alter behavior
✗ **Short duration**: Most lab studies last < 2 hours; work relationships develop over years

**Example: Leadership and Performance**

```
LABORATORY STUDY

Setting: University computer lab
Participants: 120 undergraduate psychology students
Duration: 90 minutes
Incentive: Course research credit

Design:
- Form groups of 4 students
- Assign one student as "leader" (randomly)
- IV: Leader receives either transformational or transactional leadership script
- Task: Solve 10 business case problems as a group
- DV: Number of correct solutions, time to completion

Strengths:
✓ High control (all groups see identical materials, same time limit)
✓ Can randomly assign leadership style (true experiment)
✓ Standardized measurement (objective task performance)
✓ Can establish causation

Weaknesses:
✗ 90 minutes ≠ years of working under a leader
✗ Students ≠ experienced employees
✗ Business case puzzles ≠ real job tasks
✗ No real stakes (course credit vs. livelihood, promotion, career)
✗ Artificial leader-follower relationship (no history, no future)
```

### **3.2 Field Studies**

**Definition**: Research conducted in actual workplaces with real employees doing their actual jobs.  

**Characteristics:**

**Realistic Setting**:  
- Natural work environment
- Real organizational context
- Authentic work tasks

**Natural Behavior**:
- Employees perform their regular jobs
- Genuine relationships and dynamics
- Realistic time scales (months, years)

**Meaningful Outcomes**:
- Real performance (not simulated)
- Actual turnover, promotion, salary
- Genuine satisfaction and stress

**Advantages:**

✓ **High external validity**: Findings generalize to similar workplaces  
✓ **Ecological validity**: Captures complexity and nuance of real work
✓ **Participant engagement**: Employees care about outcomes (real stakes)
✓ **Long-term observation**: Study phenomena that unfold over time
✓ **Practical relevance**: Organizations value findings they can apply

**Disadvantages:**

✗ **Low control**: Cannot control extraneous variables  
  - Different managers, departments, work conditions
  - Organizational changes during study (restructuring, policy changes)
  - External events (economic changes, industry trends)
✗ **Ethical constraints**: Cannot randomly assign to important outcomes
✗ **Access difficulties**: Companies hesitant to allow research (proprietary concerns, disruption)
✗ **Expensive and time-consuming**: Travel, coordination, lengthy data collection
✗ **High attrition**: Employees leave company, get transferred, promoted
✗ **Confounding**: Many variables correlated (can't isolate cause)

**Example: Leadership and Performance**

```
FIELD STUDY

Setting: Manufacturing company (5 plants, 2,000 employees)
Participants: 50 supervisors and their 500 subordinates
Duration: 12 months
Incentive: None (part of organizational assessment)

Design:
- Measure supervisor leadership style (subordinate ratings on validated survey)
- IV: Leadership style (transformational vs. transactional)
  Note: Naturally occurring, not manipulated
- DV: Subordinate performance (objective productivity metrics: units produced, error rate, safety)
- Measure quarterly for 1 year

Strengths:
✓ Real supervisors with years of experience
✓ Real subordinates doing actual jobs
✓ Objective performance data (not simulated tasks)
✓ Long-term observation (1 year)
✓ Realistic organizational context

Weaknesses:
✗ Cannot randomly assign leadership style (correlational, not causal)
✗ Many confounds:
  - Different plants have different equipment, culture
  - Different supervisors have different experience, personality
  - Different work groups have different composition
✗ Cannot isolate leadership effect from other factors
✗ Difficult to replicate (unique company context)
✗ Required extensive company cooperation (time, access, trust)
```

### **3.3 Archival Data Research**

**Definition**: Research using **existing data** that organizations have already collected for operational purposes.  

**Types of Archival Data:**
- HR databases (hiring, performance, salary, promotion, turnover)
- Personnel files (applications, resumes, interview notes)
- Performance appraisals (ratings, reviews)
- Surveys (engagement, satisfaction, climate)
- Organizational records (productivity, sales, absenteeism)
- Public data (financial reports, demographic statistics)

**Characteristics:**

**No New Data Collection**:  
- Data already exists in company records
- Researcher accesses and analyzes existing information

**Large Samples**:
- Access to entire employee populations
- Years of historical data
- Thousands of employees

**Objective Measures**:
- Actual turnover (not intentions)
- Real performance (not self-report)
- True salary (not estimates)

**Advantages:**

✓ **Low cost**: Data already collected, no survey/experiment expenses  
✓ **Large samples**: Entire populations, high statistical power  
✓ **Longitudinal**: Track employees over years  
✓ **Objective measures**: Behavioral outcomes, not just attitudes  
✓ **Unobtrusive**: No Hawthorne effect (data collected before research question)
✓ **Rare events**: Can study infrequent outcomes (executive promotion, termination)
✓ **Historical perspective**: Examine trends over time

**Disadvantages:**

✗ **Limited variables**: Can only study what was already measured  
  - No job satisfaction data if it wasn't surveyed
  - No leadership quality if it wasn't assessed
✗ **Missing data**: Incomplete records, inconsistent measurement across years  
✗ **Measurement quality**: Data not collected with research rigor  
  - Performance ratings may be biased
  - Inconsistent definitions across departments
  - Changes in measurement systems over time
✗ **Correlational**: Archival data is almost always correlational (no manipulation)  
✗ **Data access barriers**: Privacy concerns, proprietary information, legal restrictions
✗ **Unknown validity**: Don't know reliability/validity of measures

**Example: Predictors of Voluntary Turnover**

```
ARCHIVAL DATA STUDY

Data Source: Fortune 500 company HR database
Time Period: 10 years (2015-2024)
Sample: 15,000 employees

Variables Available:
- Demographics: Age, gender, race, education
- Job info: Department, level, title, tenure, location
- Compensation: Base salary, bonuses, raises, promotions
- Performance: Annual ratings (1-5 scale)
- Turnover: Voluntary/involuntary, exit date, destination (competitor, different industry, retirement)

Research Question: What predicts voluntary turnover?

Analysis:
- Logistic regression: Predict turnover (yes/no) from available variables
- Survival analysis: Time until turnover
- Compare voluntary vs. involuntary turnover

Strengths:
✓ Huge sample (high power to detect effects)
✓ 10-year longitudinal data
✓ Objective turnover data (actual departures, not intentions)
✓ Objective performance data (ratings, not self-report)
✓ No data collection costs
✓ Can examine rare events (executive turnover)

Weaknesses:
✗ Cannot measure job satisfaction (not in database)
✗ Cannot measure leadership quality (not systematically assessed)
✗ Cannot measure work-life balance, stress, engagement
✗ Missing data for employees hired before database implementation
✗ Performance ratings may be biased (leniency, halo effect)
✗ Correlational design (cannot infer causation)
✗ Don't know why people left (exit interviews not systematically recorded)
```

### **Choosing a Research Setting**

**Use Laboratory When:**
- Testing specific causal hypotheses that require control
- Studying micro-level processes (perception, cognition, decision-making)
- Manipulating variables that are unethical/impossible to manipulate in field
- Need for precise measurement and replication

**Use Field When:**
- Studying complex organizational phenomena (culture, change)
- Need external validity and generalizability
- Long-term processes (socialization, leadership development)
- Outcomes that require real stakes (actual turnover, performance)

**Use Archival When:**
- Need large samples or rare events
- Studying historical trends or patterns
- Variables of interest are recorded in organizational data
- Limited budget or time
- Unobtrusive observation is important

**Mixed Methods:**
Many researchers combine settings:
- Lab study (establish causation) + Field study (test external validity)
- Field study (identify patterns) + Lab study (test mechanisms)
- Archival study (large-scale patterns) + Interviews (understand why)


# **PART 4: UNDERSTANDING STATISTICS**

***

## **INTRODUCTION: WHY STATISTICS MATTER IN I/O PSYCHOLOGY**

Statistics are the **language** of empirical research. Every claim you make about workplace behavior must be supported by statistical evidence. Without statistics, we cannot:  
- Summarize data in meaningful ways
- Determine if patterns are real or due to chance
- Compare groups objectively
- Make predictions
- Draw conclusions from research

I/O psychologists use two broad categories of statistics:  

1. **Descriptive Statistics**: Summarize and describe data
2. **Inferential Statistics**: Make inferences about populations from samples

***

## **SECTION 1: DESCRIPTIVE STATISTICS**

### **1.1 Purpose of Descriptive Statistics**

**Definition**: Statistical techniques that summarize and describe the basic features of a dataset.  

**Goal**: Reduce large amounts of data into understandable, interpretable summaries

**Two Types of Descriptive Statistics:**
1. **Central Tendency**: Where is the "center" or "typical score"?
2. **Variability**: How spread out are the scores?

***

### **1.2 Measures of Central Tendency**

These statistics describe the "typical" or "average" score in a dataset.  

#### **1.2.1 Mean (M): The Arithmetic Average**

**Definition**: The sum of all scores divided by the number of scores.  

**Formula**:
\[ M = \frac{\sum X}{N} \]

Where:
- \(M\) = Mean
- \(\sum X\) = Sum of all scores (Σ means "sum")
- \(N\) = Number of scores

**Example: Job Satisfaction Scores**

```
10 employees rate job satisfaction (1-5 scale):
Employee 1: 5
Employee 2: 4
Employee 3: 3
Employee 4: 5
Employee 5: 4
Employee 6: 3
Employee 7: 2
Employee 8: 5
Employee 9: 4
Employee 10: 3

Step 1: Sum all scores
∑X = 5 + 4 + 3 + 5 + 4 + 3 + 2 + 5 + 4 + 3 = 38

Step 2: Divide by number of scores
M = 38 / 10 = 3.8

Interpretation: Average job satisfaction is 3.8 out of 5
```

**Advantages:**
✓ Uses all data points (every score contributes)
✓ Most commonly used measure
✓ Required for many advanced statistics
✓ Mathematically useful (algebraic properties)

**Disadvantages:**
✗ Sensitive to extreme scores (outliers)
✗ Can be misleading with skewed distributions

**When Mean Is Misleading: The Outlier Problem**

```
Employee salaries at a small startup (10 employees):

Employee 1: $45,000
Employee 2: $48,000
Employee 3: $50,000
Employee 4: $52,000
Employee 5: $50,000
Employee 6: $47,000
Employee 7: $49,000
Employee 8: $51,000
Employee 9: $48,000
Employee 10: $900,000 (CEO)

Sum = $1,340,000
Mean = $1,340,000 / 10 = $134,000

Problem: Mean suggests "average" employee earns $134K
Reality: 9 out of 10 employees earn around $50K
The CEO's extreme salary distorts the mean

The mean is technically correct but highly misleading!
```

#### **1.2.2 Median: The Middle Score**

**Definition**: The score that divides the distribution in half—50% of scores are above it, 50% below.  

**How to Calculate:**

**Step 1**: Arrange scores in order from lowest to highest

**Step 2**: Find the middle position
- If **odd** number of scores: Median is the middle score
- If **even** number of scores: Median is the average of the two middle scores

**Formula for Position**:
\[ \text{Position} = \frac{N + 1}{2} \]

**Example 1: Odd Number of Scores**

```
Job satisfaction for 9 employees:
Unordered: 3, 5, 2, 4, 3, 5, 4, 3, 4

Step 1: Order from low to high
2, 3, 3, 3, 4, 4, 4, 5, 5

Step 2: Find middle position
Position = (9 + 1) / 2 = 5th position

Step 3: Identify middle score
2, 3, 3, 3, [4], 4, 4, 5, 5
              ↑
           5th position

Median = 4
```

**Example 2: Even Number of Scores (Same Salary Data)**

```
Ordered salaries:
$45,000  (1)
$47,000  (2)
$48,000  (3)
$48,000  (4)
$49,000  (5) ← Lower middle
$50,000  (6) ← Upper middle
$50,000  (7)
$51,000  (8)
$52,000  (9)
$900,000 (10)

Positions: (10 + 1) / 2 = 5.5
Take average of 5th and 6th scores

Median = ($49,000 + $50,000) / 2 = $49,500

Interpretation: Half of employees earn more than $49,500, half earn less

Compare:
Mean = $134,000 (distorted by CEO)
Median = $49,500 (representative of typical employee)

The median is MUCH more accurate here!
```

**Advantages:**
✓ Not affected by outliers
✓ Better for skewed distributions
✓ Easy to interpret (50th percentile)
✓ Good for ordinal data

**Disadvantages:**
✗ Doesn't use all data (ignores specific values, only uses positions)
✗ Can't be used in many advanced statistics
✗ Less mathematically useful than mean

**When to Use Median:**
- Data has outliers
- Distribution is skewed (not symmetric)
- Ordinal data (rankings, Likert scales where intervals may not be equal)
- Income, salary, housing prices (typically right-skewed)

#### **1.2.3 Mode: The Most Frequent Score**

**Definition**: The score that occurs most often in the dataset.  

**How to Calculate**: Count frequency of each score; identify the most common

**Example: Performance Ratings**

```
Performance ratings for 15 employees (1-5 scale):
5, 4, 3, 3, 4, 4, 4, 5, 3, 2, 4, 3, 4, 5, 4

Step 1: Count frequency of each rating
Rating 1: 0 employees
Rating 2: 1 employee   (▪)
Rating 3: 4 employees  (▪▪▪▪)
Rating 4: 7 employees  (▪▪▪▪▪▪▪) ← Most frequent
Rating 5: 3 employees  (▪▪▪)

Mode = 4

Interpretation: Most employees received a rating of 4
```

**Types of Distributions:**

**Unimodal**: One mode
```
Frequency
    │     ●
    │    ●●●
    │   ●●●●●
    │  ●●●●●●●
    └──────────── Score
    Single peak at one value
```

**Bimodal**: Two modes
```
Frequency
    │   ●       ●
    │  ●●●     ●●●
    │ ●●●●●   ●●●●●
    └──────────────── Score
    Two distinct peaks
    
Example: Employee satisfaction
- Mode 1 at 2 (dissatisfied group)
- Mode 2 at 5 (satisfied group)
- Suggests two distinct subgroups
```

**Multimodal**: More than two modes
```
Frequency
    │  ●    ●    ●
    │ ●●●  ●●●  ●●●
    └──────────────── Score
    Multiple peaks
```

**Advantages:**
✓ Only measure that works for categorical/nominal data
✓ Can identify most typical category
✓ Useful for identifying subgroups (bimodal distributions)
✓ Easy to understand

**Disadvantages:**
✗ Ignores most of the data (only tells you most frequent)
✗ May not exist (all scores occur once)
✗ May not be unique (multiple modes)
✗ Rarely used in advanced statistics

**When to Use Mode:**
- **Categorical data**: Most common job title, most frequent turnover reason, most popular leadership style
- **Identifying typical case**: "What rating do most employees receive?"
- **Detecting subgroups**: Bimodal distributions suggest distinct groups

**Example: Categorical Data**

```
Turnover reasons for 50 employees who quit:

Better pay:           18 employees ← MODE
Career growth:        14 employees
Poor manager:         9 employees
Work-life balance:    5 employees
Relocation:           4 employees

Mode = "Better pay"
Interpretation: Most common reason for turnover is better pay elsewhere
```

#### **1.2.4 Comparing Mean, Median, and Mode**

**Symmetric Distribution (Normal):**
```
All three are equal

    Frequency
        │      ●
        │     ●●●
        │    ●●●●●
        │   ●●●●●●●
        └────────────
           Mode
          Median
           Mean
        (all at center)
```

**Right-Skewed Distribution (Positive Skew):**
```
Mean > Median > Mode

    Frequency
        │●
        │●●
        │●●●
        │●●●●
        │●●●●●
        └────────●●●●──→
         Mode
           Median
               Mean (pulled right by outliers)

Example: Salaries (few very high earners pull mean up)
```

**Left-Skewed Distribution (Negative Skew):**
```
Mean < Median < Mode

    Frequency
        │        ●
        │       ●●
        │      ●●●
        │     ●●●●
        │    ●●●●●
     ←──●●●●──────────
         Mean (pulled left)
            Median
               Mode

Example: Age at retirement (most retire at 65, few retire very early)
```

***

### **1.3 Measures of Variability**

Central tendency tells you the "average," but variability tells you how **spread out** scores are.  

**Why Variability Matters:**

```
Company A - Job Satisfaction:
4, 4, 4, 4, 4, 4, 4
Mean = 4.0
All employees have identical satisfaction

Company B - Job Satisfaction:
1, 2, 3, 4, 5, 6, 7
Mean = 4.0
Huge spread in satisfaction

Both companies have the SAME mean, but VERY different employee experiences!
Variability reveals this critical difference.
```

#### **1.3.1 Range: Simplest Measure**

**Definition**: The difference between the highest and lowest scores

**Formula**:
\[ \text{Range} = \text{Maximum} - \text{Minimum} \]

**Example:**
```
Performance scores: 2, 3, 3, 4, 4, 4, 5, 5, 6

Maximum = 6
Minimum = 2
Range = 6 - 2 = 4
```

**Advantages:**
✓ Very easy to calculate
✓ Easy to interpret
✓ Quick sense of spread

**Disadvantages:**
✗ Uses only two data points (ignores everything in between)
✗ Extremely sensitive to outliers
✗ Doesn't tell you about distribution of middle scores

**Rarely used in formal research** (too limited)

#### **1.3.2 Standard Deviation (SD): The Most Important Measure**

**Definition**: The average distance of scores from the mean.  

**Conceptual Idea**: "On average, how far away are scores from the mean?"

**Formula (for sample)**:
\[ SD = \sqrt{\frac{\sum (X - M)^2}{N}} \]

Or with more precise notation for a sample:
\[ s = \sqrt{\frac{\sum (X - \bar{X})^2}{n-1}} \]

Where:
- \(SD\) or \(s\) = Sample standard deviation
- \(X\) = Individual score
- \(M\) or \(\bar{X}\) = Mean
- \(N\) or \(n\) = Number of scores
- \((X - M)\) = Deviation score (distance from mean)

**Step-by-Step Calculation:**

**Example: Job Satisfaction for 5 Employees**

```
Scores: 2, 3, 4, 5, 6

Step 1: Calculate the mean
M = (2 + 3 + 4 + 5 + 6) / 5 = 20 / 5 = 4.0

Step 2: Calculate deviation scores (X - M)
Employee 1: 2 - 4 = -2
Employee 2: 3 - 4 = -1
Employee 3: 4 - 4 = 0
Employee 4: 5 - 4 = +1
Employee 5: 6 - 4 = +2

Step 3: Square the deviation scores (X - M)²
(-2)² = 4
(-1)² = 1
(0)² = 0
(+1)² = 1
(+2)² = 4

Step 4: Sum the squared deviations
∑(X - M)² = 4 + 1 + 0 + 1 + 4 = 10

Step 5: Divide by N
10 / 5 = 2.0
(This is called the variance)

Step 6: Take the square root
SD = √2.0 = 1.41

Interpretation: On average, scores deviate 1.41 points from the mean of 4.0
```

**Why We Square Deviations:**

```
If we didn't square:
-2 + -1 + 0 + 1 + 2 = 0

Sum of deviations ALWAYS equals zero!
(Negative and positive deviations cancel out)

By squaring:
- All values become positive
- Larger deviations count more (squared values are bigger)
- Allows meaningful average
```

**Why We Take Square Root:**

```
After squaring and averaging, units are squared (e.g., "squared satisfaction points")

Taking square root returns to original units:
√(squared units) = original units

Now SD is in same units as original scores (interpretable)
```

**Interpreting Standard Deviation:**

**Small SD** = Scores clustered tightly around mean (low variability)
```
Scores: 4, 4, 4, 4, 4
M = 4.0
SD = 0.0
│
│    ●●●●●
│
└──────────
    4
(No variability at all)
```

**Large SD** = Scores spread widely (high variability)
```
Scores: 1, 2, 3, 4, 5, 6, 7
M = 4.0
SD = 2.0
│
│●  ●  ●  ●  ●  ●  ●
└──────────────────────
1  2  3  4  5  6  7
(High variability)
```

**Example: Comparing Two Companies**

```
Company A:
Job satisfaction scores: 3.8, 3.9, 4.0, 4.1, 4.2
M = 4.0
SD = 0.16 (very small)

Interpretation: Employees have very consistent satisfaction
All employees feel similarly about their jobs
Homogeneous workforce experience

Company B:
Job satisfaction scores: 1.5, 2.0, 4.0, 6.0, 6.5
M = 4.0 (same mean!)
SD = 2.28 (very large)

Interpretation: Employees have wildly different satisfaction
Some are very dissatisfied (1.5), some very satisfied (6.5)
Suggests potential fairness issues or subgroup differences
```

**The Empirical Rule (For Normal Distributions):**

When data is normally distributed:
- **68%** of scores fall within **1 SD** of the mean
- **95%** of scores fall within **2 SD** of the mean
- **99.7%** of scores fall within **3 SD** of the mean

```
        34%│34%
           │
    14%    │    14%
  ───────┬─┴─┬───────
  2%  │     │     │ 2%
─────┬─────┬─────┬─────
    -2SD  -1SD  M  +1SD  +2SD

Example: Job Performance
M = 3.5, SD = 0.5

68% of employees score between 3.0 and 4.0
95% of employees score between 2.5 and 4.5
99.7% of employees score between 2.0 and 5.0

Employees scoring > 4.5 are in top 2.5% (exceptional performers)
Employees scoring < 2.5 are in bottom 2.5% (poor performers)
```

**Why Standard Deviation Matters:**

**1. Detecting Unusual Scores**
```
If M = 75, SD = 5 on a test:
- Score of 85 = 2 SD above mean (top 2.5%, unusual)
- Score of 76 = 0.2 SD above mean (average, typical)
```

**2. Comparing Across Different Scales**
```
Job satisfaction: M = 3.5, SD = 1.0 (1-5 scale)
You score 4.5 → You are 1 SD above mean

Organizational commitment: M = 50, SD = 10 (1-100 scale)
You score 60 → You are 1 SD above mean

Both are equally "high" relative to their distributions
```

**3. Identifying Measurement Problems**
```
If you design a 10-item satisfaction survey (1-5 scale):
Possible range: 10 to 50

If your sample has:
M = 30, SD = 2 (very small SD)

Problem: Scale isn't differentiating between people
Everyone scores nearly identically
Need to revise survey items to increase variability
```

**4. Understanding Group Differences**
```
Training Group: M = 85, SD = 10
Control Group: M = 75, SD = 10

Mean difference = 10 points
Difference = 1.0 SD (large, meaningful effect)

vs.

Training Group: M = 78, SD = 15
Control Group: M = 75, SD = 15

Mean difference = 3 points
Difference = 0.2 SD (small, trivial effect)

Same 3-point difference can be large or small depending on SD!
```

***

## **SECTION 2: INFERENTIAL STATISTICS**

### **2.1 The Purpose of Inferential Statistics**

**The Central Problem:**

We almost never have data on the entire population. Instead:
- We study a **sample** (e.g., 500 employees)
- We want to make conclusions about the **population** (e.g., all employees in the industry)

**Key Question**: Is the pattern we observed in our sample **real** (exists in the population), or just **random chance** (sampling error)?  

**Example:**
```
We survey 500 employees:
- Group A (flexible work): M satisfaction = 4.2
- Group B (no flexible work): M satisfaction = 3.8
- Difference = 0.4 points

Is this difference REAL (flexible work improves satisfaction)?
Or could it be RANDOM (we happened to sample slightly happier people in Group A)?

Inferential statistics answer this question.
```

### **2.2 Statistical Significance and p-values**

**Definition**: Statistical significance indicates that the observed result is unlikely to have occurred by chance alone.  

**The p-value**:
**Definition**: The probability of obtaining results as extreme as (or more extreme than) what you observed, **assuming there is no true effect in the population**.  

**Formula** (conceptual):
\[ p = P(\text{data} | H_0) \]

Where:
- \(p\) = p-value
- \(H_0\) = Null hypothesis (assumption of no effect)

**Interpretation:**

**p < .05**:  
- **Statistically significant**
- Less than 5% chance results are due to random chance
- We **reject the null hypothesis** (conclude there IS an effect)
- Convention: This is the standard threshold in I/O Psychology

**p < .01**:  
- **Highly significant**
- Less than 1% chance results are random

**p < .001**:  
- **Very highly significant**
- Less than 0.1% chance results are random

**p ≥ .05**:  
- **Not statistically significant**
- Results could easily be due to chance
- We **fail to reject the null hypothesis** (cannot conclude there's an effect)
- Does NOT prove there's no effect (just insufficient evidence)

**Example: Leadership Training**

```
Research Question: Does leadership training improve employee performance?

Design:
- Control group (no training): M = 3.2, SD = 0.8, n = 50
- Experimental group (training): M = 3.9, SD = 0.7, n = 50
- Difference = 0.7 points

Statistical test: Independent samples t-test
Result: t(98) = 4.82, p = .003

Interpretation:
✓ The difference IS statistically significant (p = .003 < .05)
✓ If there were NO real effect of training, we would only see
  a difference this large (or larger) by chance 0.3% of the time
✓ Conclusion: Training likely has a real effect on performance
```

**What if p = .18?**
```
Result: t(98) = 1.35, p = .18

Interpretation:
✗ The difference is NOT statistically significant (p = .18 > .05)
✗ We could easily see this difference by chance 18% of the time
✗ Conclusion: Cannot conclude training had an effect
   (Difference might just be sampling error)
```

### **2.3 Important Caveats About p-values**

#### **Caveat 1: Statistical Significance ≠ Practical Significance**

A result can be statistically significant but practically trivial.

**Example:**
```
Company with 10,000 employees implements flexible work policy

Before: M satisfaction = 3.20
After: M satisfaction = 3.25
Difference = 0.05 points (on 1-5 scale)

Statistical test: t(9999) = 3.12, p < .001
Result: STATISTICALLY SIGNIFICANT

But wait:
- 0.05 point difference on 5-point scale = 1% improvement
- Would employees even notice this tiny change?
- Is it worth the cost of implementing the policy?

Statistically significant ≠ Practically meaningful
```

**Why This Happens:**
With very large samples, tiny effects become statistically significant because:
- Large N increases statistical power
- Smaller and smaller effects can be detected
- p-value reflects sample size, not just effect magnitude

**Solution:** Always report **effect size** in addition to p-value

#### **Caveat 2: p-value Doesn't Tell You Effect Size**

**p-value** tells you: "Is there an effect?"
**Effect size** tells you: "How large is the effect?"

You need BOTH for complete interpretation.

#### **Caveat 3: Non-Significant ≠ No Effect**

```
p = .08 means:
✗ NOT: "There is definitely no effect"
✓ Correct: "We don't have sufficient evidence of an effect"

Reasons for non-significance:
- True effect doesn't exist
- Effect exists but sample size too small (low power)
- Effect exists but measurement is noisy (low reliability)
- Effect exists but is very small
```

#### **Caveat 4: p-value Assumes Null Hypothesis**

The p-value is calculated assuming the null hypothesis (no effect) is true.

It answers: "If there's no real effect, how likely would I see these data?"
It does NOT answer: "How likely is it that there's a real effect?"

***

## **SECTION 3: COMPARING GROUPS**

When your research question asks **"Do groups differ?"** you use t-tests or ANOVA.  

### **3.1 Independent Samples t-test: Comparing Two Groups**

**When to Use**: Compare means of **two independent groups**.  

**Independent Groups**: Participants are in **one group OR the other**, not both
- Example: Men vs. Women
- Example: Treatment vs. Control
- Example: Department A vs. Department B

**Research Question Format**:
- "Do men and women differ in job satisfaction?"
- "Does training improve performance compared to no training?"
- "Is turnover higher in Department A than Department B?"

**Formula** (simplified):
\[ t = \frac{\text{Difference between group means}}{\text{Standard error of difference}} \]

More precisely:
\[ t = \frac{M_1 - M_2}{SE} \]

Where:
- \(M_1\) = Mean of Group 1
- \(M_2\) = Mean of Group 2
- \(SE\) = Standard error (incorporates sample sizes and variability)

**Interpretation of t-value**:
- **Larger |t|** = Larger difference relative to variability
- **Smaller |t|** = Smaller difference relative to variability

**Example: Gender Differences in Job Satisfaction**

```
Research Question: Do men and women differ in job satisfaction?

Data:
Men (n = 50):
  M = 3.8
  SD = 0.9

Women (n = 50):
  M = 4.2
  SD = 0.8

Step 1: Calculate difference
Difference = 4.2 - 3.8 = 0.4 points

Step 2: Run t-test
t(98) = -2.44, p = .017

Step 3: Interpret
✓ Statistically significant (p = .017 < .05)
✓ Women report significantly higher satisfaction than men
✓ Difference = 0.4 points

Step 4: Report effect size (Cohen's d)
d = 0.47 (medium effect)

Interpretation:
- Women's satisfaction is 0.47 standard deviations higher than men's
- This is a medium-sized, meaningful difference

Full Interpretation:
"Women (M = 4.2, SD = 0.8) reported significantly higher job satisfaction 
than men (M = 3.8, SD = 0.9), t(98) = -2.44, p = .017, d = 0.47. 
This represents a medium effect size."
```

**Effect Size: Cohen's d**

\[ d = \frac{M_1 - M_2}{SD_{pooled}} \]

**Guidelines** (Cohen, 1988):
- **d = 0.2**: Small effect
- **d = 0.5**: Medium effect
- **d = 0.8**: Large effect

### **3.2 ANOVA: Comparing Three or More Groups**

**When to Use**: Compare means across **3 or more groups**.  

**Why Not Just Multiple t-tests?**
```
If comparing 3 groups:
- Group 1 vs. Group 2
- Group 1 vs. Group 3
- Group 2 vs. Group 3

That's 3 t-tests!

Problem: Multiple comparisons inflate Type I error rate
- Each test has 5% false positive rate
- Doing 3 tests increases overall error rate
- ANOVA controls for this (maintains 5% overall error rate)
```

**Research Question Format**:
- "Does organizational climate differ across departments?"
- "Do different leadership styles yield different performance?"
- "Does job satisfaction vary by job level?"

**ANOVA Tests**:
- **Null Hypothesis**: All group means are equal (\(\mu_1 = \mu_2 = \mu_3 = ...\))
- **Alternative Hypothesis**: At least one group differs from others

**Formula** (conceptual):
\[ F = \frac{\text{Variance between groups}}{\text{Variance within groups}} \]

More precisely:
\[ F = \frac{MS_{between}}{MS_{within}} \]

Where:
- \(MS_{between}\) = Mean square between groups (differences among group means)
- \(MS_{within}\) = Mean square within groups (variability within each group)

**Interpretation of F-value**:
- **Large F** = Group means differ more than expected by chance
- **Small F** = Group means are similar (differences could be chance)

**Example: Organizational Climate Across Departments**

```
Research Question: Does organizational climate differ across departments?

Data (Climate ratings, 1-5 scale):

Sales (n = 30):
  M = 4.1
  SD = 0.6

Engineering (n = 35):
  M = 3.6
  SD = 0.8

Customer Service (n = 28):
  M = 2.9
  SD = 0.7

Step 1: Run One-Way ANOVA
F(2, 90) = 8.76, p < .001

Step 2: Interpret omnibus test
✓ Statistically significant (p < .001)
✓ At least one department differs from others
✓ But ANOVA doesn't tell us WHICH departments differ!

Step 3: Post-hoc tests (pairwise comparisons)
Using Tukey HSD (controls Type I error):

Sales vs. Engineering:
  Difference = 0.5, p = .04 (significant)
  Sales has higher climate

Sales vs. Customer Service:
  Difference = 1.2, p < .001 (highly significant)
  Sales has much higher climate

Engineering vs. Customer Service:
  Difference = 0.7, p = .01 (significant)
  Engineering has higher climate

Step 4: Pattern
Sales > Engineering > Customer Service

Practical Implication:
Customer Service department has significantly worse organizational 
climate and needs intervention.

Full Reporting:
"A one-way ANOVA revealed significant differences in organizational 
climate across departments, F(2, 90) = 8.76, p < .001. Post-hoc 
comparisons using Tukey HSD indicated that Sales (M = 4.1, SD = 0.6) 
had significantly higher climate than Engineering (M = 3.6, SD = 0.8, 
p = .04), which in turn had higher climate than Customer Service 
(M = 2.9, SD = 0.7, p = .01). Sales also differed significantly from 
Customer Service (p < .001)."
```

**Effect Size: Eta-Squared (η²)**

\[ \eta^2 = \frac{SS_{between}}{SS_{total}} \]

**Interpretation**: Proportion of variance in DV explained by group membership

**Guidelines**:
- **η² = 0.01**: Small effect (1% of variance)
- **η² = 0.06**: Medium effect (6% of variance)
- **η² = 0.14**: Large effect (14% of variance)

***

## **SECTION 4: EXAMINING RELATIONSHIPS: CORRELATION**

### **4.1 What is Correlation?**

**Definition**: A statistical measure of the strength and direction of the relationship between two continuous variables.  

**Correlation Coefficient (r)**:  
- **Range**: -1.00 to +1.00
- Developed by Karl Pearson (Pearson correlation)

**Two Key Aspects**:  
1. **Direction**: Positive or negative
2. **Strength**: Weak, moderate, or strong

### **4.2 Direction of Correlation**

#### **Positive Correlation (r > 0)**

**Definition**: As X increases, Y increases; as X decreases, Y decreases.  

Variables change in the **same direction**.

**Example: Job Satisfaction and Performance**
```
r = +0.35

Interpretation:
- Higher satisfaction associated with higher performance
- Lower satisfaction associated with lower performance

Scatterplot:
Performance
    │     ●
    │    ●  ●
    │   ●  ●  ●
    │  ●  ●
    │ ●  ●
    │●
    └────────── Satisfaction

Upward slope (positive relationship)
```

**Other Examples of Positive Correlations**:
- Conscientiousness and job performance: r = +0.30
- Job satisfaction and organizational commitment: r = +0.65
- Training hours and skill level: r = +0.45

#### **Negative Correlation (r < 0)**

**Definition**: As X increases, Y decreases; as X decreases, Y increases.  

Variables change in **opposite directions**.

**Example: Job Stress and Satisfaction**
```
r = -0.48

Interpretation:
- Higher stress associated with lower satisfaction
- Lower stress associated with higher satisfaction

Scatterplot:
Satisfaction
    │●
    │ ●  ●
    │  ●  ●
    │   ●  ●  ●
    │    ●  ●
    │     ●
    └────────── Stress

Downward slope (negative relationship)
```

**Other Examples of Negative Correlations**:
- Job satisfaction and turnover intentions: r = -0.45
- Role conflict and performance: r = -0.30
- Job insecurity and commitment: r = -0.52

#### **Zero Correlation (r ≈ 0)**

**Definition**: No systematic relationship between variables.

Knowing X tells you nothing about Y.

**Example: Shoe Size and Job Performance**
```
r = 0.02 (essentially zero)

Interpretation:
- Shoe size is unrelated to performance
- Knowing someone's shoe size doesn't help predict their performance

Scatterplot:
Performance
    │ ●   ●  ●
    │  ● ●   ●
    │ ●  ●  ●
    │●  ●   ●
    │ ●  ● ●
    └────────── Shoe Size

No pattern (random scatter)
```

### **4.3 Strength of Correlation**

The **absolute value** of r indicates strength.  

**Guidelines** (Cohen, 1988):

```
|r| = 0.00 - 0.10:  Negligible (no practical relationship)
|r| = 0.10 - 0.30:  Small/Weak
|r| = 0.30 - 0.50:  Moderate/Medium
|r| = 0.50 - 0.70:  Large/Strong
|r| = 0.70 - 1.00:  Very Large/Very Strong
```

**Important**: Direction (+ or -) does NOT affect strength!
- r = +0.60 and r = -0.60 are **equally strong**
- One is positive, one is negative, but both are "strong"

**Examples from I/O Psychology**:

```
|r| = 0.10: Age and job performance
"Weak relationship; age explains only 1% of performance variance"

|r| = 0.30: Conscientiousness and job performance
"Moderate relationship; conscientiousness explains 9% of performance variance"

|r| = 0.50: Cognitive ability and job performance
"Strong relationship; cognitive ability explains 25% of performance variance"

|r| = 0.70: Job satisfaction at Time 1 and Time 2 (6 months apart)
"Very strong relationship; satisfaction is stable over time"

|r| = 0.90: Same intelligence test taken twice
"Near-perfect relationship; test is highly reliable"
```

### **4.4 Visualizing Correlations: Scatterplots**

**Perfect Positive (r = +1.0)**:
```
Y │     ●
  │    ●
  │   ●
  │  ●
  │ ●
  │●
  └────── X
All points on straight line, upward slope
```

**Strong Positive (r = +0.70)**:
```
Y │    ● ●
  │   ●  ●
  │  ●  ●
  │ ●  ●
  │●  ●
  └────── X
Points cluster around upward line
```

**Moderate Positive (r = +0.40)**:
```
Y │   ●  ● ●
  │  ●  ●  ●
  │ ●  ●  ●
  │●  ●  ●
  └────── X
Wider scatter, but general upward trend
```

**Zero Correlation (r = 0.0)**:
```
Y │ ●   ●  ●
  │  ● ●   ●
  │ ●  ●  ●
  │●  ●
  └────── X
Random scatter, no pattern
```

**Strong Negative (r = -0.70)**:
```
Y │● ●
  │ ●  ●
  │  ●  ●
  │   ●  ●
  │    ● ●
  └────── X
Points cluster around downward line
```

### **4.5 Variance Explained: r²**

**r² (R-squared)**: Proportion of variance in Y explained by X

**Formula**:
\[ r^2 = \text{(correlation)}^2 \]

**Example:**
```
Satisfaction and performance: r = 0.35

r² = (0.35)² = 0.1225 = 12.25%

Interpretation:
"Job satisfaction explains 12.25% of the variance in job performance."

Meaning:
- 12.25% of differences in performance are associated with satisfaction
- 87.75% of performance variance is due to other factors
```

**Why r² Matters**:

Even "significant" correlations may explain little variance:

```
r = 0.20 (significant with large sample)
r² = 0.04 = 4%

Only 4% of variance explained!
Statistically significant but practically limited
```

**Comparison:**
```
Weak correlation:     r = 0.10 → r² = 0.01 = 1% variance
Moderate correlation: r = 0.30 → r² = 0.09 = 9% variance
Strong correlation:   r = 0.50 → r² = 0.25 = 25% variance
Very strong:          r = 0.70 → r² = 0.49 = 49% variance
```

### **4.6 Full Example: Job Satisfaction and Turnover Intentions**

```
Research Question: Is job satisfaction related to turnover intentions?

Sample: 500 employees
Measurement:
- Job satisfaction: 1-5 scale (survey)
- Turnover intentions: 1-5 scale (survey)

Results:
r = -0.52, p < .001

Step 1: Significance
p < .001 means statistically significant
Result is very unlikely due to chance

Step 2: Direction
r is NEGATIVE
Higher satisfaction associated with LOWER turnover intentions

Step 3: Strength
|r| = 0.52 is in the "strong" range
This is a substantial relationship

Step 4: Variance explained
r² = (-0.52)² = 0.27 = 27%
Satisfaction explains 27% of variance in turnover intentions

Full Interpretation:
"Job satisfaction was significantly negatively correlated with 
turnover intentions, r = -.52, p < .001. This represents a strong 
negative relationship, indicating that employees with higher 
satisfaction report lower intentions to leave. Job satisfaction 
explained 27% of the variance in turnover intentions."

Practical Implication:
Improving satisfaction could substantially reduce turnover risk.
But 73% of turnover variance is explained by other factors 
(pay, career opportunities, management quality, etc.)
```

### **4.7 Reminder: Correlation ≠ Causation**

Even with strong, significant correlations, you **cannot infer causation**.  

```
Finding: Job satisfaction and performance correlated (r = 0.35)

Possible Interpretations:
1. Satisfaction → Performance (satisfaction causes performance)
2. Performance → Satisfaction (performance causes satisfaction)
3. Third variable → Both (e.g., conscientiousness causes both)

Correlation alone cannot distinguish these!
```
