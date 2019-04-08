# MQL4-iCustom-Mode-Shift-Numbers-Detector

They are the only parameters for making an EA from any indicator gives just SELL and BUY signals.

Normal iCustom function in Expert Advisor like that:

  double val=iCustom(NULL,0,"SampleInd",13,1,0);


0 is Shift

1 is Mode

double val=iCustom(NULL,0,"SampleInd",13,Mode,Shift);

in Shift codes, 0 means that signal is comming from the current bur, 1 means that comes from the privous bar.

Mode numbers are between 0 to 7, Shift's are 0, 1.

Usually modes for 0 and 1 mean that one of them means that signal is BUY SIGNAL or SELL SIGNAL, other means other SIGNAL.

![ScreenShot 1](https://github.com/inceabdullah/MQL4-iCustom-Mode-Shift-Numbers-Detector/blob/master/iCustom_Shift_Mode_Signal_Count_for_EA.png)

This example in ScreenShot 1 is for the indicator "Tipu CCI".

If you want to change into your own custom indicator, you should change value in indicator name parameter. Like this:

![ScreenShot 2](https://github.com/inceabdullah/MQL4-iCustom-Mode-Shift-Numbers-Detector/blob/master/iCustom_indicators_folder.png)

But in ![YouTube video](https://youtu.be/aHXldAYU7hU) is for few different indicators give SELL and BUY signals.
