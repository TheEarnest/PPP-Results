Full field SST assimilated Ocean of NorESM (3rd version)
==========

  * The results (in global map) can be found in the following pages. Note that the results won't be shown if the PPP is smaller than __0.001__.

    * [__MICOM__] (FF_3rd_try/PPP_ocn.markdown), presented/total figures in ocn: __7__/114 
    * [__CAM__] (FF_3rd_try/PPP_atm.markdown), presented/total figures in atm: __82__/1099 
    * [__CLM__] (FF_3rd_try/PPP_lnd.markdown), presented/total figures in lnd: __146__/2808 
    * [__CICE__] (FF_3rd_try/PPP_ice.markdown), presented/total figures in ice: __8__/104 

  * About this analysis:
    * __Finished on 28 Jan. 2016__
    * Data is kept @Norstore-osl:/tape/NS9207K/earnest/NorCPM/FF_3rd_try_tar/
    * We use [Norwegian Earth System Model (NorESM)] (http://folk.uib.no/ngfhd/EarthClim/) version F19_tn21 (approximately two degree atmosphere and two degree ocean)
    * Applying full-field SST ([HadISST2](http://www.metoffice.gov.uk/hadobs/hadisst2/)) assimilation ([EnKF](http://enkf.nersc.no/), 30 members) on ocean compartment only
    * Applying atmosphere nudging above PBL
    * From __1970-1990__
    * Known issue:  
    * PPP cannot identify this skill loose because the noise is calculated base on the ensemble mean. 
  * PPP of SST ![] (../figures/FF_3rd_try/PPP_PPP-08.cam2.h0.SST.png)
  * PPP (against observation) of SST ![] (../figures/FF_3rd_try/Glabal2D_sst_NorCPM_F19_tn21_PP08.nc.png)
  * Prediction Skill of SST ![] (../figures/FF_3rd_try/Glabal2D_corr_ACC_SST_r008_08.nc.png)
  * Notes on this prediction:

