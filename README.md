# Shiny App using sigma.js for R - Social Network Analysis

### Teenage Friends and Lifestyle Study - Glasgow

[(West and Sweeting 1995, Michell and Amos 1997, Pearson and Michell 2000, Pearson and West 2003)](https://www.stats.ox.ac.uk/~snijders/siena/Glasgow_data.htm)

## Demo for Interactive Network Graph - Public Engagement

This is a shiny app for exploratory analysis of social network data. This is an important process to every project that involves understanding the interdependencies of data observations and the interactions these have along demographic covariates. The following demo allows users to explore the Teenage Glasgow dataset through a modellers' lense and seeks to contribute towards participatory action methods, involving stakeholders in the modelling process as they are able to visualise variation of smoking behaviours (non-smoker, occassional, frequent) color of nodes along personal attributes including sex and parent smoking outcomes. A table with descriptive statistics is updated with each selection of the survey wave, these values report metrics that reflect on the school-cohort cohesion. 

You could skip cloning the repo and run it directly in your R script/console the following lines of code, try to check if you've installed shiny and/or pacman before running this in the console/a script. Pacman will serve as your package installation/loading manager, it will install any of the packages used and not already installed so this may take a moment. It's worth restarting your R session if there is an error the first time you try to run the following lines of code, this may likely need to happen since many of the packages required will be new to your R environment.

## To Run from Script/Console 

```r
install.packages("shiny")

install.packages("pacman")

require(shiny)

require("pacman")

runGitHub(repo = "teenage-glasgow-shiny-demo", username = "omiridoue", ref = "main")
```

## To Clone the Repository 

**Step 1:** Open a new Rproject
![openj](https://github.com/omiridoue/teenage-glasgow-shiny-demo/assets/126977992/28344d37-4605-4248-950d-fc4fdd0257fd)

**Step 2:** Navigate to the code folder and open Rproj 'teenage-glasgow-shiny-demo'
![step3](https://github.com/omiridoue/teenage-glasgow-shiny-demo/assets/126977992/0ca9def5-afd9-4d54-ac5d-c2b13f01b857)

**Step 3:** Navigate to the app.R file and open the script, click on the Run App button to render the shiny app file.
![img3](https://github.com/omiridoue/teenage-glasgow-shiny-demo/assets/126977992/c814a190-0b8a-4a25-9ff7-4191f48cde13)

**Step 4:** View in Browser
![shiny-demo](https://github.com/omiridoue/teenage-glasgow-shiny-demo/assets/126977992/69862d19-b874-4519-be21-238138d54da2)

## References 

**Bush, H., P. West, and L. Michell (1997)**. The role of friendship groups in the uptake and maintenance of smoking amongst pre-adolescent and adolescent children: Distribution of Frequencies. Working Paper No. 62. MRC Medical Sociology Unit Glasgow.<br>
**Michell, L. (1997a)**. Pressure groups: young people's accounts of peer pressure to smoke. Social Sciences in Health, 3, 3-17.<br>
**Michell, L. (1997b)**. Loud, sad or bad: young people's perceptions of peer groups and smoking. Health Education Research, 12(1), 1-14.<br>
**Michell, L., and A. Amos (1997).** Girls, pecking order and smoking. Social Science and Medicine, 44, 1861-1869.<br>
**Michell, L., and P. West (1996).** Peer pressure to smoke: the meaning depends on the method. Health Education Research, 11(1), 39-49.<br>
**Pearson, M., and L. Michell. 2000.** Smoke Rings: Social network analysis of friendship groups, smoking and drug-taking. Drugs: education, prevention and policy, 7, 21-37.<br>
**Pearson, M., and P. West. 2003.** Drifting Smoke Rings: Social Network Analysis and Markov Processes in a Longitudinal Study of Friendship Groups and Risk-Taking. Connections, 25(2), 59-76.<br>
**Pearson, M., Ch. Steglich, and T.A.B. Snijders (2006).** Homophily and assimilation among sport-active adolescent substance users. Connections 27(1), 47-63.<br>
**Steglich, Ch., T.A.B. Snijders, and M. Pearson (2010).** Dynamic Networks and Behavior: Separating Selection from Influence. Sociological Methodology, 329-393. DOI: http://dx.doi.org/10.1111/j.1467-9531.2010.01225.x.<br>
**Steglich, Ch., T.A.B. Snijders, and P. West (2006),** Applying SIENA: An illustrative analysis of the co-evolution of adolescents' friendship networks, taste in music, and alcohol consumption. Methodology, 2, 48-56.<br>
**Veenstra, R., and Ch. Steglich (2012).** Actor-based model for network and behavior dynamics: A tool to examine selection and influence processes. Chapter 34 (pp. 598-618) in B. Laursen, T. D. Little, and N. A. Card (Eds.), Handbook of developmental research methods. New York: Guilford Press.
