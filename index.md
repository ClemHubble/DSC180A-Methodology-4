---
layout: default
title: Home
---

# Fong Vo
UCSD email: fvo@ucsd.edu

**Section:** A12 Quantifying the credibility of large language model outputs  
**Mentor:** Professor Yian Ma

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic for me this quarter was model calibration and reliability evaluation. I learned that a model can be accurate overall but still poorly calibrated. In other words, the model's confidence scores don’t always reflect how often it’s actually right. Metrics like Expected Calibration Error (ECE) measure this mismatch between confidence and accuracy. QRC bounds (Quantile Reliability Curves) help visualize and quantify how reliability changes across different confidence levels, and CVaR (Conditional Value at Risk) focuses on the model’s worst-case performance, showing how unreliable it gets on its most uncertain predictions. I found it fascinating how these metrics reveal deeper insights into how trustworthy a model really is, beyond just its accuracy score.  

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I might investigate other large language models beyond Llama 8B and see how they perform in terms of accuracy, ECE, QRC bounds, and CVaR on other open-ended datasets.  

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
Another potential change would be to test how calibration behaves across different model architectures or decoding strategies. So far, my project has focused on one model and fixed sampling parameters, but comparing greedy decoding, nucleus sampling, and temperature scaling could reveal how generation strategy influences calibration.  

**What other techniques would you be interested in using in your project?**  
Answer4

