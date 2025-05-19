# Xianglab-publication-code
![XiangLab_icon_small](https://github.com/rwfwuwx/Xianglab-publication-code/assets/60617251/3449052a-b6e8-45ea-9216-437d61501e85)   

## What's in here
The lab's work (http://www.xianglab.com.cn/col.jsp?id=105) is performed on the 11buddy-&-I research platform (https://github.com/rwfwuwx/11buddy-and-I).   

From 2024, as 11buddies grow up, we present them here along with the publication, which is critical for resarch integrety and replication.   

For each publicated work, we show how ada generate the reported results: 
- fill in the **ada_requirement_table**   
  i.e., tell ada your requirements for generating the reported results.   
  The table is in the .xlsx format.   

- ask ada to generate the **ada_report_file**   
  given your requirement, ada asks for the necessary data/info from other 11buddies, and generates the report file.   
  The report file contains the exact reported results including the statistical texts, tables, figures, along with the codes generating them.   
  The report file is in the .docx and .mlx formart.   

Note: For the end-to-end 11buddy research pipeline of a study from the starting data collection ... untill the result reporting here, i.e., the Study_TaskList, please see https://github.com/rwfwuwx/11buddy-and-I.   
Note: The ada_report_file was in the .docx or .mlx formart, which is not supported for uploading in github. A .pdf version is thus attached instead.   
Note: The most latest 11buddies are presented here, and may look not exactly the same as they were originally with pubilication months/years before (it's normal, they are growing up).  

## Publication with 11buddy
### work 2025_VR
Huang Y#, Wang C#, Wu X* (2025) Could an auditory equivalent to a continuously varying visual stimulus improve beat synchronization? Evidence supporting vision as a trustworthy modality in sensorimotor timing. Vision Research 232: 108616.   
[1-s2.0-S004269892500077X-main.pdf](https://github.com/user-attachments/files/20277289/1-s2.0-S004269892500077X-main.pdf)   

To generate the reported results,
- fill in the ada_requirement_table
![image](https://github.com/user-attachments/assets/0c0d2f2b-f191-4f7b-95cb-bbc7535bdc44)   

- ask ada to generate the ada_report_file
  Type 'ada_ganhuola_behav_template_studyID' in Matlab command window; wait ada finish running; then open and read the ada_report_file:   
  [ada_report_behav_meanAsynSd_ss_20240619.pdf](https://github.com/user-attachments/files/20277374/ada_report_behav_meanAsynSd_ss_20240619.pdf)   
  [ada_report_behav_meanVar_circ_20240619.pdf](https://github.com/user-attachments/files/20277377/ada_report_behav_meanVar_circ_20240619.pdf)   

In addition to ada, yangyang of the present work is also attached here [VR2025_program.zip](https://github.com/user-attachments/files/20277424/VR2025_program.zip)   
To run the program,   
- given yangyang(Psychobuddy) is already installed；
- extract VR2025_program.zip, enter the VR2025_program folder in matlab
- in matlab command window, type: >> load yangyang; yangyang()  (enjoy)

btw, a note for the bouncing ball program, the paper describing it was published (2015) before yangyang was born (2021), and a version of the program has been online at Journal of Visualized Experiments (2017) 127:e562025 (while the website link was broken somehow later).    
For those who have requested the program, I apologize for the much delayed response, which is as below:    
- For research consideration, I recommend to use the contracting ring here, instead of the bouncing ball. Particularly if you plan to use brain-imaging methods; while the ball is behaviorally superior (a little bit) , the ring does not yield potential eyemovements.
- Specifically for the ball program, upon the nex work using the ball, 11buddy will check the backup versions, update it to the automatic manner (as the manner presented here), and you will be able to use it directly: just ask 11buddy to do it for you, no need to ask anybody(I am so tired of this kind of stuff, I believe you could also be); just let 11buddy handle it.   

### work 2024_VR
Huang Y#, Zhan L#, Zhong S, Sun M, Wang C, Yang C, Wu X* (2024) Sustaining attention in visuomotor timing is associated with location-based binding. Vision Research 219: 108405.   
[Huang et al. - 2024 - Sustaining attention in visuomotor timing is assoc.pdf](https://github.com/rwfwuwx/Xianglab-publication-code/files/15328828/Huang.et.al.-.2024.-.Sustaining.attention.in.visuomotor.timing.is.assoc.pdf)   

To generate the reported results,
- fill in the ada_requirement_table   
![image](https://github.com/rwfwuwx/Xianglab-publication-code/assets/60617251/9261b5a7-56b2-466b-bb6e-1a30dca398f9)   

- ask ada to generate the ada_report_file   
  Type 'ada_ganhuola_behav_template_studyID' in Matlab command window; wait ada finish running; then open and read the ada_report_file:   
[ada_report_behav_20231204_Stab_20240515.pdf](https://github.com/rwfwuwx/Xianglab-publication-code/files/15328905/ada_report_behav_20231204_Stab_20240515.pdf)


### work 2023_FNS
Zhou P#, Wu Q#, Zhan L#, Guo Z, Wang C, Wang S, Yang Q, Lin J, Zhang F, Liu L, Lin D, Fu W* Wu X* (2023) Alpha peak activity in resting-state EEG is associated with depressive score. Frontiers in Neuroscience 17: 1057908.   
[Zhou et al. - 2023 - Alpha peak activity in resting-state EEG is associ.pdf](https://github.com/rwfwuwx/Xianglab-publication-code/files/14718774/Zhou.et.al.-.2023.-.Alpha.peak.activity.in.resting-state.EEG.is.associ.pdf)   

To generate the reported results,   
- fill in the ada_requirement_table   
![image](https://github.com/rwfwuwx/Xianglab-publication-code/assets/60617251/9f82c499-2ca1-4d81-a441-a4692c97f2b7)   

- ask ada to generate the ada_report_file   
  Type 'ada_ganhuola_template_studyID' in Matlab command window; wait ada finish running; then open and read the ada_report_file:
[ada_report_sds_corr_P_Pre_source_20231204.pdf](https://github.com/rwfwuwx/Xianglab-publication-code/files/14719037/ada_report_sds_corr_P_Pre_source_20231204.pdf)
