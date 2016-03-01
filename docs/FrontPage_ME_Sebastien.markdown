SST anomaly assimilated Ocean of NorESM (ME by Sebastien)
==========

  * The results (in global map) can be found in the following pages. Note that the results won't be shown if the PPP is smaller than __0.001__.

    * [__MICOM__] (ME_Sebastien/PPP_ocn.markdown), presented/total figures in ocn: __24__/1998 
    * [__CAM__] (ME_Sebastien/PPP_atm.markdown), presented/total figures in atm: __0__/0 
    * [__CLM__] (ME_Sebastien/PPP_lnd.markdown), presented/total figures in lnd: __223__/262 
    * [__CICE__] (ME_Sebastien/PPP_ice.markdown), presented/total figures in ice: __0__/0 

  * About this analysis:
    * __Finished on 5 Oct 2015__
    * Data is kept @Norstore-osl:/projects/NS9039K/shared/norcpm/cases/NorCPM/True_Obs-1980-2000/ME_Sebastien
    * We use [Norwegian Earth System Model (NorESM)] (http://folk.uib.no/ngfhd/EarthClim/) version F19_tn21 (approximately two degree atmosphere and two degree ocean)
    * Applying SST anomaly ([HadISST2](http://www.metoffice.gov.uk/hadobs/hadisst2/)) assimilation ([EnKF](http://enkf.nersc.no/), 30 members) on ocean compartment only
    * From __1980-2000__
    * Known issue:  
    * PPP cannot identify this skill loose because the noise is calculated base on the ensemble mean. 
  * PPP of SST ![] (../figures/ME_Sebastien/PPP_PPP-08.cam2.h0.SST.png)
  * PPP (against observation) of SST ![] (../figures/ME_Sebastien/Glabal2D_sst_NorCPM_F19_tn21_PP08.nc.png)
  * Prediction Skill of SST ![] (../figures/ME_Sebastien/Glabal2D_corr_ACC_SST_r008_08.nc.png)
  * Notes on this prediction:

