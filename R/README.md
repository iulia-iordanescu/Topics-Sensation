Instructions for running R code:  
Step 1: Go to the R project home[page](https://www.r-project.org/) and download the latest release. As of 5/26/2018, the latest release was R version 3.5.0 (Joy in Playing)[https://cran.r-project.org/src/base/R-3/R-3.5.0.tar.gz].  
Step 2: Follow the [download R](https://cran.r-project.org/mirrors.html) instructions.  
Step 3: Select a mirror.  
Step 4: Download [R studio](https://www.rstudio.com/products/rstudio/download/#download) As of 5/26/2018, the latest version was RStudio 1.1.453.  
Step 5:You are now ready to edit my R program.  
Step 6: To run my R program:  
 > Open a command line window(click  Windows Start button and type "cmd" or "run" -> "cmd"   
 > Let's suppose you land in C:\Users\user1>  
 > You can run my script using 3 ways. Rscript.exe,R.exe (the non-interactive way) and R.exe the intercative way.(typically they will be in C:\Users\user1\Documents\R\R-3.5.0\bin\x64\)
 
 > To use Rscript.exe do: 	
 > Step 1: Copy and paste the following command in the command line window:  
  C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\Rscript.exe "C:\noi\iulia\prj\Topics-Sensation\R\Hello_World_R_Coding.R"  
 > Step 2: If it has been done successfully, the output should look like this:    
  [1] "Hello world! sqrt of 2 is ... 1.4142135623731"   
 
 > To use R.exe (interactively)do:         
 > Step 1:Copy and paste the following command in the command line window: C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\R.exe  
 > Step 2: Now that you are in R, copy and paste this function to define it:  
 
myfirstfunction <- function(){  
		square_root_of_2 = sqrt(2)  
	paste(c("Hello world! sqrt of 2 is ...", square_root_of_2), collapse=" ")  
  
}  
  
 > Step 3: Now that the function has been defined, type in:   
 myfirstfunction()         
  > Step 4: If this has been done correctly, the output should be:[1] "Hello world! sqrt of 2 is ... 1.4142135623731"   
 
 > To use R.exe (non-interactively) do:          
 > Step 1: Copy and paste the following command in command line(Note: Close the R before doing this step):      
C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\R.exe CMD BATCH "C:\noi\iulia\prj\Topics-Sensation\R\Hello_World_R_Coding.R" "C:\noi\crt_output.txt"   
 > Step 2: After doing this, go to the file (noi), and there you should be able to find "crt_output.txt"  
 > Step 3: When you open "crt_output.txt" you will find that your output is:    
"Hello world! sqrt of 2 is ... 1.4142135623731"





C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\R.exe CMD BATCH "C:\noi\iulia\prj\Topics-Sensation\R\Hello_World_R_Coding.R" "C:\noi\crt_output.txt"






C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\Rscript.exe "C:\noi\iulia\prj\Topics-Sensation\R\Hello_World_R_Coding.R"  
[1] "Hello world! sqrt of 2 is ... 1.4142135623731"

C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\R.exe CMD BATCH "C:\noi\iulia\prj\Topics-Sensation\R\Hello_World_R_Coding.R" "C:\noi\crt_output.txt"

C:\Users\copiii\Documents\R\R-3.5.0\bin\x64\R.exe