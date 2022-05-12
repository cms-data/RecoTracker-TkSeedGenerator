# RecoTracker-TkSeedGenerator

## DeepCore
This folder contains the data needed for DeepCoreSeedGenerator, the CNN-based seeding algorithm for JetCore trackin iteration.

More info: https://twiki.cern.ch/twiki/bin/view/CMSPublic/NNJetCoreAtCtD2019

File loaded: 
* _DeepCoreSeedGenerator_TrainedModel_barrel_2017.pb_ : training of DeepCore, performed in 2019 on 2017-condition MC (QCD_Pt_1800-2400). This training inclide only |eta|<1.4 (barrel)
* _DeepCoreSeedGenerator_TrainedModel_barrel_2022.pb_ : training of DeepCore, performed in 2022 on 2022-condition MC (QCD_Pt_1800-2400, specifically this dataset:"/RelValQCD_Pt_1800_2400_14/CMSSW_12_1_1-PU_121X_mcRun3_2021_realistic_v15-v1/"). This training for the barrel region.
