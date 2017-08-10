# excel2latexTable_MAC
A shell script to convert an Excel table to latex format using the clipboard.

Made for mac OS X with homebrew bash.

## How to use this script:

1. Select your table in Excel and copy it
2. Run the script  
3. Go to your latex file and do "Paste"

## Tip

Copy the file in a folder whose path is included in your environnement for immediate use.
For example, I copied the file in the bin folder (/Users/quentin/bin). Then I can simple use the terminal and type "bash excel2latex" to run the script.

## Example of the result:  

\begin{table}  
	\centering  
	\caption{}  
	\label{}   
	\begin{tabular}{||}   
		\toprule \\  
		107 & 719 & 8 \\  
		\midrule    
		33 & 19 & 67 \\  
		17 & 6 & 13 \\  
		\bottomrule \\  
	\end{tabular}   
\end{table}   
 
