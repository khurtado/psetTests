# Test

# Setup CMSSW
I'm using: CMSSW_10_6_19_patch3
scram arch: slc7_amd64_gcc820 

# Then:
edm_pset_tweak.py --json test.json --input_pkl test.pkl --output_pkl test_output.pkl
