
Prognostic Potential Predictability (PPP)
==========
>> For calculating Prognostic Potential Predictability (PPP) on nostore-osl 
>> Mainly evaluating if the system is well constrained. 

Author: Mao-Lin Shen (E-mail: maolin.shen@uib.no)

  * Figures of the PPP for different levels are not shown because there are too many levels and GitHub can only present the web-page if the page size is smaller than 1MB.


## Analysis:
--------------------------------------
* ### Full Profile assimilated Ocean and State-nudged Atmosphere of NorESM (1st version)

  * About this analysis:
    * __Finished on ?? ?? 2016__
    * Have to wait for Yiguo Wang's work on full profiled assimilation
    * More details can be found in the [description page] (docs/FrontPage.markdown)
    * PPP of SST ![] (figures/FFSSTwiNudA_ini_1st_try/PPP_PPP-08.cam2.h0.SST.png)

--------------------------------------
* ### Full Profile assimilated Ocean of NorESM (1st version)

  * About this analysis:
    * __Finished on ?? ?? 2016__
    * Have to wait for Yiguo Wang's work on full profiled assimilation
    * More details can be found in the [description page] (docs/FrontPage.markdown)
    * PPP of SST ![] (figures/FFSSTwiNudA_ini_1st_try/PPP_PPP-08.cam2.h0.SST.png)

--------------------------------------
* ### [Full field SST assimilated Ocean of NorESM (3rd version)] (docs/FrontPage_FF_3rd_try.markdown)

  * About this analysis:
    * __Finished on 28 Jan 2016__
    * More details can be found in the [description page] (docs/FrontPage_FF_3rd_try.markdown)
    * PPP of air surface temperature [![] (figures/FF_3rd_try/PPP_atm/PPP_All_G04.cam2.h0.TS.png)] (docs/FrontPage_FF_3rd_try.markdown)



--------------------------------------
* ### Full field SST assimilated Ocean of NorESM (2nd version)

  * About this analysis:
    * __Finished on 20 Dec 2015__
    * More details can be found in the [description page] (docs/FrontPage_FF_2nd_try.markdown)
    * PPP of air surface temperature [![] (figures/FF_ini_2nd_try/PPP_atm/PPP_All_G04.cam2.h0.TS.png)] (docs/FrontPage_FF_2nd_try.markdown)

