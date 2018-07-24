# PipeLine


#####  README  #####  July 24, 2018

This readme file describes the example pipeline programs for human and mouse antibody repertoire analyses.
(The details of the programs will be appeared in the Journal of Visualized Experiments (submitted on July 20, 2018).)

The body contains three blocks:
1) 02_MiSeqDataPolish
2) 03_PipeLine_Mouse
3) 05_PipeLine_Human

Note: The example programs were implemented on UNIX environment in MacOS_10.13.5.
Please use them as an example reference because the performance may depend on the operating systems and hardware environments. The authors do not accept any liability for errors or omissions.

# Download and Install R
http://cran.cnr.berkeley.edu/
(Package ‘rgl’ needed)

# Install the latest version of Perl

# Install IgBLAST according to the instructions
https://www.ncbi.nlm.nih.gov/igblast/faq.html#standalone
(The germline gene databases should be preferably from "IMGT".)

# Download and Install FASTX-Toolkit
http://hannonlab.cshl.edu/fastx_toolkit/



I. Quality control of FASTQ data  #####

"02_MiSeqDataPolish" folder contains the example shell scripts for the .fastq data.



II. Visualization of the holistic feature for mouse antibody repertoire   #####

"03_PipeLine_Mouse" folder contains two folders.

1) In the "03a_MoIgH_PipeLine_180724" folder, run the shell script;
$ . 00a1_3DView_MoIgH_Kz180406.sh
, will give the rgl 3D-plots of VDJ-repertoire for mouse IgH classes in "Kz180406_Test" folder.

2) In the "03b_MoIgL_PipeLine_180724" folder, run the shell script;
$ . 00_2DView_MoIgL_Kz180406.sh
, will give "*Dim2Rpm.txt" file in "099_Kz180406_MoIgL_Test" folder, which gives 2D-bar graph (with Excel) of mouse IgL VJ-repertoire.



III. Visualization of the holistic feature for human antibody repertoire   #####

"05_PipeLine_Human" folder contains two folders.

1) In the "05a_HuIgH_PipeLine_180724" folder, run the shell script;
$ . 00a1_3DView_HuIgH_Kz180411.sh
, will give the rgl 3D-plots of VDJ-repertoire for human IgH classes in "Test_HuIgH_180724" folder.

2) In the "05b_HuIgL_PipeLine_180724" folder, run the shell script;
$ . 00_2DView_HuIgL_Kz180319.sh
, will give "*Dim2Rpm.txt" file in "Test180319_Polished_TrmQflRcp_100" folder, which gives 2D-bar graph (with Excel) of human IgL VJ-repertoire.



###### Feel free to contact us at
ohnishik@nih.go.jp
for any comments or questions.

##########################################################################
