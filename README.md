Whilst looking for health data scientist positions, I interviewed for one job centered around mental health prediction modelling. To become more familiar with this domain of medicine, I started some practice analysis on a mental health dataset -
https://www.kaggle.com/datasets/thedevastator/medical-student-mental-health

This dataset has 887 rows and the following 12 columns:

    id - unique identifier
    sex - Gender of the participant. (String)
    age - age at time of questionnaire 20-21. (Integer)
    year - In which curriculum year are you? 1=Bmed1; 2=Bmed2; 3=Bmed3; 4=Mmed1; 5=Mmed2; 6=Mmed3. (Integer)
    glang - Language spoken by the participant.  (String)
    job - Job of the participant. (String)
    stud_h - Hours of study per week of the participant. (Integer)
    health - Self-reported health status of the participant. (String)
    psyt - Psychological distress score of the participant. (Integer)
    jspe - Job satisfaction score of the participant. (Integer)
    qcae_cog - Cognitive empathy score of the participant. (Integer)    
    qcae_aff - Affective empathy score of the participant. (Integer)
    amsp - Academic motivation score of the participant. (Integer)
    erec_mean - Empathy rating score mean of the participant. (Integer)
    cesd - Center for Epidemiologic Studies Depression scale of the participant. (Integer)
    stai_t - State-Trait Anxiety Inventory scale of the participant. (Integer)
    mbi_ex - Maslach Burnout Inventory-Exhaustion scale of the participant. (Integer)
    mbi_cy - Maslach Burnout Inventory - Cynicism Scale of the participant. (Integer)
    mbi_ea - Maslach Burnout Inventory - Professional Efficacy Scale of the participant. (Integer)

I plan to do the formatting of variables and exploratory data analysis (summary statistics, Q-Q plots, box-plots, t-tests etc.), followed by survival analysis and prediction modelling in an RMD to be knitted into an interactive HTML document.

I've planned the analysis using the following resources:

    Other repos on my github - https://github.com/georgemelrose/Dummy-HES-APC-Data-Work , https://github.com/georgemelrose/Mental-Health-Data-Practice

    The excellent HealthyR textbook - https://argoshare.is.ed.ac.uk/healthyr_book/

    The unsurpassable survival analysis tutorial of Dr Emily Zabor - https://www.emilyzabor.com/tutorials/survival_analysis_in_r_tutorial.html
