---
title: "AI4H Lab - Research"
layout: textlay
excerpt: "AI4H Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

## Blood Glucose Management for People with Type 1 Diabetes (Ken Li)
![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/res_bglp.png){: style="width: 90%; float: center; margin: 10px"}

Diabetes is a group of chronic metabolic disorders that affect almost half a billion people worldwide1, and around 10% of them have **type 1 diabetes (T1D)**. Due to an absolute deficiency of endogenous insulin caused by pancreatic β-cell loss, the management of T1D relies on exogenous insulin delivery and adherence to a group of self-care behaviors, such as estimating dietary carbohydrate and exercise, and titrating insulin therapy. The primary objective of T1D self-management is to prevent immediate adverse glycemic events, including hypoglycemia and hyperglycemia, and minimize the risk of long-term diabetes complications. Severe hypoglycemia may cause seizures, brain damage, and intellectual impairment, while hyperglycemia is a risk factor for cardiovascular diseases, neuropathy, nephropathy and retinopathy. The development of **continuous glucose monitoring (CGM)** has led to therapeutic benefits in diabetes management. The usage of real-time CGM systems has been demonstrated to reduce the number of severe hypoglycemic events for T1D subjects with multiple daily injection (MDI). As a wearable device that automatically measures glucose levels with a fixed frequency (e.g. five minutes), CGM can be combined with an insulin pump as sensor-augmented therapy or an **artificial pancreas (AP)** for closed-loop glycemic control. [MORE INFO](https://www.nature.com/articles/s41746-022-00626-5)


![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/pancras.png){: style="width: 90%; float: center; margin: 10px"}

In an AP system, the CGM sensor measures real-time glucose concentration at a fixed frequency (e.g., every 5 min) and transmits the readings to a controller which computes the insulin doses to be delivered by a pump. **Reinforcement learning**, a sub-field of machine learning, employs a goal-oriented agent to learn the strategies for sequential decision-making, which has been increasingly applied to glycemic control, and in particular, for **basal insulin modulation**.[MORE INFO](https://www.mdpi.com/1424-8220/20/18/5058)

![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/prediction_bg.png){: style="width: 90%; float: center; margin: 10px"}

CGM has produced a vast amount of BG data with its increasing use in the diabetes population. Taking advantage of this, the emergence of deep learning algorithms for **BG prediction** has achieved recent success and outperformed several conventional machine learning approaches in terms of accuracy. Generally, the major challenge of BG prediction lies in accounting for the intra- and interperson variability that leads to various glucose responses under different conditions. Furthermore, many external events and factors can influence glucose dynamics, such as meal ingestion, physical exercise, psychological stress, and illness. **Deep learning** is powerful at extracting hidden representations from large-scale raw data, making it suitable for accounting for the complexity of glucose dynamics in diabetes.[MORE INFO](http://ceur-ws.org/Vol-2675/paper15.pdf)

## Improving Healthcare and Outcomes of Critically Ill Children During Transport to a Higher Level of Care (Zhiqiang Huo)
![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/ill_child.png){: style="width: 250px; float: left; margin: 0px  10px"}

"A healthy person has a thousand wishes, a sick man has but one - Berger R, 1986"

The Paediatric patient is a special cohort of patients with a wide age range from birth through to aged 16. They need careful care and specialized treatment and intervention due to their complexity. Due to developmental disease, some children need to be referred and transported to receive a higher level of care in a children's hospital. During transport, patients are likely to experience health deterioration and poor outcomes. Our work aims to early detect patients who have a deteriorating health condition in a proactive fashion using continuously monitored patient vital signs and advanced artificial intelligence. More importantly, this will help dedicated intensivists make better decision-making whilst the whole course of transport, medication and intervention to improve the health care and outcomes of patients.

<!-- ## Stroke Care: improving lives of stroke patients using data (Zhiqiang Huo)

![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/stroke_care.png){: style="width: 250px; float: left; margin: 0px  10px"}

Stroke is the fourth leading cause of death in the UK and single largest cause of complex disability in adults, with annual costs projected to rise to £75bn within 20 years. 100,000 people have strokes each year in the UK. The NHS England (NHSE) Long Term Plan is committed to saving 150,000 lives from cardiovascular disease over the next 10 years. Stroke survivors, clinicians, and policymakers have consistently called for better quality data on the long-term consequences of stroke, to better inform their clinical decision making. -->

<!-- We are commited to unlocking the potential of data - reshaping health and care for stroke survivors with data. Providing data-driven solutions for stroke patients, health providers, researchers and policymakers, with an improved understanding of patient-centred health data and the use of cut-edging data analytics such as statistics, data mining, and AI technologies. [MORE INFO](http://strokecare.uk) -->


<!-- ## Health monitoring and fault diagnosis of industrial machinery system (Zhiqiang Huo)
![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/pump.png){: style="width: 250px; float: left; margin: 0px  10px"}

Fault diagnosis of the multistage centrifuge air pump is of great significance to ensure a reliable and safe environment for the indsutry. This project aims to monitor and diagnose the health condition of the industrial-level equipment so that incipient faults can be identified and troubleshoot as early as possible. My role is to design and deploy condition monitoring system on the machinery. Develop data-driven fault diagnosis methods (i.e., data processing, data analysis, and decision making) to identify potential faults and distinguish between various machine health states. Involve project planning and technology choosing. -->


## Real-time Aggregated Prediction of Hospital Admission for Emergency (Zella King)

![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/zk_npj.png){: style="width: 50%; float: left; margin: 0px  10px"}

To date, most applications of Artificial Intelligence (AI) to healthcare have been applied to address clinical questions at the level of individual patients. Now that many hospitals have electronic health records (EHRs) and data warehouse capabilities, there is the potential to exploit the promise of AI for operational purposes. Hospitals are highly connected systems in which capacity constraints in one area (for example, lack of ward beds) impede the flow of patients from other locations, such as the emergency department (ED) or those ready for discharge from intensive care. Arrivals to the ED show diurnal and seasonal variations, with predicted peaks in the morning and early evening, but workflows elsewhere in a hospital mean that discharges from the hospital happen late in the day, creating flow problems. This mismatch of cadence between different parts of the hospital results in patients boarding in ED, or being admitted to inappropriate wards, with adverse consequences including longer stays, greater risk of medical errors and worse long-term outcomes in elderly patients.

Hospital services can be managed more efficiently if accurate short-term forecasts for emergency demand are available. Currently, most hospitals use simple heuristics to make short-term forecasts of numbers of emergency admissions, which are based on rolling averages for each day of the week. Maching Learning (ML) is attractive for such predictions because its aggregation of weak predictors may create a strong prediction model. [MORE INFO](https://www.nature.com/articles/s41746-022-00649-y)

<!-- Our overarching goal is to explore and understand new quantum states of electronic matter on the atomic scale. To do so, we use and develop novel spectroscopic-imaging scanning tunneling microscopy (SI-STM) tools to visualize the relevant quantum mechanical degrees of freedom.

Our goal is to build instruments and develop techniques that enable us to address the questions we find most interesting. This is possible thanks also to Milan's broad background with different research themes and technologies: he learned his trade in [Seamus Davis’ SI-STM lab](http://davisgroup.lassp.cornell.edu/) and with [Felix Baumberger](http://dpmc.unige.ch/gr_baumberger/index.html), and later moved as an [ETH fellow](http://www.ethfellows.ethz.ch/) to [Andreas Wallraff’s qudev lab](http://www.qudev.ethz.ch/) where he investigated coupled cavity arrays in circuit QED. We further have group members with different background and interests, working together on physics and instrumentation.

Here are some themes and techniques that we currently work on:

**Scanning tunneling noise spectroscopy (STNS).** We have developed a novel cryogenic MHz amplifier that allows us to measure not only the average tunneling current, but also its fluctuation! This has many applications: one can detect the fluctuations of the electronic states, peculiar tunneling processes, and shot noise. We have used this instrument to discover charge trapping in the insulating layer of the cuprates, connected to the c-axis mystery, and to measure the doubling of the charge due to Andreev processes to the superfluid in a lead sample.


**Mott physics and high-temperature superconductivity.** Questions of interest include: (i), How does the Mott state collapse upon doping and how is this related to the complex phase diagram of high-temperature superconductors? (ii), What is the strange metal phase seen in correlated electron systems? Is this an exotic long-range entangled state? What is the mechanism of dissipation in that state? (iii), Why is the transition temperature in high-temperature superconductors so high? We have worked on iridates, rhodates, and cuprates.

**Nanofabricated "Smart Tips"**.
![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}
One of the  projects back from my job-proposal is to develop nanofabricated STM tips. The idea behind these “smart tips” is to use the technologies that were developed over decades in nanofabrication and make them available for scanning probe by using a nano-device instead of the traditional STM tungsten tip. One gains the flexibility of using different functionalities that are known from the fields of nanofabrication and mesoscopic physics. We are collaborating with the group Simon Groeblacher at TU Delft to realize this concept, benefitting from their unparalleled micro/nano fabrication know how.  A prototype of a smart tip is shown to the left. See publications in Microsyst Nanoeng, Nanotechnology, and PRB.

**Josephson STM.** Josephson STM has the ability to gain insight into spatial variations of the order parameter, or superfluid density. We have managed to, for the first time, use JSTM with atomic resolution on a quantum material.
We have used atomic-resolution Josephson scanning tunneling microscopy to reveal a strongly inhomogeneous superfluid in the iron-based superconductor FeTe0.55Se0.45. The results and their implications are published in Nature.

We also detected and investigated a quite particular YSR state in the same material.

**Ultra-stable SI-STM instrument.**  ![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/STMHead.png){: style="width: 250px; float: right; margin: 0px 10px"}
For SI-STM, having the most stable STM head is key. We have used finite element simulations, good choices in material science, and craftsmanship to build the most stable STM head in the world, to our knowledge. See publication in RSI.


**Strange Metals.** The strange metal phase might be the most mysterious phase of high-temperature superconductors. Here, the electrical resistivity grows linearly with temperature T in large areas of the phase diagram, with a mean free path that diminishes to a fraction of the interatomic distance. T-linear resistivity is often associated with quantum critical points and marginal-Fermi-liquid physics. In strange metals, the mystery seems to go even further: we deal with something that looks like a quantum critical phase over an extended range of the phase diagram instead of cumulating in a point. There exists no consistent theory for strange metals, leading to more adventurous new approaches including the holographic theories that use insights from gravity to explain strange metals (a recent textbook on this was written by our colleagues at Leiden University, Schalm and Zaanen).
We are part of the 'Strange Metal consortium NL' that includes the groups of Hussey, Golden, van Heumen, Zaanen, Schalm, Stoof and Vandoren. 

**Magnetic fluctuations and electron spin resonance.**
![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/SpinFluc.png){: style="width: 70%; float: center; margin: 10px"}

**Twisted bilayer graphene and other material with super-periodicities.**
We have proposed that artificial super-periodicities can lead to improved superconductivity, both because of increased density of states and because of phase space arguments (see image from our SciPost publication below). Perhaps for different reasons, twisted bilayer graphene has been shown to superconduct! We are investigate this material with the groups of Efetov, Baumberger, and van der Molen.

![]({{ site.remote_url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"} -->

### ... and more.