--------------------------------------
* ### [Full field SST assimilated Ocean of NorESM (1st version)] (docs/FrontPage_FF_ini_try.markdown)

  * About this analysis:
   * __Finished on 18 Apr. 2015__
   * More details can be found in the [description page] (docs/FrontPage_FF_ini_try.markdown)
   * PPP of  air surface temperature[![] (figures/FF_ini_try/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_FF_ini_try.markdown)

--------------------------------------
* ### [Uninitialized NorESM (histrical forcing only)] (docs/FrontPage_Historical_forcing_ens.markdown)

  * About this analysis:
   * __Finished on 10 Mar. 2014__
   * More details can be found in the [description page] (docs/FrontPage_Historical_forcing_ens.markdown)
   * PPP of air surface temperature [![] (figures/Historical_forcing_ens/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_Historical_forcing_ens.markdown)


--------------------------------------
* ### [AMIP run] (docs/FrontPage_normal_AMIP.markdown)

  * About this analysis:
   * __Finished on 13 Feb. 2016__
   * More details can be found in the [description page] (docs/FrontPage_normal_AMIP.markdown)
   * PPP of air surface temperature [![] (figures/normal_AMIP/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_normal_AMIP.markdown)

--------------------------------------
* ### [AMIP with 1 day atmospheric nudging] (docs/FrontPage_n01d_AMIP.markdown)

  * About this analysis:
   * __Finished on 12 Feb. 2016__
   * More details can be found in the [description page] (docs/FrontPage_n01d_AMIP.markdown)
   * PPP of air surface temperature [![] (figures/n01d_AMIP/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_n01d_AMIP.markdown)



--------------------------------------
* ### [AMIP with 2 day atmospheric nudging] (docs/FrontPage_n02d_AMIP.markdown)

  * About this analysis:
   * __Finished on ?? Feb. 2016__
   * More details can be found in the [description page] (docs/FrontPage_n02d_AMIP.markdown)
   * PPP of air surface temperature [![] (figures/n02d_AMIP/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_n02d_AMIP.markdown)


--------------------------------------
* ### [AMIP with 3 day atmospheric nudging] (docs/FrontPage_n03d_AMIP.markdown)

  * About this analysis:
   * __Finished on ?? Feb. 2016__
   * More details can be found in the [description page] (docs/FrontPage_n03d_AMIP.markdown)
   * PPP of air surface temperature [![] (figures/n03d_AMIP/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_n03d_AMIP.markdown)


--------------------------------------
* ### [AMIP with 5 day atmospheric nudging] (docs/FrontPage_n05d_AMIP.markdown)

  * About this analysis:
   * __Finished on 18 Feb. 2016__
   * More details can be found in the [description page] (docs/FrontPage_n05d_AMIP.markdown)
   * PPP of air surface temperature [![] (figures/n05d_AMIP/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_n05d_AMIP.markdown)


--------------------------------------
* ### [AMIP with 30 day atmospheric nudging] (docs/FrontPage_n30d_AMIP.markdown)

  * About this analysis:
   * __Finished on 17 Feb. 2016__
   * More details can be found in the [description page] (docs/FrontPage_n30d_AMIP.markdown)
   * PPP of air surface temperature [![] (figures/n30d_AMIP/PPP_atm/PPP_All_G04.cam2.h0.TS.png)](docs/FrontPage_n30d_AMIP.markdown)


------------------
## Do these before using the script ##

* Change the following head parameters in "cheeck_Prognostic_SNR"
  * DIR="the main output path"
  * tempDIR="where the temporary files are saved"
  * casePrefix="a general case name for all ensemble members" 
  * MEyear="a year which must be existed in all ensemble members. For determining the file prefixes" 
  * DataDIR="dir for the outputs"
  * ModelCompartments="ocn atm ice lnd"

* Before running the script (some known issues)
  * Make sure the data are well-prepared (no missing ensemble member or missing years)
  * micom outputs are compressed format, and cannot be processed by "cdo" because each file has different factor and offset. Better convert the outputs to F32 format before using this script.
  * The script of CAM automatically keeps the output of previous simulation, of which the exported variables are highly possible different with any new simulation. So those files (NorCPM_F19_tn21_mem??.cam2.h0.1979-12.nc in this case) should be removed in advance.   
  * MICOM & ICE outputs have to be regridded before ploting
  * Main scripts are sitting @norstore-osl:/norstore_osl/projects/NS9207K/earnest/Analysis/Prognostic-Potential-Predictabil

## Working Notes

  * should add a script to check PPP evolving (comparing spatial std in this case, and focus on SST only) (Note: fldvar/fldcorr is not helpful)
  * Should build a system to counter check the files
  * uploading the nc files of PPP as well??
  * Regional PPP (Nino 3.4; ATL3; SPG) (not urgent)
  * From PPP to evaluate prediction barrier/uncertainty - comparing to ENSO prediction barrier 
  * the ploting script has to be revised to get a better presentation, ie thiner colorbar, grids lines (not urgent)
  * MICOM hy output is missing in the figure list (also fail plot the figures?)
  * Trouble in presenting local maximum predictability!!! (HDF error).
  * Should add the sctipt for calculating PPP with observation
  * Should add a matlab script for ploting results of vertical section (mainly for MICOM)
  * add a global map of SST bias or RMSE
  * add Seasonal, 5-year pantad, decadal pantad results
  * Sometime the model might write different number of variables when restart files were generated. (error handling is necessary) 

