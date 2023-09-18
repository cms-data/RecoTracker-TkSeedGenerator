# RecoTracker-TkSeedGenerator

## DeepCore
This folder contains the data needed for DeepCoreSeedGenerator, the CNN-based seeding algorithm for JetCore trackin iteration.

More info (DeepCore2017): https://twiki.cern.ch/twiki/bin/view/CMSPublic/NNJetCoreAtCtD2019

More info (DeepCore2023): cms-sw/cmssw#42816 

  File loaded: 
* _DeepCoreSeedGenerator_TrainedModel_barrel_2017.pb_ : training of DeepCore, performed in 2019 on 2017-condition MC (QCD_Pt_1800-2400). This training inclide only |eta|<1.4 (barrel)
* _DeepCoreSeedGenerator_TrainedModel_barrel_2023.pb_ : training of DeepCore, performed in 2023 on 2021-condition MC and tested on 2023-condition (QCD_Pt_1800-2400). This training includes |eta|<1.4 (barrel) and other fixes and improvements from the previous model.
