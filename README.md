### This repository contains online materials from our most recent study about hearing impairment.
####
##### - Citation:
***Exome sequencing identifies known and candidate genes in hearing impairment in Cameroon***.\
Ambroise Wonkam, Edmond Wonkam-Tingang, Abdoulaye Yalcouyé, Jean Jacques N
Noubiap, Seraphin Nguefack, Valentina Josiane Ngo Bitoungui, Lettilia Xhakaza, Kalinka
Popel, Thashi Bharadwaj, Rachel Latanich, Cesar A Fortes-Lima, Carmen de Kock, Kevin
Esoh, Hong Zhang, Isabelle Schrauwen, Ulrich Mueller, and Suzanne M Leal


###### Of note, on the top-right side of the figures of the interactive plots, there are different tools for scrolling, zooming in, and zooming out with the mouse (using Box Zoom, Wheel Zoom, Wheel Zoom on the y-axis, Zoom in on the x-axis, Undo, and Reset) or saving the plots as figures in high resolution (*.svg or *.png format). 

### Main Figures
##### Main Figure 2
###### &emsp;[Figure 2A | Principal Component Analysis (PCA) plot based on sub-Saharan African populations.](https://raw.githack.com/GeneMAP-Research/Hearing_Impairment_in_Cameroon/main/Figures/Main_Figure_2A_PCA_plots.html)

##### Python script for PCA plots from PC1 to PC10.
###### python3 scripts/bokeh_pca_plot_PC9toPC10_python3.py -i Tables/Cameroon_HI_DB.pca.evec -p Tables/pattern.csv -o Figures/Main_Figure_2A


###### &emsp;[Figure 2B | ADMIXTURE plot based on sub-Saharan African populations (bottom).](https://raw.githack.com/GeneMAP-Research/Hearing_Impairment_in_Cameroon/main/Figures/Main_Figure_2B-Ref.pdf)

###### &emsp;[Figure 2B | ADMIXTURE plot based on sub-Saharan African populations (top).](https://raw.githack.com/GeneMAP-Research/Hearing_Impairment_in_Cameroon/main/Figures/Main_Figure_2B-Target.pdf)

##### PONG script for ADMIXTURE results at K=4.
###### pong -m Tables/Qfilemap_4.txt -n Tables/pop_order.txt -i Tables/ind2pop.txt -p $RANDOM

