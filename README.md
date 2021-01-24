# block_copolymers
Supplementary information for thesis chapter 6 - 'High-Throughput Virtual Screening of Block Co-polymers'.
----------------------------------------------------------------------------------------------------------
This repository contains the csv files to support the discussion in chapter 6 of my PhD thesis.

**The following csv files contain the xTB, (TD-)DFT and calibrated properties for the octamers and dodecamers in water and benzene:**

final_dodecamers_benz_df.csv\
final_dodecamers_h2o_df.csv\
final_octamers_benz_df.csv\
final_octamers_h2o_df.csv

**Columns description:**

'ID' - Oligomer ID (format: A_B_sequence)
'xTB_IP', 'xTB_EA', 'xTB_Opticalgap', 'xTB_oscillator_strength' - xTB calibrated properties\
'Smiles', 'A', 'B' - SMILES strings of the full oligomer, A monomer and B monomer\
'Sequence' - Oligomer sequence (octamer options: ['AABB', 'AAAABBBB', 'AB']; dodecamer options: ['AABB', 'AAAAAABBBBBB', 'AB', 'AAABBB'])\
'Monomer_no_A', 'Monomer_no_B' - Monomer numbers of unit A and B (see fig. 6.2 in thesis)\
'TDDFT_Opticalgap', 'DFT_IP', 'DFT_EA' - (TD-)DFT-calculated properties\
'IP_cal', 'EA_cal', 'Opticalgap_cal' - calibrated properties

-------------------------------------------------------------------------------------------------------------------------------------------

**The following csv files contain the xTB, (TD-)DFT, calibrated properties and open circuit voltage of the octamers possessing the properties
to make them suitable candidates as OPV donor materials:**

PN1_donor_OPV_driv_elec_options.csv\
PN1_donor_OPV_elec_options.csv\
PN1_donor_OPV_elec_options.csv\
PN1_donor_OPV_optical_options.csv\
expPC70BM_donor_OPV_driv_elec_options.csv\
expPC70BM_donor_OPV_elec_options.csv\
expPC70BM_donor_OPV_optical_options.csv\
expPCBM_donor_OPV_driv_elec_options.csv\
expPCBM_donor_OPV_elec_options.csv\
expPCBM_donor_OPV_optical_options.csv

**Columns description:**

'ID' - Oligomer ID (format: A_B_sequence)\
'xTB_IP', 'xTB_EA', 'xTB_Opticalgap', 'xTB_oscillator_strength' - xTB calibrated properties\
'Smiles', 'A', 'B' - SMILES strings of the full oligomer, A monomer and B monomer\
'Sequence' - Oligomer sequence (options: ['AABB', 'AAAABBBB', 'AB'])\
'Monomer_no_A', 'Monomer_no_B' - Monomer numbers of unit A and B (see fig. 6.2 in thesis)\
'Optical_gap', 'IP', 'EA' - (TD-)DFT-calculated properties\
'IP_cal', 'EA_cal', 'Opticalgap_cal' - calibrated properties\
'V_oc_{ACCEPTOR}' - Open circuit voltage of oligomer relative to given acceptor (PN1, PCBM or PC70BM)
