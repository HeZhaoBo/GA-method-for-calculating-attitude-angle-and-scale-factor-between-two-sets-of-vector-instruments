# GA-method-for-calculating-attitude-angle-and-scale-factor-between-two-sets-of-vector-instruments
A program in a manuscript in Earth Planet and Space

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Function: A GA method to calculate attitude angles and scale factors between two vector instruments
Authors: Zhaobo He, Xingxing Hu, Yuntian Teng, Xiuxia Zhang, Xiaoyu Shen.
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

1.Unzip the file "generic.rar" and copy the folder to the MATLAB installation path.

2.Open the "mytoolbox.txt" file, modify the "generic" path and run in the MATLAB window.
Note: This step may be made each time you restart your computer when you find a error report with key word "function rep" in matlab.

3.Open the "GA_days.m" or "GA_days_ex.m" file, modify the data path and the month of data . 
Run "GA_days.m" or "GA_days_ex.m" file after confirming or modifying the attitude angle range in the function file "jiaodufanyan_gen.m".

4.The program gives the data comparison diagram before and after daily-correction, 
and the calculation results "Q_huizong" are given in the variable position of the MATLAB command window.
The column of "Q_huizong" is represented from left to right: attitude angles Roll, Pitch, YAW, and scale factors on the three components.

5.It should be noted that this program can continuously calculate the attitude angles and scale factors of two sets of instruments 
in one month. However, in order to obtain a good calculation result, the results should be filtered in accordance with the flowchart 
in the manuscript, and may calculate multiple times. This is mainly because of the attitude angle and the scale factor are mutually coupled
 in the raw data of the two sets of instruments, , and we need to gradually peel the two influencing factors through a series of operations.




