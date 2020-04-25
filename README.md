# DEStemplates
Codes to produce templates from DES SN data

Run in sequence:
  1) 01_LightCurveStats.ipynb   <-- no need to run this one (takes a long time); output is in LC_MergedOutput.csv
  2) 02_PrepData.ipynb
  3) 03_ApplyCuts.ipynb
  4) 04_runGP2_v4.ipynb
 
In each notebook, edit the BASEDIR variable to point to your base directory where these codes exist.

Also download large files from Midway:

  /scratch/midway2/masao/psnid_desdata/DES_ALL/DESALL_forcePhoto_real_snana_fits/
  
and save them in:

  BASEDIR/DES_ALL/DESALL_forcePhoto_real_snana_fits/
